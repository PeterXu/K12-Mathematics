# Mathematics - 题目 690

**ID**: e3f83148d6444fcfb5871f5546f02e79
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=2x{^{3}}-ax{^{2}}+2\left ({a>0}\right )$ ．(1)求曲线 $y=f\left ({x}\right )$ 在点 $\left ({0,f\left ({0}\right )}\right )$ 处的切线方程；​​​​​​​‌(2)若在区间 $\left [-1,1\right ]$ 内存在 $x{{}_{1}},x{{}_{2}}$ ，使得 $f\left ({x{{}_{1}}}\right )\cdot f\left ({x{{}_{2}}}\right )\geqslant 9$ ，求实数 $a$ 的取值范围．

## 解答

1. （1）因为 $f\left ({x}\right )=2x{^{3}}-ax{^{2}}+2\left ({a>0}\right )$ ，所以 $f\left ({0}\right )=2$ ，
2. 又 $f^{′}{\left ({x}\right )}=6x{^{2}}-2ax$ ，所以 $f^{′}{\left ({0}\right )}=0$ ，所以曲线 $y=f\left ({x}\right )$ 在点 $\left ({0,f\left ({0}\right )}\right )$ 处的切线方程为 $y=2$ ；
3. （2）因为 $f^{′}{\left ({x}\right )}=6x{^{2}}-2ax=6x\left ({x-\frac {a}{3}}\right )$ ，又 $a>0$ ，
4. 所以当 $0<x<\frac {a}{3}$ 时 $f^{′}{\left ({x}\right )}<0$ ，当 $x<0$ 或 $x>\frac {a}{3}$ 时 $f^{′}{\left ({x}\right )}>0$ ，
5. 所以 $f\left ({x}\right )$ 在 $\left ({0,\frac {a}{3}}\right )$ 上单调递减，在 $\left ({-\infty ,0}\right ),\left ({\frac {a}{3},+\infty }\right )$ 上单调递增，
6. 则在区间 $\left [-1,1\right ]$ 内存在 $x{{}_{1}},x{{}_{2}}$ ，使得 $f\left ({x{{}_{1}}}\right )\cdot f\left ({x{{}_{2}}}\right )\geqslant 9$ ，
7. 等价于在区间 $\left [-1,1\right ]$ 内存在 $x$ ，使得 $f{^{2}}\left ({x}\right )\geqslant 9$ ，
8. 等价于在区间 $\left [-1,1\right ]$ 内存在 $x$ ，使得 $\left |{f\left ({x}\right )}\right |\geqslant 3$ ，
9. 等价于在区间 $\left [-1,1\right ]$ 内， $\left |{f\left ({x}\right )}\right |$ 的最大值不小于 $3$ ，
10. 不妨令 $g\left ({x}\right )=\left |{f\left ({x}\right )}\right |$ ，
11. ①当 $\frac {a}{3}\geqslant 1$ ，即 $a\geqslant 3$ 时， $f\left ({x}\right )$ 在 $\left [-1,0\right ]$ 上单调递增，在 $\left [0,1\right ]$ 上单调递减，
12. 且 $f\left ({-1}\right )=-a\leqslant -3$ ， $f\left ({0}\right )=2$ ， $f\left ({1}\right )=4-a\leqslant 1$ ，
13. 所以 $g\left ({x}\right ){{}_{{\rm \max }}}=\left |{f\left ({x}\right )}\right |{{}_{{\rm \max }}}={\rm \max }\left \{a,2,\left |{4-a}\right |\right \}\geqslant 3$ ，符合题意；
14. ②当 $0<\frac {a}{3}<1$ ，即 $0\mathrm{<}a\mathrm{<}3$ 时， $f\left ({x}\right )$ 在 $\left [-1,0\right ]$ 和 $\left [\frac {a}{3},1\right ]$ 上单调递增，在 $\left [0,\frac {a}{3}\right ]$ 上单调递减，显然 $f\left ({x}\right )$ 在 $x=\frac {a}{3}$ 处取得极小值，此时极小值为 $f\left ({\frac {a}{3}}\right )=2-\frac {a{^{3}}}{27}>0$ ，
15. 而 $f\left ({-1}\right )=-a\in \left ({-3,0}\right )$ ， $f\left ({0}\right )=2$ ， $f\left ({1}\right )=4-a>0$ ，
16. 所以 $g\left ({x}\right ){{}_{{\rm \max }}}=\left |{f\left ({x}\right )}\right |{{}_{{\rm \max }}}={\rm \max }\left \{a,2,\left |{4-a}\right |\right \}$ ，
17. 要使 $g\left ({x}\right ){{}_{{\rm \max }}}\geqslant 3$ ，则必有 $4-a\geqslant 3$ ，解得 $a\leqslant 1$ ，故 $0<a\leqslant 1$ ，
18. 综上可得 $a$ 的取值范围为 $\left ({0,1}\right ]\cup \left [{3,+\infty }\right )$ .

## 知识点

**中文**:
  - 利用导数解决不等式能成立问题
  - 导数几何意义的应用

**English**:
  - Solving Solvable Inequality Problems
  - Applications of Geometric Meaning of Derivatives

---
