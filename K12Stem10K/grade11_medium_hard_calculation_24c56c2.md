# Mathematics - 题目 787

**ID**: 24c56c2f1c33451f97383d988f3df6a0
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
在数列 $\left \{a{{}_{n}}\right \}$ 中，已知 $a{{}_{1}}=2$ ，且当 $n$ 为奇数时， $a{{}_{n+1}}=3a{{}_{n}}+1$ ；当 $n$ 为偶数时， $a{{}_{n+1}}=2a{{}_{n-1}}$ .​​​​​​​‌（1）求 $\left \{a{{}_{n}}\right \}$ 的通项公式；（2）求 $\left \{a{{}_{n}}\right \}$ 的前 $n$ 项和 $S{{}_{n}}$ ；（3）设 $b{{}_{n}}=\frac {a{{}_{n}}}{2{^{n}}}$ ，若集合 $M=\left \{n|b{{}_{n}}\geqslant λ\right \}$ 中恰好有3个元素，求实数 $λ$ 的取值范围.

## 解答

1. （1）由条件可知， $a{{}_{2}}=3a{{}_{1}}+1=7$ ，
2. 当 $n$ 为偶数时， $a{{}_{n+1}}=2a{{}_{n-1}}$ ，所以数列 $\left \{a{{}_{n}}\right \}$ 的奇数项成公比为2的等比数列，
3. 所以 $a{{}_{2n-1}}=a{{}_{1}}\cdot 2{^{n-1}}=2{^{n}}$ ，所以 $n$ 为奇数时， $a{{}_{n}}=2{^{\frac {n+1}{2}}}$ ，
4. 当 $n$ 为偶数时， $a{{}_{n}}=3a{{}_{n-1}}+1=3\cdot 2{^{\frac {n}{2}}}+1$ ，
5. 所以 $a{{}_{n}}=\begin{cases}2{^{\frac {n+1}{2}}},n为奇数\\3\cdot 2{^{\frac {n}{2}}}+1,n为偶数\end{cases}$ ；
6. （2）当 $n$ 为偶数时，
7. $S{{}_{n}}=2+\left ({3\times 2+1}\right )+4+\left ({3\times 2{^{2}}+1}\right )+...+2{^{\frac {n}{2}}}+\left ({3\times 2{^{\frac {n}{2}}}+1}\right )$
8. $=\left ({2+4+...+2{^{\frac {n}{2}}}}\right )+3\times \left ({2+2{^{2}}+...2{^{\frac {n}{2}}}}\right )+\frac {n}{2}$
9. $=4\times \frac {2\times \left ({1-2{^{\frac {n}{2}}}}\right )}{1-2}+\frac {n}{2}=2{^{\frac {n}{2}+3}}-8+\frac {n}{2}$ ；
10. 当 $n$ 为奇数时，
11. $S{{}_{n}}=2+\left ({3\times 2+1}\right )+4+\left ({3\times 2{^{2}}+1}\right )+...+\left ({3\times 2{^{\frac {n-1}{2}}}+1}\right )+2{^{\frac {n+1}{2}}}$ ，
12. $=\left ({2+4+...+2{^{\frac {n+1}{2}}}}\right )+3\times \left ({2+2{^{2}}+...2{^{\frac {n-1}{2}}}}\right )+\frac {n-1}{2}$
13. $=\frac {2\times \left ({1-2{^{\frac {n+1}{2}}}}\right )}{1-2}+3\times \frac {2\times \left ({1-2{^{\frac {n-1}{2}}}}\right )}{1-2}+\frac {n-1}{2}$ ；
14. $=5\cdot 2{^{\frac {n+1}{2}}}-8+\frac {n-1}{2}$ ，
15. 所以 $S{{}_{n}}=\begin{cases}5\cdot 2{^{\frac {n+1}{2}}}-8+\frac {n-1}{2},n为奇数\\2{^{\frac {n}{2}+3}}-8+\frac {n}{2},n为偶数\end{cases}$ ；
16. （3） $b{{}_{n}}=\begin{cases}2{^{\frac {1-n}{2}}},n为奇数\\3\cdot 2{^{-\frac {n}{2}}}+2{^{-n}},n为偶数\end{cases}$ ，
17. 所以当 $n$ 为奇数时，数列 $\left \{b{{}_{n}}\right \}$ 单调递减，当 $n$ 为偶数时，数列 $\left \{b{{}_{n}}\right \}$ 单调递减，
18. $b{{}_{1}}=1$ ， $b{{}_{2}}=\frac {7}{4}$ ， $b{{}_{3}}=\frac {1}{2}$ ， $b{{}_{4}}=\frac {13}{16}$ ，
19. 若集合 $M=\left \{n|b{{}_{n}}\geqslant λ\right \}$ 中恰好有3个元素，则 $\frac {1}{2}<λ\leqslant \frac {13}{16}$ .

## 知识点

**中文**:
  - 数列求和方法之分组转化法
  - 等比数列的概念与通项公式
  - 数列通项求法之构造法

**English**:
  - Grouping Method
  - Concept and Formula
  - Construction Method

---
