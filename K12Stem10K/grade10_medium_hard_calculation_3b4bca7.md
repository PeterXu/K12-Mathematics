# Mathematics - 题目 791

**ID**: 3b4bca7581124885a9fa2ea8533e216e
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知 $f\left ({x}\right )=\frac {ax-b}{x{^{2}}+4}$ 是定义在R上的奇函数，其中 $a,b\in {\mathbf{R}}$ ，且 $f\left ({1}\right )=\frac {4}{5}$ .​​​​​​​‌（1）求 $a,b$ 的值；（2）判断 $f\left ({x}\right )$ 在 $\left [{2,+\infty }\right )$ 上的单调性，并用单调性的定义证明；（3）设 $g\left ({x}\right )=mx{^{2}}-2x+2-m$ ，若对任意的 $x{{}_{1}}\in \left [2,4\right ]$ ，总存在 $x{{}_{2}}\in \left [0,1\right ]$ ，使得 $f\left ({x{{}_{1}}}\right )=g\left ({x{{}_{2}}}\right )$ 成立，求 $m$ 的取值范围.

## 解答

1. （1）因为 $f\left ({x}\right )$ 是定义在R上的奇函数，
2. 所以 $f\left ({0}\right )=-b=0$ ，解得 $b=0$ ，
3. 又因为 $f\left ({1}\right )=\frac {4}{5}$ ，所以 $f\left ({1}\right )=\frac {a}{1+4}=\frac {4}{5}$ ，
4. 解得 $a=4$ ，所以 $f\left ({x}\right )=\frac {4x}{x{^{2}}+4}$ ，
5. $f\left ({-x}\right )=\frac {-4x}{x{^{2}}+4}=-f\left ({x}\right )$ ，则 $f\left ({x}\right )$ 为奇函数
6. 所以 $a=4,b=0$
7. （2） $f\left ({x}\right )$ 在 $\left [{2,+\infty }\right )$ 上单调递减.
8. 证明如下：
9. 设 $2\leqslant x{{}_{1}}<x{{}_{2}}$ ，则
10. $f\left ({x{{}_{1}}}\right )-f\left ({x{{}_{2}}}\right )=\frac {4x{{}_{1}}}{x{{}_{1}^{2}}+4}-\frac {4x{{}_{2}}}{x{{}_{2}^{2}}+4}$  $=\frac {\left ({x{{}_{1}}-x{{}_{2}}}\right )\left ({16-4x{{}_{1}}x{{}_{2}}}\right )}{\left ({x{{}_{1}^{2}}+4}\right )\left ({x{{}_{2}^{2}}+4}\right )}$
11. 因为 $2\leqslant x{{}_{1}}<x{{}_{2}}$ ，则 $x{{}_{1}}-x{{}_{2}}<0$ ，
12. $16-4x{{}_{1}}x{{}_{2}}<0$ ，所以 $f\left ({x{{}_{1}}}\right )>f\left ({x{{}_{2}}}\right )$ ，
13. 所以 $f\left ({x}\right )$ 在 $\left [{2,+\infty }\right )$ 上单调递减.
14. （3）记 $f\left ({x}\right )$ 在 $\left [2,4\right ]$ 上的值域为集合A， $g(x)$ 在 $\left [0,1\right ]$ 上的值域为集合B，
15. 则原问题等价于 $A\subseteq B$
16. 由（2）可知 $f\left ({x}\right )$ 在 $\left [2,4\right ]$ 上单调递减，所以
17. $f(x){{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}=f\left ({2}\right )=1,f(x){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=f\left ({4}\right )$  $=\frac {4}{5}$
18. 记 $f\left ({x}\right )$ 在区间 $\left [2,4\right ]$ 内的值域为 $A=\left [\frac {4}{5},1\right ]$ .
19. 当 $m<0$ 时，易知 $g\left ({x}\right )$ 在 $\left [0,1\right ]$ 上单调递减，
20. 则 $g(x){{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}=g\left ({0}\right )=2-m>2$ ， $g(x){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=g\left ({1}\right )=0$
21. 得 $g\left ({x}\right )$ 在区间 $\left [0,1\right ]$ 内的值域为 $B=\left [0,2-m\right ]$ ，满足 $A\subseteq B$
22. 当 $m=0$ 时， $g\left ({x}\right )=-2x+2$ 在 $\left [0,1\right ]$ 上单调递减，
23. 则 $g(x){{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}=g\left ({0}\right )=2$ ， $g(x){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=g\left ({1}\right )=0$ ，
24. 得 $g\left ({x}\right )$ 在区间 $\left [0,1\right ]$ 内的值域为 $B=\left [0,1\right ]$ ，满足 $A\subseteq B$ ，
25. 当 $0<m\leqslant 1$ 时， $\frac {1}{m}\geqslant 1,g\left ({x}\right )$ 在 $\left [0,1\right ]$ 上单调递减，
26. 则 $g(x){{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}=g\left ({0}\right )=2-m\geqslant 1$ ，
27. $g(x){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=g\left ({1}\right )=0$ ，得 $g\left ({x}\right )$ 在区间 $\left [0,1\right ]$ 内的值域为 $B=\left [0,2-m\right ]$ ，满足 $A\subseteq B$ ，
28. 当 $1<m\leqslant 2$ 时， $\frac {1}{2}\leqslant \frac {1}{m}<1,g\left ({x}\right )$ 在 $\left [0,\frac {1}{m}\right ]$ 上单调递减，在 $\left [\frac {1}{m},1\right ]$ 上单调递增，则
29. $g(x){{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}=g\left ({0}\right )=2-m,g(x){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}$  $=g\left ({\frac {1}{m}}\right )=-\frac {1}{m}+2-m$ ，
30. 得 $g\left ({x}\right )$ 在区间 $\left [0,1\right ]$ 内的值域为 ${B=\left [-\frac {1}{m}+2-m,2-m\right ]}$
31. $\therefore \begin{cases}-\frac {1}{m}+2-m\leqslant \frac {4}{5}\\2-m\geqslant 1\end{cases}$ 无实数解
32. 当 $m>2$ 时， $0<\frac {1}{m}<\frac {1}{2}$ ， $g(x)$ 在 $[0,\frac {1}{m}]$ 上单调递减，在 $[\frac {1}{m},1]$ 上单调递增，
33. 则 $g(x){{}_{{\rm \max }}}=g(1)=0,g(x){{}_{{\rm \min }}}=g(\frac {1}{m})=-\frac {1}{m}+2-m$
34. 得 $g(x)$ 在区间 $[0,1]$ 内的值域为 $B=[-\frac {1}{m}+2-m,0]$ ，不符合题意.
35. 综上， $m$ 的取值范围为 $(-\infty ,1]$

## 知识点

**中文**:
  - 与函数有关的参数问题
  - 函数单调性的判断与证明
  - 函数奇偶性的应用

**English**:
  - Parameter Problems Related to Functions
  - Judgment and Proof of Monotonicity
  - Applications of Parity

---
