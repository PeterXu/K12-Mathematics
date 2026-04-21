# Mathematics - 题目 2248

**ID**: d451b371f1d74d14b2bdd45273301a93
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\frac {1}{2}ax^{2}+{\ln}x-\left ({a+1}\right )x$ .​​​​​​​‌(1)当 $a=-4$ 时，求 $f\left ({x}\right )$ 的单调区间与极值；(2)当 $a\geqslant 1$ 时，证明： $f\left ({x}\right )$ 只有一个零点.

## 解答

1. （1）当 $a=-4$ 时， $f\left ({x}\right )=-2x^{2}+{\ln}x+3x$ ， $x\in \left ({0,+\infty }\right )$
2. $f^{′}\left ({x}\right )=-4x+\frac {1}{x}+3=\frac {-\left ({4x^{2}+3x+1}\right )}{x}=\frac {-\left ({4x+1}\right )\left ({x-1}\right )}{x}$
3. 由 $f^{′}\left ({x}\right )>0$ 得， $-\frac {1}{4}<x<1$ ，由 $f^{′}\left ({x}\right )<0$ 得， $x<-\frac {1}{4}$ 或 $x>1$
4. ∴ $f\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上单调递增， $\left ({1,+\infty }\right )$ 上单调递减，
5. ∴ $f\left ({x}\right )$ 在 $x=1$ 处取得极大值 $f\left ({1}\right )=1$ ，无极小值.
6. （2）∵ $f\left ({x}\right )=\frac {1}{2}ax^{2}+{\ln}x-\left ({a+1}\right )x$ ， $x\in \left ({0,+\infty }\right )$
7. ∴ $f^{′}\left ({x}\right )=ax+\frac {1}{x}-\left ({a+1}\right )=\frac {ax^{2}-\left ({a+1}\right )x+1}{x}=\frac {\left ({ax-1}\right )\left ({x-1}\right )}{x}$
8. 由 $f^{′}\left ({x}\right )=0$ ， $a>0$ 得， $x=\frac {1}{a}$ 或 $x=1$
9. ①当 $a=1$ 时， $f^{′}\left ({x}\right )\geqslant 0$ ， $f\left ({x}\right )$ 在 $\left ({0,\infty }\right )$ 上单调递增
10. ∵ $f\left ({1}\right )=-\frac {3}{2}<0$ ， $f\left ({4}\right )={\ln}4>0$
11. ∴ $f\left ({1}\right )\cdot f\left ({4}\right )<0$ ，故 $f\left ({x}\right )$ 在 $\left ({1,4}\right )$ 上有唯一零点
12. ②当 $a>1$ 时， $f^{′}\left ({x}\right )>0$ 得 $x<\frac {1}{a}$ 或 $x>1$
13. ∴ $f\left ({x}\right )$ 在 $\left ({0,\frac {1}{a}}\right )$ 上单调递增，在 $\left ({\frac {1}{a},1}\right )$ 上单调递减，在 $\left ({1,+\infty }\right )$ 上单调递增
14. ∵ $f\left ({\frac {1}{a}}\right )=-\frac {1}{2a}-{\ln}a-1<0$ ， $f\left ({4}\right )=4a-4+{\ln}4>0$
15. ∴ $f\left ({\frac {1}{a}}\right )\cdot f\left ({4}\right )<0$ ，故 $f\left ({x}\right )$ 在 $\left ({\frac {1}{a},4}\right )$ 上有唯一零点
16. 综上：当 $a\geqslant 1$ 时， $f\left ({x}\right )$ 只有一个零点.

## 知识点

**中文**:
  - 利用导数研究函数的单调性与单调区间
  - 利用导数研究函数的极值
  - 利用导数解决函数零点问题

**English**:
  - Monotonicity and Monotonic Intervals
  - Extrema of Functions using Derivatives
  - Solving Zero Point Problems

---
