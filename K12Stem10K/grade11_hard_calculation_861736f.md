# Mathematics - 题目 3526

**ID**: 861736fb2e5c41a4a1a19ba911046085
**年级**: Grade 11
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )={\rm{s}}{\rm{i}}{\rm{n}}\mathrm{π}x$ 的所有正零点从小到大排列组成数列 $\left \{a{{}_{n}}\right \}$ ．(1)求 $\left \{a{{}_{n}}\right \}$ 的通项公式．(2)从 $\left \{a{{}_{n}}\right \}$ 的前 $n\left ({n\geqslant 2}\right )$ 项中随机选出不同的两项相乘，所得结果为偶数的概率记为 $P{{}_{n}}$ ，问：是否存在正整数 $M$ ，使得当 $n\geqslant M$ 时，恒有 $P{{}_{n}}<\frac {5}{6}$ ？若存在，求出 $M$ 的最小值；​​​​​​​‌若不存在，请说明理由．(3)若 $b{{}_{n}}=\frac {{\left({-1}\right)^{n+1}}}{a{{}_{n}}}$ ，且数列 $\left \{b{{}_{n}}\right \}$ 的前 $n$ 项和为 $S{{}_{n}}$ ，求证： $S{{}_{2n}}<{\rm{l}}{\rm{n}}2$ ．

## 解答

