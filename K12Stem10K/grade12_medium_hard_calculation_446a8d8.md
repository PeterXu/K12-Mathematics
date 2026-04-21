# Mathematics - 题目 3814

**ID**: 446a8d8c2aca43678174dba4ebd5e95b
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知椭圆  $E{{}_{n}}：\frac {x{^{2}}}{a{{}_{n}^{2}}}+\frac {y{^{2}}}{b{{}_{n}^{2}}}=1\left ({a{{}_{n}}>b{{}_{n}}>0，n\in {\rm N}{^{{\rm{*}}}},a{{}_{1}}=1}\right )$  的离心率为  $\frac {\sqrt {2}}{2}，F{{}_{n}}$  为  $E{{}_{n}}$  的右焦点，过  $F{{}_{n}}$  的直线 (不与  $x$  轴重合) 与  $E{{}_{n}}$  交于  $A{{}_{n}}，B{{}_{n}}$  两点，过  $A{{}_{n}}，B{{}_{n}}$  分别作平行于  $x$  轴的直线与直线  $x=\sqrt {2}a{{}_{n}}$  分别交于  $C{{}_{n}}，D{{}_{n}}$  两点，直线  $A{{}_{n}}D{{}_{n}}$  与  $x$  轴的交点为  $M{{}_{n}}\left ({3\sqrt {2}a{{}_{n+1}},0}\right )$  ，设直线  $A{{}_{n}}D{{}_{n}}$  与直线  $B{{}_{n}}C{{}_{n}}$  的交点为  $H{{}_{n}}$  ． 记  $\vartriangle A{{}_{n}}B{{}_{n}}H{{}_{n}}$  的面积为  $S{{}_{n}}$  ．（1）求数列  $\left \{a{{}_{n}}\right \}$  的通项公式；​​​​​​​‌（2）求证：  $S{{}_{n}}\leqslant \frac {\sqrt {2}}{8}$  ．

## 解答

