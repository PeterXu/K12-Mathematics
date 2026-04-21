# Mathematics - 题目 3426

**ID**: 701130da67b142569398be472ebac787
**年级**: Grade 12
**难度**: Medium
**题型**: Multiple-choice

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ 中， $a{{}_{1}}=1$ ，且 $a{{}_{n+1}}-a{{}_{n}}={\left({-\frac {1}{3}}\right)^{n}}$ ，若存在正整数 $n$ ，使得 $\left ({t-a{{}_{n}}}\right )\left ({t-a{{}_{n+1}}}\right )<0$ 成立，则实数 $t$ 的取值范围为（      ）​​​​​​​‌

## 解答

1. 由题， $a{{}_{n}}=a{{}_{1}}+\left ({a{{}_{2}}-a{{}_{1}}}\right )+\left ({a{{}_{3}}-a{{}_{2}}}\right )+\cdot \cdot \cdot +\left ({a{{}_{n}}-a{{}_{n-1}}}\right )=1-\frac {1}{3}+\frac {1}{9}-\frac {1}{27}+\cdot \cdot \cdot +{\left({-\frac {1}{3}}\right)^{n-1}}$ ，
2. 即： $a{{}_{n}}=\frac {3}{4}\times \left [1-{\left({-\frac {1}{3}}\right)^{n}}\right ]$ ， $n\mathrm{\geqslant }2$ ，
3. $n=1$ 时， $a{{}_{1}}=1$ ，符合上式，所以 $a{{}_{n}}=\frac {3}{4}\times \left [1-{\left({-\frac {1}{3}}\right)^{n}}\right ]$ ，
4. ①当 $n=2k\left ({k\in {\rm{N}}{^{*}}}\right )$ 时， $a{{}_{2k+1}}-a{{}_{2k}}={\left({-\frac {1}{3}}\right)^{2k}}=\frac {1}{9{^{k}}}>0$
5. 则由 $\left ({t-a{{}_{n}}}\right )\left ({t-a{{}_{n+1}}}\right )<0$ 得： $a{{}_{2k}}<t<a{{}_{2k+1}}$ ，
6. 此时 $a{{}_{2k}}=\frac {3}{4}\times \left [1-{\left({\frac {1}{3}}\right)^{2k}}\right ]\geqslant a{{}_{2}}=\frac {2}{3}$ ， $a{{}_{2k+1}}=\frac {3}{4}\times \left [1+{\left({\frac {1}{3}}\right)^{2k+1}}\right ]\leqslant a{{}_{3}}=\frac {7}{9}$ ，
7. 所以 $t\in \left ({\frac {2}{3},\frac {7}{9}}\right )$ ；
8. ②当 $n=2k-1\left ({k\in {\rm{N}}{^{*}}}\right )$ 时， $a{{}_{2k}}-a{{}_{2k-1}}={\left({-\frac {1}{3}}\right)^{2k-1}}=-\frac {1}{3{^{2k-1}}}<0$ ，
9. 则由 $\left ({t-a{{}_{n}}}\right )\left ({t-a{{}_{n+1}}}\right )<0$ 得： $a{{}_{2k}}<t<a{{}_{2k-1}}$ ，
10. 此时 $a{{}_{2k}}=\frac {3}{4}\times \left [1-{\left({\frac {1}{3}}\right)^{2k}}\right ]\geqslant a{{}_{2}}=\frac {2}{3}$ ； $a{{}_{2k-1}}=\frac {3}{4}\times \left [1+{\left({\frac {1}{3}}\right)^{2k-1}}\right ]\leqslant a{{}_{1}}=1$ ，
11. 所以 $t\in \left ({\frac {2}{3},1}\right )$ ；
12. 综上所述： $t\in \left ({\frac {2}{3},1}\right )$ .
13. 故选B.

## 知识点

**中文**:
  - 数列与不等式的综合
  - 数列通项求法之累加法

**English**:
  - Sequences with Inequalities
  - Accumulation Method (Telescoping Sums)

---
