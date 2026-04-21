# Mathematics - 题目 160

**ID**: 76f205f241244c8c9be550e3ae99ae68
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\left ({x{^{2}}-a}\right ){\rm{l}}{\rm{n}}\left |{x}\right |$ .​​​​​​​‌（1）当 $a=1$ ，求函数的零点；（2）是否存在实数 $a$ ，使得 $x=\frac {1}{{\rm{e}}}$ 是函数 $f\left ({x}\right )$ 的极值点？若存在，求出 $a$ 的值；若不存在，请说明理由；（3）若 $f\left ({x}\right )>-\frac {1}{2}$ 恒成立，求满足条件的整数 $a$ 的最大值.

## 解答

1. （1） $f\left ({x}\right )=\left ({x{^{2}}-a}\right ){\rm{l}}{\rm{n}}\left |{x}\right |$ 的定义域为 $\left ({-\infty ,0}\right )\cup \left ({0,+\infty }\right )$ ，
2. 当 $a=1$ ， $f\left ({x}\right )=\left ({x{^{2}}-1}\right ){\rm{l}}{\rm{n}}\left |{x}\right |$ ，令 $\left ({x{^{2}}-1}\right ){\rm{l}}{\rm{n}}\left |{x}\right |=0$ ，
3. 则 $x{^{2}}-1=0$ 或 ${\rm{l}}{\rm{n}}\left |{x}\right |=0$ ，若 $x{^{2}}-1=0$ ，则 $x=\pm 1$ ，若 ${\rm{l}}{\rm{n}}\left |{x}\right |=0$ ，则 $x=\pm 1$ ，
4. 故当 $a=1$ 时，函数 $f\left ({x}\right )$ 的零点为 $\pm 1$ ；
5. （2）不存在实数 $a$ ，使得 $x=\frac {1}{{\rm{e}}}$ 是函数 $f\left ({x}\right )$ 的极值点，理由如下：
6. 当 $x>0$ 时， $f\left ({x}\right )=\left ({x{^{2}}-a}\right ){\ln}x$ ， $f^{′}{\left ({x}\right )}=2x{\ln}x+\frac {x{^{2}}-a}{x}=2x{\ln}x+x-\frac {a}{x}$ ，
7. 若 $x=\frac {1}{{\rm{e}}}$ 是函数 $f\left ({x}\right )$ 的极值点，则有 $f^{′}{\left ({\frac {1}{{\rm{e}}}}\right )}=\frac {2}{{\rm{e}}}{\ln}\frac {1}{{\rm{e}}}+\frac {1}{{\rm{e}}}-a{\rm{e}}=0$ ，即 $a=-\frac {1}{{\rm{e}}{^{2}}}$ ；
8. 验证：当 $a=-\frac {1}{{\rm{e}}{^{2}}}$ 时， $f^{′}{\left ({x}\right )}=2x{\ln}x+x+\frac {1}{{\rm{e}}{^{2}}x}=x\left ({2{\ln}x+1+\frac {1}{{\rm{e}}{^{2}}x{^{2}}}}\right )$ ，
9. 令 $g\left ({x}\right )=2{\ln}x+1+\frac {1}{{\rm{e}}{^{2}}x{^{2}}}$ ， $x>0$ ，则 $g^{′}{\left ({x}\right )}=\frac {2}{x}-\frac {2}{{\rm{e}}{^{2}}x{^{3}}}=\frac {2\left ({{\rm{e}}x+1}\right )\left ({{\rm{e}}x-1}\right )}{{\rm{e}}{^{2}}x{^{3}}}$ ，
10. 则当 $x\in \left ({0,\frac {1}{{\rm{e}}}}\right )$ 时， $g^{′}{\left ({x}\right )}<0$ ，当 $x\in \left ({\frac {1}{{\rm{e}}},+\infty }\right )$ 时， $g^{′}{\left ({x}\right )}>0$ ，
11. 故 $g\left ({x}\right )$ 在 $\left ({0,\frac {1}{{\rm{e}}}}\right )$ 上单调递减，在 $\left ({\frac {1}{{\rm{e}}},+\infty }\right )$ 上单调递增，
12. 则 $g\left ({x}\right )\geqslant g\left ({\frac {1}{{\rm{e}}}}\right )=2{\ln}\frac {1}{{\rm{e}}}+1+1=0$ ，故 $f^{′}{\left ({x}\right )}=xg\left ({x}\right )\geqslant 0$ 恒成立，
13. 故 $f\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上单调递增，故 $x=\frac {1}{{\rm{e}}}$ 不是函数 $f\left ({x}\right )$ 的极值点；
14. 综上可得，不存在实数 $a$ ，使得 $x=\frac {1}{{\rm{e}}}$ 是函数 $f\left ({x}\right )$ 的极值点；
15. （3） $f\left ({-x}\right )=\left [{\left({-x}\right)^{2}}-a\right ]{\rm{l}}{\rm{n}}\left |{-x}\right |=\left ({x{^{2}}-a}\right ){\rm{l}}{\rm{n}}\left |{x}\right |=f\left ({x}\right )$ ，
16. 又 $f\left ({x}\right )$ 的定义域为 $\left ({-\infty ,0}\right )\cup \left ({0,+\infty }\right )$ ，故 $f\left ({x}\right )$ 为偶函数，
17. 则只需考虑 $x>0$ 时的情况，
18. 当 $x>0$ 时， $f\left ({x}\right )=\left ({x{^{2}}-a}\right ){\ln}x$ ，令 $f\left ({x}\right )=\left ({x{^{2}}-a}\right ){\ln}x>-\frac {1}{2}$ ，
19. 即 $a{\ln}x<x{^{2}}{\ln}x+\frac {1}{2}$ ，若 $x=1$ ，有 $0<\frac {1}{2}$ ，符合，
20. 当 $0<x<1$ 时， ${\ln}x<0$ ，则需 $a>x{^{2}}+\frac {1}{2{\ln}x}$ 对任意 $x\in \left ({0,1}\right )$ 恒成立，
21. 当 $x>1$ 时， ${\ln}x>0$ ，则需 $a<x{^{2}}+\frac {1}{2{\ln}x}$ 对任意 $x\in \left ({1,+\infty }\right )$ 恒成立；
22. 令 $h\left ({x}\right )=x{^{2}}+\frac {1}{2{\ln}x}$ ， $x>0$ 且 $x\ne 1$ ，
23. $h^{′}{\left ({x}\right )}=2x-\frac {1}{2x{\ln}{^{2}}x}=\frac {4x{^{2}}{\ln}{^{2}}x-1}{2x{\ln}{^{2}}x}=\frac {\left ({2x{\ln}x-1}\right )\left ({2x{\ln}x+1}\right )}{2x{\ln}{^{2}}x}$ ，
24. 令 $m\left ({x}\right )=x{\ln}x$ ，则 $m^{′}{\left ({x}\right )}={\ln}x+1$ ，
25. 则当 $x\in \left ({0,\frac {1}{{\rm{e}}}}\right )$ 时， $m^{′}{\left ({x}\right )}<0$ ，当 $x\in \left ({\frac {1}{{\rm{e}}},+\infty }\right )$ 时， $m{^{\prime }}\left ({x}\right )>0$ ，
26. 故 $m\left ({x}\right )$ 在 $\left ({0,\frac {1}{{\rm{e}}}}\right )$ 上单调递减，在 $\left ({\frac {1}{{\rm{e}}},+\infty }\right )$ 上单调递增，
27. 则 $m\left ({x}\right )\geqslant m\left ({\frac {{{1}}}{{\rm{e}}}}\right )=\frac {{{1}}}{{\rm{e}}}{\ln}\frac {{{1}}}{{\rm{e}}}=-\frac {{{1}}}{{\rm{e}}}$ ，则 $2x{\ln}x+1\geqslant 1-\frac {2}{{\rm{e}}}>0$ ；
28. 又当 $0<x<1$ 时， $m\left ({x}\right )=x{\ln}x<0$ ，则 $2x{\ln}x-1<0$ ，
29. 令 $u\left ({x}\right )={\rm{e}}{^{x}}-1-x-\frac {x{^{2}}}{2}$ ， $x\geqslant 0$ ，则 $u^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-1-x$ ，
30. 令 $λ\left ({x}\right )=u^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-1-x$ ，则 $λ^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-1\geqslant 0$ ，
31. 故 $λ\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上单调递增，则 $u^{′}{\left ({x}\right )}\geqslant u^{′}{\left ({0}\right )}=1-1=0$ ，
32. 故 $u\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上单调递增，则 $u\left ({\frac {5}{14}}\right )={\rm{e}}{^{\frac {5}{14}}}-1-\frac {5}{14}-\frac {{\left({\frac {5}{14}}\right)^{2}}}{2}={\rm{e}}{^{\frac {5}{14}}}-\frac {557}{392}>0$ ，
33. 则 ${\rm{e}}{^{\frac {5}{14}}}>\frac {557}{392}>\frac {7}{5}$ ，故 $\frac {5}{14}>{\ln}\frac {7}{5}$ ，则 $\frac {14}{5}{\ln}\frac {7}{5}-1<0$ ，
34. 当 $x>1$ 时，令 $n\left ({x}\right )=2x{\ln}x-1$ ，由 $m\left ({x}\right )=x{\ln}x$ 在 $\left ({\frac {1}{{\rm{e}}},+\infty }\right )$ 上单调递增，
35. 则 $n\left ({x}\right )=2x{\ln}x-1$ 在 $\left ({1,+\infty }\right )$ 上单调递增，
36. 又 $n\left ({\frac {7}{5}}\right )=\frac {14}{5}{\ln}\frac {7}{5}-1<0$ ， $n\left ({\frac {3}{2}}\right )=3{\ln}\frac {3}{2}-1={\ln}\frac {27}{8{\rm{e}}}>{\ln}\frac {27}{24}>0$ ，
37. 故函数 $n\left ({x}\right )=2x{\ln}x-1$ 存在唯一零点 $x{{}_{0}}\in \left ({\frac {7}{5},\frac {3}{2}}\right )$ ，
38. 即有 $2x{{}_{0}}{\ln}x{{}_{0}}-1=0$ ，即 ${\ln}x{{}_{0}}=\frac {1}{2x{{}_{0}}}$ ，
39. 则当 $x\in \left ({0,1}\right )\cup \left ({1,x{{}_{0}}}\right )$ 时， $h^{′}{\left ({x}\right )}<0$ ，当 $x\in \left ({x{{}_{0}},+\infty }\right )$ 时， $h^{′}{\left ({x}\right )}>0$ ，
40. 故 $h\left ({x}\right )$ 在 $\left ({0,1}\right )$ 、 $\left ({1,x{{}_{0}}}\right )$ 上单调递减，在 $\left ({x{{}_{0}},+\infty }\right )$ 上单调递增，
41. 又当 $x\to 0$ 时， $h\left ({x}\right )→0$ 且 $h\left ({x}\right )<0$ ，则当 $0<x<1$ ，需 $a\geqslant 0$ ；
42. 当 $x>1$ 时， $a<h\left ({x}\right ){{}_{{\rm \min }}}=x{{}_{0}^{2}}+\frac {1}{2{\ln}x{{}_{0}}}=x{{}_{0}^{2}}+x{{}_{0}}$ ，
43. 由 $x{{}_{0}}\in \left ({\frac {7}{5},\frac {3}{2}}\right )$ ， $y=x{^{2}}+x$ 在 $\left ({\frac {7}{5},\frac {3}{2}}\right )$ 上单调递增，
44. 当 $x=\frac {7}{5}$ 时， $y=x{^{2}}+x=\frac {49}{25}+\frac {7}{5}=\frac {84}{25}$ ，
45. 当 $x=\frac {3}{2}$ 时， $y=x{^{2}}+x=\frac {9}{4}+\frac {3}{2}=\frac {15}{4}$ ，
46. 则 $x{{}_{0}^{2}}+x{{}_{0}}\in \left ({\frac {84}{25},\frac {15}{4}}\right )$ ，又 $3<\frac {84}{25}<\frac {15}{4}<4$ ，则整数 $a\leqslant 3$ ；
47. 综上：整数 $a$ 可取 $0$ 、 $1$ 、 $2$ 、 $3$ ，即满足条件的整数 $a$ 的最大值为 $3$ .

## 知识点

**中文**:
  - 函数零点的概念
  - 利用导数研究函数的单调性与单调区间
  - 利用导数解决不等式恒成立问题

**English**:
  - Concept of Zero Points
  - Monotonicity and Monotonic Intervals
  - Solving Universally True Inequalities

---
