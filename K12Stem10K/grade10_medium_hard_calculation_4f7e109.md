# Mathematics - 题目 139

**ID**: 4f7e109e3483448fbe774fba348de79f
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设函数 $f\left ({x}\right )=\left |{x{^{2}}-ax}\right |+2b\left ({a,b\in \mathbf{R}}\right )$ .​​​​​​​‌(1)当 $a=-2$ ， $b=-\frac {15}{2}$ 时，解方程 $f\left ({x{^{3}}}\right )=0$ ；(2)当 $b=0$ 时，若不等式 $f\left ({x}\right )\leqslant 2x$ 在 $x\in \left [0,2\right ]$ 上恒成立，求实数 $a$ 的取值范围；(3)若 $a$ 为常数， $f\left ({x}\right )=0$ 在区间 $\left [0,2\right ]$ 上有解，求实数 $b$ 的取值范围.

## 解答

1. （1）当 $a=-2$ ， $b=-\frac {15}{2}$ 时， $f\left ({x}\right )=\left |{x{^{2}}+2x}\right |-15$ ，
2. 所以 $f\left ({x{^{3}}}\right )=\left |{{\left({x{^{3}}}\right)^{2}}+2x{^{3}}}\right |-15=0$ ，
3. 即 ${\left({x{^{3}}}\right)^{2}}+2x{^{3}}=15$ 或 ${\left({x{^{3}}}\right)^{2}}+2x{^{3}}=-15$ ，
4. 解得 $x{^{3}}=3$ 或 $x{^{3}}=-5$ ，
5. 即 $x=\sqrt[3]{3}$ 或 $x=\sqrt[3]{-5}$ ；
6. （2）当 $b=0$ 时， $f\left ({x}\right )=\left |{x{^{2}}-ax}\right |$ ，
7. 所以不等式 $f\left ({x}\right )=\left |{x{^{2}}-ax}\right |\leqslant 2x$ 在 $x\in \left [0,2\right ]$ 上恒成立，
8. 即为不等式 $x\left |{x-a}\right |\leqslant 2x$ 在 $x\in \left [0,2\right ]$ 上恒成立，
9. 当 $x=0$ 时，不等式恒成立，即 $a\in \mathbf{R}$ ，
10. 当 $x\in \left ({0,2}\right ]$ 时，不等式可转化为 $\left |{x-a}\right |\leqslant 2$ ，
11. 即 $-2\leqslant x-a\leqslant 2$ 在 $\left ({0,2}\right ]$ 上恒成立，
12. 又函数 $y=x-a$ 在 $\left ({0,2}\right ]$ 上单调递增，
13. 所以 $y=x-a\in \left ({-a,2-a}\right ]$ ，
14. 所以 $\begin{cases}-a\leqslant -2\\2-a\leqslant 2\end{cases}$ ，解得 $0\leqslant a\leqslant 2$ ，
15. 即 $a$ 的取值范围为 $\left [0,2\right ]$ ；
16. （3） $f\left ({x}\right )=0$ 在区间 $\left [0,2\right ]$ 上有解，即方程 $x\left |{x-a}\right |=-2b$ 在 $\left [0,2\right ]$ 上有解，
17. 设 $g\left ({x}\right )=\begin{cases}x{^{2}}-ax,x\geqslant a\\-x{^{2}}+ax,x<a\end{cases}$ ，
18. 当 $a\leqslant 0$ 时， $g\left ({x}\right )=\begin{cases}x{^{2}}-ax,x\geqslant a\\-x{^{2}}+ax,x<a\end{cases}$ 在 $\left [0,2\right ]$ 上单调递增，
19. 所以 $g\left ({x}\right ){{}_{{\rm \min }}}=g\left ({0}\right )=0$ ， $g\left ({x}\right ){{}_{{\rm \max }}}=g\left ({2}\right )=4-2a$ ，
20. 则当 $0\leqslant -2b\leqslant 4-2a$ 时，原方程有解，即 $a-2\leqslant b\leqslant 0$ ；
21. 当 $a>0$ 时， $g\left ({x}\right )=\begin{cases}x{^{2}}-ax,x\geqslant a\\-x{^{2}}+ax,x<a\end{cases}$ ，
22. 在 $\left [0,\frac {a}{2}\right ]$ 上单调递增，在 $\left [\frac {a}{2},a\right ]$ 上单调递减，在 $\left [{a,+\infty }\right )$ 上单调增；
23. ①当 $\frac {a}{2}\geqslant 2$ ，即 $a\geqslant 4$ 时， $g\left ({x}\right ){{}_{{\rm \max }}}=g\left ({2}\right )=2a-4$ ， $g\left ({x}\right ){{}_{{\rm \min }}}=g\left ({0}\right )=0$ ，
24. 则当 $0\leqslant -2b\leqslant 4-2a$ 时，原方程有解，即 $a-2\leqslant b\leqslant 0$ ；
25. ②当 $\frac {a}{2}<2\leqslant a$ ，即 $2\leqslant a<4$ 时， $g\left ({x}\right ){{}_{{\rm \max }}}=g\left ({\frac {a}{2}}\right )=\frac {a{^{2}}}{4}$ ， $g\left ({x}\right ){{}_{{\rm \min }}}=g\left ({0}\right )=0$ ，
26. 则当 $0\leqslant -2b\leqslant \frac {a{^{2}}}{4}$ 时，原方程有解，则 $-\frac {a{^{2}}}{8}\leqslant b\leqslant 0$ ；
27. ③当 $0<a<2$ 时， $g\left ({x}\right ){{}_{{\rm \min }}}=g\left ({0}\right )=0$ ， $g\left ({\frac {a}{2}}\right )=\frac {a{^{2}}}{4}$ ， $g\left ({2}\right )=4-2a$ ，
28. 当 $\frac {a{^{2}}}{4}\geqslant 4-2a$ ，即 $-4+4\sqrt {2}\leqslant a<2$ 时， $g\left ({x}\right ){{}_{{\rm \max }}}=g\left ({\frac {a}{2}}\right )=\frac {a{^{2}}}{4}$ ，
29. 则当 $0\leqslant -2b\leqslant \frac {a{^{2}}}{4}$ 时，原方程有解，即 $-\frac {a{^{2}}}{8}\leqslant b\leqslant 0$ ；
30. 当 $\frac {a{^{2}}}{4}<4-2a$ ，即 $0<a<-4+4\sqrt {2}$ 时， $g\left ({x}\right ){{}_{{\rm \max }}}=g\left ({2}\right )=2a-4$ ，
31. 则当 $0\leqslant -2b\leqslant 4-2a$ 时，原方程有解，即 $a-2\leqslant b\leqslant 0$ ；
32. 综上所述：当 $a<-4+4\sqrt {2}$ 时，实数 $b$ 的取值范围为 $\left [a-2,0\right ]$ ；
33. 当 $-4+4\sqrt {2}\leqslant a<4$ 时，实数 $b$ 的取值范围为 $\left [-\frac {a{^{2}}}{8},0\right ]$ ；
34. 当 $a\geqslant 4$ 时，实数 $b$ 的取值范围为 $\left [2-a,0\right ]$ .

## 知识点

**中文**:
  - 与函数有关的参数问题
  - 与函数有关的恒成立问题

**English**:
  - Parameter Problems Related to Functions
  - Universally True Problems Related to Functions

---
