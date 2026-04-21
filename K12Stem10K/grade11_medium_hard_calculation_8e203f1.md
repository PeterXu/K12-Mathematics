# Mathematics - 题目 480

**ID**: 8e203f118ebd43b182bd03c0ab30c19d
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f(x)={\rm e}^{x}-1-x-ax{^{2}}$ ．（1）当 $a=0$ 时，求 $f\left ({x}\right )$ 的单调区间；​​​​​​​‌（2）当 $x\geqslant 0$ 时，若不等式 $f\left ({x}\right )\geqslant 0$ 恒成立，求实数 $a$ 的取值范围；（3）若 $x>0$ ，证明： $\left ({{\rm e}^{x}-1}\right ){\ln}\left ({x+1}\right )>x{^{2}}$ ．

## 解答

1. （1）由题意可知，当 $a=0$ 时， $f\left ({x}\right )={\rm e}^{x}-1-x$ ， $x\in \mathbf{R}$ ，
2. 则 $f^{′}{\left ({x}\right )}={\rm e}^{x}-1$ ，令 $f^{′}{\left ({x}\right )}=0$ ，则 $x=0$ ，当 $x>0$ 时， $f^{′}{\left ({x}\right )}>0$ ；当 $x<0$ 时， $f^{′}{\left ({x}\right )}<0$ ，
3. 所以 $f\left ({x}\right )$ 在 $(-\infty ,0]$ 上单调递减，在 $[0,+\infty )$ 上单调递增．
4. （2）由条件得 $f^{′}{\left ({x}\right )}={\rm e}^{x}-1-2ax$ ，
5. 令 $h\left ({x}\right )={\rm e}^{x}-1-2ax$ ，则 $h^{′}{\left ({x}\right )}={\rm e}^{x}-2a$ ，
6. ①当 $2a\leqslant 1$ ，即 $a\leqslant \frac {1}{2}$ 时，在 $\left [0,+\infty \right ]$ 上， $h^{′}{\left ({x}\right )}\geqslant 0$ ，即 $h\left ({x}\right )$ 单调递增，
7. 所以 $h\left ({x}\right )\geqslant h\left ({0}\right )$ ，即 $f^{′}{\left ({x}\right )}\geqslant f^{′}{\left ({0}\right )}=0$ ，
8. $\therefore f\left ({x}\right )$ 在 $\left [0,+\infty \right ]$ 上为增函数， $\therefore f\left ({x}\right )\geqslant f\left ({0}\right )=0$ ，
9. $\therefore a\leqslant \frac {1}{2}$ 时满足条件．
10. ②当 $2a\geqslant 1$ 时，令 $h^{′}{\left ({x}\right )}=0$ ，
11. 解得 $x={\ln}2a$ ，在 $\left [0,{\ln}2a\right ]$ 上， $h^{′}{\left ({x}\right )}<0$ ， $h\left ({x}\right )$ 单调递减，
12. $\therefore $ 当 $x\in \left ({0,{\ln}2a}\right )$ 时，有 $h\left ({x}\right )\mathrm{<}h\left ({0}\right )=0$ ，即 $f^{′}{\left ({x}\right )}<f^{′}{\left ({0}\right )}=0$ ，则 $f\left ({x}\right )$ 在 $\left ({0,{\ln}2a}\right )$ 上为减函数， $\therefore f\left ({x}\right )<f\left ({0}\right )=0$ ，不合题意．
13. 综上，实数 $a$ 的取值范围为 $\left ({-\infty ,\frac {1}{2}}\right ]$ ．
14. （3）由（2）得，当 $a=\frac {1}{2}$ 且 $x>0$ 时， ${\rm }{\rm e}^{x}>1+x+\frac {x{^{2}}}{2}{\rm }$ ，即 ${\rm }{\rm e}^{x}-1>x+\frac {x{^{2}}}{2}=\frac {x{^{2}}+2x}{2}{\rm }$ ，
15. 要证不等式 $\left ({{\rm e}^{x}-1}\right ){\ln}(x+1)>x{^{2}}$ ，只需证明 ${\rm }{\rm e}^{x}-1>\frac {x{^{2}}}{{\ln}(x+1)}{\rm }$ ，
16. 只需证明 $\frac {x{^{2}}+2x}{2}>\frac {x{^{2}}}{{\ln}(x+1)}$ ，只需证 ${\ln}(x+1)>\frac {2x}{2+x}$ ，
17. 设 $F(x)={\ln}(x+1)-\frac {2x}{2+x}(x>0)$ ，则 $F^{′}(x)=\frac {1}{x+1}-\frac {4}{(x+2){^{2}}}=\frac {x{^{2}}}{(x+1)(x+2){^{2}}}(x>0)$ ，
18. 所以当 $x>0$ 时， $F^{′}{\left ({x}\right )}>0$ 恒成立，故 $F\left ({x}\right )$ 在 $(0,+\infty )$ 上单调递增，
19. 又 $F\left ({0}\right )=0$ ． $\therefore F\left ({x}\right )>0$ 恒成立， $\therefore $ 原不等式成立．
20. 已知函数有零点(方程有根)，求参数的值或取值范围
21. (1)直接法：直接根据题设条件构造关于参数的方程(组)或不等式 (组)，通过解方程(组)或不等式(组)确定参数的值或取值范围；
22. (2)分离参数法：先将参数分离，化为a＝g(x)的形式，进而转化成求函数的值域问题；
23. (3)数形结合法：将函数解析式(方程)作移项等变形，转化为两函数图象的交点问题，结合函数的单调性、周期性、奇偶性等性质求解．

## 知识点

**中文**:
  - 函数单调性（单调区间）与最大（小）值的求法
  - 利用导数研究函数的最值
  - 利用导数求函数中的参数

**English**:
  - Monotonicity and Extrema
  - Global Extrema (Max/Min) using Derivatives
  - Finding Parameters using Derivatives

---
