# Mathematics - 题目 1565

**ID**: 4a7f86b449354e79a0664761ff86211e
**年级**: Grade 10
**难度**: Medium
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=x-2,g\left ({x}\right )=x{^{2}}-mx+4\left ({m\in {\rm{R}}}\right )$ .​​​​​​​‌（1）当 $m=5$ 时，求不等式 $g\left ({x}\right )>f\left ({x}\right )$ 的解集；（2）若对任意 $x{{}_{1}}\in \left [1,2\right ]$ ，存在 $x{{}_{2}}\in \left [4,5\right ]$ ，使得 $g\left ({x{{}_{1}}}\right )=f\left ({x{{}_{2}}}\right )$ ，求 $m$ 的取值范围.

## 解答

1. （1）当 $m=5$ 时，由 $x{^{2}}-5x+4>x-2$ 得 $x{^{2}}-6x+6>0$ ，
2. 因为方程 $x{^{2}}-6x+6=0$ 的根 $x=3\pm \sqrt {3}$ ，
3. 所以不等式 $x{^{2}}-6x+6>0$ 的解为 $x>3+\sqrt {3}$ 或 $x<3-\sqrt {3}$ ，
4. 所以不等式 $g\left ({x}\right )>f\left ({x}\right )$ 的解集为 $\{x\left |{x>3+\sqrt {3}}\right .$ 或 $x<3-\sqrt {3}\}$
5. （2）当 $x{{}_{2}}\in \left [4,5\right ]$ 时， $f\left ({x{{}_{2}}}\right )=x{{}_{2}}-2\in \left [2,3\right ]$ .
6. 又 $g\left ({x}\right )=x{^{2}}-mx+4={\left({x-\frac {m}{2}}\right)^{2}}+4-\frac {m{^{2}}}{4}$ .
7. ①当 $\frac {m}{2}\leqslant 1$ ，即 $m\leqslant 2$ 时， $g\left ({x}\right )$ 在 $\left [1,2\right ]$ 单调递增，则 $g\left ({x}\right )\in \left [5-m,8-2m\right ]$ ，
8. 由题意可知 $\left [5-m,8-2m\right ]\subseteq \left [2,3\right ]$ ，
9. 所以 $\begin{cases}m\leqslant 2\\5-m\geqslant 2\\8-2m\leqslant 3\end{cases}$ ，此时不等式组无解，
10. ②当 $1<\frac {m}{2}\leqslant \frac {3}{2}$ ，即 $2<m\leqslant 3$ 时， $g\left ({x}\right )$ 在 $\left ({1,\frac {m}{2}}\right )$ 单调递减，在 $\left ({\frac {m}{2},2}\right )$ 上单调递增，
11. 且根据二次函数对称可知，在 $x=\frac {m}{2}$ 处取得最小值，在 $x=2$ 处取得最大值，
12. 可知 $g\left ({\frac {m}{2}}\right )=4-\frac {m{^{2}}}{4},g\left ({2}\right )=8-2m$ ，所以对任意 $x{{}_{1}}\in \left [1,2\right ],g\left ({x{{}_{1}}}\right )\in \left [4-\frac {m{^{2}}}{4},8-2m\right ]\subseteq \left [2,3\right ]$ .
13. 所以 $\begin{cases}2<m\leqslant 3\\4-\frac {m{^{2}}}{4}\geqslant 2\\8-2m\leqslant 3\end{cases}$ ，解得 $\frac {5}{2}\leqslant m\leqslant 2\sqrt {2}$ ，
14. ③当 $\frac {3}{2}<\frac {m}{2}<2$ ，即 $3<m<4$ 时， $g\left ({x}\right )$ 在 $\left ({1,\frac {m}{2}}\right )$ 单调递减，在 $\left ({\frac {m}{2},2}\right )$ 上单调递增，
15. 且根据二次函数对称可知，在 $x=\frac {m}{2}$ 处取得最小值，在 $x=1$ 处取得最大值，
16. 可知 $g\left ({1}\right )=5-m$ ，所以对任意 $x{{}_{1}}\in \left [1,2\right ],g\left ({x{{}_{1}}}\right )\in \left [4-\frac {m{^{2}}}{4},5-m\right ]\subseteq \left [2,3\right ]$ .
17. 所以 $\begin{cases}3<m<4\\4-\frac {m{^{2}}}{4}\geqslant 2\\5-m\leqslant 3\end{cases}$ ，解得 $3<m<2\sqrt {2}$ ，
18. ④当 $\frac {m}{2}\geqslant 2$ ，即 $m\geqslant 4$ 时， $g\left ({x}\right )$ 在 $\left [1,2\right ]$ 单调递减，则对任意 $x{{}_{1}}\in \left [1,2\right ],g\left ({x{{}_{1}}}\right )\in \left [8-2m,5-m\left ]{\subseteq }\right [2,3\right ]$ .
19. 所以 $\begin{cases}m\geqslant 4\\8-2m\geqslant 2\\5-m\leqslant 3\end{cases}$ ，此时不等式组无解.
20. 综上，实数 $m$ 的取值范围是 $\left [\frac {5}{2},2\sqrt {2}\right ]$

## 知识点

**中文**:
  - 一元二次不等式及其解法（不含参）
  - 二次函数的图象与性质

**English**:
  - Solving Quadratic Inequalities (No Parameters)
  - Graph and Properties of Quadratic Functions

---
