# Mathematics - 题目 2637

**ID**: 1d489f5c78cf49f1aa816390bae4ff77
**年级**: Grade 11
**难度**: Medium
**题型**: Calculation

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ 的前 $n$ 项和为 $S{{}_{n}}$ ，且 $2S{{}_{n}}+a{{}_{n}}=2n$ .​​​​​​​‌(1)证明： $\left \{a{{}_{n}}-1\right \}$ 是等比数列；(2)求 $\left \{a{{}_{n}}\right \}$ 的通项公式；(3)已知 $b{{}_{n}}=\frac {1}{3{^{n}}a{{}_{n}}a{{}_{n+1}}}$ ，求数列 $\left \{b{{}_{n}}\right \}$ 的前 $n$ 项和 $T{{}_{n}}$ ，并证明： $\frac {9}{16}\leqslant T{{}_{n}}<\frac {3}{4}$ .

## 解答

1. （1）（1）因为 $2S{{}_{n}}+a{{}_{n}}=2n$ ，所以当 $n=1$ 时， $2S{{}_{1}}+a{{}_{1}}=2$ ，
2. 即 $2a{{}_{1}}+a{{}_{1}}=2$ ，所以 $a{{}_{1}}=\frac {2}{3}$ .
3. 当 $n\mathrm{\geqslant }2$ 时， $2S{{}_{n-1}}+a{{}_{n-1}}=2\left ({n-1}\right )$ ，
4. 两式相减，得 $2a{{}_{n}}+a{{}_{n}}-a{{}_{n-1}}=2$ ，即 $a{{}_{n}}=\frac {1}{3}a{{}_{n-1}}+\frac {2}{3}$ ，
5. 所以 $a{{}_{n}}-1=\frac {1}{3}\left ({a{{}_{n-1}}-1}\right )\left ({n\geqslant 2}\right )$ ，
6. 又 $a{{}_{1}}-1=-\frac {1}{3}\ne 0$ ，
7. 所以 $\left \{a{{}_{n}}-1\right \}$ 是以 $-\frac {1}{3}$ 为首项，以 $\frac {1}{3}$ 为公比的等比数列
8. （2）解：由（1）知， $a{{}_{n}}-1=\left ({-\frac {1}{3}}\right )\times {\left({\frac {1}{3}}\right)^{n-1}}=-\frac {1}{3{^{n}}}$ ，
9. 所以 $a{{}_{n}}=1-\frac {1}{3{^{n}}}$ .
10. （3）解：由（2），得 $b{{}_{n}}=\frac {1}{3{^{n}}a{{}_{n}}a{{}_{n+1}}}=\frac {1}{3{^{n}}\left ({1-\frac {1}{3{^{n}}}}\right )\left ({1-\frac {1}{3{^{n+1}}}}\right )}=\frac {3{^{n+1}}}{\left ({3{^{n}}-1}\right )\left ({3{^{n+1}}-1}\right )}=\frac {3}{2}\left ({\frac {1}{3{^{n}}-1}-\frac {1}{3{^{n+1}}-1}}\right )$ ，
11. 所以 $T{{}_{n}}=\frac {3}{2}\left ({\frac {1}{3{^{1}}-1}-\frac {1}{3{^{2}}-1}}\right )+\frac {3}{2}\left ({\frac {1}{3{^{2}}-1}-\frac {1}{3{^{3}}-1}}\right )+\frac {3}{2}\left ({\frac {1}{3{^{3}}-1}-\frac {1}{3{^{4}}-1}}\right )+\cdots +\frac {3}{2}\left ({\frac {1}{3{^{n}}-1}-\frac {1}{3{^{n+1}}-1}}\right )$ ，
12. $=\frac {3}{2}\left ({\frac {1}{2}-\frac {1}{3{^{2}}-1}+\frac {1}{3{^{2}}-1}-\frac {1}{3{^{3}}-1}+\frac {1}{3{^{3}}-1}-\frac {1}{3{^{4}}-1}+\cdots +\frac {1}{3{^{n}}-1}-\frac {1}{3{^{n+1}}-1}}\right )$
13. $=\frac {3}{2}\left ({\frac {1}{2}-\frac {1}{3{^{n+1}}-1}}\right ),$
14. 因为 $\forall n\in {\mathbf{N}}{^{{\rm{*}}}},\frac {1}{3{^{n+1}}-1}>0$ ，所以 $T{{}_{n}}=\frac {3}{2}\left ({\frac {1}{2}-\frac {1}{3{^{n+1}}-1}}\right )<\frac {3}{4}$ ，
15. 又 $T{{}_{n+1}}-T{{}_{n}}=b{{}_{n+1}}=\frac {1}{3{^{n+1}}a{{}_{n+1}}a{{}_{n+2}}}>0$ ，
16. 所以 $\left \{T{{}_{n}}\right \}$ 是递增数列，
17. 所以 $T{{}_{n}}\geqslant T{{}_{1}}=b{{}_{1}}=\frac {1}{3\times \left ({1-\frac {1}{3{^{1}}}}\right )\left ({1-\frac {1}{3{^{2}}}}\right )}=\frac {9}{16}$ ，
18. 所以 $\frac {9}{16}\leqslant T{{}_{n}}<\frac {3}{4}$ .

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
