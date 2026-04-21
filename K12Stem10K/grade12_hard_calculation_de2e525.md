# Mathematics - 题目 3468

**ID**: de2e525628fb4c629103a4af8015581f
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
洛必达法则对导数的研究产生了深远的影响.​​​​​​​‌洛必达法则：给定两个函数 $F\left ({x}\right ),G\left ({x}\right )$ ，当 $F\left ({x{{}_{0}}}\right )=0,G\left ({x{{}_{0}}}\right )=0$ 时， ${\mathop {{\rm \lim }}\limits_{x\to x{{}_{0}}}^{}}\frac {F(x)}{G(x)}={\mathop {{\rm \lim }}\limits_{x\to x{{}_{0}}}^{}}\frac {F{^{\prime }}(x)}{G{^{\prime }}(x)}$ .已知函数 $f\left ({x}\right )=\frac {1}{6}ax{^{3}}+{\rm{s}}{\rm{i}}{\rm{n}}x-x$ ， $h\left ({x}\right )=3{\rm{s}}{\rm{i}}{\rm{n}}x-x{\rm{c}}{\rm{o}}{\rm{s}}x-2x$ .(1)证明： $h\left ({x}\right )$ 在区间 $\left [0,2{\rm{π}}\right ]$ 上单调递减；(2)对于 $x\in \left [0,2{\rm{π}}\right ],f\left ({x}\right )\geqslant 0$ 恒成立，求实数 $a$ 的取值范围；(3) $\forall n\in \mathbf{N}{^{{\rm{*}}}}$ ，证明： ${\rm{c}}{\rm{o}}{\rm{s}}\frac {1}{{\rm{e}}}+{\rm{c}}{\rm{o}}{\rm{s}}\frac {1}{{\rm{e}}{^{2}}}+\cdots +{\rm{c}}{\rm{o}}{\rm{s}}\frac {1}{{\rm{e}}{^{n}}}>n-\frac {1}{12}$ （附： ${\rm{e}}\approx 2.718,{\rm{e}}{^{2}}\approx 7.389$ ）.

## 解答

