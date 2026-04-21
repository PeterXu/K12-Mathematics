# Mathematics - 题目 1099

**ID**: 6a7441395339408dbffaf8582b923373
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )={\rm{e}}{^{x}}-2{\rm{e}}{\rm{l}}{\rm{n}}x+ax+{\rm{l}}{\rm{n}}a(a>0)$ ．(1)若 $a=1$ ，证明： $f\left ({x}\right )>\frac {3}{2}x$ ；​​​​​​​‌(2)若 $f\left ({x}\right )\geqslant 2{\rm{e}}+1$ 恒成立，求实数 $a$ 的取值范围．

## 解答

1. （1）当 $a=1$ 时， $f\left ({x}\right )={\rm{e}}{^{x}}-2{\rm{e}}{\rm{l}}{\rm{n}}x+x$ ，
2. 要证明 $f\left ({x}\right )>\frac {3}{2}x$ ，即证 $g\left ({x}\right )=f\left ({x}\right )-\frac {3}{2}x={\rm{e}}{^{x}}-2{\rm{e}}{\rm{l}}{\rm{n}}x-\frac {x}{2}>0$ .
3. 令 $h\left ({x}\right )={\rm{e}}{^{x}}-{\rm{e}}x,x\in \left ({0,+\infty }\right )$ ，则 $h^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-{\rm{e}}$ ，令 $h^{′}{\left ({x}\right )}=0$ ，解得 $x=1$ ，
4. 当 $x\in \left ({0,1}\right )$ 时， $h^{′}{\left ({x}\right )}<0$ ，即可得 $h\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上单调递减，
5. 当 $x\in \left ({1,+\infty }\right )$ 时， $h^{′}{\left ({x}\right )}>0$ ，即可得 $h\left ({x}\right )$ 在 $\left ({1,+\infty }\right )$ 上单调递增，
6. 即 $h\left ({x}\right )$ 在 $x=1$ 处取得极小值，也是最小值 $h\left ({1}\right )=0$ ，故 ${\rm{e}}{^{x}}\geqslant {\rm{e}}x$ ；
7. 令 $p\left ({x}\right )=x-{\rm{e}}{\rm{l}}{\rm{n}}x,x\in \left ({0,+\infty }\right )$ ，则 $p^{′}{\left ({x}\right )}=1-\frac {{\rm{e}}}{x}$ ，令 $p^{′}{\left ({x}\right )}=0$ ，解得 $x={\rm{e}}$ ；
8. 即可得当 $x\in \left ({0,{\rm{e}}}\right )$ 时， $p{^{\prime }}\left ({x}\right )<0$ ，可得 $p\left ({x}\right )$ 在 $\left ({0,{\rm{e}}}\right )$ 上单调递减，
9. 当 $x\in \left ({{\rm{e}},+\infty }\right )$ 时， $p{^{\prime }}\left ({x}\right )>0$ ，可得 $p\left ({x}\right )$ 在 $\left ({{\rm{e}},+\mathrm{∞}}\right )$ 上单调递增，
10. 即 $p\left ({x}\right )$ 在 $x={\rm{e}}$ 处取得极小值，也是最小值 $p\left ({{\rm{e}}}\right )=0$ ，故 $x\geqslant {\rm{e}}{\rm{l}}{\rm{n}}x$ ；
11. 因此 ${\rm{e}}{^{x}}-2{\rm{e}}{\rm{l}}{\rm{n}}x-\frac {x}{2}>{\rm{e}}x-2x-\frac {x}{2}=\left ({{\rm{e}}-\frac {5}{2}}\right )x>0$ ,
12. 故 $f\left ({x}\right )>\frac {3}{2}x$ .
13. （2）易知 $f\left ({x}\right )={\rm{e}}{^{x}}-2{\rm{e}}{\rm{l}}{\rm{n}}x+ax+{\rm{l}}{\rm{n}}a\geqslant 2{\rm{e}}+1$ 恒成立的一个必要条件是 $f\left ({1}\right )\geqslant 2{\rm{e}}+1$ ,
14. 即 ${\rm{e}}+a+{\rm{l}}{\rm{n}}a\geqslant 2{\rm{e}}+1$ ，故 $a+{\rm{l}}{\rm{n}}a\geqslant {\rm{e}}+1$ ；
15. 令 $t\left ({x}\right )=x+{\ln}x$ ，则 $t^{′}{\left ({x}\right )}=1+\frac {1}{x}>0$ 恒成立，即 $t\left ({x}\right )$ 为 $\left ({0,+\infty }\right )$ 上的增函数，
16. 因此可得 $t\left ({a}\right )=a+{\ln}a\geqslant {\rm{e}}+{{1}}{\rm{=}}t\left ({{\rm{e}}}\right )$ ，可得 $a\geqslant {\rm{e}}$ ；
17. 下面证明充分性：
18. 当 $a\geqslant {\rm{e}}$ 时， $f\left ({x}\right )\geqslant {\rm{e}}{^{x}}-2{\rm{e}}{\rm{l}}{\rm{n}}x+{\rm{e}}x+1$ ，
19. 令 $m\left ({x}\right )={\rm{e}}{^{x}}-2{\rm{e}}{\rm{l}}{\rm{n}}x+{\rm{e}}x+1$ ，则 $m^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-\frac {2{\rm{e}}}{x}+{\rm{e}}$ ，
20. 易知 $m^{′}{\left ({x}\right )}$ 为单调递增函数，令 $m^{′}{\left ({x}\right )}=0$ ，解得 $x=1$ ；
21. 可知当 $x\in \left ({0,1}\right )$ 时， $m^{′}{\left ({x}\right )}<0$ ，可得 $m\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上单调递减，
22. 当 $x\in \left ({1,+\infty }\right )$ 时， $m{^{\prime }}\left ({x}\right )>0$ ，可得 $m\left ({x}\right )$ 在 $\left ({1,+\infty }\right )$ 上单调递增，
23. 即 $m\left ({x}\right )$ 在 $x=1$ 处取得极小值，也是最小值 $m\left ({1}\right )=2{\rm{e}}+1$ ，
24. 故当 $a\geqslant {\rm{e}}$ 时， $f\left ({x}\right )\geqslant m\left ({x}\right )\geqslant 2{\rm{e}}+1$ ，
25. 综上可知，实数 $a$ 的取值范围是 $\left [{{\rm{e}}{\rm{,}}{{+}}\infty }\right )$ .

## 知识点

**中文**:
  - 利用导数解决不等式恒成立问题
  - 利用导数证明不等式

**English**:
  - Solving Universally True Inequalities
  - Proving Inequalities using Derivatives

---
