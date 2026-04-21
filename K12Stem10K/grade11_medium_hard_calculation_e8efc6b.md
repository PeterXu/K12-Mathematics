# Mathematics - 题目 1287

**ID**: e8efc6b2d9eb4a5087185bae806ff02d
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设圆 $M:(x-3){^{2}}+(y-4){^{2}}=25$ ，直线 $l:(m+1)x+(2m+1)y=7m+4$ .​​​​​​​‌（1）证明： $l$ 始终与圆M相交；（2）设 $l$ 与圆M交于A，B两点.${\rm （i）}$ 求过A，B，且半径为5的圆的圆心N到原点O的距离的最值；${\rm （ii）}$ 证明：存在唯一的定点P，使 $\overrightarrow {{PA}}\cdot \overrightarrow {{PB}}$ 为定值，并求出该定值.

## 解答

1. （1）圆 $M:(x-3){^{2}}+(y-4){^{2}}=25$ 的圆心 $M(3,4)$ ，半径 $r\mathrm{=}5$ ，
2. 直线 $l:(m+1)x+(2m+1)y=7m+4$ ，即 $m(x+2y-7)+(x+y-4)=0$ .
3. 由 $\begin{cases}x+2y-7=0\\x+y-4=0\end{cases}$ ，解得 $\begin{cases}x=1\\y=3\end{cases}$ ，即直线 $l$ 过定点 $P{{}_{0}}(1,3)$ ，
4. 由 $\left |{P{{}_{0}}M}\right |=\sqrt {(1-3){^{2}}+(3-4){^{2}}}=\sqrt {(-2){^{2}}+(-1){^{2}}}=\sqrt {5}<5=r$ ，
5. 得 $P{{}_{0}}(1,3)$ 位于圆M的内部，因此直线 $l$ 始终过圆内的一个点，它必然会与圆交于两个不同的点，
6. 所以直线 $l$ 始终与圆M相交.
7. （2）（i）依题意，点N到A，B的距离均为5，由 $M(3,4)$ 到A，B的距离也为5，
8. 得N与M重合，或N是M关于直线 $l$ 的对称点，则 $\left |{NP{{}_{0}}}\right |=\left |{MP{{}_{0}}}\right |=\sqrt {5}$ ，
9. 因此N的轨迹是以 $P{{}_{0}}(1,3)$ 为圆心、 $\sqrt {5}$ 为半径的圆 $(x-1){^{2}}+(y-3){^{2}}=5$ ，
10. 且N的轨迹不过点 $(\frac {7}{5},\frac {4}{5})$ ，又直线 $l$ 表示除 $x+2y-7=0$ 之外的所有过点 $P{{}_{0}}(1,3)$ 的直线，
11. $\left |{OP{{}_{0}}}\right |=\sqrt {1{^{2}}+3{^{2}}}=\sqrt {10}$ ，所以ON的最大值为 $\sqrt {10}+\sqrt {5}$ ，最小值为 $\sqrt {10}-\sqrt {5}$ .
12. 
13. ${\rm （ii）}$ 定点P即为 $P{{}_{0}}(1,3)$ ，
14. 先证明存在性：即证明当P为 $P{{}_{0}}(1,3)$ 时， $\overrightarrow {{P{{}_{0}}A}}\cdot \overrightarrow {{P{{}_{0}}B}}$ 为一个定值，取线段AB的中点为 $Q$ ，
15. 则 $\overrightarrow {{P{{}_{0}}A}}\cdot \overrightarrow {{P{{}_{0}}B}}=(\overrightarrow {{P{{}_{0}}Q}}+\overrightarrow {{QA}})\cdot (\overrightarrow {{P{{}_{0}}Q}}+\overrightarrow {{QB}})=\overrightarrow {{P{{}_{0}}Q}}{^{2}}-\overrightarrow {{QA}}{^{2}}$  $=(\overrightarrow {{P{{}_{0}}M}}{^{2}}-\overrightarrow {{MQ}}{^{2}})-(\overrightarrow {{MA}}{^{2}}-\overrightarrow {{MQ}}{^{2}})=\overrightarrow {{P{{}_{0}}M}}{^{2}}-r{^{2}}=-20$ ，
16. 所以存在定点P，使 $\overrightarrow {{PA}}\cdot \overrightarrow {{PB}}$ 为定值为 $-20$ ；
17. 再证明唯一性：假设存在不同于 $P{{}_{0}}(1,3)$ 的定点 $P(x{{}_{P}},y{{}_{P}})$ ，使得 $\overrightarrow {{PA}}\cdot \overrightarrow {{PB}}$ 也是一个与m无关的定值 $k$ ，
18. 由 $\overrightarrow {{PA}}=\overrightarrow {{P{{}_{0}}A}}-\overrightarrow {{P{{}_{0}}P}}$ ， $\overrightarrow {{PB}}=\overrightarrow {{P{{}_{0}}B}}-\overrightarrow {{P{{}_{0}}P}}$ ，得 $\overrightarrow {{PA}}\cdot \overrightarrow {{PB}}=(\overrightarrow {{P{{}_{0}}A}}-\overrightarrow {{P{{}_{0}}P}})\cdot (\overrightarrow {{P{{}_{0}}B}}-\overrightarrow {{P{{}_{0}}P}})$ ，
19. 也即 $k=\overrightarrow {{P{{}_{0}}A}}\cdot \overrightarrow {{P{{}_{0}}B}}-\overrightarrow {{P{{}_{0}}A}}\cdot \overrightarrow {{P{{}_{0}}P}}-\overrightarrow {{P{{}_{0}}P}}\cdot \overrightarrow {{P{{}_{0}}B}}+|\overrightarrow {{P{{}_{0}}P}}|{^{2}}=\overrightarrow {{P{{}_{0}}A}}\cdot \overrightarrow {{P{{}_{0}}B}}-\overrightarrow {{P{{}_{0}}P}}\cdot (\overrightarrow {{P{{}_{0}}A}}+\overrightarrow {{P{{}_{0}}B}})+|\overrightarrow {{P{{}_{0}}P}}|{^{2}}$ ，
20. 由 $\overrightarrow {{P{{}_{0}}A}}\cdot \overrightarrow {{P{{}_{0}}B}}=-20$ ，且P和 $P{{}_{0}}$ 都是定点，则 $|\overrightarrow {{P{{}_{0}}P}}|{^{2}}$ 也是一个与m无关的定值，
21. 因此 $k=-20-\overrightarrow {{P{{}_{0}}P}}\cdot (\overrightarrow {{P{{}_{0}}A}}+\overrightarrow {{P{{}_{0}}B}})+|\overrightarrow {{P{{}_{0}}P}}|{^{2}}$ ，
22. 由 $k$ ， $-20$ 和 $|\overrightarrow {{P{{}_{0}}P}}|{^{2}}$ 都是定值，则 $\overrightarrow {{P{{}_{0}}P}}\cdot (\overrightarrow {{P{{}_{0}}A}}+\overrightarrow {{P{{}_{0}}B}})$ 也是一个定值，
23. 设 $K$ 是弦AB的中点，则 $\overrightarrow {{P{{}_{0}}A}}+\overrightarrow {{P{{}_{0}}B}}=2\overrightarrow {{P{{}_{0}}K}}$ ，即 $2\overrightarrow {{P{{}_{0}}P}}\cdot \overrightarrow {{P{{}_{0}}K}}$ 也是一个定值，
24. 当 $m=-1$ 时，直线 $l$ 为 $y=3$ ，对应 $K{{}_{1}}(3,3)$ ；当 $m=-\frac {1}{2}$ 时，直线 $l$ 为 $x=1$ ，对应 $K{{}_{2}}(1,4)$ ；
25. 当 $m=0$ 时，直线 $l$ 为 $x+y=4$ ，对应 $K{{}_{3}}(\frac {3}{2},\frac {5}{2})$ ，而 $\overrightarrow {{P{{}_{0}}P}}=(x{{}_{P}}-1,y{{}_{P}}-3)$ ，
26. 则 $\overrightarrow {{P{{}_{0}}P}}\cdot \overrightarrow {{P{{}_{0}}K{{}_{1}}}}=2x{{}_{P}}-2$ ， $\overrightarrow {{P{{}_{0}}P}}\cdot \overrightarrow {{P{{}_{0}}K{{}_{2}}}}=y{{}_{P}}-3$ ， $\overrightarrow {{P{{}_{0}}P}}\cdot \overrightarrow {{P{{}_{0}}K{{}_{3}}}}=\frac {1}{2}x{{}_{P}}-\frac {1}{2}y{{}_{P}}+1$ ，
27. 由于恒为定值，则 $\begin{cases}y{{}_{P}}-3=2x{{}_{P}}-2\\y{{}_{P}}-3=\frac {1}{2}x{{}_{P}}-\frac {1}{2}y{{}_{P}}+1\end{cases}$ ，解得 $x{{}_{P}}=1,y{{}_{P}}=3$ ，
28. 即 $P(1,3)$ ，与 $P{{}_{0}}(1,3)$ 重合，假设矛盾，因此定点P是唯一的，
29. 所以存在唯一的定点 $P(1,3)$ ，使 $\overrightarrow {{PA}}\cdot \overrightarrow {{PB}}$ 是定值 $-20$ .

## 知识点

**中文**:
  - 圆的方程与圆的几何性质的结合问题
  - 直线与圆的位置关系的判断
  - 直线与圆相交

**English**:
  - Circle Equation and Geometric Properties
  - Determining Line-Circle Relationship
  - Line Intersection with Circle

---