1. （1） $h\left ({x}\right )=3{\rm{s}}{\rm{i}}{\rm{n}}x-x{\rm{c}}{\rm{o}}{\rm{s}}x-2x,\therefore h^{′}{\left ({x}\right )}=2{\rm{c}}{\rm{o}}{\rm{s}}x+x{\rm{s}}{\rm{i}}{\rm{n}}x-2$ ，
2. 令 $m\left ({x}\right )=2{\rm{c}}{\rm{o}}{\rm{s}}x+x{\rm{s}}{\rm{i}}{\rm{n}}x-2$ ，则 $m^{′}{\left ({x}\right )}=-{\rm{s}}{\rm{i}}{\rm{n}}x+x{\rm{c}}{\rm{o}}{\rm{s}}x$ ，
3. 令 $n\left ({x}\right )=-{\rm{s}}{\rm{i}}{\rm{n}}x+x{\rm{c}}{\rm{o}}{\rm{s}}x$ ，则 $n^{′}{\left ({x}\right )}=-x{\rm{s}}{\rm{i}}{\rm{n}}x$ ，
4. 若 $x\in \left [0,{\rm{π}}\right ]$ ，则 $n^{′}{\left ({x}\right )}\leqslant 0,\therefore n\left ({x}\right )$ 单调递减， $n\left ({x}\right )\leqslant n\left ({0}\right )=0,\therefore m\left ({x}\right )$ 单调递减， $m\left ({x}\right )\leqslant m\left ({0}\right )=0$ ， $\therefore h\left ({x}\right )$ 在 $\left [0,{\rm{π}}\right ]$ 上单调递减，
5. 若 $x\in \left ({{\rm{π}},2{\rm{π}}}\right ]$ ，则 $n^{′}{\left ({x}\right )}\geqslant 0,\therefore n\left ({x}\right )$ 单调递增， $\therefore n\left ({{\rm{π}}}\right )<n\left ({x}\right )\leqslant n\left ({2{\rm{π}}}\right )$ ，即 $-{\rm{π}}<n\left ({x}\right )\leqslant 2{\rm{π}},$
6. $\therefore $ 存在唯一 $x{{}_{0}}\in \left ({{\rm{π}},2{\rm{π}}}\right )$ ，使得 $n\left ({x{{}_{0}}}\right )=0$ ，且在 $\left ({{\rm{π}},x{{}_{0}}}\right )$ 上， $n\left ({x}\right )<0,m\left ({x}\right )$ 单调递减，在 $\left ({x{{}_{0}},2{\rm{π}}}\right ]$ 上， $n\left ({x}\right )>0,m\left ({x}\right )$ 单调递增，
7. 且 $m\left ({{\rm{π}}}\right )=-4<0,m\left ({2{\rm{π}}}\right )=0,\therefore m\left ({x}\right )\leqslant 0$ ，
8. $\therefore h\left ({x}\right )$ 在区间 $\left ({{\rm{π}},2{\rm{π}}}\right ]$ 上单调递减，且 $h\left ({x}\right )$ 在 $\left [0,2{\rm{π}}\right ]$ 上连续，
9. 综上， $h\left ({x}\right )$ 在区间 $\left [0,2{\rm{π}}\right ]$ 上单调递减.
10. （2）当 $x=0$ 时， $f\left ({0}\right )=0$ 成立.当 $0<x\leqslant 2{\rm{π}}$ 时，由 $f\left ({x}\right )\geqslant 0$ 可得 $\frac {1}{6}a\geqslant \frac {x-{\rm{s}}{\rm{i}}{\rm{n}}x}{x{^{3}}}$ ，
11. 令 $g\left ({x}\right )=\frac {x-{\rm{s}}{\rm{i}}{\rm{n}}x}{x{^{3}}},\therefore g^{′}{\left ({x}\right )}=\frac {3{\rm{s}}{\rm{i}}{\rm{n}}x-x{\rm{c}}{\rm{o}}{\rm{s}}x-2x}{x{^{4}}}=\frac {h\left ({x}\right )}{x{^{4}}}$ ，
12. 由（1）可知 $h\left ({x}\right )\leqslant h\left ({0}\right )=0,\therefore g^{′}{\left ({x}\right )}\leqslant 0,\therefore g\left ({x}\right )$ 在 $\left ({0,2{\rm{π}}}\right ]$ 上单调递减， $g(x)<{\mathop {{\rm \lim }}\limits_{x\to 0}^{}}g(x)$ .
13. 由洛必达法则： ${\mathop {{\rm \lim }}\limits_{x\to 0}^{}}g(x)={\mathop {{\rm \lim }}\limits_{x\to 0}^{}}\frac {x-{\rm{s}}{\rm{i}}{\rm{n}}x}{x{^{3}}}={\mathop {{\rm \lim }}\limits_{x\to 0}^{}}\frac {1-{\rm{c}}{\rm{o}}{\rm{s}}x}{3x{^{2}}}={\mathop {{\rm \lim }}\limits_{x\to 0}^{}}\frac {{\rm{s}}{\rm{i}}{\rm{n}}x}{6x}={\mathop {{\rm \lim }}\limits_{x\to 0}^{}}\frac {{\rm{c}}{\rm{o}}{\rm{s}}x}{6}=\frac {1}{6}$ ，
14. $\therefore \frac {1}{6}a\geqslant \frac {1}{6},\therefore a\geqslant 1$ .
15. （3）当 $a=1$ 且 $x\geqslant 0$ 时， $f^{′}{\left ({x}\right )}=\frac {1}{2}x{^{2}}+{\rm{c}}{\rm{o}}{\rm{s}}x-1$ ，令 $G\left ({x}\right )=\frac {1}{2}x{^{2}}+{\rm{c}}{\rm{o}}{\rm{s}}x-1$ ，
16. 则 $G^{′}{\left ({x}\right )}=x-{\rm{s}}{\rm{i}}{\rm{n}}x$ ，令 $H\left ({x}\right )=x-{\rm{s}}{\rm{i}}{\rm{n}}x$ ，则 $H^{′}{\left ({x}\right )}=1-{\rm{c}}{\rm{o}}{\rm{s}}x\geqslant 0$ ，
17. $\therefore G^{′}{\left ({x}\right )}$ 在 $\left [{0,+\infty }\right )$ 上单调递增， $\therefore G^{′}{\left ({x}\right )}\geqslant G^{′}{\left ({0}\right )}=0$ ，
18. 即 $G\left ({x}\right )$ 在 $\left [{0,+\infty }\right )$ 上单调递增， $G\left ({x}\right )\geqslant G\left ({0}\right )=0,\therefore {\rm{c}}{\rm{o}}{\rm{s}}x\geqslant 1-\frac {1}{2}x{^{2}}$ （当 $x=0$ 时取等号），
19. $\therefore {\rm{c}}{\rm{o}}{\rm{s}}\frac {1}{{\rm{e}}{^{n}}}>1-\frac {1}{2{\rm{e}}{^{2n}}}$ ，
20. $\therefore {\rm{c}}{\rm{o}}{\rm{s}}\frac {1}{{\rm{e}}}+{\rm{c}}{\rm{o}}{\rm{s}}\frac {1}{{\rm{e}}{^{2}}}+\cdots +{\rm{c}}{\rm{o}}{\rm{s}}\frac {1}{{\rm{e}}{^{n}}}>n-\frac {1}{2}\left ({\frac {1}{{\rm{e}}{^{2}}}+\frac {1}{{\rm{e}}{^{4}}}+\cdots +\frac {1}{{\rm{e}}{^{2n}}}}\right )=n-\frac {1}{2}\cdot \frac {\frac {1}{{\rm{e}}{^{2}}}\left ({1-\frac {1}{{\rm{e}}{^{2n}}}}\right )}{1-\frac {1}{{\rm{e}}{^{2}}}}=n-\frac {1-\frac {1}{{\rm{e}}{^{2n}}}}{2{\rm{e}}{^{2}}-2}$ ，
21. $\because \frac {1-\frac {1}{{\rm{e}}{^{2n}}}}{2{\rm{e}}{^{2}}-2}<\frac {1}{2{\rm{e}}{^{2}}-2}<\frac {1}{12}$ ，
22. $\therefore n-\frac {1-\frac {1}{{\rm{e}}{^{2n}}}}{2{\rm{e}}{^{2}}-2}>n-\frac {1}{12}$ ，
23. 即 ${\rm{c}}{\rm{o}}{\rm{s}}\frac {1}{{\rm{e}}}+{\rm{c}}{\rm{o}}{\rm{s}}\frac {1}{{\rm{e}}{^{2}}}+\cdots +{\rm{c}}{\rm{o}}{\rm{s}}\frac {1}{{\rm{e}}{^{n}}}>n-\frac {1}{12}$ .

## 知识点

**中文**:
  - 利用导数研究函数的单调性与单调区间
  - 利用导数证明不等式
  - 利用导数解决不等式恒成立问题
  - 利用导数解决新定义问题

**English**:
  - Monotonicity and Monotonic Intervals
  - Proving Inequalities using Derivatives
  - Solving Universally True Inequalities
  - Solving New Definition Problems

---
