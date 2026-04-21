# Mathematics - 题目 2976

**ID**: 599e852d546d4e569f6266d079fe3366
**年级**: Grade 12
**难度**: Hard
**题型**: Multiple-select

## 题目
已知正方体 $ABCD-A{{}_{1}}B{{}_{1}}C{{}_{1}}D{{}_{1}}$ 的棱长为1，点 $P$ 满足 $\overrightarrow {{AP}}=λ\overrightarrow {{AD}}+μ\overrightarrow {{AA{{}_{1}}}}$ ，其中 $λ\in \mathbf{R}$ ， $μ\in {\mathbf{R}}$ ，则（      ）​​​​​​​‌

## 解答

1. 对于A：当 $λ=μ$ 时， $\overrightarrow {{AP}}=λ\left ({\overrightarrow {{AD}}+\overrightarrow {{AA{{}_{1}}}}}\right )=λ\overrightarrow {{AD{{}_{1}}}}$ ，
2. 所以点 $P$ 在线段 $AD{{}_{1}}$ 上，
3. 如图，将三角形 $AD{{}_{1}}D$ 与矩形 $D{{}_{1}}ABC{{}_{1}}$ 沿 $AD{{}_{1}}$ 展成平面图形如下所示，
4. 则线段 $DC{{}_{1}}$ 即为 $C{{}_{1}}P+PD$ 的最小值，
5. 利用余弦定理可知 $C{{}_{1}}D{^{2}}=C{{}_{1}}D{{}_{1}^{2}}+DD{{}_{1}^{2}}-2C{{}_{1}}D{{}_{1}}\cdot DD{{}_{1}}\cdot {\rm{c}}{\rm{o}}{\rm{s}}\frac {3{\rm{π}}}{4}=2+\sqrt {2}$ ，
6. 所以 $C{{}_{1}}D=\sqrt {2+\sqrt {2}}$ ，即 $C{{}_{1}}P+PD$ 的最小值为 $\sqrt {2+\sqrt {2}}$ ，故A正确；
7. 
8. 对于B：当 $P$ 在 $D{{}_{1}}$ 时，过点 $P$ 在平面 $ADD{{}_{1}}A{{}_{1}}$ 内只可以作一条直线与 $CP$ 垂直，故B错误；
9. 对于C：以D为原点，分别以 $DA,DC,DD{{}_{1}}$ 为x轴，y轴，z轴建立空间直角坐标系，
10. 则 $D(0,0,0),C{{}_{1}}(0,1,1),A(1,0,0),B(1,1,0),P(x,0,z)$ ，得 $\overrightarrow {{C{{}_{1}}P}}=(x,-1,z-1),\overrightarrow {{AD}}=(-1,0,0)$ ，
11. 所以 ${\cos}\frac {{\rm{π}}}{4}=\frac {\left |{\overrightarrow {{C{{}_{1}}P}}\cdot \overrightarrow {{AD}}}\right |}{\left |{\overrightarrow {{C{{}_{1}}P}}}\right |\cdot \left |{\overrightarrow {{AD}}}\right |}=\frac {\left |{-x}\right |}{\sqrt {x{^{2}}+(z-1){^{2}}+1}}=\frac {\sqrt {2}}{2}$ ，
12. 
13. 整理得 $x{^{2}}-(z-1){^{2}}=1$ ，为双曲线方程，故C正确．
14. 对于D：当 $λ=1$ 时， $\overrightarrow {{AP}}=\overrightarrow {{AD}}+μ\overrightarrow {{AA}}{{}_{1}}\Rightarrow \overrightarrow {{DP}}=μ\overrightarrow {{AA}}{{}_{1}}$ ，故点 $P$ 在线段 $DD{{}_{1}}$ 上运动,
15. 正方体经过点 $A$ ， $P$ ， $C{{}_{1}}$ 的截面为平行四边形 $APC{{}_{1}}H$ ，
16. 以 $D$ 为坐标原点，建立如图所示的空间直角坐标系 $D-xyz$ ，
17. 
18. 则 $A\left ({1,0,0}\right )$ ， $C{{}_{1}}\left ({0,1,1}\right )$ ， $A{{}_{1}}\left ({1,0,1}\right )$ ， $P\left ({0,0,μ}\right )$ ，
19. 所以 $\overrightarrow {{PC{{}_{1}}}}=\left ({0,1,1-μ}\right )$ ， $\overrightarrow {{AC{{}_{1}}}}=\left ({-1,1,1}\right )$ ， $\overrightarrow {{PC{{}_{1}}}}\cdot \overrightarrow {{AC{{}_{1}}}}=2-μ$ ，
20. $\left |{\overrightarrow {{PC{{}_{1}}}}}\right |=\sqrt {1+{\left({1-μ}\right)^{2}}}$ ， $\left |{\overrightarrow {{A{{}_{1}}C}}}\right |=\sqrt {3}$ ，
21. 所以点 $P$ 到直线 $AC{{}_{1}}$ 的距离为 $d=\sqrt {\left |{\overrightarrow {{PC{{}_{1}}}}}\right |{^{2}}-{\left({\frac {\overrightarrow {{PC{{}_{1}}}}\cdot \overrightarrow {{AC{{}_{1}}}}}{\left |{AC{{}_{1}}}\right |}}\right)^{2}}}=\sqrt {1+{\left({1-μ}\right)^{2}}-{\left({\frac {2-μ}{\sqrt {3}}}\right)^{2}}}=\sqrt {\frac {2μ{^{2}}-2μ+2}{3}}$ ，
22. $\left ({d=\sqrt {\left |{\overrightarrow {{PC{{}_{1}}}}}\right |{^{2}}-{\left({\frac {\overrightarrow {{PC{{}_{1}}}}\cdot \overrightarrow {{AC{{}_{1}}}}}{\left |{\overrightarrow {{AC{{}_{1}}}}}\right |}}\right)^{2}}}=\sqrt {\left |{\overrightarrow {{PC{{}_{1}}}}}\right |{^{2}}-\left |{\overrightarrow {{PC{{}_{1}}}}}\right |{^{2}}{\cos}{^{2}}θ}=\left |{\overrightarrow {{PC{{}_{1}}}}}\right |\sin θ}\right )$ ，其中 $θ{\rm{=}}\angle PC{{}_{1}}A$ .
23. 于是当 $μ=\frac {1}{2}$ 时 $d{{}_{{\rm \min }}}=\frac {\sqrt {2}}{2}$ ， $\mathrm{△}PAC{{}_{1}}$ 的面积取最小值，此时截面面积为 $\frac {\sqrt {2}}{2}\times \sqrt {3}=\frac {\sqrt {6}}{2}$ ；
24. 当 $μ=0$ 或 $1$ 时 $d{{}_{{\rm \max }}}=\frac {\sqrt {6}}{3}$ ， $\mathrm{△}PAC{{}_{1}}$ 的面积取最大值，此时截面面积为 $\frac {\sqrt {6}}{3}\times \sqrt {3}=\sqrt {2}$ ，
25. 所以正方体经过点 $A$ ， $P$ ， $C{{}_{1}}$ 的截面面积的取值范围为 $\left [\frac {\sqrt {6}}{2},\sqrt {2}\right ]$ ，故D正确．
26. 故选ACD．

## 知识点

**中文**:
  - 动点问题
  - 空间几何体的平面展开图
  - 截面问题

**English**:
  - Moving Point Problems
  - Planar Nets
  - Cross-section Problems

---
