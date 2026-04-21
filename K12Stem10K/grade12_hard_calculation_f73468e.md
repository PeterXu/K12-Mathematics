# Mathematics - 题目 1836

**ID**: f73468e6b8e94df6bcf81ff051df88fc
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f(x)={\rm{e}}{^{x-1}}$ .​​​​​​​‌（1）若 $\forall x\in {\mathbf{R}}$ ， $af(x)\geqslant x$ ，求实数a的取值集合；（2）设 $g{{}_{n}}(x)=xf(x)-n$ ，${\rm （i）}$ 对任意正整数n，证明：函数 $g{{}_{n}}(x)$ 有唯一的零点（记零点为 $x{{}_{n}}$ ）；${\rm （ii）}$ 证明： $2(\sqrt {n+1}-1)<\frac {1}{x{{}_{1}}}+\frac {1}{x{{}_{2}}}+\cdots +\frac {1}{x{{}_{n}}}\leqslant \frac {1}{2}(n+1+{\ln}n)$ .

## 解答

1. （1）由 $af(x)\geqslant x$ 可得 $a\geqslant x{\rm{e}}{^{1-x}}$ ，
2. 记 $h\left ({x}\right )=x{\rm{e}}{^{1-x}}$ ，则 $h^{′}{\left ({x}\right )}=\left ({1-x}\right ){\rm{e}}{^{1-x}}$ ，
3. 当 $x<1$ 时， $h^{′}(x)>0{\rm{,}}$ 此时 $h(x)$ 在 $\left ({-\infty ,1}\right )$ 上单调递增，当 $x>1$ 时， $h^{′}(x)<0{\rm{,}}$ 此时 $h(x)$ 在 $\left ({1,+\infty }\right )$ 上单调递减，
4. 故当 $x=1$ 时， $h\left ({x}\right )$ 取到最大值，且最大值为 $h\left ({1}\right )=1$ ，故 $a\geqslant 1$ ，
5. 实数a的取值集合为 $\left [{1,+\infty }\right )$ .
6. （2）（i）证明： $g{{}_{n}}\left ({x}\right )=x{\rm{e}}{^{x-1}}-n{\rm{,}}$ 则 $g{{}_{n}}{^{\prime }}\left ({x}\right )=\left ({x+1}\right ){\rm{e}}{^{x-1}}$ ，
7. 当 $x\leqslant -1$ 时，由 $x<0,{\rm{e}}{^{x-1}}>0,n>0$ 得 $g{{}_{n}}\left ({x}\right )<0$ ，此时 $g{{}_{n}}(x)$ 无零点，不符合题意，
8. 当 $x>-1$ 时， $g{{}_{n}}{^{\prime }}\left ({x}\right )>0,g{{}_{n}}\left ({x}\right )$ 单调递增，
9. 由于 $g{{}_{n}}\left ({-1}\right )=-{\rm{e}}{^{-2}}-n<-{\rm{e}}{^{-2}}<0$ ， $g{{}_{n}}\left ({n+1}\right )=\left ({n+1}\right ){\rm{e}}{^{n}}-n>n+1-n>0$ ，
10. 故 $g{{}_{n}}(x)$ 在 $\left [{-1,+\infty }\right )$ 有唯一的零点，
11. 综上可知：对任意正整数n，证明：函数 $g{{}_{n}}(x)$ 有唯一的零点，
12. ${\rm （ii）}$ 设 $m(x)={\ln}x-x+1$ ， $m^{′}(x)=\frac {1}{x}-1$ ，
13. 则当 $x>1$ 时， $m{^{\prime }}(x)<0$ ， $m\left ({x}\right )$ 在 $\left ({1,+\infty }\right )$ 单调递减，
14. 当 $0<x<1$ 时， $m^{′}(x)>0,m\left ({x}\right )$ 在 $\left ({0,1}\right )$ 单调递增，
15. 故 $m(x)\leqslant m\left ({1}\right )=0$ ，故 ${\ln}x\leqslant x-1,$ 当且仅当 $x=1$ 时取等号，
16. 由 $g{{}_{n}}\left ({x{{}_{n}}}\right )=x{{}_{n}}{\rm{e}}{^{x{{}_{n}}-1}}-n=0$ 得 $x{{}_{n}}-1+{\ln}x{{}_{n}}={\ln}n$ ，
17. 故 ${\ln}n=x{{}_{n}}-1+{\ln}x{{}_{n}}\geqslant {\ln}x{{}_{n}}+{\ln}x{{}_{n}}=2{\ln}x{{}_{n}}$ ，
18. 所以 ${\ln}n\geqslant 2{\ln}x{{}_{n}}$ ，则 $x{{}_{n}^{2}}\leqslant n\Rightarrow x{{}_{n}}\leqslant \sqrt {n}$ ，
19. 又因为 $\sqrt {n}<\frac {\sqrt {n}+\sqrt {n+1}}{2}$ ，所以 $\frac {1}{x{{}_{n}}}>\frac {2}{\sqrt {n}+\sqrt {n+1}}=2\left ({\sqrt {n+1}-\sqrt {n}}\right ),$
20. 即 $\frac {1}{x{{}_{1}}}+\frac {1}{x{{}_{2}}}+\cdots +\frac {1}{x{{}_{n}}}>2\left ({\sqrt {2}-\sqrt {1}}\right )+2\left ({\sqrt {3}-\sqrt {2}}\right )+\cdots +2\left ({\sqrt {n+1}-\sqrt {n}}\right )=2\left ({\sqrt {n+1}-1}\right )$ ，
21. 再由 $x-1\geqslant {\rm{l}}{\rm{n}}x$ 可得 $\frac {x{{}_{n}}}{n}-1\geqslant {\ln}\frac {x{{}_{n}}}{n}={\ln}x{{}_{n}}-{\ln}n$ ，当且仅当 $x{{}_{n}}=n$ 时取等号，
22. 由 $x{{}_{n}}-1+{\ln}x{{}_{n}}={\ln}n$ 得 ${\ln}x{{}_{n}}-{\ln}n=1-x{{}_{n}}$ ，
23. ${\ln}x{{}_{n}}-{\ln}n=1-x{{}_{n}}\leqslant \frac {x{{}_{n}}}{n}-1$ ，即 $\frac {\left ({n+1}\right )x{{}_{n}}}{n}\geqslant 2$ ，则 $\frac {1}{x{{}_{n}}}\leqslant \frac {1}{2}\left ({1+\frac {1}{n}}\right )$ ，
24. 当且仅当 $n=1$ 时取等号，
25. 当 $n\mathrm{\geqslant }2$ 时，
26. $\frac {1}{x{{}_{1}}}+\frac {1}{x{{}_{2}}}+\cdots +\frac {1}{x{{}_{n}}}<\frac {1}{2}\left ({1+1}\right )+\frac {1}{2}\left ({1+\frac {1}{2}}\right )+\cdots +\frac {1}{2}\left ({1+\frac {1}{n}}\right )=\frac {n}{2}+\frac {1}{2}\left ({1+\frac {1}{2}+\frac {1}{3}+\cdots +\frac {1}{n}}\right )$ ，
27. 由 $x-1\geqslant {\rm{l}}{\rm{n}}x$ 得 $\frac {1}{x}-1\geqslant {\ln}\frac {1}{x}\Rightarrow 1-\frac {1}{x}\leqslant {\ln}x\Rightarrow 1-\frac {n-1}{n}<{\ln}\frac {n}{n-1}\Rightarrow \frac {1}{n}<{\ln}\frac {n}{n-1},\left ({n\geqslant 2}\right )$ ，
28. 所以 $1+\frac {1}{2}+\frac {1}{3}+\cdots +\frac {1}{n}<1+{\ln}\frac {2}{1}+{\ln}\frac {3}{2}+{\ln}\frac {4}{3}+\cdots +{\ln}\frac {n}{n-1}=1+{\ln}n$ ，
29. 故 $\frac {1}{x{{}_{1}}}+\frac {1}{x{{}_{2}}}+\cdots +\frac {1}{x{{}_{n}}}<\frac {n}{2}+\frac {1}{2}\left ({1+\frac {1}{2}+\frac {1}{3}+\cdots +\frac {1}{n}}\right )<\frac {n}{2}+\frac {1}{2}\left ({1+{\ln}n}\right )=\frac {1}{2}\left ({n+1+{\ln}n}\right )$ ，
30. 则 $2(\sqrt {n+1}-1)<\frac {1}{x{{}_{1}}}+\frac {1}{x{{}_{2}}}+\cdots +\frac {1}{x{{}_{n}}}\leqslant \frac {1}{2}(n+1+{\ln}n)$ ,当且仅当 $n=1$ 时取等号，

## 知识点

**中文**:
  - 利用导数解决不等式恒成立问题
  - 利用导数证明不等式
  - 利用导数解决函数零点问题

**English**:
  - Solving Universally True Inequalities
  - Proving Inequalities using Derivatives
  - Solving Zero Point Problems

---
