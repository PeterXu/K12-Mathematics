# Mathematics - 题目 2850

**ID**: c46a30b77d63492e93938a069ef81b5d
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知椭圆 $C:\frac {x{^{2}}}{a{^{2}}}+\frac {y{^{2}}}{b{^{2}}}=1\left ({a>b>0}\right )$ 过点 $P\left ({2,\sqrt {2}}\right )$ ，短轴长为 $4$ .​​​​​​​‌（1）求椭圆 $C$ 的方程；（2）已知点 $H\left ({m,0}\right )$ ，若椭圆 $C$ 上的点到 $H$ 的距离的最小值是 $\sqrt {3}$ ，求正实数 $m$ 的值；（3）椭圆 $C$ 与 $y$ 轴的交点为 $A$ 、 $B$ （点 $A$ 位于点 $B$ 的上方），直线 $l:y=kx+4$ 与椭圆 $C$ 交于不同的两点 $M$ 、 $N$ .设直线 $AN$ 与直线 $BM$ 相交于点 $G$ ，求 $\left |{GA}\right |+\left |{GP}\right |$ 的最小值.

## 解答

1. （1）由题意得椭圆过点 $P\left ({2,\sqrt {2}}\right )$ ，且短轴长为 $4$ ，
2. 可得 $\begin{cases}\frac {4}{a{^{2}}}+\frac {2}{b{^{2}}}=1\\2b=4\end{cases}$ ，解得 $\begin{cases}b=2\\a=2\sqrt {2}\end{cases}$ ，
3. 可得椭圆 $C$ 的方程为 $\frac {x{^{2}}}{8}+\frac {y{^{2}}}{4}=1$ ；
4. （2）设椭圆上任一点为 $Q\left ({x{{}_{0}},y{{}_{0}}}\right )$ ，故 $\frac {x{{}_{0}^{2}}}{8}+\frac {y{{}_{0}^{2}}}{4}=1$ ，则 $y{{}_{0}^{2}}=4-\frac {x{{}_{0}^{2}}}{2}$ ，
5. 则点 $Q$ 到 $H$ 的距离为 $d=\sqrt {(x{{}_{0}}-m){^{2}}+y{{}_{0}}{^{2}}}=\sqrt {\frac {1}{2}x{{}_{0}}{^{2}}-2mx{{}_{0}}+m{^{2}}+4}=\sqrt {\frac {1}{2}{\left({x{{}_{0}}-2m}\right)^{2}}-m{^{2}}+4}$ ，
6. 由于 $Q\left ({x{{}_{0}},y{{}_{0}}}\right )$ 在椭圆上，所以 $x{{}_{0}}\in \left [-2\sqrt {2},2\sqrt {2}\right ]$ ，
7. 令二次函数 $y=\frac {1}{2}{\left({x{{}_{0}}-2m}\right)^{2}}-m{^{2}}+4$ ，其对称轴为 $x{{}_{0}}=2m$ ，
8. 而 $m>0$ ，当 $2m<2\sqrt {2}$ 时，解得 $0<m<\sqrt {2}$ ，
9. 此时 $\sqrt {-m{^{2}}+4}\mathrm{=}\sqrt {3}$ ，解得 $m=1$ 或  $m=-1$ （舍），
10. 当 $2m\mathrm{\geqslant }2\sqrt {2}$ 时，解得 $m\geqslant \sqrt {2}$ ，
11. 此时二次函数 $y=\frac {1}{2}{\left({x{{}_{0}}-2m}\right)^{2}}-m{^{2}}+4$ 在 $\left [-2\sqrt {2},2\sqrt {2}\right ]$ 上单调递减，
12. 则当 $x{{}_{0}}=2\sqrt {2}$ 时，二次函数取得最小值，
13. 此时 $\sqrt {\frac {1}{2}{\left({2\sqrt {2}-2m}\right)^{2}}-m{^{2}}+4}\mathrm{=}\sqrt {3}$ ，
14. 解得 $m=2\sqrt {2}+\sqrt {3}$ 或 $m=2\sqrt {2}-\sqrt {3}$ （舍）；
15. 综上， $m=1$ 或 $m=2\sqrt {2}+\sqrt {3}$ ；
16. （3）设点 $N\left ({x{{}_{1}},y{{}_{1}}}\right )$ 、 $M\left ({x{{}_{2}},y{{}_{2}}}\right )\left ({y{{}_{1}}\ne \pm 2,y{{}_{2}}\ne \pm 2}\right )$ ，
17. 直线 $l$ 与椭圆 $C$ 的方程联立消去 $y$ 整理得 $\left ({1+2k{^{2}}}\right )x{^{2}}+16kx+24=0$ ，
18. 由 ${\rm{Δ}}={\left({16k}\right)^{2}}-4\times 24\left ({1+2k{^{2}}}\right )>0\Rightarrow k{^{2}}>\frac {3}{2}$ ，
19. 且 $x{{}_{1}}+x{{}_{2}}=-\frac {16k}{1+2k{^{2}}},x{{}_{1}}\cdot x{{}_{2}}=\frac {24}{1+2k{^{2}}}$ ，所以 $x{{}_{1}}+x{{}_{2}}=-\frac {2}{3}kx{{}_{1}}\cdot x{{}_{2}}$ ，
20. 由于 $N\left ({x{{}_{1}},y{{}_{1}}}\right )$ 在椭圆 $\frac {x{^{2}}}{8}+\frac {y{^{2}}}{4}=1$ 上，则 $\frac {x{{}_{1}^{2}}}{8}+\frac {y{{}_{1}^{2}}}{4}=1$ ，
21. 所以 $\left ({2-y{{}_{1}}}\right )\left ({2+y{{}_{1}}}\right )=\frac {x{{}_{1}^{2}}}{2}$ ，则 $y{{}_{1}}-2=-\frac {x{{}_{1}^{2}}}{2\left ({y{{}_{1}}+2}\right )}$ ，
22. 易知 $A\left ({0,2}\right )$ 、 $B\left ({0,-2}\right )$ ，则直线 $AN$ 的方程为 $y-2=\frac {y{{}_{1}}-2}{x{{}_{1}}}x$ ，
23. 直线 $BM$ 的方程为 $y+2=\frac {y{{}_{2}}+2}{x{{}_{2}}}x$ ，
24. 两式作商得 $\frac {y-2}{y+2}=\frac {\left ({y{{}_{1}}-2}\right )\cdot x{{}_{2}}}{\left ({y{{}_{2}}+2}\right )\cdot x{{}_{1}}}=-\frac {x{{}_{1}^{2}}\cdot x{{}_{2}}}{2\left ({y{{}_{2}}+2}\right )\left ({y{{}_{1}}+2}\right )\cdot x{{}_{1}}}=-\frac {x{{}_{1}}\cdot x{{}_{2}}}{2\left ({kx{{}_{1}}+6}\right )\left ({kx{{}_{2}}+6}\right )}$
25. $\hspace{-0.5em}\begin{array}{l}=-\frac {x{{}_{1}}\cdot x{{}_{2}}}{2k{^{2}}x{{}_{1}}\cdot x{{}_{2}}+12k\left ({x{{}_{1}}+x{{}_{2}}}\right )+72}=-\frac {\frac {24}{1+2k{^{2}}}}{2k{^{2}}\cdot \frac {24}{1+2k{^{2}}}+12k\cdot \frac {-16k}{1+2k{^{2}}}+72}\\=-\frac {24}{48k{^{2}}-192k{^{2}}+72+144k{^{2}}}=-\frac {1}{3}\end{array}\hspace{-0.5em}$
26. 解得 $y=1$ ，故 $G$ 在定直线 $y=1$ 上，
27. 
28. 由图可知，点 $A$ 、 $P$ 都在直线 $y=1$ 的上方，点 $A$ 关于直线 $y=1$ 的对称点为原点 $O$ ，
29. 由对称性知 $\left |{GA}\right |=\left |{GO}\right |$ ，所以 $\left |{GA}\right |+\left |{GP}\right |=\left |{GO}\right |+\left |{GP}\right |\geqslant \left |{OP}\right |=\sqrt {2{^{2}}+(\sqrt {2}){^{2}}}=\sqrt {6}$ ，
30. 当且仅当 $G$ 为线段 $OP$ 与直线 $y=1$ 的交点时，即点 $G$ 的坐标为 $\left ({\sqrt {2},1}\right )$ 时等号成立，
31. 故 $\left |{GA}\right |+\left |{GP}\right |$ 的最小值为 $\sqrt {6}$ .

## 知识点

**中文**:
  - 由椭圆的几何性质求方程
  - 直线与椭圆的位置关系
  - 范围最值问题

**English**:
  - Finding Equation from Properties
  - Line-Ellipse Relationship
  - Range and Extrema Problems

---
