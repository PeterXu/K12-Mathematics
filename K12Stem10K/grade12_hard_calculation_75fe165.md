# Mathematics - 题目 1032

**ID**: 75fe16525c7d4c718a16c8243bdb0f42
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\left ({a-1}\right ){\rm{e}}{^{x}}-b{\rm{e}}{^{-x}}-ax\left ({a,b\in {\rm{R}}}\right )$ .​​​​​​​‌（1）当 $a=3$ ， $b=0$ 时，求曲线 $y=f\left ({x}\right )$ 在点 $\left ({0,f\left ({0}\right )}\right )$ 处的切线方程；（2）当 $b=1$ 时， $f\left ({x}\right )$ 既存在极大值，又存在极小值，求 $a$ 的取值范围；（3）当 $1<a<2$ ， $b=1$ 时， $x{{}_{1}}$ ， $x{{}_{2}}$ 分别为 $f\left ({x}\right )$ 的极大值点和极小值点，且 $f\left ({x{{}_{1}}}\right )+kf\left ({x{{}_{2}}}\right )>0$ ，求实数 $k$ 的取值范围.

## 解答

1. （1）函数 $f\left ({x}\right )=\left ({a-1}\right ){\rm{e}}{^{x}}-b{\rm{e}}{^{-x}}-ax\left ({a,b\in {\rm{R}}}\right )$ 的定义域为 ${\rm{R}}$ ，
2. 当 $a=3$ ， $b=0$ 时， $f\left ({x}\right )=2{\rm{e}}{^{x}}-3x$ ，
3. 则 $f^{′}{\left ({x}\right )}=2{\rm{e}}{^{x}}-3$ ，故 $f^{′}{\left ({0}\right )}=2-3=-1$ ，又 $f\left ({0}\right )=2$ ，
4. 所以曲线 $y=f\left ({x}\right )$ 在点 $\left ({0,f\left ({0}\right )}\right )$ 处的切线方程为 $y-2=-\left ({x-0}\right )$ ，即 $x+y-2=0$ .
5. （2）当 $b=1$ 时， $f\left ({x}\right )=\left ({a-1}\right ){\rm{e}}{^{x}}-{\rm{e}}{^{-x}}-ax$ ，定义域为 ${\rm{R}}$ ，
6. 所以 $f^{′}{\left ({x}\right )}=\left ({a-1}\right ){\rm{e}}{^{x}}+{\rm{e}}{^{-x}}-a=\frac {\left ({a-1}\right ){\rm{e}}{^{2x}}-a{\rm{e}}{^{x}}+1}{{\rm{e}}{^{x}}}=\frac {\left [\left ({a-1}\right ){\rm{e}}{^{x}}-1\right ]\left ({{\rm{e}}{^{x}}-1}\right )}{{\rm{e}}{^{x}}}$ ，
7. 因为 $f\left ({x}\right )$ 既存在极大值，又存在极小值，
8. 所以 $f^{′}{\left ({x}\right )}=0$ 必有两个不等的实数根，
9. 当 $a\leqslant 1$ 时，不符合题意，
10. 故 $a>1$ ，令 $f^{′}{\left ({x}\right )}=0$ ，解得 $x{{}_{1}}=0$ 或 $x{{}_{2}}=-{\ln}\left ({a-1}\right )$ 且 $-{\ln}\left ({a-1}\right )\ne 0$
11. 所以 $a>1$ 且 $a\ne 2$ ，
12. 当 $1<a<2$ 时， $x{{}_{1}}<x{{}_{2}}$ ，
13. 当 $x<x{{}_{1}}$ 时， $f^{′}{\left ({x}\right )}>0$ ， $f\left ({x}\right )$ 单调递增；
14. 当 $x{{}_{1}}<x<x{{}_{2}}$ 时， $f^{′}{\left ({x}\right )}<0$ ， $f\left ({x}\right )$ 单调递减；
15. 当 $x\mathrm{>}x{{}_{2}}$ 时， $f^{′}{\left ({x}\right )}>0$ ， $f\left ({x}\right )$ 单调递增；
16. 所以函数 $f\left ({x}\right )$ 分别在 $x=x{{}_{1}}$ ， $x=x{{}_{2}}$ 时取到极大值和极小值，满足题意，
17. 当 $a>2$ 时， $x{{}_{1}}>x{{}_{2}}$ ，
18. 当 $x<x{{}_{2}}$ 时， $f^{′}{\left ({x}\right )}>0$ ， $f\left ({x}\right )$ 单调递增；
19. 当 $x{{}_{2}}<x<x{{}_{1}}$ 时， $f^{′}{\left ({x}\right )}<0$ ， $f\left ({x}\right )$ 单调递减；
20. 当 $x>x{{}_{1}}$ 时， $f^{′}{\left ({x}\right )}>0$ ， $f\left ({x}\right )$ 单调递增；
21. 所以函数 $f\left ({x}\right )$ 分别在 $x=x{{}_{2}}$ ， $x=x{{}_{1}}$ 时取到极大值和极小值，满足题意，
22. 综上， $a$ 的取值范围为 $\left ({1,2}\right )\cup \left ({2,+\infty }\right )$ .
23. （3）由（2）知， $x{{}_{1}}=0$ 或 $x{{}_{2}}=-{\ln}\left ({a-1}\right )$ ，
24. 所以 $f\left ({x{{}_{1}}}\right )=f\left ({0}\right )=a-1-1=a-2$ ，
25. $f\left ({x{{}_{2}}}\right )=f\left ({-{\ln}\left ({a-1}\right )}\right )=\left ({a-1}\right ){\rm{e}}{^{-{\ln}\left ({a-1}\right )}}-{\rm{e}}{^{{\ln}\left ({a-1}\right )}}+a{\ln}\left ({a-1}\right )=2-a+a{\ln}\left ({a-1}\right )$ ，
26. 由题意，得 $a-2+k\left [2-a+a{\ln}\left ({a-1}\right )\right ]>0$ 对任意的 $a\in \left ({1,2}\right )$ 恒成立，
27. 因为当 $1<a<2$ 时， $f\left ({x}\right )$ 在 $\left ({0,-{\ln}\left ({a-1}\right )}\right )$ 上单调递减，
28. 所以 $f\left ({x{{}_{2}}}\right )-f\left ({x{{}_{1}}}\right )<0$ ，故 $f\left ({x{{}_{2}}}\right )<f\left ({x{{}_{1}}}\right )<0$ ，
29. 所以 $k<0$ ，且 $ka{\ln}\left ({a-1}\right )>\left ({k-1}\right )\left ({a-2}\right )$ ，则 ${\ln}\left ({a-1}\right )<\frac {\left ({k-1}\right )\left ({a-2}\right )}{ka}=\left ({1-\frac {1}{k}}\right )\cdot \frac {a-2}{a}$ .
30. 令 $g\left ({x}\right )={\ln}x-\left ({1-\frac {1}{k}}\right )\cdot \frac {x-1}{x+1}$ ，其中 $0<x<1$ ，
31. 所以 $g^{′}{\left ({x}\right )}=\frac {1}{x}-\left ({1-\frac {1}{k}}\right )\cdot \frac {2}{{\left({x+1}\right)^{2}}}=\frac {{\left({x+1}\right)^{2}}-2x\left ({1-\frac {1}{k}}\right )}{x{\left({x+1}\right)^{2}}}=\frac {x{^{2}}+\frac {2}{k}x+1}{x{\left({x+1}\right)^{2}}}$ ，
32. 令 $x{^{2}}+\frac {2}{k}x+1=0$ ，则 $Δ=\frac {4}{k{^{2}}}-4=\frac {4\left ({1-k{^{2}}}\right )}{k{^{2}}}$ ，
33. 当 $\Delta \leqslant 0$ ，即 $k\leqslant -1$ 时， $g^{′}{\left ({x}\right )}\geqslant 0$ ， $g\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上单调递增，
34. 所以 $g\left ({x}\right )<g\left ({1}\right )=0$ ，即 ${\ln}\left ({a-1}\right )<\left ({1-\frac {1}{k}}\right )\cdot \frac {a-2}{a}$ ，符合题意，
35. 当 $\Delta >0$ ，即 $-1<k<0$ 时，设方程 $x{^{2}}+\frac {2}{k}x+1=0$ 的两根分别为 $x{{}_{3}}$ ， $x{{}_{4}}$ ，
36. 则 $x{{}_{3}}+x{{}_{4}}=-\frac {2}{k}>0$ ， $x{{}_{3}}x{{}_{4}}=1$ ，不妨设 $0<x{{}_{3}}<1<x{{}_{4}}$ ，
37. 当 $x{{}_{3}}<x<1$ 时， $g^{′}{\left ({x}\right )}<0$ ， $g\left ({x}\right )$ 在 $\left ({x{{}_{3}},1}\right )$ 上单调递减，
38. 所以当 $x{{}_{3}}<x<1$ 时， $g\left ({x}\right )>g\left ({1}\right )=0$ ，即 ${\ln}\left ({a-1}\right )>\left ({1-\frac {1}{k}}\right )\cdot \frac {a-2}{a}$ ，不合题意，
39. 综上所述， $k$ 的取值范围为 $\left ({-\infty ,-1}\right ]$ .

## 知识点

**中文**:
  - 利用导数研究函数的极值
  - 导数几何意义的应用

**English**:
  - Extrema of Functions using Derivatives
  - Applications of Geometric Meaning of Derivatives

---
