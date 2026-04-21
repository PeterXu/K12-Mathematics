# Mathematics - 题目 941

**ID**: 4e6764f123184546af622e8b60beb112
**年级**: Grade 11
**难度**: Medium
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\left ({x-a}\right ){\rm{e}}{^{x-1}}+x+a-2$ ， $a\in {\mathbf{R}}$ .​​​​​​​‌ $f\left ({x}\right )$ 的导函数为 $g\left ({x}\right )$ .（1）当 $a=3$ 时.求函数 $g\left ({x}\right )$ 的最小值；（2）若 $a>3$ .①证明： $f\left ({x}\right )$ 恰有3个零点；②证明： $f\left ({x}\right )$ 的所有零点之和为定值.

## 解答

1. （1）由题意 $g\left ({x}\right )=f^{′}{\left ({x}\right )}=\left ({x-2}\right ){\rm{e}}{^{x-1}}+1$ ， $g^{′}{\left ({x}\right )}=\left ({x-1}\right ){\rm{e}}{^{x-1}}$
2. 令 $g^{′}{\left ({x}\right )}=0\Rightarrow x=1$
3. 当 $x>1$ 时， $g^{′}{\left ({x}\right )}>0$ ， $\therefore g\left ({x}\right )$ 在 $\left ({1,+∞}\right )$ 上为增函数；
4. 当 $x<1$ 时， $g^{′}{\left ({x}\right )}<0$ ， $\therefore g\left ({x}\right )$ 在 $\left ({-∞,1}\right )$ 上为减函数.
5. $\therefore g\left ({x}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=g\left ({1}\right )=0$ ；
6. （2）① $g\left ({x}\right )=\left ({x-a+1}\right ){\rm{e}}{^{x-1}}+1\Rightarrow g^{′}{\left ({x}\right )}=\left ({x-a+2}\right ){\rm{e}}{^{x-1}}$
7. 令 $g^{′}{\left ({x}\right )}=0\Rightarrow x=a-2$ ；
8. 当 $x<a-2$ 时， $g^{′}{\left ({x}\right )}<0$ ， $g\left ({x}\right )=f^{′}{\left ({x}\right )}$ 单调递减；
9. 当 $x>a-2$ 时， $g^{′}{\left ({x}\right )}>0$ ， $g\left ({x}\right )=f^{′}{\left ({x}\right )}$ 单调递增；
10. 所以 $f^{′}{\left ({x}\right )}{{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=f^{′}{\left ({a-2}\right )}=1-{\rm{e}}{^{a-3}}$ ，
11. 又 $a>3$ ，所以 $f^{′}{\left ({x}\right )}{{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=1-{\rm{e}}{^{a-3}}<0$ ，且当 $x\to +\infty $ 时， $f^{′}{\left ({x}\right )}\to +∞$ ； $x\to -\infty $ 时， $f^{′}{\left ({x}\right )}\to 1$ ；
12. 所以 $f^{′}{\left ({x}\right )}$ 在 $\left ({-∞,a-2}\right )$ 与 $\left ({a-2,+∞}\right )$ 上各有一个零点，不妨分别记为 $x{{}_{1}},x{{}_{2}}$ ，
13. 所以 $x\in \left ({-∞,x{{}_{1}}}\right )$ 时， $f^{′}{\left ({x}\right )}>0\Rightarrow f\left ({x}\right )$ 单调递增；
14. $x\in \left ({x{{}_{1}},x{{}_{2}}}\right )$ 时， $f^{′}{\left ({x}\right )}<0\Rightarrow f\left ({x}\right )$ 单调递减；
15. $x\in \left ({x{{}_{2}},+∞}\right )$ 时， $f^{′}{\left ({x}\right )}>0\Rightarrow f\left ({x}\right )$ 单调递增；
16. 且 $f^{′}{\left ({1}\right )}=3-a<0$ ，所以 $1\in \left ({x{{}_{1}},x{{}_{2}}}\right )$ ；
17. 则 $f\left ({x{{}_{1}}}\right )>f\left ({1}\right )=0$ ， $f\left ({x{{}_{2}}}\right )<f\left ({1}\right )=0$ ，又当 $x\to +\infty $ 时， $f\left ({x}\right )\to +∞$ ； $x\to -\infty $ 时， $f\left ({x}\right )\to -∞$ ；
18. 所以 $f\left ({x}\right )$ 在 $\left ({-∞,x{{}_{1}}}\right )$ 与 $\left ({x{{}_{2}},+∞}\right )$ 上各有一个零点，且 $f\left ({1}\right )=0$ ，
19. 所以 $f\left ({x}\right )$ 有且仅有三个零点.
20. ②令 $h\left ({x}\right )=f\left ({x+1}\right )=\left ({x+1-a}\right )\cdot {\rm{e}}{^{x}}+x+a-1$
21. $=x\cdot \left ({{\rm{e}}{^{x}}+1}\right )-\left ({a-1}\right )\cdot \left ({{\rm{e}}{^{x}}-1}\right )$
22. $=\left ({{\rm{e}}{^{x}}+1}\right )\cdot \left [x-\left ({a-1}\right )\cdot \frac {{\rm{e}}{^{x}}-1}{{\rm{e}}{^{x}}+1}\right ]$
23. 令 $h\left ({x}\right )=0$ ， $\because {\rm{e}}{^{x}}+1>0$ ， $\therefore x-\left ({a-1}\right )\cdot \frac {{\rm{e}}{^{x}}-1}{{\rm{e}}{^{x}}+1}=0$ .
24. 令 $φ\left ({x}\right )=x-\left ({a-1}\right )\cdot \frac {{\rm{e}}{^{x}}-1}{{\rm{e}}{^{x}}+1}$ ，
25. $\because φ\left ({-x}\right )=-x-\left ({a-1}\right )\cdot \frac {{\rm{e}}{^{-x}}-1}{{\rm{e}}{^{-x}}+1}=-x+\left ({a-1}\right )\cdot \frac {{\rm{e}}{^{x}}-1}{{\rm{e}}{^{x}}+1}=-φ\left ({x}\right )$
26. $\therefore φ\left ({x}\right )$ 为奇函数.因为奇函数的图象关于原点对称，所以 $φ\left ({x}\right )$ 所有零点和为0；
27. $\therefore h\left ({x}\right )$ 所有零点和为0.
28. 由于 $f\left ({x}\right )$ 的图象可由 $h\left ({x}\right )$ 向右平移一个单位长度得到，
29. 所以 $f\left ({x}\right )$ 所有的零点和为定值3.

## 知识点

**中文**:
  - 利用导数研究函数的最值
  - 利用导数解决函数零点问题

**English**:
  - Global Extrema (Max/Min) using Derivatives
  - Solving Zero Point Problems

---
