# Mathematics - 题目 3480

**ID**: cdd5fff984f64d6b8da511d4eba82a2f
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设数列 $\left \{a{{}_{n}}\right \}$ 满足 $a{{}_{1}}=\frac {1}{2},a{{}_{n+1}}=\frac {1}{2}a{{}_{n}}+\frac {1}{2{^{n+1}}},n\in {\rm{N}}{^{*}}$ .​​​​​​​‌（1）证明：数列 $\left \{2{^{n}}\cdot a{{}_{n}}\right \}$ 为等差数列；（2）设 $b{{}_{n}}=\left ({2n+1}\right )\cdot a{{}_{n}}$ ，求数列 $\left \{b{{}_{n}}\right \}$ 的最大项.

## 解答

1. （1）将 $a{{}_{n+1}}=\frac {1}{2}a{{}_{n}}+\frac {1}{2{^{n+1}}}$ 两边同乘以 $2{^{n+1}}$ ，
2. 得 $2{^{n+1}}\cdot a{{}_{n+1}}=2{^{n}}\cdot a{{}_{n}}+1$ ，即 $2{^{n+1}}\cdot a{{}_{n+1}}-2{^{n}}\cdot a{{}_{n}}=1$ ，
3. 又 $2{^{1}}\cdot a{{}_{1}}=1$ ，因此， $\left \{2{^{n}}\cdot a{{}_{n}}\right \}$ 是以1为公差，1为首项的等差数列.
4. （2）由（1）得 $2{^{n}}\cdot a{{}_{n}}=1+\left ({n-1}\right )\times 1=n,a{{}_{n}}=\frac {n}{2{^{n}}}$ ，
5. 因此， $b{{}_{n}}=\frac {n\left ({2n+1}\right )}{2{^{n}}},b{{}_{n+1}}=\frac {\left ({n+1}\right )\left ({2n+3}\right )}{2{^{n+1}}}$ ，
6. $b{{}_{n+1}}-b{{}_{n}}=\frac {\left ({n+1}\right )\left ({2n+3}\right )-2n\left ({2n+1}\right )}{2{^{n+1}}}=\frac {-2n{^{2}}+3n+3}{2{^{n+1}}}=\frac {3-n\left ({2n-3}\right )}{2{^{n+1}}}$ .
7. 当 $n\geqslant 3$ 时， $3-n\left ({2n-3}\right )<0$ ，得 $b{{}_{n+1}}-b{{}_{n}}<0$ ，即 $b{{}_{n+1}}<b{{}_{n}}$ .
8. 又因为 $b{{}_{1}}=\frac {3}{2},b{{}_{2}}=\frac {5}{2},b{{}_{3}}=\frac {21}{8}$ ，所以 $b{{}_{1}}<b{{}_{2}}<b{{}_{3}}$ ，
9. 即当 $n<3$ 时， $b{{}_{n+1}}>b{{}_{n}}$ ，
10. 所以 $\left \{b{{}_{n}}\right \}$ 的最大项是 $b{{}_{3}}=\frac {21}{8}$ .

## 知识点

**中文**:
  - 等差数列的判定与证明

**English**:
  - Determination and Proof

---
