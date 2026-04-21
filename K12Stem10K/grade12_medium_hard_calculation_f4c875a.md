# Mathematics - 题目 2947

**ID**: f4c875ac246e4b948d8974b03d83bc35
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知圆 $O:x{^{2}}+y{^{2}}=4$ ，直线 $l{{}_{1}}:x=m$ ，直线 $l{{}_{2}}:y=x+b$ 和圆交于A，B两点，过A，B分别做直线 $l{{}_{1}}$ 的垂线，垂足为C，D.​​​​​​​‌(1)求实数b的取值范围；(2)若 $m=-4$ ，求四边形ABDC的面积取最大值时，对应实数 $b$ 的值；(3)若直线AD和直线BC交于点 $E$ ，问是否存在实数 $m$ ，使得点 $E$ 在一条平行于 $x$ 轴的直线上?若存在，求出实数 $m$ 的值；若不存在，请说明理由.

## 解答

1. （1）圆 $O$ 的半径为2，因为直线 $l{{}_{2}}$ 和圆 $O$ 交于A，B两点，
2. 所以圆心到直线 $l{{}_{2}}$ 的距离 $d=\frac {\left |{b}\right |}{\sqrt {2}}<2$ ，解得 $-2\sqrt {2}<b<2\sqrt {2}$ ，
3. 则实数b的取值范围为 $-2\sqrt {2}<b<2\sqrt {2}$ ；
4. （2）设 $A\left ({x{{}_{1}},y{{}_{1}}}\right ),B\left ({x{{}_{2}},y{{}_{2}}}\right )$ ，则 $C\left ({-4,y{{}_{1}}}\right ),D\left ({-4,y{{}_{2}}}\right )$ ，
5. 由 $\begin{cases}y=x+b\\x{^{2}}+y{^{2}}=4\end{cases}$ 得 $2x{^{2}}+2bx+b{^{2}}-4=0$ ，
6. 所以 $x{{}_{1}}+x{{}_{2}}=-b,x{{}_{1}}x{{}_{2}}=\frac {b{^{2}}-4}{2}$ ， $y{{}_{1}}-y{{}_{2}}=x{{}_{1}}-x{{}_{2}}$ ，
7. 则 $\left |{y{{}_{1}}-y{{}_{2}}}\right |=\sqrt {{\left({x{{}_{1}}-x{{}_{2}}}\right)^{2}}}=\sqrt {{\left({x{{}_{1}}+x{{}_{2}}}\right)^{2}}-4x{{}_{1}}x{{}_{2}}}$  $=\sqrt {8-b{^{2}}}$ ，因为四边形 $ABDC$ 为直角梯形，
8. 所以四边形 $ABDC$ 的面积 $S=\frac {1}{2}\left ({\left |{AC}\right |+\left |{DB}\right |}\right )\left |{y{{}_{1}}-y{{}_{2}}}\right |$
9. $=\frac {1}{2}\left ({x{{}_{1}}+4+x{{}_{2}}+4}\right )\left |{y{{}_{1}}-y{{}_{2}}}\right |=\frac {1}{2}\sqrt {\left ({8-b{^{2}}}\right ){\left({8-b}\right)^{2}}}$ ，
10. 令 $f\left ({b}\right )=\left ({8-b{^{2}}}\right ){\left({8-b}\right)^{2}}$  $\left ({-2\sqrt {2}<b<2\sqrt {2}}\right )$ ，
11. $f^{′}{\left ({b}\right )}=4\left ({8-b}\right )\left ({b{^{2}}-4b-4}\right )$ ，令 $f^{′}{\left ({b}\right )}=0$ ，解得 $b=2-2\sqrt {2}$ ，
12. 当 $-2\sqrt {2}<b<2-2\sqrt {2}$ 时， $f^{′}{\left ({b}\right )}>0$ ， $f\left ({b}\right )$ 单调递增，
13. 当 $2-2\sqrt {2}<b<2\sqrt {2}$ 时， $f^{′}{\left ({b}\right )}<0$ ， $f\left ({b}\right )$ 单调递减，
14. 所以当 $b=2-2\sqrt {2}$ 时四边形ABDC的面积最大，
15. 且最大值为 $\left ({6+2\sqrt {2}}\right )\sqrt {2\sqrt {2}-1}$ ；
16. 
17. ${\rm （3）}A\left ({x{{}_{1}},y{{}_{1}}}\right ),B\left ({x{{}_{2}},y{{}_{2}}}\right )$ ，则 $C\left ({m,y{{}_{1}}}\right ),D\left ({m,y{{}_{2}}}\right )$ ，且直线 $AD$ ， $BC$ 的斜率存在，
18. 由 ${\rm （2）}x{{}_{1}}+x{{}_{2}}=-b,x{{}_{1}}x{{}_{2}}=\frac {b{^{2}}-4}{2}$ ， $y{{}_{1}}=x{{}_{1}}+b$ ， $y{{}_{2}}=x{{}_{2}}+b$ ，
19. 直线 $AD:\frac {y-y{{}_{2}}}{y{{}_{1}}-y{{}_{2}}}=\frac {x-m}{x{{}_{1}}-m}$ ，直线 $BC:\frac {y-y{{}_{1}}}{y{{}_{2}}-y{{}_{1}}}=\frac {x-m}{x{{}_{2}}-m}$ ，
20. 联立得 $y=\frac {y{{}_{2}}x{{}_{1}}+x{{}_{2}}y{{}_{1}}-my{{}_{1}}-my{{}_{2}}}{x{{}_{1}}+x{{}_{2}}-2m}=\frac {\left ({x{{}_{2}}+b}\right )\left ({x{{}_{1}}-m}\right )+\left ({x{{}_{1}}+b}\right )\left ({x{{}_{2}}-m}\right )}{x{{}_{1}}+x{{}_{2}}-2m}$
21. $=\frac {2x{{}_{2}}x{{}_{1}}+\left ({x{{}_{1}}+x{{}_{2}}}\right )\left ({b-m}\right )-2bm}{x{{}_{1}}+x{{}_{2}}-2m}=\frac {b{^{2}}-4-b\left ({b-m}\right )-2bm}{-b-2m}=\frac {bm+4}{b+2m}$ ，
22. 若 $\frac {bm+4}{b+2m}$ 为常数，则 $bm+4=k\left ({b+2m}\right )$ ，其中 $k$ 为常数，
23. 可得 $\begin{cases}k=m\\4=2mk\end{cases}$ ，解得 $k=\pm \sqrt {2}$ ，
24. 所以当 $m=\pm \sqrt {2}$ 时点 $E$ 在一条平行于 $x$ 轴的直线上.
25. 

## 知识点

**中文**:
  - 导数在优化问题中的应用
  - 直线与圆相交

**English**:
  - Optimization Problems
  - Line Intersection with Circle

---
