# Mathematics - 题目 3012

**ID**: 2a8be1f0db5d4618af2ba2c922a345c1
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ 满足 $a{{}_{n+1}^{3}}-a{{}_{n+1}^{2}}a{{}_{n}}-a{{}_{n}}=6\times 7{^{n}}\left ({a{{}_{n+1}^{2}}+1}\right )-a{{}_{n+1}}$ ，且 $a{{}_{1}}=7$ .​​​​​​​‌ 若整数 $a{{}_{n}}$ 能被正整数 $k$ 整除，则称 $k$ 为 $a{{}_{n}}$ 的一个正约数. 设 $a{{}_{n}}$ 的正约数个数为 $m$ ，将这 $m$ 个正约数从小到大排成一排，分别为 $b{{}_{0}},b{{}_{1}},b{{}_{2}},\cdots ,b{{}_{m-1}}$ .（1）证明： $\left \{a{{}_{n+1}}-a{{}_{n}}\right \}$ 是等比数列.（2）证明： $m-n$ 为定值.（3）在 $b{{}_{i}}$ 和 $b{{}_{i+1}}$ 之间插入 $i\left ({i=1,2,3,\cdot \cdot \cdot ,n-1,n\geqslant 2}\right )$ 个数 $t{{}_{i1}},t{{}_{i2}},\cdot \cdot \cdot ,t{{}_{ii}}$ ，使  $b{{}_{i}},t{{}_{i1}},t{{}_{i2}},\cdots ,t{{}_{ii}},b{{}_{i+1}}$ 成等差数列.①当 $n\mathrm{\geqslant }2$ 时，求 $S{{}_{n-1}}=t{{}_{11}}+t{{}_{21}}+t{{}_{22}}+\cdots +t{{}_{\left ({n-1}\right )1}}+t{{}_{\left ({n-1}\right )2}}+\cdots +t{{}_{\left ({n-1}\right )\left ({n-1}\right )}}$ ；②在①的前提下，是否存在正整数 $j,n$ ，使得 $\left ({j{^{2}}+13-4n}\right )S{{}_{n-1}}=840\left ({n\geqslant 2}\right )$ ？若存在， 求出所有的正整数对 $\left ({j,n}\right )$ ；若不存在，请说明理由.

## 解答

1. （1）因为 $a{{}_{n+1}^{3}}-a{{}_{n+1}^{2}}a{{}_{n}}-a{{}_{n}}=6\times 7{^{n}}\left ({a{{}_{n+1}^{2}}+1}\right )-a{{}_{n+1}}$ ，整理可得 $\left ({a{{}_{n+1}^{2}}+1}\right )\left ({a{{}_{n+1}}-a{{}_{n}}}\right )=6\times 7{^{n}}\left ({a{{}_{n+1}^{2}}+1}\right )$ ，
2. 且 $a{{}_{n+1}^{2}}+1\ne 0$ ，可得 $a{{}_{n+1}}-a{{}_{n}}=6\times 7{^{n}}$ ，
3. 则 $\frac {a{{}_{n+2}}-a{{}_{n+1}}}{a{{}_{n+1}}-a{{}_{n}}}=\frac {6\times 7{^{n+1}}}{6\times 7{^{n}}}=7$ ，所以 $\left \{a{{}_{n+1}}-a{{}_{n}}\right \}$ 是等比数列.
4. （2）由（1）可知： $a{{}_{n+1}}-a{{}_{n}}=6\times 7{^{n}}$ ，且 $a{{}_{1}}=7$ ，
5. 当 $n\mathrm{\geqslant }2$ 时，则 $a{{}_{n}}=\left ({a{{}_{n}}-a{{}_{n-1}}}\right )+\left ({a{{}_{n-1}}-a{{}_{n-2}}}\right )+\cdot \cdot \cdot +\left ({a{{}_{2}}-a{{}_{1}}}\right )+a{{}_{1}}$
6. $=6\times 7{^{n-1}}+6\times 7{^{n-2}}+\cdot \cdot \cdot +6\times 7+7$
7. $=\frac {42\left ({1-7{^{n-1}}}\right )}{1-7}+7=7{^{n}}$ ，
8. 且 $a{{}_{1}}=7$ 符合上式，所以 $a{{}_{n}}=7{^{n}}$ ，
9. 可知整数 $a{{}_{n}}$ 只能被正整数 $7{^{k}},k\leqslant n,k\in {\mathbf{N}}$ 整除，
10. 即 $a{{}_{n}}$ 的正约数为 $7{^{0}},7{^{1}},\cdot \cdot \cdot ,7{^{n}}$ ，个数为 $m=n+1$ ，
11. 所以 $m-n=1$ 为定值.
12. （3）①由（2）可知： $b{{}_{k}}=7{^{k}},k=1,2,\cdot \cdot \cdot ,n$ ，
13. 因为 $b{{}_{i}},t{{}_{i1}},t{{}_{i2}},\cdots ,t{{}_{ii}},b{{}_{i+1}}$ 成等差数列，
14. 则 $t{{}_{i1}}+t{{}_{i2}}+\cdots +t{{}_{ii}}=\frac {i\left ({t{{}_{i1}}+t{{}_{ii}}}\right )}{2}=\frac {i\left ({b{{}_{i}}+b{{}_{i+1}}}\right )}{2}=\frac {i\left ({7{^{i}}+7{^{i+1}}}\right )}{2}$
15. $=4i\cdot 7{^{i}}=\frac {1}{9}\left \{\left [6\left ({i+1}\right )-7\right ]7{^{i+1}}-\left ({6i-7}\right )7{^{i}}\right \}$ ，
16. 当 $n\mathrm{\geqslant }2$ 时，所以 $S{{}_{n-1}}=\frac {1}{9}\left [5\times 7{^{2}}+7+11\times 7{^{3}}-5\times 7{^{2}}+\cdot \cdot \cdot +\left ({6n-7}\right )7{^{n}}-\left ({6n-13}\right )7{^{n-1}}\right ]=\frac {\left ({6n-7}\right )7{^{n}}+7}{9}$ .
17. ②存在，理由如下：由①可得 $S{{}_{n-1}}=\frac {\left ({6n-7}\right )7{^{n}}+7}{9},n\geqslant 2$ ，
18. 因为 $\left ({j{^{2}}+13-4n}\right )S{{}_{n-1}}=840$ ，
19. 显然 $S{{}_{n-1}}>0$ ，可知 $j{^{2}}+13-4n$ 为正整数，即 $j{^{2}}+13-4n\geqslant 1$ ，
20. 又因为 $S{{}_{2}}=28,S{{}_{3}}=420,S{{}_{3}}=4536>840$ ，
21. 即当 $n\geqslant 4$ 时， $S{{}_{n-1}}>840$ ，方程不成立；
22. 若 $n\mathrm{=}2$ ，可得 $28\left ({j{^{2}}+5}\right )=840$ ，解得 $j=5$ ，符合题意；
23. 若 $n=3$ ，可得 $420\left ({j{^{2}}+1}\right )=840$ ，解得 $j=1$ ，符合题意；
24. 综上所述：符合题意的正整数对为 $\left ({5,2}\right )$ 或 $\left ({1,3}\right )$ .

## 知识点

**中文**:
  - 数列新定义问题
  - 等差数列的概念及通项公式

**English**:
  - New Definition Problems
  - Concept and Formula

---
