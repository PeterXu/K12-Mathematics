# Mathematics - 题目 845

**ID**: 648552c798b64b14b637b91063ba4236
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\left ({x-a}\right )^{2}+b{\rm{e}}^{x}\left ({a,b\in {\rm{R}}}\right )$ .​​​​​​​‌(1)若 $a=0$ 时，函数 $y=f\left ({x}\right )$ 有3个零点，求 $b$ 的取值范围；(2)若 $a>0$ ， $b=\frac {2}{{\rm{e}}}$ ，方程 $f\left ({x}\right )=3$ 有解，求 $a$ 的取值范围.

## 解答

1. （1）函数 $y=f\left ({x}\right )$ 有3个零点，即 $f\left ({x}\right )=0$ 有3个根，
2. 即 $b=-\frac {x^{2}}{{\rm{e}}^{x}}$ 有3个根，
3. 即 $y=b$ 与 $g\left ({x}\right )=-\frac {x^{2}}{{\rm{e}}^{x}}$ 的图象有三个交点；
4. $g^{′}\left ({x}\right )=\frac {x\left ({x-2}\right )}{{\rm{e}}^{x}}$ ，
5. 令 $g^{′}\left ({x}\right )<0$ ，解得 $0<x<2$ ；令 $g^{′}\left ({x}\right )>0$ 解得 $x<0$ 或 $x>2$ ，
6. 即 $g\left ({x}\right )$ 在 $\left ({-∞,0}\right )$ 单调递增，在 $\left ({0,2}\right )$ 单调递减，在 $\left ({2,+∞}\right )$ 单调递增.
7. 
8. 又 $g\left ({0}\right )=0$ ， $g\left ({2}\right )=-\frac {4}{{\rm{e}}^{2}}$ ， $x>0$ 时 $g\left ({x}\right )<0$ ，
9. 所以 $-\frac {4}{{\rm{e}}^{2}}<b<0$ ，
10. 即 $b$ 的取值范围为 $\left ({-\frac {4}{{\rm{e}}^{2}},0}\right )$ .
11. （2）由方程 $f\left ({x}\right )=3$ 有解，
12. 即 $\left ({x-a}\right )^{2}+\frac {2}{{\rm{e}}}\cdot {\rm{e}}^{x}-3=0$ 有解.
13. 设 $h\left ({x}\right )=\left ({x-a}\right )^{2}+2{\rm{e}}^{x-1}-3$ ，
14. 则 $h^{′}\left ({x}\right )=2\left ({x-a}\right )+2{\rm{e}}^{x-1}$ ，
15. 设 $m\left ({x}\right )=2\left ({x-a}\right )+2{\rm{e}}^{x-1}$ ，
16. 则 $m^{′}\left ({x}\right )=2+2{\rm{e}}^{x-1}>0$ 恒成立，
17. 故 $m\left ({x}\right )$ 在 ${\rm{R}}$ 单调递增，
18. 又 $m\left ({-1}\right )=2\left ({-1-a+{\rm{e}}^{-2}}\right )<0$ ， $m\left ({a}\right )=2{\rm{e}}^{a-1}>0$ ，
19. 且存在唯一的 $x_{0}$ ，使得 $m\left ({x_{0}}\right )=h^{′}\left ({x_{0}}\right )=2\left ({x_{0}-a}\right )+2{\rm{e}}^{x_{0}-1}=0$ ，
20. 所以 $x_{0}-a=-{\rm{e}}^{x_{0}-1}$ ，
21. 且 $x>x_{0}$ 时， $h^{′}\left ({x}\right )>0$ ； $x<x_{0}$ 时， $h^{′}\left ({x}\right )<0$ .
22. 即 $h\left ({x}\right )$ 在 $\left ({-\infty ,x_{0}}\right )$ 单调递减，在 $\left ({x_{0},+\infty }\right )$ 单调递增，
23. $x\to -\infty $ 时 $h\left ({x}\right )\to +\infty $ ， $x\to +\infty $ 时 $h\left ({x}\right )\to +\infty $ ，
24. 故要使得 $h\left ({x}\right )=0$ 有解，只需 $h\left ({x}\right )_{{\rm{m}}{\rm{i}}{\rm{n}}}\leqslant 0$ ，
25. 故 $h\left ({x}\right )_{{\rm{m}}{\rm{i}}{\rm{n}}}=h\left ({x_{0}}\right )=\left ({x_{0}-a}\right )^{2}+2{\rm{e}}^{x_{0}-1}-3={\rm{e}}^{2\left ({x_{0}-1}\right )}+2{\rm{e}}^{x_{0}-1}-3=\left ({{\rm{e}}^{x_{0}-1}+3}\right )\left ({{\rm{e}}^{x_{0}-1}-1}\right )\leqslant 0$ ，
26. 故 ${\rm{e}}^{x_{0}-1}\leqslant 1$ ，解得 $x_{0}\leqslant 1$ ，
27. 而 $a=x_{0}+{\rm{e}}^{x_{0}-1}$ 在 $x_{0}\in \left ({-\infty ,1}\right ]$ 上单调递增，故 $a\leqslant 1+1=2$ ，
28. 又因为 $a>0$ ，故 $a$ 的取值范围为 $\left ({0,2}\right ]$ .
29. 【点睛】方法点睛：函数的零点问题，常转化为函数与函数的交点问题，进而利用导数分析函数的单调性，再结合大致图象进行求解.

## 知识点

**中文**:
  - 利用导数研究方程的根
  - 利用导数解决函数零点问题

**English**:
  - Studying Equation Roots
  - Solving Zero Point Problems

---
