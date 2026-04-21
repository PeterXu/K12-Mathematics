# Mathematics - 题目 1247

**ID**: 275b7d8212d94f00b3205a87aba0038d
**年级**: Grade 11
**难度**: Easy
**题型**: Calculation

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ 的百项 $a{{}_{1}}=\frac {3}{5}$ ，且满足 $a{{}_{n+1}}=\frac {3a{{}_{n}}}{2a{{}_{n}}+1}$ ．(1)求证：数列 $\left \{\frac {1}{a{{}_{n}}}-1\right \}$ 为等比数列；​​​​​​​‌(2)若 $\frac {1}{a{{}_{1}}}+\frac {1}{a{{}_{2}}}+\frac {1}{a{{}_{3}}}+\cdots +\frac {1}{a{{}_{n}}}<2025$ ，求满足条件的最大整数n．

## 解答

1. （1）∵ $a{{}_{n+1}}=\frac {3a{{}_{n}}}{2a{{}_{n}}+1}$ ，∴ $\frac {1}{a{{}_{n+1}}}=\frac {2a{{}_{n}}+1}{3a{{}_{n}}}=\frac {1}{3}\cdot \frac {1}{a{{}_{n}}}+\frac {2}{3}$ ，
2. 可得 $\frac {1}{a{{}_{n+1}}}-1=\frac {1}{3}\cdot \frac {1}{a{{}_{n}}}+\frac {2}{3}-1=\frac {1}{3}\left ({\frac {1}{a{{}_{n}}}-1}\right )$ ，
3. 又由 $a{{}_{1}}=\frac {3}{5}$ ，所以 $\frac {1}{a{{}_{1}}}-1=\frac {2}{3}$ ，则数列 $\left \{\frac {1}{a{{}_{n}}}-1\right \}$ 表示首项为 $\frac {2}{3}$ ，公比为 $\frac {1}{3}$ 的等比数列．
4. （2）由（1）可得 $\frac {1}{a{{}_{n}}}-1=\frac {2}{3}\times {\left({\frac {1}{3}}\right)^{n-1}}=2\cdot {\left({\frac {1}{3}}\right)^{n}}$ ，所以 $\frac {1}{a{{}_{n}}}=2\cdot {\left({\frac {1}{3}}\right)^{n}}+1$ ．
5. 设数列 $\left \{\frac {1}{a{{}_{n}}}\right \}$ 的前n项和为 $S{{}_{n}}$ ，
6. 则 $S{{}_{n}}=\frac {1}{a{{}_{1}}}+\frac {1}{a{{}_{2}}}+\frac {1}{a{{}_{3}}}+\cdots +\frac {1}{a{{}_{n}}}=2\left ({\frac {1}{3}+\frac {1}{3{^{2}}}+\frac {1}{3{^{3}}}+\cdots +\frac {1}{3{^{n}}}}\right )+n$  $=2\times \frac {\frac {1}{3}\left [1-{\left({\frac {1}{3}}\right)^{n}}\right ]}{1-\frac {1}{3}}+n=n+1-\frac {1}{3{^{n}}}$ ，
7. 若 $S{{}_{n}}<2025$ ，即 $n+1-\frac {1}{3{^{n}}}<2025$ ，因为函数 $y=x+1-\frac {1}{3{^{x}}}$ 为单调递增函数，所以满足 $S{{}_{n}}<2025$ 的最大整数n的值为2024．

## 知识点

**中文**:
  - 数列求和方法之分组转化法
  - 等比数列的判定与证明

**English**:
  - Grouping Method
  - Determination and Proof

---
