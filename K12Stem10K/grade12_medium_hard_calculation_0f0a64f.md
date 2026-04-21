# Mathematics - 题目 1350

**ID**: 0f0a64f49d2a40098191bc61c19739df
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=x{\rm{l}}{\rm{n}}x-2x-\frac {a}{x}\left ({a\in {\mathbf{R}}}\right )$ .​​​​​​​‌（1）证明：曲线 $y=f\left ({x}\right )$ 在点 $\left ({1,f\left ({1}\right )}\right )$ 处的切线恒过定点，并求出该定点坐标；（2）若存在 $x{{}_{1}}<x{{}_{2}}<x{{}_{3}}$ 使得 $f\left ({x{{}_{1}}}\right )=f\left ({x{{}_{2}}}\right )=f\left ({x{{}_{3}}}\right )$ ，记 $f\left ({x}\right )$ 的导函数为 $f^{′}{\left ({x}\right )}$ .${\rm （i）}$ 求 $a$ 的取值范围；${\rm （ii）}$ 证明： $f^{′}{\left ({x{{}_{1}}}\right )}+f^{′}{\left ({x{{}_{2}}}\right )}>0$ .

## 解答

1. （1）由题意可知：函数 $f\left ({x}\right )$ 的定义域为 $\left ({0,+∞}\right )$ ，且 $f^{′}{\left ({x}\right )}={\rm{l}}{\rm{n}}x-1+\frac {a}{x{^{2}}}$ ，
2. 则 $f\left ({1}\right )=-a-2$ ， $f^{′}{\left ({1}\right )}=a-1$ ，即切点坐标为 $\left ({1,-a-2}\right )$ ，切线斜率 $k=a-1$ ，
3. 所求切线方程为 $y+a+2=\left ({a-1}\right )\left ({x-1}\right )$ ，即 $a\left ({x-2}\right )-\left ({x+y+1}\right )=0$ ，
4. 令 $\begin{cases}x-2=0\\x+y+1=0\end{cases}$ ，解得 $\begin{cases}\begin{matrix}x=2\\y=-3\end{matrix}\end{cases}$ ，
5. 所以切线恒过定点 $\left ({2,-3}\right )$ .
6. （2）构建 $t\left ({x}\right )={\ln}x+\frac {1}{x}-1,x>0$ ，则 $t^{′}{\left ({x}\right )}=\frac {1}{x}-\frac {1}{x{^{2}}}=\frac {x-1}{x{^{2}}}$ ，
7. 当 $0<x<1$ 时， $t^{′}{\left ({x}\right )}<0$ ；当 $x>1$ 时， $t^{′}{\left ({x}\right )}>0$ ；
8. 可知 $t\left ({x}\right )$ 在 $\left ({0,1}\right )$ 内单调递减，在 $\left ({1,+∞}\right )$ 内单调递增，
9. 则 $t\left ({x}\right )\geqslant t\left ({1}\right )=0$ ，所以 ${\ln}x-1\mathrm{\geqslant }-\frac {1}{x}$ .
10. ${\rm （i）}$ 构建 $g\left ({x}\right )=f^{′}{\left ({x}\right )},x>0$ ，则 $g^{′}{\left ({x}\right )}=\frac {1}{x}-\frac {2a}{x{^{3}}}=\frac {x{^{2}}-2a}{x{^{3}}}$ ，
11. ①若 $a\leqslant 0$ ，则 $g^{′}{\left ({x}\right )}>0$ ，可知 $g\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 内单调递增，
12. 且 $g\left ({1}\right )=-1+a<0$ ，当 $x$ 趋近于 $+\infty $ 时， $g\left ({x}\right )$ 趋近于 $+\infty $ ，
13. 可知 $g\left ({x}\right )$ 在定义域 $\left ({0,+∞}\right )$ 内存在唯一零点 $x{{}_{0}}$ ，
14. 当 $0<x<x{{}_{0}}$ 时， $g\left ({x}\right )<0$ ，即 $f^{′}{\left ({x}\right )}<0$ ；当 $x>x{{}_{0}}$ 时， $g\left ({x}\right )>0$ ，即 $f^{′}{\left ({x}\right )}>0$ ；
15. 可知 $f\left ({x}\right )$ 在 $\left ({0,x{{}_{0}}}\right )$ 内单调递减，在 $\left ({x{{}_{0}},+∞}\right )$ 内单调递增，
16. 则至多存在两个实数 $m,n$ ，使得 $f\left ({m}\right )=f\left ({n}\right )$ ，不合题意；
17. ②若 $a>0$ ，令 $g^{′}{\left ({x}\right )}>0$ ，解得 $x>\sqrt {2a}$ ；令 $g^{′}{\left ({x}\right )}<0$ ，解得 $0<x<\sqrt {2a}$ ；
18. 可知 $g\left ({x}\right )$ 在 $\left ({0,\sqrt {2a}}\right )$ 内单调递减，在 $\left ({\sqrt {2a},+∞}\right )$ 内单调递增，
19. 则 $g\left ({x}\right )\geqslant g\left ({\sqrt {2a}}\right )=\frac {-1+{\ln}2a}{2}$ ，即 $f^{′}{\left ({x}\right )}\geqslant f^{′}{\left ({\sqrt {2a}}\right )}=\frac {-1+{\ln}2a}{2}$ ，
20. 若 $a\geqslant \frac {{\rm{e}}}{2}$ ，则 $\frac {-1+{\ln}2a}{2}\geqslant 0$ ，即 $f^{′}{\left ({x}\right )}\geqslant 0$ ，
21. 可知 $f\left ({x}\right )$ 在定义域 $\left ({0,+∞}\right )$ 内单调递增，不合题意；
22. 若 $0<a<\frac {{\rm{e}}}{2}$ ，则 $\frac {-1+{\ln}2a}{2}<0$ ，
23. 当 $0<x<a$ 时，则 $f^{′}{\left ({x}\right )}\geqslant -\frac {1}{x}+\frac {a{^{2}}}{x{^{2}}}=\frac {a{^{2}}-x}{x{^{2}}}>0$ ；
24. 当 $x>{\rm{e}}$ 时，则 $f^{′}{\left ({x}\right )}\geqslant \frac {a{^{2}}}{x{^{2}}}>0$ ；
25. 可知 $f^{′}{\left ({x}\right )}$ 在 $\left ({0,\sqrt {2a}}\right )$ 和 $\left ({\sqrt {2a},+∞}\right )$ 内分别存在一个零点 $p,q\left ({0<p<\sqrt {2a}<q}\right )$ ，
26. 当 $x\in \left ({0,p}\right )\cup \left ({q,+∞}\right )$ 时， $f^{′}{\left ({x}\right )}>0$ ；当 $x\in \left ({p,q}\right )$ 时， $f^{′}{\left ({x}\right )}<0$ ；
27. 可知 $f\left ({x}\right )$ 在 $\left ({0,p}\right ),\left ({q,+∞}\right )$ 内单调递增，在 $\left ({p,q}\right )$ 内单调递减，
28. 且当 $x$ 趋近于0时， $f\left ({x}\right )$ 趋近于 $-\infty $ ，当 $x$ 趋近于 $+\infty $ 时， $f\left ({x}\right )$ 趋近于 $+\infty $ ，符合题意；
29. 综上所述：实数 $a$ 的取值范围 $\left ({0,\frac {{\rm{e}}}{2}}\right )$ ；
30. ${\rm （ii）}$ 设 $m=\frac {x{{}_{1}}+x{{}_{2}}}{2}$ ，构建 $h\left ({x}\right )=f\left ({m+x}\right )-f\left ({m-x}\right ),x\in \left [0,\frac {x{{}_{2}}-x{{}_{1}}}{2}\right ]$ ，
31. 则 $h\left ({0}\right )=h\left ({\frac {x{{}_{2}}-x{{}_{1}}}{2}}\right )=0$ ，
32. 记 $f^{′}{\left ({x}\right )}$ 的导函数为 $f^{′′}{\left ({x}\right )}$ ， $f^{′′}{\left ({x}\right )}$ 的导函数为 $f{^{\prime \prime \prime }}\left ({x}\right )$ ，
33. 且 $h^{′}{\left ({x}\right )}$ 的导函数为 $h{^{^{′′}}}\left ({x}\right )$ ， $h{^{^{′′}}}\left ({x}\right )$ 的导函数为 $h{^{\prime \prime \prime }}\left ({x}\right )$ ，
34. 则 $h^{′}{\left ({x}\right )}=f^{′}{\left ({m+x}\right )}+f^{′}{\left ({m-x}\right )}$ ，且 $h^{′}{\left ({\frac {x{{}_{2}}-x{{}_{1}}}{2}}\right )}=f^{′}{\left ({x{{}_{1}}}\right )}+f^{′}{\left ({x{{}_{2}}}\right )}$ ，
35. 因为 $h^{′′}{\left ({x}\right )}=f^{′′}{\left ({m+x}\right )}-f^{′′}{\left ({m-x}\right )}$ ，且 $h^{′′}{\left ({0}\right )}=0$ ，
36. 又因为 $h{^{\prime \prime \prime }}\left ({x}\right )=f{^{\prime \prime \prime }}\left ({m+x}\right )+f{^{\prime \prime \prime }}\left ({m-x}\right )$ ，
37. 且 $f{^{\prime \prime \prime }}\left ({x}\right )=-\frac {1}{x{^{2}}}+\frac {6a}{x{^{4}}}=\frac {6a-x{^{2}}}{x{^{4}}}\geqslant 0$ 在 $x\in \left ({0,\sqrt {6a}}\right ]$ 内恒成立，
38. 若 $0<x{{}_{2}}\leqslant \sqrt {6a}$ ，则 $f{^{\prime \prime \prime }}\left ({x}\right )\geqslant 0$ ，可得 $h{^{\prime \prime \prime }}\left ({x}\right )>0$ ，
39. 可知 $h^{′′}{\left ({x}\right )}$ 在 $\left [0,\frac {x{{}_{2}}-x{{}_{1}}}{2}\right ]$ 内单调递增，则 $h^{′′}{\left ({x}\right )}\geqslant h^{′′}{\left ({0}\right )}=0$ ，
40. 可知 $h^{′}{\left ({x}\right )}$ 在 $\left [0,\frac {x{{}_{2}}-x{{}_{1}}}{2}\right ]$ 内单调递增，则 $h^{′}{\left ({x}\right )}\leqslant h^{′}{\left ({\frac {x{{}_{2}}-x{{}_{1}}}{2}}\right )}$ ，
41. 若 $h^{′}{\left ({\frac {x{{}_{2}}-x{{}_{1}}}{2}}\right )}\leqslant 0$ ，则 $h^{′}{\left ({x}\right )}\leqslant 0$ ，可知 $h\left ({x}\right )$ 在 $\left [0,\frac {x{{}_{2}}-x{{}_{1}}}{2}\right ]$ 内单调递增，不合题意；
42. 所以 $h^{′}{\left ({\frac {x{{}_{2}}-x{{}_{1}}}{2}}\right )}=f^{′}{\left ({x{{}_{1}}}\right )}+f^{′}{\left ({x{{}_{2}}}\right )}>0$ ；
43. 若 $x{{}_{2}}>\sqrt {6a}$ ，由 ${\rm （i）}$ 可知：直线 $y=f\left ({\sqrt {2a}}\right )$ 与 $y=f\left ({x}\right )$ 在 $\left ({0,\sqrt {2a}}\right )$ 内存在唯一交点横坐标为 $x{{}_{4}}$ ，
44. 则 $f\left ({x{{}_{1}}}\right )=f\left ({x{{}_{2}}}\right )<f\left ({\sqrt {2a}}\right )=f\left ({x{{}_{4}}}\right )$ ，由单调性可得 $x{{}_{1}}<x{{}_{4}}$ ，
45. 可得 $f^{′}{\left ({x{{}_{4}}}\right )}+f^{′}{\left ({\sqrt {2a}}\right )}>0$ ，
46. 因为 $f^{′}{\left ({x}\right )}$ 在 $\left ({0,\sqrt {2a}}\right )$ 内单调递减，在 $\left ({\sqrt {2a},+∞}\right )$ 内单调递增，
47. 可得 $f^{′}{\left ({x{{}_{1}}}\right )}>f^{′}{\left ({x{{}_{4}}}\right )}$ ，  $f^{′}{\left ({x{{}_{2}}}\right )}>f^{′}{\left ({\sqrt {2a}}\right )}$ ，
48. 所以 $f^{′}{\left ({x{{}_{1}}}\right )}+f^{′}{\left ({x{{}_{2}}}\right )}>f^{′}{\left ({x{{}_{4}}}\right )}+f^{′}{\left ({\sqrt {2a}}\right )}>0$ ；
49. 综上所述： $f^{′}{\left ({x{{}_{1}}}\right )}+f^{′}{\left ({x{{}_{2}}}\right )}>0$ .

## 知识点

**中文**:
  - 利用导数研究函数的图象
  - 导数几何意义的应用
  - 利用导数证明不等式

**English**:
  - Studying Function Graphs
  - Applications of Geometric Meaning of Derivatives
  - Proving Inequalities using Derivatives

---
