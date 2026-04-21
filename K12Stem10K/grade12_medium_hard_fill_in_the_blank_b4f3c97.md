# Mathematics - 题目 1146

**ID**: b4f3c972b2314252aa2f5f87288f3b75
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Fill-in-the-blank

## 题目
已知函数 $f\left ({x}\right )=\left ({2-a}\right )x{\ln}x-2ax{^{2}}-\left ({a{^{2}}-4a}\right )x$ ，若存在 $x\in \left ({0,+\infty }\right )$ ，使得 $f\left ({x}\right )\geqslant 1$ ，则实数 $a$ 的取值范围是.​​​​​​​‌

## 解答

1. 设 $h\left ({t}\right )=\left ({t-2}\right ){\ln}t-t{^{2}}+3t$ ，则 $h^{′}{\left ({t}\right )}={\ln}t+1-\frac {2}{t}-2t+3$ ， $h^{′}{{^{\prime }}}\left ({t}\right )=\frac {1}{t}+\frac {2}{t{^{2}}}-2=-\frac {2t{^{2}}-t-2}{t{^{2}}}$ .
2. 故对 $0<t<\frac {1+\sqrt {17}}{4}$ 有 $h^{′}{{^{\prime }}}\left ({t}\right )=-\frac {2t{^{2}}-t-2}{t{^{2}}}>0$ ，对 $t>\frac {1+\sqrt {17}}{4}$ 有 $h^{′}{{^{\prime }}}\left ({t}\right )=-\frac {2t{^{2}}-t-2}{t{^{2}}}<0$ .
3. 这表明 $h^{′}{\left ({t}\right )}$ 在 $\left ({0,\frac {1+\sqrt {17}}{4}}\right ]$ 上递增，在 $\left [{\frac {1+\sqrt {17}}{4},+∞}\right )$ 上递减.
4. 而 $h^{′}{\left ({1}\right )}={\ln}1+1-\frac {2}{1}-2+3=0$ ， $h^{′}{\left ({\frac {1+\sqrt {17}}{4}}\right )}={\ln}\frac {1+\sqrt {17}}{4}+1-2\cdot \frac {\sqrt {17}-1}{4}-2\cdot \frac {1+\sqrt {17}}{4}+3={\ln}\frac {1+\sqrt {17}}{4}+4-\sqrt {17}>0$ ， $h^{′}{\left ({2}\right )}={\ln}2+1-1-4+3={\ln}2-1<0$ .
5. 所以结合 $h^{′}{\left ({t}\right )}$ 的单调性知，存在 $u\in \left ({\frac {1+\sqrt {17}}{4},2}\right )$ ，使得对 $t\in \left ({1,u}\right )$ 有 $h^{′}{\left ({t}\right )}>0$ ，对 $t\in \left ({0,1}\right )\cup \left ({u,+∞}\right )$ 有 $h^{′}{\left ({t}\right )}<0$ ，且 $h^{′}{\left ({1}\right )}=h^{′}{\left ({u}\right )}=0$ .
6. 这表明 $h\left ({t}\right )$ 在 $(0,1)$ 和 $\left ({u,+∞}\right )$ 上递减，在 $\left ({1,u}\right )$ 上递增.
7. 从而对 $0<t\leqslant u$ 有 $h\left ({t}\right )\geqslant h\left ({1}\right )=2$ ，对 $u<t\leqslant 2$ 有 $h\left ({t}\right )\geqslant h\left ({2}\right )=2$ ，对 $t>2$ 有 $h\left ({t}\right )<h\left ({2}\right )=2$ .
8. 故对任意 $0<t\leqslant 2$ ，都有 $h\left ({t}\right )\geqslant 2$ ，而对任意 $t>2$ ，都有 $h\left ({t}\right )<2$ .
9. 下面对 $a$ 进行分类讨论：
10. ①若 $a\leqslant 0$ ，则对 $x>\frac {\left |{a{^{2}}-4a}\right |}{-2a}+{\rm{e}}$ 有 $x>{\rm{e}}>0$ ， $x>\frac {\left |{a{^{2}}-4a}\right |}{-2a}\geqslant \frac {a{^{2}}-4a}{-2a}$ ，从而 $-2ax{^{2}}-\left ({a{^{2}}-4a}\right )x=-2ax\left ({x-\frac {a{^{2}}-4a}{-2a}}\right )\geqslant 0$ ，且 $x{\ln}x\geqslant 1$ .
11. 故 $f\left ({x}\right )=\left ({2-a}\right )x{\ln}x-2ax{^{2}}-\left ({a{^{2}}-4a}\right )x\geqslant \left ({2-a}\right )x{\ln}x\geqslant 2x{\ln}x\geqslant 2>1$ ，满足条件；
12. ②若 $0<a\leqslant 2$ ，则有 $f\left ({\frac {1}{a}}\right )=\left ({2-a}\right )\cdot \frac {1}{a}{\ln}\frac {1}{a}-2a\cdot {\left({\frac {1}{a}}\right)^{2}}-\left ({a{^{2}}-4a}\right )\cdot \frac {1}{a}=\left ({1-\frac {2}{a}}\right ){\ln}a-\frac {2}{a}-a+4=\frac {h\left ({a}\right )-2}{a}+1\geqslant 1$ ，满足条件；
13. ③若 $a>2$ ，设 $g\left ({x}\right )=\left ({2-a}\right ){\ln}x-2ax-\left ({a{^{2}}-4a}\right )-\frac {1}{x}$ ，则 $g^{′}{\left ({x}\right )}=\frac {2-a}{x}-2a+\frac {1}{x{^{2}}}=-\frac {1}{x{^{2}}}\left ({2ax{^{2}}+\left ({a-2}\right )x-1}\right )=-\frac {1}{x{^{2}}}\left ({2x+1}\right )\left ({ax-1}\right )$ .
14. 从而对 $0<x<\frac {1}{a}$ 有 $g^{′}{\left ({x}\right )}=-\frac {1}{x{^{2}}}\left ({2x+1}\right )\left ({ax-1}\right )>0$ ，对 $x>\frac {1}{a}$ 有 $g^{′}{\left ({x}\right )}=-\frac {1}{x{^{2}}}\left ({2x+1}\right )\left ({ax-1}\right )<0$ .
15. 所以 $g\left ({x}\right )$ 在 $\left ({0,\frac {1}{a}}\right )$ 上递增，在 $\left ({\frac {1}{a},+\infty }\right )$ 上递减，这就得到
16. $g\left ({x}\right )\leqslant g\left ({\frac {1}{a}}\right )=\left ({2-a}\right ){\ln}\frac {1}{a}-2-\left ({a{^{2}}-4a}\right )-a=\left ({a-2}\right ){\ln}a-a{^{2}}+3a-2=h\left ({a}\right )-2<0$ .
17. 故对任意 $x>0$ ，都有
18. $f\left ({x}\right )=\left ({2-a}\right )x{\ln}x-2ax{^{2}}-\left ({a{^{2}}-4a}\right )x=x\left ({\left ({2-a}\right ){\ln}x-2ax-\left ({a{^{2}}-4a}\right )-\frac {1}{x}}\right )+1=xg\left ({x}\right )+1<1$ ，不满足条件.
19. 综上， $a$ 的取值范围是 $\left ({-\infty ,2}\right ]$ .
20. 故答案为： $\left ({-∞,2}\right ]$

## 知识点

**中文**:
  - 利用导数解决不等式能成立问题

**English**:
  - Solving Solvable Inequality Problems

---
