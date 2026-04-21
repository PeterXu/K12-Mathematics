# Mathematics - 题目 3802

**ID**: 0d721b9e188f451bbd4e8c447c82001f
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
在正项数列 $\left \{a{{}_{n}}\right \}$ 中， $a{{}_{1}}=4,a{{}_{n+1}}-a{{}_{n}}=2\sqrt {a{{}_{n}}}+1$ .​​​​​​​‌（1）证明：数列 $\left \{\sqrt {a{{}_{n}}}\right \}$ 是等差数列；（2）设 $b{{}_{n}}=(-1){^{n}}a{{}_{n}}$ ，求数列 $\left \{b{{}_{n}}\right \}$ 的前 $n$ 项和 $S{{}_{n}}$ ；（3）若不等式 $\left ({1+\frac {1}{a{{}_{1}}}}\right )\left ({1+\frac {1}{a{{}_{2}}}}\right )\cdots \left ({1+\frac {1}{a{{}_{n}}}}\right )\leqslant \frac {25}{18}m\times {\left({\frac {11}{10}}\right)^{n}}$ 对 $\forall n\in {\mathbf{N}}{^{*}}$ 都成立，求 $m$ 的取值范围.

## 解答

1. （1）因 $a{{}_{n+1}}-a{{}_{n}}=2\sqrt {a{{}_{n}}}+1$ ，则 $a{{}_{n+1}}={\left({\sqrt {a{{}_{n}}}+1}\right)^{2}}$ ，
2. 因数列 $\left \{a{{}_{n}}\right \}$ 为正项数列，则 $\sqrt {a{{}_{n+1}}}=\sqrt {a{{}_{n}}}+1$ ，即 $\sqrt {a{{}_{n+1}}}-\sqrt {a{{}_{n}}}=1$ ，
3. 故数列 $\left \{\sqrt {a{{}_{n}}}\right \}$ 是等差数列；
4. （2）由（1）可知，数列 $\left \{\sqrt {a{{}_{n}}}\right \}$ 是以 $\sqrt {a{{}_{1}}}=2$ 为首项， $1$ 为公差的等差数列，
5. 则 $\sqrt {a{{}_{n}}}=2+n-1=n+1$ ，即 $a{{}_{n}}={\left({n+1}\right)^{2}}$ ，
6. 则 $b{{}_{n}}=(-1){^{n}}a{{}_{n}}={\left({-1}\right)^{n}}\cdot {\left({n+1}\right)^{2}}$ ，
7. 当 $n$ 为偶数时， $S{{}_{n}}=b{{}_{1}}+b{{}_{2}}+\cdots +b{{}_{n-1}}+b{{}_{n}}=\left ({-2{^{2}}+3{^{2}}}\right )+\cdots +\left [-n{^{2}}+{\left({n+1}\right)^{2}}\right ]$
8. $=2+3+\cdots +n+\left ({n+1}\right )=\frac {\left ({2+n+1}\right )n}{2}=\frac {n\left ({n+3}\right )}{2}$ ，
9. 当 $n$ 为奇数时， $S{{}_{n}}=S{{}_{n+1}}-b{{}_{n+1}}=\frac {\left ({n+1}\right )\left ({n+4}\right )}{2}-{\left({n+2}\right)^{2}}=-\frac {n{^{2}}+3n+4}{2}$ ，
10. 故 $S{{}_{n}}=\begin{cases}-\frac {n{^{2}}+3n+4}{2},n为奇数\\\frac {n\left ({n+3}\right )}{2},n为偶数\end{cases}$ ；
11. （3）因 $\left ({1+\frac {1}{a{{}_{1}}}}\right )\left ({1+\frac {1}{a{{}_{2}}}}\right )\cdots \left ({1+\frac {1}{a{{}_{n}}}}\right )\leqslant \frac {25}{18}m\times {\left({\frac {11}{10}}\right)^{n}}$ 对 $\forall n\in {\mathbf{N}}{^{*}}$ 都成立，
12. 则 $\frac {25}{18}m\geqslant \frac {\left ({1+\frac {1}{a{{}_{1}}}}\right )\left ({1+\frac {1}{a{{}_{2}}}}\right )\cdots \left ({1+\frac {1}{a{{}_{n}}}}\right )}{{\left({\frac {11}{10}}\right)^{n}}}$ 对 $\forall n\in {\mathbf{N}}{^{*}}$ 都成立，
13. 令 $c{{}_{n}}=\frac {\left ({1+\frac {1}{a{{}_{1}}}}\right )\left ({1+\frac {1}{a{{}_{2}}}}\right )\cdots \left ({1+\frac {1}{a{{}_{n}}}}\right )}{{\left({\frac {11}{10}}\right)^{n}}}$ ，
14. 则 $\frac {c{{}_{n+1}}}{c{{}_{n}}}=\frac {\left ({1+\frac {1}{a{{}_{1}}}}\right )\left ({1+\frac {1}{a{{}_{2}}}}\right )\cdots \left ({1+\frac {1}{a{{}_{n+1}}}}\right )}{{\left({\frac {11}{10}}\right)^{n+1}}}\times \frac {{\left({\frac {11}{10}}\right)^{n}}}{\left ({1+\frac {1}{a{{}_{1}}}}\right )\left ({1+\frac {1}{a{{}_{2}}}}\right )\cdots \left ({1+\frac {1}{a{{}_{n}}}}\right )}=\frac {10}{11}\left ({1+\frac {1}{a{{}_{n+1}}}}\right )$
15. $=\frac {10}{11}\left [1+\frac {1}{{\left({n+2}\right)^{2}}}\right ]$ ，
16. 当 $n=1$ 时， $\frac {c{{}_{n+1}}}{c{{}_{n}}}>1$ ，即 $c{{}_{n+1}}>c{{}_{n}}$ ，即 $c{{}_{2}}>c{{}_{1}}$ ；
17. 当 $n\mathrm{\geqslant }2$ 时， $\frac {c{{}_{n+1}}}{c{{}_{n}}}<1$ ，即 $c{{}_{n+1}}<c{{}_{n}}$ ，即 $c{{}_{2}}>c{{}_{3}}>c{{}_{4}}>\cdots $ ；
18. 则数列 $\left \{c{{}_{n}}\right \}$ 的最大值为 $c{{}_{2}}=\frac {\left ({1+\frac {1}{a{{}_{1}}}}\right )\left ({1+\frac {1}{a{{}_{2}}}}\right )}{{\left({\frac {11}{10}}\right)^{2}}}=\frac {\left ({1+\frac {1}{4}}\right )\times \left ({1+\frac {1}{9}}\right )}{{\left({\frac {11}{10}}\right)^{2}}}=\frac {1250}{1089}$ ，
19. 则 $\frac {25}{18}m\geqslant \frac {1250}{1089}$ ，得 $m\geqslant \frac {100}{121}$ ，
20. 则 $m$ 的取值范围为 $\left [{\frac {100}{121},+∞}\right )$ .

## 知识点

**中文**:
  - 数列与不等式的综合
  - 数列的递推公式
  - 等差数列的判定与证明

**English**:
  - Sequences with Inequalities
  - Recurrence Formula
  - Determination and Proof

---
