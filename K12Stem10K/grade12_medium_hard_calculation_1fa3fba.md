# Mathematics - 题目 2990

**ID**: 1fa3fba79b8a440590d6bd26217d8469
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数f(x)＝e^{x}＋ax－a(a∈R且a≠0).​​​​​​​‌（1）若f(0)＝2，求实数a的值，并求此时f(x)在[－2，1]上的最小值；（2）若函数f(x)不存在零点，求实数a的取值范围.

## 解答

1. （1）由题意知，函数f(x)的定义域为R，
2. 又f(0)＝1－a＝2，得a＝－1，
3. 所以f(x)＝e^{x}－x＋1，求导得f′(x)＝e^{x}－1.
4. 易知f(x)在[－2，0]上单调递减，在[0，1]上单调递增，
5. 所以当x＝0时，f(x)在[－2，1]上取得最小值2.
6. （2）由（1）知f′(x)＝e^{x}＋a，由于e^{x}>0，
7. ①当a>0时，f′(x)>0，f(x)在R上是增函数，
8. 当x>1时，f(x)＝e^{x}＋a(x－1)>0；
9. 当x<0时，取x＝－ $\frac {1}{a}$ ，
10. 则f$\left ({-\frac {1}{a}}\right )$ <1＋a$\left ({-\frac {1}{a}-1}\right )$ ＝－a<0.
11. 所以函数f(x)存在零点，不满足题意.
12. ②当a<0时，令f′(x)＝0，得x＝ln(－a).
13. 在(－∞，ln(－a))上，f′(x)<0，f(x)单调递减，
14. 在(ln (－a)，＋∞)上，f′(x)>0，f(x)单调递增，
15. 所以当x＝ln(－a)时，f(x)取最小值.
16. 函数f(x)不存在零点，等价于f(ln(－a))＝e^{ln(}^{－}^{a}^{)}＋aln(－a)－a＝－2a＋aln(－a)>0，
17. 解得－e^{2}<a<0.
18. 综上所述，所求实数a的取值范围是(－e^{2}，0).

## 知识点

**中文**:
  - 利用导数求函数中的参数
  - 利用导数研究函数的单调性与单调区间
  - 利用导数研究函数的最值

**English**:
  - Finding Parameters using Derivatives
  - Monotonicity and Monotonic Intervals
  - Global Extrema (Max/Min) using Derivatives

---
