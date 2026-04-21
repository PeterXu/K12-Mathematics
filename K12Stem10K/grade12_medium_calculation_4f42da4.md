# Mathematics - 题目 698

**ID**: 4f42da4657984f96934b63810628d9b6
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
已知 $f\left ({x}\right )=\left ({ax{^{2}}+x+1}\right ){\rm{e}}{^{x}}$ .​​​​​​​‌（1）若 $a=0$${\rm （i）}$ 过点 $P\left ({m,0}\right )$ 作曲线 $y=f\left ({x}\right )$ 的两条切线，求 $m$ 的取值范围；${\rm （ii）}$ 求不等式 $f\left ({x}\right )\geqslant x{^{2}}+3x+2$ 的解集；（2）若 $f\left ({x}\right )$ 在区间 $\left ({-3,-1}\right )$ 内存在极小值点，求 $a$ 的取值范围.

## 解答

1. （1）当 $a=0$ 时， $f\left ({x}\right )=\left ({x+1}\right ){\rm{e}}{^{x}}$ ，
2. ${\rm （i）}f^{′}{\left ({x}\right )}=\left ({x+2}\right ){\rm{e}}{^{x}}$ ，设切点为 $\left ({x,\left ({x+1}\right ){\rm{e}}{^{x}}}\right )$
3. $\therefore \left ({x+2}\right ){\rm{e}}{^{x}}=\frac {\left ({x+1}\right ){\rm{e}}{^{x}}}{x-m}$ ，整理得 $x{^{2}}+\left ({1-m}\right )x-2m-1={\rm 0}$ ，
4. 问题转化为方程 $x{^{2}}+\left ({1-m}\right )x-2m-1=0$ 有两个实数根，
5. $\therefore {\rm{Δ}}=(1-m){^{2}}+4\left ({2m+1}\right )=m{^{2}}+6m+5>0$ ，
6. $\therefore m<-5$ 或 $m>-1$ .
7. $\therefore m$ 的取值范围为 $\left ({-∞,-5}\right )\cup \left ({-1,+∞}\right )$ .
8. ${\rm （ii）}f\left ({x}\right )-\left ({x{^{2}}+3x+2}\right )=\left ({x+1}\right )\left ({{\rm{e}}{^{x+1}}-x-2}\right )$ .
9. 令 $g\left ({x}\right )={\rm{e}}{^{x+1}}-x-2,x\in {\mathbf{R}}$ ，则 $g^{′}{\left ({x}\right )}={\rm{e}}{^{x+1}}-1$ ，
10. 由 $g^{′}{\left ({x}\right )}=0$ ，得 $x=-1$ ，
11. 当 $x\in \left ({-∞,-1}\right )$ 时， $g^{′}{\left ({x}\right )}<0,g\left ({x}\right )$ 单调递减，
12. 当 $x\in \left ({-1,+∞}\right )$ 时， $g^{′}{\left ({x}\right )}>0,g\left ({x}\right )$ 单调递增，则 $g\left ({x}\right )\geqslant g\left ({-1}\right )=0$ .
13. 故当 $x<-1$ 时， $\left ({x+1}\right )\left ({{\rm{e}}{^{x+1}}-x-2}\right )<0$ ，当 $x\geqslant -1$ 时， $\left ({x+1}\right )\left ({{\rm{e}}{^{x+1}}-x-2}\right )\geqslant 0$ ，
14. 从而原不等式的解集为 $\left [{-1,+\infty }\right )$ .
15. （2）由已知得 $f^{′}{\left ({x}\right )}=\left ({ax{^{2}}+x+1+2ax+1}\right ){\rm{e}}{^{x}}=\left ({x+2}\right )\left ({ax+1}\right ){\rm{e}}{^{x}}$
16. 1．若 $a=0,f^{′}{\left ({x}\right )}=\left ({x+2}\right ){\rm{e}}{^{x}}$ ，
17. 当 $x\in \left ({-∞,-2}\right )$ 时， $f^{′}{\left ({x}\right )}<0,f\left ({x}\right )$ 在 $\left ({-∞,-2}\right )$ 上单调递减，
18. 当 $x\in \left ({-2,+∞}\right )$ 时， $f^{′}{\left ({x}\right )}>0,f\left ({x}\right )$ 在 $\left ({-2,+∞}\right )$ 上单调递增，
19. $\therefore y=f\left ({x}\right )$ 在 $x=-2$ 取得最小值，符合题意.
20. 2．若 $a>0$ ，
21. i）若 $-\frac {1}{a}\mathrm{>}-2$ 即 $a>\frac {1}{2}$ ，
22. 当 $x\in \left ({-2,-\frac {1}{a}}\right ),f^{′}{\left ({x}\right )}<0,\therefore f\left ({x}\right )$ 在 $\left ({-2,-\frac {1}{a}}\right )$ 上单调递减，
23. 当 $x\in \left ({-\frac {1}{a},+∞}\right ),f^{′}{\left ({x}\right )}>0,\therefore f\left ({x}\right )$ 在 $\left ({-\frac {1}{a},+∞}\right )$ 上单调递增，
24. $\therefore y=f\left ({x}\right )$ 在 $x=-\frac {1}{a}$ 取得最小值， $-\frac {1}{a}<-1,a<1,\therefore \frac {1}{2}<a<1$
25. ii）当 $-\frac {1}{a}=-2,f^{′}{\left ({x}\right )}=(x+2){^{2}}{\rm{e}}{^{x}}\geqslant 0,\therefore y=f\left ({x}\right )$ 无极值，不符合题意，
26. iii）当 $-\frac {1}{a}\mathrm{<}-2$ 即 $a\in \left ({0,\frac {1}{2}}\right )$ ，
27. 当 $x\in \left ({-\frac {1}{a},-2}\right ),f^{′}{\left ({x}\right )}<0,\therefore f\left ({x}\right )$ 在 $\left ({-\frac {1}{a},-2}\right )$ 上单调递减，
28. 当 $x\in \left ({-2,+∞}\right ),f^{′}{\left ({x}\right )}>0,\therefore f\left ({x}\right )$ 在 $\left ({-2,+∞}\right )$ 上单调递增，
29. $\therefore f\left ({x}\right )$ 在 $x=-2$ 取得极小值符合.
30. 3．若 $a<0,-\frac {1}{a}>0$ ，
31. 当 $x\in \left ({-∞,-2}\right )$ 时， $f^{′}{\left ({x}\right )}<0,\therefore f\left ({x}\right )$ 在 $\left ({-∞,-2}\right )$ 上单调递减，
32. 当 $x\in \left ({-2,-\frac {1}{a}}\right )$ 时， $f^{′}{\left ({x}\right )}>0,\therefore f\left ({x}\right )$ 在 $\left ({-2,-\frac {1}{a}}\right )$ 上单调递增，
33. $\therefore y=f\left ({x}\right )$ 在 $x=-2$ 取得极小值，符合题意；
34. 综上所述： $a$ 的取值范围为 $\left ({-∞,\frac {1}{2}}\right )\cup \left ({\frac {1}{2},1}\right )$ .

## 知识点

**中文**:
  - 利用导数研究函数的图象
  - 导数几何意义的应用
  - 利用导数研究函数的极值

**English**:
  - Studying Function Graphs
  - Applications of Geometric Meaning of Derivatives
  - Extrema of Functions using Derivatives

---
