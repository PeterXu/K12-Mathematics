# Mathematics - 题目 815

**ID**: e8348f3812c54c0e99a03bfb508b9199
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设 $A\left ({x{{}_{A}}{\rm{,}}y{{}_{A}}}\right )$ ， $B\left ({x{{}_{B}},y{{}_{B}}}\right )$ 为平面直角坐标系上的两点，其中 $x{{}_{A}},y{{}_{A}},x{{}_{B}},y{{}_{B}}\in {\mathbf{Z}}$ ，令 $\Delta x=x{{}_{B}}-x{{}_{A}}$ ， $Δy=y{{}_{B}}-y{{}_{A}}$ ，若 $\left |{{\rm{Δ}}x}\right |+\left |{{\rm{Δ}}y}\right |=3$ ，且 $\left |{{\rm{Δ}}x}\right |,\left |{{\rm{Δ}}y}\right |\ne 0$ ，则称点B为点A的“相关点”，记作： $B=T\left ({A}\right )$ .​​​​​​​‌已知 $P{{}_{0}}\left ({x{{}_{0}}{\rm{,}}y{{}_{0}}}\right )$ （ $x{{}_{0}},y{{}_{0}}\in {\mathbf{Z}}$ ）为平面上一个定点，平面上点列 $\left \{P{{}_{i}}\right \}$ 满足： $P{{}_{i}}=T\left ({P{{}_{i-1}}}\right )$ ，且点 $P{{}_{i}}$ 的坐标为 $\left ({x{{}_{i}},y{{}_{i}}}\right )$ ，其中 $i=1,2,3,\cdot \cdot \cdot ,n$ .（1）请问：点 $P{{}_{0}}$ 的“相关点”有几个？判断这些“相关点”是否在同一个圆上，若在同一个圆上，写出圆的方程；若不在同一个圆上，说明理由；（2）求证：若 $P{{}_{0}}$ 与 $P{{}_{n}}$ 重合， $n$ 一定为偶数；（3）若 $P{{}_{0}}\left ({1,0}\right )$ ，且 $y{{}_{n}}=100$ ，记 $T=\sum \limits_{i=0}^{n}\mathop{x{{}_{i}}}$ ，求T的最大值.

## 解答

