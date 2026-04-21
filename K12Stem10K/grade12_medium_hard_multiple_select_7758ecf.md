# Mathematics - 题目 1747

**ID**: 7758ecfc84334793b66c0d011b6bc724
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Multiple-select

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ 满足 $a{{}_{1}}=0$ ， $e{{}^{a{{}_{n+1}}+a{{}_{n}}}}=e{{}^{a{{}_{n}}}}+1\left ({n\in \mathbf{N}{{}^{∗}}}\right )$ ，前n项和为 $S{{}_{n}}$ ，则下列选项中正确的是（      ）（参考数据： ${\ln}2\approx 0.​​​​​​​‌693$ ， ${\ln}3\approx 1.099$ ）

## 解答

1. 解：对于A：由 $e{{}^{a{{}_{n+1}}+a{{}_{n}}}}=e{{}^{a{{}_{n}}}}+1\left ({n\in \mathbf{N}{{}^{∗}}}\right )$ 得 $e{{}^{a{{}_{n+1}}}}=\frac {1}{e{{}^{a{{}_{n}}}}}+1\left ({n\in \mathbf{N}{{}^{∗}}}\right )$ ，令 $b{{}_{n}}=e{{}^{a{{}_{n}}}}$ ， 即 $a{{}_{n}}={\ln}b{{}_{n}}$ ，则 $b{{}_{n{\rm{+}}1}}=1{\rm{+}}\frac {1}{b{{}_{n}}}$ ，
2. 又 $a{{}_{1}}=0$ ，所以 $b{{}_{1}}=1$ ，则 $y=1{\rm{+}}\frac {1}{x}$ 在 $\left ({0\mathrm{，}+\infty }\right )$ 上单调递减，所以 $b{{}_{n}}\in \left [1，2\right ]，b{{}_{n{\rm{+}}1}}b{{}_{n}}=1{\rm{+}}\frac {1}{b{{}_{n}}}\in \left [2，3\right ]$ ，
3. 所以 ${\ln}2\leqslant a{{}_{n}}+a{{}_{n+1}}={\ln}b{{}_{n}}{\rm{+}}{\ln}b{{}_{n{\rm{+}}1}}={\ln}b{{}_{n}}b{{}_{n{\rm{+}}1}}\leqslant {\ln}3$ ，故A正确；
4. 对于B：因为 $a{{}_{n}}+a{{}_{n+1}}\geqslant {\ln}2$ ， $S{{}_{2020}}=\left ({a{{}_{1}}+a{{}_{2}}}\right ){\rm{+}}\left ({a{{}_{3}}+a{{}_{4}}}\right ){\rm{+}}\cdots {\rm{+}}\left ({a{{}_{2019}}+a{{}_{2020}}}\right )\geqslant 1010{\ln}2{\rm{>}}693>666$ ，故B不正确；
5. 对于C：因为 $a{{}_{n}}={\ln}b{{}_{n}}$ ，所以 $0\leqslant a{{}_{n}}\leqslant {\ln}2$ ， ${\ln}2\leqslant a{{}_{n}}+a{{}_{n+1}}\leqslant {\ln}3$ ，所以 ${\ln}3\leqslant a{{}_{n}}+{\ln}2$ ，即 ${\ln}\frac {3}{2}\leqslant a{{}_{n}}$ ，所以 ${\ln}\frac {3}{2}\leqslant a{{}_{n}}\leqslant {\ln}2\left ({n\geqslant 2}\right )$ ，故C正确；
6. 对于D：因为 $b{{}_{n{\rm{+}}1}}=1{\rm{+}}\frac {1}{b{{}_{n}}}$ ， $b{{}_{n}}\in \left [1，2\right ]$ ，令 $b{{}_{n{\rm{+}}1}}-\frac {1{\rm{+}}\sqrt {5}}{2}=\frac {1-\sqrt {5}}{2b{{}_{n}}}\left ({b{{}_{n}}-\frac {1{\rm{+}}\sqrt {5}}{2}}\right )$ ，所以 $b{{}_{n{\rm{+}}1}}-\frac {1{\rm{+}}\sqrt {5}}{2}$ 与 $b{{}_{n}}-\frac {1{\rm{+}}\sqrt {5}}{2}$ 异号， $b{{}_{n{\rm{+}}{\rm{2}}}}-\frac {1{\rm{+}}\sqrt {5}}{2}$ 与 $b{{}_{n}}-\frac {1{\rm{+}}\sqrt {5}}{2}$ 同号，
7. 又 $b{{}_{1}}-\frac {1{\rm{+}}\sqrt {5}}{2}<0$ ，所以 $b{{}_{2n-1}}-\frac {1{\rm{+}}\sqrt {5}}{2}<0$ ， $b{{}_{2n}}-\frac {1{\rm{+}}\sqrt {5}}{2}{\rm{>}}0$ ，即 $b{{}_{2n-1}}<\frac {1{\rm{+}}\sqrt {5}}{2}$ ， $b{{}_{2n}}{\rm{>}}\frac {1{\rm{+}}\sqrt {5}}{2}$ ，
8. 又 $b{{}_{n{\rm{+}}{\rm{2}}}}=1{\rm{+}}\frac {1}{b{{}_{n{\rm{+}}1}}}=1{\rm{+}}\frac {1}{1{\rm{+}}\frac {1}{b{{}_{n}}}}=\frac {2b{{}_{n}}{\rm{+}}1}{1{\rm{+}}b{{}_{n}}}$ ，所以 $b{{}_{n{\rm{+}}{\rm{2}}}}-b{{}_{n}}=\frac {2b{{}_{n}}{\rm{+}}1}{1{\rm{+}}b{{}_{n}}}-b{{}_{n}}=\frac {-b{{}_{n}}{{}^{2}}{\rm{+}}b{{}_{n}}{\rm{+}}1}{1{\rm{+}}b{{}_{n}}}=\frac {-\left ({b{{}_{n}}-\frac {1-\sqrt {5}}{2}}\right )\left ({b{{}_{n}}-\frac {1{\rm{+}}\sqrt {5}}{2}}\right )}{1{\rm{+}}b{{}_{n}}}$ ，
9. 所以 $b{{}_{2n{\rm{+}}{\rm{2}}}}-b{{}_{2n}}=\frac {-\left ({b{{}_{2n}}-\frac {1-\sqrt {5}}{2}}\right )\left ({b{{}_{2n}}-\frac {1{\rm{+}}\sqrt {5}}{2}}\right )}{1{\rm{+}}b{{}_{2n}}}<0$ ， $b{{}_{2n{\rm{+}}{\rm{1}}}}-b{{}_{2n-1}}=\frac {-\left ({b{{}_{2n-1}}-\frac {1-\sqrt {5}}{2}}\right )\left ({b{{}_{2n-1}}-\frac {1{\rm{+}}\sqrt {5}}{2}}\right )}{1{\rm{+}}b{{}_{2n-1}}}{\rm{>}}0$ ，
10. 所以 $\left \{b{{}_{2n-1}}\right \}$ 是单调递增数列， $\left \{b{{}_{2n}}\right \}$ 是单调递减数列，
11. 所以 $\left \{a{{}_{2n-1}}\right \}$ 是单调递增数列， $\left \{a{{}_{2n}}\right \}$ 是单调递减数列，故D正确，
12. 故选：ACD.

## 知识点

**中文**:
  - 单调性
  - 数列的递推公式
  - 数列的通项
  - 数列的前n项和

**English**:
  - Monotonicity
  - Recurrence Formula
  - General Term
  - Sum of the First n Terms

---
