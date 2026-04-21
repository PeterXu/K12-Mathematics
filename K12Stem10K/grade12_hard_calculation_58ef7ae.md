# Mathematics - 题目 3959

**ID**: 58ef7aed041045a6b8ddd87811f3174a
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f(x)=x-\frac {1}{x}-m{\ln}x-m$ ，其中 ${\rm{e}}$ 是自然对数的底数．(1)讨论 $f\left ({x}\right )$ 的单调性；​​​​​​​‌(2)若 $m=1$ ，设关于 $x$ 的不等式 $f(x)\leqslant x{\ln}x-\frac {1}{x}-kx+n$ 对 $\forall x\in \left [1,{\rm{e}}\right ]$ 恒成立时 $k$ 的最大值为 $c\left ({k\in {\mathbf{R}},n\in \left [1,{\rm{e}}\right ]}\right )$ ，求 $n+c$ 的取值范围．

## 解答

1. （1） $f\left ({x}\right )$ 的定义域为 $\left ({0,+\infty }\right )$ ，
2. $f^{′}(x)=1+\frac {1}{x{^{2}}}-\frac {m}{x}=\frac {x{^{2}}-mx+1}{x{^{2}}}$ ，
3. 当 $m\leqslant 2$ 时， $f^{′}(x)\geqslant 0$ ， $x\in \left ({0,+\infty }\right ),f\left ({x}\right )$ 单调递增；
4. 当 ${\rm{m}}{\rm{>}}2$ 时， $f^{′}(x)=\frac {x{^{2}}-mx+1}{x{^{2}}}=0$ ，
5. $x{{}_{1}}=\frac {m-\sqrt {m{^{2}}-4}}{2},x{{}_{2}}=\frac {m+\sqrt {m{^{2}}-4}}{2}$ ，
6. $f^{′}{\left ({x}\right )}>0,x\in \left ({0,x{{}_{1}}}\right ),\left ({x{{}_{2}},+\infty }\right ),f\left ({x}\right )$ 单调递增；
7. $f^{′}{\left ({x}\right )}<0,x\in \left ({x{{}_{1}},x{{}_{2}}}\right ),f\left ({x}\right )$ 单调递减；
8. 综上，当 $m\leqslant 2$ 时， $f(x)$ 在 $(0,+\infty )$ 单调递增；
9. 当 $m{\rm{>}}{{2}}$ 时， $f(x)$ 在 $(0,\frac {m-\sqrt {m{^{2}}-4}}{2}),(\frac {m+\sqrt {m{^{2}}-4}}{2},+\infty )$ 单调递增，
10. 在 $(\frac {m-\sqrt {m{^{2}}-4}}{2},\frac {m+\sqrt {m{^{2}}-4}}{2})$ 单调递减.
11. （2）因为 $x$ 的不等式 $f(x)\leqslant x{\ln}x-\frac {1}{x}-kx+n$ 对 $\forall x\in \left [1,{\rm{e}}\right ]$ 恒成立，
12. 则 $k\leqslant \frac {(1+{\ln}x)-x+x{\ln}x+n}{x}$ ，对 $\forall x\in \left [1,{\rm{e}}\right ]$ 恒成立，
13. 令 $g(x)=\frac {1+{\ln}x-x+x{\ln}x+n}{x}$ ，
14. 即 $g^{′}(x)=\frac {-{\ln}x+x-n}{x{^{2}}}$ ，
15. 令 $p(x)=-{\ln}x+x-n$ ，即 $p^{′}(x)=-\frac {1}{x}+1>0$ ，
16. 所以 $p(x)$ 在 $x\in \left [1,{\rm{e}}\right ]$ 上递增；
17. ①当 $p(1)\geqslant 0$ ，即 $n\leqslant 1$ 时，因为 $n\in \left [1,{\rm{e}}\right ]$ ，所以 $n=1$ ，
18. 当 $x\in \left [1,{\rm{e}}\right ]$ ， $p(x)\geqslant 0$ ，即 $g^{′}(x)\geqslant 0$ ，所以 $g(x)$ 在 $\left [1,{\rm{e}}\right ]$ 上递增，
19. 所以 $c=g(x){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=g(1)=n$ ，故 $n+c=2n=2$ ；
20. ②当 $p({\rm{e}})\leqslant 0$ 即 $n\in \left [{\rm{e}}-1,{\rm{e}}\right ]$ 时，因为 $x\in \left [1,{\rm{e}}\right ]$ ， $p(x)\leqslant 0$ ，即 $g^{′}(x)\leqslant 0$ ，
21. 所以 $g(x)$ 在 $\left [1,{\rm{e}}\right ]$ 上递减，所以 $c=g(x){{}_{{\rm \min }}}=g({\rm{e}})=\frac {n+2}{{\rm{e}}}$ ，
22. 故 $n+c=\frac {n+2}{{\rm{e}}}+n\in \left [{\rm{e}}+\frac {1}{{\rm{e}}},{\rm{e}}+\frac {2}{{\rm{e}}}+1\right ]$ ；
23. ③当 $p(1)p({\rm{e}})<0$ ，即 $n\in (1,{\rm{e}}-1)$ 时，因为 $p(x)=-{\ln}x+x-n$ 在 $\left [1,{\rm{e}}\right ]$ 上递增，
24. 所以存在唯一实数 $x{{}_{0}}\in (1,{\rm{e}})$ ，使得 $p\left ({x{{}_{0}}}\right )=0$ ，即 $n=x{{}_{0}}-{\ln}x{{}_{0}}$ ，
25. 则当 $x\in \left ({1,x{{}_{0}}}\right )$ 时， $p(x)<0$ ，即 $g^{′}(x)<0$ ；当 $x\in \left ({x{{}_{0}},{\rm{e}}}\right )$ 时， $p(x)>0$ ，即 $g^{′}(x)>0$ ，
26. 故 $g(x)$ 在 $\left ({1,x{{}_{0}}}\right )$ 上单减， $\left ({x{{}_{0}},{\rm{e}}}\right )$ 上单增，
27. 所以 $c=g(x){{}_{{\rm \min }}}=g\left ({x{{}_{0}}}\right )=\frac {1+{\ln}x{{}_{0}}-x{{}_{0}}+x{{}_{0}}{\ln}x{{}_{0}}+n}{x{{}_{0}}}={\ln}x{{}_{0}}+\frac {1}{x{{}_{0}}}$ ，
28. 所以 $n+c={\ln}x{{}_{0}}+\frac {1}{x{{}_{0}}}+x{{}_{0}}-{\ln}x{{}_{0}}=x{{}_{0}}+\frac {1}{x{{}_{0}}}$ ，
29. 设 $u(x)=x{{}_{0}}+\frac {1}{x{{}_{0}}}\left ({x{{}_{0}}\in (1,{\rm{e}})}\right )$ ，则 $u^{′}(x)=1-\frac {1}{x{{}_{0}^{2}}}=\frac {x{{}_{0}^{2}}-1}{x{{}_{0}}}>0$ ，
30. 所以 $u(x)$ 在 $\left [1,{\rm{e}}\right ]$ 上递增，所以 $n+c\in \left ({2,{\rm{e}}+\frac {1}{{\rm{e}}}}\right )$ ．
31. 综上所述， $n+c\in \left [2,{\rm{e}}+\frac {2}{{\rm{e}}}+1\right ]$  ．

## 知识点

**中文**:
  - 利用导数研究函数的单调性与单调区间
  - 利用导数解决不等式恒成立问题

**English**:
  - Monotonicity and Monotonic Intervals
  - Solving Universally True Inequalities

---
