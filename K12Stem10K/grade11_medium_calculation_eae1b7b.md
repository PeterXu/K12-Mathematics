# Mathematics - 题目 3769

**ID**: eae1b7bd74e64fd59b70112fdcd64378
**年级**: Grade 11
**难度**: Medium
**题型**: Calculation

## 题目
已知等差数列 $\left \{a{{}_{n}}\right \}$ 的前 $n$ 项和为 $S{{}_{n}}$ ，且 $S{{}_{4}}=4S{{}_{2}}$ ， $a{{}_{2n}}=2a{{}_{n}}+1\left ({n\in {\mathbf{N}}{^{{\rm{*}}}}}\right )$ ．（1）求数列 $\left \{a{{}_{n}}\right \}$ 的通项公式；​​​​​​​‌（2）若 $b{{}_{n}}=3{^{n-1}}$ ，令 $c{{}_{n}}=a{{}_{n}}b{{}_{n}}$ ，求数列 $\left \{c{{}_{n}}\right \}$ 的前 $n$ 项和 $T{{}_{n}}$ ．

## 解答

1. （1）设等差数列 $\left \{a{{}_{n}}\right \}$ 的公差为 $d$ ，
2. 由 $a{{}_{2n}}=2a{{}_{n}}+1$ ，可得 $a{{}_{1}}+\left ({2n-1}\right )d=2a{{}_{1}}+2\left ({n-1}\right )d+1$ ，可得 $a{{}_{1}}-d+1=0$ ①，
3. 由 $S{{}_{4}}=4S{{}_{2}}$ 可得 $4a{{}_{1}}+\frac {3\times 4d}{2}=4\left ({2a{{}_{1}}+\frac {2\times 1}{2}d}\right )$ ，整理可得 $2a{{}_{1}}=d$ ②，
4. 联立①②可得 $a{{}_{1}}=1$ ， $d=2$ ，所以， $a{{}_{n}}=a{{}_{1}}+\left ({n-1}\right )d=1+2\left ({n-1}\right )=2n-1$ .
5. （2）因为 $b{{}_{n}}=3{^{n-1}}$ ，则 $c{{}_{n}}=a{{}_{n}}b{{}_{n}}=\left ({2n-1}\right )\cdot 3{^{n-1}}$ ，
6. 所以， $T{{}_{n}}=1\cdot 3{^{0}}+3\cdot 3{^{1}}+5\cdot 3{^{2}}+\cdots +\left ({2n-1}\right )\cdot 3{^{n-1}}$ ，
7. $3T{{}_{n}}=1\cdot 3{^{1}}+3\cdot 3{^{2}}+\cdots +\left ({2n-3}\right )\cdot 3{^{n-1}}+\left ({2n-1}\right )\cdot 3{^{n}}$ ，
8. 上式 $-$ 下式得 $-2T{{}_{n}}=1+2\times \left ({3{^{1}}+3{^{2}}+\cdots +3{^{n-1}}}\right )-\left ({2n-1}\right )\cdot 3{^{n}}$
9. $=1+\frac {6\left ({1-3{^{n-1}}}\right )}{1-3}-\left ({2n-1}\right )\cdot 3{^{n}}=-2+\left ({2-2n}\right )\cdot 3{^{n}}$ ，
10. 因此， $T{{}_{n}}=\left ({n-1}\right )\cdot 3{^{n}}+1$ .

## 知识点

**中文**:
  - 数列求和方法之错位相减法
  - 等差数列的概念及通项公式
  - 等差数列求和公式基本应用

**English**:
  - Offset Subtraction Method
  - Concept and Formula
  - Basic Applications of Sum Formula

---
