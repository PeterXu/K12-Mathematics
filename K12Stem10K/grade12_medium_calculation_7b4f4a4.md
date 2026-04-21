# Mathematics - 题目 2257

**ID**: 7b4f4a45c42a4948ba86558287de4efe
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
已知函数 $f(x)=2{\ln}x-x+\frac {m}{x}(m\in {\mathbf{R}})$ ．(1)当 $m=-3$ 时，求函数 $f(x)$ 的单调区间；​​​​​​​‌(2)若不等式 $f(x)\leqslant 0$ 对任意的 $x\in [1,+\infty )$ 恒成立，求实数m的取值范围．

## 解答

1. （1）
2. 当 $m=-3$ 时， $f(x)=2{\ln}x-x-\frac {3}{x}$ ，其定义域为 $(0,+\infty )$ ，
3. $f^{′}{\left ({x}\right )}=\frac {2}{x}-1+\frac {3}{x{^{2}}}=\frac {-x{^{2}}+2x+3}{x{^{2}}}=\frac {-\left ({x-3}\right )\left ({x+1}\right )}{x{^{2}}}$ ，
4. 令 $f^{′}{\left ({x}\right )}=0$ ，得 $x=3$ （ $x{\rm{=}}-{{1}}$ 舍去），
5. 当 $0<x<3$ 时， $f^{′}{\left ({x}\right )}>0$ ，函数 $f(x)$ 单调递增；
6. 当 $x>3$ 时， $f^{′}{\left ({x}\right )}<0$ ，函数 $f(x)$ 单调递减．
7. 所以函数 $f(x)$ 的单调递增区间为 $(0,3)$ ，单调递减区间为 $(3,+\infty )$ ；
8. （2）
9. 方法一：由条件可知 $f(1)\leqslant 0$ ，于是 $m-1\leqslant 0$ ，解得 $m\leqslant 1$ ．
10. 当 $m\leqslant 1$ 时， $f(x)=2{\ln}x-x+\frac {m}{x}\leqslant 2{\ln}x-x+\frac {1}{x}$ ，
11. 构造函数 $g(x)=2{\ln}x-x+\frac {1}{x}$ ， $x\geqslant {{1}}$ ，
12. $g^{′}{\left ({x}\right )}=\frac {2}{x}-1-\frac {1}{x{^{2}}}=-\frac {{\left({x-1}\right)^{2}}}{x{^{2}}}\leqslant 0$ ，
13. 所以函数 $g(x)$ 在 $[1,+\infty )$ 上单调递减，于是 $g(x)\leqslant g(1)=0$ ，
14. 因此实数m的取值范围是 $(-\infty ,1]$ ．
15. 方法二：由条件可知 $m\leqslant x{^{2}}-2x{\ln}x$ 对任意的 $x\in [1,+\infty )$ 恒成立，
16. 令 $h(x)=x{^{2}}-2x{\ln}x$ ， $x\geqslant {{1}}$ ，只需 $m\leqslant [h(x)]{{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}$ 即可．
17. $h^{′}{\left ({x}\right )}=2x-2\left ({{\ln}x+1}\right )=2\left ({x-{\ln}x-1}\right )$ ，
18. 令 $μ\left ({x}\right )=x-{\ln}x-1$ ，则 $μ^{′}{\left ({x}\right )}=\frac {x-1}{x}\geqslant 0$ ，
19. 所以函数 $h^{′}{\left ({x}\right )}$ 在 $[1,+\infty )$ 上单调递增，
20. 于是 $h^{′}{\left ({x}\right )}\geqslant h^{′}{\left ({1}\right )}=0$ ，所以函数 $h(x)$ 在 $[1,+\infty )$ 上单调递增，
21. 所以 $\left [h\left ({x}\right )\right ]{{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=h\left ({1}\right )=1$ ，于是 $m\leqslant 1$ ，因此实数m的取值范围是 $(-\infty ,1]$ ．

## 知识点

**中文**:
  - 利用导数研究函数的单调性与单调区间
  - 利用导数解决不等式恒成立问题

**English**:
  - Monotonicity and Monotonic Intervals
  - Solving Universally True Inequalities

---
