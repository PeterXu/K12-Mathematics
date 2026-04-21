# Mathematics - 题目 37

**ID**: 78c80cc6f9cc42aca5fdf782ad4940c2
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Fill-in-the-blank

## 题目
$\forall x\in (0,+\infty )$ ，不等式 ${\rm{e}}{^{x}}+1\geqslant 2\left ({a{^{2}}x+\frac {1}{x}}\right ){\ln}(ax)$ 恒成立，则正实数 $a$ 的最大值是．​​​​​​​‌

## 解答

1. 将不等式 ${\rm{e}}{^{x}}+1\geqslant 2\left ({a{^{2}}x+\frac {1}{x}}\right ){\ln}(ax)$ 变形可得 $x\left ({{\rm{e}}{^{x}}+1}\right )\geqslant \left ({a{^{2}}x{^{2}}+1}\right ){\ln}{\left({ax}\right)^{2}}$ ，
2. 即 $\left ({{\rm{e}}{^{x}}+1}\right ){\ln}{\rm{e}}{^{x}}\geqslant \left [{\left({ax}\right)^{2}}+1\right ]{\ln}{\left({ax}\right)^{2}}$ ，
3. 构造函数 $f\left ({x}\right )=\left ({x+1}\right ){\ln}x$ ，可得 $f^{′}{\left ({x}\right )}={\ln}x+\left ({x+1}\right )\cdot \frac {1}{x}={\ln}x+\frac {1}{x}+1$ ；
4. 令 $g\left ({x}\right )=f^{′}{\left ({x}\right )}={\ln}x+\frac {1}{x}+1$ ，则 $g^{′}{\left ({x}\right )}=\frac {1}{x}-\frac {1}{x{^{2}}}=\frac {x-1}{x{^{2}}}$ ；
5. 所以当 $x\in \left ({0,1}\right )$ 时， $g^{′}{\left ({x}\right )}=\frac {x-1}{x{^{2}}}<0$ ，即 $g\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上单调递减；
6. 当当 $x\in \left ({1,+\infty }\right )$ 时， $g^{′}{\left ({x}\right )}=\frac {x-1}{x{^{2}}}>0$ ，即 $g\left ({x}\right )$ 在 $\left ({1,+\infty }\right )$ 上单调递增，
7. 所以 $g\left ({x}\right )\geqslant g\left ({1}\right )=2$ ，即 $f^{′}{\left ({x}\right )}\geqslant 2$ ，所以函数 $f\left ({x}\right )$ 在 $\left ({0,+\infty }\right )$ 上单调递增，
8. 利用单调性并根据 $\left ({{\rm{e}}{^{x}}+1}\right ){\ln}{\rm{e}}{^{x}}\geqslant \left [{\left({ax}\right)^{2}}+1\right ]{\ln}{\left({ax}\right)^{2}}$ 可得 ${\rm{e}}{^{x}}\geqslant {\left({ax}\right)^{2}}$ ，
9. 即可得 ${\rm{e}}{^{\frac {x}{2}}}\geqslant ax$ ，即 $a\leqslant \frac {{\rm{e}}{^{\frac {x}{2}}}}{x}$ 对 $\forall x\in (0,+\infty )$ 恒成立，因此 $a\leqslant \left ({\frac {{\rm{e}}{^{\frac {x}{2}}}}{x}}\right ){{}_{{\rm \min }}}$ 即可；
10. 令 $h\left ({x}\right )=\frac {{\rm{e}}{^{\frac {x}{2}}}}{x},x\in (0,+\infty )$ ，则 $h^{′}{\left ({x}\right )}=\frac {\frac {1}{2}x{\rm{e}}{^{\frac {x}{2}}}-{\rm{e}}{^{\frac {x}{2}}}}{x{^{2}}}=\frac {{\rm{e}}{^{\frac {x}{2}}}\left ({\frac {1}{2}x-1}\right )}{x{^{2}}}$ ，
11. 显然当 $x\in \left ({0,2}\right )$ 时， $h^{′}{\left ({x}\right )}<0$ ，即函数 $h\left ({x}\right )$ 在 $\left ({0,2}\right )$ 上单调递减，
12. 当 $x\in \left ({2,+\infty }\right )$ 时， $h^{′}{\left ({x}\right )}>0$ ，即函数 $h\left ({x}\right )$ 在 $\left ({2,+\mathrm{∞}}\right )$ 上单调递增，
13. 所以 $h\left ({x}\right ){{}_{{\rm \min }}}=h\left ({2}\right )=\frac {{\rm{e}}}{2}$ ，即 $a\leqslant \left ({\frac {{\rm{e}}{^{\frac {x}{2}}}}{x}}\right ){{}_{{\rm \min }}}=\frac {{\rm{e}}}{2}$ ，
14. 因此正实数 $a$ 的最大值是 $\frac {{\rm{e}}}{2}$ .
15. 故答案为： $\frac {{\rm{e}}}{2}$ .

## 知识点

**中文**:
  - 构造同构函数问题

**English**:
  - Constructing Isomorphic Functions

---
