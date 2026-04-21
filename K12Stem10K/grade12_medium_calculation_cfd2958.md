# Mathematics - 题目 1635

**ID**: cfd29583fa0d4277af8adbee0035bc91
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
已知数列 $\left\{\begin{array}{l}a_{n}\end{array}\right \}$ 满足： $a_{1}=5$ ， $a_{n+1}=3a_{n}-4$ ，设 $b_{n}=a_{n}-2$ ， $n\in {\rm{N}}^{*}$ ．(1)求数列 $\left\{\begin{array}{l}b_{n}\end{array}\right \}$ 的通项公式；​​​​​​​‌(2)设 $T_{n}=\frac {{\log}_{3}b_{1}}{b_{1}}+\frac {{\log}_{3}b_{2}}{b_{2}}+\cdot \cdot \cdot +\frac {{\log}_{3}b_{n}}{b_{n}}$ ， $\left ({n\in {\rm{N}}^{*}}\right )$ ，求证： $T_{n}<\frac {3}{4}$ ．

## 解答

1. （1）由 $a_{n+1}=3a_{n}-4$ 可得： $a_{n+1}-2=3(a_{n}-2)$ ，又 $a_{1}-2=3$ ，
2. 所以 $\{a_{n}-2\}$ ，即 $\left\{\begin{array}{l}b_{n}\end{array}\right \}$ 是首项、公比均为3的等比数列，故 $b_{n}=3^{n}$ .
3. （2）由（1）知： $T_{n}=\frac {1}{3}+\frac {2}{3^{2}}+...+\frac {n}{3^{n}}$ ，则 $\frac {1}{3}T_{n}=\frac {1}{3^{2}}+\frac {2}{3^{3}}+...+\frac {n-1}{3^{n}}+\frac {n}{3^{n+1}}$ ，
4. 所以 $\frac {2}{3}T_{n}=\frac {1}{3}+\frac {1}{3^{2}}+\frac {1}{3^{3}}+...+\frac {1}{3^{n}}-\frac {n}{3^{n+1}}=\frac {\frac {1}{3}\times (1-\frac {1}{3^{n}})}{1-\frac {1}{3}}-\frac {n}{3^{n+1}}=\frac {1}{2}-\frac {1}{2\cdot 3^{n}}-\frac {n}{3^{n+1}}$ ，
5. 所以 $T_{n}=\frac {3}{4}-\frac {3}{4\cdot 3^{n}}-\frac {n}{2\cdot 3^{n}}=\frac {3}{4}-\frac {(3+2n)}{4\cdot 3^{n}}$ ，且 $n\in {\rm{N}}^{*}$ ，故 $T_{n}<\frac {3}{4}$ .

## 知识点

**中文**:
  - 数列求和方法之错位相减法
  - 数列通项求法之构造法

**English**:
  - Offset Subtraction Method
  - Construction Method

---
