# Mathematics - 题目 3376

**ID**: e5a4e3ac25a94fd7a1606b70eff8d2d5
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设等差数列 $\{a{{}_{n}}\}$ 的前 $n$ 项和为 $S{{}_{n}}$ ， $a{{}_{3}}=4$ ， $a{{}_{4}}=S{{}_{3}}$ ，数列 $\{b{{}_{n}}\}$ 满足：对每 $n\in \mathbf{N}{^{∗}},S{{}_{n}}+b{{}_{n}},S{{}_{n+1}}+b{{}_{n}},S{{}_{n+2}}+b{{}_{n}}$ 成等比数列.​​​​​​​‌（1）求数列 $\{a{{}_{n}}\},\{b{{}_{n}}\}$ 的通项公式；（2）记 $C{{}_{n}}=\sqrt {\frac {a{{}_{n}}}{2b{{}_{n}}}},n\in \mathbf{N}{^{∗}},$  证明： $C{{}_{1}}+C{{}_{2}}{\rm{+}}\cdots +C{{}_{n}}<2\sqrt {n},n\in \mathbf{N}{^{∗}}.$

## 解答

1. (1)设数列 $\{a{{}_{n}}\}$ 的公差为d，由题意得
2. $a{{}_{1}}+2d=4,a{{}_{1}}+3d=3a{{}_{1}}+3d$ ，
3. 解得 $a{{}_{1}}=0,d=2$ ．
4. 从而 $a{{}_{n}}=2n-2,n\in {\mathbf{N}}{^{*}}$ ．
5. 所以 $S{{}_{n}}=n{^{2}}-n，n\in {\mathbf{N}}{^{*}}$ .  ………………………………….……………….………（3分）
6. 由 $S{{}_{n}}+b{{}_{n}},S{{}_{n+1}}+b{{}_{n}},S{{}_{n+2}}+b{{}_{n}}$ 成等比数列得
7. ${\left({S{{}_{n+1}}+b{{}_{n}}}\right)^{2}}=\left ({S{{}_{n}}+b{{}_{n}}}\right )\left ({S{{}_{n+2}}+b{{}_{n}}}\right )$ ．
8. 解得 $b{{}_{n}}=\frac {1}{d}\left ({S{{}_{n+1}^{2}}-S{{}_{n}}S{{}_{n+2}}}\right )$ ．
9. 所以 $b{{}_{n}}=n{^{2}}+n,n\in {\mathbf{N}}{^{*}}$ ． ……………………..………………….….……….……（7分）
10. （2）
11. 方法一（通解通法）：数学归纳法和放缩法
12. $c{{}_{n}}=\sqrt {\frac {a{{}_{n}}}{2b{{}_{n}}}}=\sqrt {\frac {2n-2}{2n(n+1)}}=\sqrt {\frac {n-1}{n(n+1)}},n\in {\mathbf{N}}{^{*}}$ ．
13. 我们用数学归纳法证明．
14. （i）当n=1时，c_{1}=0<2，不等式成立；
15. （ii）假设 $n=k\left ({k\in {\mathbf{N}}{^{*}}}\right )$ 时不等式成立，即 $c{{}_{1}}+c{{}_{2}}+\cdots +c{{}_{k}}<2\sqrt {k}$ ． …………（10分）
16. 那么，当 $n=k+1$ 时，
17. $c{{}_{1}}+c{{}_{2}}+\cdots +c{{}_{k}}+c{{}_{k+1}}<2\sqrt {k}+\sqrt {\frac {k}{(k+1)(k+2)}}<2\sqrt {k}+\sqrt {\frac {1}{k+1}}$  $<2\sqrt {k}+\frac {2}{\sqrt {k+1}+\sqrt {k}}=2\sqrt {k}+2(\sqrt {k+1}-\sqrt {k})=2\sqrt {k+1}$ ．
18. 即当 $n=k+1$ 时不等式也成立．
19. 根据（i）和（ii），不等式 $c{{}_{1}}+c{{}_{2}}+\cdots +c{{}_{n}}<2\sqrt {n}$ 对任意 $n\in {\mathbf{N}}{^{*}}$ 成立．…….…（15分）
20. 方法二（拓展性方法）：放缩法
21. 结合(1)中的通项公式可得：
22. $C{{}_{n}}=\sqrt {\frac {a{{}_{n}}}{2b{{}_{n}}}}=\sqrt {\frac {n-1}{n\left ({n+1}\right )}}<\sqrt {\frac {1}{n}}=\frac {2}{\sqrt {n}+\sqrt {n}}<\frac {2}{\sqrt {n}+\sqrt {n-1}}=2\left ({\sqrt {n}-\sqrt {n-1}}\right )$ ，……（10分）
23. 则 $C{{}_{1}}+C{{}_{2}}+\cdots +C{{}_{n}}<2\left ({\sqrt {1}-0}\right )+2\left ({\sqrt {2}-\sqrt {1}}\right )+\cdots +2\left ({\sqrt {n}-\sqrt {n-1}}\right )=2\sqrt {n}$ . .………（15分）

## 知识点

**中文**:
  - 数学归纳法
  - 等差数列的概念及通项公式
  - 等比中项

**English**:
  - Mathematical Induction
  - Concept and Formula
  - Geometric Mean (Middle Term)

---
