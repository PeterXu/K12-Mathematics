# Mathematics - 题目 1780

**ID**: 3063a0e2e87e4d7bac53d5f1b5c91f81
**年级**: Grade 11
**难度**: Medium
**题型**: Fill-in-the-blank

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ 满足 $a{{}_{1}}=728\frac {1}{2}$ ， $3a{{}_{n+1}}=a{{}_{n}}-1$ ，则满足不等式 $a{{}_{k-1}}\cdot a{{}_{k}}\mathrm{<}0$ 的 $k$ 的值为.​​​​​​​‌

## 解答

1. 由 $3a{{}_{n+1}}=a{{}_{n}}-1$ 得， $3\left ({a{{}_{n+1}}+\frac {1}{2}}\right )=\left ({a{{}_{n}}+\frac {1}{2}}\right )$ ，
2. 因为 $a{{}_{1}}+\frac {1}{2}=729$ ， $\left ({a{{}_{n+1}}+\frac {1}{2}}\right )=\frac {1}{3}\left ({a{{}_{n}}+\frac {1}{2}}\right )$ ，
3. 所以数列 $\left \{a{{}_{n}}+\frac {1}{2}\right \}$ 是首项为 $729$ ，公比为 $\frac {1}{3}$ 的等比数列.
4. 有 $a{{}_{n}}+\frac {1}{2}=729\times {\left({\frac {1}{3}}\right)^{n-1}}$ ， $a{{}_{n}}=3{^{7-n}}-\frac {1}{2}$ .
5. 因为 $a{{}_{n}}-a{{}_{n-1}}=\left ({3{^{7-n}}-\frac {1}{2}}\right )-\left ({3{^{8-n}}-\frac {1}{2}}\right )=-2\cdot 3{^{7-n}}<0$ ，
6. 所以数列 $\left \{a{{}_{n}}\right \}$ 为递减数列，
7. 若 $a{{}_{k-1}}\cdot a{{}_{k}}\mathrm{<}0$ ，则有 $a{{}_{k-1}}>0$ ， $a{{}_{k}}<0$
8. 由 $\begin{cases}3{^{8-k}}-\frac {1}{2}>0,\\3{^{7-k}}-\frac {1}{2}<0\end{cases}$ 得， $2\cdot 3{^{7}}<3{^{k}}<2\cdot 3{^{8}}$ ，
9. 又 $n\in {\mathbf{N}^{*}}$ ，所以 $k=8$ .
10. 故答案为：8.

## 知识点

**中文**:
  - 数列的递推公式
  - 等比数列的概念与通项公式
  - 等比数列的判定与证明

**English**:
  - Recurrence Formula
  - Concept and Formula
  - Determination and Proof

---
