# Mathematics - 题目 2686

**ID**: a4138b0b06254795ae2cd2af36be77c2
**年级**: Grade 11
**难度**: Hard
**题型**: Fill-in-the-blank

## 题目
已知 $f\left ({x}\right )=\left |{x{\rm e}{^{x}}-x}\right |-\left |{ax{^{2}}-x}\right |$ 恰有四个不同零点，则 $a$ 的取值范围为.​​​​​​​‌

## 解答

1. 由函数 $f\left ({x}\right )=\left |{x{\rm{e}}{^{x}}-x}\right |-\left |{ax{^{2}}-x}\right |=\left |{x}\right |\cdot \left ({\left |{{\rm{e}}{^{x}}-1}\right |-\left |{ax-1}\right |}\right )$ ，
2. 可得 $f\left ({0}\right )=0$ ，所以 $x=0$ 是函数 $y=f\left ({x}\right )$ 的一个零点，
3. 要使得 $y=f\left ({x}\right )$ 恰有四个不同零点，即方程 $\left |{{\rm{e}}{^{x}}-1}\right |-\left |{ax-1}\right |=0$ 恰有三个非零的实数根，
4. 即方程 ${\rm e}{^{x}}=ax$ 或 ${\rm e}{^{x}}+ax-2=0$ 恰有三个非零的实数根，
5. 即方程 $a=\frac {{\rm e}{^{x}}}{x}$ 或 ${\rm e}{^{x}}+ax-2=0$ 恰有三个非零的实数根，
6. 令 $g\left ({x}\right )=\frac {{\rm{e}}{^{x}}}{x}$ ，可得 $g^{′}{\left ({x}\right )}=\frac {{\rm{e}}{^{x}}(x-1)}{x{^{2}}}$ ，
7. 当 $x\in (-\infty ,0)$ 时， $g^{′}{\left ({x}\right )}<0$ ；当 $x\in (0,1)$ 时， $g^{′}{\left ({x}\right )}<0$ ；当 $x\in (1,+\infty )$ 时， $g^{′}{\left ({x}\right )}>0$ ，
8. 所以 $g\left ({x}\right )$ 在 $(-\infty ,0),(0,1)$ 上单调递减，在 $(1,+\infty )$ 上单调递增，
9. $g\left ({1}\right )={\rm{e}}$ 且 $x<0$ 时， $g\left ({x}\right )<0$ ； $x>0$ 时， $g\left ({x}\right )>0$ ，
10. 函数 $g\left ({x}\right )$ 的图象如图所示，
11. 当 $a>{\rm e}$ 时，方程 $a=\frac {{\rm e}{^{x}}}{x}$ 有两个实数根；当 $a={\rm e}$ 时，方程 $a=\frac {{\rm e}{^{x}}}{x}$ 只有一个实数根；
12. 当 $0\leqslant a<{\rm e}$ 时，方程 $a=\frac {{\rm e}{^{x}}}{x}$ 没有实数根；当 $a<0$ 时，方程 $a=\frac {{\rm e}{^{x}}}{x}$ 只有一个实数根；
13. 
14. 令 $h\left ({x}\right )={\rm{e}}{^{x}}+ax-2$ ，可得 $h^{′}{\left ({x}\right )}={\rm{e}}{^{x}}+a$ ，
15. 当 $a\geqslant 0$ 时， $h^{′}{\left ({x}\right )}>0$ 恒成立，所以 $h\left ({x}\right )$ 单调递增，
16. 且 $h\left ({0}\right )=-1\left \langle {0,h\left ({1}\right )={\rm{e}}+a-2}\right \rangle 0$ ，所以函数 $h\left ({x}\right )$ 只有一个零点；
17. 当 $a<0$ 时，令 $h^{′}{\left ({x}\right )}=0$ ，可得 $x={\ln}(-a)$ ，
18. 当 $x<{\ln}(-a)$ 时， $h^{′}{\left ({x}\right )}<0$ ；当 $x>{\ln}(-a)$ 时， $h^{′}{\left ({x}\right )}>0$ ；
19. 所以 $x={\ln}(-a)$ 时，函数取得极小值， $h({\ln}(-a))=-a+a{\ln}(-a)-2$ ，
20. 令 $x=-a$ ，则 $x>0$ ，令 $φ\left ({x}\right )=x-x{\ln}x-2,x>0$ ，
21. 可得 $φ^{′}{\left ({x}\right )}=-{\ln}x$ ，令 $φ^{′}{\left ({x}\right )}=0$ ，可得 $x=1$ ，
22. 当 $x\in (0,1)$ 时， $φ^{′}{\left ({x}\right )}>0$ ；当 $x\in (1,+\infty )$ 时， $φ^{′}{\left ({x}\right )}<0$ ，
23. 函数 $φ\left ({x}\right )$ 在 $(0,1)$ 上单递增，在 $(1,+\infty )$ 上单调递减，
24. 当 $x=1$ 时，函数取得极大值，极大值为 $φ\left ({1}\right )=-1$ ，即 $h({\ln}(-a))<0$ ，
25. 又由 $x\to -\infty $ 时， $h\left ({x}\right )\to +\mathrm{∞}$ ； $x\to +\infty $ 时， $h\left ({x}\right )\to +\mathrm{∞}$ ，
26. 所以，当 $a<0$ 时，函数 $h\left ({x}\right )$ 有两个零点，
27. 综上可得：当 $a>{\rm e}$ 时，方程 ${\rm e}{^{x}}=ax$ 有两个实根，方程 ${\rm e}{^{x}}+ax-2=0$ 只有一个实根，
28. 此时 $f\left ({x}\right )$ 恰有四个不同零点，符合题意；
29. 当 $a={\rm e}$ 时，方程 ${\rm e}{^{x}}=ax$ 有一个实根，方程 ${\rm e}{^{x}}+ax-2=0$ 只有一个实根，
30. 此时函数 $f\left ({x}\right )$ 三个零点，不符合题意；
31. 当 $0\leqslant a<{\rm e}$ 时，方程 ${\rm e}{^{x}}=ax$ 没有实根，方程 ${\rm e}{^{x}}+ax-2=0$ 只有一个实根，
32. 此时函数 $f\left ({x}\right )$ 一个零点，不符合题意；
33. 当 $a<0$ 时，方程 ${\rm e}{^{x}}=ax$ 只有一个实根，方程 ${\rm e}{^{x}}+ax-2=0$ 有两个实根，
34. 此时函数 $f\left ({x}\right )$ 恰有四个零点，符合题意，
35. 所以当 $a\in (-\infty ,0)\cup ({\rm e},+\infty )$ 时，函数 $f\left ({x}\right )=\left |{x{\rm{e}}{^{x}}-x}\right |-\left |{ax{^{2}}-x}\right |$ 恰有四个零点.

## 知识点

**中文**:
  - 利用导数解决函数零点问题

**English**:
  - Solving Zero Point Problems

---
