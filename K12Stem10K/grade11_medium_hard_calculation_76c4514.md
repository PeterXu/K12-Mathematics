# Mathematics - 题目 365

**ID**: 76c4514da28549f0a118031d39d33df7
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\frac {x-a}{{\ln}x}$ .​​​​​​​‌（1）若 $f\left ({x}\right )$ 无单调递减区间，求 $a$ 的取值范围；（2）关于 $x$ 的方程 $f\left ({x}\right )=k$ 有两个不同的根 $x{{}_{1}}$ ， $x{{}_{2}}$ ，且 $x{{}_{1}}<x{{}_{2}}$ .${\rm （i）}$ 若 $a=0$ ，求 $k$ 的取值范围；${\rm （ii）}$ 若 $a>1$ ，记 $t=\frac {x{{}_{2}}}{x{{}_{1}}}$ .问：当 $k$ 取何值时， $t$ 取得最小值.

## 解答

1. （1）因为 $f\left ({x}\right )=\frac {x-a}{{\ln}x}$ ，其中 $x>0$ 且 $x\ne 1$ ，则 $f^{′}{\left ({x}\right )}=\frac {{\ln}x-\frac {x-a}{x}}{{\left({{\ln}x}\right)^{2}}}=\frac {{\ln}x+\frac {a}{x}-1}{{\left({{\ln}x}\right)^{2}}}$ ，
2. 因为函数 $f\left ({x}\right )$ 无单调递减区间，则对 $\forall x\in \left ({0,1}\right )\cup \left ({1,+\infty }\right )$ ， $f^{′}{\left ({x}\right )}=\frac {{\ln}x+\frac {a}{x}-1}{{\left({{\ln}x}\right)^{2}}}\geqslant 0$ ，
3. 即 ${\ln}x+\frac {a}{x}-1\geqslant 0$ ，可得 $a\geqslant x-x{\ln}x$ ，
4. 令 $g\left ({x}\right )=x-x{\ln}x$ ，其中 $x\in \left ({0,1}\right )\cup \left ({1,+\infty }\right )$ ，则 $g^{′}{\left ({x}\right )}=-{\ln}x$ ，
5. 当 $0<x<1$ 时， $g^{′}{\left ({x}\right )}>0$ ， $g\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上单调递增，
6. 当 $x>1$ 时， $g^{′}{\left ({x{{}_{0}}}\right )}<0$ ， $g\left ({x}\right )$ 在 $\left ({1,+\infty }\right )$ 上单调递减，
7. 所以 $a\geqslant g\left ({1}\right )=1-{\ln}1=1$ ，即实数 $a$ 的取值范围是 $\left [{1,+\infty }\right )$ .
8. （2）（i）当 $a=0$ 时，由 $f\left ({x}\right )=\frac {x}{{\ln}x}=k$ 可知，直线 $y=k$ 与函数 $f\left ({x}\right )$ 的图象有两个交点，
9. $f^{′}{\left ({x}\right )}=\frac {{\ln}x-1}{{\left({{\ln}x}\right)^{2}}}$ ，由 $f^{′}{\left ({x}\right )}=0$ 可得 $x={\rm{e}}$ ，列表如下：
10. $x$
11. $\left ({0,1}\right )$
12. $\left ({1,{\rm{e}}}\right )$
13. ${\rm{e}}$
14. $\left ({{\rm{e}},+\infty }\right )$
15. $f^{′}{\left ({x}\right )}$
16. $-$
17. $-$
18. $0$
19. $+$
20. $f\left ({x}\right )$
21. 减
22. 减
23. 极小值
24. 增
25. 故函数 $f\left ({x}\right )$ 的极小值为 $f\left ({{\rm{e}}}\right )={\rm{e}}$ ，
26. 且当 $0<x<1$ 时， $f\left ({x}\right )<0$ ；当 $x>1$ 时， $f\left ({x}\right )>0$ ，如图所示.
27. 
28. 由图可知，当 $k>{\rm{e}}$ 时，直线 $y=k$ 与函数 $f\left ({x}\right )$ 的图象有两个交点，
29. 故实数 $k$ 的取值范围是 $\left ({{\rm{e}},+\infty }\right )$ .
30. ${\rm （ii）}$ 由题意可得 $\begin{cases}\frac {x{{}_{1}}-a}{{\ln}x{{}_{1}}}=k,\\\frac {x{{}_{2}}-a}{{\ln}x{{}_{2}}}=k,\end{cases}$ 即 $\begin{cases}\frac {x{{}_{1}}-a}{k}={\ln}x{{}_{1}},\\\frac {x{{}_{2}}-a}{k}={\ln}x{{}_{2}},\end{cases}$ 且 $t=\frac {x{{}_{2}}}{x{{}_{1}}}>1$ ，
31. 可得 $\frac {x{{}_{2}}-x{{}_{1}}}{k}={\ln}x{{}_{2}}-{\ln}x{{}_{1}}={\ln}\frac {x{{}_{2}}}{x{{}_{1}}}$ ，即 $\frac {\left ({t-1}\right )x{{}_{1}}}{k}={\ln}t$ ，故 $\frac {{\ln}t}{t-1}=\frac {x{{}_{1}}}{k}=\frac {x{{}_{1}}{\ln}x{{}_{1}}}{x{{}_{1}}-a}$ ，
32. 因为 $f\left ({x}\right )=\frac {x-a}{{\ln}x}$ ，其中 $x>0$ 且 $x\ne 1$ ， $f^{′}{\left ({x}\right )}=\frac {{\ln}x+\frac {a}{x}-1}{{\left({{\ln}x}\right)^{2}}}$ ，
33. 令 $p\left ({x}\right )={\ln}x+\frac {a}{x}-1$ ，则 $p^{′}{\left ({x}\right )}=\frac {1}{x}-\frac {a}{x{^{2}}}=\frac {x-a}{x{^{2}}}$ ，
34. 当 $0<x<a$ 时， $p^{′}{\left ({x}\right )}<0$ ，即 $p\left ({x}\right )$ 在 $\left ({0,a}\right )$ 上单调递减，
35. 当 $x>a$ 时， $p^{′}{\left ({x}\right )}>0$ ，即 $p\left ({x}\right )$ 在 $\left ({a,+\infty }\right )$ 上单调递增，
36. 故 $p\left ({x}\right ){{}_{{\rm \min }}}=p\left ({a}\right )={\ln}a>0$ ，
37. 故 $f^{′}{\left ({x}\right )}>0$ ，即 $f\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上单调递增，在 $\left ({1,+\infty }\right )$ 上单调递增，
38. 因为 $a>1$ ，故当 $x\in \left ({0,1}\right )$ 时， $f\left ({x}\right )=\frac {x-a}{{\ln}x}>0$ ；当 $x\in \left ({1,a}\right )$ 时， $f\left ({x}\right )=\frac {x-a}{{\ln}x}<0$ ；
39. 当 $x\in \left ({a,+\infty }\right )$ 时， $f\left ({x}\right )=\frac {x-a}{{\ln}x}>0$ .故有 $0<x{{}_{1}}<1$ ， $x{{}_{2}}>a$ ，
40. 令 $q\left ({t}\right )=\frac {{\ln}t}{t-1}\left ({t>1}\right )$ ，则 $q^{′}{\left ({t}\right )}=\frac {\frac {t-1}{t}-{\ln}t}{{\left({t-1}\right)^{2}}}=\frac {1-\frac {1}{t}-{\ln}t}{{\left({t-1}\right)^{2}}}$ ，
41. 令 $m\left ({t}\right )=1-\frac {1}{t}-{\ln}t\left ({t>1}\right )$ ，则 $m^{′}{\left ({t}\right )}=\frac {1}{t{^{2}}}-\frac {1}{t}=\frac {1-t}{t{^{2}}}<0$ ，
42. 故函数 $m\left ({t}\right )$ 在 $\left ({1,+\infty }\right )$ 上单调递减，故 $m\left ({t}\right )<m\left ({1}\right )=0$ ，故 $q^{′}{\left ({t}\right )}<0$ ，
43. 故当 $t$ 取最小值时， $q\left ({t}\right )$ 取最大值，即 $\frac {x{{}_{1}}{\ln}x{{}_{1}}}{x{{}_{1}}-a}$ 在 $x{{}_{1}}\in \left ({0,1}\right )$ 时取最大值，
44. 令 $u\left ({x}\right )=\frac {x{\ln}x}{x-a}$ ，其中 $x\in \left ({0,1}\right )$ ，则 $u^{′}{\left ({x}\right )}=\frac {x-a{\ln}x-a}{{\left({x-a}\right)^{2}}}$ ，
45. 令 $v\left ({x}\right )=x-a{\ln}x-a$ ，则 $v^{′}{\left ({x}\right )}=1-\frac {a}{x}=\frac {x-a}{x}<0$ 对任意的 $x\in \left ({0,1}\right )$ 恒成立，
46. 即函数 $v\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上单调递减，
47. 当 $x\to 0$ 时， $v\left ({x}\right )\to +\infty $ ，且 $v\left ({1}\right )=1-a<0$ ，
48. 故存在 $x{{}_{0}}\in \left ({0,1}\right )$ ，使得 $v\left ({x{{}_{0}}}\right )=x{{}_{0}}-a{\ln}x{{}_{0}}-a=0$ ，
49. 当 $x\in \left ({0,x{{}_{0}}}\right )$ 时， $v\left ({x}\right )>0$ ， $u^{′}{\left ({x}\right )}>0$ ，即函数 $u\left ({x}\right )$ 在 $\left ({0,x{{}_{0}}}\right )$ 上单调递增，
50. 当 $x\in \left ({x{{}_{0}},1}\right )$ 时， $v\left ({x}\right )<0$ ， $u^{′}{\left ({x}\right )}<0$ ，即函数 $u\left ({x}\right )$ 在 $\left ({x{{}_{0}},1}\right )$ 上单调递减，
51. 所以 $u\left ({x}\right ){{}_{{\rm \max }}}=u\left ({x{{}_{0}}}\right )=\frac {x{{}_{0}}{\ln}x{{}_{0}}}{x{{}_{0}}-a}=\frac {x{{}_{0}}}{a}$ ，此时 $\frac {1}{k}=\frac {{\ln}x{{}_{0}}}{x{{}_{0}}-a}=\frac {1}{a}$ ，即 $k=a$ ，
52. 即当 $k=a$ 时， $t$ 取最小值.

## 知识点

**中文**:
  - 利用导数求函数中的参数
  - 利用导数研究函数的单调性与单调区间
  - 利用导数研究方程的根

**English**:
  - Finding Parameters using Derivatives
  - Monotonicity and Monotonic Intervals
  - Studying Equation Roots

---
