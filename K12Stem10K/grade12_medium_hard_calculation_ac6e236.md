# Mathematics - 题目 1714

**ID**: ac6e236b89844c07bd981c9b53752dfc
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知 $S{{}_{n}}$ 为数列 $\left \{a{{}_{n}}\right \}$ 的前 $n$ 项和， $T{{}_{n}}$ 为数列 $\left \{b{{}_{n}}\right \}$ 的前 $n$ 项和， $a{{}_{n+2}}=2a{{}_{n+1}}-a{{}_{n}},b{{}_{n}}=\left \{\hspace{-0.​​​​​​​‌5em}\begin{array}{l}2a{{}_{n}}+1,n为奇数\\2{^{a{{}_{n}}-1}},n为偶数\end{array}\hspace{-0.5em},b{{}_{4}}=8,S{{}_{5}}=15\right.$ .(1)求 $\left \{a{{}_{n}}\right \}$ 的通项公式；(2)若 $T{{}_{2n}}-S{{}_{2n}}<2025$ ，求 $n$ 的最大值；

## 解答

1. （1）由 $a{{}_{n+2}}=2a{{}_{n+1}}-a{{}_{n}}$ ，得 $a{{}_{n+2}}+a{{}_{n}}=2a{{}_{n+1}}$ ，所以数列 $\left \{a{{}_{n}}\right \}$ 为等差数列，
2. 所以 $S{{}_{5}}=5a{{}_{3}}=15$ ，所以 $a{{}_{3}}=3$ .
3. 又 $b{{}_{4}}=2{^{a{{}_{4}}-1}}=8$ ，所以 $a{{}_{4}}=4$ ，
4. 设 $\left \{a{{}_{n}}\right \}$ 的公差为 $d$ ，
5. 即 $\begin{cases}a{{}_{3}}=a{{}_{1}}+2d=3,\\a{{}_{4}}=a{{}_{1}}+3d=4,\end{cases}$ 解得 $\begin{cases}a{{}_{1}}=1,\\d=1,\end{cases}$
6. 所以 $\left \{a{{}_{n}}\right \}$ 的通项公式是 $a{{}_{n}}=n$
7. （2）由（1）知 $a{{}_{n}}=n$ ，
8. 所以 $b{{}_{n}}=\begin{cases}2n+1,n为奇数{\rm{,}}\\2{^{n-1}},n为偶数{\rm{,}}\end{cases}$
9. $S{{}_{2n}}=\frac {2n\left ({a{{}_{1}}+a{{}_{2n}}}\right )}{2}=\frac {2n\left ({1+2n}\right )}{2}=n\left ({2n+1}\right ),$
10. $T{{}_{2n}}=\left ({b{{}_{1}}+b{{}_{3}}+\cdots +b{{}_{2n-1}}}\right )+\left ({b{{}_{2}}+b{{}_{4}}+\cdots +b{{}_{2n}}}\right )$
11. $=\frac {n\left ({3+4n-1}\right )}{2}+\frac {2\left ({1-4{^{n}}}\right )}{1-4}=n\left ({2n+1}\right )+\frac {2\left ({4{^{n}}-1}\right )}{3}$
12. 令 $T{{}_{2n}}-S{{}_{2n}}=\frac {2\left ({4{^{n}}-1}\right )}{3}<2025$ ，
13. 得 $2\cdot 4{^{n}}<6077$ ，
14. 设 $d{{}_{n}}=2\cdot 4{^{n}}$ ，则数列 $\left \{d{{}_{n}}\right \}$ 是递增数列.
15. 又 $d{{}_{5}}=2048<6077,d{{}_{6}}=2\times 4{^{6}}=8192>6077$ ，
16. 所以 $n$ 的最大值为5.

## 知识点

**中文**:
  - 数列求和方法之分组转化法
  - 等差数列的概念及通项公式
  - 等差数列求和公式基本应用

**English**:
  - Grouping Method
  - Concept and Formula
  - Basic Applications of Sum Formula

---
