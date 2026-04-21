# Mathematics - 题目 3775

**ID**: 9cacabd280ec4d0a96f70200c7a9c71e
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
已知椭圆 $C$ ： $\frac {x{^{2}}}{a{^{2}}}+\frac {y{^{2}}}{b{^{2}}}=1\left ({a>b>0}\right )$ 的左､右焦点分别是 $F{{}_{1}}$ ､ $F{{}_{2}}$ ，上､右顶点分别是 $A$ ､ $B$ ，满足 $\angle F{{}_{1}}AF{{}_{2}}=120{}^\circ $ ， $\left |{AB}\right |=\sqrt {5}$ .​​​​​​​‌（1）求椭圆 $C$ 的标准方程；（2）与圆 $x{^{2}}+y{^{2}}=1$ 相切的直线 $l$ 交椭圆 $C$ 于 $P$ ､ $Q$ 两点，求 $\left |{PQ}\right |$ 的最大值及此时直线 $l$ 的斜率.

## 解答

1. （1）因为 ${\tan}\angle OAF{{}_{2}}=\frac {c}{b}$ ， $\left |{AB}\right |=\sqrt {a{^{2}}+b{^{2}}}$ ，
2. 得 ${\tan}60{}^\circ =\frac {c}{b}$ ， $\sqrt {a{^{2}}+b{^{2}}}=\sqrt {5}$ ，
3. 又 $a{^{2}}=b{^{2}}+c{^{2}}$ ，所以 $c=\sqrt {3}b$ ， $a{^{2}}=4b{^{2}}$ ， $5b{^{2}}=5$ ，解得 $b=1$ ， $a=2$ ，
4. 椭圆的标准方程为 $C$ ： $\frac {x{^{2}}}{4}+y{^{2}}=1$ ；
5. （2）法一：由题意知直线 $l$ 不能平行于 $x$ 轴，所以设为 $x=ty+m$ ，
6. 由已知得 $\left ({0,0}\right )$ 到 $x-ty-m=0$ 的距离为1，即 $\frac {\left |{m}\right |}{\sqrt {1+t{^{2}}}}=1$ ，
7. 所以 $m{^{2}}=t{^{2}}+1$ ，
8. 联立直线和椭圆得 ${\left({ty+m}\right)^{2}}+4y{^{2}}=4$ ，即 $\left ({t{^{2}}+4}\right )y{^{2}}+2tmy+m{^{2}}-4=0$ ，
9. 得 $\Delta ={\left({2tm}\right)^{2}}-4\left ({t{^{2}}+4}\right )\left ({m{^{2}}-4}\right )=-4\left ({4m{^{2}}-4t{^{2}}-16}\right )=16\left ({t{^{2}}-m{^{2}}+4}\right )$  $=16\times 3$ ，
10. 设 $P\left ({x{{}_{1}},y{{}_{1}}}\right )$ ， $Q\left ({x{{}_{2}},y{{}_{2}}}\right )$ ，则 $\left |{y{{}_{2}}-y{{}_{1}}}\right |=\frac {\sqrt {\Delta }}{t{^{2}}+4}=\frac {4\sqrt {3}}{t{^{2}}+4}$ ，
11. $\left |{PQ}\right |=\sqrt {1+t{^{2}}}\left |{y{{}_{2}}-y{{}_{1}}}\right |=\frac {4\sqrt {3}\sqrt {t{^{2}}+1}}{t{^{2}}+4}$ ，
12. 设 $\sqrt {1+t{^{2}}}=n$ ，则 $n\geqslant 1$ ， $\left |{PQ}\right |=\frac {4\sqrt {3}n}{n{^{2}}+3}=\frac {4\sqrt {3}}{n+\frac {3}{n}}\leqslant \frac {4\sqrt {3}}{2\sqrt {3}}=2$ ，
13. 当 $n=\frac {3}{n}$ ，即 $n=\sqrt {3}$ 时，得 $\left |{PQ}\right |{{}_{{\rm \max }}}=2$ ，
14. 此时 $t=\pm \sqrt {2}$ ，直线 $l$ 的斜率为 $\frac {1}{t}=\pm \frac {\sqrt {2}}{2}$ .
15. 法二：当直线 $l$ 垂直于 $x$ 轴时，为 $x=\pm 1$ ，代入椭圆得 $y=\pm \frac {\sqrt {3}}{2}$ ，得 $\left |{PQ}\right |=\sqrt {3}$ ①；
16. 当直线 $l$ 不垂直于 $x$ 轴时，设 $y=kx+m$ ，由题意知 $k\ne 0$ ，
17. 由已知得 $\left ({0,0}\right )$ 到 $kx-y+m=0$ 的距离为1，即 $\frac {\left |{m}\right |}{\sqrt {k{^{2}}+1}}=1$ ，
18. 所以 $m{^{2}}=k{^{2}}+1$ ，
19. 联立直线和椭圆得 $x{^{2}}+4{\left({kx+m}\right)^{2}}=4$ ，即 $\left ({4k{^{2}}+1}\right )x{^{2}}+8kmx+4m{^{2}}-4=0$ ，
20. 得 $Δ={\left({8km}\right)^{2}}-16\left ({4k{^{2}}+1}\right )\left ({m{^{2}}-1}\right )=-16\left ({-4k{^{2}}+m{^{2}}-1}\right )=16\times 3k{^{2}}$ ，
21. 设 $P\left ({x{{}_{1}},y{{}_{1}}}\right )$ ， $Q\left ({x{{}_{2}},y{{}_{2}}}\right )$ ，则 $\left |{x{{}_{2}}-x{{}_{1}}}\right |=\frac {\sqrt {Δ}}{4k{^{2}}+1}=\frac {4\sqrt {3}k}{4k{^{2}}+1}$ ，
22. $\left |{PQ}\right |=\sqrt {1+k{^{2}}}\left |{x{{}_{2}}-x{{}_{1}}}\right |=\frac {4\sqrt {3}k\sqrt {k{^{2}}+1}}{4k{^{2}}+1}$ ，
23. 设 $4k{^{2}}+1=n$ ，则 $n>1$ ，则 $\left |{PQ}\right |{^{2}}=\frac {3\times 4k{^{2}}\times 4\left ({k{^{2}}+1}\right )}{{\left({4k{^{2}}+1}\right)^{2}}}=\frac {3\left ({n-1}\right )\left ({n+3}\right )}{n{^{2}}}=3\left ({1+\frac {2}{n}-\frac {3}{n{^{2}}}}\right )$ ，
24. $\left |{PQ}\right |{^{2}}=3\left [-3\left ({\frac {1}{n{^{2}}}-\frac {2}{3}\cdot \frac {1}{n}}\right )+1\right ]=3\left [-3{\left({\frac {1}{n}-\frac {1}{3}}\right)^{2}}+\frac {4}{3}\right ]\leqslant 3\times \frac {4}{3}=4$ ，
25. 得 $\left |{PQ}\right |\leqslant 2$ ，结合①，得 $\left |{PQ}\right |{{}_{{\rm \max }}}=2$ ，
26. 此时 $n=3$ ，直线 $l$ 的斜率为 $k=\pm \frac {\sqrt {2}}{2}$ .

## 知识点

**中文**:
  - 圆锥曲线与直线、圆相结合的问题
  - 椭圆的标准方程及应用
  - 弦长面积问题
  - 范围最值问题

**English**:
  - Combined Problems with Lines and Circles
  - Standard Equation and Applications
  - Chord Length and Area Problems
  - Range and Extrema Problems

---