1. （1） $P{{}_{0}}$ 的“相关点”有 $8$ 个，且都在圆 ${\left({x-x{{}_{0}}}\right)^{2}}+{\left({y-y{{}_{0}}}\right)^{2}}=5$ 上，理由如下：
2. 由 $\left |{{\rm{Δ}}x}\right |+\left |{{\rm{Δ}}y}\right |=3$ ，且 $\left |{{\rm{Δ}}x}\right |,\left |{{\rm{Δ}}y}\right |\ne 0$ ， $x{{}_{A}},y{{}_{A}},x{{}_{B}},y{{}_{B}}\in {\mathbf{Z}}$ ，
3. 则 $\left |{{\rm{Δ}}x}\right |=1$ ， $\left |{{\rm{Δ}}y}\right |=2$ 或 $\left |{{\rm{Δ}}x}\right |=2$ ， $\left |{{\rm{Δ}}y}\right |=1$ ，故 $P{{}_{0}}$ 的“相关点”有 $8$ 个，
4. 又因为 ${\left({{\rm{Δ}}x}\right)^{2}}+{\left({{\rm{Δ}}y}\right)^{2}}=5$ ，即有 ${\left({x-x{{}_{0}}}\right)^{2}}+{\left({y-y{{}_{0}}}\right)^{2}}=5$ ，
5. 故这些“相关点”在圆 ${\left({x-x{{}_{0}}}\right)^{2}}+{\left({y-y{{}_{0}}}\right)^{2}}=5$ 上；
6. （2）若 $P{{}_{0}}$ 与 $P{{}_{n}}$ 重合，则 $x{{}_{n}}=x{{}_{0}}$ 、 $y{{}_{n}}=y{{}_{0}}$ ，
7. 令 $\Delta x{{}_{i}}=x{{}_{i}}-x{{}_{i-1}}$ 、 $\Delta y{{}_{i}}=y{{}_{i}}-y{{}_{i-1}}$ ，
8. 则 $\sum \limits_{1}^{n}\mathop{\Delta x{{}_{i}}}=0$ ， $\sum \limits_{1}^{n}\mathop{\Delta y{{}_{i}}}=0$ ，
9. 则 $\sum\limits_{1}^{n}\mathop{}{\rm{Δ}}x{{}_{i}}+\sum\limits_{1}^{n}\mathop{}{\rm{Δ}}y{{}_{i}}=\sum\limits_{1}^{n}\mathop{}\left ({{\rm{Δ}}x{{}_{i}}+{\rm{Δ}}y{{}_{i}}}\right )=0$ ，
10. 由（1）知 $\left |{{\rm{Δ}}x{{}_{i}}}\right |=1$ ， $\left |{{\rm{Δ}}y{{}_{i}}}\right |=2$ 或 $\left |{{\rm{Δ}}x{{}_{i}}}\right |=2$ ， $\left |{{\rm{Δ}}y{{}_{i}}}\right |=1$ ，
11. 则 $\Delta x{{}_{i}}+\Delta y{{}_{i}}$ 必为奇数，即有 $n$ 个奇数相加为 $0$ ，
12. 因为奇数个奇数的和为奇数，故 $n$ 必为偶数；
13. （3）由题意可得 $y{{}_{n}}=\left ({y{{}_{n}}-y{{}_{n-1}}}\right )+\left ({y{{}_{n-1}}-y{{}_{n-2}}}\right )+\cdots +\left ({y{{}_{1}}-y{{}_{0}}}\right )+y{{}_{0}}=100$ ，
14. 又 $\left |{{\rm{Δ}}y{{}_{i}}}\right |=2$ 或 $\left |{{\rm{Δ}}y{{}_{i}}}\right |=1$ ，则 $y{{}_{n}}-y{{}_{n-1}}\leqslant 2$ ， $y{{}_{n-1}}-y{{}_{n-2}}\leqslant 2$ ， $\cdots $ ， $y{{}_{1}}-y{{}_{0}}\leqslant 2$ ，
15. 则 $y{{}_{n}}\leqslant 2n+y{{}_{0}}=2n$ ，故 $n\geqslant 50$ ，
16. $T=\sum\limits_{i=0}^{n}\mathop{}x{{}_{i}}=x{{}_{0}}+x{{}_{1}}+\cdots +x{{}_{n}}=1+\left ({1+{\rm{Δ}}x{{}_{1}}}\right )+\left ({1+{\rm{Δ}}x{{}_{1}}+{\rm{Δ}}x{{}_{2}}}\right )+\cdots +\left ({1+{\rm{Δ}}x{{}_{1}}+{\rm{Δ}}x{{}_{2}}+\cdots +{\rm{Δ}}x{{}_{n}}}\right )$
17. $=n+1+n{\rm{Δ}}x{{}_{1}}+\left ({n-1}\right ){\rm{Δ}}x{{}_{2}}+\cdots +{\rm{Δ}}x{{}_{n}}$ ，
18. 由 $\left |{{\rm{Δ}}x{{}_{i}}}\right |=1$ ， $\left |{{\rm{Δ}}y{{}_{i}}}\right |=2$ 或 $\left |{{\rm{Δ}}x{{}_{i}}}\right |=2$ ， $\left |{{\rm{Δ}}y{{}_{i}}}\right |=1$ ，
19. 则 $\Delta x{{}_{i}}=2$ 的个数越多，则 $T$ 的值越大，
20. 而且在序列 $\Delta x{{}_{1}},\Delta x{{}_{2}},\cdots ,\Delta x{{}_{n}}$ 中，数字 $2$ 的位置越靠前，则相应的 $T$ 的值越大，
21. 则 $\left |{{\rm{Δ}}y{{}_{i}}}\right |=1$ 的次数最多时， $\Delta x{{}_{i}}$ 取 $2$ 的次数才能最多，相应的 $T$ 的值最大；
22. ①当 $50\leqslant n<100$ 时，令 $\Delta y{{}_{p}}=1$ ， $p\leqslant 2n-100$ ，
23. ${\rm{Δ}}y{{}_{q}}=2$ ， $2n-100<q\leqslant n$ ， $p,q\in {\mathbf{N}}$ ，
24. 则相应的取 $\Delta x{{}_{p}}=2$ ， $p\leqslant 2n-100$ ， $\Delta x{{}_{q}}=1$ ， $2n-100<q\leqslant n$ ，
25. 则 $T=n+1+2\left [n+\left ({n-1}\right )+\cdots +\left ({101-n}\right )\right ]+\left [\left ({100-n}\right )+\left ({99-n}\right )+\cdots +2+1\right ]$
26. $=n+1+2\times \frac {\left ({n+101-n}\right )\cdot \left ({2n-100}\right )}{2}+\frac {\left ({100-n+1}\right )\cdot \left ({100-n}\right )}{2}$
27. $=\frac {1}{2}\left ({n{^{2}}+205n-10098}\right )$ ；
28. ② ${\rm （\mathit{i}）}n\geqslant 100$ 且 $n$ 为偶数时，设 $n=2k$ ，此时 $\Delta y{{}_{i}}$ 可取 $k+50$ 个 $1$ ， $k-50$ 个 $-1$ ，
29. 则所有的 $\left |{{\rm{Δ}}x{{}_{i}}}\right |$ 都为 $2$ ，为使 $T$ 最大，则所有 $Δx{{}_{i}}$ 都取 $2$ ，
30. 且 $T=n+1+2\left [n+\left ({n-1}\right )+\cdots +2+1\right ]=n+1+2\times \frac {\left ({n+1}\right )n}{2}=n{^{2}}+2n+1$ ；
31. ${\rm （\mathit{ii}）}$ 当 $n\geqslant 100$ 且 $n$ 为奇数时，设 $n=2k+1$ ，
32. 令 $\Delta y{{}_{n}}=2$ ，则其余的 $\Delta y{{}_{i}}$ 中取 $k+49$ 个 $1$ ， $k-49$ 个 $-1$ ，
33. 则相应的 $\Delta x{{}_{n}}=1$ ，其余的 $\Delta x{{}_{i}}=2$ 时， $T$ 最大，
34. 此时 $T=n+1+2\left [n+\left ({n-1}\right )+\cdots +2\right ]+1=n+2+2\times \frac {\left ({n+2}\right )\cdot \left ({n-1}\right )}{2}=n{^{2}}+2n$ ；
35. 综上所述： $T{{}_{{\rm \max }}}=\begin{cases}\frac {1}{2}\left ({n{^{2}}+205n-10098}\right ),50\leqslant n<100\\n{^{2}}+2n+1,n\geqslant 100且n为偶数\\n{^{2}}+2n,n\geqslant 100且n为奇数\end{cases}$ .

## 知识点

**中文**:
  - 平面向量的新定义问题

**English**:
  - New Definition Problems

---
