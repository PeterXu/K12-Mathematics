# Mathematics - 题目 2059

**ID**: bc6a54705ae842cfa237bf8aa27a544d
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )={\rm{e}}{^{x}}-\frac {a}{3}x{^{3}}-1$ ．(1)若 $f\left ({x}\right )$ 有3个极值点，求 $a$ 的取值范围；​​​​​​​‌(2)若 $x\geqslant 0,f\left ({x}\right )\geqslant ax{^{2}}+x$ ，求 $a$ 的取值范围．

## 解答

1. （1）由 $f\left ({x}\right )={\rm{e}}{^{x}}-\frac {a}{3}x{^{3}}-1$ ，得 $f^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-ax{^{2}}$ ，
2. 由 $f\left ({x}\right )$ 存在极值，则 $f^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-ax{^{2}}=0$ ，知 $a\ne 0$ ，则 $\frac {1}{a}=\frac {x{^{2}}}{{\rm{e}}{^{x}}}$ 有3个不相等实数根，
3. 令 $g\left ({x}\right )=\frac {x{^{2}}}{{\rm{e}}{^{x}}}$ ，则 $g^{′}{\left ({x}\right )}=\frac {2x-x{^{2}}}{{\rm{e}}{^{x}}}=\frac {-x\left ({x-2}\right )}{{\rm{e}}{^{x}}}$ ，
4. 当 $x<0$ 时， $g^{′}{\left ({x}\right )}<0,g\left ({x}\right )$ 单调递减；当 $0<x<2$ 时， $g^{′}{\left ({x}\right )}>0,g\left ({x}\right )$ 单调递增；当 $x>2$ 时， $g^{′}{\left ({x}\right )}<0,g\left ({x}\right )$ 单调递减．
5. 则 $g\left ({x}\right )$ 在 $x=0$ 时取极小值 $g\left ({0}\right )=0,g\left ({x}\right )$ 在 $x=2$ 处取得极大值 $g\left ({2}\right )=\frac {4}{{\rm{e}}{^{2}}}$ ，
6. 又 $x\to -∞$ 时， $g\left ({x}\right )\to +∞;x\to +∞$ 时， $g\left ({x}\right )\to 0$ ，又 $g\left ({x}\right )>0$ ．
7. 所以 $f^{′}{\left ({x}\right )}=0$ 有3个不相等实数根时， $0<\frac {1}{a}<\frac {4}{{\rm{e}}{^{2}}}$ ，即 $a>\frac {{\rm{e}}{^{2}}}{4}$ ，
8. 所以 $f\left ({x}\right )$ 有3个极值点时， $a$ 的取值范围是 $\left ({\frac {{\rm{e}}{^{2}}}{4},+∞}\right )$ ．
9. （2）由 $f\left ({x}\right )\geqslant ax{^{2}}+x$ ，得 ${\rm{e}}{^{x}}-\frac {a}{3}x{^{3}}-ax{^{2}}-x-1\geqslant 0$ ，
10. 令 $h\left ({x}\right )={\rm{e}}{^{x}}-\frac {a}{3}x{^{3}}-ax{^{2}}-x-1$ ，得 $h^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-ax{^{2}}-2ax-1$ ，知 $h^{′}{\left ({0}\right )}=0,h\left ({0}\right )=0$ ，
11. 令 $u\left ({x}\right )=h^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-ax{^{2}}-2ax-1$ ，则 $u^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-2ax-2a$ ，
12. 又令 $v\left ({x}\right )=u^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-2ax-2a$ ，则 $v^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-2a$ ，知 $v\left ({0}\right )=1-2a,v^{′}{\left ({0}\right )}=1-2a$ ，
13. 当 $v^{′}{\left ({0}\right )}=1-2a\geqslant 0$ 时，即 $a\leqslant \frac {1}{2}$ 时，
14. 由于 $v^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-2a$ 单调递增，则 $v^{′}{\left ({x}\right )}\geqslant v^{′}{\left ({0}\right )}\geqslant 0$ ，
15. 故当 $x\geqslant 0$ 时， $v\left ({x}\right )$ 即 $u^{′}{\left ({x}\right )}$ 单调递增，则 $u^{′}{\left ({x}\right )}\geqslant u^{′}{\left ({0}\right )}=1-2a\geqslant 0$ ，
16. 所以，当 $x\geqslant 0$ 时， $u\left ({x}\right )$ 即 $h^{′}{\left ({x}\right )}$ 单调递增，则 $h^{′}{\left ({x}\right )}\geqslant h^{′}{\left ({0}\right )}=0$ ，
17. 故当 $x\geqslant 0$ 时， $h\left ({x}\right )$ 单调递增，则 $h\left ({x}\right )\geqslant h\left ({0}\right )=0$ ，
18. 所以，当 $x\geqslant 0,h\left ({x}\right )\geqslant 0$ 恒成立．则 $a\leqslant \frac {1}{2}$ 时满足条件．
19. 当 $v^{′}{\left ({0}\right )}=1-2a<0$ 时，即 $a>\frac {1}{2}$ 时，
20. 由于 $v^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-2a$ 单调递增，由于 $v^{′}{\left ({{\rm{l}}{\rm{n}}\left ({1+2a}\right )}\right )}={\rm{e}}{^{{\rm{l}}{\rm{n}}\left ({1+2a}\right )}}-2a=1>0$ ，
21. 故 $\exists t{{}_{0}}\in \left ({0,{\rm{l}}{\rm{n}}\left ({1+2a}\right )}\right )$ ，使得 $v^{′}{\left ({t{{}_{0}}}\right )}=0$ ，
22. 当 $0<x<t{{}_{0}}$ 时， $v^{′}{\left ({x}\right )}<0$ ，则 $0<x<t{{}_{0}}$ 时， $v\left ({x}\right )$ 即 $u^{′}{\left ({x}\right )}$ 单调递减，
23. 故 $u^{′}{\left ({x}\right )}<u^{′}{\left ({0}\right )}=1-2a<0$ ，
24. 故当 $0<x<t{{}_{0}}$ 时， $u\left ({x}\right )$ 即 $h^{′}{\left ({x}\right )}$ 单调递减，
25. 所以 $h^{′}{\left ({x}\right )}<h^{′}{\left ({0}\right )}=0$ ，此时 $h\left ({x}\right )$ 单调递减， $h\left ({x}\right )\mathrm{<}h\left ({0}\right )=0$ ，不满足条件．
26. 综上所述，当 $x\geqslant 0,f\left ({x}\right )\geqslant ax{^{2}}+x$ 恒成立时， $a$ 的取值范围是 $\left ({-∞,\frac {1}{2}}\right ]$ ．

## 知识点

**中文**:
  - 利用导数研究函数的极值
  - 利用导数解决不等式恒成立问题

**English**:
  - Extrema of Functions using Derivatives
  - Solving Universally True Inequalities

---
