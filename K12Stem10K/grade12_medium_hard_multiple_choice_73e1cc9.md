# Mathematics - 题目 2648

**ID**: 73e1cc92500949ff964231a122b6c69d
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Multiple-choice

## 题目
设 $x{{}_{n}}$ 是关于 $x$ 的方程 $x{^{2}}+{\log}{{}_{n+1}}x{^{n}}=n{^{2}}+3n$ 的正实数根.​​​​​​​‌记 $a{{}_{n}}=\left [\frac {x{{}_{n}}}{2}\right ]$ ，其中 $\left [x\right ]$ 表示不超过 $x$ 的最大整数，设数列 $\left \{a{{}_{n}}\right \}$ 的前 $n$ 项和为 $S{{}_{n}}$ ，则 $S{{}_{2025}}=$ （      ）

## 解答

1. 令 $f\left ({x}\right )=x{^{2}}+{\log}{{}_{n+1}}x{^{n}}-n{^{2}}-3n$ ，则函数 $f\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上为增函数，
2. 因为 $f\left ({n}\right )=n{^{2}}+{\log}{{}_{n+1}}n{^{n}}-n{^{2}}-3n=n{\log}{{}_{n+1}}n-3n<n-3n=-2n<0$ ，
3. $f\left ({n+1}\right )={\left({n+1}\right)^{2}}+{\log}{{}_{n+1}}{\left({n+1}\right)^{n}}-n{^{2}}-3n=1>0$ ，
4. 由零点存在定理可得 $n<x{{}_{n}}<n+1$ ，则 $\frac {n}{2}<\frac {x{{}_{n}}}{2}<\frac {n+1}{2}$ ，
5. 当 $n$ 为正奇数时，设 $n=2k+1\left ({k\in {\mathbf{N}}}\right )$ ，则 $k+\frac {1}{2}<\frac {x{{}_{n}}}{2}<k+1$ ，则 $a{{}_{n}}=\left [\frac {x{{}_{n}}}{2}\right ]=k$ ，
6. 当 $n$ 为正偶数时，设 $n=2k\left ({k\in {\mathbf{N}}{^{∗}}}\right )$ ，则 $k<\frac {x{{}_{n}}}{2}<k+\frac {1}{2}$ ，则 $a{{}_{n}}=\left [\frac {x{{}_{n}}}{2}\right ]=k$ ，
7. 所以， $S{{}_{2025}}=a{{}_{1}}+\left ({a{{}_{2}}+a{{}_{3}}}\right )+\left ({a{{}_{4}}+a{{}_{5}}}\right )+\cdots +\left ({a{{}_{2024}}+a{{}_{2025}}}\right )$
8. $=0+1\times 2+2\times 2+\cdots +1012\times 2=\frac {\left ({2+2\times 1012}\right )\times 1012}{2}=1012\times 1013$ .
9. 故选B.

## 知识点

**中文**:
  - 函数零点的存在性定理及应用
  - 等差数列求和公式基本应用

**English**:
  - Existence Theorem of Zero Points and Applications
  - Basic Applications of Sum Formula

---
