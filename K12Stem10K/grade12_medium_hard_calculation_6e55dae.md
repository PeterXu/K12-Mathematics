# Mathematics - 题目 2210

**ID**: 6e55daebfef74485b39066cccd97a833
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ 满足 $a{{}_{1}}=\frac {1}{4}$ ， $a{{}_{n}}$ ， $\frac {3}{2}a{{}_{n{{+}}1}}$ ， $2a{{}_{n}}a{{}_{n+1}}$ 成等差数列.​​​​​​​‌(1)求证：数列 $\left \{\frac {1}{a{{}_{n}}}-1\right \}$ 是等比数列，并求出 $\left \{a{{}_{n}}\right \}$ 的通项公式；(2)记 $\left \{a{{}_{n}}\right \}$ 的前n项和为 $S{{}_{n}}$ ，证明： $\frac {3}{8}\left [1-{\left({\frac {1}{3}}\right)^{n}}\right ]\leqslant S{{}_{n}}<\frac {5}{12}$ .

## 解答

1. （1）由 $a{{}_{n}}$ ， $\frac {3}{2}a{{}_{n+1}}$ ， $2a{{}_{n}}a{{}_{n+1}}$ 成等差数列可得： $3a{{}_{n+1}}=a{{}_{n}}+2a{{}_{n}}a{{}_{n+1}}$ ，
2. 因为 $a{{}_{1}}=\frac {1}{4}$ ，可得 $a{{}_{n}}\ne 0$ ，所以两边同时除以 $a{{}_{n}}a{{}_{n+1}}$ 得： $\frac {1}{a{{}_{n+1}}}=\frac {3}{a{{}_{n}}}-2$ ，
3. 上式可化为： $\frac {1}{a{{}_{n+1}}}-1=3\left ({\frac {1}{a{{}_{n}}}-1}\right )$ ，
4. 所以数列 $\left \{\frac {1}{a{{}_{n}}}-1\right \}$ 表示是以 $\frac {1}{a{{}_{1}}}-1=3$ 为首项，3为公比的等比数列，
5. 所以 $\frac {1}{a{{}_{n}}}-1=3\times 3{^{n-1}}=3{^{n}}$ ，即 $a{{}_{n}}=\frac {1}{3{^{n}}+1}$ .
6. （2）因为 $a{{}_{n}}=\frac {1}{3{^{n}}+1}<\frac {1}{3{^{n}}}$ ，
7. 所以 $S{{}_{n}}=a{{}_{1}}+a{{}_{2}}+a{{}_{3}}+\cdots +a{{}_{n}}<a{{}_{1}}+\frac {1}{3{^{2}}}+\frac {1}{3{^{2}}}+\cdots +\frac {1}{3{^{n}}}$
8. $=\frac {1}{4}+\frac {1}{3{^{2}}}+\frac {1}{3{^{2}}}+\cdots +\frac {1}{3{^{n}}}=\frac {1}{4}+\frac {\frac {1}{9}\left ({1-\frac {1}{3{^{n-1}}}}\right )}{1-\frac {1}{3}}=\frac {5}{12}-\frac {1}{2}\cdot \frac {1}{3{^{n}}}<\frac {5}{12}$ ，
9. 又因为 $a{{}_{n}}=\frac {1}{3{^{n}}+1}=\frac {1}{3\times 3{^{n-1}}+1}\geqslant \frac {1}{4\times 3{^{n-1}}}$ ，
10. 所以 $S{{}_{n}}=a{{}_{1}}+a{{}_{2}}+a{{}_{3}}+\cdots +a{{}_{n}}\geqslant \frac {1}{4}\left ({\frac {1}{3{^{0}}}+\frac {1}{3{^{1}}}+\cdots +\frac {1}{3{^{n-1}}}}\right )$  $=\frac {1}{4}\times \frac {1-\frac {1}{3{^{n}}}}{1-\frac {1}{3}}=\frac {3}{8}\left [1-{\left({\frac {1}{3}}\right)^{n}}\right ]$ ，
11. （当n＝1时等号成立），
12. 综上可知： $\frac {3}{8}\left [1-{\left({\frac {1}{3}}\right)^{n}}\right ]\leqslant S{{}_{n}}<\frac {5}{12}$ .

## 知识点

**中文**:
  - 数列与不等式的综合
  - 等差中项
  - 等比数列的判定与证明
  - 数列通项求法之构造法

**English**:
  - Sequences with Inequalities
  - Arithmetic Mean (Middle Term)
  - Determination and Proof
  - Construction Method

---
