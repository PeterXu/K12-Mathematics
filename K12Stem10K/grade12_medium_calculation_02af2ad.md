# Mathematics - 题目 770

**ID**: 02af2ad8b3c5426eb47c93f586112040
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\frac {{\rm{e}}{^{x}}+{\rm{e}}{^{ax}}}{2},a\in {\mathbf{R}}$ ，且 $y=f\left ({x+1}\right )$ 的图象关于直线 $x=-1$ 对称．（1）求实数 $a$ 的值；​​​​​​​‌（2）求函数 $f\left ({x}\right )$ 在 $\left [-1,1\right ]$ 上的值域；（3）若 $\forall x\in \left [-1,1\right ]$ ，不等式 $f\left ({2x}\right )+$  $mf\left ({x}\right )\geqslant 0$ 恒成立，求实数 $m$ 的取值范围．

## 解答

1. （1）由题意知 $y=f\left ({x+1}\right )$ 的图象关于直线 $x=-1$ 对称，
2. 则 $y=f\left ({x}\right )$ 的图象关于y轴对称，即 $f\left ({x}\right )=\frac {{\rm{e}}{^{x}}+{\rm{e}}{^{ax}}}{2},x\in {\mathbf{R}}$ 为偶函数，
3. 故 $f\left ({-x}\right )=f\left ({x}\right ),\therefore \frac {{\rm{e}}{^{-x}}+{\rm{e}}{^{-ax}}}{2}=\frac {{\rm{e}}{^{x}}+{\rm{e}}{^{ax}}}{2}$ ，即 ${\rm{e}}{^{x}}-{\rm{e}}{^{-x}}=-\left ({{\rm{e}}{^{ax}}-{\rm{e}}{^{-ax}}}\right )$ ，
4. 设 $g\left ({x}\right )={\rm{e}}{^{x}}-{\rm{e}}{^{-x}},x\in {\rm{R}}$ ，则 $g\left ({-x}\right )={\rm{e}}{^{-x}}-{\rm{e}}{^{x}}=-g\left ({x}\right )$ ，
5. 即 $g\left ({x}\right )$ 为奇函数，而 $g^{′}{\left ({x}\right )}={\rm{e}}{^{x}}+{\rm{e}}{^{-x}}>0$ ，即 $g\left ({x}\right )$ 在R上单调递增，
6. 则由 ${\rm{e}}{^{x}}-{\rm{e}}{^{-x}}=-\left ({{\rm{e}}{^{ax}}-{\rm{e}}{^{-ax}}}\right )$ ，可得 $g\left ({x}\right )=-g\left ({ax}\right )$ ，则 $g\left ({x}\right )=g\left ({-ax}\right )$ ，
7. 则 $x=-ax,\therefore \left ({a+1}\right )x=0$ ，由于 $x\in {\rm{R}}$ ，故 $a+1=0,\therefore a=-1$ ；
8. （2）由（1）可知 $f\left ({x}\right )=\frac {{\rm{e}}{^{x}}+{\rm{e}}{^{-x}}}{2}$ ，则 $f^{′}{\left ({x}\right )}=\frac {{\rm{e}}{^{x}}-{\rm{e}}{^{-x}}}{2}$ ，
9. 当 $-1\leqslant x<0$ 时， ${\rm{e}}{^{x}}<{\rm{e}}{^{-x}}$ ，则 $f^{′}{\left ({x}\right )}<0$ ，则 $f\left ({x}\right )$ 在 $\left [{-1,0}\right )$ 上单调递减，
10. 当 $0<x\leqslant 1$ 时， ${\rm{e}}{^{x}}>{\rm{e}}{^{-x}}$ ，则 $f^{′}{\left ({x}\right )}>0$ ，则 $f\left ({x}\right )$ 在 $\left ({0,1}\right ]$ 上单调递增，
11. 而 $f\left ({1}\right )=\frac {{\rm{e}}+{\rm{e}}{^{-1}}}{2},f\left ({-1}\right )=\frac {{\rm{e}}{^{-1}}+{\rm{e}}}{2},f\left ({0}\right )=1$ ，
12. 故 $f\left ({x}\right )$ 在 $\left [-1,1\right ]$ 上的值域为 $\left [1,\frac {{\rm{e}}+{\rm{e}}{^{-1}}}{2}\right ]$ ；
13. （3） $\forall x\in \left [-1,1\right ]$ ，不等式 $f\left ({2x}\right )+$  $mf\left ({x}\right )\geqslant 0$ 恒成立，即 $\frac {{\rm{e}}{^{2x}}+{\rm{e}}{^{-2x}}}{2}+m\cdot \frac {{\rm{e}}{^{x}}+{\rm{e}}{^{-x}}}{2}\geqslant 0$ 恒成立，
14. 即 $\forall x\in \left [-1,1\right ]$ ， ${\left({{\rm{e}}{^{x}}+{\rm{e}}{^{-x}}}\right)^{2}}-2+m\left ({{\rm{e}}{^{x}}+{\rm{e}}{^{-x}}}\right )\geqslant 0$ 恒成立，
15. 令 $t={\rm{e}}{^{x}}+{\rm{e}}{^{-x}}$ ，由于 $x\in \left [-1,1\right ]$ ，结合（2）可知 $t\in \left [2,{\rm{e}}+{\rm{e}}{^{-1}}\right ]$ ，
16. 则 ${\left({{\rm{e}}{^{x}}+{\rm{e}}{^{-x}}}\right)^{2}}-2+m\left ({{\rm{e}}{^{x}}+{\rm{e}}{^{-x}}}\right )\geqslant 0$ 即为 $t{^{2}}+mt-2\geqslant 0$ ，
17. 即得 $m\geqslant \frac {2}{t}-t$ 对于 $t\in \left [2,{\rm{e}}+{\rm{e}}{^{-1}}\right ]$ 恒成立，
18. 而函数 $y=\frac {2}{t}-t$ 在 $\left [2,{\rm{e}}+{\rm{e}}{^{-1}}\right ]$ 上单调递减，故 $\left ({\frac {2}{t}-t}\right ){{}_{{\rm \max }}}=\frac {2}{2}-2=-1$ ，
19. 故 $m\geqslant -1$ .

## 知识点

**中文**:
  - 与函数有关的恒成立问题
  - 函数的值域
  - 函数对称性

**English**:
  - Universally True Problems Related to Functions
  - Range of Functions
  - Symmetry of Functions

---
