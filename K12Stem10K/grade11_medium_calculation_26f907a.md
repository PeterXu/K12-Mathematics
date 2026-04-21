# Mathematics - 题目 3403

**ID**: 26f907a715d44c4daeeece8c0c0492b6
**年级**: Grade 11
**难度**: Medium
**题型**: Calculation

## 题目
已知数列 ${\rm \{a_{n}\}}$ 的前n项和为S_{n}， 且满足a_{1}= 2， na_{n + 1}= S_{n}+ n（n + 1）.​​​​​​​‌（Ⅰ）求数列 ${\rm \{a_{n}\}}$ 的通项公式a_{n}；（Ⅱ）设T_{n}为数列 $\left \{\frac {a{{}_{n}}}{2{^{n}}}\right \}$ }的前n项和， 求T_{n}；（Ⅲ）设 $b{{}_{n}}=\frac {1}{a{{}_{n}}a{{}_{n+1}}a{{}_{n+2}}}$ ， 证明： $b{{}_{1}}+b{{}_{2}}+b{{}_{3}}+\cdots +b{{}_{n}}<\frac {1}{32}$

## 解答

1. 试题分析：（Ⅰ）由已知 $na{{}_{n+1}}=S{{}_{n}}+n\left ({n+1}\right )$ 当 $n\mathrm{\geqslant }2$  时 $\left ({n-1}\right )a{{}_{n}}=S{{}_{n-1}}+n\left ({n-1}\right )$ ，两式项减，得到.求出 $a{{}_{1}}=2$ ，则数列的通项公式可得
2. （Ⅱ）由题意可得 $\frac {a{{}_{n}}}{2{^{n}}}=\frac {n}{2{^{n-1}}}$ ，直接利用错位相减法即可求出 $T{{}_{n}}=4-\frac {n+2}{2{^{n}}{^{-1}}}$
3. （Ⅲ）（Ⅰ），得
4. 利用裂项相消法即可得
5. 试题解析：（Ⅰ）
6. 由题意，当 $n\mathrm{\geqslant }2$  时，有 $\{\hspace{-0.5em}\begin{array}{l}na{{}_{n+1}}=S{{}_{n}}+n\left ({n+1}\right ).\\\left ({n-1}\right )a{{}_{n}}=S{{}_{n-1}}+n\left ({n-1}\right )\end{array}\hspace{-0.5em}$
7. 两式相减得 $na{{}_{n+1}}-\left ({n-1}\right )a{{}_{n}}=a{{}_{n}}+{{2}}n\Rightarrow a{{}_{n+1}}-a{{}_{n}}={{2}}$
8. 由 $\{\hspace{-0.5em}\begin{array}{l}a{{}_{1}}=2\\a{{}_{2}}=S{{}_{1}}+2\Rightarrow a{{}_{2}}-a{{}_{1}}=2\\S{{}_{1}}=a{{}_{1}}\end{array}\hspace{-0.5em}$ ，所以对任意 $n\in {\mathbf{N}^{*}}$  ，都有
9. 故 $a{{}_{n}}=a{{}_{1}}+\left ({n-1}\right )2=2n$
10. （Ⅱ）由（Ⅰ）得 $\frac {a{{}_{n}}}{2{^{n}}}=\frac {2n}{2{^{n}}}=\frac {n}{2{^{n-1}}}$ ，因此 $T{{}_{n}}=1+\frac {2}{2}+\frac {3}{2{^{2}}}+\frac {4}{23}+...+\frac {n}{2{^{n-1}}}$  ，两边同乘以 $\frac {1}{2}$ 得
11. $\frac {1}{2}T{{}_{n}}=\frac {1}{2}+\frac {2}{2{^{2}}}+\frac {3}{2{^{3}}}+\frac {4}{2{^{4}}}+...+\frac {n-1}{2{^{n-1}}}+\frac {n}{2{^{n}}}$ ．两式错位相减得 $\frac {1}{2}T{{}_{n}}=1+\frac {1}{2}+\frac {2}{2{^{2}}}+\frac {1}{2{^{3}}}+\frac {1}{2{^{4}}}+...+\frac {1}{2{^{n-1}}}-\frac {n}{2{^{n}}}\Rightarrow \frac {1}{2}T{{}_{n}}=\frac {1-\frac {1}{2{^{n}}}}{1-\frac {1}{2}}-\frac {n}{2{^{n}}}$
12. $\Rightarrow T{{}_{n}}=4-\frac {n+2}{2{^{n}}{^{-1}}}$
13. （Ⅲ）由（Ⅰ），得
14. 
15. 
16. .
17. 考点：数列的通项公式，错位相减法，裂项相消法

## 知识点

**中文**:
  - 利用前n项和与通项关系求通项公式
  - 数列求和方法之错位相减法
  - 数列求和方法之裂项相消法

**English**:
  - Using Sum-Term Relation
  - Offset Subtraction Method
  - Telescoping Series Method

---
