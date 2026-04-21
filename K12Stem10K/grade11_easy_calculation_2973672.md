# Mathematics - 题目 1167

**ID**: 29736724ce324022af0c9401ac4f84c5
**年级**: Grade 11
**难度**: Easy
**题型**: Calculation

## 题目
已知等差数列 $\left \{a{{}_{n}}\right \}$ 的前 $n$ 项和为 $S{{}_{n}}$ ，其中 $a{{}_{4}}=9,S{{}_{5}}=35$ .​​​​​​​‌(1)求数列 $\left \{a{{}_{n}}\right \}$ 的通项公式以及 $S{{}_{n}}$ ；(2)若数列 $\left \{b{{}_{n}}\right \}$ 满足 $\frac {1}{b{{}_{n}}}=a{{}_{n}}a{{}_{n+1}}$ ，证明： $\sum \limits_{i=1}^{n}\mathop{b{{}_{i}}}<\frac {1}{6}$ .

## 解答

1. （1）依题意， $S{{}_{5}}=5a{{}_{3}}=35$ ，故 $a{{}_{3}}=7$ ，
2. 则数列 $\left \{a{{}_{n}}\right \}$ 的公差 $d=a{{}_{4}}-a{{}_{3}}=2$ ，
3. 故 $a{{}_{n}}=a{{}_{3}}+\left ({n-3}\right )d=7+\left ({n-3}\right )\times 2=2n+1$ ，
4. 则 $S{{}_{n}}=\frac {\left ({3+2n+1}\right )n}{2}=n{^{2}}+2n$ .
5. （2）证明：依题意， $b{{}_{n}}=\frac {1}{a{{}_{n}}a{{}_{n+1}}}=\frac {1}{\left ({2n+1}\right )\left ({2n+3}\right )}=\frac {1}{2}\left ({\frac {1}{2n+1}-\frac {1}{2n+3}}\right )$ ，
6. 故 $\sum \limits_{i=1}^{n}\mathop{b{{}_{i}}}=\frac {1}{2}\left ({\frac {1}{3}-\frac {1}{5}+\frac {1}{5}-\frac {1}{7}+\cdots +\frac {1}{2n+1}-\frac {1}{2n+3}}\right )=\frac {1}{6}-\frac {1}{4n+6}<\frac {1}{6}$ .

## 知识点

**中文**:
  - 数列求和方法之裂项相消法
  - 等差数列的概念及通项公式
  - 等差数列求和公式基本应用

**English**:
  - Telescoping Series Method
  - Concept and Formula
  - Basic Applications of Sum Formula

---
