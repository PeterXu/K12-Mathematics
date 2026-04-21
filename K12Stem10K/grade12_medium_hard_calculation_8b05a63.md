# Mathematics - 题目 790

**ID**: 8b05a63fc19d4287a22d3d74d18cd469
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
若f(x)=log_{a}x(a>0,a≠1).​​​​​​​‌(1)曲线y=f(x)过(4,2),求f(2x−2)<f(x)的解集;(2)存在x使得f(x+1),f(ax),f(x+2)成等差数列,求a的取值范围.

## 解答

1. (1)由曲线y=f(x)过点(4,2)可得log_{a}4=2,则a^{2}=4,解得a=±2,又a>0,所以a=2.
2. 因为f(x)=log_{2}x在(0,+∞)上单调递增,f(2x−2)<f(x),所以0<2x−2<x,解得1<x<2,
3. 所以f(2x−2)<f(x)的解集为(1,2).
4. (2)因为存在x使得f(x+1),f(ax),f(x+2)成等差数列,所以f(x+1)+f(x+2)=2f(ax),
5. 即log_{a}(x+1)+log_{a}(x+2)=2log_{a}(ax)有解.
6. 化简可得log_{a}[(x+1)(x+2)]=log_{a}(ax)^{2},
7. 即 ${\rm (\mathit{x}+1)(\mathit{x}+2)=(\mathit{ax})^{2}}$ 且 $\begin{cases}x+1>0,\\x+2>0,\\ax>0,\\a>0,a\ne 1\end{cases}$ (提示:对数函数y=log_{a}x的定义域为(0,+∞),考虑函数性质时应注意定义域优先原则),解得x>0,且 ${\rm \mathit{a}^{2}=}\frac{(x+1)(x+2)}{{x}^{2}}$ 在(0,+∞)上有解.
8. 又 $\frac{(x+1)(x+2)}{{x}^{2}}{\rm =}$  $\frac{2}{{x}^{2}}{\rm +}$  $\frac{3}{x}{\rm +1=2}$  ${\left(\frac{1}{x}+\frac{3}{4}\right)^{2}}{\rm -}$  $\frac{1}{8}$ ,令 ${\rm \mathit{t}=}\frac{1}{x}{\rm ,\mathit{t}∈(0,+∞)}$ ,
9. ${\rm \mathit{y}=2}{\left(t+\frac{3}{4}\right)^{2}}{\rm -}$  $\frac{1}{8}$ 在(0,+∞)上单调递增,则 ${\rm \mathit{y}=2}{\left(\frac{1}{x}+\frac{3}{4}\right)^{2}}{\rm -}$  $\frac{1}{8}$ 在(0,+∞)上单调递减,当x→+∞时,y→1,所以 $\frac{(x+1)(x+2)}{{x}^{2}}$ >1,
10. 即a^{2}>1,解得a<−1或a>1,又a>0,所以a>1.

## 知识点

**中文**:
  - 对数函数的单调性
  - 等差中项
  - 等差数列的综合应用

**English**:
  - Monotonicity of Logarithmic Functions
  - Arithmetic Mean (Middle Term)
  - Comprehensive Applications

---
