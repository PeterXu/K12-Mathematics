# Mathematics - 题目 3646

**ID**: 7dfb6ca74aa04a35a2fb15e17e3ddc7a
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
已知正项等比数列 $\{b{{}_{n}}\}$ 的前 $n$ 项和为 $S{{}_{n}}$ ， $b{{}_{3}}=4$ ， $S{{}_{3}}=7$ ，数列 $\{a{{}_{n}}\}$ 满足 $a{{}_{n+1}}-a{{}_{n}}=n+1(n\in {\mathbf{N}^{*}})$ ，且 $a{{}_{1}}=b{{}_{1}}$ ．（1）求数列 $\{a{{}_{n}}\}$ 的通项公式；​​​​​​​‌（2）求数列 $\{\frac {1}{a{{}_{n}}}\}$ 的前 $n$ 项和．

## 解答

1. （Ⅰ）根据题意，由等比数列 $\left \{b{{}_{n}}\right \}$ 的通项公式及前 $n$ 项和公式，建立关于首项和公比的方程，求数列 $\left \{a{{}_{n}}\right \}$ 的首项 $a{{}_{1}}=b{{}_{1}}$ ，再用迭加法求出数列 $\left \{a{{}_{n}}\right \}$ 的通项公式；（Ⅱ）由（Ⅰ）得 $\frac {1}{a{{}_{n}}}=\frac {2}{n{^{2}}+n}=2\left ({\frac {1}{n}-\frac {1}{n+1}}\right )$ ，再采用裂项相消法，即可求出数列 $\left \{\frac {1}{a{{}_{n}}}\right \}$ 的前 $n$ 项和.
2. 【试卷分析】
3. （Ⅰ）根据题意，设 $\left \{b{{}_{n}}\right \}$ 的公比为 $q$ ，所以 $\{\hspace{-0.5em}\begin{array}{}b{{}_{1}}q{^{2}}=4,\\b{{}_{1}}+b{{}_{1}}q+b{{}_{1}}q{^{2}}=7,\end{array}\hspace{-0.5em}$ 解得 $\{\hspace{-0.5em}\begin{array}{}b{{}_{1}}=1,\\q=2.\end{array}\hspace{-0.5em}$
4. 又 $a{{}_{n+1}}-a{{}_{n}}=n+1$ ，
5. 所以 $a{{}_{n}}=\left ({a{{}_{n}}-a{{}_{n-1}}}\right )+\left ({a{{}_{n-1}}-a{{}_{n-2}}}\right )+\ldots +\left ({a{{}_{3}}-a{{}_{2}}}\right )+\left ({a{{}_{2}}-a{{}_{1}}}\right )+a{{}_{1}}$
6. $=n+\left ({n+1}\right )+\ldots +2+1=\frac {n\left ({n+1}\right )}{2}=\frac {n{^{2}}+n}{2}$ ．
7. （Ⅱ）因为 $\frac {1}{a{{}_{n}}}=\frac {2}{n{^{2}}+n}=2\left ({\frac {1}{n}-\frac {1}{n+1}}\right )$ ，
8. 所以 $\frac {1}{a{{}_{1}}}+\frac {1}{a{{}_{2}}}++\frac {1}{a{{}_{n}}}=2\left [\left ({1-\frac {1}{2}}\right )+\left ({\frac {1}{2}-\frac {1}{3}}\right )+\ldots +\left ({\frac {1}{n-1}-\frac {1}{n}}\right )+\left ({\frac {1}{n}-\frac {1}{n+1}}\right )\right ]=2\left ({1-\frac {1}{n+1}}\right )=\frac {2n}{n+1}$ ．

## 知识点

**中文**:
  - 数列求和方法之裂项相消法
  - 等比数列的概念与通项公式
  - 等比数列前n项和公式
  - 数列通项求法之累加法

**English**:
  - Telescoping Series Method
  - Concept and Formula
  - Sum Formula
  - Accumulation Method (Telescoping Sums)

---
