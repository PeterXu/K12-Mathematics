# Mathematics - 题目 2999

**ID**: 7cc91d56db33405ea7a2cfb8c10ed33f
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Multiple-select

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ 满足 $a{{}_{1}}=1$ ， $a{{}_{1}}+\frac {a{{}_{2}}}{2}+\cdots +\frac {a{{}_{n}}}{n}=\frac {na{{}_{n+1}}}{2(n+1)}$ ，令 $b{{}_{n}}=\frac {1}{1012}\left ({\frac {a{{}_{n}}}{n}-1}\right )$ ，则（      ）​​​​​​​‌

## 解答

1. 因为 $a{{}_{1}}+\frac {a{{}_{2}}}{2}+\cdots +\frac {a{{}_{n}}}{n}=\frac {na{{}_{n+1}}}{2\left ({n+1}\right )}$ ①，
2. 所以当 $n\geqslant 2$ 时， $a{{}_{1}}+\frac {a{{}_{2}}}{2}+\cdots +\frac {a{{}_{n-1}}}{n-1}=\frac {\left ({n-1}\right )a{{}_{n}}}{2n}$ ②，
3. ①-②得： $\frac {a{{}_{n}}}{n}=\frac {na{{}_{n+1}}}{2\left ({n+1}\right )}-\frac {\left ({n-1}\right )a{{}_{n}}}{2n}=\frac {n{^{2}}a{{}_{n+1}}-\left ({n{^{2}}-1}\right )a{{}_{n}}}{2n\left ({n+1}\right )}$ .
4. 化简得 $n{^{2}}a{{}_{n+1}}={\left({n+1}\right)^{2}}a{{}_{n}}$ .
5. 所以 $\frac {a{{}_{n+1}}}{{\left({n+1}\right)^{2}}}=\frac {a{{}_{n}}}{n{^{2}}}$ ，所以数列 $\left \{\frac {a{{}_{n}}}{n{^{2}}}\right \}$ 为首项是1，公比为1的等比数列.
6. 所以 $\frac {a{{}_{n}}}{n{^{2}}}=a{{}_{1}}q{^{n-1}}=1$ ，所以 $a{{}_{n}}=n{^{2}}$ .
7. 所以 $b{{}_{n}}=\frac {1}{1012}\left ({\frac {a{{}_{n}}}{n}-1}\right )=\frac {n-1}{1012}$ .
8. 对于选项A： $a{{}_{10}}=10{^{2}}=100$ ，所以A正确；
9. 对于选项B：因为 $b{{}_{n}}=\frac {n-1}{1012}=0+\left ({n-1}\right )·\frac {1}{1012}$ ，所以数列 $\left \{b{{}_{n}}\right \}$ 是首项为0，公差为 $\frac {1}{1012}$ 的等差数列，所以B正确；
10. 对于选项C： $b{{}_{2024}}=\frac {2024-1}{1012}=\frac {2023}{1012}$ ，不是整数，所以C错误；
11. 对于选项D：因为数列 $\left \{b{{}_{n}}\right \}$ 是首项为0，公差为 $\frac {1}{1012}$ 的等差数列，
12. 所以 $S{{}_{2025}}=2025\times 0+\frac {2025\times 2024}{2}\times \frac {1}{1012}=2025$ ，所以D正确.
13. 故选ABD.

## 知识点

**中文**:
  - 数列通项求法之构造法
  - 等差数列的概念及通项公式
  - 等差数列求和公式基本应用

**English**:
  - Construction Method
  - Concept and Formula
  - Basic Applications of Sum Formula

---
