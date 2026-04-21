# Mathematics - 题目 2752

**ID**: 75431ab2b3e44427a2b4dd76d35e8776
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\frac {x}{{\rm{e}}{^{x}}}$ ，直线l为曲线 $y=f\left ({x}\right )$ 在点 $\left ({t,f\left ({t}\right )}\right )$ 处的切线.​​​​​​​‌(1)当 $t=0$ 时，求出直线 $l$ 的方程；(2)若 $g\left ({x}\right )=f^{′}{\left ({x}\right )}$ ，求 $g\left ({x}\right )$ 的最值；(3)若直线 $l$ 与曲线 $y=f\left ({x}\right )$ 相交于点 $\left ({s,f\left ({s}\right )}\right )$ ，且 $s<t$ ，求实数 $t$ 的取值范围．

## 解答

1. （1）由题意可得 $f^{′}{\left ({x}\right )}=\frac {{\rm{e}}{^{x}}-x{\rm{e}}{^{x}}}{{\rm{e}}{^{2x}}}=\frac {1-x}{{\rm{e}}{^{x}}}$ ，
2. 所以曲线 $y=f\left ({x}\right )$ 在点 $\left ({t,f\left ({t}\right )}\right )$ 处的切线斜率 $k=\frac {1-t}{{\rm{e}}{^{t}}}$ ，
3. 切线方程为 $y-\frac {t}{{\rm{e}}{^{t}}}=\frac {1-t}{{\rm{e}}{^{t}}}\left ({x-t}\right )$ ，整理得 $y=\frac {1-t}{{\rm{e}}{^{t}}}x+\frac {t{^{2}}}{{\rm{e}}{^{t}}}$ ，
4. 所以当 $t=0$ 时，直线 $l$ 的方程为 $y=x$ .
5. （2）因为 $g\left ({x}\right )=f^{′}{\left ({x}\right )}=\frac {1-x}{{\rm{e}}{^{x}}}$ ， $x\in \mathbf{R}$ ，则 $g^{′}{\left ({x}\right )}=\frac {-{\rm{e}}{^{x}}-{\rm{e}}{^{x}}\left ({1-x}\right )}{{\rm{e}}{^{2x}}}=\frac {x-2}{{\rm{e}}{^{x}}}$ ，
6. 由 $g^{′}{\left ({x}\right )}>0$ 解得 $x>2$ ，由 $g^{′}{\left ({x}\right )}<0$ 解得 $x<2$ ，
7. 所以 $g\left ({x}\right )$ 在 $\left ({-\infty ,2}\right )$ 上单调递减，在 $\left ({2,+\infty }\right )$ 上单调递增，
8. 所以当 $x=2$ 时， $g\left ({x}\right )$ 取得最小值 $g\left ({2}\right )=-\frac {1}{{\rm{e}}{^{2}}}$ ，无最大值.
9. （3）由（1）得切线 $l$ 的方程为 $y=\frac {1-t}{{\rm{e}}{^{t}}}x+\frac {t{^{2}}}{{\rm{e}}{^{t}}}$ ，
10. 因为直线 $l$ 与曲线 $y=f\left ({x}\right )$ 相交于点 $\left ({s,f\left ({s}\right )}\right )$ ，且 $s<t$ ，
11. 所以关于 $x$ 的方程 $\frac {x}{{\rm{e}}{^{x}}}=\frac {1-t}{{\rm{e}}{^{t}}}x+\frac {t{^{2}}}{{\rm{e}}{^{t}}}$ 在 $\left ({-\infty ,t}\right )$ 有解，
12. 令 $F\left ({x}\right )=\frac {x}{{\rm{e}}{^{x}}}-\frac {1-t}{{\rm{e}}{^{t}}}x-\frac {t{^{2}}}{{\rm{e}}{^{t}}}\left ({x<t}\right )$ ，则 $F\left ({t}\right )=0,F^{′}{\left ({x}\right )}=\frac {1-x}{{\rm{e}}{^{x}}}-\frac {1-t}{{\rm{e}}{^{t}}},F^{′}{\left ({t}\right )}=0$ ，
13. 令 $h\left ({x}\right )=F^{′}{\left ({x}\right )}=\frac {1-x}{{\rm{e}}{^{x}}}-\frac {1-t}{{\rm{e}}{^{t}}}$ ，则 $h^{′}{\left ({x}\right )}=\frac {x-2}{{\rm{e}}{^{x}}}$ ，
14. ①当 $t>2$ 时，由 $h^{′}{\left ({x}\right )}>0$ ，得 $2<x<t$ ，由 $h^{′}{\left ({x}\right )}<0$ ，得 $x<2$ ，
15. 所以 $h\left ({x}\right )$ 在 $\left ({-\infty ,2}\right )$ 上单调递减，在 $\left ({2,t}\right )$ 上单调递增，
16. 所以 $h\left ({2}\right )<h\left ({t}\right )=0$ ，
17. 因为 $h\left ({1}\right )=-\frac {1-t}{{\rm{e}}{^{t}}}>0$ ，所以存在唯一实数 $x{{}_{0}}\in \left ({1,2}\right )$ ，使 $h\left ({x{{}_{0}}}\right )=0$ ，
18. 当 $x\in \left ({-\infty ,x{{}_{0}}}\right )$ 时， $h\left ({x}\right )>0$ ，则 $F^{′}{\left ({x}\right )}>0$ ，
19. 所以 $F\left ({x}\right )$ 在 $x\in \left ({-\infty ,x{{}_{0}}}\right )$ 上单调递增，
20. 当 $x\in \left ({x{{}_{0}},t}\right )$ 时， $h\left ({x}\right )<0$ ，则 $F^{′}{\left ({x}\right )}<0$ ，
21. 所以 $F\left ({x}\right )$ 在 $x\in \left ({x{{}_{0}},t}\right )$ 上单调递减，
22. 所以 $F\left ({x{{}_{0}}}\right )>F\left ({t}\right )=0$ ，
23. 因为 $F\left ({0}\right )=-\frac {t{^{2}}}{{\rm{e}}{^{t}}}<0$ ，所以存在唯一实数 $s\in \left ({0,x{{}_{0}}}\right )$ ，使 $F\left ({s}\right )=0$ ，
24. 所以 $t>2$ 符合题意；
25. ②当 $t\leqslant 2$ 时，由 $h^{′}{\left ({x}\right )}<0$ ，得 $x<t$ ，则 $h\left ({x}\right )$ 在 $\left ({-\infty ,t}\right )$ 上单调递减，
26. 所以 $h\left ({x}\right )>h\left ({t}\right )=0$ ，
27. 所以 $F\left ({x}\right )$ 在 $\left ({-\infty ,t}\right )$ 上单调递增，所以 $F\left ({x}\right )<F\left ({t}\right )=0$ ，
28. 所以 $F\left ({x}\right )$ 在 $\left ({-\infty ,t}\right )$ 上无零点，所以 $t\leqslant 2$ 不符合题意.
29. 综上 $t>2$ ，即实数 $t$ 的取值范围为 $\left ({2,+\infty }\right )$ .

## 知识点

**中文**:
  - 利用导数研究函数的图象
  - 导数几何意义的应用
  - 利用导数研究函数的最值

**English**:
  - Studying Function Graphs
  - Applications of Geometric Meaning of Derivatives
  - Global Extrema (Max/Min) using Derivatives

---
