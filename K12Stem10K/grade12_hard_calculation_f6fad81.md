# Mathematics - 题目 1916

**ID**: f6fad8127b7d465fb6256aa9e192e05e
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知 $S{{}_{n}}$ 是数列 $\left \{a{{}_{n}}\right \}$ 的前 $n$ 项和，对任意 $n\in {\mathbf{N}^{*}}$ ，都有 $\left ({1-m}\right )S{{}_{n}}=-ma{{}_{n}}+4{^{n}}\\left ({m>0}\right )$ ；（1）若 $m=4$ ，求证：数列 $\left \{\frac {a{{}_{n}}}{4{^{n-1}}}\right \}$ 是等差数列，并求此时数列 $\left \{a{{}_{n}}\right \}$ 的通项公式；（2）若 $m\ne 4$ ，求证：数列 $\left \{a{{}_{n}}+\frac {3}{m-4}\cdot 4{^{n}}\right \}$ 是等比数列，并求此时数列 $\left \{a{{}_{n}}\right \}$ 的通项公式；（3）设 $b{{}_{n}}=\frac {a{{}_{n}}}{4{^{n}}}\\left ({n\in {\mathbf{N}^{*}}}\right )$ ，若 $\left |{b{{}_{n}}}\right |\leqslant 2$ ，求实数 $m$ 的取值范围.​​​​​​​‌

## 解答

