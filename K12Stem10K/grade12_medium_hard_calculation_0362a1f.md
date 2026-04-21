# Mathematics - 题目 1348

**ID**: 0362a1fe8bc44668b670283172024e30
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知定义在 ${\mathbf{R}}$ 上的函数 $f\left ({x}\right )$ 满足 $f\left ({-x}\right )-f\left ({x}\right )=0$ 且 $f\left ({x}\right )={\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}\left ({2{^{x}}+1}\right )+kx$ ， $g\left ({x}\right )=f\left ({x}\right )+x$ ．（1）求 $f\left ({x}\right )$ 的解析式；​​​​​​​‌（2）若不等式 $g\left ({4{^{x}}-a\cdot 2{^{x}}+1}\right )>g\left ({-3}\right )$ 恒成立，求实数 $a$ 取值范围；（3）设 $h\left ({x}\right )=x{^{2}}-2mx+1$ ，若对任意的 $x{{}_{1}}\in \left [0,3\right ]$ ，存在 $x{{}_{2}}\in \left [1,3\right ]$ ，使得 $g\left ({x{{}_{1}}}\right )\geqslant h\left ({x{{}_{2}}}\right )$ ，求实数 $m$ 取值范围．

## 解答

1. （1）由题意知， ${\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}\left ({2{^{-x}}+1}\right )-kx-{\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}\left ({2{^{x}}+1}\right )-kx=0$ ，
2. 即 $2kx={\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}\left ({2{^{-x}}+1}\right )-{\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}\left ({2{^{x}}+1}\right )={\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}\frac {2{^{-x}}+1}{2{^{x}}+1}={\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}\left [\left ({\frac {2{^{x}}+1}{2{^{x}}+1}}\right )\cdot 2{^{-x}}\right ]=-x$ ，所以 $k=-\frac {1}{2}$ ，
3. 故 $f\left ({x}\right )={\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}\left ({2{^{x}}+1}\right )-\frac {1}{2}x$
4. （2）由（1）知， $g\left ({x}\right )=f\left ({x}\right )+x={\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}\left ({2{^{x}}+1}\right )+\frac {1}{2}x$ ，
5. 所以 $g\left ({x}\right )$ 在 ${\rm R}$ 上单调递增，
6. 所以不等式 $g\left ({4{^{x}}-a\cdot 2{^{x}}+1}\right )>g\left ({-3}\right )$ 恒成立等价于 $4{^{x}}-a\cdot 2{^{x}}+1>-3$ 恒成立，
7. 即 $a<\frac {4{^{x}}+4}{2{^{x}}}$ 恒成立．
8. 设 $t=2{^{x}}$ ，则 $t>0$ ， $\frac {4{^{x}}+4}{2{^{x}}}=\frac {t{^{2}}+4}{t}=t+\frac {4}{t}\geqslant 4$ ，当且仅当 $t=2$ ，即 $x=1$ 时，等号成立
9. 所以 $a<4$ ，
10. 故实数 $a$ 的取值范围是 $\left ({-∞,4}\right )$
11. （3）因为对任意的 $x{{}_{1}}\in \left [0,3\right ]$ ，存在 $x{{}_{2}}\in \left [1,3\right ]$ ，使得 $g\left ({x{{}_{1}}}\right )\geqslant h\left ({x{{}_{2}}}\right )$ ，
12. 所以 $g\left ({x}\right )$ 在 $\left [0,3\right ]$ 上的最小值不小于 $h\left ({x}\right )$ 在 $\left [1,3\right ]$ 上的最小值，
13. 因为 $g\left ({x}\right )={\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}\left ({2{^{x}}+1}\right )+\frac {1}{2}x$ 在 $\left [0,3\right ]$ 上单调递增，
14. 所以当 $x\in \left [0,3\right ]$ 时， $g\left ({x}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=g\left ({0}\right )=1$ ，
15. 又 $h\left ({x}\right )=x{^{2}}-2mx+1$ 的对称轴为 $x=m$ ， $x\in \left [1,3\right ]$ ，
16. 当 $m\mathrm{\leqslant }1$ 时， $h\left ({x}\right )$ 在 $\left [1,3\right ]$ 上单调递增， $h\left ({x}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=h\left ({1}\right )=2-2m\leqslant 1$ ，解得 $m\geqslant \frac {1}{2}$ ，
17. 所以 $\frac {1}{2}\leqslant m\leqslant 1$ ；
18. 当 $1<m<3$ 时， $h\left ({x}\right )$ 在 $\left [{1,m}\right )$ 上单调递减，在 $\left [m,3\right ]$ 上单调递增，
19. $h\left ({x}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=h\left ({m}\right )=1-m{^{2}}\leqslant 1$ ，解得 $m\in {\rm{R}}$ ，所以 $1<m<3$ ；
20. 当 $m\geqslant 3$ 时， $h\left ({x}\right )$ 在 $\left [1,3\right ]$ 上单调递减， $h\left ({x}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=h\left ({3}\right )=10-6m\leqslant 1$ ，解得 $m\geqslant \frac {3}{2}$ ，
21. 所以 $m\geqslant 3$ ，
22. 综上可知，实数 $m$ 的取值范围是 $\left [{\frac {1}{2},+\infty }\right )$

## 知识点

**中文**:
  - 与函数有关的参数问题
  - 与函数有关的恒成立问题
  - 对数函数的概念

**English**:
  - Parameter Problems Related to Functions
  - Universally True Problems Related to Functions
  - Concept of Logarithmic Functions

---
