# Mathematics - 题目 2786

**ID**: 454343cff3824a45809afe36320db8d3
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=a{^{x}}$ （ $a>0$ ，且 $a\ne 1$ ）过点 $\left ({-1{\rm{,}}\frac {1}{2}}\right )$ ．(1)求函数 $f\left ({x}\right )$ 的解析式；​​​​​​​‌(2)若函数 $h\left ({x}\right )$ 为 $f\left ({x}\right )$ 的反函数，且 $h\left ({x{^{2}}-bx+6}\right )$ 在 $\left ({1,5}\right )$ 上单调递增，求b的取值范围；(3)若函数 $f\left ({x}\right )=g\left ({x}\right )+m\left ({x}\right )$ ，其中 $g\left ({x}\right )$ 为奇函数， $m\left ({x}\right )$ 为偶函数，已知函数 $w\left ({x}\right )=\left |{x}\right |$ ，对于任意 $x{{}_{1}}\in \left [\frac {1}{2}{\rm{,}}3\right ]$ ，都存在 $x{{}_{2}}\in {\mathbf{R}}$ ，使得等式 $2cg\left ({x{{}_{1}}}\right )+m\left ({2x{{}_{1}}}\right )=w\left ({x{{}_{2}}}\right )$ 成立，求实数c的取值范围．

## 解答

1. （1）∵函数 $f\left ({x}\right )=a{^{x}}$ 过点 $\left ({-1{\rm{,}}\frac {1}{2}}\right )$ ，
2. ∴ $a{^{-1}}=\frac {1}{2}$ ，解得 $a=2$ ，故函数解析式为 $f\left ({x}\right )=2{^{x}}$ .
3. （2）∵函数 $h(x)$ 为 $f\left ({x}\right )$ 的反函数，∴ $h\left ({x}\right )={\log}{{}_{2}}x$ ， $h(x)$ 在 $(0,+\infty )$ 上为增函数，
4. ∵ $h\left ({x{^{2}}-bx+6}\right )$ 在 $\left ({1,5}\right )$ 上单调递增，
5. ∴ $y=x{^{2}}-bx+6$ 在 $\left ({1,5}\right )$ 上单调递增，且当 $x\in \left ({1,5}\right )$ 时， $x{^{2}}-bx+6>0$ ，
6. ∵ $y=x{^{2}}-bx+6$ 对称轴为直线 $x=\frac {b}{2}$ ，∴ $\begin{cases}\frac {b}{2}\leqslant 1\\1{^{2}}-b+6\geqslant 0\end{cases}$ ，解得 $b\leqslant 2$ ，
7. ∴b的取值范围为 $(-\infty ,2]$ .
8. （3）∵ $f\left ({x}\right )=g\left ({x}\right )+m\left ({x}\right )=2{^{x}}$ ，
9. ∴ $f\left ({-x}\right )=g\left ({-x}\right )+m\left ({-x}\right )=2{^{-x}}$ ，
10. ∵ $g\left ({x}\right )$ 为奇函数， $m\left ({x}\right )$ 为偶函数，∴ $-g\left ({x}\right )+m\left ({x}\right )=2{^{-x}}$ ，
11. ∴ $g\left ({x}\right )=\frac {2{^{x}}-2{^{-x}}}{2}$ ， $m\left ({x}\right )=\frac {2{^{x}}+2{^{-x}}}{2}$ .
12. ∵ $w\left ({x}\right )=\left |{x}\right |$ ， $x{{}_{2}}\in {\mathbf{R}}$ ，∴ $w\left ({x{{}_{2}}}\right )\geqslant 0$ ，
13. ∵对于任意 $x{{}_{1}}\in \left [\frac {1}{2}{\rm{,}}3\right ]$ ，都存在 $x{{}_{2}}\in {\mathbf{R}}$ ，使得等式 $2cg\left ({x{{}_{1}}}\right )+m\left ({2x{{}_{1}}}\right )=w\left ({x{{}_{2}}}\right )$ 成立，
14. ∴ $2cg\left ({x}\right )+m\left ({2x}\right )\geqslant 0$ 在 $x\in \left [\frac {1}{2}{\rm{,}}3\right ]$ 上恒成立，
15. ∵ $y=2{^{x}}$ 在 $\left [\frac {1}{2}{\rm{,}}3\right ]$ 上为增函数， $y=2{^{-x}}$ 在 $\left [\frac {1}{2}{\rm{,}}3\right ]$ 上为减函数，∴ $g\left ({x}\right )$ 在 $\left [\frac {1}{2}{\rm{,}}3\right ]$ 上为增函数.
16. 令 $t=g\left ({x}\right )=\frac {2{^{x}}-2{^{-x}}}{2},t\in \left [\frac {\sqrt {2}}{4},\frac {63}{16}\right ]$ ，则 $m\left ({2x}\right )=\frac {2{^{2x}}+2{^{-2x}}}{2}=\frac {{\left({2{^{x}}-2{^{-x}}}\right)^{2}}+2}{2}=\frac {{\left({2t}\right)^{2}}+2}{2}=2t{^{2}}+1$ ，
17. 问题转化为 $2ct+2t{^{2}}+1\geqslant 0$ 在 $t\in \left [\frac {\sqrt {2}}{4},\frac {63}{16}\right ]$ 上恒成立，∴ $c\geqslant -\frac {2t{^{2}}+1}{2t}$ 恒成立，即 $c\geqslant \left ({-\frac {2t{^{2}}+1}{2t}}\right ){{}_{{\rm \max }}}$ ，
18. ∵ $\frac {2t{^{2}}+1}{2t}=t+\frac {1}{2t}\geqslant 2\sqrt {t\cdot \frac {1}{2t}}=\sqrt {2}$ ，当且仅当 $t=\frac {1}{2t}$ ，即 $t=\frac {\sqrt {2}}{2}$ 时等号成立，
19. ∴ $-\frac {2t{^{2}}+1}{2t}\leqslant -\sqrt {2}$ ，即 $\left ({-\frac {2t{^{2}}+1}{2t}}\right ){{}_{{\rm \max }}}=-\sqrt {2}$ ，∴ $c\geqslant -\sqrt {2}$ ，
20. ∴实数c的取值范围为 $[-\sqrt {2},+\infty )$ .

## 知识点

**中文**:
  - 反函数
  - 指数函数的概念
  - 指数函数性质的综合应用
  - 对数函数的单调性

**English**:
  - Inverse Functions
  - Concept of Exponential Functions
  - Comprehensive Application of Exponential Function Properties
  - Monotonicity of Logarithmic Functions

---
