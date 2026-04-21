# Mathematics - 题目 3477

**ID**: a08ebc114a894138a333d31570426292
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ 满足 $a{{}_{1}}+\frac {a{{}_{2}}}{2}+\frac {a{{}_{3}}}{2{^{2}}}+\cdots +\frac {a{{}_{n}}}{2{^{n-1}}}=2n,n\in {\rm{N}}{^{*}}$(1)求 $\left \{a{{}_{n}}\right \}$ 的通项公式；(2)在 $a{{}_{n}}$ 和 $a{{}_{n+1}}$ 之间插入 $n$ 个数，使得这 $n+2$ 个数依次构成公差为 $d{{}_{n}}$ 的等差数列，求数列 $\left \{\frac {1}{d{{}_{n}}}\right \}$ 的前 $n$ 项和 $T{{}_{n}}$ .​​​​​​​‌

## 解答

1. （1） $\because a{{}_{1}}+\frac {a{{}_{2}}}{2}+\frac {a{{}_{3}}}{2{^{2}}}+\cdots +\frac {a{{}_{n}}}{2{^{n-1}}}=2n$ ①，
2. 当 $n\mathrm{\geqslant }2$ 时， $a{{}_{1}}+\frac {a{{}_{2}}}{2}+\frac {a{{}_{3}}}{2{^{2}}}+\cdots +\frac {a{{}_{n-1}}}{2{^{n-2}}}=2(n-1)$ ②，
3. 由① $-$ ②，得 $\frac {a{{}_{n}}}{2{^{n-1}}}=2$ ，即 $a{{}_{n}}=2{^{n}}$ ，
4. 又当 $n=1$ 时， $a{{}_{1}}=2$ ，满足 $a{{}_{n}}=2{^{n}}$ ，所以 $a{{}_{n}}=2{^{n}}$ .
5. （2）由（1）知 $a{{}_{n}}=2{^{n}}$ ，所以 $d{{}_{n}}=\frac {a{{}_{n+1}}-a{{}_{n}}}{n+1}=\frac {2{^{n+1}}-2{^{n}}}{n+1}=\frac {2{^{n}}}{n+1}$ ，则 $\frac {1}{d{{}_{n}}}=\frac {n+1}{2{^{n}}}$ ，
6. 所以 $T{{}_{n}}=2\cdot {\left({\frac {1}{2}}\right)^{1}}+3\cdot {\left({\frac {1}{2}}\right)^{2}}+4\cdot {\left({\frac {1}{2}}\right)^{3}}+\cdot \cdot \cdot +\left ({n+1}\right ){\left({\frac {1}{2}}\right)^{n}}$ ③，
7. $\frac {1}{2}T{{}_{n}}=2\cdot {\left({\frac {1}{2}}\right)^{2}}+3\cdot {\left({\frac {1}{2}}\right)^{3}}+4\cdot {\left({\frac {1}{2}}\right)^{4}}+\cdot \cdot \cdot +n{\left({\frac {1}{2}}\right)^{n}}+\left ({n+1}\right ){\left({\frac {1}{2}}\right)^{n+1}}$ ④，
8. 由③ $-$ ④得： $\frac {1}{2}T{{}_{n}}=2\cdot {\left({\frac {1}{2}}\right)^{1}}+{\left({\frac {1}{2}}\right)^{2}}+\cdot \cdot \cdot +{\left({\frac {1}{2}}\right)^{n}}-\left ({n+1}\right ){\left({\frac {1}{2}}\right)^{n+1}}$
9. $=1+\frac {\frac {1}{4}-{\left({\frac {1}{2}}\right)^{n+1}}}{1-\frac {1}{2}}-\left ({n+1}\right ){\left({\frac {1}{2}}\right)^{n+1}}=\frac {3}{2}-\frac {n+3}{2{^{n+1}}}$ ，
10. 所以 $T{{}_{n}}=3-\frac {n+3}{2{^{n}}}$ .

## 知识点

**中文**:
  - 数列求和方法之错位相减法
  - 数列通项求法之构造法

**English**:
  - Offset Subtraction Method
  - Construction Method

---
