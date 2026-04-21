# Mathematics - 题目 2435

**ID**: c873fa46f9904776b40da6f27db9a152
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Multiple-choice

## 题目
$l$ 、 $l{^{\prime }}$ 为两条直线， $α,β$ 为两个平面，满足： $l\cap l{^{\prime }}=O,l$ 与 $l{^{\prime }}$ 的夹角为 $\frac {{\rm{π}}}{6},α//β,l\bot α,α$ 与 $β$ 之间的距离为2．以 $l$ 为轴将 $l{^{\prime }}$ 旋转一周，并用 $α,β$ 截取得到两个同顶点 $O$ (点 $O$ 在平面 $α$ 与 $β$ 之间)的圆锥．设这两个圆锥的体积分别为 $V{{}_{1}}{\rm{、}}V{{}_{2}}$ ，则 $V{{}_{1}}+V{{}_{2}}$ 的最小值为（      ）​​​​​​​‌

## 解答

1. 两个圆锥的轴截面如下图所示， $O{{}_{1}},O{{}_{2}}$ 分别为两圆锥的底面圆的圆心，设半径分别为 $r{{}_{1}},r{{}_{2}}$ ，
2. $O{{}_{1}}O{{}_{2}}\bot DE,O{{}_{1}}O{{}_{2}}\bot BC$ ，直线 $DE,BC$ 分别为两圆锥与 $α,β$ 的交线，
3. 因为 $α$ 与 $β$ 之间的距离为2，所以设 $OO{{}_{1}}=h,OO{{}_{2}}=2-h$ ，
4. 因为 $l$ 与 $l{^{\prime }}$ 的夹角为 $\frac {{\rm{π}}}{6}$ ，所以 $\angle DOE=\frac {{\rm{π}}}{3}$ ，由圆锥的性质知， $OB=OC,OD=OE$ ，
5. 所以 $\vartriangle ODE,\vartriangle OBC$ 为等边三角形，所以 ${\tan}\angle OBC=\frac {OO{{}_{2}}}{BO{{}_{2}}}=\frac {2-h}{r{{}_{2}}}=\sqrt {3}$ ,
6. 所以 $r{{}_{2}}=\frac {2-h}{\sqrt {3}}=\frac {\sqrt {3}}{3}\left ({2-h}\right )$ ，同理 $r{{}_{1}}=\frac {\sqrt {3}}{3}h$ ，
7. 所以 $V{{}_{1}}+V{{}_{2}}=\frac {1}{3}{\rm{π}}r{{}_{1}}{^{2}}h+\frac {1}{3}{\rm{π}}r{{}_{2}}{^{2}}\left ({2-h}\right )=\frac {1}{3}{\rm{π}}{\left({\frac {\sqrt {3}}{3}h}\right)^{2}}h+\frac {1}{3}{\rm{π}}\left [\frac {\sqrt {3}}{3}\left ({2-h}\right )\right ]{^{2}}\left ({2-h}\right )$
8. $=\frac {1}{9}{\rm{π}}\left [h{^{3}}+{\left({2-h}\right)^{3}}\right ]$ ， $0<h<2$ ，
9. 令 $f\left ({h}\right )=\frac {1}{9}{\rm{π}}\left [h{^{3}}+{\left({2-h}\right)^{3}}\right ],0<h<2$ ，
10. $f^{′}{\left ({h}\right )}=\frac {1}{9}{\rm{π}}\left [3h{^{2}}-3{\left({2-h}\right)^{2}}\right ]=\frac {1}{3}{\rm{π}}\left ({-4+4h}\right )=0,$ 解得： $h=1$ ，
11. 所以当 $h\in \left ({0,1}\right )$ 时， $f^{′}{\left ({h}\right )}<0$ ，当 $h\in \left ({1,+∞}\right )$ 时， $f^{′}{\left ({h}\right )}>0$ ，
12. 所以 $f\left ({h}\right )$ 在 $\left ({0,1}\right )$ 上单调递减，在 $\left ({1,+\infty }\right )$ 单调递增，
13. 所以 $f\left ({h}\right ){{}_{{\rm \min }}}=f\left ({1}\right )=\frac {2}{9}{\rm{π}}$ .
14. 所以 $V{{}_{1}}+V{{}_{2}}$ 的最小值为 $\frac {2{\rm{π}}}{9}$ .
15. 故选：D.
16. 

## 知识点

**中文**:
  - 圆柱、圆锥、圆台的体积
  - 导数在优化问题中的应用

**English**:
  - Volume of Revolving Solids
  - Optimization Problems

---
