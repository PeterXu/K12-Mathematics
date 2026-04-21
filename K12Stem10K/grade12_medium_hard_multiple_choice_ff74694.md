# Mathematics - 题目 2457

**ID**: ff7469498ff947d29f40a47e78a98ff5
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Multiple-choice

## 题目
已知函数 $f\left ({x}\right )=\begin{cases}x{^{2}}+x+\frac {5}{4},x\leqslant 0\\2{\ln}x-ax,x>0\end{cases}$ ，若 $\forall x{{}_{2}}\leqslant 0,\exists x{{}_{1}}>0$ ，使 $f\left ({x{{}_{1}}}\right )+f\left ({x{{}_{2}}}\right )=0$ 成立，则 $a$ 的取值范围为（      ）​​​​​​​‌

## 解答

1. 当 $x\leqslant 0$ 时，函数 $f\left ({x}\right )=x{^{2}}+x+\frac {5}{4}=(x+\frac {1}{2}){^{2}}+1$ ，所以函数 $f\left ({x}\right )$ 的值域为 $[1,+\infty )$ ，
2. 当 $x>0$ 时，函数 $f\left ({x}\right )=2{\ln}x-ax$ ，可得 $f^{′}{\left ({x}\right )}=\frac {2}{x}-a$ ，
3. ①当 $a>0$ 时，令 $f^{′}{\left ({x}\right )}=0$ ，解得 $x=\frac {2}{a}$ ，
4. 当 $x\in (\frac {2}{a},+\infty )$ 时， $f^{′}{\left ({x}\right )}<0$ ， $f\left ({x}\right )$ 单调递减；
5. 当 $x\in (0,\frac {2}{a})$ 时， $f^{′}{\left ({x}\right )}>0$ ， $f\left ({x}\right )$ 单调递增，
6. 所以 $f\left ({x}\right )\leqslant f(\frac {2}{a})=2{\ln}\frac {2}{a}-2$ ，
7. 因为对 $\forall x{{}_{2}}\leqslant 0,\exists x{{}_{1}}>0$ ，使 $f\left ({x{{}_{1}}}\right )+f\left ({x{{}_{2}}}\right )=0$ 成立，转化为 $f\left ({x{{}_{1}}}\right )$ 值域包含 $-f\left ({x{{}_{2}}}\right )$ 的值域，
8. 所以 $2{\ln}\frac {2}{a}-2\geqslant -1$ ，即 ${\ln}\frac {2}{a}\geqslant \frac {1}{2}$ ，解得 $a\leqslant \frac {2}{\sqrt {e}}=\frac {2\sqrt {e}}{e}$ ，所以 $0<a\leqslant \frac {2\sqrt {e}}{e}$ ；
9. ②当 $a\leqslant 0$ 时，令 $f^{′}{\left ({x}\right )}=\frac {2}{x}-a>0$ ，解得 $x=\frac {2}{a}$ ，
10. 当 $x\in (\frac {2}{a},+\infty )$ 时， $f^{′}{\left ({x}\right )}<0$ ， $f\left ({x}\right )$ 单调递增，此时值域为 $\mathbf{R}$ ，
11. 满足对 $\forall x{{}_{2}}\leqslant 0,\exists x{{}_{1}}>0$ ，使 $f\left ({x{{}_{1}}}\right )+f\left ({x{{}_{2}}}\right )=0$ 成立，
12. 综上所述，实数 $a$ 的取值范围为 $(-\infty ,\frac {2\sqrt {e}}{e}]$ .
13. 故选：A.

## 知识点

**中文**:
  - 与函数有关的参数问题
  - 与函数有关的恒成立问题
  - 利用导数研究函数的最值

**English**:
  - Parameter Problems Related to Functions
  - Universally True Problems Related to Functions
  - Global Extrema (Max/Min) using Derivatives

---
