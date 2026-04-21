# Mathematics - 题目 2021

**ID**: d0912da15e6f4d2a90e29705deaf0af9
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知公差不为0的等差数列 $\left \{a{{}_{n}}\right \}$ 的首项 $a{{}_{1}}=1$ ，前 $n$ 项和为 $S{{}_{n}}$ ，且 $a{{}_{1}}$ ， $a{{}_{2}}$ ， $a{{}_{4}}$ 成等比数列．（1）求数列 $\left \{a{{}_{n}}\right \}$ 的通项公式及 $S{{}_{n}}$ ；​​​​​​​‌（2）记 $A=\frac {1}{S{{}_{1}}}+\frac {1}{S{{}_{2}}}+\cdots +\frac {1}{S{{}_{n}}}$ ， $B=\frac {1}{a{{}_{2}^{0}}}+\frac {1}{a{{}_{2}^{1}}}+\cdots +\frac {1}{a{{}_{2}^{n-1}}}$ ，当 $n\mathrm{\geqslant }2$ 时，比较 $\mathrm{A}$ 与 $B$ 的大小；（3）是否存在实数 $k$ ，使得对任意的正整数 $m$ ， $n$ ，都有 $a{{}_{m}^{2}}+a{{}_{n}^{2}}\geqslant k\cdot a{{}_{m+n}^{2}}$ 成立？若存在，求 $k$ 的最大值；若不存在，请说明理由．

## 解答

1. （1）设公差为 $d$ ，由 $a{{}_{1}}$ ， $a{{}_{2}}$ ， $a{{}_{4}}$ 成等比数列得 $a{{}_{2}^{2}}=a{{}_{1}}a{{}_{4}}$ ，即 $(1+d){^{2}}=1\cdot (1+3d)$ ，
2. 求得 $d=1$ 或 $d=0$ （舍去），
3. 所以 $a{{}_{n}}=1+(n-1)\cdot 1=n$ ， $S{{}_{n}}=\frac {\left ({1+a{{}_{n}}}\right )\cdot n}{2}=\frac {1}{2}n(n+1)$ ．
4. （2）由（1）知， $a{{}_{n}}=n$ ， $S{{}_{n}}=\frac {1}{2}n\left ({n+1}\right )$ ，则 $a{{}_{2}}=2$ ，
5. $A=\frac {1}{S{{}_{1}}}+\frac {1}{S{{}_{2}}}+\cdots +\frac {1}{S{{}_{n}}}=2\left [\frac {1}{1\times 2}+\frac {1}{2\times 3}+\cdots +\frac {1}{n\times (n+1)}\right ]$
6. $=2\left [\frac {1}{1}-\frac {1}{2}+\frac {1}{2}-\frac {1}{3}+\cdots +\frac {1}{n}-\frac {1}{n+1}\right ]=2\left ({1-\frac {1}{n+1}}\right )$ ，
7. $B=\frac {1}{a{{}_{2}^{0}}}+\frac {1}{a{{}_{2}^{1}}}+\cdots +\frac {1}{a{{}_{2}^{n-1}}}=\frac {1}{2{^{0}}}+\frac {1}{2{^{1}}}+\cdots +\frac {1}{2{^{n-1}}}=2-\frac {1}{2{^{n-1}}}=2\left ({1-\frac {1}{2{^{n}}}}\right )$ ，
8. 因为当 $n\mathrm{\geqslant }2$ 时， $2{^{n}}>n+1$ ，即 $1-\frac {1}{2{^{n}}}\geqslant 1-\frac {1}{n+1}$ ，所以 $A<B$ ．
9. （3）要使 $a{{}_{m}^{2}}+a{{}_{n}^{2}}\geqslant k\cdot a{{}_{m+n}^{2}}\left ({m,n\in {\mathbf{N}}{^{*}}}\right )$ 恒成立，
10. 只需 $k\leqslant \frac {a{{}_{m}^{2}}+a{{}_{n}^{2}}}{a{{}_{m+n}^{2}}}\left ({m,n\in {\mathbf{N}}{^{*}}}\right )$ 恒成立，即 $k\leqslant \left ({\frac {a{{}_{m}^{2}}+a{{}_{n}^{2}}}{a{{}_{m+n}^{2}}}}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}$ ，
11. 因为 $\frac {a{{}_{m}^{2}}+a{{}_{n}^{2}}}{a{{}_{m+n}^{2}}}=\frac {m{^{2}}+n{^{2}}}{(m+n){^{2}}}=\frac {m{^{2}}+n{^{2}}}{m{^{2}}+n{^{2}}+2mn}$ ，又因为 $2mn\leqslant m{^{2}}+n{^{2}}$ ，
12. 所以 $\frac {m{^{2}}+n{^{2}}}{m{^{2}}+n{^{2}}+2mn}\geqslant \frac {m{^{2}}+n{^{2}}}{2\left ({m{^{2}}+n{^{2}}}\right )}=\frac {1}{2}$ （当且仅当 $m=n$ 时等号成立），
13. 所以 $k\leqslant \frac {1}{2}$ 时，对任意的正整数 $m$ ， $n$ ，不等式 $a{{}_{m}^{2}}+a{{}_{n}^{2}}\geqslant k\cdot a{{}_{m+n}^{2}}$ 都成立，
14. 即实数 $k$ 存在，最大值为 $\frac {1}{2}$ ．

## 知识点

**中文**:
  - 等差数列的概念及通项公式
  - 等比数列的概念与通项公式
  - 等比中项

**English**:
  - Concept and Formula
  - Concept and Formula
  - Geometric Mean (Middle Term)

---
