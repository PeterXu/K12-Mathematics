# Mathematics - 题目 3927

**ID**: 6bed5c207d514bb6809d20c81fc11de1
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f(x)=-x+{\ln}x$ ， $g(x)=x{\rm{e}}{{}^{x}}-2x-m$ ．(1)求函数 $f\left ({x}\right )$ 的极值点；​​​​​​​‌(2)若 $f\left ({x}\right )\leqslant g\left ({x}\right )$ 恒成立，求实数 $m$ 的取值范围．

## 解答

1. （1）由已知可得，函数 $f\left ({x}\right )$ 的定义域为 $\left ({0,+∞}\right )$ ，且 $f^{′}{\left ({x}\right )}=\frac {1-x}{x}$ ，
2. 当 $0<x<1$ 时， $f^{′}{\left ({x}\right )}>0$ ；当 $x>1$ 时， $f^{′}{\left ({x}\right )}<0$ ，
3. 所以 $f\left ({x}\right )$ 的单调递增区间为 $\left ({0,1}\right )$ ，单调递减区间为 $\left ({1,+\infty }\right )$ ，
4. 所以 $x=1$ 是 $f\left ({x}\right )$ 的极大值点，无极小值点．
5. （2）解法一：设 $h(x)=f(x)-g(x)={\ln}x+x-x{\rm{e}}{{}^{x}}+m$ ， $x\in (0,+\infty )$ ，
6. 则 $h^{′}(x)=\frac {1}{x}+1-(x+1){\rm{e}}{{}^{x}}=(x+1)\left ({\frac {1}{x}-{\rm{e}}{{}^{x}}}\right )$ ，
7. 令 $t(x)=\frac {1}{x}-{\rm{e}}{{}^{x}}$ ， $x\in (0,+\infty )$ ，则 $t^{′}(x)=-\frac {1}{x{{}^{2}}}-{\rm{e}}{{}^{x}}<0$ 对任意 $x\in (0,+\infty )$ 恒成立，
8. 所以 $t(x)=\frac {1}{x}-{\rm{e}}{{}^{x}}$ 在 $\left ({0,+∞}\right )$ 上单调递减．
9. 又 $t\left ({\frac {1}{2}}\right )=2-\sqrt {{\rm{e}}}>0$ ， $t(1)=1-{\rm{e}}<0$ ，
10. 所以 $\exists x{{}_{0}}\in \left ({\frac {1}{2},1}\right )$ ，使得 $t\left ({x{{}_{0}}}\right )=\frac {1}{x{{}_{0}}}-{\rm{e}}{{}^{x{{}_{0}}}}=0$ ，即 $\frac {1}{x{{}_{0}}}={\rm{e}}{{}^{x{{}_{0}}}}$ ，则 ${\ln}\frac {1}{x{{}_{0}}}={\ln}{\rm{e}}{{}^{x{{}_{0}}}}$ ，即 $-{\ln}x{{}_{0}}=x{{}_{0}}$ ．
11. 因此，当 $0<x<x{{}_{0}}$ 时， $t(x)>0$ ，即 $h^{′}(x)>0$ ，则 $h(x)$ 单调递增；
12. 当 $x>x{{}_{0}}$ 时， $t(x)<0$ ，即 $h^{′}(x)<0$ ，则 $h(x)$ 单调递减，
13. 故 $h(x){{}_{\max }}=h\left ({x{{}_{0}}}\right )={\ln}x{{}_{0}}+x{{}_{0}}-x{{}_{0}}{\rm{e}}{{}^{x{{}_{0}}}}+m=0-1+m\leqslant 0$ ，解得 $m\leqslant 1$ ，
14. 所以当 $m\leqslant 1$ 时， $f\left ({x}\right )\leqslant g\left ({x}\right )$ 恒成立．
15. 解法二：令 $m\left ({x}\right )={\rm{e}}{{}^{x}}-x-1$ ， $m^{′}(x)={\rm{e}}{{}^{x}}-1$ ，当 $x<0$ 时， $m^{′}{\left ({x}\right )}<0$ ；当 $x>0$ 时， $m{{}^{\prime }}\left ({x}\right )>0$ ，
16. 所以 $m\left ({x}\right )$ 在 $\left ({-∞,0}\right )$ 上单调递减，在 $\left ({0,+∞}\right )$ 上单调递增，
17. 所以 $m\left ({x}\right )\geqslant m\left ({0}\right )=0$ ，即 ${\rm{e}}{{}^{x}}\geqslant x+1$ ．
18. 因为 $x{\rm{e}}{{}^{x}}={\rm{e}}{{}^{x+{\ln}x}}$ ，所以 $x{\rm{e}}{{}^{x}}={\rm{e}}{{}^{x+{\ln}x}}\geqslant x+{\ln}x+1$ ，当 $x+{\ln}x=0$ 时等号成立，
19. 即 $x{\rm{e}}{{}^{x}}-x-{\ln}x\geqslant 1$ ，当 $x+{\ln}x=0$ 时等号成立，
20. 所以 $y=x{\rm{e}}{{}^{x}}-x-{\ln}x$ 的最小值为1．
21. 若 $f\left ({x}\right )\leqslant g\left ({x}\right )$ 恒成立，则 $x{\rm{e}}{{}^{x}}-x-{\ln}x\geqslant m$ ，
22. 所以当 $m\leqslant 1$ 时， $f\left ({x}\right )\leqslant g\left ({x}\right )$ 恒成立．

## 知识点

**中文**:
  - 利用导数研究函数的极值
  - 利用导数解决不等式恒成立问题

**English**:
  - Extrema of Functions using Derivatives
  - Solving Universally True Inequalities

---
