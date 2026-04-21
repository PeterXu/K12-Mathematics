# Mathematics - 题目 3898

**ID**: 71a7cbfc0c544a4491d5252228c71303
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设曲线 $C:x{^{3}}-xy-y{^{3}}=1$ ．（1）求证： $C$ 关于直线 $y=-x$ 对称；​​​​​​​‌（2）求证： $C$ 是某个函数的图象；（3）试求所有实数 $k$ 与 $m$ ，使得直线 $y=kx+m$ 在 $C$ 的上方．

## 解答

1. （1）点 $\left ({m,n}\right )$ 关于 $y=-x$ 的对称点是 $\left ({-n,m}\right )$ ，
2. 若点 $\left ({m,n}\right )$ 在曲线 $C$ 上，即 $m{^{3}}-mn-n{^{3}}=1$ ，
3. 所以 ${\left({-n}\right)^{3}}-\left ({-n}\right )\left ({-m}\right )-{\left({-m}\right)^{3}}=-n{^{3}}-mn+m{^{3}}=1$ ，
4. 即 $\left ({-n,m}\right )$ 也在曲线 $C$ 上，故 $C$ 关于直线 $y=-x$ 对称．
5. （2）固定 $y$ ，设 $f\left ({x}\right )=x{^{3}}-xy-y{^{3}}-1$ ，则 $f^{′}{\left ({x}\right )}=3x{^{2}}-y$ ，
6. 当 $y\leqslant 0$ 时， $f^{′}{\left ({x}\right )}\geqslant 0$ 恒成立，至多只有一个零点；
7. 当 $y>0$ 时，令 $f^{′}{\left ({x}\right )}=0，x{{}_{1}}=-\sqrt {\frac {y}{3}}，x{{}_{2}}=\sqrt {\frac {y}{3}}$ ，设 $m=\sqrt {\frac {y}{3}}$ ，则 $x{{}_{1}}=-m，y=3m{^{2}}$ ，
8. $f(x)$ 在 $(-\infty ,-m)$ 上单调增，在 $(-m，3m{^{2}})$ 上单调减，在 $(3m{^{2}},+\infty )$ 上单调增，
9. 又 $f\left ({x{{}_{1}}}\right )=-m{^{3}}+m\cdot 3m{^{2}}-27m{^{6}}-1=2m{^{3}}-\left ({27m{^{6}}+1}\right )\leqslant 2m{^{3}}-2\cdot 3\sqrt {3}m{^{3}}<0$ ，
10. 所以 $f\left ({x}\right )=0$ 有且仅有一根，即对任意实数 $y$ ，关于 $x$ 的方程 $x{^{3}}-xy-y{^{3}}=1$ 只有一解，即对任意实数 $y$ ， $x{^{3}}-xy-y{^{3}}=1$ 只有一个 $x$ 与之对应，
11. 互换 $x,y$ 曲线方程不变，同理可知对任意实数 $x$ ， $x{^{3}}-xy-y{^{3}}=1$ 只有一个 $y$ 与之对应，所以 $C$ 是某个函数图象．
12. （3）引理：对于 $C$ 上任意一点 $\left ({p，q}\right )$ ，恒有 $q<p<q+2$ ．
13. 证明：设 $f\left ({x}\right )=x{^{3}}-qx-q{^{3}}-1$ ，则 $f\left ({q}\right )=-q{^{2}}-1<0$ ，
14. $f\left ({q+2}\right )={\left({q+2}\right)^{3}}-q\left ({q+2}\right )-q{^{3}}-1=5q{^{2}}+10q+7>0，$
15. 所以 $q<p<q+2$ ，所以 $C$ 的图象夹在 $y=x$ 与 $y=x-2$ 之间，故 $k=1$ ．
16. 联立 $\begin{cases}y=x+m\\x{^{3}}-xy-y{^{3}}=1\end{cases}$ ，可得 $\left ({3m+1}\right )x{^{2}}+\left ({3m{^{2}}+m}\right )x+m{^{3}}+1=0$ ，
17. 当 $m\ne -\frac {1}{3}$ 时， ${\rm{Δ}}={\left({3m{^{2}}+m}\right)^{2}}-4\left ({3m+1}\right )\left ({m{^{3}}+1}\right )=\left ({3m+1}\right )\left ({-m{^{3}}+m{^{2}}-4}\right )$ ，
18. 令 $g(m)=-m{^{3}}+m{^{2}}-4，g^{′}(m)=-3m{^{2}}+2m=0$ ，则 $m=0$ 或 $m=\frac {2}{3}$ ，
19. 又 $g(0)=-4<0,g(\frac {2}{3})=\frac {4}{27}-4<0,g(-\frac {1}{3})=\frac {4}{27}-4<0,g(-2)=8>0$ ，
20. 又 $m>-2$ ， $Δ<0$ ，所以 $m\in \left ({-\frac {1}{3},+∞}\right )$ ，此时方程无解，
21. 当 $m=-\frac {1}{3}$ 时，方程也无解，
22. 综上： $k=1，m\in \left [{-\frac {1}{3},+∞}\right )$ ．

## 知识点

**中文**:
  - 函数与方程的综合应用
  - 利用导数解决不等式恒成立问题
  - 利用导数研究函数的图象
  - 曲线与方程

**English**:
  - Comprehensive Application of Functions and Equations
  - Solving Universally True Inequalities
  - Studying Function Graphs
  - Curves and Equations

---
