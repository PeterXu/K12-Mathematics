# Mathematics - 题目 1010

**ID**: a777b98d3f194f35a68f85935c88c5cd
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
设数列 $\left \{a{{}_{n}}\right \}$ 的前 $n$ 项和为 $S{{}_{n}}$ ， $2S{{}_{n}}=n{^{2}}+5n.​​​​​​​‌$(1)求 $\left \{a{{}_{n}}\right \}$ 的通项公式；(2)设 $b{{}_{n}}=n\cdot 2{^{n}}$ ，求数列 $\left \{\frac {S{{}_{n}}+4}{a{{}_{n}}b{{}_{n}}}\right \}$ 的前 $n$ 项和 $T{{}_{n}}$ ；(3)设 $c{{}_{n}}=\frac {1}{\sqrt {a{{}_{n}}-2}}$ ，求证： $c{{}_{1}}+c{{}_{2}}+c{{}_{3}}+\ldots +c{{}_{n}}>2\sqrt {n}-\frac {3}{2}.$

## 解答

1. （1）因为 $2S{{}_{n}}=n{^{2}}+5n$ ，即 $S{{}_{n}}=\frac {n{^{2}}+5n}{2}$ ，
2. 当 $n=1$ 时， $S{{}_{1}}=\frac {1{^{2}}+5}{2}$ ，所以 $a{{}_{1}}=S{{}_{1}}=3$ ；
3. 当 $n\mathrm{\geqslant }2$ 时， $S{{}_{n-1}}=\frac {{\left({n-1}\right)^{2}}+5\left ({n-1}\right )}{2}$ ，
4. 所以 $a{{}_{n}}=S{{}_{n}}-S{{}_{n-1}}=\frac {n{^{2}}+5n}{2}-\frac {(n-1){^{2}}+5\left ({n-1}\right )}{2}=n+2$ ，
5. 而 $a{{}_{1}}=3$ 也满足上式，
6. $\therefore a{{}_{n}}=n+2$ ；
7. （2）因为 $S{{}_{n}}=\frac {n{^{2}}+5n}{2}$ ， $a{{}_{n}}=n+2$ ， $b{{}_{n}}=n\cdot 2{^{n}}$ ，
8. $\therefore \frac {S{{}_{n}}+4}{a{{}_{n}}b{{}_{n}}}=\frac {\frac {n{^{2}}+5n}{2}+4}{\left ({n+2}\right )\times n\times 2{^{n}}}=\frac {n{^{2}}+5n+8}{\left ({n+2}\right )n\times 2{^{n+1}}}$
9. $=\frac {\left ({n+2}\right )n+3n+8}{\left ({n+2}\right )n\times 2{^{n+1}}}=\frac {1}{2{^{n+1}}}+\frac {3n+8}{\left ({n+2}\right )n\times 2{^{n+1}}}$
10. $=\frac {1}{2{^{n+1}}}+\frac {4\left ({n+2}\right )-n}{\left ({n+2}\right )\times n\times 2{^{n+1}}}$
11. $=\frac {1}{2{^{n+1}}}+\frac {1}{n\times 2{^{n-1}}}-\frac {1}{\left ({n+2}\right )\times 2{^{n+1}}}$ ，
12. $\therefore T{{}_{n}}=\frac {\frac {1}{4}\left [1-{\left({\frac {1}{2}}\right)^{n}}\right ]}{1-\frac {1}{2}}+\frac {1}{1\times 2{^{0}}}-\frac {1}{3\times 2{^{2}}}+\frac {1}{2\times 2{^{1}}}-\frac {1}{4\times 2{^{3}}}+\frac {1}{3\times 2{^{2}}}-\frac {1}{5\times 2{^{4}}}+\cdots +\frac {1}{n\times 2{^{n-1}}}-\frac {1}{\left ({n+2}\right )\times 2{^{n+1}}}$
13. $=\frac {1}{2}-{\left({\frac {1}{2}}\right)^{n+1}}+1+\frac {1}{4}-\frac {1}{\left ({n+1}\right )\cdot 2{^{n}}}-\frac {1}{\left ({n+2}\right )\cdot 2{^{n+1}}}=\frac {7}{4}-\frac {1}{2{^{n+1}}}-\frac {1}{\left ({n+1}\right )\cdot 2{^{n}}}-\frac {1}{\left ({n+2}\right )\cdot 2{^{n+1}}}$ ；
14. （3）由（1）可得 $c{{}_{n}}=\frac {1}{\sqrt {a{{}_{n}}-2}}=\frac {1}{\sqrt {n}}$ ，
15. 因为 $\frac {1}{\sqrt {k}}+\frac {1}{\sqrt {k+1}}-\frac {4}{\sqrt {k}+\sqrt {k+1}}$
16. $=\frac {\sqrt {k+1}\left ({\sqrt {k}+\sqrt {k+1}}\right )+\sqrt {k}\left ({\sqrt {k}+\sqrt {k+1}}\right )-4\sqrt {k}\sqrt {k+1}}{\sqrt {k}\sqrt {k+1}\left ({\sqrt {k}+\sqrt {k+1}}\right )}$
17. $=\frac {{\left({\sqrt {k+1}}\right)^{2}}+{\left({\sqrt {k}}\right)^{2}}-2\sqrt {k}\sqrt {k+1}}{\sqrt {k}\sqrt {k+1}\left ({\sqrt {k}+\sqrt {k+1}}\right )}>\frac {2\sqrt {k}\sqrt {k+1}-2\sqrt {k}\sqrt {k+1}}{\sqrt {k}\sqrt {k+1}\left ({\sqrt {k}+\sqrt {k+1}}\right )}=0$ （ $k\in \mathbf{N}{\rm{*}}$ ），
18. 所以 $\frac {1}{\sqrt {k}}+\frac {1}{\sqrt {k+1}}>\frac {4}{\sqrt {k}+\sqrt {k+1}}$ （ $k\in \mathbf{N}{\rm{*}}$ ）
19. 所以 $\frac {1}{2}\left ({\frac {1}{\sqrt {k}}+\frac {1}{\sqrt {k+1}}}\right )>\frac {2}{\sqrt {k}+\sqrt {k+1}}=2\left ({\sqrt {k+1}-\sqrt {k}}\right )$ （ $k\in \mathbf{N}{\rm{*}}$ ），
20. $\therefore c{{}_{1}}+c{{}_{2}}+\cdots +c{{}_{n}}=1+\frac {1}{\sqrt {2}}+\frac {1}{\sqrt {3}}+\cdots +\frac {1}{\sqrt {n}}$
21. $=\frac {1}{2}\left ({1+\frac {1}{\sqrt {2}}+\frac {1}{\sqrt {2}}+\frac {1}{\sqrt {3}}+\frac {1}{\sqrt {3}}+\cdots +\frac {1}{\sqrt {n-1}}+\frac {1}{\sqrt {n-1}}+\frac {1}{\sqrt {n}}}\right )+\frac {1}{2}+\frac {1}{2\sqrt {n}}$
22. $>2\left ({\sqrt {2}-1+\sqrt {3}-\sqrt {2}+\cdots +\sqrt {n}-\sqrt {n-1}}\right )+\frac {1}{2}+\frac {1}{2\sqrt {n}}$
23. $=2\left ({\sqrt {n}-1}\right )+\frac {1}{2}+\frac {1}{2\sqrt {n}}=2\sqrt {n}-\frac {3}{2}+\frac {1}{2\sqrt {n}}>2\sqrt {n}-\frac {3}{2}.$

## 知识点

**中文**:
  - 利用前n项和与通项关系求通项公式
  - 数列求和方法之裂项相消法
  - 数列与不等式的综合

**English**:
  - Using Sum-Term Relation
  - Telescoping Series Method
  - Sequences with Inequalities

---
