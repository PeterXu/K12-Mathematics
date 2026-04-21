# Mathematics - 题目 2674

**ID**: 9663addc31434b0196b85ddd6b1aee34
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Fill-in-the-blank

## 题目
设实数 $m>0$ ，若对任意的 $x\in [2,+\infty )$ ，不等式 $2{\rm{e}}{^{2mx}}-\frac {{\ln}x}{m}\geqslant 0$ 恒成立，则实数 $m$ 的最小值为.​​​​​​​‌

## 解答

1. 由 $m>0,x\in [2,+\infty )$ ，不等式 $2{\rm{e}}{^{2mx}}-\frac {{\ln}x}{m}\geqslant 0\Leftrightarrow 2m{\rm{e}}{^{2mx}}\geqslant {\ln}x\Leftrightarrow 2mx{\rm{e}}{^{2mx}}\geqslant x{\ln}x={\rm{e}}{^{{\ln}x}}\cdot {\ln}x$ ，
2. 又 ${\ln}x>0$ ，令 $g(x)=x{\rm{e}}{^{x}},x>0$ ，求导得 $g^{′}(x)={\rm{e}}{^{x}}+x{\rm{e}}{^{x}}=(x+1){\rm{e}}{^{x}}>0$ ， $g(x)$ 在 $(0,+\infty )$ 上单调递增，
3. 不等式 $2mx{\rm{e}}{^{2mx}}\geqslant {\rm{e}}{^{{\ln}x}}\cdot {\ln}x\Leftrightarrow g(2mx)\geqslant g({\ln}x)\Leftrightarrow 2mx\geqslant {\ln}x\Leftrightarrow 2m\geqslant \frac {{\ln}x}{x}$ ，
4. 依题意， $\forall x\in [2,+\infty )$ ， $2m\geqslant \frac {{\ln}x}{x}$ 恒成立，令 $h(x)=\frac {{\ln}x}{x},x\geqslant 2$ ，求导得 $h^{′}(x)=\frac {1-{\ln}x}{x{^{2}}}$ ，
5. 当 $2\leqslant x<{\rm{e}}$ 时， $h^{′}(x)>0$ ；当 $x>{\rm{e}}$ 时， $h^{′}(x)<0$ ， $h(x)$ 在 $[2,\mathrm{e})$ 是单调递增，在 $({\rm{e}},+\infty )$ 上单调递减，
6. 因此当 $x={\rm{e}}$ ，函数 $h(x)$ 取得最大值 $h\mathrm{(}{\rm{e}}{\rm{)}}=\frac {1}{{\rm{e}}}$ ，则 $2m\geqslant \frac {1}{{\rm{e}}}$ ，即 $m\geqslant \frac {1}{{{2}}{\rm{e}}}$ ，
7. 所以实数m的最小值为 $\frac {1}{2{\rm{e}}}$ ．

## 知识点

**中文**:
  - 利用导数解决不等式能成立问题
  - 构造同构函数问题

**English**:
  - Solving Solvable Inequality Problems
  - Constructing Isomorphic Functions

---
