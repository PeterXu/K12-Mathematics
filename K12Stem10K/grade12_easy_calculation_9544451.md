# Mathematics - 题目 2326

**ID**: 95444511741c4ca39c0917ecc870a064
**年级**: Grade 12
**难度**: Easy
**题型**: Calculation

## 题目
在数列 $\left \{a{{}_{n}}\right \}$ 中， $a{{}_{1}}=1$ ， $a{{}_{n+1}}=2a{{}_{n}}+3\cdot 2{^{n-1}}$ ．(1)若 $b{{}_{n}}=\frac {a{{}_{n}}}{2{^{n}}}$ ，证明：数列 $\left \{b{{}_{n}}\right \}$ 是等差数列，并求数列 $\left \{b{{}_{n}}\right \}$ 的通项公式；​​​​​​​‌(2)求数列 $\left \{4a{{}_{n}}\right \}$ 的前n项和 $T{{}_{n}}$ ．

## 解答

1. （1） $\because b{{}_{n+1}}-b{{}_{n}}=\frac {a{{}_{n+1}}}{2{^{n+1}}}-\frac {a{{}_{n}}}{2{^{n}}}=\frac {a{{}_{n+1}}-2a{{}_{n}}}{2{^{n+1}}}=\frac {2a{{}_{n}}+3\cdot 2{^{n-1}}-2a{{}_{n}}}{2{^{n+1}}}=\frac {3}{4}$ ，
2. 又 $b{{}_{1}}=\frac {a{{}_{1}}}{2}=\frac {1}{2}$ ，∴ $\left \{b{{}_{n}}\right \}$ 是以 $\frac {1}{2}$ 为首项， $\frac {3}{4}$ 为公差的等差数列，
3. ∴ $b{{}_{n}}=\frac {1}{2}+(n-1)\times \frac {3}{4}=\frac {3}{4}n-\frac {1}{4}$ ；
4. （2）由（1）知 $\frac {a{{}_{n}}}{2{^{n}}}=\frac {3}{4}n-\frac {1}{4}$ ，则 $a{{}_{n}}=\left ({\frac {3}{4}n-\frac {1}{4}}\right )2{^{n}}$ ，∴ $4a{{}_{n}}=(3n-1)2{^{n}}$ ，
5. $T{{}_{n}}=2\times 2{^{1}}+5\times 2{^{2}}+8\times 2{^{3}}+\cdots +(3n-1)2{^{n}}$ ①，
6. $2T{{}_{n}}=2\times 2{^{2}}+5\times 2{^{3}}+8\times 2{^{4}}+\cdots +(3n-4)2{^{n}}+(3n-1)2{^{n+1}}$ ②，
7. ① $-$ ②，得 $-T{{}_{n}}=4+3\times 2{^{2}}+3\times 2{^{3}}+\cdots +3\times 2{^{n}}-(3n-1)2{^{n+1}}$
8. $=4+3\times \frac {4\left ({1-2{^{n-1}}}\right )}{1-2}-(3n-1)2{^{n+1}}$  $=-8+(4-3n)\cdot 2{^{n+1}}$ ，
9. ∴ $T{{}_{n}}=(3n-4)2{^{n+1}}+8$ ．

## 知识点

**中文**:
  - 数列求和方法之错位相减法
  - 数列的递推公式
  - 等差数列的概念及通项公式
  - 等差数列的判定与证明

**English**:
  - Offset Subtraction Method
  - Recurrence Formula
  - Concept and Formula
  - Determination and Proof

---
