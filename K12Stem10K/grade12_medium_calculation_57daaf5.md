# Mathematics - 题目 3463

**ID**: 57daaf5a1abc43f283cf2c02dea7cd2b
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ 对于任意 $n∈{\rm{N}}{^{*}}$ 都有 $\frac {\left ({a{{}_{1}}+1}\right )}{2}+\frac {\left ({a{{}_{2}}+1}\right )}{2{^{2}}}+\frac {\left ({a{{}_{3}}+1}\right )}{2{^{3}}}+\cdots +\frac {\left ({a{{}_{n}}+1}\right )}{2{^{n}}}=n$ ．(1)求数列 $\left \{a{{}_{n}}\right \}$ 的通项公式．(2)设数列 $\left \{\frac {2n}{a{{}_{n}}+1}\right \}$ 前n项和为 $S{{}_{n}}$ ，求 $S{{}_{n}}$ ．(3)证明： $\frac {1}{a{{}_{1}}}+\frac {1}{a{{}_{2}}}+\frac {1}{a{{}_{3}}}+\cdots +\frac {1}{a{{}_{n+1}}}<\frac {5}{3}$ ， $\left ({n\in {\rm{N}}{{}_{+}}}\right )$ ．​​​​​​​‌

## 解答

1. （1）因为 $\frac {\left ({a{{}_{1}}+1}\right )}{2}+\frac {\left ({a{{}_{2}}+1}\right )}{2{^{2}}}+\frac {\left ({a{{}_{3}}+1}\right )}{2{^{3}}}+\cdots +\frac {\left ({a{{}_{n}}+1}\right )}{2{^{n}}}=n$ ①，
2. 当 $n\mathrm{\geqslant }2$ 时， $\frac {\left ({a{{}_{1}}+1}\right )}{2}+\frac {\left ({a{{}_{2}}+1}\right )}{2{^{2}}}+\frac {\left ({a{{}_{3}}+1}\right )}{2{^{3}}}+\cdots +\frac {\left ({a{{}_{n-1}}+1}\right )}{2{^{n-1}}}=n-1$ ②，
3. 由① $-$ ②，得到 $\frac {a{{}_{n}}+1}{2{^{n}}}=1$ ，所以 $a{{}_{n}}=2{^{n}}-1$ ，
4. 又 $n=1$ 时， $\frac {a{{}_{1}}+1}{2}=1$ ，得到 $a{{}_{1}}=1$ ，满足 $a{{}_{n}}=2{^{n}}-1$ ，
5. 所以数列 $\left \{a{{}_{n}}\right \}$ 的通项公式为 $a{{}_{n}}=2{^{n}}-1$ .
6. （2）由题意 $\frac {2n}{a{{}_{n}}+1}=\frac {2n}{2{^{n}}}=\frac {n}{2{^{n-1}}}$ ，
7. 所以 $S{{}_{n}}=1+\frac {2}{2}+\frac {3}{2{^{2}}}+\cdots +\frac {n}{2{^{n-1}}}$ ③，得到 $\frac {1}{2}S{{}_{n}}=\frac {1}{2}+\frac {2}{2{^{2}}}+\frac {3}{2{^{3}}}+\cdots +\frac {n}{2{^{n}}}$ ④，
8. 由③ $-$ ④，得到 $\frac {1}{2}S{{}_{n}}=1+\frac {1}{2}+\frac {1}{2{^{2}}}+\cdots +\frac {1}{2{^{n-1}}}-\frac {n}{2{^{n}}}=\frac {1-{\left({\frac {1}{2}}\right)^{n}}}{1-\frac {1}{2}}-\frac {n}{2{^{n}}}=2-\frac {n+2}{2{^{n}}}$ ，
9. 所以 $S{{}_{n}}=4-\frac {n+2}{2{^{n-1}}}$ .
10. （3）因为 $n\geqslant 3$ ， $2{^{n}}-1-3\times 2{^{n-2}}=2{^{n-2}}-1>0$ ，所以 $n\geqslant 3$ 时， $2{^{n}}-1>3\times 2{^{n-2}}$ ，
11. 当 $n=1$ 时， $\frac {1}{a{{}_{1}}}+\frac {1}{a{{}_{2}}}=1+\frac {1}{3}=\frac {4}{3}<\frac {5}{3}$ ，
12. 当 $n\mathrm{=}2$ 时， $\frac {1}{a{{}_{1}}}+\frac {1}{a{{}_{2}}}+\frac {1}{a{{}_{3}}}=1+\frac {1}{3}+\frac {1}{7}<1+\frac {1}{3}+\frac {1}{3}=\frac {5}{3}$ ，
13. 当 $n\geqslant 3$ 时， $\frac {1}{a{{}_{1}}}+\frac {1}{a{{}_{2}}}+\frac {1}{a{{}_{3}}}+\cdots +\frac {1}{a{{}_{n+1}}}=1+\frac {1}{3}+\frac {1}{7}+\frac {1}{15}+\frac {1}{31}+\cdots +\frac {1}{2{^{n+1}}-1}$
14. $<\frac {1}{1}+\frac {1}{3}+\frac {1}{6}+\frac {1}{12}+\frac {1}{24}+\cdots +\frac {1}{3\cdot 2{^{n-2}}}=\frac {4}{3}+\frac {\frac {1}{6}\left ({1-{\left({\frac {1}{2}}\right)^{n-2}}}\right )}{1-\frac {1}{2}}=\frac {4}{3}+\frac {1}{3}\left ({1-{\left({\frac {1}{2}}\right)^{n-2}}}\right )<\frac {4}{3}+\frac {1}{3}=\frac {5}{3}$ ，
15. 综上， $\frac {1}{a{{}_{1}}}+\frac {1}{a{{}_{2}}}+\frac {1}{a{{}_{3}}}+\cdots +\frac {1}{a{{}_{n+1}}}<\frac {5}{3}$ ， $\left ({n\in {\rm{N}}{^{∗}}}\right )$ .

## 知识点

**中文**:
  - 利用前n项和与通项关系求通项公式
  - 数列求和方法之错位相减法
  - 数学归纳法

**English**:
  - Using Sum-Term Relation
  - Offset Subtraction Method
  - Mathematical Induction

---
