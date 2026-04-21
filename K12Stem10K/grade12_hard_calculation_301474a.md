# Mathematics - 题目 177

**ID**: 301474a05e44420285634269b7f62d8e
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )={\rm{e}}{{}^{x-1}}+ax$ .​​​​​​​‌(1)若 $f\left ({x}\right )\geqslant 0$ 恒成立，求 $a$ 的取值范围；(2)当 $m\geqslant 1$ 时，证明 ${\ln}x+\frac {m{\rm{e}}{{}^{x}}}{x}-{\sin}x>1$ 恒成立.

## 解答

1. （1）解： $\because f\left ({x}\right )={\rm{e}}{{}^{x-1}}+ax$ ，且该函数的定义域为 $\mathbf{R}$ ， $f^{′}\left ({x}\right )={\rm{e}}{{}^{x-1}}+a$ .
2. ①当 $a>0$ 时， $f^{′}\left ({x}\right )>0$ 恒成立， $f\left ({x}\right )$ 在 $\mathbf{R}$ 上单调递增，
3. 因为 $f\left ({-\frac {1}{a}}\right )={\rm{e}}{{}^{-\frac {1}{a}-1}}-1<0$ ，所以 $a>0$ 时不符合题意；
4. ②当 $a=0$ 时， $f\left ({x}\right )={\rm{e}}{{}^{x-1}}>0$ ，显然成立；
5. ③当 $a<0$ 时，由 $f^{′}\left ({x}\right )=0$ 解得 $x=1+{\rm{l}}{\rm{n}}\left ({-a}\right )$ ，
6. 当 $x\in \left ({-\infty ,1+{\rm{l}}{\rm{n}}\left ({-a}\right )}\right )$ 时， $f^{′}\left ({x}\right )<0$ ， $f\left ({x}\right )$ 单调递减；
7. 当 $x\in \left ({1+{\rm{l}}{\rm{n}}\left ({-a}\right ),+\infty }\right )$ 时， $f^{′}\left ({x}\right )>0$ ， $f\left ({x}\right )$ 单调递增.
8. 所以， $f\left ({x}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=f\left ({1+{\rm{l}}{\rm{n}}\left ({-a}\right )}\right )=-a+a\left [1+{\rm{l}}{\rm{n}}\left ({-a}\right )\right ]=a{\rm{l}}{\rm{n}}\left ({-a}\right )\geqslant 0$ ，即 ${\rm{l}}{\rm{n}}\left ({-a}\right )\leqslant 0$ ，
9. 所以， $0<-a\leqslant 1$ ，解得 $-1\leqslant a<0$ .
10. 综上所述， $-1\leqslant a\leqslant 0$ .
11. （2）证明：由题意可知，函数 $g\left ({x}\right )={\ln}x+\frac {m{\rm{e}}{{}^{x}}}{x}-{\sin}x-1$ 的定义域为 $\left ({0,+∞}\right )$ ，
12. 先证明 ${\ln}x+\frac {{\rm{e}}{{}^{x}}}{x}-{\sin}x-1>0$ ，令 $h\left ({x}\right )=\frac {{\rm{e}}{{}^{x}}}{x}+{\rm{l}}{\rm{n}}x-{\rm{s}}{\rm{i}}{\rm{n}}x-1$ ，
13. 则 $h\left ({x}\right )={\rm{e}}{{}^{x-{\rm{l}}{\rm{n}}x}}-\left ({x-{\rm{l}}{\rm{n}}x+1}\right )+x-{\rm{s}}{\rm{i}}{\rm{n}}x$ ，
14. 由（1）可知 ${\rm{e}}{{}^{x-1}}-x\geqslant 0$ ，所以， ${\rm{e}}{{}^{x-{\rm{l}}{\rm{n}}x}}-\left ({x-{\rm{l}}{\rm{n}}x+1}\right )\geqslant 0$ ，
15. 设 $p\left ({x}\right )=x-{\rm{s}}{\rm{i}}{\rm{n}}x$ ，其中 $x>0$ ，则 $p^{′}\left ({x}\right )=1-{\rm{c}}{\rm{o}}{\rm{s}}x\geqslant 0$ 且 $p^{′}\left ({x}\right )$ 不恒为零，
16. 所以， $p\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上为增函数，故当 $x>0$ 时， $p\left ({x}\right )>p\left ({0}\right )=0$ ，
17. 所以， ${\rm{e}}{{}^{x-{\ln}x}}-x+{\ln}x-1+x-{\sin}x>0$ ，
18. 因为 $m\geqslant 1$ ，故 $g\left ({x}\right )\geqslant h\left ({x}\right )>0$ ，故原不等式得证.

## 知识点

**中文**:
  - 利用导数解决不等式恒成立问题

**English**:
  - Solving Universally True Inequalities

---
