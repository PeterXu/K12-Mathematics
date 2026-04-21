# Mathematics - 题目 1808

**ID**: d32acf1d4b6a4daeb192cdf0dc35e6a4
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: 多选题（本大题共3小题，共15分）

## 题目
设 ${x}^{2026}={a}_{0}+{a}_{1}(x+1)+{a}_{2}(x+1)^{2}+\cdots +{a}_{2026}{\left(x+1\right)^{2026}}$ ，则（      ）​​​​​​​‌

## 解答

1. 令 $x+1=t$ ,可得 $x=t-1$ ,代入题干等式得 $(-1+t)^{2026}={a}_{0}+{a}_{1}t+{a}_{2}{t}^{2}+\cdots +{a}_{2026}{t}^{2026}$ .令 $f(t)={\left(-1+t\right)^{2026}}={a}_{0}+{a}_{1}t+{a}_{2}{t}^{2}+\cdots +{a}_{2026}{t}^{2026}$ .
2. 对于 $\mathrm{A}$ 选项,展开式通项为 ${T}_{k+1}={\mathrm{C}}_{2026}^{k}\cdot (-1)^{2026-k}{t}^{k}(0\leqslant k\leqslant 2026,k\in \boldsymbol{N})$ ,所以 ${a}_{1}={\mathrm{C}}_{2026}^{1}\cdot (-1)^{2025}=-2026$ , $\mathrm{A}$ 正确；
3. 对于 $\mathrm{B}$ 选项, ${a}_{0}-{a}_{1}+{a}_{2}-\cdots +{a}_{2026}=f(-1)={\left(-2\right)^{2026}}={2}^{2026}$ , $\mathrm{B}$ 正确；
4. 对于 $\mathrm{C}$ 选项,由 $\mathrm{A}$ 选项可知, ${a}_{k}={\mathrm{C}}_{2026}^{k}\cdot (-1)^{2026-k}(0\leqslant k\leqslant 2026,k\in \boldsymbol{N})$ ,当 $k$ 为奇数时, ${a}_{k}<0$ ,且 ${a}_{k}=-{\mathrm{C}}_{2026}^{k}$ ,当 $k$ 为偶数时, ${a}_{k}>0$ ,且 ${a}_{k}={\mathrm{C}}_{2026}^{k}$ ,结合二项式系数的增减性可知, ${a}_{k}(0\leqslant k\leqslant 2026,k\in \boldsymbol{N})$ 中最大的是 ${a}_{1012}$ 和 ${a}_{1014}$ , $\mathrm{C}$ 错误；
5. 对于 $\mathrm{D}$ 选项,因为 $f^\prime (t)={a}_{1}+2{a}_{2}t+\cdots +2026{a}_{2026}{t}^{2025}=2026(t-1)^{2025}$ ,故 ${a}_{1}+2{a}_{2}+3{a}_{3}+\cdots +2026{a}_{2026}=f^\prime (1)=2026\cdot (1-1)^{2025}=0$ , $\mathrm{D}$ 正确.故选 $\mathrm{A}\mathrm{B}\mathrm{D}$ .

## 知识点

**中文**:
  - 二项展开式中各项的系数
  - 导数的四则运算
  - 增减性与最大值
  - 二项展开式中各项的系数和

**English**:
  - Coefficients in Binomial Expansion
  - Arithmetic Operations of Derivatives
  - Monotonicity and Maximum Value
  - Sum of Coefficients

---
