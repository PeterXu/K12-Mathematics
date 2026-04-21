# Mathematics - 题目 1929

**ID**: 590de7b526f74bafa5c36ccbff0ab7f0
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设数列 $\{a{{}_{n}}\}$ 的首项 $a{{}_{1}}\ne \frac {3}{5}$ ，且 $a{{}_{n+1}}+2a{{}_{n}}=3{^{n}}$ ， $a{{}_{n}}-b{{}_{n}}=\frac {3{^{n}}}{5}$ ， $(n\in \mathbf{N}{^{∗}})$ ．（Ⅰ）证明： $\{b{{}_{n}}\}$ 是等比数列；​​​​​​​‌（Ⅱ）若 $a{{}_{1}}=\frac {3}{2}$ ，数列 $\{a{{}_{n}}\}$ 中是否存在连续三项成等差数列？若存在，写出这三项，若不存在说明理由．（Ⅲ）若 $\{a{{}_{n}}\}$ 是递增数列，求 $a{{}_{1}}$ 的取值范围．

## 解答

1. （Ⅰ）因为 $\frac {b{{}_{n+1}}}{b{{}_{n}}}=\frac {a{{}_{n+1}}-\frac {1}{5}\cdot 3{^{n+1}}}{a{{}_{n}}-\frac {1}{5}\cdot 3{^{n}}}=-2$ ，且 $b{{}_{1}}=a{{}_{1}}-\frac {3}{5}\ne 0$ ，
2. 所以数列 $\left \{b{{}_{n}}\right \}$ 是首项为 $a{{}_{1}}-\frac {3}{5}$ ，公比为 $-2$ 的等比数列；
3. （Ⅱ）由（Ⅰ）知 $\left \{b{{}_{n}}\right \}$ 是首项为 $a{{}_{1}}-\frac {3}{5}=b{{}_{1}}=\frac {9}{10}$ ，公比为 $-2$ 的等比数列．
4. ∴ $b{{}_{n}}=a{{}_{n}}-\frac {1}{5}\cdot 3{^{n}}=\frac {9}{10}\cdot {\left({-2}\right)^{n-1}}\Rightarrow a{{}_{n}}=\frac {1}{5}\cdot 3{^{n}}+\frac {9}{10}\cdot {\left({-2}\right)^{n-1}}$
5. 若 $\left \{a{{}_{n}}\right \}$ 中存在连续三项成等差数列，则必有 $2a{{}_{n+1}}=a{{}_{n}}+a{{}_{n+2}}$ ，
6. 即 $2\left [\frac {1}{5}\cdot 3{^{n+1}}+\frac {9}{10}\cdot {\left({-2}\right)^{n}}\right ]=\frac {1}{5}\cdot 3{^{n}}+\frac {9}{10}\cdot {\left({-2}\right)^{n-1}}+\frac {1}{5}\cdot 3{^{n+2}}+\frac {9}{10}\cdot {\left({-2}\right)^{n+1}}$
7. 解得 $n=4$ ，即 $a{{}_{4}},a{{}_{5}},a{{}_{6}}$ 成等差数列．
8. （Ⅲ）如果 $a{{}_{n+1}}>a{{}_{n}}$ 成立，即 $\frac {1}{5}\cdot 3{^{n+1}}+\left ({a{{}_{1}}-\frac {3}{5}}\right )\cdot {\left({-2}\right)^{n}}>\frac {1}{5}\cdot 3{^{n}}+\left ({a{{}_{1}}-\frac {3}{5}}\right )\cdot {\left({-2}\right)^{n-1}}$ 对任意自然数均成立．
9. 化简得 $\frac {4}{15}\cdot 3{^{n}}>-\left ({a{{}_{1}}-\frac {3}{5}}\right ){\left({-2}\right)^{n}}$
10. 当 $n$ 为偶数时， $a{{}_{1}}>\frac {3}{5}-\frac {4}{15}{\left({\frac {3}{2}}\right)^{n}}$ ，因为 $p\left ({n}\right )=\frac {3}{5}-\frac {4}{15}{\left({\frac {3}{2}}\right)^{n}}$ 是递减数列，
11. 所以 $p\left ({n}\right ){{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}=p\left ({2}\right )=0$ ，即 $a{{}_{1}}>0$ ；
12. 当 $n$ 为奇数时， $a{{}_{1}}<\frac {3}{5}+\frac {4}{15}{\left({\frac {3}{2}}\right)^{n}}$ ，因为 $q\left ({n}\right )=\frac {3}{5}+\frac {4}{15}{\left({\frac {3}{2}}\right)^{n}}$ 是递增数列，
13. 所以 $q\left ({n}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=q\left ({1}\right )=1$ ，即 $a{{}_{1}}<1$ ；
14. 故 $a{{}_{1}}$ 的取值范围为 $\left ({0,1}\right )$ ．

## 知识点

**中文**:
  - 单调性
  - 等差数列的概念及通项公式
  - 等比数列的概念与通项公式

**English**:
  - Monotonicity
  - Concept and Formula
  - Concept and Formula

---
