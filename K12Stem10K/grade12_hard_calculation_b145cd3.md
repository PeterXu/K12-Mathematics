# Mathematics - 题目 1662

**ID**: b145cd353d014f25a21b6b9f1221f13d
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
若对于函数 $y=f\left ({x}\right )$ ，存在直线 $y=kx+b$ ，使得方程 $f\left ({x}\right )=kx+b$ 有 $m$ 个解 $x{{}_{1}}$ ， $x{{}_{2}}$ ， $\cdots $ ， $x{{}_{m}}$ ，且 $k=f^{′}{\left ({x{{}_{1}}}\right )}=f^{′}{\left ({x{{}_{2}}}\right )}=\cdot \cdot \cdot =f^{′}{\left ({x{{}_{m}}}\right )}$ ，则称直线 $y=kx+b$ 为函数 $y=f\left ({x}\right )$ 的 $m$ 阶临界直线，若 $m$ 可趋近于无穷大，则称直线 $y=kx+b$ 为函数 $y=f\left ({x}\right )$ 的无限阶临界直线.​​​​​​​‌（1）判断函数 $f\left ({x}\right )=x{^{2}}-4\left |{x}\right |$ ， $x\in {\mathbf{R}}$ 的奇偶性并直接写出它的一条 $2$ 阶临界直线方程；（2）若 $f\left ({x}\right )={\rm{e}}{^{x}}{\ln}x$ ， $x\in \left [{1,+\mathrm{∞}}\right )$ ，判断函数 $y=f\left ({x}\right )$ 是否存在 $2$ 阶临界直线，并说明理由；（3）已知函数 $f\left ({x}\right )=\begin{cases}x{^{2}}+4{\cos}x,x\in \left [{0,1}\right )\\f\left ({x-1}\right )+4{\cos}1-3,x\in \left [{n,n+1}\right ),n\in {\mathbf{N}}{^{*}}\end{cases}$ .证明：函数 $y=f\left ({x}\right )$ 存在无限阶临界直线.

## 解答

