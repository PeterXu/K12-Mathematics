# Mathematics - 题目 2081

**ID**: a2708be56ac44d93ad420f6e93d57aac
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知 $f\left ({x}\right )=x+\frac {a}{x}$ ．（1）若 $a=1,x\in \left [\frac {1}{2},3\right ]$ ，求 $f\left ({x}\right )$ 的值域；​​​​​​​‌（2）若 $a>0,x>0$ ，且 $f\left ({x{{}_{1}}}\right )=f\left ({x{{}_{2}}}\right )\left ({x{{}_{1}}\ne x{{}_{2}}}\right )$ ，证明： $x{{}_{1}}+x{{}_{2}}>2\sqrt {a}$ ；（3）若 $a=-1,b\in {\rm{R}}$ ，当 $b$ 变化时，求 $y=f{^{2}}\left ({x}\right )+bf\left ({x}\right )+2,x\in \left [\frac {1}{2},2\right ]$ 的最小值的最大值．

## 解答

1. （1） $a=1$ 时， $f\left ({x}\right )=x+\frac {1}{x}$ 在 $\left ({0,1}\right )$ 上单调递减，在 $\left ({1,+∞}\right )$ 上单调递增，
2. $\therefore f\left ({x}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=f\left ({1}\right )=2$ ，又 $f\left ({\frac {1}{2}}\right )=\frac {5}{2},f\left ({3}\right )=\frac {10}{3},\frac {5}{2}<\frac {10}{3}$ ，
3. 故 $f\left ({x}\right )$ 的值域为 $\left [2,\frac {10}{3}\right ]$ .
4. （2）法1：设 $f\left ({x{{}_{1}}}\right )=f\left ({x{{}_{2}}}\right )=m$ ，
5. 则 $x{{}_{1}},x{{}_{2}}$ 为 $x+\frac {a}{x}=m$ ，即 $x{^{2}}-mx+a=0$ 的两个不相等的正实根，
6. 所以 $\begin{cases}{\rm{Δ}}=m{^{2}}-4a>0\\x{{}_{1}}+x{{}_{2}}=m>0\\x{{}_{1}}x{{}_{2}}=a>0\end{cases}$ ，
7. 故 $x{{}_{1}}+x{{}_{2}}=m>2\sqrt {a}$ .
8. 法2：由题 $x{{}_{1}}+\frac {a}{x{{}_{1}}}=x{{}_{2}}+\frac {a}{x{{}_{2}}}$ 则 $x{{}_{1}}-x{{}_{2}}=\frac {a}{x{{}_{2}}}-\frac {a}{x{{}_{1}}}=\frac {a\left ({x{{}_{1}}-x{{}_{2}}}\right )}{x{{}_{1}}x{{}_{2}}}$ ，
9. 又 $x{{}_{1}}\ne x{{}_{2}}$ ，故 $x{{}_{1}}x{{}_{2}}=a$ ，
10. 由基本不等式 $x{{}_{1}}+x{{}_{2}}>2\sqrt {x{{}_{1}}x{{}_{2}}}$ ，可得 $x{{}_{1}}+x{{}_{2}}>2\sqrt {a}$
11. （3）当 $a=-1$ 时， $f\left ({x}\right )=x-\frac {1}{x}$ ， $\forall x{{}_{1}},x{{}_{2}}\in \left ({0,+∞}\right )$ ，且 $x{{}_{1}}<x{{}_{2}}$ ，
12. $f\left ({x{{}_{2}}}\right )-f\left ({x{{}_{1}}}\right )=x{{}_{2}}-\frac {1}{x{{}_{2}}}-\left ({x{{}_{1}}-\frac {1}{x{{}_{1}}}}\right )=\left ({x{{}_{2}}-x{{}_{1}}}\right )\left ({1+\frac {1}{x{{}_{1}}x{{}_{2}}}}\right )>0，$
13. 所以 $f\left ({x{{}_{2}}}\right )>f\left ({x{{}_{1}}}\right )$ ，故 $f\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上单调递增.
14. 设 $t=f\left ({x}\right )$ ，因为 $x\in \left [\frac {1}{2},2\right ]$ ，则 $t\in \left [-\frac {3}{2},\frac {3}{2}\right ]$ ，此时 $y=g\left ({t}\right )=t{^{2}}+bt+2,t\in \left [-\frac {3}{2},\frac {3}{2}\right ]$ ．
15. 法1：设 $g\left ({t}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=h\left ({b}\right )$ ．
16. 当 $-\frac {b}{2}\geqslant \frac {3}{2}$ ，即 $b\leqslant -3$ 时， $g\left ({t}\right )$ 在 $\left [-\frac {3}{2},\frac {3}{2}\right ]$ 上单调递减， $g\left ({t}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=g\left ({\frac {3}{2}}\right )=\frac {3}{2}b+\frac {17}{4}，$
17. 当 $-\frac {b}{2}\leqslant -\frac {3}{2}$ ，即 $b\geqslant 3$ 时， $g\left ({t}\right )$ 在 $\left [-\frac {3}{2},\frac {3}{2}\right ]$ 上单调递增， $g\left ({t}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=g\left ({-\frac {3}{2}}\right )=-\frac {3}{2}b+\frac {17}{4}，$
18. 当 $-\frac {3}{2}<-\frac {b}{2}<\frac {3}{2}$ ，即 $-3<b<3$ 时， $g\left ({t}\right )$ 在 $\left [-\frac {3}{2},-\frac {b}{2}\right ]$ 上单调递减，在 $\left ({-\frac {b}{2},\frac {3}{2}}\right ]$ 上单调递增， $g\left ({t}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=g\left ({-\frac {b}{2}}\right )=-\frac {b{^{2}}}{4}+2$
19. 故 $h\left ({b}\right )=\begin{cases}\frac {3}{2}b+\frac {17}{4},b\leqslant -3\\-\frac {3}{2}b+\frac {17}{4},b\geqslant 3\\-\frac {b{^{2}}}{4}+2,-3<b<3\end{cases}$ ，
20. 
21. 结合图象可知， $g\left ({t}\right )$ 的最小值的最大值为2.
22. 法2：当 $b=0$ 时，则 $g\left ({t}\right )=t{^{2}}+2$ ，此时 $g\left ({t}\right )$ 的最小值为2；
23. 当 $b\ne 0,0\in \left [-\frac {3}{2},\frac {3}{2}\right ]$ ，由最小值的定义， $g\left ({t}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}\leqslant g\left ({0}\right )=2$ ，
24. 综上， $g\left ({t}\right )$ 的最小值的最大值为2.

## 知识点

**中文**:
  - 函数单调性（单调区间）与最大（小）值的求法
  - 利用基本不等式证明（或判断）不等关系
  - 函数的值域

**English**:
  - Monotonicity and Extrema
  - Proving Inequalities
  - Range of Functions

---
