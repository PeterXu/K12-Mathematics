# Mathematics - 题目 1433

**ID**: 8a44b4b741be49f298a7ec353965d790
**年级**: Grade 11
**难度**: Medium
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=2{\ln}x-2ax$ ， $g\left ({x}\right )=ax{^{2}}-2x-2\left ({a\in {\mathbf{R}}}\right )$ .​​​​​​​‌（1）若 $a=\frac {1}{2}$ ，求函数 $f\left ({x}\right )$ 的极值；（2）若 $a\in {\mathbf{Z}}$ ，且不等式 $f\left ({x}\right )\leqslant g\left ({x}\right )$ 在 $\left ({0,+\infty }\right )$ 上恒成立，求a的最小值.

## 解答

1. （1）当 $a=\frac {1}{2}$ 时， $f\left ({x}\right )=2{\ln}x-x$ ， $x>0$ .
2. 所以 $f^{′}{\left ({x}\right )}=\frac {2}{x}-1=\frac {2-x}{x}$ ， $x>0$ .
3. 由 $f^{′}{\left ({x}\right )}>0$  $\Rightarrow $  $0<x<2$ ；由 $f^{′}{\left ({x}\right )}<0$  $\Rightarrow $  $x>2$ .
4. 所以 $f\left ({x}\right )$ 在 $\left ({0,2}\right )$ 上单调递增，在 $\left ({2,+\infty }\right )$ 上单调递减.
5. 所以当 $x=2$ 时，函数 $f\left ({x}\right )$ 有极大值，为 $f\left ({2}\right )=2{\ln}2-2$ ，无极小值.
6. （2）因为 $a\in {\mathbf{Z}}$ ，且不等式 $f\left ({x}\right )\leqslant g\left ({x}\right )$ 在 $\left ({0,+\infty }\right )$ 上恒成立，
7. 所以 $2{\ln}x-2ax\leqslant ax{^{2}}-2x-2$ 在 $\left ({0,+\infty }\right )$ 上恒成立.
8. 即 $ax{^{2}}+2ax\geqslant 2{\ln}x+2x+2$ 在 $\left ({0,+\infty }\right )$ 上恒成立.
9. 设 $h\left ({x}\right )=x-{\ln}x-1$ ， $x>0$ .
10. 则 $h^{′}{\left ({x}\right )}=1-\frac {1}{x}=\frac {x-1}{x}$ .
11. 由 $h^{′}{\left ({x}\right )}>0$  $\Rightarrow $  $x>1$ ；由 $h^{′}{\left ({x}\right )}<0$  $\Rightarrow $  $0<x<1$ .
12. 所以 $h\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上单调递减，在 $\left ({1,+\infty }\right )$ 上单调递增.
13. 所以 $h\left ({1}\right )$ 是函数 $h\left ({x}\right )$ 的最小值，且 $h\left ({1}\right )=0$ .
14. 所以 $x-{\ln}x-1\geqslant 0$ 在 $\left ({0,+\infty }\right )$ 上恒成立.所以 $x\geqslant {\ln}x+1$  $\Rightarrow $  $4x\geqslant 2{\ln}x+2x+2$ .
15. 所以 $ax{^{2}}+2ax\geqslant 4x$ 在 $\left ({0,+\infty }\right )$ 上恒成立.
16. 所以 $ax{^{2}}+\left ({2a-4}\right )x\geqslant 0$  $\Rightarrow $  $\begin{cases}a>0，\\\frac {4-2a}{2a}\leqslant 0\end{cases}$  $\Rightarrow $  $a\geqslant 2$ .
17. 又 $a\in {\mathbf{Z}}$ ，所以 $a$ 的最小值为2.

## 知识点

**中文**:
  - 利用导数研究函数的极值
  - 利用导数解决不等式恒成立问题

**English**:
  - Extrema of Functions using Derivatives
  - Solving Universally True Inequalities

---