1. （1）因为 $f\left ({x}\right )={\rm{s}}{\rm{i}}{\rm{n}}{\rm{π}}x$ ，
2. 所以令 $f\left ({x}\right )=0$ ，可得 ${\rm{π}}x=k{\rm{π}}$ ， $k\in {\mathbf{Z}}$ ，解得 $x=k$ ， $k\in {\mathbf{Z}}$ ，
3. 则 $f\left ({x}\right )$ 的所有正零点可表示为 $x=n$ ， $n\in {\mathbf{N}}{^{{\rm{*}}}}$ ，
4. 故 $\left \{a{{}_{n}}\right \}$ 的通项公式为 $a{{}_{n}}=n$ ．
5. （2）从 $\left \{a{{}_{n}}\right \}$ 的前 $n$ 项中随机选出不同的两项相乘，共有 ${\rm{C}}{{}_{n}^{2}}=\frac {n\left ({n-1}\right )}{2}$ 种方法．
6. 设事件 $A=$ “不同的两项相乘，所得乘积为偶数”，则 ${\overline{A}}=$ “不同的两项相乘，所得乘积为奇数”，可知 $P\left ({{\overline{A}}}\right )=1-P{{}_{n}}$ ．
7. 当 $n$ 为偶数时，前 $n$ 项中有 $\frac {n}{2}$ 个奇数， $\frac {n}{2}$ 个偶数，要使所得乘积为奇数，则两项均为奇数，
8. 易得当 $n\mathrm{=}2$ 时， $P{{}_{2}}=1$ ，
9. 当 $n>2$ 时，即从 $\frac {n}{2}$ 个奇数中任取2个不同的奇数，共有 ${\rm{C}}{{}_{\frac {n}{2}}^{2}}$ 种方法，
10. 则 $1-P{{}_{n}}=\frac {{\rm{C}}{{}_{\frac {n}{2}}^{2}}}{{\rm{C}}{{}_{n}^{2}}}=\frac {\frac {n}{2}\left ({\frac {n}{2}-1}\right )}{n\left ({n-1}\right )}=\frac {n-2}{4\left ({n-1}\right )}$ ，所以 $P{{}_{n}}=1-\frac {n-2}{4\left ({n-1}\right )}$ ．
11. 由 $P{{}_{n}}<\frac {5}{6}$ ，可得 $\frac {n-2}{4\left ({n-1}\right )}>\frac {1}{6}$ ，解得 $n>4$ ，
12. 由 $n$ 为偶数，可得 $n\geqslant 6$ ．
13. 当 $n\left ({n\geqslant 3}\right )$ 为奇数时，前 $n$ 项中有 $\frac {n+1}{2}$ 个奇数， $\frac {n-1}{2}$ 个偶数，要使所得乘积为奇数，
14. 则两项均为奇数，即从 $\frac {n+1}{2}$ 个奇数中任取2个不同的奇数，共有 ${\rm{C}}{{}_{\frac {n+1}{2}}^{2}}$ 种方法，
15. 则 $1-P{{}_{n}}=\frac {{\rm{C}}{{}_{\frac {n+1}{2}}^{2}}}{{\rm{C}}{{}_{n}^{2}}}=\frac {\frac {n+1}{2}\left ({\frac {n+1}{2}-1}\right )}{n\left ({n-1}\right )}=\frac {n+1}{4n}$ ，所以 $P{{}_{n}}=1-\frac {n+1}{4n}$ ．
16. 由 $P{{}_{n}}<\frac {5}{6}$ ，可得 $\frac {n+1}{4n}>\frac {1}{6}$ ，
17. 由 $\frac {n+1}{4n}=\frac {1}{4}+\frac {1}{4n}>\frac {1}{6}$ ，可知该不等式对任意大于或等于3的奇数恒成立．
18. 综上，存在正整数 $M\geqslant 5$ ，当 $n\geqslant M$ 时，恒有 $P{{}_{n}}<\frac {5}{6}$ ．
19. 故 $M$ 的最小值为5．
20. （3）由（1）可知 $b{{}_{n}}=\frac {{\left({-1}\right)^{n+1}}}{a{{}_{n}}}=\frac {{\left({-1}\right)^{n+1}}}{n}$ ，
21. 则 $S{{}_{2n}}=1+\frac {1}{2}+\frac {1}{3}+\frac {1}{4}+\cdots +\frac {1}{2n-1}+\frac {1}{2n}-2\left ({\frac {1}{2}+\frac {1}{4}+\frac {1}{6}+\cdots +\frac {1}{2n}}\right )$
22. $=1+\frac {1}{2}+\frac {1}{3}+\frac {1}{4}+\cdots +\frac {1}{2n-1}+\frac {1}{2n}-\left ({1+\frac {1}{2}+\frac {1}{3}+\cdots +\frac {1}{n}}\right )$
23. $=\frac {1}{n+1}+\frac {1}{n+2}+\cdots +\frac {1}{2n-1}+\frac {1}{2n}$ ．
24. 令 $g\left ({x}\right )=1-\frac {1}{x}-{\rm{l}}{\rm{n}}x$ ，则 $g^{′}{\left ({x}\right )}=\frac {1}{x{^{2}}}-\frac {1}{x}=\frac {1-x}{x{^{2}}}<0$ 在 $\left ({1,+\infty }\right )$ 上恒成立，
25. 所以 $g\left ({x}\right )$ 在 $\left ({1,+\infty }\right )$ 上单调递减．
26. 所以 $g\left ({x}\right )<g\left ({1}\right )=0$ ，
27. 所以对任意的 $x>1$ ， $1-\frac {1}{x}-{\rm{l}}{\rm{n}}x<0$ ，即 $1-\frac {1}{x}<{\rm{l}}{\rm{n}}x$ 恒成立．
28. 令 $x=\frac {n+1}{n}$ ，则 $1-\frac {n}{n+1}<{\rm{l}}{\rm{n}}\frac {n+1}{n}$ ，即 $\frac {1}{n+1}<{\rm{l}}{\rm{n}}\left ({n+1}\right )-{\rm{l}}{\rm{n}}n$ ，
29. 所以有 $\frac {1}{n+1}<{\rm{l}}{\rm{n}}\left ({n+1}\right )-{\rm{l}}{\rm{n}}n,\frac {1}{n+2}<{\rm{l}}{\rm{n}}\left ({n+2}\right )-{\rm{l}}{\rm{n}}\left ({n+1}\right ),\cdots ,\frac {1}{2n}<{\rm{l}}{\rm{n}}\left ({2n}\right )-{\rm{l}}{\rm{n}}\left ({2n-1}\right )$ ．
30. 以上各式相加得 $\frac {1}{n+1}+\frac {1}{n+2}+\cdots +\frac {1}{2n}<{\rm{l}}{\rm{n}}\left ({n+1}\right )-{\rm{l}}{\rm{n}}n+{\rm{l}}{\rm{n}}\left ({n+2}\right )-{\rm{l}}{\rm{n}}\left ({n+1}\right )+\cdots +{\rm{l}}{\rm{n}}\left ({2n}\right )-$  ${\rm{l}}{\rm{n}}\left ({2n-1}\right )={\rm{l}}{\rm{n}}\left ({2n}\right )-{\rm{l}}{\rm{n}}n={\rm{l}}{\rm{n}}2$ ，
31. 故 $S{{}_{2n}}<{\rm{l}}{\rm{n}}2$ ，得证．

## 知识点

**中文**:
  - 数列与不等式的综合
  - 数列求和方法之分组转化法
  - 概率与计数原理相结合的应用题

**English**:
  - Sequences with Inequalities
  - Grouping Method
  - Combined Problems

---
