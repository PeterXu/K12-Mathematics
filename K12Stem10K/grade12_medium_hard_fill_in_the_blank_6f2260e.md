# Mathematics - 题目 2948

**ID**: 6f2260e62f1e437aa1b0dfc7558f658d
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: 填空题(本大题共5小题，每小题5分，共25分．把答案填在题中的横线上)

## 题目
已知数列 ${\rm \{\mathit{a}\mathit{_{n}}\}}$ 的各项均为正数,其前n项和S_{n}满足a_{n}·S_{n}=9(n=1,2,…).​​​​​​​‌给出下列四个结论:① ${\rm \{\mathit{a}\mathit{_{n}}\}}$ 的第2项小于3;② ${\rm \{\mathit{a}\mathit{_{n}}\}}$ 为等比数列;③ ${\rm \{\mathit{a}\mathit{_{n}}\}}$ 为递减数列;④ ${\rm \{\mathit{a}\mathit{_{n}}\}}$ 中存在小于 $\frac{1}{100}$ 的项.其中所有正确结论的序号是.

## 解答

1. 因为a_{n}·S_{n}=9,所以a_{1}·S_{1}=9,又a_{n}>0,所以a_{1}=3.
2. a_{2}·S_{2}=a_{2}(a_{1}+a_{2})=9,即 ${a}_{2}^{2}{\rm +3\mathit{a}_{2}-9=0}$ ,解得 ${\rm \mathit{a}_{2}=}\frac{-3+3\sqrt{5}}{2}{\rm =3×}$  $\frac{\sqrt{5}-1}{2}$ <3,所以①正确.当n⩾2时,由 ${\rm \mathit{S}\mathit{_{n}}=}\frac{9}{{a}_{n}}$ ,得 ${\rm \mathit{S}\mathit{_{n}}_{-1}=}\frac{9}{{a}_{n-1}}$ ,两式作差可得 ${\rm \mathit{a}\mathit{_{n}}=}\frac{9}{{a}_{n}}{\rm -}$  $\frac{9}{{a}_{n-1}}$ (提示:利用公式a_{n}=S_{n}-S_{n}_{−1}(n⩾2)求解),即 ${\rm \mathit{a}\mathit{_{n}}=}\frac{9({a}_{n-1}-{a}_{n})}{{a}_{n}{a}_{n-1}}$ ,整理得 ${a}_{n}^{2}{\rm =}$  $\frac{9({a}_{n-1}-{a}_{n})}{{a}_{n-1}}$ ,即 $\frac{{a}_{n}}{{a}_{n-1}}{\rm =}$  $\frac{9-{a}_{n}^{2}}{9}{\rm \mathit{.}}$ 若数列 ${\rm \{\mathit{a}\mathit{_{n}}\}}$ 为等比数列,则当n⩾2时, $\frac{{a}_{n+1}}{{a}_{n}}{\rm =}$  $\frac{9-{a}_{n+1}^{2}}{9}{\rm =}$  $\frac{{a}_{n}}{{a}_{n-1}}{\rm =}$  $\frac{9-{a}_{n}^{2}}{9}$ ,所以a_{n}_{+1}=a_{n}.又a_{1}=3≠a_{2},所以数列 ${\rm \{\mathit{a}\mathit{_{n}}\}}$ 不为等比数列,所以②不正确.由题知a_{n}·S_{n}=a_{n}_{+1}·S_{n}_{+1},所以 $\frac{{a}_{n}}{{a}_{n+1}}{\rm =}$  $\frac{{S}_{n+1}}{{S}_{n}}$ >1,所以a_{n}>a_{n}_{+1}>0,所以数列 ${\rm \{\mathit{a}\mathit{_{n}}\}}$ 为递减数列,所以③正确.若数列 ${\rm \{\mathit{a}\mathit{_{n}}\}}$ 的所有项均大于等于 $\frac{1}{100}$ ,即 ${\rm \mathit{a}\mathit{_{n}}\geqslant }\frac{1}{100}$ ,取n>90 000,则S_{n}>900,于是a_{n}·S_{n}>9,与已知矛盾,所以 ${\rm \{\mathit{a}\mathit{_{n}}\}}$ 中存在小于 $\frac{1}{100}$ 的项,所以④正确.

## 知识点

**中文**:
  - 单调性
  - 等比数列的判定与证明

**English**:
  - Monotonicity
  - Determination and Proof

---
