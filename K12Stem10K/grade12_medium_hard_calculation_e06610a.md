# Mathematics - 题目 3904

**ID**: e06610a3d0c645cd9c6ef5b7deacc755
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
数学归纳法是一种数学证明方法，通常被用于证明某个给定的命题在整个（或者局部）自然数范围内成立，证明分为下面两个步骤：1.​​​​​​​‌证明当 $n=n{{}_{0}}$ （ $n{{}_{0}}\in {\mathbf{N}}$ ）时命题成立；2.假设 $n=k$ （ $k\in {\mathbf{N}}$ ，且 $k\geqslant n{{}_{0}}$ ）时命题成立，推导出在 $n=k+1$ 时命题也成立.只要完成这两个步骤，就可以断定命题对从 $n{{}_{0}}$ 开始的所有自然数n都成立.已知有穷递增数列 $\left \{a{{}_{n}}\right \}$ ， $a{{}_{1}}=-1$ ， $a{{}_{2}}>0$ ， $n\in {\mathbf{N}}{^{*}}$ 且 $n\geqslant 3$ .定义：集合 $A=\left \{\left ({x,y}\right )\left |{x=a{{}_{i}},y=a{{}_{j}},1\leqslant i,j\leqslant n,i,j\in {\mathbf{N}}{^{*}}}\right .\right \}$ ，若对 $\forall \left ({x{{}_{1}},y{{}_{1}}}\right )\in A$ ， $\exists \left ({x{{}_{2}},y{{}_{2}}}\right )\in A$ ，使得 $x{{}_{1}}x{{}_{2}}+y{{}_{1}}y{{}_{2}}=0$ ，则称 $\left \{a{{}_{n}}\right \}$ 具有性质T.(1)若数列 $-1$ ，1，2，m（ $m>2$ ）具有性质T，求实数m的值；(2)若 $\left \{a{{}_{n}}\right \}$ 具有性质T，且 $a{{}_{2}}=1$ ， $a{{}_{3}}=2$ ，（ⅰ）猜想当 $n\mathrm{\geqslant }2$ 时 $\left \{a{{}_{n}}\right \}$ 的通项公式，并用数学归纳法证明你的猜想；（ⅱ）求 $\frac {3}{2a{{}_{2}}}+\frac {2}{3a{{}_{3}}}+\frac {5}{12a{{}_{4}}}+\cdots +\frac {n+1}{n\left ({n-1}\right )a{{}_{n}}}$ （ $n\mathrm{\geqslant }2$ ）.

## 解答

1. （1）由已知，数列 $-1,1,2$ 具有性质 $T$ ，
2. 当 $\left ({x{{}_{1}},y{{}_{1}}}\right )=\left ({-1,m}\right )$ 时，取 $\left ({x{{}_{2}},y{{}_{2}}}\right )=\left ({m,1}\right )$ ，满足题意；
3. 当 $\left ({x{{}_{1}},y{{}_{1}}}\right )=\left ({1,m}\right )$ 时，取 $\left ({x{{}_{2}},y{{}_{2}}}\right )=\left ({m,-1}\right )$ ，满足题意；
4. 当 $\left ({x{{}_{1}},y{{}_{1}}}\right )=\left ({2,m}\right )$ 时， $2x{{}_{2}}+my{{}_{2}}=0$ ，此时 $x{{}_{2}},y{{}_{2}}$ 中有且仅有一个数为 $-1$ ，
5. 若 $x{{}_{2}}=-1$ ，则 $m=\frac {2}{y{{}_{2}}}\in \left ({0,2}\right ]$ ，不满足题意；
6. 若 $y{{}_{2}}=-1$ ，则 $m=2x{{}_{2}}=2$ 或 $4$ 或 $2m$ ，
7. 又因为 $m>2$ ，故 $m=4$ ；
8. 综上所述， $m=4$ .
9. （2）（ⅰ）猜想 $a{{}_{n}}=2{^{n-2}}\left ({n\geqslant 2}\right )$ .
10. 当 $n=2$ 时， $a{{}_{n}}=2{^{n-2}}$ 满足题意；
11. 假设 $n=k$ 时， $a{{}_{k}}=2{^{k-2}}$ 成立，则当 $n=k+1$ 时，
12. 若 $\left ({x{{}_{1}},y{{}_{1}}}\right )=\left ({-1,a{{}_{k+1}}}\right )$ ，则取 $\left ({x{{}_{2}},y{{}_{2}}}\right )=\left ({a{{}_{k+1}},1}\right )$ 满足题意；
13. 若 $\left ({x{{}_{1}},y{{}_{1}}}\right )=\left ({a{{}_{i}},a{{}_{k+1}}}\right ),i=2,3,\cdots ,k+1$ ，则 $x{{}_{2}},y{{}_{2}}$ 中有且仅有一个数为 $-1$ ，
14. 当 $x{{}_{2}}=-1$ 时，设 $y{{}_{2}}=a{{}_{j}},j=2,3,\cdots ,k+1$ ，则 $-a{{}_{i}}+a{{}_{k+1}}a{{}_{j}}=0$ ，
15. 故 $a{{}_{k+1}}=\frac {a{{}_{i}}}{a{{}_{j}}}\leqslant a{{}_{i}}\leqslant a{{}_{k+1}}$ ，当且仅当 $i=k+1,j=2$ 时，取得等号；
16. 当 $y{{}_{2}}=-1$ 时，设 $x{{}_{2}}=a{{}_{j}},j=2,3,\cdots ,k+1$ ，则 $a{{}_{i}}a{{}_{j}}=a{{}_{k+1}}=2{^{i+j-4}}$ ，
17. 记 $i+j-4=p$ ，则 $j=p-i+4$ ；
18. 因为对任意的 $i=2,3,\cdots ,k+1$ ，都有 $j=p-i+4=p-k+3,p-k+4,\cdots ,p+2$ 在 $2,3,4,\cdots ,k+1$ 中取到，
19. 则 $\begin{cases}2\leqslant p-k+3\\p+2\leqslant k+1\end{cases}$ ，即 $p=k-1$ ；
20. 故 $i+j=k+3$ ，故 $a{{}_{k+1}}=2{^{\left ({k+1}\right )-2}}$ 成立；
21. 综上， $a{{}_{n}}=2{^{n-2}}\left ({n\geqslant 2}\right )$ .
22. （ⅱ）因为 $n\geqslant 2$ 时，
23. $\frac {n+1}{n\left ({n-1}\right )a{{}_{n}}}=\frac {n+1}{\left ({n-1}\right )\cdot n\cdot 2{^{n-2}}}=\frac {1}{\left ({n-1}\right )\cdot 2{^{n-3}}}-\frac {1}{n\cdot 2{^{n-2}}}$
24. 故 $\frac {3}{2a{{}_{2}}}+\frac {2}{3a{{}_{3}}}+\frac {5}{12a{{}_{4}}}+\cdots +\frac {n+1}{n\left ({n-1}\right )a{{}_{n}}}$
25. $=\left ({2-\frac {1}{2}}\right )+\left ({\frac {1}{2}-\frac {1}{6}}\right )+\left ({\frac {1}{6}-\frac {1}{16}}\right )+\cdots +\left [\frac {1}{\left ({n-1}\right )\cdot 2{^{n-3}}}-\frac {1}{n\cdot 2{^{n-2}}}\right ]$
26. $=2-\frac {1}{n\cdot 2{^{n-2}}}\left ({n\geqslant 2}\right )$ .

## 知识点

**中文**:
  - 数学归纳法
  - 集合的新定义问题

**English**:
  - Mathematical Induction
  - New Definition Problems in Sets

---
