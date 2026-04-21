# Mathematics - 题目 2731

**ID**: e1190d5e4a3e4a0da19f7fe76c2276e8
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ 为等差数列，首项 $a{{}_{1}}=1$ ，公差 $d=2$ ．(1)若 $b{{}_{n}}=3{^{a{{}_{n}}+1}}$ ，证明： $\left \{b{{}_{n}}\right \}$ 是等比数列；​​​​​​​‌(2)若 $c{{}_{n}}=\frac {1}{a{{}_{n}}a{{}_{n+1}}}$ ，设数列 $\left \{c{{}_{n}}\right \}$ 的前 $n$ 项和为 $S{{}_{n}}$ ，求满足 $S{{}_{n}}>\frac {12}{25}$ 的 $n$ 的最小值．(3)若 $d{{}_{n}}=12-a{{}_{n}}$ ，求数列 $\left \{\left |{d{{}_{n}}}\right |\right \}$ 的前 $n$ 项和 $T{{}_{n}}$ ；

## 解答

1. （1）因为数列 $\left \{a{{}_{n}}\right \}$ 为等差数列，首项 $a{{}_{1}}=1$ ，公差 $d=2$ ，
2. 所以 $a{{}_{n}}=1+2\left ({n-1}\right )=2n-1$ .
3. 对于 $b{{}_{n}}=3{^{a{{}_{n}}+1}}=3{^{2n}}\ne 0$ ，且 $\frac {b{{}_{n+1}}}{b{{}_{n}}}=\frac {3{^{2n+2}}}{3{^{2n}}}=9$ ，
4. 所以 $\left \{b{{}_{n}}\right \}$ 是等比数列.
5. （2）由（1）可知： $c{{}_{n}}=\frac {1}{a{{}_{n}}a{{}_{n+1}}}=\frac {1}{\left ({2n-1}\right )\left ({2n+1}\right )}=\frac {1}{2}\left ({\frac {1}{2n-1}-\frac {1}{2n+1}}\right )$ ，
6. 可得 $S{{}_{n}}=\frac {1}{2}\left ({1-\frac {1}{3}+\frac {1}{3}-\frac {1}{5}+\cdot \cdot \cdot +\frac {1}{2n-1}-\frac {1}{2n+1}}\right )=\frac {1}{2}\left ({1-\frac {1}{2n+1}}\right )$ ，
7. 令 $S{{}_{n}}=\frac {1}{2}\left ({1-\frac {1}{2n+1}}\right )>\frac {12}{25}$ ，解得 $n>12$ ，
8. 所以满足 $S{{}_{n}}>\frac {12}{25}$ 的 $n$ 的最小值为13.
9. （3）由（1）可知： $d{{}_{n}}=12-a{{}_{n}}=13-2n$ ，
10. 则 $d{{}_{n+1}}-d{{}_{n}}=\left ({11-2n}\right )-\left ({13-2n}\right )=-2$ ，可知数列 $\left \{d{{}_{n}}\right \}$ 为等差数列，
11. 设数列 $\left \{d{{}_{n}}\right \}$ 的前n项和为 $D{{}_{n}}$ ，则 $D{{}_{n}}=\frac {n\left ({11+13-2n}\right )}{2}=-n{^{2}}+12n$ ，
12. 令 $d{{}_{n}}=13-2n>0$ ，解得 $n<\frac {13}{2}$ ，
13. 当 $n\leqslant 6$ 时， $d{{}_{n}}>0$ ，则 $T{{}_{n}}=\left |{d{{}_{1}}}\right |+\left |{d{{}_{2}}}\right |+\cdot \cdot \cdot \left |{d{{}_{n}}}\right |=d{{}_{1}}+d{{}_{2}}+\cdot \cdot \cdot +d{{}_{n}}=D{{}_{n}}=-n{^{2}}+12n$ ；
14. 当 $n\geqslant 7$ 时， $d{{}_{n}}<0$ ，则 $T{{}_{n}}=\left |{d{{}_{1}}}\right |+\left |{d{{}_{2}}}\right |+\cdot \cdot \cdot \left |{d{{}_{n}}}\right |$
15. $=\left ({d{{}_{1}}+\cdot \cdot \cdot +d{{}_{6}}}\right )-\left ({d{{}_{7}}+\cdot \cdot \cdot +d{{}_{n}}}\right )$
16. $=D{{}_{6}}-\left ({D{{}_{n}}-D{{}_{6}}}\right )=-D{{}_{n}}+2D{{}_{6}}=n{^{2}}-12n+72$ ；
17. 综上所述： $T{{}_{n}}=\begin{cases}-n{^{2}}+12n,n\leqslant 6\\n{^{2}}-12n+72,n\geqslant 7\end{cases}$ .

## 知识点

**中文**:
  - 数列求和方法之分组转化法
  - 等差数列的概念及通项公式
  - 等比数列的判定与证明
  - 数列求和方法之裂项相消法

**English**:
  - Grouping Method
  - Concept and Formula
  - Determination and Proof
  - Telescoping Series Method

---
