# Mathematics - 题目 1005

**ID**: d2eb01f3849344cfafca1942edac869f
**年级**: Grade 10
**难度**: Medium
**题型**: Calculation

## 题目
设函数 $f\left ({x}\right )=x{^{2}}+ax+3$ ， $a\in {\rm{R}}$ .​​​​​​​‌（1）若对于任意的 $x\in \left [2,4\right ]$ ， $f\left ({x}\right )\geqslant 0$ 恒成立，求a的取值范围；（2）若 $f\left ({x}\right )<6-6x$ 的解集为 $\left ({-1,b}\right )$ .①求a，b的值;②求函数 $h\left ({x}\right )=2x+3-f\left ({x}\right )$ 在 $x\in \left [t,t+2\right ]$ 的最大值 $g\left ({t}\right )$ .

## 解答

1. （1）法1：由题知，任意 $x\in \left [2,4\right ]$ 有 $f\left ({x}\right )\geqslant 0$ ，即当 $x\in \left [2,4\right ]$ ，只需 $f\left ({x}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}\geqslant 0$ ，
2. 由 $f\left ({x}\right )=x{^{2}}+ax+3$ 的对称轴为 $x=-\frac {a}{2}$ ，
3. 当 $-\frac {a}{2}\leqslant 2$ ，即 $a\geqslant -4$ 时， $f\left ({x}\right )$ 在 $\left [2,4\right ]$ 上单调递增，
4. 此时 $f\left ({x}\right ){{}_{{\rm \min }}}=f\left ({2}\right )=7+2a\geqslant 0$ ，即 $a\geqslant -\frac {7}{2}$ ；
5. 当 $2<-\frac {a}{2}<4$ ，即 $-8<a<-4$ 时， $f\left ({x}\right )$ 在 $\left [2,-\frac {a}{2}\right ]$ 上单调递减，在 $\left [-\frac {a}{2},2\right ]$ 上单调递增，
6. 此时 $f\left ({x}\right ){{}_{{\rm \min }}}=f\left ({-\frac {a}{2}}\right )=3-\frac {1}{4}a{^{2}}\geqslant 0$ ，解得 $-2\sqrt {3}\leqslant a<2\sqrt {3}$ ，与前提矛盾，舍去；
7. 当 $-\frac {a}{2}\geqslant 4$ ，即 $a\leqslant -8$ 时， $f\left ({x}\right )$ 在 $\left [2,4\right ]$ 上单调递减，
8. 此时 $f\left ({x}\right ){{}_{{\rm \min }}}=f\left ({4}\right )=19+4a\geqslant 0$ ，即 $a\geqslant -\frac {19}{4}$ ，与前提矛盾，舍去.
9. 综上所述：a的取值范围 $\left [{-\frac {7}{2},+∞}\right )$ .
10. 法2：由题，得 $f\left ({x}\right )=x{^{2}}+ax+3\geqslant 0$ 对任意 $x\in \left [2,4\right ]$ 都成立，即 $a\geqslant -x-\frac {3}{x}$ ，
11. 令 $g\left ({x}\right )=-x-\frac {3}{x}\left ({x\in \left [2,4\right ]}\right )$ ，则 $a\geqslant g\left ({x}\right ){{}_{{\rm \max }}}$ ，
12. 令 $h\left ({x}\right )=x+\frac {3}{x}$ ，则 $h\left ({x}\right )=x+\frac {3}{x}$ 在 $\left [2,4\right ]$ 上单调递增，
13. 则 $g\left ({x}\right )=-h\left ({x}\right )$ 在 $\left [2,4\right ]$ 上单调递减，故 $g\left ({x}\right ){{}_{{\rm \max }}}=g\left ({2}\right )=-\frac {7}{2}$ ，即 $a\geqslant -\frac {7}{2}$ ，
14. 所以a的取值范围 $\left [{-\frac {7}{2},+∞}\right )$ .
15. （2）① $x{^{2}}+ax+3<6-6x$ ，即 $x{^{2}}+\left ({a+6}\right )x-3<0$ 的解集为 $\left ({-1,b}\right )$ ，
16. 则有 $\begin{cases}-\left ({a+6}\right )=-1+b\\-3=-b\end{cases}$ ，解得 $\begin{cases}a=-8\\b=3\end{cases}$ ，
17. ②由于 $h\left ({x}\right )=2x+3-f\left ({x}\right )=2x+3-\left ({x{^{2}}-8x+3}\right )=-x{^{2}}+10x=-{\left({x-5}\right)^{2}}+25$
18. 当 $t+2\leqslant 5$ ，即 $t\leqslant 3$ 时， $f\left ({x}\right )$ 在 $\left [t,t+2\right ]$ 上单调递增，
19. 所以 $h\left ({x}\right ){{}_{{\rm \max }}}=h\left ({t+2}\right )=-{\left({t-3}\right)^{2}}+25=-t{^{2}}+6t+16=g\left ({t}\right )$ ；
20. 当 $t<5<t+2$ ，即 $3<t<5$ 时， $f\left ({x}\right )$ 在 $\left [t,5\right ]$ 上单调递增，在 $\left [5,t+2\right ]$ 上单调递减，
21. 所以 $h\left ({x}\right ){{}_{{\rm \max }}}=h\left ({5}\right )=25=g\left ({t}\right )$ ；
22. 当 $t\geqslant 5$ 时， $f\left ({x}\right )$ 在 $\left [t,t+2\right ]$ 单调递减，所以 $h\left ({x}\right ){{}_{{\rm \max }}}=h\left ({t}\right )=-t{^{2}}+10t=g\left ({t}\right )$ ；
23. 综上所述，所以 $g\left ({t}\right )=\begin{cases}-t{^{2}}+6t+16,t\leqslant 3\\25,3<t<5\\-t{^{2}}+10t,t\geqslant 5\end{cases}$

## 知识点

**中文**:
  - 一元二次不等式恒成立问题与有解问题
  - 二次函数的图象与性质

**English**:
  - Universally True and Solvable Problems
  - Graph and Properties of Quadratic Functions

---
