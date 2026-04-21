# Mathematics - 题目 3270

**ID**: 29f14ba59a0f44efaba2be437c531c15
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Fill-in-the-blank

## 题目
已知函数 $f\left ({x}\right )=\left\{\begin{array}{l}\begin{array}{}{\rm{e}}^{-2x}-1,x\leqslant 0\\\frac {1}{2}{\ln}\left ({x+1}\right ),x>0\end{array}\end{array}\right.​​​​​​​‌$ .若 $x\left ({f\left ({x}\right )-a\left |{x}\right |}\right )\leqslant 0$ ，则a的取值范围是.

## 解答

1. 当 $x=0$ 时， $x\left ({f\left ({x}\right )-a\left |{x}\right |}\right )=0\leqslant 0$ 恒成立；
2. 当 $x<0$ 时，此时应有 $f\left ({x}\right )-a\left |{x}\right |=f\left ({x}\right )+ax\geqslant 0$ ，即 ${\rm{e}}^{-2x}-1+ax\geqslant 0$ .
3. 令 $g\left ({x}\right )={\rm{e}}^{-2x}-1+ax$ , $x<0$ ，则 $g^{′}\left ({x}\right )=-2{\rm{e}}^{-2x}+a$ .
4. 设 $h\left ({x}\right )=-2{\rm{e}}^{-2x}+a$ ，则 $h^{′}\left ({x}\right )=4{\rm{e}}^{-2x}>0$ 恒成立，
5. 所以 $h\left ({x}\right )$ ，即 $g^{′}\left ({x}\right )$ 单调递增.
6. 又 $g\left ({0}\right )={\rm{e}}^{0}-1=0$ ，则要使 $g\left ({x}\right )\geqslant 0$ 在 $\left ({-∞,0}\right )$ 上恒成立，
7. 应有 $g^{′}\left ({x}\right )=-2{\rm{e}}^{-2x}+a\leqslant 0$ 在 $\left ({-∞,0}\right )$ 上恒成立，
8. 即 $a\leqslant 2{\rm{e}}^{-2x}$ 在 $\left ({-∞,0}\right )$ 上恒成立.
9. 又 $x<0$ 时， $2{\rm{e}}^{-2x}>2$ ，所以 $a\leqslant 2$ ；
10. 当 $x>0$ 时，此时应有 $f\left ({x}\right )-a\left |{x}\right |=f\left ({x}\right )-ax\leqslant 0$ ，即 $\frac {1}{2}{\ln}\left ({x+1}\right )-ax\leqslant 0$ .
11. 令 $k\left ({x}\right )=\frac {1}{2}{\ln}\left ({x+1}\right )-ax$ ，则 $k^{′}\left ({x}\right )=\frac {1}{2\left ({x+1}\right )}-a$ .
12. 令 $m\left ({x}\right )=\frac {1}{2\left ({x+1}\right )}-a$ ，则 $m^{′}\left ({x}\right )=\frac {-1}{2\left ({x+1}\right )^{2}}<0$ 恒成立，
13. 所以 $m\left ({x}\right )$ ，即 $k^{′}\left ({x}\right )$ 单调递减.
14. 又 $k\left ({0}\right )=0$ ，则要使 $k\left ({x}\right )\leqslant 0$ 在 $\left ({0,+∞}\right )$ 上恒成立，
15. 应有 $k^{′}\left ({x}\right )=\frac {1}{2\left ({x+1}\right )}-a\leqslant 0$ 在 $\left ({0,+∞}\right )$ 上恒成立，
16. 即 $a\geqslant \frac {1}{2\left ({x+1}\right )}$ 在 $\left ({0,+∞}\right )$ 上恒成立.
17. 因为， $y=\frac {1}{2\left ({x+1}\right )}$ 在 $\left ({0,+∞}\right )$ 上单调递减，所以 $\frac {1}{2\left ({x+1}\right )}<\frac {1}{2}$ ，
18. 所以 $a\geqslant \frac {1}{2}$ .
19. 综上所述，a的取值范围是 $\left [\frac {1}{2},2\right ]$ .
20. 故答案为： $\left [\frac {1}{2},2\right ]$

## 知识点

**中文**:
  - 分段函数
  - 利用导数研究函数的单调性与单调区间
  - 利用导数解决不等式恒成立问题

**English**:
  - Piecewise Functions
  - Monotonicity and Monotonic Intervals
  - Solving Universally True Inequalities

---
