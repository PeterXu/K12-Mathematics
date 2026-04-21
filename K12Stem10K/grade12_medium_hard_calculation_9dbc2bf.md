# Mathematics - 题目 3126

**ID**: 9dbc2bfed67a4ae3b7bd266b3b65ca18
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知 $f\left ({x}\right )={\log}{{}_{2}}\left ({9{^{x}}-4\times 3{^{x+1}}+43}\right )$ ， $g\left ({x}\right )=x{^{2}}-2mx+{\log}{{}_{2}}7$ .​​​​​​​‌（1）求不等式 $f\left ({x}\right )\leqslant 4$ 的解集；（2）设函数 $h\left ({x}\right )=g\left ({x}\right )-{\log}{{}_{2}}7$ ，若存在实数 $x$ ，使得 $h\left ({4{^{-x}}}\right )=-h\left ({4{^{x}}}\right )$ 成立，求实数m的取值范围；（3）若 $\forall x{{}_{1}}\in \left [1,2\right ]$ ， $\exists x{{}_{2}}\in \left [1,2\right ]$ ，使得 $f\left ({x{{}_{1}}}\right )\geqslant g\left ({x{{}_{2}}}\right )$ ，求实数 $m$ 的取值范围.

## 解答

1. （1）由 $9{^{x}}-4\times 3{^{x+1}}+43={\left({3{^{x}}-6}\right)^{2}}+7>0$ 可知函数 $f\left ({x}\right )$ 的定义域为R，
2. 因 $f\left ({x}\right )={\log}{{}_{2}}\left ({9{^{x}}-4\times 3{^{x+1}}+43}\right )\leqslant 4={\log}{{}_{2}}16$ ，
3. 结合对数函数的单调性可得， $9{^{x}}-4\times 3{^{x+1}}+43\leqslant 16$ ，即 ${\left({3{^{x}}}\right)^{2}}-12\times 3{^{x}}+27\leqslant 0$ ，
4. 解得 $3\leqslant 3{^{x}}\leqslant 9$ ，得 $1\leqslant x\leqslant 2$ ，
5. 故不等式 $f\left ({x}\right )\leqslant 4$ 的解集为 $\left \{x\left |{1\leqslant x\leqslant 2}\right .\right \}$ .
6. （2）由题可得 $h\left ({x}\right )=x{^{2}}-2mx$ ，
7. 因存在实数 $x$ ，使得 $h\left ({4{^{-x}}}\right )=-h\left ({4{^{x}}}\right )$ 成立，
8. 即存在实数 $x$ ，使得 ${\left({4{^{-x}}}\right)^{2}}-2m\left ({4{^{-x}}}\right )=-{\left({4{^{x}}}\right)^{2}}+2m\left ({4{^{x}}}\right )$ 成立，
9. 所以方程 $2m=\frac {{\left({4{^{-x}}}\right)^{2}}+{\left({4{^{x}}}\right)^{2}}}{4{^{-x}}+4{^{x}}}=\frac {{\left({4{^{-x}}+4{^{x}}}\right)^{2}}-2}{4{^{-x}}+4{^{x}}}=4{^{-x}}+4{^{x}}-\frac {2}{4{^{-x}}+4{^{x}}}$ 有实数解，
10. 令 $s=4{^{-x}}+4{^{x}}\geqslant 2\sqrt {4{^{-x}}\times 4{^{x}}}=2$ ，当且仅当 $4{^{-x}}=4{^{x}}$ 即 $x=0$ 时等号成立，
11. 所以方程 $2m=s-\frac {2}{s},s\geqslant 2$ 有实数解，
12. 因为 $y=x$ 和 $y=-\frac {2}{x}$ 为 $\left [{2,+\infty }\right )$ 上的增函数，所以 $y=x-\frac {2}{x}$ 为 $\left [{2,+\infty }\right )$ 上的增函数，
13. 所以 $s-\frac {2}{s}\geqslant 2-\frac {2}{2}=1$ ，所以 $2m\geqslant 1$ ，得 $m\geqslant \frac {1}{2}$ ，
14. 所以实数m的取值范围为 $\left [{\frac {1}{2},+\infty }\right )$ ；
15. （3）由题意 $\forall x{{}_{1}}\in \left [1,2\right ],\exists x{{}_{2}}\in \left [1,2\right ]$ ，使得 $f\left ({x{{}_{1}}}\right )\geqslant g\left ({x{{}_{2}}}\right )$ ，所以 $f\left ({x}\right ){{}_{{\rm \min }}}\geqslant g\left ({x}\right ){{}_{{\rm \min }}}$ ，
16. 由（1）知 $f\left ({x}\right )={\log}{{}_{2}}\left [{\left({3{^{x}}-6}\right)^{2}}+7\right ]$ ，
17. 因为 $x{{}_{1}}\in \left [1,2\right ]$ ，所以 $3\leqslant 3{^{x{{}_{1}}}}\leqslant 9$ ， $7\leqslant {\left({3{^{x{{}_{1}}}}-6}\right)^{2}}+7\leqslant 16$ ，所以 $f\left ({x}\right ){{}_{{\rm \min }}}={\log}{{}_{2}}7$ ，
18. 因为 $g\left ({x}\right )=x{^{2}}-2mx+{\log}{{}_{2}}7={\left({x-m}\right)^{2}}-m{^{2}}+{\log}{{}_{2}}7$ ，
19. ①当 $m\mathrm{\leqslant }1$ 时， $g\left ({x}\right )$ 在区间 $\left [1,2\right ]$ 上单调递增，所以 $g\left ({x}\right ){{}_{{\rm \min }}}=g\left ({1}\right )=1-2m+{\log}{{}_{2}}7$ ，
20. 则 $1-2m+{\log}{{}_{2}}7\leqslant {\log}{{}_{2}}7$ ，得 $m\geqslant \frac {1}{2}$ ，所以 $\frac {1}{2}\leqslant m\leqslant 1$ ；
21. ②当 $1<m<2$ 时， $g\left ({x}\right )$ 在区间 $\left [1,m\right ]$ 上单调递减，在区间 $\left ({m,2}\right ]$ 上单调递增，
22. 所以 $g\left ({x}\right ){{}_{{\rm \min }}}=g\left ({m}\right )=-m{^{2}}+{\log}{{}_{2}}7$ ，则 $-m{^{2}}+{\log}{{}_{2}}7\leqslant {\log}{{}_{2}}7$ ，即 $m{^{2}}\geqslant 0$ ，
23. 所以 $1<m<2$ ；
24. ③当 $m\mathrm{\geqslant }2$ 时， $g\left ({x}\right )$ 在区间 $\left [1,2\right ]$ 上单调递减，所以 $g\left ({x}\right ){{}_{{\rm \min }}}=g\left ({2}\right )=4-4m+{\log}{{}_{2}}7$ ，
25. 则 $4-4m+{\log}{{}_{2}}7\leqslant {\log}{{}_{2}}7$ ，得 $m\geqslant 1$ ，所以 $m\mathrm{\geqslant }2$ ；
26. 综上所述，满足题意的实数 $m$ 的取值范围为 $\left [{\frac {1}{2},+\infty }\right )$ .

## 知识点

**中文**:
  - 对数函数性质的综合应用
  - 指数函数的单调性
  - 对数函数的单调性

**English**:
  - Comprehensive Application of Logarithmic Function Properties
  - Monotonicity of Exponential Functions
  - Monotonicity of Logarithmic Functions

---