1. （1）因为 ${\rm }{\rm {\rm e}}^{2}=\frac {a{{}_{n}^{2}}-b{{}_{n}^{2}}}{a{{}_{n}^{2}}}=1-\frac {b{{}_{n}^{2}}}{a{{}_{n}^{2}}}=\frac {1}{2}{\rm }$ ，
2. 所以 $b{{}_{n}}=\frac {\sqrt {2}}{2}a{{}_{n}},c{{}_{n}}=\frac {\sqrt {2}}{2}a{{}_{n}}$ ，椭圆 $E{{}_{n}}:\frac {x{^{2}}}{a{{}_{n}^{2}}}+\frac {2y{^{2}}}{a{{}_{n}^{2}}}=1$ ，焦点 $F{{}_{n}}\left ({\frac {\sqrt {2}}{2}a{{}_{n}},0}\right )$ ．
3. 设直线 $A{{}_{n}}B{{}_{n}}$ 的方程为 $x=my+\frac {\sqrt {2}}{2}a{{}_{n}}$ ，代入椭圆 $E{{}_{n}}:\frac {x{^{2}}}{a{{}_{n}^{2}}}+\frac {2y{^{2}}}{a{{}_{n}^{2}}}=1$ ，
4. 可得： $\left ({m{^{2}}+2}\right )y{^{2}}+\sqrt {2}ma{{}_{n}}y-\frac {1}{2}a{{}_{n}^{2}}=0,Δ=\left ({4m{^{2}}+4}\right )a{{}_{n}^{2}}>0$ ．
5. 设点 $A{{}_{n}}\left ({x{{}_{n}},y{{}_{n}}}\right ),B{{}_{n}}\left ({x{{}_{n}}{^{\prime }},y{{}_{n}}{^{\prime }}}\right ),C{{}_{n}}\left ({\sqrt {2}a{{}_{n}},y{{}_{n}}}\right ),D{{}_{n}}\left ({\sqrt {2}a{{}_{n}},y{{}_{n}}{^{\prime }}}\right )$ ，
6. 由韦达定理 $y{{}_{n}}+y{{}_{n}}{^{\prime }}=\frac {-\sqrt {2}ma{{}_{n}}}{m{^{2}}+2},y{{}_{n}}y{{}_{n}}{^{\prime }}=\frac {-\frac {1}{2}a{{}_{n}^{2}}}{m{^{2}}+2}$ ，可得 $my{{}_{n}}y{{}_{n}}{^{\prime }}=\frac {\sqrt {2}a{{}_{n}}}{4}\left ({y{{}_{n}}+y{{}_{n}}{^{\prime }}}\right )$ ．
7. 直线 $A{{}_{n}}D{{}_{n}}$ 的斜率 $k{{}_{A{{}_{n}}D{{}_{n}}}}=\frac {y{{}_{n}}{^{\prime }}-y{{}_{n}}}{\sqrt {2}a{{}_{n}}-x{{}_{n}}}$ ，其方程为 $y-y{{}_{n}}{^{\prime }}=\frac {y{{}_{n}}{^{\prime }}-y{{}_{n}}}{\sqrt {2}a{{}_{n}}-x{{}_{n}}}\left ({x-\sqrt {2}a{{}_{n}}}\right )$ ，
8. 令 $y=0$ ，可得 $x=\frac {-y{{}_{n}}{^{^{′}}}\left ({\sqrt {2}a{{}_{n}}-x{{}_{n}}}\right )}{y{{}_{n}}{^{^{′}}}-y{{}_{n}}}+\sqrt {2}a{{}_{n}}=\frac {-y{{}_{n}}{^{^{′}}}\left ({\frac {\sqrt {2}}{2}a{{}_{n}}-my{{}_{n}}}\right )}{y{{}_{n}}{^{^{′}}}-y{{}_{n}}}+\sqrt {2}a{{}_{n}}=\frac {-\frac {\sqrt {2}}{2}a{{}_{n}}y{{}_{n}}{^{^{′}}}+\frac {\sqrt {2}}{4}a{{}_{n}}\left ({y{{}_{n}}{^{^{′}}}+y{{}_{n}}}\right )}{y{{}_{n}}{^{^{′}}}-y{{}_{n}}}+\sqrt {2}a{{}_{n}}$
9. $=\frac {\frac {\sqrt {2}}{4}a{{}_{n}}y{{}_{n}}-\frac {\sqrt {2}}{4}a{{}_{n}}y{{}_{n}}{^{\prime }}}{y{{}_{n}}{^{\prime }}-y{{}_{n}}}+\sqrt {2}a{{}_{n}}=\frac {3\sqrt {2}}{4}a{{}_{n}}$ ，
10. 所以直线 $A{{}_{n}}D{{}_{n}}$ 恒过点 $\left ({\frac {3\sqrt {2}}{4}a{{}_{n}},0}\right )$ ．
11. 又直线 $A{{}_{n}}D{{}_{n}}$ 与 $x$ 轴的交点为 $M{{}_{n}}\left ({3\sqrt {2}a{{}_{n+1}},0}\right )$ ，所以 $\frac {3\sqrt {2}}{4}a{{}_{n}}=3\sqrt {2}a{{}_{n+1}}$ ，
12. 即 $\frac {a{{}_{n+1}}}{a{{}_{n}}}=\frac {1}{4}$ ，所以数列 $\left \{a{{}_{n}}\right \}$ 是首项为 $a{{}_{1}}=1$ ，公比为 $\frac {1}{4}$ 的等比数列，
13. 所以 $a{{}_{n}}={\left({\frac {1}{4}}\right)^{n-1}}$ ．
14. （2）由对称性可知，直线 $B{{}_{n}}C{{}_{n}}$ 也恒过定点 $\left ({\frac {3\sqrt {2}}{4}a{{}_{n}},0}\right )$ ，
15. 故两直线 $A{{}_{n}}D{{}_{n}}$ 与 $B{{}_{n}}C{{}_{n}}$ 的交点为 $H{{}_{n}}\left ({\frac {3\sqrt {2}}{4}a{{}_{n}},0}\right )$ ．
16. 所以 $\left |{H{{}_{n}}F{{}_{n}}}\right |=\left |{\frac {3\sqrt {2}}{4}a{{}_{n}}-\frac {\sqrt {2}}{2}a{{}_{n}}}\right |=\frac {\sqrt {2}}{4}a{{}_{n}},\left |{y{{}_{n}}-y{{}_{n}}{^{\prime }}}\right |=\sqrt {{\left({y{{}_{n}}+y{{}_{n}}{^{\prime }}}\right)^{2}}-4y{{}_{n}}y{{}_{n}}{^{\prime }}}$
17. $=\sqrt {{\left({\frac {-\sqrt {2}ma{{}_{n}}}{m{^{2}}+2}}\right)^{2}}-4\cdot \frac {-\frac {1}{2}a{{}_{n}^{2}}}{m{^{2}}+2}}=\frac {2\sqrt {m{^{2}}+1}}{m{^{2}}+2}a{{}_{n}}$ ，
18. 所以 $S{{}_{n}}=\frac {1}{2}\left |{H{{}_{n}}F{{}_{n}}}\right |\cdot \left |{y{{}_{n}}-y{{}_{n}}{^{\prime }}}\right |=\frac {\sqrt {2}}{4}\cdot \frac {\sqrt {m{^{2}}+1}}{m{^{2}}+2}\cdot a{{}_{n}^{2}}$ ，而 $\frac {S{{}_{n+1}}}{S{{}_{n}}}=\frac {a{{}_{n+1}^{2}}}{a{{}_{n}^{2}}}=\frac {1}{16}$ ，
19. 故数列 $\left \{S{{}_{n}}\right \}$ 是以 $S{{}_{1}}=\frac {\sqrt {2}}{4}\cdot a{{}_{1}^{2}}\cdot \frac {\sqrt {m{^{2}}+1}}{m{^{2}}+2}=\frac {\sqrt {2}}{4}\cdot \frac {\sqrt {m{^{2}}+1}}{m{^{2}}+2}$ 为首项，以 $\frac {1}{16}$ 为公比的等比数列，
20. 且为单调递减数列，所以 $S{{}_{n}}$ 的所有项的最大值为 $S{{}_{1}}=\frac {\sqrt {2}}{4}\cdot \frac {\sqrt {m{^{2}}+1}}{m{^{2}}+2}$ ．
21. 令 $t=\sqrt {m{^{2}}+1}$ ，则 $t\geqslant 1$ ，
22. 故 $S{{}_{1}}=\frac {\sqrt {2}}{4}\cdot \frac {\sqrt {m{^{2}}+1}}{m{^{2}}+2}=\frac {\sqrt {2}}{4}\cdot \frac {t}{t{^{2}}+1}=\frac {\sqrt {2}}{4}\cdot \frac {1}{t+\frac {1}{t}}\leqslant \frac {\sqrt {2}}{4}\cdot \frac {1}{2\sqrt {t\cdot \frac {1}{t}}}=\frac {\sqrt {2}}{8}$ ，
23. 当且仅当 $t=1$ ，即 $m=0$ 时，取最大值 $\frac {\sqrt {2}}{8}$ ，
24. 所以数列 $\left \{S{{}_{n}}\right \}$ 的所有项的最大值的最大值为 $\frac {\sqrt {2}}{8}$ ．
25. 

## 知识点

**中文**:
  - 数列与解析几何的综合
  - 椭圆的标准方程及应用

**English**:
  - Sequences with Analytic Geometry
  - Standard Equation and Applications

---
