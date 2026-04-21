# Mathematics - 题目 2149

**ID**: f90262bdc8b74f71a24ce71eaf1f38a4
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知 $\left \{a{{}_{n}}\right \}$ 为等差数列 ${\rm ，}\left \{b{{}_{n}}\right \}$ 是公比为2的等比数列 ${\rm ．}a{{}_{1}}=1{\rm ，}$ 且 $a{{}_{3}}-b{{}_{1}}=1，a{{}_{4}}-b{{}_{1}}=b{{}_{3}}-a{{}_{6}}$ ．(1)求数列 $\left \{a{{}_{n}}\right \}$ 和 $\left \{b{{}_{n}}\right \}$ 的通项公式；​​​​​​​‌(2)若 $c{{}_{k}}=\begin{cases}\left ({a{{}_{k}}-\frac {1}{a{{}_{k}}}}\right )b{{}_{k}}，k为奇数，\\\left ({a{{}_{2n+1-k}}+\frac {1}{a{{}_{2n+1-k}}}}\right )b{{}_{2n+1-k}}，k为偶数．\end{cases}$①当 $k$ 为奇数，求 $c{{}_{k}}+c{{}_{2n+1-k}}$ ；②求 ${\mathop {\sum ^{2n}\mathop{}}\limits_{k=1}^{}}c{{}_{k}}$ ．

## 解答

1. （1）设数列 $\left \{a{{}_{n}}\right \}$ 的公差为 $d，\because ｛{b}_{n}｝$ 的公比为 $2，a{{}_{1}}=1{\rm ，}$
2. 由已知可得 $\begin{cases}1+2d-b{{}_{1}}=1\\1+3d-b{{}_{1}}=4b{{}_{1}}-\left ({1+5d}\right )\end{cases}{\rm ，}$ 得 $b{{}_{1}}=2，d=1{\rm ，}$
3. $\therefore a{{}_{n}}=n，b{{}_{n}}=2{^{n}}$ ；
4. （2）① $\because k$ 为奇数 ${\rm ，}\therefore 2n+1-k$ 为偶数．
5. $\therefore c{{}_{k}}+c{{}_{2n+1-k}}=\left ({a{{}_{k}}-\frac {1}{a{{}_{k}}}}\right )b{{}_{k}}+\left ({a{{}_{2n+1-\left ({2n+1-k}\right )}}+\frac {1}{a{{}_{2n+1-\left ({2n+1-k}\right )}}}}\right )\cdot b{{}_{2n+1-\left ({2n+1-k}\right )}}$
6. $=\left ({a{{}_{k}}-\frac {1}{a{{}_{k}}}}\right )b{{}_{k}}+\left ({a{{}_{k}}+\frac {1}{a{{}_{k}}}}\right )b{{}_{k}}=2a{{}_{k}}b{{}_{k}}=2k\cdot 2{^{k}}=k\cdot 2{^{k+1}}$ ；
7. ②当 $k$ 为偶数 ${\rm ，}2n+1-k$ 为奇数，
8. $c{{}_{k}}+c{{}_{2n+1-k}}=\left ({a{{}_{2n+1-k}}+\frac {1}{a{{}_{2n+1-k}}}}\right )b{{}_{2n+1-k}}+\left ({a{{}_{2n+1-k}}-\frac {1}{a{{}_{2n+1-k}}}}\right )b{{}_{2n+1-k}}=2a{{}_{2n+1-k}}b{{}_{2n+1-k}}$
9. $=2\left ({2n+1-k}\right )\cdot 2{^{2n+1-k}}=\left ({2n+1-k}\right )\cdot 2{^{2n+2-k}}$
10. ②令 $S{{}_{2n}}={\mathop {\sum ^{2n}\mathop{}}\limits_{k=1}^{}}c{{}_{k}}{\rm ，}$
11. $\because S{{}_{2n}}=c{{}_{1}}+c{{}_{2}}+\cdots +c{{}_{2n-1}}+c{{}_{2n}}{\rm ，}$
12. 即 $S{{}_{2n}}=c{{}_{2n}}+c{{}_{2n-1}}+\cdots +c{{}_{2}}+c{{}_{1}}{\rm ，}$
13. $\therefore 2S{{}_{2n}}=\left ({c{{}_{1}}+c{{}_{2n}}}\right )+\left ({c{{}_{2}}+c{{}_{2n-1}}}\right )+\cdots +\left ({c{{}_{2n-1}}+c{{}_{2}}}\right )+\left ({c{{}_{2n}}+c{{}_{1}}}\right ){\rm ，}$
14. $2S{{}_{2n}}=\left ({c{{}_{1}}+c{{}_{2n}}}\right )+\left ({c{{}_{3}}+c{{}_{2n-2}}}\right )+\cdots +\left ({c{{}_{2n-1}}+c{{}_{2}}}\right )+\left ({c{{}_{2}}+c{{}_{2n-1}}}\right )+\left ({c{{}_{4}}+c{{}_{2n-3}}}\right )+\cdots +\left ({c{{}_{2n}}+c{{}_{1}}}\right )$  $=1\times 2{^{2}}+3\times 2{^{4}}+\cdots +\left ({2n-1}\right )\cdot 2{^{2n}}+\left ({2n-1}\right )\cdot 2{^{2n}}+\left ({2n-3}\right )\cdot 2{^{2n-2}}+\cdots +1\times 2{^{2}}$
15. $\therefore $  $S{{}_{2n}}=1\times 2+3\times 2{^{3}}+\cdots +\left ({2n-1}\right )\cdot 2{^{2n-1}}+\left ({2n-1}\right )\cdot 2{^{2n-1}}+\left ({2n-3}\right )\cdot 2{^{2n-3}}+\cdots +1\times 2$
16. $\therefore $  $4S{{}_{2n}}=1\times 2{^{3}}+3\times 2{^{5}}+\cdots +\left ({2n-1}\right )\cdot 2{^{2n+1}}+\left ({2n-1}\right )\cdot 2{^{2n+1}}+\left ({2n-3}\right )\cdot 2{^{2n-1}}+\cdots +1\times 2{^{3}}$
17. $\therefore $  $-3S{{}_{2n}}=2+2\left ({2{^{3}}+2{^{5}}+\cdots +2{^{2n-1}}}\right )-\left ({2n-1}\right )\cdot 2{^{2n+1}}-\left ({2n-1}\right )\cdot 2{^{2n+1}}+2\left ({2{^{2n-1}}+2{^{2n-3}}+\cdots +2{^{3}}}\right )+2$  $=2+2\times \frac {2{^{3}}-2{^{2n-1}}\times 4}{1-4}-\left ({2n-1}\right )\cdot 2{^{2n+1}}-\left ({2n-1}\right )\cdot 2{^{2n+1}}+2\times \frac {2{^{3}}-2{^{2n-1}}\times 4}{1-4}+2$
18. $=-\frac {20}{3}+\frac {10-12n}{3}\times 2{^{2n+1}}$
19. $\therefore $  $S{{}_{2n}}=\frac {20}{9}+\frac {12n-10}{9}\times 2{^{2n+1}}$ .

## 知识点

**中文**:
  - 数列求和方法之倒序相加法
  - 等差数列的概念及通项公式
  - 等比数列的概念与通项公式
  - 数列求和方法之错位相减法

**English**:
  - Reversing Order Summation
  - Concept and Formula
  - Concept and Formula
  - Offset Subtraction Method

---
