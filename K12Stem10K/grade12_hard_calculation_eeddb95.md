# Mathematics - 题目 1624

**ID**: eeddb957a7f94cf5bd29d2a9ab7bb807
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )={\rm{e}}{^{x}}+ax{^{2}}-{\rm{e}}$ ， $a\in {\mathbf{R}}$ .​​​​​​​‌（注： ${\rm{e}}=2.71828\cdot \cdot \cdot $ 是自然对数的底数）(1)若 $f\left ({x}\right )$ 无极值点，求实数 $a$ 的取值范围；(2)当 $x\geqslant 0$ 时， $f\left ({x}\right )\geqslant \frac {1}{2}x{^{3}}+x-{\rm{e}}+1$ 恒成立，求实数 $a$ 的取值范围.

## 解答

1. （1）（方法一）易知 $f^{′}{\left ({x}\right )}={\rm{e}}{^{x}}+2ax$ ，由 $f\left ({x}\right )$ 无极值点可知，
2. $f^{′}{\left ({x}\right )}$ 无变号零点，令 ${\rm{e}}{^{x}}+2ax=0{\rm （*）}$ ，
3. 显然 $a=0$ 时，（*）无零点，此时 $f\left ({x}\right )$ 无极值点，满足题意；
4. 故当（*）可变形得 $\frac {x}{{\rm{e}}{^{x}}}=-\frac {1}{2a}$ ，
5. 令 $g\left ({x}\right )=\frac {x}{{\rm{e}}{^{x}}}$ ，原问题等价于 $g\left ({x}\right )$ 的图像与 $y=-\frac {1}{2a}$ 无相交交点，
6. 又 $g^{′}{\left ({x}\right )}=\frac {1-x}{{\rm{e}}{^{x}}}$ ，则 $x\in \left ({-\infty ,1}\right )$ ， $g^{′}{\left ({x}\right )}>0$ ， $g\left ({x}\right )$ 单调递增；
7. $x\in \left ({1,+\infty }\right )$ ， $g^{′}{\left ({x}\right )}<0$ ， $g\left ({x}\right )$ 单调递减；
8. 又 $x$ 趋于 $-\infty $ ， $g\left ({x}\right )$ 趋于 $-\infty $ ； $x$ 趋于 $+\infty $ ， $g\left ({x}\right )$ 趋于 $0$ ； $f\left ({1}\right )=\frac {1}{{\rm{e}}}$ .
9. 可得 $g\left ({x}\right )$ 的图象如图：
10. 
11. 由图可知 $-\frac {1}{2a}\geqslant \frac {1}{{\rm{e}}}$ ，解得 $-\frac {{\rm{e}}}{2}\leqslant a<0$ ，
12. 综上， $-\frac {{\rm{e}}}{2}\leqslant a\leqslant 0$
13. （方法二）构建 $g\left ({x}\right )=f^{′}{\left ({x}\right )}$ ，则 $g^{′}{\left ({x}\right )}={\rm{e}}{^{x}}+2a$ ，
14. ①当 $a>0$ 时， $g^{′}{\left ({x}\right )}>0$ 当 $x\in {\mathbf{R}}$ 时恒成立， $g\left ({x}\right )$ 在 ${\mathbf{R}}$ 上单调递增，
15. 因为 $g\left ({-\frac {1}{2a}}\right )={\rm{e}}{^{-\frac {1}{2a}}}-1<0$ ， $g\left ({0}\right )=1>0$ ，
16. 所以 $g\left ({x}\right )$ 有一个零点，即为 $f\left ({x}\right )$ 的一个极值点；
17. ②当 $a=0$ 时， $g\left ({x}\right )>0$ 当 $x\in {\mathbf{R}}$ 时恒成立，即 $f\left ({x}\right )$ 无极值点；
18. ③当 $a<0$ 时，当 $x<{\rm{l}}{\rm{n}}\left ({-2a}\right )$ ， $g^{′}{\left ({x}\right )}<0$ ；当 $x>{\rm{l}}{\rm{n}}\left ({-2a}\right )$ ， $g^{′}{\left ({x}\right )}>0$ ，
19. 所以 $g\left ({x}\right )$ 在 $\left ({-\infty ,{\ln}\left ({-2a}\right )}\right )$ 单调递减，在 $\left ({{\ln}\left ({-2a}\right ),+\infty }\right )$ 上单调递增，
20. 故 $g\left ({x}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=g\left ({{\rm{l}}{\rm{n}}\left ({-2a}\right )}\right )=-2a+2a{\rm{l}}{\rm{n}}\left ({-2a}\right )$ ，
21. 若 $g\left ({x}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}<0$ ，则 $-1+{\rm{l}}{\rm{n}}\left ({-2a}\right )>0$ 即 $a<-\frac {{\rm{e}}}{2}$ .
22. 当 $x<0$ 时， $g\left ({x}\right )>0$ ，
23. 当 $x>0$ 时， $g\left ({2{\rm{l}}{\rm{n}}\left ({-2a}\right )}\right )=4a{^{2}}+4a{\rm{l}}{\rm{n}}\left ({-2a}\right )=-2a\left [-2a-2{\rm{l}}{\rm{n}}\left ({-2a}\right )\right ]$ ，
24. 设 $s\left ({t}\right )=t-2{\ln}t$ ， $t>{\rm{e}}$ ，故 $s^{′}{\left ({t}\right )}=\frac {t-2}{t}>0$ ，
25. 故 $s\left ({t}\right )$ 在 $\left ({{\rm{e}},+\infty }\right )$ 上为单调递增函数，
26. 故 $s\left ({t}\right )>s\left ({{\rm{e}}}\right )={\rm{e}}-2{\rm{l}}{\rm{n}}{\rm{e}}={\rm{e}}-2>0$ ，
27. 故 $-2a\left [-2a-2{\rm{l}}{\rm{n}}\left ({-2a}\right )\right ]>0$ ，
28. 故当 $g\left ({{\rm{l}}{\rm{n}}\left ({-2a}\right )}\right )<0$ 时， $g\left ({x}\right )$ 有两个零点，此时 $f\left ({x}\right )$ 有两个极值点.
29. 当 $g\left ({{\rm{l}}{\rm{n}}\left ({-2a}\right )}\right )\geqslant 0$ 时， $g\left ({x}\right )\geqslant 0$ 当 $x\in {\mathbf{R}}$ 时恒成立，即 $f\left ({x}\right )$ 无极值点；
30. 综上所述： $-\frac {{\rm{e}}}{2}\leqslant a\leqslant 0$ ；
31. （2）（方法一）由 $f\left ({x}\right )\geqslant \frac {1}{2}x{^{3}}+x-{\rm{e}}+1$ 可知， ${\rm{e}}{^{x}}\geqslant \frac {1}{2}x{^{3}}-ax{^{2}}+x+1$ ，
32. 即 $1\geqslant {\rm{e}}{^{-x}}\left ({\frac {1}{2}x{^{3}}-ax{^{2}}+x+1}\right )$ ，
33. 令 $φ\left ({x}\right )={\rm{e}}{^{-x}}\left ({\frac {1}{2}x{^{3}}-ax{^{2}}+x+1}\right )-1$ ，即证 $φ\left ({x}\right )\leqslant 0$ ，
34. 易知 $φ\left ({0}\right )=0$ ，
35. 则 $φ^{′}{\left ({x}\right )}=-\frac {1}{2}x{\rm{e}}{^{-x}}\left ({x{^{2}}-\left ({2a+3}\right )x+4a+2}\right )=-\frac {1}{2}x{\rm{e}}{^{-x}}\left ({x-2}\right )\left ({x-2a-1}\right )$ ，
36. 若 $2a+1\leqslant 0$ ，即 $a\leqslant -\frac {1}{2}$ 时，
37. 则 $x\in \left ({0,2}\right )$ ， $φ^{′}{\left ({x}\right )}>0$ ， $φ\left ({x}\right )$ 单调递增， $φ\left ({x}\right )>φ\left ({0}\right )=0$ ，不符合题意；
38. 若 $0<2a+1<2$ ，即 $-\frac {1}{2}<a<\frac {1}{2}$ 时，
39. 则 $x\in \left ({0,2a+1}\right )$ ， $φ^{′}{\left ({x}\right )}<0$ ， $φ\left ({x}\right )$ 单调递减，
40. $x\in \left ({2a+1,2}\right )$ ， $φ^{′}{\left ({x}\right )}>0$ ， $φ\left ({x}\right )$ 单调递增，
41. $x\in \left ({2,+\infty }\right )$ ， $φ^{′}{\left ({x}\right )}<0$ ， $φ\left ({x}\right )$ 单调递减，
42. 又 $φ\left ({0}\right )=0$ ，故令 $φ\left ({2}\right )={\rm{e}}{^{-2}}\left ({\frac {1}{2}\times 2{^{3}}-a\times 2{^{2}}+2+1}\right )-1=\frac {7-{\rm{e}}{^{2}}-4a}{{\rm{e}}{^{2}}}\leqslant 0$ ，
43. 解得 $a\geqslant \frac {7-{\rm{e}}{^{2}}}{4}$ ，即 $\frac {7-{\rm{e}}{^{2}}}{4}\leqslant a<\frac {1}{2}$ ，
44. 若 $2a+1\geqslant 2$ ，即 $a\geqslant \frac {1}{2}$ 时，
45. 则 $x\in \left ({0,2}\right )$ ， $φ^{′}{\left ({x}\right )}<0$ ， $φ\left ({x}\right )$ 单调递减，
46. $x\in \left ({2,2a+1}\right )$ ， $φ^{′}{\left ({x}\right )}>0$ ， $φ\left ({x}\right )$ 单调递增，
47. $x\in \left ({2a+1,+\infty }\right )$ ， $φ^{′}{\left ({x}\right )}<0$ ， $φ\left ({x}\right )$ 单调递减，
48. 故令 $φ\left ({2a+1}\right )={\rm{e}}{^{-\left ({2a+1}\right )}}\left ({\frac {1}{2}{\left({2a+1}\right)^{3}}-a\times {\left({2a+1}\right)^{2}}+2a+1+1}\right )-1$
49. $={\rm{e}}{^{-\left ({2a+1}\right )}}\left ({2a{^{2}}+4a+\frac {5}{2}}\right )-1$ ，
50. 记 $h\left ({a}\right )={\rm{e}}{^{-\left ({2a+1}\right )}}\left ({2a{^{2}}+4a+\frac {5}{2}}\right )-1$ ，则 $h^{′}{\left ({a}\right )}=-{\rm{e}}{^{-\left ({2a+1}\right )}}{\left({2a+1}\right)^{2}}\leqslant 0$ 恒成立，
51. 所以 $h\left ({a}\right )$ 在 $\left ({\frac {1}{2},+\infty }\right )$ 上单调递减，
52. 所以 $h\left ({a}\right )\leqslant h\left ({\frac {1}{2}}\right )=\frac {5}{{\rm{e}}{^{2}}}-1<0$ ，即 $φ\left ({2a+1}\right )\leqslant 0$ ，
53. 即对于任意 $a\geqslant \frac {1}{2}$ ， $φ\left ({x}\right )\leqslant 0$ 恒成立，
54. 综上所述， $a\geqslant \frac {7-{\rm{e}}{^{2}}}{4}$ ；
55. （方法二）①当 $x=0$ 时，不等式恒成立，可得 $a\in {\mathbf{R}}$ ；
56. ②当 $x>0$ 时，可得 $a\geqslant \frac {\frac {1}{2}x{^{3}}+x+1-{\rm{e}}{^{x}}}{x{^{2}}}$ 恒成立，设 $h\left ({x}\right )=\frac {\frac {1}{2}x{^{3}}+x+1-{\rm{e}}{^{x}}}{x{^{2}}}$ ，
57. 则 $h^{′}{\left ({x}\right )}=\frac {\left ({2-x}\right ){\rm{e}}{^{x}}+\left ({\frac {1}{2}x{^{3}}-x-2}\right )}{x{^{3}}}=\frac {\left ({2-x}\right ){\rm{e}}{^{x}}+\left ({\frac {1}{2}x{^{3}}-x{^{2}}}\right )+\left ({x{^{2}}-x-2}\right )}{x{^{3}}}$
58. $=\frac {\left ({2-x}\right ){\rm{e}}{^{x}}+\frac {1}{2}x{^{2}}\left ({x-2}\right )+\left ({x-2}\right )\left ({x+1}\right )}{x{^{3}}}=\frac {\left ({2-x}\right )\left ({{\rm{e}}{^{x}}-\frac {1}{2}x{^{2}}-x-1}\right )}{x{^{3}}}$ .
59. 可设 $m\left ({x}\right )={\rm{e}}{^{x}}-\frac {1}{2}x{^{2}}-x-1$ ，可得 $m^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-x-1$ ，
60. 设 $k\left ({x}\right )={\rm{e}}{^{x}}-x-1$ ， $k^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-1$ ，
61. 由 $x>0$ ，可得 $k^{′}{\left ({x}\right )}>0$ 恒成立，可得 $k\left ({x}\right )$ 在 $\left ({0,+\infty }\right )$ 上单调递增，
62. $m^{′}{\left ({x}\right )}$ 在 $\left ({0,+\infty }\right )$ 上单调递增，所以 $m^{′}{\left ({x}\right )}>m^{′}{\left ({0}\right )}=0$ ，
63. 即 $m^{′}{\left ({x}\right )}>0$ 恒成立，即 $m\left ({x}\right )$ 在 $\left ({0,+\infty }\right )$ 上单调递增，所以 $m\left ({x}\right )>m\left ({0}\right )=0$ ，
64. 再令 $h^{′}{\left ({x}\right )}=0$ ，可得 $x=2$ ，
65. 当 $0<x<2$ 时， $h^{′}{\left ({x}\right )}>0$ ， $h\left ({x}\right )$ 在 $\left ({0,2}\right )$ 上单调递增；
66. $x>2$ 时， $h^{′}{\left ({x}\right )}<0$ ， $h\left ({x}\right )$ 在 $\left ({2,+\infty }\right )$ 上单调递减，
67. 所以 $h\left ({x}\right ){{}_{{\rm \max }}}=h\left ({2}\right )=\frac {7-{\rm{e}}{^{2}}}{4}$ ，
68. 所以 $a\geqslant \frac {7-{\rm{e}}{^{2}}}{4}$ ，综上可得 $a$ 的取值范围是 $\left [{\frac {7-{\rm{e}}{^{2}}}{4},+\infty }\right )$ .

## 知识点

**中文**:
  - 利用导数研究函数的极值
  - 利用导数解决不等式恒成立问题

**English**:
  - Extrema of Functions using Derivatives
  - Solving Universally True Inequalities

---
