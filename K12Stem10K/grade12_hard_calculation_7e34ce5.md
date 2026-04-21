# Mathematics - 题目 2159

**ID**: 7e34ce54579b4428988e15dcac9253ee
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ ， $\left \{b{{}_{n}}\right \}$ 均为各项都不相等的数列， $S{{}_{n}}$ 为 $\left \{a{{}_{n}}\right \}$ 的前n项和， $a{{}_{n+1}}b{{}_{n}}=S{{}_{n}}+1\left ({n\in {\mathbf{N}^{*}}}\right )$ ．$\left ({1}\right )$ 若 $a{{}_{1}}=1,b{{}_{n}}=\frac {n}{2}$ ，求 $a{{}_{4}}$ 的值；​​​​​​​‌$\left ({2}\right )$ 若 $\left \{a{{}_{n}}\right \}$ 是公比为 $q\left ({q\ne 1}\right )$ 的等比数列，求证：数列 $\left \{b{{}_{n}}+\frac {1}{1-q}\right \}$ 为等比数列；$\left ({3}\right )$ 若 $\left \{a{{}_{n}}\right \}$ 的各项都不为零， $\left \{b{{}_{n}}\right \}$ 是公差为d的等差数列，求证： $a{{}_{2}}$ ， $a{{}_{3}}$ ， $\ldots $ ， $a{{}_{n}}$ ， $\ldots $ 成等差数列的充要条件是 $d=\frac {1}{2}$ ．

## 解答

