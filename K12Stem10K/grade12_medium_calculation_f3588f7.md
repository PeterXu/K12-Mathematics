# Mathematics - 题目 2192

**ID**: f3588f7286a24885adbfd37f365186e3
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ 是公差不等于0的等差数列，其前n项和为 $S{{}_{n}}$ ，且 $a{{}_{1}}=1,S{{}_{1}},S{{}_{2}},S{{}_{4}}$ 成等比数列．（1）求数列 $\left \{a{{}_{n}}\right \}$ 的通项公式；​​​​​​​‌（2）设 $b{{}_{n}}=\frac {2}{a{{}_{n}}\cdot a{{}_{n+1}}}\left ({n\in {\mathbf{N}}{^{∗}}}\right )$ ，其前n项和为 $T{{}_{n}}$ ．（ⅰ）若 $T{{}_{2}},T{{}_{m}},T{{}_{22}}$ 成等差数列，求m的值；（ⅱ）求 $\sum \limits_{i=1}^{n}\mathop{\frac {2{^{a{{}_{i}}}}}{1-T{{}_{i}}}}$ ．

## 解答

1. （1）设等差数列 $\left \{a{{}_{n}}\right \}$ 的公差为 $d(d\ne 0)$ ，因为 $S{{}_{1}},S{{}_{2}},S{{}_{4}}$ 成等比数列，
2. 且 $a{{}_{1}}=1$ ，所以 $S{{}_{2}}{^{2}}=S{{}_{1}}\times S{{}_{4}}$ ，所以 $(2+d){^{2}}=1\times (4+6d)$ ，解得 $d=2$ ，
3. 于是有 $a{{}_{n}}=1+\left ({n-1}\right )\times 2=2n-1$ ，
4. 所以数列 $\left \{a{{}_{n}}\right \}$ 的通项公式是 $a{{}_{n}}=2n-1$ .
5. （2）由（1）知， $b{{}_{n}}=\frac {2}{a{{}_{n}}\cdot a{{}_{n+1}}}=\frac {2}{\left ({2n-1}\right )\left ({2n+1}\right )}=\frac {1}{2n-1}-\frac {1}{2n+1}$ ，
6. 因此， $T{{}_{n}}=\left ({1-\frac {1}{3}}\right )+\left ({\frac {1}{3}-\frac {1}{5}}\right )+\cdot \cdot \cdot +\left ({\frac {1}{2n-1}-\frac {1}{2n+1}}\right )=1-\frac {1}{2n+1}$ .
7. （ⅰ）因为 $T{{}_{2}}$ ， $T{{}_{m}}$ ， $T{{}_{22}}$ 成等差数列，
8. 则 $T{{}_{2}}+T{{}_{22}}=2T{{}_{m}}$ ，即 $1-\frac {1}{4+1}+1-\frac {1}{44+1}=2\left ({1-\frac {1}{2m+1}}\right )$ ，整理得 $\frac {1}{2m+1}=\frac {1}{9}$ ，
9. 解得 $m=4$ ；
10. （ⅱ）由（ⅰ）知 $\frac {2{^{a{{}_{i}}}}}{1-T{{}_{i}}}=\frac {2{^{2i-1}}}{1-(1-\frac {1}{2i+1})}=(2i+1)\times 2{^{2i-1}}=(i+\frac {1}{2})\times 4{^{i}}$ ，
11. 记 $M{{}_{n}}=\sum\limits_{i=1}^{n}\mathop{}\frac {2{^{a{{}_{i}}}}}{1-T{{}_{i}}}=\sum\limits_{i=1}^{n}\mathop{}(\frac {2i+1}{2})\times 4{^{i}}$ ，
12. 则 $M{{}_{n}}=\frac {3}{2}\times 4+\frac {5}{2}\times 4{^{2}}+\frac {7}{2}\times 4{^{3}}+\cdots +(\frac {2n-1}{2})\times 4{^{n-1}}+(\frac {2n+1}{2})\times 4{^{n}}$
13. 所以 $4M{{}_{n}}=\frac {3}{2}\times 4{^{2}}+\frac {5}{2}\times 4{^{3}}+\frac {7}{2}\times 4{^{4}}+\cdots +(\frac {2n-1}{2})\times 4{^{n}}+(\frac {2n+1}{2})\times 4{^{n+1}}$
14. 两式相减得 $-3M{{}_{n}}=\frac {3}{2}\times 4+(4{^{2}}+4{^{3}}+\cdots +4{^{n}})-(\frac {2n+1}{2})\times 4{^{n+1}}$
15. $=6+\frac {4{^{2}}-4{^{n+1}}}{1-4}-(\frac {2n+1}{2})\times 4{^{n+1}}=\frac {2}{3}-(\frac {6n+1}{6})\times 4{^{n+1}}$ ，
16. 所以 $M{{}_{n}}=-\frac {2}{9}+(\frac {6n+1}{18})\times 4{^{n+1}}$ ，即 $\sum\limits_{i=1}^{n}\mathop{}\frac {2{^{a{{}_{i}}}}}{1-T{{}_{i}}}=-\frac {2}{9}+(\frac {6n+1}{18})\times 4{^{n+1}}$ .

## 知识点

**中文**:
  - 数列求和方法之裂项相消法
  - 等差数列的概念及通项公式
  - 数列求和方法之错位相减法

**English**:
  - Telescoping Series Method
  - Concept and Formula
  - Offset Subtraction Method

---
