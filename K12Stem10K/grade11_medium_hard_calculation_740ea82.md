# Mathematics - 题目 3375

**ID**: 740ea82e1f7e4c3b9eb2b9b5c9377d4a
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ 满足 $a{{}_{1}}=1$ ， $a{{}_{n+1}}=1-\frac {1}{4a{{}_{n}}}$ ，设 $b{{}_{n}}=\frac {2}{2a{{}_{n}}-1}$ ，其中 $n\in {\mathbf{N}}{^{*}}$ .​​​​​​​‌(1)求证：数列 $\left \{b{{}_{n}}\right \}$ 是等差数列；(2)求数列 $\left \{\frac {b{{}_{n}}}{2{^{n+1}}}\right \}$ 的前 $n$ 项和 $S{{}_{n}}$ ；(3)设数列 $\left \{\frac {n+2}{b{{}_{n}}\cdot b{{}_{n+1}}\cdot 2{^{n}}}\right \}$ 的前 $n$ 项和为 $T{{}_{n}}$ ，证明： $\frac {3}{16}\leqslant T{{}_{n}}<\frac {1}{4}$ .

## 解答

1. （1）因为 $a{{}_{1}}=1$ ， $a{{}_{n+1}}=1-\frac {1}{4a{{}_{n}}}$ ，且 $b{{}_{n}}=\frac {2}{2a{{}_{n}}-1}$ ，
2. 所以 $b{{}_{1}}=\frac {2}{2a{{}_{1}}-1}=2$ ，
3. $b{{}_{n+1}}-b{{}_{n}}=\frac {2}{2a{{}_{n+1}}-1}-\frac {2}{2a{{}_{n}}-1}$
4. $=\frac {2}{2\left ({1-\frac {1}{4a{{}_{n}}}}\right )-1}-\frac {2}{2a{{}_{n}}-1}=\frac {2}{1-\frac {1}{2a{{}_{n}}}}-\frac {2}{2a{{}_{n}}-1}=\frac {4a{{}_{n}}-2}{2a{{}_{n}}-1}=2$ ，
5. 所以数列 $\left \{b{{}_{n}}\right \}$ 是首项为 $2$ ，公差为 $2$ 的等差数列；
6. （2）由（1）可得 $b{{}_{n}}=2+(n-1)\times 2=2n$ ，
7. 所以 $\frac {b{{}_{n}}}{2{^{n+1}}}=\frac {2n}{2{^{n+1}}}=\frac {n}{2{^{n}}}$ ，
8. 则 $S{{}_{n}}=\frac {1}{2}+\frac {2}{2{^{2}}}+\cdots +\frac {n}{2{^{n}}}$ ①，
9. $\frac {1}{2}S{{}_{n}}=\frac {1}{2{^{2}}}+\frac {2}{2{^{3}}}+\cdots +\frac {n}{2{^{n+1}}}②$ ，
10. ① $-$ ②得 $\frac {1}{2}S{{}_{n}}=\frac {1}{2}+\frac {1}{2{^{2}}}+\cdots +\frac {1}{2{^{n}}}-\frac {n}{2{^{n+1}}}=\frac {\frac {1}{2}\left ({1-\frac {1}{2{^{n}}}}\right )}{1-\frac {1}{2}}-\frac {n}{2{^{n+1}}}$
11. $=1-\frac {1}{2{^{n}}}-\frac {n}{2{^{n+1}}}$ ，
12. 所以 $S{{}_{n}}=2-\frac {n+2}{2{^{n}}}$ ；
13. （3）由（2）可得 $\frac {n+2}{b{{}_{n}}\cdot b{{}_{n+1}}\cdot 2{^{n}}}=\frac {n+2}{2n\left ({2n+2}\right )\times 2{^{n}}}$
14. $=\frac {1}{4}\times \frac {2{^{n+1}}(n+2)}{n\times 2{^{n}}\times (n+1)\times 2{^{n+1}}}=\frac {1}{n\times 2{^{n+1}}}-\frac {1}{(n+1)\times 2{^{n+2}}}$ ，
15. 所以 $T{{}_{n}}=\frac {1}{1\times 2{^{2}}}-\frac {1}{2\times 2{^{3}}}+\cdots +\frac {1}{n\times 2{^{n+1}}}-\frac {1}{(n+1)\times 2{^{n+2}}}=\frac {1}{4}-\frac {1}{(n+1)\times 2{^{n+2}}}<\frac {1}{4}$ ，
16. 又因为 $T{{}_{n+1}}-T{{}_{n}}=\frac {1}{4}-\frac {1}{(n+2)\times 2{^{n+3}}}-\frac {1}{4}+\frac {1}{(n+1)\times 2{^{n+2}}}=\frac {1}{(n+1)\times 2{^{n+2}}}-\frac {1}{(n+2)\times 2{^{n+3}}}$
17. $=\frac {n+3}{(n+1)\left ({n+2}\right )\times 2{^{n+3}}}>0$ ，
18. 所以数列 $\left \{T{{}_{n}}\right \}$ 单调递增，所以 $T{{}_{n}}=\frac {1}{4}-\frac {1}{(n+1)\times 2{^{n+2}}}\geqslant T{{}_{1}}=\frac {3}{16}$ ，
19. 综上可得 $\frac {3}{16}\leqslant T{{}_{n}}<\frac {1}{4}$ ．

## 知识点

**中文**:
  - 数列与不等式的综合
  - 等差数列的判定与证明
  - 数列求和方法之错位相减法

**English**:
  - Sequences with Inequalities
  - Determination and Proof
  - Offset Subtraction Method

---
