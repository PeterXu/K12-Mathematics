# Mathematics - 题目 66

**ID**: c6b034fe54a9429bbe3254d38d3ffa5e
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设数列 $\left \{a{{}_{n}}\right \}$ 满足 $a{{}_{1}}=3,a{{}_{n+1}}=\frac {na{{}_{n}}}{n+1}+\frac {1}{n+1}$（1）证明： $\left \{na{{}_{n}}\right \}$ 为等差数列并求 $a{{}_{n}}$ ；​​​​​​​‌（2）设 $f\left ({x}\right )=a{{}_{1}}x+a{{}_{2}}x{^{2}}+\cdots +a{{}_{m}}x{^{m}}$ ，求 $f^{′}{\left ({x}\right )}$ ；（3）求 $f^{′}{\left ({-3}\right )}$

## 解答

1. （1）由题意证明如下， $n\in {\rm{N}}{^{*}}$ ，
2. 在数列 $\left \{a{{}_{n}}\right \}$ 中， $a{{}_{1}}=3$ ， $a{{}_{n+1}}=\frac {na{{}_{n}}}{n+1}+\frac {1}{n+1}$ ，
3. 所以 $\left ({n+1}\right )a{{}_{n+1}}=na{{}_{n}}+1$ ，即 $\left ({n+1}\right )a{{}_{n+1}}-na{{}_{n}}=1$ ，
4. 所以数列 $\left \{na{{}_{n}}\right \}$ 是以 $1\times a{{}_{1}}=3$ 为首项，1为公差的等差数列.
5. （2）由题意及（1）得， $n\in {\rm{N}}{^{*}}$ ，
6. 在数列 $\left \{na{{}_{n}}\right \}$ 中，首项为3，公差为1，所以 $na{{}_{n}}=3+1\times \left ({n-1}\right )$ ，即 $a{{}_{n}}=1+\frac {2}{n}$ ，
7. 在 $f\left ({x}\right )=a{{}_{1}}x+a{{}_{2}}x{^{2}}+\cdots +a{{}_{m}}x{^{m}}$ 中， $f\left ({x}\right )=3x+2x{^{2}}+\cdots +\left ({1+\frac {2}{m}}\right )x{^{m}}$ ，
8. 所以 $f^{′}{\left ({x}\right )}=3+4x+\cdots +\left ({m+2}\right )x{^{m-1}}$ ，所以 $xf^{′}{\left ({x}\right )}=3x+4x{^{2}}+\cdots +\left ({m+2}\right )x{^{m}}$ ，
9. 当 $x\ne 1$ 且 $x\ne 0$ 时，两式相减得 $\left ({1-x}\right )f^{′}{\left ({x}\right )}=3+x+x{^{2}}+\cdots +x{^{m-1}}-\left ({m+2}\right )x{^{m}}=3+\frac {x\left ({1-x{^{m-1}}}\right )}{1-x}-\left ({m+2}\right )x{^{m}}$ ，
10. 所以 $f^{′}{\left ({x}\right )}=\frac {3}{1-x}+\frac {x\left ({1-x{^{m-1}}}\right )}{{\left({1-x}\right)^{2}}}-\frac {\left ({m+2}\right )x{^{m}}}{1-x}$ ；
11. 当 $x=1$ 时， $f^{′}{\left ({1}\right )}=3+4+\cdots +\left ({m+2}\right )=\frac {m\left ({m+5}\right )}{2}$ ；
12. 当 $x=0$ 时， $f^{′}{\left ({0}\right )}=3$ ；
13. 综上， $f^{′}{\left ({x}\right )}=\begin{cases}\frac {3}{1-x}+\frac {x\left ({1-x{^{m-1}}}\right )}{{\left({1-x}\right)^{2}}}-\frac {\left ({m+2}\right )x{^{m}}}{1-x},x\ne 0且x\ne 1\\3，x=0\\\frac {m\left ({m+5}\right )}{2},x=1\end{cases}$ ；
14. （3）当 $x=-3$ 时， $f^{′}{\left ({-3}\right )}=\frac {3}{1+3}+\frac {\left ({-3}\right )\left [1-{\left({-3}\right)^{m-1}}\right ]}{{\left({1+3}\right)^{2}}}-\frac {\left ({m+2}\right ){\left({-3}\right)^{m}}}{1+3}$
15. $=\frac {3}{4}-\frac {3}{16}-\frac {{\left({-3}\right)^{m}}}{16}-\frac {\left ({m+2}\right ){\left({-3}\right)^{m}}}{4}=\frac {9-\left ({4m+9}\right ){\left({-3}\right)^{m}}}{16}$ .

## 知识点

**中文**:
  - 导数的四则运算
  - 等差数列的判定与证明

**English**:
  - Arithmetic Operations of Derivatives
  - Determination and Proof

---
