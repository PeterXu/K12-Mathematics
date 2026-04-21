# Mathematics - 题目 453

**ID**: 30e9f22498f645d9a35b6a1aaff1697a
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知椭圆 $\frac {x{^{2}}}{a{^{2}}}+\frac {y{^{2}}}{b{^{2}}}=1$  $\left ({a>b>0}\right )$ 的左、右焦点分别为 $F{{}_{1}}$ 、 $F{{}_{2}}$ ，离心率为 $\frac {\sqrt {3}}{2}$ ，过 $F{{}_{2}}$ 且斜率不为0的直线与椭圆交于 $A$ ， $B$ 两点， $\vartriangle F{{}_{1}}AF{{}_{2}}$ 的周长为 $4+2\sqrt {3}$ ．（1）求椭圆 $C$ 的方程；​​​​​​​‌（2）设 $O$ 为坐标原点，求 $\left |{{\mathop {OA}\limits_{}^{\to }}+{\mathop {OB}\limits_{}^{\to }}}\right |$ 的取值范围．

## 解答

1. （1）由题得 $\begin{cases}2a+2c=4+2\sqrt {3}\\\frac {c}{a}=\frac {\sqrt {3}}{2}\end{cases},\therefore \begin{cases}a=2\\c=\sqrt {3}\end{cases},\therefore b{^{2}}=4-3=1$ .
2. 所以椭圆的方程为 $\frac {x{^{2}}}{4}{\rm{+}}y{^{2}}=1$ .
3. （2）因为 $F{{}_{2}}(\sqrt {3},0)$ ,所以设直线AB的方程为 $x=my+\sqrt {3},A(x{{}_{1}},y{{}_{1}}),B(x{{}_{2}},y{{}_{2}})$ ,
4. 由 $\begin{cases}\frac {x{^{2}}}{4}{\rm{+}}y{^{2}}=1\\x=my+\sqrt {3}\end{cases}$ 消去 $x$ 得 $(m{^{2}}+4)y{^{2}}+2\sqrt {3}my-1=0$ ，
5. 所以 $\begin{cases}y{{}_{1}}+y{{}_{2}}=-\frac {2\sqrt {3}m}{m{^{2}}+4}\\y{{}_{1}}\cdot y{{}_{2}}=-\frac {1}{m{^{2}}+4}\end{cases}$ ，
6. 又 ${\mathop {OA}\limits_{}^{\to }}+{\mathop {OB}\limits_{}^{\to }}=(x{{}_{1}}+x{{}_{2}},y{{}_{1}}+y{{}_{2}})=(my{{}_{1}}+my{{}_{2}}+2\sqrt {3},y{{}_{1}}+y{{}_{2}})$ ，
7. 所以 $|{\mathop {OA}\limits_{}^{\to }}+{\mathop {OB}\limits_{}^{\to }}|=\sqrt {(my{{}_{1}}+my{{}_{2}}+2\sqrt {3}){^{2}}+(y{{}_{1}}+y{{}_{2}}){^{2}}}=\sqrt {(\frac {8\sqrt {3}}{m{^{2}}+4}){^{2}}+(-\frac {2\sqrt {3}m}{m{^{2}}+4}){^{2}}}$
8. ${\rm{=}}2\sqrt {\frac {3m{^{2}}+48}{(m{^{2}}+4){^{2}}}}$ ，
9. 令 $t=\frac {1}{m{^{2}}+4}\in (0,\frac {1}{4}],$ 所以 $\frac {3m{^{2}}+48}{(m{^{2}}+4){^{2}}}=\frac {3(m{^{2}}+4)+36}{(m{^{2}}+4){^{2}}}=\frac {\frac {3}{t}+36}{\frac {1}{t{^{2}}}}=36t{^{2}}+3t$ ，
10. 因为二次函数 $y=36t{^{2}}+3t$ 在 $t\in (0,\frac {1}{4}]$ 上单调递增，
11. 所以 $y=36t{^{2}}+3t\in （0,3]$ ，
12. 因此 ${\rm{|}}{\mathop {OA}\limits_{}^{\to }}{\rm{+}}{\mathop {OB}\limits_{}^{\to }}{\rm{|}}{\rm{=}}2\sqrt {\frac {3m{^{2}}+48}{(m{^{2}}+4){^{2}}}}\in (0,2\sqrt {3}]$ （当m=0时取得最大值），
13. 所以 ${\rm{|}}{\mathop {OA}\limits_{}^{\to }}{\rm{+}}{\mathop {OB}\limits_{}^{\to }}{\rm{|}}\in (0,2\sqrt {3}]$ .

## 知识点

**中文**:
  - 圆锥曲线与向量综合问题
  - 由椭圆的几何性质求方程
  - 范围最值问题

**English**:
  - Conic Sections and Vectors
  - Finding Equation from Properties
  - Range and Extrema Problems

---
