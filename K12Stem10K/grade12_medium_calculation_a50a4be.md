# Mathematics - 题目 3668

**ID**: a50a4be3fe814bb4bc8a0ea10c0d8d09
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
己知数列 $\left \{a{{}_{n}}\right \}$ 和 $\left \{b{{}_{n}}\right \}$ 的各项为正，且 $a{{}_{3}}=18b{{}_{1}}$ ， $\left \{b{{}_{n}}\right \}$ 是公比3的等比数列．数列 $\left \{a{{}_{n}}\right \}$ 的前n项和 $S{{}_{n}}$ 满足 $4S{{}_{n}}=a{{}_{n}^{2}}+2a{{}_{n}}$ ．(1)求数列 $\left \{a{{}_{n}}\right \}$ ， $\left \{b{{}_{n}}\right \}$ 的通项公式；​​​​​​​‌(2)设 $C{{}_{n}}=\frac {b{{}_{n+3}}}{\left ({b{{}_{n+3}}-3}\right )\left ({b{{}_{n+3}}-1}\right )}+a{{}_{n}}{\cos}n{\rm{π}}$ ，求数列 $\left \{c{{}_{n}}\right \}$ 的前n项和 $S{{}_{n}}$ ．

## 解答

1. （1）由题设，当 $n=1$ 时 $4S{{}_{1}}=a{{}_{1}^{2}}+2a{{}_{1}}$ ，所以 $a{{}_{1}}=2$
2. 由 $4S{{}_{n}}=a{{}_{n}^{2}}+2a{{}_{n}}$ ，知 $4S{{}_{n-1}}=a{{}_{n-1}^{2}}+2a{{}_{n-1}}$ ，
3. 两式相减得 $\left ({a{{}_{n}}+a{{}_{n-1}}}\right )\left ({a{{}_{n}}-a{{}_{n-1}}-2}\right )=0$ ，
4. 所以 $a{{}_{n}}+a{{}_{n-1}}=0$ （舍）或 $a{{}_{n}}-a{{}_{n-1}}-2=0$ ，即 $a{{}_{n}}-a{{}_{n-1}}=2$ ，
5. 所以数列 $\left \{a{{}_{n}}\right \}$ 是首项为2，公差为2的等差数列，所以 $a{{}_{n}}=2n$ ．
6. 又 $a{{}_{3}}=18b{{}_{1}}=6$ ，所以 $b{{}_{1}}=\frac {1}{3}$ ，所以 $b{{}_{n}}=3{^{n-2}}$ ．
7. （2） $C{{}_{n}}=\frac {b{{}_{n+3}}}{\left ({b{{}_{n+3}}-3}\right )\left ({b{{}_{n+3}}-1}\right )}+a{{}_{n}}{\cos}n{\rm{π}}=\frac {3{^{n+1}}}{\left ({3{^{n+1}}-3}\right )\left ({3{^{n+1}}-1}\right )}+(-1){^{n}}2n$
8. $=\frac {3{^{n}}}{\left ({3{^{n}}-1}\right )\left ({3{^{n+1}}-1}\right )}+(-1){^{n}}2n=\frac {1}{2}\left ({\frac {1}{3{^{n}}-1}-\frac {1}{3{^{n+1}}-1}}\right )+(-1){^{n}}2n$
9. 则 $S{{}_{n}}=\frac {1}{2}\left [\left ({\frac {1}{3-1}-\frac {1}{3{^{2}}-1}}\right )+\left ({\frac {1}{3{^{2}}-1}-\frac {1}{3{^{3}}-1}}\right )+\ldots \ldots +\left ({\frac {1}{3{^{n}}-1}-\frac {1}{3{^{n+1}}-1}}\right )\right ]$  $+2\left [(-1+2)+(-3+4)+\ldots .+(-1){^{n}}n\right ]$
10. 当n为偶数时 $S{{}_{n}}=\frac {1}{2}\left ({\frac {1}{2}-\frac {1}{3{^{n+1}}-1}}\right )+n$ ；
11. 当n为奇数时， $S{{}_{n}}=\frac {1}{2}\left ({\frac {1}{2}-\frac {1}{3{^{n+1}}-1}}\right )-(n+1)=-\frac {1}{2\left ({3{^{n+1}}-1}\right )}-n-\frac {3}{4}$ ．
12. 所以 $S{{}_{n}}=\begin{cases}\frac {1}{2}\left ({\frac {1}{2}-\frac {1}{3{^{n+1}}-1}}\right )+n，当n为偶数\\-\frac {1}{2\left ({3{^{n+1}}-1}\right )}-n-\frac {3}{4}，当n为奇数\end{cases}$ .

## 知识点

**中文**:
  - 数列求和方法之分组转化法
  - 等差数列的概念及通项公式
  - 等比数列的概念与通项公式
  - 数列求和方法之裂项相消法

**English**:
  - Grouping Method
  - Concept and Formula
  - Concept and Formula
  - Telescoping Series Method

---
