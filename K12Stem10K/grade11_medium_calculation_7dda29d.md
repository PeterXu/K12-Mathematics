# Mathematics - 题目 2904

**ID**: 7dda29d31fa940479f1248e6d4edaf74
**年级**: Grade 11
**难度**: Medium
**题型**: Calculation

## 题目
在数列 $\left \{a{{}_{n}}\right \}$ 中， $a{{}_{2}}=5$ ，点 $\left ({a{{}_{n+1}},a{{}_{n}}}\right )\left ({n\in {\mathbf{N}^{*}}}\right )$ 在直线 $x-y-2=0$ 上.​​​​​​​‌（1）求 $\left \{a{{}_{n}}\right \}$ 的通项公式；（2）记 $\left \{a{{}_{n}}\right \}$ 的前 $n$ 项和为 $S{{}_{n}}$ ，且 $b{{}_{n}}=\frac {1}{S{{}_{n}}-n}$ ，求数列 $\left \{b{{}_{n}}\right \}$ 的前 $n$ 项和 $T{{}_{n}}$ .

## 解答

1. （1）由题意可知， $a{{}_{n+1}}-a{{}_{n}}=2$ ，所以数列 $\left \{a{{}_{n}}\right \}$ 是公差 $d=2$ 的等差数列
2. 又 $a{{}_{2}}=a{{}_{1}}+d=5$ ，所以 $a{{}_{1}}=3$ ，故 $a{{}_{n}}=3+2(n-1)=2n+1$
3. （2） $S{{}_{n}}=\frac {n(2n+4)}{2}=n{^{2}}+2n$ ，则 $b{{}_{n}}=\frac {1}{S{{}_{n}}-n}=\frac {1}{n(n+1)}=\frac {1}{n}-\frac {1}{n+1}$
4. 故 $T{{}_{n}}=1-\frac {1}{2}+\frac {1}{2}-\frac {1}{3}+\cdots +\frac {1}{n-1}-\frac {1}{n}+\frac {1}{n}-\frac {1}{n+1}$  $=1-\frac {1}{n+1}=\frac {n}{n+1}$

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