1. 解： $\left ({1}\right )\because a{{}_{n+1}}b{{}_{n}}=S{{}_{n}}+1$ ， $a{{}_{1}}=1$ ， $b{{}_{n}}=\frac {n}{2}$ ，
2. $\therefore a{{}_{2}}=\frac {a{{}_{1}}+1}{b{{}_{1}}}=\frac {1+1}{\frac {1}{2}}=4$ ， $\frac {1+4+6+1}{\frac {3}{2}}$
3. $a{{}_{3}}=\frac {S{{}_{2}}+1}{b{{}_{2}}}=\frac {1+4+1}{1}=6$ ，
4. $a{{}_{4}}=\frac {S{{}_{3}}+1}{b{{}_{3}}}=\frac {1+4+6+1}{\frac {3}{2}}=8$ ，
5. 证明： $\left ({2}\right )$ 设 $a{{}_{n}}=a{{}_{1}}q{^{n-1}}\left ({q\ne 1}\right )$ ，则 $S{{}_{n}}=\frac {a{{}_{1}}\left ({1-q{^{n}}}\right )}{1-q}$ ，
6. $\because a{{}_{n+1}}b{{}_{n}}=S{{}_{n}}+1$ ，
7. $\therefore b{{}_{n}}=\frac {S{{}_{n}}+1}{a{{}_{n+1}}}=\frac {\frac {a{{}_{1}}\left ({1-q{^{n}}}\right )}{1-q}+1}{a{{}_{1}}q{^{n}}}=\frac {a{{}_{1}}-a{{}_{1}}q{^{n}}+1-q}{\left ({1-q}\right )a{{}_{1}}q{^{n}}}$ ，
8. $\therefore b{{}_{n}}+\frac {1}{1-q}=\frac {a{{}_{1}}-a{{}_{1}}q{^{n}}+1-q}{\left ({1-q}\right )a{{}_{1}}q{^{n}}}+\frac {1}{1-q}=\frac {a{{}_{1}}+1-q}{\left ({1-q}\right )a{{}_{1}}q{^{n}}}$
9. $\therefore b{{}_{n+1}}+\frac {1}{1-q}=\frac {a{{}_{1}}+1-q}{\left ({1-q}\right )a{{}_{1}}q{^{n+1}}}$
10. $\therefore \frac {b{{}_{n+1}}}{b{{}_{n}}}=q$ ， $(q$ 为常数 $)$
11. $\therefore $ 数列 $\left \{b{{}_{n}}+\frac {1}{1-q}\right \}$ 为等比数列，
12. $\left ({3}\right )\because $ 数列 $\left \{b{{}_{n}}\right \}$ 是公差为d的等差数列，
13. $\therefore $ 当 $n\geqslant 2$ 时， $a{{}_{n+1}}b{{}_{n}}-a{{}_{n}}\left ({b{{}_{n}}-d}\right )=a{{}_{n}}$ ，
14. 即 $\left ({a{{}_{n+1}}-a{{}_{n}}}\right )b{{}_{n}}=\left ({1-d}\right )a{{}_{n}}$ ，
15. $\because $ 数列 $\left \{a{{}_{n}}\right \}$ 的各项都不为零，
16. $\therefore a{{}_{n+1}}-a{{}_{n}}\ne 0$ ， $1-d\ne 0$ ，
17. $\therefore $ 当 $n\geqslant 2$ 时， $\frac {b{{}_{n}}}{1-d}=\frac {a{{}_{n}}}{a{{}_{n+1}}-a{{}_{n}}}$ ，
18. 当 $n\geqslant 3$ 时， $\frac {b{{}_{n-1}}}{1-d}=\frac {a{{}_{n-1}}}{a{{}_{n}}-a{{}_{n-1}}}$ ，
19. 两式相减得：当 $n\geqslant 3$ 时， $\frac {a{{}_{n}}}{a{{}_{n+1}}-a{{}_{n}}}-\frac {a{{}_{n-1}}}{a{{}_{n}}-a{{}_{n-1}}}=\frac {b{{}_{n}}-b{{}_{n-1}}}{1-d}=\frac {d}{1-d}$ ．
20. 先证充分性：
21. 由 $d=\frac {1}{2}$ 可知 $\frac {a{{}_{n}}}{a{{}_{n+1}}-a{{}_{n}}}-\frac {a{{}_{n-1}}}{a{{}_{n}}-a{{}_{n-1}}}=1$ ，
22. $\therefore $ 当 $n\geqslant 3$ 时， $\frac {a{{}_{n-1}}}{a{{}_{n}}-a{{}_{n-1}}}+1=\frac {a{{}_{n}}}{a{{}_{n+1}}-a{{}_{n}}}$ ，
23. 又 $\because a{{}_{n}}\ne 0$ ，
24. $\therefore a{{}_{n+1}}-a{{}_{n}}=a{{}_{n}}-a{{}_{n-1}}$ ，
25. 即 $a{{}_{2}}$ ， $a{{}_{3}}$ ， $\ldots $ ， $a{{}_{n}}\ldots $ 成等差数列；
26. 再证必要性：
27. $\because a{{}_{2}}$ ， $a{{}_{3}}$ ， $\ldots $ ， $a{{}_{n}}\ldots $ 成等差数列，
28. $\therefore $ 当 $n\geqslant 3$ 时， $a{{}_{n+1}}-a{{}_{n}}=a{{}_{n}}-a{{}_{n-1}}$ ，
29. $\therefore \frac {a{{}_{n}}}{a{{}_{n+1}}-a{{}_{n}}}-\frac {a{{}_{n-1}}}{a{{}_{n}}-a{{}_{n-1}}}=\frac {a{{}_{n-1}}}{a{{}_{n}}-a{{}_{n-1}}}-\frac {a{{}_{n-1}}}{a{{}_{n}}-a{{}_{n-1}}}=1=\frac {d}{1-d}$ ，
30. $\therefore d=\frac {1}{2}$ ．
31. 综上所述， $a{{}_{2}}$ ， $a{{}_{3}}$ ， $\ldots $ ， $a{{}_{n}}\ldots $ 成等差数列的充要条件是 $d=\frac {1}{2}$

## 知识点

**中文**:
  - 充要条件
  - 数列的递推公式
  - 等差数列的判定与证明
  - 等比数列的判定与证明

**English**:
  - Necessary and Sufficient Condition
  - Recurrence Formula
  - Determination and Proof
  - Determination and Proof

---
