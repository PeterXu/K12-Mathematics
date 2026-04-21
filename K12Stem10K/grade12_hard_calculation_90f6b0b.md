# Mathematics - 题目 2234

**ID**: 90f6b0bfc7a24cf9b70985b1e62db110
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ 前 $n$ 项和为 $S{{}_{n}}$ ，满足 $S{{}_{n+1}}=3S{{}_{n}}-2n+4$ ，且 $a{{}_{1}}=4$ .​​​​​​​‌(1)求数列 $\left \{a{{}_{n}}\right \}$ 的通项公式 $a{{}_{n}}$ ；(2)令 $f\left ({x}\right )=a{{}_{1}}x+a{{}_{2}}x{^{2}}+\cdots +a{{}_{n-1}}x{^{n-1}}+a{{}_{n}}x{^{n}},n\in {\mathbf{N}}{^{{\rm{*}}}}$ ，讨论 $f^{′}{\left ({1}\right )}$ 与 $\frac {8n{^{2}}+11n-3}{4}$ 的大小关系；(3)对任意正整数 $n\in {\mathbf{N}}{^{{\rm{*}}}},\left ({1+\frac {1}{a{{}_{1}}}}\right )\left ({1+\frac {1}{a{{}_{2}}}}\right )\cdots \left ({1+\frac {1}{a{{}_{n}}}}\right )<m$ 恒成立，求正整数 $m$ 的最小值．

## 解答