1. （1）将 $m=4$ 代入 $\left ({1-m}\right )S{{}_{n}}=-ma{{}_{n}}+4{^{n}}$ ，得 $-3S{{}_{n}}=-4a{{}_{n}}+4{^{n}}$ ，即 $3S{{}_{n}}=4a{{}_{n}}-4{^{n}}$ .
2. 当 $n=1$ 时，则有 $3a{{}_{1}}=4a{{}_{1}}-4$ ，得 $a{{}_{1}}=4$ ；
3. 当 $n\geqslant 2$ 时， 由 $3S{{}_{n}}=4a{{}_{n}}-4{^{n}}$ 得出 $3S{{}_{n-1}}=4a{{}_{n-1}}-4{^{n-1}}$ ，
4. 上述两式相减得 $3a{{}_{n}}=4a{{}_{n}}-4a{{}_{n-1}}-4{^{n}}-4{^{n-1}}=4a{{}_{n}}-4a{{}_{n-1}}-4{^{n-1}}\left ({4-1}\right )$ ，
5. 整理得 $a{{}_{n}}=4a{{}_{n-1}}+3\cdot 4{^{n-1}}$ ，等式两边同时除以 $4{^{n-1}}$ 得 $\frac {a{{}_{n}}}{4{^{n-1}}}=\frac {a{{}_{n-1}}}{4{^{n-2}}}+3$ ，即 $\frac {a{{}_{n}}}{4{^{n-1}}}-\frac {a{{}_{n-1}}}{4{^{n-2}}}=3$ ，
6. 所以，数列 $\left \{\frac {a{{}_{n}}}{4{^{n-1}}}\right \}$ 是以首项为 $\frac {a{{}_{1}}}{4{^{0}}}=4$ 为首项，以 $3$ 为公差的等差数列，
7. 则 $\frac {a{{}_{n}}}{4{^{n-1}}}=4+3\left ({n-1}\right )=3n+1$ ，因此， $a{{}_{n}}=\left ({3n+1}\right )\cdot 4{^{n-1}}$ ；
8. （2）对任意 $n\in {\mathbf{N}^{*}}$ ，都有 $\left ({1-m}\right )S{{}_{n}}=-ma{{}_{n}}+4{^{n}}\\left ({m>0}\right )$ .
9. 当 $n=1$ 时， $\left ({1-m}\right )S{{}_{1}}=-ma{{}_{1}}+4$ ，解得 $a{{}_{1}}=4$ ；
10. 当 $n\geqslant 2$ 时，由 $\left ({1-m}\right )S{{}_{n}}=-ma{{}_{n}}+4{^{n}}$ 得出 $\left ({1-m}\right )S{{}_{n-1}}=-ma{{}_{n-1}}+4{^{n-1}}$ ，
11. 两式相减得 $\left ({1-m}\right )a{{}_{n}}=-ma{{}_{n}}+ma{{}_{n-1}}+4{^{n}}-4{^{n-1}}=-ma{{}_{n}}+ma{{}_{n-1}}+3\cdot 4{^{n-1}}$ ，
12. 化简得 $a{{}_{n}}=ma{{}_{n-1}}+3\cdot 4{^{n-1}}$ ，
13. $\because \frac {a{{}_{n}}+\frac {3}{m-4}\cdot 4{^{n}}}{a{{}_{n-1}}+\frac {3}{m-4}\cdot 4{^{n-1}}}=\frac {ma{{}_{n-1}}+3\cdot 4{^{n-1}}+\frac {3}{m-4}\cdot 4{^{n}}}{a{{}_{n-1}}+\frac {3}{m-4}\cdot 4{^{n-1}}}=\frac {ma{{}_{n-1}}+\frac {3}{4}\cdot 4{^{n}}+\frac {3}{m-4}\cdot 4{^{n}}}{a{{}_{n-1}}+\frac {3}{m-4}\cdot 4{^{n-1}}}$  $=\frac {ma{{}_{n-1}}+\left ({\frac {3}{4}+\frac {3}{m-4}}\right )\cdot 4{^{n}}}{a{{}_{n-1}}+\frac {3}{m-4}\cdot 4{^{n-1}}}=\frac {ma{{}_{n-1}}+\frac {3m}{m-4}\cdot 4{^{n-1}}}{a{{}_{n-1}}+\frac {3}{m-4}\cdot 4{^{n-1}}}=\frac {m\left ({a{{}_{n-1}}+\frac {3}{m-4}\cdot 4{^{n-1}}}\right )}{a{{}_{n-1}}+\frac {3}{m-4}\cdot 4{^{n-1}}}=m$ ，
14. 所以，数列 $\left \{a{{}_{n}}+\frac {3}{m-4}\cdot 4{^{n}}\right \}$ 是以 $m$ 为公比，以 $a{{}_{1}}+\frac {3}{m-4}\times 4=4+\frac {12}{m-4}=\frac {4\left ({m-1}\right )}{m-4}$ 为首项的等比数列，则 $a{{}_{n}}+\frac {3}{m-4}\cdot 4{^{n}}=\frac {4\left ({m-1}\right )}{m-4}\cdot m{^{n-1}}$ ，因此， $a{{}_{n}}=\frac {4\left ({m-1}\right )\cdot m{^{n-1}}-3\cdot 4{^{n}}}{m-4}$ ；
15. （3） $\because b{{}_{n}}=\frac {a{{}_{n}}}{4{^{n}}}\\left ({n\in {\mathbf{N}^{*}}}\right )$ ，且 $\left |{b{{}_{n}}}\right |\leqslant 2$ .
16. 当 $m=4$ 时， $b{{}_{n}}=\frac {3n+1}{4}$ ，当 $n\geqslant 3$ 时， $b{{}_{n}}>2$ ，不满足条件；
17. 则 $m\ne 4$ ，可得 $b{{}_{n}}=\frac {1}{m}\cdot \frac {4\left ({m-1}\right )}{m-4}\cdot {\left({\frac {m}{4}}\right)^{n}}-\frac {3}{m-4}$ ，
18. 可得 $-2+\frac {3}{m-4}\leqslant \frac {1}{m}\cdot \frac {4\left ({m-1}\right )}{m-4}\cdot {\left({\frac {m}{4}}\right)^{n}}\leqslant 2+\frac {3}{m-4}$ ，
19. 显然 $m>4$ 时，数列 $\left \{\frac {1}{m}\cdot \frac {4\left ({m-1}\right )}{m-4}\cdot {\left({\frac {m}{4}}\right)^{n}}\right \}$ 单调递增，不满足条件， $\therefore 0<m<4$ .
20. 当 $m=1$ 时，则有 $-3<0<1$ 显然成立；
21. 当 $0<m<1$ 时，若 $n=1$ ，则数列 $\left \{\frac {1}{m}\cdot \frac {4\left ({m-1}\right )}{m-4}\cdot {\left({\frac {m}{4}}\right)^{n}}\right \}$ 的最大项为 $\frac {m-1}{m-4}$ ，
22. $\therefore 2+\frac {3}{m-4}>\frac {m-1}{m-4}$ ，即 $2m-5<m-1$ 恒成立；
23. 当 $1<m\leqslant \frac {5}{2}$ 时，数列 $\left \{\frac {1}{m}\cdot \frac {4\left ({m-1}\right )}{m-4}\cdot {\left({\frac {m}{4}}\right)^{n}}\right \}$ 的最大项为 $\frac {m-1}{m-4}<0$ ，
24. 则 $2+\frac {3}{m-4}\geqslant 0$ 满足条件；
25. 当 $\frac {5}{2}<m<4$ 时， $2+\frac {3}{m-4}<0$ ，数列 $\left \{\frac {1}{m}\cdot \frac {4\left ({m-1}\right )}{m-4}\cdot {\left({\frac {m}{4}}\right)^{n}}\right \}$ 的最大项为 $\frac {m-1}{m-4}>0$ ，不满足条件；
26. 综上所述，实数 $m$ 的取值范围是 $\left ({0,\frac {5}{2}}\right ]$ .

## 知识点

**中文**:
  - 数列与不等式的综合
  - 等差数列的概念及通项公式
  - 等差数列的判定与证明
  - 等比数列的概念与通项公式
  - 等比数列的判定与证明

**English**:
  - Sequences with Inequalities
  - Concept and Formula
  - Determination and Proof
  - Concept and Formula
  - Determination and Proof

---
