# Mathematics - 题目 2111

**ID**: 321709e025c346fda912caf0e8e0faf1
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知数列 $\left\{\begin{array}{l}a{{}_{n}}\end{array}\right \}$ 是首项为1的等差数列，数列 $\left\{\begin{array}{l}b{{}_{n}}\end{array}\right \}$ 是公比不为1的等比数列，且满足 $a{{}_{1}}+a{{}_{2}}=b{{}_{2}}$ ， $a{{}_{2}}+a{{}_{3}}=b{{}_{3}}$ ， $a{{}_{4}}+a{{}_{5}}=b{{}_{4}}$ .​​​​​​​‌(1)求数列 $\left\{\begin{array}{l}a{{}_{n}}\end{array}\right \}$ ， $\left\{\begin{array}{l}b{{}_{n}}\end{array}\right \}$ 的通项公式；(2)求 $\sum \limits_{k=1}^{2n}\mathop{}$ ；(3)令 $c{{}_{n}}=\frac {a{{}_{n+2}}b{{}_{n+2}}}{\left ({a{{}_{n}}b{{}_{n}}+1}\right )\left ({a{{}_{n+1}}b{{}_{n+1}}+1}\right )}(n\in N{{}^{*}})$ ，记数列 $\left\{\begin{array}{l}C{{}_{n}}\end{array}\right \}$ 的前 $n$ 项和为 $S{{}_{n}}$ ，求证：对任意的 $n\in {\rm{N}}{{}^{*}}$ ，都有 $1<S{{}_{n}}<\frac {4}{3}$ .

## 解答

