# Mathematics - 题目 699

**ID**: 0bb2fee4ab584e0eb999d5e7ab33beeb
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知双曲线 $C:\frac {x{^{2}}}{a{^{2}}}-\frac {y{^{2}}}{b{^{2}}}=1$ （ $a>0$ ， $b>0$ ）的一条渐近线的倾斜角为 $\frac {{\rm{π}}}{{{3}}}{\rm ，\mathit{C}}$ 的右焦点F到该渐近线的距离为 $2\sqrt {3}$ .​​​​​​​‌(1)求C的方程；(2)若过F的直线与C的左、右支分别交于点A，B，与圆 $O:x{^{2}}+y{^{2}}=a{^{2}}$ 交于与A，B不重合的M，N两点.（ⅰ）求直线AB斜率的取值范围；（ⅱ）求 $\left |{AB}\right |\cdot \left |{MN}\right |$ 的取值范围.

## 解答

1. （1）因为C的一条渐近线的倾斜角为 $\frac {{\rm{π}}}{{{3}}}$ ，所以 $\frac {b}{a}=\sqrt {3}$ ， $b=\sqrt {3}a$ ，
2. 则C的一条渐近线的方程为 $\sqrt {3}x-y=0$ ，
3. 因为 $\sqrt {a{^{2}}+b{^{2}}}=2a$ ，
4. 所以右焦点 $F(2a,0)$ 到渐近线 $\sqrt {3}x-y=0$ 的距离为 $\frac {\left |{2\sqrt {3}a}\right |}{\sqrt {{\left({\sqrt {3}}\right)^{2}}+1{^{2}}}}=2\sqrt {3}$ ，
5. 所以 $a=2$ ， $b=2\sqrt {3}$ ，所以C的方程为 $\frac {x{^{2}}}{4}-\frac {y{^{2}}}{12}=1$ .
6. （2）（ⅰ）由（1）知， $F(4,0)$ ，设 $A\left ({x{{}_{1}},y{{}_{1}}}\right )$ ， $B\left ({x{{}_{2}},y{{}_{2}}}\right )$ ，
7. 由题意可得直线AB的斜率存在且不为零，设直线AB的方程为 $x=my+4(m\ne 0)$ ，
8. 与 $\frac {x{^{2}}}{4}-\frac {y{^{2}}}{12}=1$ 联立得 $\left ({3m{^{2}}-1}\right )y{^{2}}+24my+36=0$ ，
9. 所以 $3m{^{2}}-1\ne 0$ ， $Δ=144\left ({m{^{2}}+1}\right )>0$ ， $y{{}_{1}}+y{{}_{2}}=-\frac {24m}{3m{^{2}}-1}$ ， $y{{}_{1}}y{{}_{2}}=\frac {36}{3m{^{2}}-1}$ ，
10. 又A，B两点在x轴同一侧，所以 $y{{}_{1}}y{{}_{2}}>0$ .此时 $3m{^{2}}-1>0$ ，即 $m{^{2}}>\frac {1}{3}$ .
11. 又圆O的方程为 $x{^{2}}+y{^{2}}=4$ ，点O到直线AB的距离 $d=\frac {4}{\sqrt {m{^{2}}+1}}$ ，
12. 由 $d<2$ 得 $m{^{2}}>3$ ，由 $\begin{cases}m{^{2}}>\frac {1}{3},\\m{^{2}}>3,\end{cases}$ 得 $m{^{2}}>3$ ，所以 $m>\sqrt {3}$ 或 $m<-\sqrt {3}$ ，
13. 因为直线AB的斜率 $k=\frac {1}{m}$ ，所以直线AB斜率的取值范围是 $\left ({-\frac {\sqrt {3}}{3},0}\right )\cup \left ({0,\frac {\sqrt {3}}{3}}\right )$ .
14. 
15. （ⅱ）由弦长公式得 $\left |{AB}\right |=\sqrt {1+m{^{2}}}\left |{y{{}_{1}}-y{{}_{2}}}\right |=\sqrt {1+m{^{2}}}\cdot \sqrt {{\left({y{{}_{1}}+y{{}_{2}}}\right)^{2}}-4y{{}_{1}}y{{}_{2}}}$
16. $=\sqrt {1+m{^{2}}}\cdot \sqrt {{\left({-\frac {24m}{3m{^{2}}-1}}\right)^{2}}-4\cdot \frac {36}{3m{^{2}}-1}}=\frac {12\left ({m{^{2}}+1}\right )}{3m{^{2}}-1}$ ，
17. 由垂径定理得 $|MN|=2\sqrt {4-d{^{2}}}=4\sqrt {\frac {m{^{2}}-3}{m{^{2}}+1}}$ ，
18. 所以 $\left |{AB}\right |\cdot \left |{MN}\right |=\frac {12\left ({m{^{2}}+1}\right )}{3m{^{2}}-1}\cdot \frac {4\sqrt {m{^{2}}-3}}{\sqrt {m{^{2}}+1}}=\frac {16\sqrt {\left ({3m{^{2}}+3}\right )\left ({3m{^{2}}-9}\right )}}{3m{^{2}}-1}$ ，
19. 其中 $m{^{2}}>3$ ，设 $t=3m{^{2}}-1$ ， $t>8$ ，
20. 则 $\left |{AB}\right |\cdot \left |{MN}\right |=\frac {16\sqrt {(t+4)(t-8)}}{t}=16\sqrt {1-\frac {4}{t}-\frac {32}{t{^{2}}}}=16\sqrt {-32{\left({\frac {1}{t}+\frac {1}{16}}\right)^{2}}+\frac {9}{8}}\in (0,16)$ ，
21. 所以 $|AB|\cdot |MN|$ 的取值范围是 $(0,16)$ .

## 知识点

**中文**:
  - 由双曲线的性质探求方程
  - 直线与双曲线的位置关系
  - 范围最值问题

**English**:
  - Finding Equation from Properties
  - Line-Hyperbola Relationship
  - Range and Extrema Problems

---
