# Mathematics - 题目 1693

**ID**: 3486e6fb78e4457e942eac44415a8e2e
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=x{^{3}}+ax{^{2}}+bx+c$ ．(1)如果1和 $-1$ 是 $f\left ({x}\right )$ 的两个极值点，且 $f\left ({x}\right )$ 的极大值为3，求 $f\left ({x}\right )$ 的极小值；​​​​​​​‌(2)当 $b=0$ 时，讨论 $f\left ({x}\right )$ 的单调性；(3)当 $c=0$ 时，且函数 $f\left ({x}\right )$ 在区间 $\left [-2,2\right ]$ 上最大值为2，最小值为 $-2$ ．求 $f\left ({3}\right )$ 的值．

## 解答

1. （1）因为 $f\left ({x}\right )=x{^{3}}+ax{^{2}}+bx+c$ ，所以 $f^{′}{\left ({x}\right )}=3x{^{2}}+2ax+b$ ，
2. 因为 $1$ 和 $-1$ 是 $f\left ({x}\right )$ 的两个极值点，所以 $1$ 和 $-1$ 是方程 $3x{^{2}}+2ax+b=0$ 的两根，
3. 故 $\begin{cases}-1+1=-\frac {2a}{3}\\-1\times 1=\frac {b}{3}\end{cases}$ ，解得 $\begin{cases}a=0\\b=-3\end{cases}$ ，即 $f\left ({x}\right )=x{^{3}}-3x+c$ ，
4. 所以 $f^{′}{\left ({x}\right )}=3x{^{2}}-3=3\left ({x+1}\right )\left ({x-1}\right )$ ，
5. 因为 $x\in \left ({-\infty ,-1}\right )\cup \left ({1,\infty }\right )$ 时， $f^{′}{\left ({x}\right )}>0$ ，当 $x\in \left ({-1,1}\right )$ 时， $f^{′}{\left ({x}\right )}<0$ ，
6. 所以 $f\left ({x}\right )$ 在区间 $\left ({-\infty ,-1}\right ),\left ({1,\infty }\right )$ 上单调增，在区间 $\left ({-1,1}\right )$ 上单调减，
7. 所以 $f\left ({x}\right ){{}_{极大值}}=f\left ({-1}\right )=-1+3+c=3$ ，解得 $c=1$ ，
8. 所以 $f\left ({x}\right ){{}_{极小值}}=f\left ({1}\right )=1-3+1=-1$ ．
9. （2）当 $b=0$ 时 $f\left ({x}\right )=x{^{3}}+ax{^{2}}+c$ 定义域为 ${\rm{R}}$ ，
10. 又 $f{^{\prime }}\left ({x}\right )=3x{^{2}}+2ax$ ，令 $f^{′}{\left ({x}\right )}=0$ ，解得 $x=0$ 或 $x=-\frac {2a}{3}$ ，
11. 若 $a<0$ ，则当 $x\in \left ({-\infty ,0}\right )\cup \left ({-\frac {2a}{3},+\infty }\right )$ 时， $f^{′}{\left ({x}\right )}>0$ ；当 $x\in \left ({0,-\frac {2a}{3}}\right )$ 时， $f^{′}{\left ({x}\right )}<0$ ．
12. 故 $f\left ({x}\right )$ 在区间 $\left ({-\infty ,0}\right ),\left ({-\frac {2a}{3},+\infty }\right )$ 单调递增，在 $\left ({0,-\frac {2a}{3}}\right )$ 上单调递减；
13. 若 $a=0$ ，则 $f^{′}{\left ({x}\right )}\geqslant 0$ 恒成立，所以 $f\left ({x}\right )$ 在区间 $\left ({-\infty ,+\infty }\right )$ 单调递增；
14. 若 $a>0$ ，则当 $x\in \left ({-\infty ,-\frac {2a}{3}}\right )\cup \left ({0,+\infty }\right )$ 时， $f^{′}{\left ({x}\right )}>0$ ；当 $x\in \left ({-\frac {2a}{3},0}\right )$ 时， $f^{′}{\left ({x}\right )}<0$ ．
15. 故 $f\left ({x}\right )$ 在区间 $\left ({-\infty ,-\frac {2a}{3}}\right ),\left ({0,+\infty }\right )$ 单调递增，在 $\left ({-\frac {2a}{3},0}\right )$ 上单调递减．
16. 综上可得：当 $a<0$ 时 $f\left ({x}\right )$ 在区间 $\left ({-\infty ,0}\right ),\left ({-\frac {2a}{3},+\infty }\right )$ 单调递增，在 $\left ({0,-\frac {2a}{3}}\right )$ 上单调递减；
17. 当 $a=0$ 时 $f\left ({x}\right )$ 在区间 $\left ({-\infty ,+\infty }\right )$ 单调递增；
18. 当 $a>0$ 时 $f\left ({x}\right )$ 在区间 $\left ({-\infty ,-\frac {2a}{3}}\right ),\left ({0,+\infty }\right )$ 单调递增，在 $\left ({-\frac {2a}{3},0}\right )$ 上单调递减．
19. （3）当 $c=0$ 时， $f\left ({x}\right )=x{^{3}}+ax{^{2}}+bx$ ，
20. 由题意得： $-2\leqslant f\left ({2}\right )=8+4a+2b\leqslant 2$ ，即 $-5\leqslant 2a+b\leqslant -3$ ，①
21. $-2\leqslant f\left ({-2}\right )=-8+4a-2b\leqslant 2$ ，即 $3\leqslant 2a-b\leqslant 5$ ，②
22. 由①、②可知， $-\frac {1}{4}\leqslant a\leqslant \frac {1}{4}$ ， $-5\leqslant b\leqslant -3$ ．③
23. 因为 $f^{′}{\left ({x}\right )}=3x{^{2}}+2ax+b$ ， $f^{′}{\left ({-2}\right )}=12-4a+b\geqslant 12-1-5=6>0$ ，
24. $f^{′}{\left ({0}\right )}=b<0$ ， $f^{′}{\left ({2}\right )}=12+4a+b\geqslant 12-1-5=6>0$ ，
25. 所以 $f^{′}{\left ({x}\right )}=0$ 有两个实数根 $x{{}_{1}},x{{}_{2}}$ ，且 $-2<x{{}_{1}}<0<x{{}_{2}}<2$ ，
26. 当 $x\in \left ({-2,x{{}_{1}}}\right )\cup \left ({x{{}_{2}},2}\right )$ 时， $f^{′}{\left ({x}\right )}>0$ ，当 $x\in \left ({x{{}_{1}},x{{}_{2}}}\right )$ 时， $f^{′}{\left ({x}\right )}<0$ ，
27. 故 $x{{}_{1}}$ 是 $f\left ({x}\right )$ 的极大值点， $x{{}_{2}}$ 是 $f\left ({x}\right )$ 的极小值点．
28. 由题意得 $f\left ({x{{}_{1}}}\right )=x{{}_{1}^{3}}+ax{{}_{1}^{2}}+bx{{}_{1}}\leqslant 2$ ， $f\left ({x{{}_{2}}}\right )=x{{}_{2}^{3}}+ax{{}_{2}^{2}}+bx{{}_{2}}\geqslant -2$ ，
29. 即 $-f\left ({x{{}_{2}}}\right )=-\left ({x{{}_{2}^{3}}+ax{{}_{2}^{2}}+bx{{}_{2}}}\right )\leqslant 2$ ，
30. 两式同向相加得： $\left ({x{{}_{1}}-x{{}_{2}}}\right )\left [{\left({x{{}_{1}}+x{{}_{2}}}\right)^{2}}-x{{}_{1}}x{{}_{2}}+a\left ({x{{}_{1}}+x{{}_{2}}}\right )+b\right ]\leqslant 4$ ，④
31. 注意到 $x{{}_{1}}+x{{}_{2}}=-\frac {2a}{3}$ ， $x{{}_{1}}x{{}_{2}}=\frac {b}{3}$ ， $x{{}_{1}}-x{{}_{2}}=-\frac {\sqrt {4a{^{2}}-12b}}{3}$ ，
32. 代入④得 $\frac {\sqrt {4a{^{2}}-12b}}{3}\left ({\frac {a{^{2}}}{9}-\frac {b}{3}}\right )\leqslant 2$ ，
33. 由③可知 $-\frac {1}{4}\leqslant a\leqslant \frac {1}{4}$ ， $-5\leqslant b\leqslant -3$ ，则 $36\leqslant 4a{^{2}}-12b\leqslant 60\frac {1}{4}$ ， $1\leqslant \frac {a{^{2}}}{9}-\frac {b}{3}\leqslant \frac {5}{3}+\frac {1}{9\times 16}$ ，
34. 所以 $\frac {\sqrt {4a{^{2}}-12b}}{3}\geqslant 2$ ， $\left ({\frac {a{^{2}}}{9}-\frac {b}{3}}\right )\geqslant 1$ ，
35. 所以 $\frac {\sqrt {4a{^{2}}-12b}}{3}\left ({\frac {a{^{2}}}{9}-\frac {b}{3}}\right )\geqslant 2$ ，
36. 所以 $\frac {\sqrt {4a{^{2}}-12b}}{3}\left ({\frac {a{^{2}}}{9}-\frac {b}{3}}\right )=2$ ，当且仅当 $\begin{cases}\frac {\sqrt {4a{^{2}}-12b}}{3}=2\\\frac {a{^{2}}}{9}-\frac {b}{3}=1\end{cases}$ ，
37. 即 $a{^{2}}-3b=9$ ，又 $-5\leqslant b\leqslant -3$ ，所以 $a=0,b=-3$ 时成立，
38. 所以 $f\left ({x}\right )=x{^{3}}-3x$ ，从而 $f\left ({3}\right )=18$ ．

## 知识点

**中文**:
  - 利用导数研究函数的单调性与单调区间
  - 利用导数研究函数的极值
  - 利用导数研究函数的最值

**English**:
  - Monotonicity and Monotonic Intervals
  - Extrema of Functions using Derivatives
  - Global Extrema (Max/Min) using Derivatives

---