1. （1） $n=1$ 时， $S{{}_{2}}=3S{{}_{1}}+2$ ，所以 $a{{}_{2}}=10$ ，
2. 因为 $S{{}_{n+1}}=3S{{}_{n}}-2n+4$ ，所以 $n\mathrm{\geqslant }2$ 时， $S{{}_{n}}=3S{{}_{n-1}}-2\left ({n-1}\right )+4$ ，
3. 所以 $a{{}_{n+1}}=3a{{}_{n}}-2,a{{}_{n+1}}-1=3\left ({a{{}_{n}}-1}\right )\left ({n\geqslant 2}\right )$ ，
4. 又因为 $a{{}_{1}}=4,a{{}_{2}}=10,a{{}_{2}}-1=3\left ({a{{}_{1}}-1}\right )$ 成立，
5. 所以 $\frac {a{{}_{n+1}}-1}{a{{}_{n}}-1}=3$ 对 $n\in {\mathbf{N}}{^{{\rm{*}}}}$ 成立，
6. 所以数列 $\left \{a{{}_{n}}-1\right \}$ 为以 $a{{}_{1}}-1=3$ 为首项， $q=3$ 为公比的等比数列，
7. 所以 $a{{}_{n}}-1=3{^{n}}$ ，即 $a{{}_{n}}=3{^{n}}+1$ ；
8. （2）因为 $f\left ({x}\right )=a{{}_{1}}x+a{{}_{2}}x{^{2}}+\cdots +a{{}_{n-1}}x{^{n-1}}+a{{}_{n}}x{^{n}}$ ，
9. $f^{′}{\left ({x}\right )}=a{{}_{1}}+2a{{}_{2}}x+\cdots +\left ({n-1}\right )a{{}_{n-1}}x{^{n-2}}+na{{}_{n}}x{^{n-1}}$ ，
10. $f^{′}{\left ({1}\right )}=a{{}_{1}}+2a{{}_{2}}+\cdots +\left ({n-1}\right )a{{}_{n-1}}+na{{}_{n}}$ ，
11. $=3{^{1}}+1+2\left ({3{^{2}}+1}\right )+\cdots +\left ({n-1}\right )\left ({3{^{n-1}}+1}\right )+n\left ({3{^{n}}+1}\right )$ ，
12. $=\left ({3{^{1}}+2\cdot 3{^{2}}+3\cdot 3{^{3}}+\cdots +n\cdot 3{^{n}}}\right )+\left ({1+2+3+\cdots +n}\right )$ ，
13. 令 $T{{}_{n}}=3{^{1}}+2\cdot 3{^{2}}+\cdots +\left ({n-1}\right )3{^{n-1}}+n\cdot 3{^{n}}$ ，
14. $3T{{}_{n}}=3{^{2}}+2\cdot 3{^{3}}+\cdots +\left ({n-1}\right )\cdot 3{^{n}}+n\cdot 3{^{n+1}}$ ，
15. 则 $-2T{{}_{n}}=3{^{1}}+3{^{2}}+\cdots +3{^{n}}-n\cdot 3{^{n+1}}$ ，
16. 所以 $T{{}_{n}}=\frac {\left ({2n-1}\right )\cdot 3{^{n+1}}}{4}+\frac {3}{4}$ ，故 $f^{′}{\left ({1}\right )}=\frac {\left ({2n-1}\right )\cdot 3{^{n+1}}}{4}+\frac {3}{4}+\frac {n{^{2}}+n}{2}$ ，
17. 所以 $f^{′}{\left ({1}\right )}-\frac {8n{^{2}}+11n-3}{4}=\frac {\left ({2n-1}\right )\cdot 3{^{n+1}}}{4}-\frac {6n{^{2}}+9n-6}{4}$  $=\frac {3\left ({2n-1}\right )\left ({3{^{n}}-\left ({n+2}\right )}\right )}{4}$ ；
18. 所以当 $n=1$ 时， $f^{′}{\left ({1}\right )}=\frac {8n{^{2}}+11n-3}{4}$ ，当 $n\mathrm{\geqslant }2$ 时， $2n-1>0$ ，
19. $3{^{n+1}}-\left ({n+3}\right )-3{^{n}}+\left ({n+2}\right )$  $=2\cdot 3{^{n}}-1>0$ ，
20. 所以 $3{^{n}}-\left ({n+2}\right )$ 单调递增，所以 $f^{′}{\left ({1}\right )}>\frac {8n{^{2}}+11n-3}{4}$ ；
21. （3）令 $f\left ({x}\right )=x-1-{\rm{l}}{\rm{n}}x$ ，则 $f^{′}{\left ({x}\right )}=1-\frac {1}{x}=\frac {x-1}{x}$ ，
22. 令 $f^{′}{\left ({x}\right )}>0$ ，则 $x>1$ ，令 $f^{′}{\left ({x}\right )}<0$ ，则 $0<x<1$ ，
23. 故 $f\left ({x}\right )$ 在 $\left ({0,1}\right )$ 单调递减， $\left ({1,+\infty }\right )$ 单调递增，则 $f(x){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=f^{′}{\left ({1}\right )}=0$ ，
24. 所以 $f\left ({x}\right )\geqslant f\left ({1}\right )=0,x-1\geqslant {\rm{l}}{\rm{n}}x$ （当且仅当 $x=1$ 时取等号），
25. 则 ${\rm{l}}{\rm{n}}\left ({1+\frac {1}{a{{}_{n}}}}\right )<\frac {1}{a{{}_{n}}}=\frac {1}{3{^{n}}+1}<\frac {1}{3{^{n}}}$ ，
26. 所以 ${\rm{l}}{\rm{n}}\left ({1+\frac {1}{a{{}_{1}}}}\right )<\frac {1}{3},{\rm{l}}{\rm{n}}\left ({1+\frac {1}{a{{}_{2}}}}\right )<\frac {1}{3{^{2}}},\cdots ,{\rm{l}}{\rm{n}}\left ({1+\frac {1}{a{{}_{n}}}}\right )<\frac {1}{3{^{n}}}$ ，
27. 所以 ${\rm{l}}{\rm{n}}\left ({1+\frac {1}{a{{}_{1}}}}\right )+{\rm{l}}{\rm{n}}\left ({1+\frac {1}{a{{}_{2}}}}\right )+\cdots +{\rm{l}}{\rm{n}}\left ({1+\frac {1}{a{{}_{n}}}}\right )<\frac {1}{3}+\frac {1}{3{^{2}}}+\cdots +\frac {1}{3{^{n}}}$ ，
28. ${\rm{l}}{\rm{n}}\left ({1+\frac {1}{a{{}_{1}}}}\right )+{\rm{l}}{\rm{n}}\left ({1+\frac {1}{a{{}_{2}}}}\right )+\cdots +{\rm{l}}{\rm{n}}\left ({1+\frac {1}{a{{}_{n}}}}\right )<\frac {1}{2}-\frac {1}{2}\cdot {\left({\frac {1}{3}}\right)^{n}}<\frac {1}{2}={\rm{l}}{\rm{n}}\sqrt {\mathrm{e}}$ ，
29. $\left ({1+\frac {1}{a{{}_{1}}}}\right )\left ({1+\frac {1}{a{{}_{2}}}}\right )\cdots \left ({1+\frac {1}{a{{}_{n}}}}\right )<\sqrt {\mathrm{e}}$ ，
30. 设 $b{{}_{n}}=\left ({1+\frac {1}{a{{}_{1}}}}\right )\left ({1+\frac {1}{a{{}_{2}}}}\right )\cdots \left ({1+\frac {1}{a{{}_{n}}}}\right )$ ，则 $\frac {b{{}_{n+1}}}{b{{}_{n}}}=1+\frac {1}{a{{}_{n+1}}}>1$ ，
31. 则 $\left \{b{{}_{n}}\right \}$ 单调递增，又因为 $\left ({1+\frac {1}{a{{}_{1}}}}\right )\left ({1+\frac {1}{a{{}_{2}}}}\right )\cdots \left ({1+\frac {1}{a{{}_{n}}}}\right )>1+\frac {1}{a{{}_{1}}}=\frac {5}{4}$ ，
32. 所以正整数 $m$ 的最小值为2．

## 知识点

**中文**:
  - 利用前n项和与通项关系求通项公式
  - 简单复合函数的求导法则
  - 数列求和方法之错位相减法
  - 赋值法在二项式定理中的应用

**English**:
  - Using Sum-Term Relation
  - Chain Rule for Simple Composite Functions
  - Offset Subtraction Method
  - Assignment Method

---
