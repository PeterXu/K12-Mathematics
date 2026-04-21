# Mathematics - 题目 3736

**ID**: 83b5737c3cfe4e9eb2c73210df6392b9
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知双曲线 $C:\frac {x^{2}}{a^{2}}-\frac {y^{2}}{b^{2}}=1(a>b>0)$ 的一个焦点为 $F\left ({2,0}\right ),O$ 为坐标原点，过点 $F$ 作直线 $l$ 与一条渐近线垂直，垂足为 $A$ ，与另一条渐近线相交于点 $B$ ，且 $A,B$ 都在 $y$ 轴右侧， $\left |{OA}\right |+\left |{OB}\right |=\sqrt {3}\left |{AB}\right |$(1)求双曲线 $C$ 的方程；(2)若直线 $l_{1}$ 与双曲线 $C$ 的右支相切，切点为 $P,l_{1}$ 与直线 $l_{2}:x=\frac {3}{2}$ 交于点 $Q$ ，试探究以线段 $PQ$ 为直径的圆是否过 $x$ 轴上的定点.​​​​​​​‌

## 解答

1. （1）不妨设点A在第一象限， $\angle AOF=α$ ，则 $\angle AOB=2α$ .
2. 因为 $OA\bot AB$ ，则 $\left |{OA}\right |=\left |{OB}\right |{\rm{c}}{\rm{o}}{\rm{s}}2α,\left |{AB}\right |=\left |{OB}\right |{\rm{s}}{\rm{i}}{\rm{n}}2α$ .
3. 由已知， $\left |{OB}\right |{\rm{c}}{\rm{o}}{\rm{s}}2α+\left |{OB}\right |=\sqrt {3}\left |{OB}\right |{\rm{s}}{\rm{i}}{\rm{n}}2α$ ，即 ${\rm{c}}{\rm{o}}{\rm{s}}2α+1=\sqrt {3}{\rm{s}}{\rm{i}}{\rm{n}}2α$ ，
4. 即 $2{\rm{c}}{\rm{o}}{\rm{s}}^{2}α=2\sqrt {3}{\rm{s}}{\rm{i}}{\rm{n}}α{\rm{c}}{\rm{o}}{\rm{s}}α$ .
5. 因为 ${\rm{c}}{\rm{o}}{\rm{s}}α\ne 0$ ，则 ${\rm{c}}{\rm{o}}{\rm{s}}α=\sqrt {3}{\rm{s}}{\rm{i}}{\rm{n}}α$ ，即 ${\rm{t}}{\rm{a}}{\rm{n}}α=\frac {1}{\sqrt {3}}$ .
6. 因为 $α$ 为渐近线 $OA$ 的倾斜角，则 $\frac {b}{a}=\frac {1}{\sqrt {3}}$ ，即 $a=\sqrt {3}b$ .
7. 又 $\sqrt {a^{2}+b^{2}}=2$ ，则 $a=\sqrt {3},b=1$ .
8. 所以双曲线 $C$ 的方程是 $\frac {x^{2}}{3}-y^{2}=1$ .
9. （2）当直线 $l_{1}$ 的斜率不存在时，直线 $l_{1}$ 与 $l_{2}:x=\frac {3}{2}$ 平行，不合要求，
10. 故直线 $l_{1}$ 的斜率存在，设其方程为 $y=kx+m$ ，
11. 联立直线 $l_{1}$ 与双曲线 $C$ 的方程，消去 $y$ ，
12. 得 $\left ({3k^{2}-1}\right )x^{2}+6kmx+3m^{2}+3=0$ ，
13. ${\rm{Δ}}=36k^{2}m^{2}-12\left ({3k^{2}-1}\right )\left ({m^{2}+1}\right )=12\left ({m^{2}+1-3k^{2}}\right )=0$ ，
14. 得 $m^{2}=3k^{2}-1$ ，则 $m\ne 0$ ，
15. 设切点 $P\left ({x_{1},y_{1}}\right )$ ，则 $x_{1}=-\frac {6km}{2\left ({3k^{2}-1}\right )}=-\frac {3k}{m}$ ，
16. $y_{1}=kx_{1}+m=-\frac {3k^{2}}{m}+m=\frac {m^{2}-3k^{2}}{m}=-\frac {1}{m}$ .
17. 设 $Q\left ({x_{2},y_{2}}\right )$ ，因为 $Q$ 是直线 $l_{1}$ 与直线 $l_{2}$ 的交点，
18. 所以 $x_{2}=\frac {3}{2},y_{2}=\frac {3}{2}k+m$ ，
19. 假设 $x$ 轴上存在定点 $M\left ({x_{0},0}\right )$ 满足条件，则 $MP\bot MQ$ 恒成立，
20. 即： $\overrightarrow {MP}\cdot \overrightarrow {MQ}=\left ({x_{1}-x_{0},y_{1}}\right )\cdot \left ({x_{2}-x_{0},y_{2}}\right )=\left ({x_{1}-x_{0}}\right )\left ({x_{2}-x_{0}}\right )+y_{1}y_{2}$
21. $=x_{1}x_{2}+y_{1}y_{2}-x_{0}\left ({x_{1}+x_{2}}\right )+x_{0}^{2}=-\frac {9k}{2m}-\frac {3k}{2m}-1-x_{0}\left ({\frac {3}{2}-\frac {3k}{m}}\right )+x_{0}^{2}$
22. $=x_{0}^{2}-\frac {3}{2}x_{0}-1+\frac {3k}{m}\left ({x_{0}-2}\right )=\frac {1}{2}\left ({x_{0}-2}\right )\left ({2x_{0}+1}\right )+\frac {3k}{m}\left ({x_{0}-2}\right )$
23. $=\left ({x_{0}-2}\right )\left ({x_{0}+\frac {1}{2}+\frac {3k}{m}}\right )=0$ ，
24. 故存在 $x_{0}=2$ ，使得 $\overrightarrow {MP}\cdot \overrightarrow {MQ}=0$ ，即 $MP\bot MQ$ ，
25. 所以 $x$ 轴上存在定点 $M\left ({2,0}\right )$ 在以 $PQ$ 为直径的圆上.

## 知识点

**中文**:
  - 双曲线标准方程及其应用
  - 直线与双曲线的位置关系
  - 定点定值定直线问题

**English**:
  - Standard Equation and Applications
  - Line-Hyperbola Relationship
  - Fixed Point, Value, Line Problems

---