1. （1）设 $\left\{\begin{array}{l}a{{}_{n}}\end{array}\right \}$ 的公差为 $d$ ， $\left\{\begin{array}{l}b{{}_{n}}\end{array}\right \}$ 的公比为 $q\left ({q\ne 1}\right )$ ，则 $a{{}_{n}}=1+\left ({n-1}\right )d$ ， $b{{}_{n}}=b{{}_{1}}q{{}^{n-1}}$ .
2. 由题意知， $b{{}_{3}}{{}^{2}}=b{{}_{2}}b{{}_{4}}=\left ({a{{}_{2}}+a{{}_{3}}}\right ){{}^{2}}=\left ({a{{}_{1}}+a{{}_{2}}}\right )\left ({a{{}_{4}}+a{{}_{5}}}\right )$ ，
3. 所以 $\left ({2+3d}\right ){{}^{2}}=\left ({2+d}\right )\left ({2+7d}\right )$ ，解之得 $d=2$ ， $d=0$ ，
4. 当 $d=0$ 时， $a{{}_{n}}=1$ ，则 $b{{}_{2}}=a{{}_{1}}+a{{}_{2}}=2$ ， $b{{}_{3}}=a{{}_{2}}+a{{}_{3}}=2$ ，即 $q=\frac {b{{}_{3}}}{b{{}_{2}}}=1$ 与 $q\ne 1$ 矛盾，故舍去；
5. 当 $d=2$ 时， $a{{}_{n}}=2n-1$ ，则 $b{{}_{2}}=a{{}_{1}}+a{{}_{2}}=4$ ， $b{{}_{3}}=a{{}_{2}}+a{{}_{3}}=8$ ，
6. 所以 $q=\frac {b{{}_{3}}}{b{{}_{2}}}=2$ , $b{{}_{1}}=\frac {b{{}_{2}}}{q}=2$ ，满足题意；
7. 所以 $a{{}_{n}}=2n-1$ ， $b{{}_{n}}=2{{}^{n}}$ .
8. （2）设 $T{{}_{n}}=\sum \limits_{k=1}^{2n}\mathop{}=\left ({-a{{}_{1}}b{{}_{1}}}\right )+a{{}_{2}}b{{}_{2}}+\left ({-a{{}_{3}}b{{}_{3}}}\right )+a{{}_{4}}b{{}_{4}}+\cdot \cdot \cdot +a{{}_{2n}}b{{}_{2n}}$ ，
9. $T{{}_{n}}=\left ({-a{{}_{1}}b{{}_{1}}}\right )+a{{}_{2}}b{{}_{2}}+\left ({-a{{}_{3}}b{{}_{3}}}\right )+a{{}_{4}}b{{}_{4}}+\cdot \cdot \cdot +a{{}_{2n}}b{{}_{2n}}$ ，
10. 设 $t{{}_{n}}=a{{}_{2n}}b{{}_{2n}}-a{{}_{2n-1}}b{{}_{2n-1}}=\left ({4n-1}\right )2{{}^{2n}}-\left ({4n-3}\right )2{{}^{2n-1}}=\left ({2n+\frac {1}{2}}\right )4{{}^{n}}$ ，
11. 则 $T{{}_{n}}=t{{}_{1}}+t{{}_{2}}+\cdot \cdot \cdot +t{{}_{n}}=\frac {5}{2}\times 4+\frac {9}{2}\times 4{{}^{2}}+\cdot \cdot \cdot +\left ({2n+\frac {1}{2}}\right )4{{}^{n}}$ ， $4T{{}_{n}}=\frac {5}{2}\times 4{{}^{2}}+\frac {9}{2}\times 4{{}^{3}}+\cdot \cdot \cdot +\left ({2n+\frac {1}{2}}\right )4{{}^{n+1}}$ ，
12. 两式相减得 $3T{{}_{n}}=-10-2\times 4{{}^{2}}-2\times 4{{}^{3}}-\cdot \cdot \cdot -\left ({-2}\right )\times 4{{}^{n}}+\left ({2n+\frac {1}{2}}\right )4{{}^{n+1}}$ ，
13. 所以 $T{{}_{n}}=\frac {2}{9}+\left ({\frac {2}{3}n-\frac {1}{18}}\right )4{{}^{n+1}}$ ，即 $\sum \limits_{k=1}^{2n}\mathop{}=\frac {2}{9}+\left ({\frac {2}{3}n-\frac {1}{18}}\right )4{{}^{n+1}}$ .
14. （3）证明： $c{{}_{n}}=\frac {a{{}_{n+2}}b{{}_{n+2}}}{\left ({a{{}_{n}}b{{}_{n}}+1}\right )\left ({a{{}_{n+1}}b{{}_{n+1}}+1}\right )}=\frac {\left ({2n+3}\right )2{{}^{n+2}}}{\left ({\left ({2n-1}\right )2{{}^{n}}+1}\right )\left ({\left ({2n+1}\right )2{{}^{n+1}}+1}\right )}=4\left ({\frac {1}{\left ({2n-1}\right )2{{}^{n}}+1}-\frac {1}{\left ({2n+1}\right )2{{}^{n+1}}+1}}\right )$ ，
15. $S{{}_{n}}=4\left ({\frac {1}{3}-\frac {1}{13}+\frac {1}{13}-\frac {1}{41}+\cdot \cdot \cdot +\frac {1}{\left ({2n-1}\right )2{{}^{n}}+1}-\frac {1}{\left ({2n+1}\right )2{{}^{n+1}}+1}}\right )$ ，
16. $S{{}_{n}}=4\left ({\frac {1}{3}-\frac {1}{\left ({2n+1}\right )2{{}^{n+1}}+1}}\right )$ ，
17. 因为 $n\in N{{}^{*}}$ ，易知 $S{{}_{n}}$ 随着 $n$ 的增大而增大，
18. 所以 $S{{}_{n}}\geqslant S{{}_{1}}=\frac {40}{39}>1$ ， $S{{}_{n}}<\frac {4}{3}$ ，
19. 所以 $1<S{{}_{n}}<\frac {4}{3}$ .

## 知识点

**中文**:
  - 数列求和方法之裂项相消法
  - 等差数列的概念及通项公式
  - 等比数列的概念与通项公式

**English**:
  - Telescoping Series Method
  - Concept and Formula
  - Concept and Formula

---
