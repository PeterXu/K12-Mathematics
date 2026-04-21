# Mathematics - 题目 3514

**ID**: 5fcb97b7e7584d58bbe74ce9e47cfd9e
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知平面上一动点 $P$ 到定点 $F\left ({\frac {1}{2},0}\right )$ 的距离比到定直线 $x=-2023$ 的距离小 $\frac {4045}{2}$ ，记动点 $P$ 的轨迹为曲线 $C$ .​​​​​​​‌(1)求 $C$ 的方程；(2)点 $A\left ({2,1}\right ),M,N$ 为 $C$ 上的两个动点，若 $M,N,B$ 恰好为平行四边形 $MANB$ 的其中三个顶点，且该平行四边形对角线的交点在第一､三象限的角平分线上，记平行四边形 $MANB$ 的面积为 $S$ ，求证： $S\leqslant \frac {8\sqrt {6}}{9}$ .

## 解答

1. （1）解法一：设 $P\left ({x,y}\right )$ ，易知 $x>-2023$ ，
2. 根据题意可得 $\sqrt {{\left({x-\frac {1}{2}}\right)^{2}}+y{^{2}}}=x+2023-\frac {4045}{2}$ ，化简得 $y{^{2}}=2x$ ，
3. 所以 $C$ 的方程为 $y{^{2}}=2x$ .
4. 解法二：因为点 $P$ 到定点 $F\left ({\frac {1}{2},0}\right )$ 的距离比到定直线 $x=-2023$ 的距离小 $\frac {4045}{2}$ ，
5. 所以点 $P$ 到定点 $F\left ({\frac {1}{2},0}\right )$ 的距离与到定直线 $x=-\frac {1}{2}$ 的距离相等，
6. 由抛物线的定义可知，点 $P$ 的轨迹是以定点 $F\left ({\frac {1}{2},0}\right )$ 为焦点，定直线 $x=-\frac {1}{2}$ 为准线的抛物线，
7. 所以 $C$ 的方程为 $y{^{2}}=2x$ .
8. （2）证明：设 $M\left ({x{{}_{1}},y{{}_{1}}}\right ),N\left ({x{{}_{2}},y{{}_{2}}}\right )$ ，直线 $MN$ 的斜率为 $k\left ({k\ne 0}\right )$ ，线段 $MN$ 的中点为 $Q$ ，
9. 
10. 因为平行四边形MANB对角线的交点在第一､三象限的角平分线上，
11. 所以线段 $MN$ 的中点 $Q$ 在直线 $y=x$ 上，
12. 设 $Q\left ({m,m}\right )\left ({m\ne 0}\right )$ ，所以 $\begin{cases}y{{}_{1}^{2}}=2x{{}_{1}},\\y{{}_{2}^{2}}=2x{{}_{2}},\end{cases}$
13. 所以 $\left ({y{{}_{1}}-y{{}_{2}}}\right )\left ({y{{}_{1}}+y{{}_{2}}}\right )=2\left ({x{{}_{1}}-x{{}_{2}}}\right )$ ，
14. 又 $y{{}_{1}}+y{{}_{2}}=2m,\frac {y{{}_{1}}-y{{}_{2}}}{x{{}_{1}}-x{{}_{2}}}=k,$
15. 所以 $km=1$ ，即 $k=\frac {1}{m}$ .
16. 设直线 $MN$ 的方程为 $y-m=\frac {1}{m}\left ({x-m}\right )$ ，
17. 即 $x-my+m{^{2}}-m=0$ ，
18. 联立 $\begin{cases}x-my+m{^{2}}-m=0,\\y{^{2}}=2x,\end{cases}$ 整理得 $y{^{2}}-2my+2m{^{2}}-2m=0$ ，
19. 所以 ${\rm{Δ}}=8m-4m{^{2}}>0$ ，解得 $0<m<2$ ，
20. $y{{}_{1}}+y{{}_{2}}=2m,y{{}_{1}}y{{}_{2}}=2m{^{2}}-2m$ ，
21. 则 $\left |{MN}\right |=\sqrt {1+m{^{2}}}\left |{y{{}_{1}}-y{{}_{2}}}\right |=\sqrt {1+m{^{2}}}$  $\sqrt {{\left({y{{}_{1}}+y{{}_{2}}}\right)^{2}}-4y{{}_{1}}y{{}_{2}}}$
22. $=\sqrt {1+m{^{2}}}$  $\sqrt {4m{^{2}}-4\left ({2m{^{2}}-2m}\right )}=2\sqrt {1+m{^{2}}}$  $\sqrt {2m-m{^{2}}}$ .
23. 又点 $A$ 到直线 $MN$ 的距离为 $d=\frac {\left |{2-2m+m{^{2}}}\right |}{\sqrt {1+m{^{2}}}}$ ，
24. 所以 $S=2S{{}_{\vartriangle AMN}}=\left |{MN}\right |\cdot d=2\sqrt {1+m{^{2}}}\sqrt {2m-m{^{2}}}\cdot \frac {\left |{2-2m+m{^{2}}}\right |}{\sqrt {1+m{^{2}}}}=2\sqrt {2m-m{^{2}}}\left |{2-2m+m{^{2}}}\right |$ ，
25. 记 $t=\sqrt {2m-m{^{2}}}$ ，
26. 因为 $0<m<2$ ，所以 $t\in \left ({0,1}\right ]$ ，
27. 所以 $S=2t\left ({2-t{^{2}}}\right )=-2t{^{3}}+4t,t\in \left ({0,1}\right ]$ .
28. 令 $f\left ({t}\right )=-2t{^{3}}+4t,t\in \left ({0,1}\right ]$ ，则 $f^{′}{\left ({t}\right )}=-6t{^{2}}+4$ ，
29. 令 $f^{′}{\left ({t}\right )}=0$ ，可得 $t=\frac {\sqrt {6}}{3}$ ，
30. 当 $t\in \left ({0,\frac {\sqrt {6}}{3}}\right )$ 时， $f^{′}{\left ({t}\right )}>0,f\left ({t}\right )$ 在区间 $(0$ ,内单调递增，当 $t\in \left ({\frac {\sqrt {6}}{3},1}\right ]$ 时， $f^{′}{\left ({t}\right )}<$  $0,f\left ({t}\right )$ 在区间 $\left ({\frac {\sqrt {6}}{3},1}\right ]$ 上单调递减，
31. 所以当 $t=\frac {\sqrt {6}}{3}$ ，即 $m=1\pm \frac {\sqrt {3}}{3}$ 时， $f\left ({t}\right )$ 取得最大值，即 $S{{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}=f\left ({\frac {\sqrt {6}}{3}}\right )=\frac {8\sqrt {6}}{9}$ ，
32. 所以 $S\leqslant \frac {8\sqrt {6}}{9}$ .

## 知识点

**中文**:
  - 中点弦问题
  - 直线与抛物线的位置关系
  - 曲线与方程

**English**:
  - Midpoint Chord Problems
  - Line-Parabola Relationship
  - Curves and Equations

---
