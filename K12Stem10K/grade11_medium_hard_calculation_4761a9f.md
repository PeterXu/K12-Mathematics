# Mathematics - 题目 1421

**ID**: 4761a9f2aaa747479d25cf3c1105cd66
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知点 $A$ 、 $B$ 在抛物线 $C:x{^{2}}=2py\left ({p>0}\right )$ 上， $O$ 为原点，且 $\mathrm{△}OAB$ 是以 $AB$ 为斜边的等腰直角三角形，斜边长为 $4$ ．（1）求抛物线 $C$ 的方程；​​​​​​​‌（2）若点 $P$ 在圆 $Q:x{^{2}}+{\left({y+4}\right)^{2}}=4$ 上，过点 $P$ 分别作的直线 $l{{}_{1}}$ 、 $l{{}_{2}}$ 与抛物线 $C$ 相切于 $M$ 、 $N$ 两点，求 ${\tan}\angle MPN$ 的取值范围．

## 解答

1. （1）由题意知， $A$ 、 $B$ 两点关于 $y$ 轴对称，
2. 设点 $B$ 在 $y$ 轴右侧，则 $x{{}_{B}}=y{{}_{B}}=2$ ，即点 $\left ({2,2}\right )$ ，
3. 将点 $B$ 的坐标代入抛物线方程可得 $4p=4$ ，解得 $p=1$ ，
4. 故抛物线 $C$ 的方程为 $x{^{2}}=2y$ ；
5. （2）不妨设点 $N$ 、 $M$ 分别在第一、二象限，直线 $MN$ 的方程为 $y=mx+n$ ，
6. 设点 $M\left ({x{{}_{1}},\frac {x{{}_{1}^{2}}}{2}}\right )\left ({x{{}_{1}}<0}\right )$ 、 $N\left ({x{{}_{2}},\frac {x{{}_{2}^{2}}}{2}}\right )\left ({x{{}_{2}}>0}\right )$ ，
7. 联立 $\begin{cases}y=mx+n\\x{^{2}}=2y\end{cases}$ 得 $x{^{2}}-2mx-2n=0$ ， $Δ=4m{^{2}}+8n>0$ ，
8. 由韦达定理可得 $x{{}_{1}}+x{{}_{2}}=2m$ ， $x{{}_{1}}x{{}_{2}}=-2n$ ，
9. 由 $y=\frac {x{^{2}}}{2}$ 得 $y{^{\prime }}=x$ ，则直线 $PM$ 的斜率为 $k{{}_{1}}=x{{}_{1}}$ ，
10. 所以直线 $PM$ 的方程为 $y-\frac {x{{}_{1}^{2}}}{2}=x{{}_{1}}\left ({x-x{{}_{1}}}\right )$ ，即 $y=x{{}_{1}}x-\frac {x{{}_{1}^{2}}}{2}$ ，
11. 同理可知，直线 $PN$ 的斜率为 $k{{}_{2}}=x{{}_{2}}$ ，直线 $PN$ 的方程为 $y=x{{}_{2}}x-\frac {x{{}_{2}^{2}}}{2}$ ，
12. 联立直线 $PM$ 、 $PN$ 的方程得 $x{{}_{1}}x-\frac {x{{}_{1}^{2}}}{2}=x{{}_{2}}x-\frac {x{{}_{2}^{2}}}{2}$ ，
13. 解得 $x{{}_{P}}=\frac {x{{}_{1}}+x{{}_{2}}}{2}$ ，则 $y{{}_{P}}=x{{}_{2}}\cdot \frac {x{{}_{1}}+x{{}_{2}}}{2}-\frac {x{{}_{2}^{2}}}{2}=\frac {x{{}_{1}}x{{}_{2}}}{2}=-n$ ，故点 $P\left ({m,-n}\right )$ ，
14. 因为点 $P$ 在圆 $Q$ 上，所以 $m{^{2}}+{\left({-n+4}\right)^{2}}=4$ ，且 $2\leqslant n\leqslant 6$ ， $Δ=4m{^{2}}+8n>0$ 显然成立，
15. 过点 $P$ 作 $x$ 轴的垂线，垂足为点 $H$ ，
16. 
17. ${\tan}\angle MPH=-\frac {1}{k{{}_{1}}}=-\frac {1}{x{{}_{1}}}$ ， ${\tan}\angle NPH=\frac {1}{k{{}_{2}}}=\frac {1}{x{{}_{2}}}$ ，
18. ${\tan}\angle MPN={\tan}\left ({\angle MPH+\angle NPH}\right )=\frac {{\tan}\angle MPH+{\tan}\angle NPH}{1-{\tan}\angle MPH{\tan}\angle NPH}$
19. $=\frac {-\frac {1}{x{{}_{1}}}+\frac {1}{x{{}_{2}}}}{1+\frac {1}{x{{}_{1}}x{{}_{2}}}}=\frac {x{{}_{1}}-x{{}_{2}}}{x{{}_{1}}x{{}_{2}}+1}=-\frac {\sqrt {{\left({x{{}_{1}}+x{{}_{2}}}\right)^{2}}-4x{{}_{1}}x{{}_{2}}}}{x{{}_{1}}x{{}_{2}}+1}=-\frac {\sqrt {4m{^{2}}+8n}}{1-2n}=\frac {2\sqrt {-n{^{2}}+10n-12}}{2n-1}$ ，
20. 令 $t=2n-1$ ，因为 $2\leqslant n\leqslant 6$ ，则 $3\leqslant t\leqslant 11$ ， $\frac {1}{11}\leqslant \frac {1}{t}\leqslant \frac {1}{3}$ ，
21. 所以 ${\tan}\angle MPN=\frac {2\sqrt {-{\left({\frac {t+1}{2}}\right)^{2}}+10\cdot \frac {t+1}{2}-12}}{t}=\sqrt {-29\cdot \frac {1}{t{^{2}}}+18\cdot \frac {1}{t}-1}$ ，
22. 令 $s=\frac {1}{t}\in \left [\frac {1}{11},\frac {1}{3}\right ]$ ，则函数 $y=-29s{^{2}}+18s-1$ 在区间 $\left [\frac {1}{11},\frac {9}{29}\right ]$ 上单调递增，在 $\left [\frac {9}{29},\frac {1}{3}\right ]$ 上单调递减，
23. 故当 $\frac {1}{t}=\frac {1}{11}$ 时， ${\tan}\angle MPN$ 取最小值，且最小值为 $\frac {4\sqrt {3}}{11}$ ，
24. 当 $\frac {1}{t}=\frac {9}{29}$ 时， ${\tan}\angle MPN$ 取最大值，且最大值为 $\frac {2\sqrt {377}}{29}$ ，
25. 因此， ${\tan}\angle MPN$ 的取范围是 $\left [\frac {4\sqrt {3}}{11},\frac {2\sqrt {377}}{29}\right ]$ .

## 知识点

**中文**:
  - 圆锥曲线与直线、圆相结合的问题
  - 由抛物线的几何性质求方程
  - 范围最值问题
  - 角度问题

**English**:
  - Combined Problems with Lines and Circles
  - Finding Equation from Properties
  - Range and Extrema Problems
  - Angle Problems

---
