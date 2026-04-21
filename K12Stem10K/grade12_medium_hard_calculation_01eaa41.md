# Mathematics - 题目 1774

**ID**: 01eaa41e2f934319a51b74533c3a0a87
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ 为等比数列， $\left \{b{{}_{n}}\right \}$ 为等差数列，且 $a{{}_{1}}=b{{}_{1}}=2$ ， $a{{}_{8}}=8a{{}_{5}}$ ， $a{{}_{4}}=b{{}_{8}}$ .​​​​​​​‌(1)求 $\left \{a{{}_{n}}\right \}$ ， $\left \{b{{}_{n}}\right \}$ 的通项公式；(2)数列 $\left \{\left ({-1}\right ){^{\frac {1}{2}\left [\sqrt {2}{\rm{s}}{\rm{i}}{\rm{n}}\left ({\frac {n\mathrm{π}}{2}-\frac {\mathrm{π}}{4}}\right )+1\right ]}}\cdot b{{}_{n}^{2}}\right \}$ 的前 $n$ 项和为 $S{{}_{n}}$ ，集合 $A=\left \{n\left |{\,\frac {S{{}_{4n}}\cdot b{{}_{n+2}}}{n\cdot a{{}_{n+2}}}\geqslant t}\right .，n\in \mathbf{N}{^{{\rm{*}}}}\right \}$ 共有5个元素，求实数 $t$ 的取值范围；(3)若数列 $\left \{c{{}_{n}}\right \}$ 中， $c{{}_{1}}=1$ ， $c{{}_{n}}=\frac {{\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}a{{}_{n}}}{\frac {1}{4}b{{}_{n}}{^{2}}-1}\left ({n\geqslant 2}\right )$ ，求证： $c{{}_{1}}+c{{}_{1}}\cdot c{{}_{2}}+c{{}_{1}}\cdot c{{}_{2}}\cdot c{{}_{3}}+\cdots +c{{}_{1}}\cdot c{{}_{2}}\cdot c{{}_{3}}\cdots \cdots c{{}_{n}}<2$ .

## 解答

1. （1）设数列 $\left \{a{{}_{n}}\right \}$ 的公比为 $q$ ，数列 $\left \{b{{}_{n}}\right \}$ 的公差为 $d$ ，
2. 则由 $a{{}_{8}}=8a{{}_{5}}$ ， $q{^{3}}=8$ ，所以 $q=2$ ，所以 $a{{}_{n}}=a{{}_{1}}q{^{n-1}}=2{^{n}}$ ，
3. 所以 $a{{}_{4}}=16$ ，即 $b{{}_{8}}=2+7d=16$ ，所以 $d=2$ ，
4. 所以 $b{{}_{n}}=b{{}_{1}}+(n-1)d=2+(n-1)\times 2=2n$ ；
5. （2）设数列 $d{{}_{n}}=\left ({-1}\right ){^{\frac {1}{2}\left [\sqrt {2}{\rm{s}}{\rm{i}}{\rm{n}}\left ({\frac {n\mathrm{π}}{2}-\frac {\mathrm{π}}{4}}\right )+1\right ]}}\cdot b{{}_{n}^{2}}$ ，
6. 则 $d{{}_{4n}}+d{{}_{4n-1}}+d{{}_{4n-2}}+d{{}_{4n-3}}=b{{}_{4n}^{2}}+b{{}_{4n-1}^{2}}-b{{}_{4n-2}^{2}}-b{{}_{4n-3}^{2}}=128n-48$ ，
7. 所以 $S{{}_{4n}}=(d{{}_{1}}+d{{}_{2}}+d{{}_{3}}+d{{}_{4}})+\cdots +(d{{}_{4n-3}}+d{{}_{4n-2}}+d{{}_{3n-1}}+d{{}_{4n}})=\frac {n(128n-48+80)}{2}$
8. $=n(64n+16)$ ，
9. $\frac {S{{}_{4n}}\cdot b{{}_{n+2}}}{na{{}_{n+2}}}=\frac {(64n+16)\cdot 2(n+2)}{2{^{n+2}}}=\frac {(32n+8)(n+2)}{2{^{n}}}$ ，
10. 令 $f(n)=\frac {(32n+8)(n+2)}{2{^{n}}}$ ， $f(n+1)-f(n)=\frac {(32n+40)(n+3)}{2{^{n+1}}}-\frac {(32n+8)(n+2)}{2{^{n}}}$
11. $=\frac {-32n{^{2}}-8n-88}{2{^{n+1}}}=\frac {4\left ({-4n{^{2}}-n+11}\right )}{2{^{n}}}$ ，
12. 可得 $f(1)<f(2)>f(3)>f(4)>\cdots >f(n)$ ，
13. 故当 $n\mathrm{=}2$ 时， $f(n)$ 最大，
14. 且 $f(1)=60，f(5)=\frac {147}{4}，f(6)=25$ ，
15. 所以 $25<t\leqslant \frac {147}{4}$ ，即 $t$ 的取值范围为 $(25,\frac {147}{4}]$ ；
16. （3）证明：由 $c{{}_{1}}=1,$  $c{{}_{n}}=\frac {{\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}a{{}_{n}}}{\frac {1}{4}b{{}_{n}^{2}}-1}=\frac {n}{n{^{2}}-1}=\frac {n}{(n+1)(n-1)}(n\geqslant 2)$ ，
17. 则当 $n\mathrm{\geqslant }2$ 时， $c{{}_{1}}\cdot c{{}_{2}}\cdot c{{}_{3}}\cdot \cdots \cdot c{{}_{n}}=1\times \frac {2}{1\times 3}\times \frac {3}{2\times 4}\times \cdots \times \frac {n}{\left ({n-1}\right )\left ({n+1}\right )}=\frac {n}{3\times 4\times 5\times \cdots \times n\times \left ({n+1}\right )}$
18. $=\frac {2n}{(n+1)!}=2[\frac {n+1-1}{(n+1)!}]=2[\frac {1}{n!}-\frac {1}{(n+1)!}]$ ，
19. 当 $n=1$ 时， $c{{}_{1}}=1$ 也满足上式，
20. 所以 $c{{}_{1}}\cdot c{{}_{2}}\cdot c{{}_{3}}\cdot \cdots \cdot c{{}_{n}}=2[\frac {1}{n!}-\frac {1}{(n+1)!}](n\in \mathbf{N}{^{*}})$ ，
21. $c{{}_{1}}+c{{}_{1}}\cdot c{{}_{2}}+c{{}_{1}}\cdot c{{}_{2}}\cdot c{{}_{3}}+\cdots +c{{}_{1}}\cdot c{{}_{2}}\cdot c{{}_{3}}\cdot \cdots \cdot c{{}_{n}}=2[1-\frac {1}{2!}+\frac {1}{2!}-\frac {1}{3!}+\cdots +\frac {1}{n!}-\frac {1}{(n+1)!}]=2-\frac {1}{(n+1)!}<2$ ，
22. 所以原不等式成立.

## 知识点

**中文**:
  - 数列与不等式的综合
  - 等差数列的概念及通项公式
  - 等比数列的概念与通项公式
  - 数列求和方法之分组转化法

**English**:
  - Sequences with Inequalities
  - Concept and Formula
  - Concept and Formula
  - Grouping Method

---
