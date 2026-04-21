# Mathematics - 题目 2584

**ID**: f3c3375c29824e88b22cba341a51ad61
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Multiple-choice

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ 满足 $a{{}_{1}}=1$ ， $a{{}_{2n}}=a{{}_{2n-1}}+{\left({-1}\right)^{n}}$ ， $a{{}_{2n+1}}=a{{}_{2n}}+3{^{n}}\left ({n\in {\mathbf{N}}{^{{\rm{*}}}}}\right )$ ，则数列 $\left \{a{{}_{n}}\right \}$ 的前2025项的和（      ）​​​​​​​‌

## 解答

1. 因为 $a{{}_{2n}}=a{{}_{2n-1}}+{\left({-1}\right)^{n}}$ ， $a{{}_{2n+1}}=a{{}_{2n}}+3{^{n}}\left ({n\in {\mathbf{N}}{^{{\rm{*}}}}}\right )$ ，
2. 所以 $a{{}_{2n+1}}=a{{}_{2n}}+3{^{n}}=a{{}_{2n-1}}+{\left({-1}\right)^{n}}+3{^{n}}$ ，即 $a{{}_{2n+1}}-a{{}_{2n-1}}={\left({-1}\right)^{n}}+3{^{n}}$ ，
3. 所以当 $n\geqslant 2$ 时， $a{{}_{2n-1}}=\left ({a{{}_{2n-1}}-a{{}_{2n-3}}}\right )+\left ({a{{}_{2n-3}}-a{{}_{2n-5}}}\right )+\cdots +\left ({a{{}_{3}}-a{{}_{1}}}\right )+a{{}_{1}}$
4. $=\left [{\left({-1}\right)^{n-1}}+3{^{n-1}}\right ]+\left [{\left({-1}\right)^{n-2}}+3{^{n-2}}\right ]+\cdots +\left ({-1+3}\right )+1=\frac {3{^{n}}-3}{2}-\frac {1-{\left({-1}\right)^{n-1}}}{2}+1=\frac {3{^{n}}}{2}+\frac {{\left({-1}\right)^{n-1}}}{2}-1$ ，
5. 又 $a{{}_{1}}=1$ 符合上式，故 $a{{}_{2n-1}}$  $=\frac {3{^{n}}}{2}+\frac {{\left({-1}\right)^{n-1}}}{2}-1$ ，
6. 所以 $a{{}_{2n}}=a{{}_{2n-1}}+{\left({-1}\right)^{n}}=\frac {3{^{n}}}{2}+\frac {{\left({-1}\right)^{n-1}}}{2}-1+{\left({-1}\right)^{n}}=\frac {3{^{n}}}{2}+\frac {1}{2}{\left({-1}\right)^{n}}-1$ .
7. 所以
8. $=\left [\frac {3{^{1}}}{2}+\frac {{\left({-1}\right)^{0}}}{2}-1+\frac {3{^{2}}}{2}+\frac {{\left({-1}\right)^{1}}}{2}-1+\cdots +\frac {3{^{1013}}}{2}+\frac {{\left({-1}\right)^{1012}}}{2}-1\right ]+$
9. $=3\times \frac {1-3{^{1012}}}{1-3}+\frac {3{^{1013}}}{2}-\frac {1}{2}-2025=3{^{1013}}-2027$ .
10. 故选D

## 知识点

**中文**:
  - 数列的前n项和
  - 数列的递推公式

**English**:
  - Sum of the First n Terms
  - Recurrence Formula

---
