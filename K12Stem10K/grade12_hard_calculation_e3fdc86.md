# Mathematics - 题目 404

**ID**: e3fdc8693d4c497c95c17e1e3e3a7ea9
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\frac {{\ln}x+1}{x}$ ，若 $a$ 为实数，且方程 $f\left ({x}\right )=a$ 有两个不同的实数根 $x{{}_{1}},x{{}_{2}}$ ．(1)求 $a$ 的取值范围：(2)①证明：对任意的 $x\in \left ({\frac {1}{{\rm{e}}},1}\right )$ 都有 $f\left ({x}\right )>\frac {{\rm{e}}x-1}{{\rm{e}}-1}$ ；​​​​​​​‌②求证： $\left |{x{{}_{1}}-x{{}_{2}}}\right |>\sqrt {2\left ({1-a}\right )}+\left ({1-a}\right )\left ({1-\frac {1}{{\rm{e}}}}\right )$ ．

## 解答

1. （1） $\because f\left ({x}\right )=\frac {{\ln}x+1}{x}$ ， $x>0$ ， $\therefore f^{′}{\left ({x}\right )}=-\frac {{\ln}x}{x{^{2}}}$ ， $x>0$ ，
2. $\therefore f\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上为增函数，在 $\left ({1,+\mathrm{∞}}\right )$ 上为减函数，
3. $\because f\left ({\frac {1}{e}}\right )=0$ ， $f\left ({1}\right )=1$ ，且 $x\to +\infty $ 时， $f\left ({x}\right )\to 0$ ，
4. 故函数 $f\left ({x}\right )$ 的图象如下：
5. 
6. 因为方程 $f\left ({x}\right )=a$ 有两个不同的实数根 $x{{}_{1}},x{{}_{2}}$ ，
7. 所以 $a\in \left ({0,1}\right )$ ；
8. （2）（ⅰ）记 ${\rm{g}}\left ({x}\right )=f\left ({x}\right )-\frac {{\rm{e}}x-1}{{\rm{e}}-1}=\frac {{\ln}x+1}{x}-\frac {{\rm{e}}x-1}{{\rm{e}}-1}$ ， $x\in \left ({\frac {1}{{\rm{e}}},1}\right )$ ，
9. 则 $g^{′}{\left ({x}\right )}=-\frac {{\ln}x}{x{^{2}}}-\frac {{\rm{e}}}{{\rm{e}}-1}$ ， $x\in \left ({\frac {1}{{\rm{e}}},1}\right )$ ，设 $t\left ({x}\right )=-\frac {{\ln}x}{x{^{2}}}-\frac {{\rm{e}}}{{\rm{e}}-1}$ ，
10. 则 $t^{′}{\left ({x}\right )}=\frac {2{\ln}x-1}{x{^{3}}}<0$ ，
11. $\therefore g^{′}{\left ({x}\right )}$ 在 $x\in \left ({\frac {1}{{\rm{e}}},1}\right )$ 上为减函数，
12. $\because g^{′}{\left ({\frac {1}{{\rm{e}}}}\right )}={\rm{e}}{^{2}}-\frac {{\rm{e}}}{{\rm{e}}-1}>0$ ， $g^{′}{\left ({1}\right )}=-\frac {{\rm{e}}}{{\rm{e}}-1}<0$ ，
13. $\therefore $ 存在 $x{{}_{0}}\in \left ({\frac {1}{{\rm{e}}},1}\right )$ ，使得 $g^{′}{\left ({x{{}_{0}}}\right )}=0$ ，
14. $\therefore x\in \left ({\frac {1}{{\rm{e}}},x{{}_{0}}}\right )$ 时， $g^{′}{\left ({x}\right )}>0$ ； $x\in \left ({x{{}_{0}},1}\right )$ 时， $g\left ({x}\right )<0$ ，
15. $\therefore g\left ({x}\right )$ 在 $\left ({\frac {1}{{\rm{e}}},x{{}_{0}}}\right )$ 上为增函数，在 $\left ({x{{}_{0}},1}\right )$ 上为减函数，
16. 又 $g\left ({\frac {1}{e}}\right )=0$ ， $g\left ({1}\right )=0$ ， $\therefore g\left ({x}\right )>0$ ；
17. （ⅱ）不妨设 $x{{}_{1}}<x{{}_{2}}$ ，则 $\frac {1}{{\rm{e}}}<x{{}_{1}}<1<x{{}_{2}}$ ，
18. 由（1）知 $f\left ({x{{}_{1}}}\right )>\frac {{\rm{e}}x{{}_{1}}-1}{{\rm{e}}-1}$ ，又 $f\left ({x{{}_{1}}}\right )=a$ ， $\therefore a>\frac {{\rm{e}}x{{}_{1}}-1}{{\rm{e}}-1}$ ，
19. $\therefore x{{}_{1}}<\frac {1}{{\rm{e}}}+a\left ({1-\frac {1}{{\rm{e}}}}\right )$ ，
20. 要证 $\left |{x{{}_{1}}-x{{}_{2}}}\right |>\sqrt {2\left ({1-a}\right )}+\left ({1-a}\right )\left ({1-\frac {1}{{\rm{e}}}}\right )$ ，
21. 只要证 $x{{}_{2}}-x{{}_{1}}>\sqrt {2\left ({1-a}\right )}+\left ({1-a}\right )\left ({1-\frac {1}{{\rm{e}}}}\right )$
22. $\Leftarrow x{{}_{2}}-\frac {1}{{\rm{e}}}-a\left ({1-\frac {1}{{\rm{e}}}}\right )>\sqrt {2\left ({1-a}\right )}+\left ({1-a}\right )\left ({1-\frac {1}{{\rm{e}}}}\right )$
23. $\Leftarrow x{{}_{2}}>\sqrt {2\left ({1-a}\right )}+1\Leftarrow {\left({x{{}_{2}}-1}\right)^{2}}>2\left ({1-a}\right )$
24. $\Leftarrow a>-\frac {{\left({x{{}_{2}}-1}\right)^{2}}}{2}+1\Leftarrow f\left ({x{{}_{2}}}\right )>-\frac {{\left({x{{}_{2}}-1}\right)^{2}}}{2}+1$
25. $\Leftarrow \frac {{\ln}x{{}_{2}}+1}{x{{}_{2}}}>-\frac {{\left({x{{}_{2}}-1}\right)^{2}}}{2}+1\Leftarrow {\ln}x{{}_{2}}+1>-\frac {x{{}_{2}}{\left({x{{}_{2}}-1}\right)^{2}}}{2}+x{{}_{2}}$
26. $\Leftarrow {\ln}x{{}_{2}}+\frac {1}{2}x{{}_{2}}{^{3}}-x{{}_{2}}{^{2}}-\frac {1}{2}x{{}_{2}}+1>0$ ，
27. 记 $h\left ({x}\right )={\ln}x+\frac {1}{2}x{^{3}}-x{^{2}}-\frac {1}{2}x+1$ ， $x>1$ ，
28. $h^{′}{\left ({x}\right )}=\frac {1}{x}+\frac {3}{2}x{^{2}}-2x-\frac {1}{2}=\frac {{\left({x-1}\right)^{2}}\left ({3x+2}\right )}{2x}>0$ ，
29. $\therefore h\left ({x}\right )$ 在 $\left ({1,+\mathrm{∞}}\right )$ 上为增函数， $\therefore h\left ({x}\right )>h\left ({1}\right )=0$ ，
30. $\therefore h\left ({x{{}_{2}}}\right )>0$ 成立，
31. $\therefore \left |{x{{}_{1}}-x{{}_{2}}}\right |>\sqrt {2\left ({1-a}\right )}+\left ({1-a}\right )\left ({1-\frac {1}{\mathrm{e}}}\right )$ 成立.

## 知识点

**中文**:
  - 利用导数研究方程的根
  - 利用导数证明不等式
  - 利用导数解决不等式恒成立问题

**English**:
  - Studying Equation Roots
  - Proving Inequalities using Derivatives
  - Solving Universally True Inequalities

---