1. （1）令 $f\left ({x}\right )=x{^{2}}-4\left |{x}\right |$ ，其中 $x\in {\mathbf{R}}$ ，则 $f\left ({-x}\right )={\left({-x}\right)^{2}}-4\left |{-x}\right |=x{^{2}}-4\left |{x}\right |=f\left ({x}\right )$ ，
2. 所以，函数 $f\left ({x}\right )=x{^{2}}-4\left |{x}\right |$ 为偶函数，
3. $f\left ({x}\right )={\left({\left |{x}\right |-2}\right)^{2}}-4$ ，故当 $x=\pm 2$ 时，函数 $f\left ({x}\right )$ 取最小值，
4. 当 $x<0$ 时， $f\left ({x}\right )=x{^{2}}+4x$ ， $f^{′}{\left ({x}\right )}=2x+4$ ， $f^{′}{\left ({-2}\right )}=0$ ，
5. 当 $x>0$ 时， $f\left ({x}\right )=x{^{2}}-4x$ ， $f^{′}{\left ({x}\right )}=2x-4$ ， $f^{′}{\left ({2}\right )}=0$ ，
6. 所以函数 $f\left ({x}\right )$ 在点 $\left ({-2,-4}\right )$ 处的切线方程为 $y=-4$ ，在点 $\left ({2,-4}\right )$ 处的切线方程为 $y=-4$ ，
7. 如下图所示：
8. 
9. 函数 $f\left ({x}\right )=x{^{2}}-4\left |{x}\right |$ 的一条 $2$ 阶临界直线方程为 $y=-4$ .
10. （2）若 $f\left ({x}\right )={\rm{e}}{^{x}}{\ln}x$ ， $f^{′}{\left ({x}\right )}={\rm{e}}{^{x}}\left ({{\ln}x+\frac {1}{x}}\right )$ ，
11. 令 $g\left ({x}\right )={\rm{e}}{^{x}}\left ({{\ln}x+\frac {1}{x}}\right )$ ， $g^{′}{\left ({x}\right )}={\rm{e}}{^{x}}\left ({{\ln}x+\frac {2}{x}-\frac {1}{x{^{2}}}}\right )$ ，
12. 令 $h\left ({x}\right )={\ln}x+\frac {2}{x}-\frac {1}{x{^{2}}}$ ， $h^{′}{\left ({x}\right )}=\frac {x{^{2}}-2x+2}{x{^{3}}}>0$ ，
13. 所以 $g^{′}{\left ({x}\right )}$ 在 $\left [{1,+\infty }\right )$ 上单调递增，所以 $g^{′}{\left ({x}\right )}{{}_{{\rm \min }}}=g^{′}{\left ({1}\right )}={\rm{e}}>0$ ，
14. 所以 $f^{′}{\left ({x}\right )}$ 在 $\left [{1,+\infty }\right )$ 上单调递增，所以不存在 $x{{}_{1}}$ ， $x{{}_{2}}\in \left [{1,+\infty }\right )$ ，使得 $f^{′}{\left ({x{{}_{1}}}\right )}=f^{′}{\left ({x{{}_{2}}}\right )}$ ，
15. 综上可知函数 $y=f\left ({x}\right )$ 不存在 $2$ 阶临界直线.
16. （3）当 $x\in \left [{0,1}\right )$ 时， $f^{′}{\left ({x}\right )}=2\left ({x-2\sin x}\right )$ ，
17. 令 $g\left ({x}\right )=x-2\sin x$ ， $g^{′}{\left ({x}\right )}=1-2{\cos}x<1-2{\cos}1<0$ ，
18. 所以 $f^{′}{\left ({x}\right )}$ 在 $\left [{0,1}\right )$ 上单调递减，
19. 因为 $f^{′}{\left ({0}\right )}=0$ ， $f^{′}{\left ({1}\right )}=2-4\sin 1$ ，所以当 $x\in \left [{0,1}\right )$ 时， $f^{′}{\left ({x}\right )}\in \left ({2-4\sin 1,0}\right ]$ ，
20. 因为 $4{\cos}1-3<4\times \frac {\sqrt {2}}{2}-3<0$ ，
21. $4{\cos}1-3-\left ({2-4\sin 1}\right )=4\left ({\sin 1+{\cos}1}\right )-5=4\sqrt {2}\sin \left ({\frac {{\rm{π}}}{4}+1}\right )-5$ ， $\frac {{\rm{π}}}{4}+1\in \left ({\frac {{\rm{π}}}{2},\frac {{\rm{π}}}{4}+\frac {{\rm{π}}}{3}}\right )$ ，
22. 所以 $4\sqrt {2}\sin \left ({\frac {{\rm{π}}}{4}+1}\right )-5>4\sqrt {2}\times \frac {\sqrt {2}}{4}\left ({1+\sqrt {3}}\right )-5>0$ ，
23. 则存在 $x{{}_{0}}\in \left [{0,1}\right )$ ，使 $f^{′}{\left ({x{{}_{0}}}\right )}=4{\cos}1-3$ ，
24. 当 $x\in \left [{n,n+1}\right )$ 时， $n\in {\mathbf{N}}{^{*}}$ ， $f\left ({x}\right )=f\left ({x-1}\right )+4{\cos}1-3$ ，所以 $f^{′}{\left ({x}\right )}=f^{′}{\left ({x-1}\right )}$ ，
25. 所以 $f^{′}{\left ({x{{}_{0}}}\right )}=f^{′}{\left ({x{{}_{0}}+1}\right )}=\cdot \cdot \cdot =f^{′}{\left ({x{{}_{0}}+n}\right )}=\cdot \cdot \cdot $ ，
26. 因为函数 $f\left ({x}\right )$ 在 $\left ({x{{}_{0}},f\left ({x{{}_{0}}}\right )}\right )$ 处的切线方程为 $y=f^{′}{\left ({x{{}_{0}}}\right )}\left ({x-x{{}_{0}}}\right )+f\left ({x{{}_{0}}}\right )$ ，
27. 函数 $f\left ({x}\right )$ 在 $\left ({x{{}_{0}}+n,f\left ({x{{}_{0}}+n}\right )}\right )$ 处的切线方程 $y=f^{′}{\left ({x{{}_{0}}+n}\right )}\left ({x-x{{}_{0}}-n}\right )+f\left ({x{{}_{0}}+n}\right )$ ，
28. 又因为 $f\left ({x{{}_{0}}+n}\right )=f\left ({x{{}_{0}}}\right )+\left ({4{\cos}1-3}\right )n$ ，
29. 所以 $f^{′}{\left ({x{{}_{0}}+n}\right )}\left ({x-x{{}_{0}}-n}\right )+f\left ({x{{}_{0}}+n}\right )=f^{′}{\left ({x{{}_{0}}}\right )}\left ({x-x{{}_{0}}}\right )-nf^{′}{\left ({x{{}_{0}}}\right )}+f\left ({x{{}_{0}}+n}\right )$
30. $=f^{′}{\left ({x{{}_{0}}}\right )}\left ({x-x{{}_{0}}}\right )-\left ({4{\cos}1-3}\right )n+f\left ({x{{}_{0}}}\right )+\left ({4{\cos}1-3}\right )n=f^{′}{\left ({x{{}_{0}}}\right )}\left ({x-x{{}_{0}}}\right )+f\left ({x{{}_{0}}}\right )$ ，
31. 所以 $f^{′}{\left ({x{{}_{0}}+n}\right )}\left ({x-x{{}_{0}}-n}\right )+f\left ({x{{}_{0}}+n}\right )=f^{′}{\left ({x{{}_{0}}}\right )}\left ({x-x{{}_{0}}}\right )+f\left ({x{{}_{0}}}\right )$ ，
32. 所以直线 $y=f^{′}{\left ({x{{}_{0}}+n}\right )}\left ({x-x{{}_{0}}-n}\right )+f\left ({x{{}_{0}}+n}\right )$ 与直线 $y=f^{′}{\left ({x{{}_{0}}}\right )}\left ({x-x{{}_{0}}}\right )+f\left ({x{{}_{0}}}\right )$ 重合，
33. 则 $x{{}_{1}}$ ， $x{{}_{2}}$ ， $\cdots $ ， $x{{}_{n}}$ ， $\cdots $ 为方程 $f\left ({x}\right )=f^{′}{\left ({x{{}_{0}}}\right )}\left ({x-x{{}_{0}}}\right )+f\left ({x{{}_{0}}}\right )$ 的解，
34. 且 $k=f^{′}{\left ({x{{}_{0}}}\right )}=f^{′}{\left ({x{{}_{0}}+1}\right )}=\cdot \cdot \cdot =f^{′}{\left ({x{{}_{0}}+n}\right )}=\cdot \cdot \cdot $ ，
35. 又因为 $n$ 可趋近于无穷大，所以存在直线 $y=f^{′}{\left ({x{{}_{0}}}\right )}\left ({x-x{{}_{0}}}\right )+f\left ({x{{}_{0}}}\right )$ 为函数 $y=f\left ({x}\right )$ 的无限阶临界直线.

## 知识点

**中文**:
  - 利用导数研究函数的单调性与单调区间
  - 导数几何意义的应用
  - 利用导数解决新定义问题

**English**:
  - Monotonicity and Monotonic Intervals
  - Applications of Geometric Meaning of Derivatives
  - Solving New Definition Problems

---
