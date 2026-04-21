# Mathematics - 题目 1066

**ID**: e2579d3e49a24b7aa6e730ef7798cf53
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f(x)={\rm{e}}{^{ax}}-x-1(a>0)$ .​​​​​​​‌(1)当 $a=2$ 时，求曲线 $y=f(x)$ 在点 $(0,f(0))$ 处的切线方程；(2)若对任意 $x\in [0,+\infty )$ ，都有 $f(x)\geqslant 0$ ，求实数 $a$ 的取值范围；(3)求证：存在实数 $a$ ，使方程 $f(x)+\frac {1}{2}=0$ 有正实根.

## 解答

1. （1）当 $a=2$ 时，函数 $f(x)={\rm{e}}{^{2x}}-x-1$ ，求导得 $f^{′}(x)=2{\rm{e}}{^{2x}}-1$ ，则 $f{^{\prime }}(0)=1$ ，而 $f(0)=0$ ，
2. 所以曲线 $y=f(x)$ 在点 $(0,f(0))$ 处的切线方程为 $y=x$ .
3. （2）对任意 $x\in [0,+\infty )$ ，不等式 $f(x)\geqslant 0\Leftrightarrow {\rm{e}}{^{ax}}-x-1\geqslant 0\Leftrightarrow {\rm{e}}{^{ax}}\geqslant x+1$ ，
4. 当 $x\geqslant 0$ 时，令 $y={\rm{e}}{^{x}}-x-1$ ，求导得 $y^{′}={\rm{e}}{^{x}}-1\geqslant 0$ ，函数 $y={\rm{e}}{^{x}}-x-1$ 在 $[0,+\infty )$ 上递增，
5. $y{{}_{{\rm \min }}}=0$ ，所以 ${\rm{e}}{^{x}}\geqslant x+1$ ，当 $a\geqslant 1$ 时， $\forall x\in [0,+\infty )$ ， ${\rm{e}}{^{ax}}\geqslant {\rm{e}}{^{x}}\geqslant x+1$ ，即 $f(x)\geqslant 0$ 恒成立，则 $a\geqslant 1$ ；
6. 当 $0<a<1$ 时， $f^{′}(x)=a{\rm{e}}{^{ax}}-1$ ，由 $f^{′}(x)=0$ ，得 $x=\frac {1}{a}{\ln}\frac {1}{a}$ ，
7. 当 $0<x<\frac {1}{a}{\ln}\frac {1}{a}$ 时， $f^{′}(x)<0$ ，函数 $f(x)$ 在 $(0,\frac {1}{a}{\ln}\frac {1}{a})$ 上单调递减， $f(x)<f(0)=0$ ，不符合题意，
8. 所以实数 $a$ 的取值范围是 $a\geqslant 1$ .
9. （3）证明：由 $x>0$ ， $f(x)+\frac {1}{2}=0$ ，得 ${\rm{e}}{^{ax}}-x-\frac {1}{2}=0\Leftrightarrow {\rm{e}}{^{ax}}=x+\frac {1}{2}\Leftrightarrow a=\frac {{\ln}(x+\frac {1}{2})}{x}$ ，
10. 令 $g(x)=\frac {{\ln}(x+\frac {1}{2})}{x},x>0$ ，求导得 $g^{′}(x)=\frac {\frac {x}{x+\frac {1}{2}}-{\ln}(x+\frac {1}{2})}{x{^{2}}}$ ，
11. 令 $h(x)=\frac {x}{x+\frac {1}{2}}-{\ln}(x+\frac {1}{2}),x>0$ ，求导得 $h^{′}(x)=\frac {\frac {1}{2}}{(x+\frac {1}{2}){^{2}}}-\frac {1}{x+\frac {1}{2}}=-\frac {x}{(x+\frac {1}{2}){^{2}}}<0$ ，
12. 函数 $h(x)$ 在 $(0,+\infty )$ 上单调递减，而 $h\left ({1}\right )=\frac {2}{3}-{\ln}\frac {3}{2}>\frac {2}{3}-{\ln}\sqrt {{\rm{e}}}=\frac {2}{3}-\frac {1}{2}>0,h\left ({3}\right )=\frac {6}{7}-{\ln}\frac {7}{2}<0$ ，
13. 则存在 $x{{}_{0}}\in (1,3)$ ，使得 $h(x{{}_{0}})=0$ ，当 $0<x<x{{}_{0}}$ 时， $h(x)>0$ ，即 $g^{′}(x)>0$ ，
14. 函数 $g(x)$ 在 $(0,x{{}_{0}})$ 上单调递增， $g(x{{}_{0}})>g(\frac {1}{2})=0$ ，取正数 $a\leqslant g(x{{}_{0}})$ ，
15. 则直线 $y=a$ 与函数 $y=g(x)$ 在 $(0,x{{}_{0}})$ 上的图象有交点，此交点横坐标在区间 $(\frac {1}{2},x{{}_{0}}]$ ，
16. 所以存在实数 $a$ ，使方程 $f(x)+\frac {1}{2}=0$ 有正实根.

## 知识点

**中文**:
  - 利用导数研究方程的根
  - 导数几何意义的应用
  - 利用导数解决不等式恒成立问题

**English**:
  - Studying Equation Roots
  - Applications of Geometric Meaning of Derivatives
  - Solving Universally True Inequalities

---
