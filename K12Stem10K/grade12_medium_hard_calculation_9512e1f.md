# Mathematics - 题目 2495

**ID**: 9512e1f60d4b41f39152cb2455a4fa9d
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
我们在研究非整数时，有时需要用到与它最接近的整数，比如与4.​​​​​​​‌6最接近的整数是5，与7.4最接近的整数是7.已知 $n\in {\mathbf{N}^{*}}$ ，请回答以下问题：(1)若 $x{{}_{n}}$ 是与 $\frac {n}{3}$ 最接近的整数，求 $x{{}_{2024}}$ ；(2)若 $a{{}_{n}}$ 是与 $\frac {n}{9}$ 最接近的整数， $n\geqslant 5$ 时，数列 $\left \{\frac {1}{a{{}_{n}}}\right \}$ 的第5项到第 $n$ 项和为 $S{{}_{n}}$ ，求 $S{{}_{100}}$ ；(3)设 $b{{}_{n}}$ 是与 $\sqrt {\frac {n}{3}}$ 最接近的整数， $c{{}_{n}}$ 是与 $\sqrt {2n}$ 最接近的整数.记 $\left \{\frac {1}{b{{}_{n}}}\right \}$ 的前 $n$ 项和为 $T{{}_{n}}$ ， $\left \{\frac {1}{c{{}_{n}}}\right \}$ 的前 $n$ 项和为 $R{{}_{n}}$ ，请比较 $T{{}_{2024}}$ 与 $R{{}_{2024}}$ 的大小，并说明理由.

## 解答

1. （1）由题可知， $x{{}_{2024}}$ 为 $\frac {2024}{3}$ 最接近的整数为 $\frac {2025}{3}=675$ .
2. （2）由题易知， $a{{}_{1}}=a{{}_{2}}=\cdots =a{{}_{4}}=0$ ， $a{{}_{5}}=a{{}_{6}}=\cdots =a{{}_{13}}=1$ ， $a{{}_{14}}=a{{}_{15}}=\cdots =a{{}_{22}}=2$ ， $\cdots \cdots $ ， $a{{}_{86}}=a{{}_{87}}=\cdots =a{{}_{94}}=10$ ，  $a{{}_{95}}=a{{}_{96}}=\cdots =a{{}_{100}}=11$
3. 所以 $S{{}_{100}}=\frac {1}{a{{}_{5}}}+\frac {1}{a{{}_{6}}}+\cdots +\frac {1}{a{{}_{99}}}+\frac {1}{a{{}_{100}}}=1\times 9+\frac {1}{2}\times 9+\cdots +\frac {1}{10}\times 9+\frac {1}{11}\times 6=\frac {82871}{3080}$
4. （3）不妨令 $b{{}_{n}}=k$ ，则 $k-\frac {1}{2}<\sqrt {\frac {n}{3}}<k+\frac {1}{2}\Rightarrow 3k{^{2}}-3k+\frac {3}{4}<n<3k{^{2}}+3k+\frac {3}{4}$
5. 所以 $3k{^{2}}-3k+1\leqslant n\leqslant 3k{^{2}}+3k$
6. 故有 $6k$ 项，使得 $b{{}_{n}}=k$
7. 所以 $T{{}_{2024}}=\sum \limits_{k=1}^{25}\mathop{\left ({\frac {1}{k}\times 6k}\right )}+\frac {1}{26}\times 74=152+\frac {1}{13}$ ；
8. 同理，令 $c{{}_{n}}=m$ ，得 $m-\frac {1}{2}<\sqrt {2n}<m+\frac {1}{2}$
9. 得 $\frac {m\left ({m-1}\right )}{2}+1\leqslant n\leqslant \frac {m\left ({m+1}\right )}{2}$
10. 故有 $m$ 项， $c{{}_{n}}=m$
11. 所以 $R{{}_{2024}}=\sum \limits_{m=1}^{63}\mathop{\left ({\frac {1}{m}\times m}\right )}+\frac {1}{64}\times 8=63+\frac {1}{8}$
12. 所以 $T{{}_{2024}}>R{{}_{2024}}$

## 知识点

**中文**:
  - 数列的递推公式
  - 数列的通项

**English**:
  - Recurrence Formula
  - General Term

---
