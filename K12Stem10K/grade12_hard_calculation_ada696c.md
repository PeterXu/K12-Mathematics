# Mathematics - 题目 623

**ID**: ada696cebc904cb18f504a9a87936c27
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
设函数 $f\left ({x}\right )=a\mathrm{e}{^{x}}+2x+ab,\left ({a,b\in \mathbf{R}}\right )$ ， $f^{′}{\left ({x}\right )}$ 为函数 $f\left ({x}\right )$ 的导函数.​​​​​​​‌（1）讨论函数 $f\left ({x}\right )$ 的单调性并写出单调区间；（2）若存在 $a$ ，使得函数 $f\left ({x}\right )$ 不存在零点，求 $b$ 的取值范围；（3）若函数 $g\left ({x}\right )=f\left ({x}\right )-ab$ 有两个不同的零点 $x{{}_{1}},x{{}_{2}}\left ({x{{}_{1}}<x{{}_{2}}}\right )$ ，求证： $\frac {f^{′}{\left ({x{{}_{1}}}\right )}}{f^{′}{\left ({x{{}_{2}}}\right )}}>-1$ .

## 解答

1. （1） $f^{′}{\left ({x}\right )}=a{\rm{e}}{^{x}}+2$ .
2. 当 $a\geqslant 0$ 时， $f^{′}{\left ({x}\right )}>0$ ，函数 $f\left ({x}\right )$ 的单调递增区间是 $\left ({-\infty ,+\infty }\right )$ .
3. 当 $a<0$ 时，令 $f^{′}{\left ({x}\right )}>0$ ，得 $x<{\ln}\left ({-\frac {2}{a}}\right )$ ，令 $f^{′}{\left ({x}\right )}<0$ ，得 $x>{\ln}\left ({-\frac {2}{a}}\right )$ .
4. 所以函数 $f\left ({x}\right )$ 的单调递增区间为 $\left ({-\infty ,{\ln}\left ({-\frac {2}{a}}\right )}\right )$ ，单调递减区间是 $\left ({{\ln}\left ({-\frac {2}{a}}\right ),+\infty }\right )$ .
5. （2）当 $a\geqslant 0$ 时，由（1）知， $f\left ({x}\right )$ 的单调递增区间是 $\left ({-\infty ,+\infty }\right )$ ，
6. 易知 $f\left ({-\frac {ab}{2}}\right )=a{\rm{e}}{^{-\frac {ab}{2}}}+4>0$ .又 $-\frac {a+\left |{ab}\right |+4}{2}<0$ ，故可得
7. $f\left ({-\frac {a+\left |{ab}\right |+4}{2}}\right )=a\left ({{\rm{e}}{^{-\frac {a+\left |{ab}\right |+4}{2}}}-1}\right )-\left |{ab}\right |+ab\leqslant 0$ ，
8. 又 $-\frac {a+\left |{ab}\right |+4}{2}<-\frac {ab}{2}$ ，且函数 $f\left ({x}\right )$ 的图象连续，所以 $f\left ({x}\right )$ 存在一个零点，不满足题意.
9. 当 $a<0$ 时，因为 $f\left ({-\frac {ab+4}{2}}\right )=a{\rm{e}}{^{-t+4}}<0$ ，函数 $f\left ({x}\right )$ 的图象不间断，若存在 $a<0$ ，使函数 $f\left ({x}\right )$ 不存在零点，则 $f\left ({x}\right )<0$ 对任意 $x\in {\mathbf{R}}$ 恒成立.
10. 由（1）知， $\left [f\left ({x}\right )\right ]{{}_{{\rm{m}}{\rm{a}}{\rm{x}}{\rm{\;}}}}=f\left ({{\ln}\left ({-\frac {2}{a}}\right )}\right )=2{\ln}\left ({-\frac {2}{a}}\right )+ab-2<0$ 能成立，即 $b>-\frac {2}{a}\left [-1+{\ln}\left ({-\frac {2}{a}}\right )\right ]$ 能成立，令 $-\frac {2}{a}=t$ ，则 $t>0$ ， $b>t\left ({-1+{\ln}t}\right )$ ，
11. $g\left ({t}\right )=t\left ({-1+{\ln}t}\right )$ ，则 $g^{′}{\left ({t}\right )}={\ln}t$ ，令 $g^{′}{\left ({t}\right )}=0$ ，得 $t=1$ ，
12. 当 $t\in \left ({0,1}\right )$ 时， $g^{′}{\left ({t}\right )}<0$ ， $g\left ({t}\right )$ 单调递减， $t\in \left ({1,+\infty }\right )$ 时， $g^{′}{\left ({t}\right )}>0$ ， $g\left ({t}\right )$ 单调递增.
13. 所以 $\left [g\left ({t}\right )\right ]{{}_{{\rm \min }}}=g\left ({1}\right )=-1$ ，所以 $b>-{\rm{e}}{^{-2}}$ ，
14. 综上， $b$ 的取值范围是 $\left ({-1,+\infty }\right )$ .
15. （3）因为函数 $y=f\left ({x}\right )-ab$ 有两个不同的零点 $x{{}_{1}},x{{}_{2}}\left ({x{{}_{1}}<x{{}_{2}}}\right )$ ，
16. 则由（1）知 $a<0$ ，且 $a{\rm{e}}{^{x{{}_{1}}}}+2x{{}_{1}}+4=0$ ， $a{\rm{e}}{^{x{{}_{2}}}}+2x{{}_{2}}+4=0$ ，消去 $a$ 得 ${\rm{e}}{^{x{{}_{1}}-x{{}_{2}}}}=\frac {x{{}_{1}}+2}{x{{}_{2}}+2}$ .
17. 设 ${\rm{e}}{^{x{{}_{1}}-x{{}_{2}}}}=\frac {x{{}_{1}}+2}{x{{}_{2}}+2}=u$ ，则 $u\in \left ({0,1}\right )$ ，可解得 $x{{}_{1}}+2=\frac {u{\ln}u}{u-1}$ ， $x{{}_{2}}+2=\frac {{\ln}u}{u-1}$ .
18. 方法1： $x{{}_{1}}+x{{}_{2}}+2=\frac {\left ({u+1}\right ){\ln}u}{u-1}-2=\frac {u+1}{u-1}\left [{\ln}u-\frac {2\left ({u-1}\right )}{u+1}\right ]$ .
19. 设 $h\left ({u}\right )={\ln}u-2\left ({u-1}\right )$ ， $u\in \left ({0,1}\right )$ ，则 $h^{′}{\left ({u}\right )}=\frac {1}{u}-\frac {4}{{\left({u+1}\right)^{2}}}=\frac {{\left({u-1}\right)^{2}}}{u{\left({u+1}\right)^{2}}}>0$ ，
20. 所以 $h\left ({u}\right )$ 在 $\left ({0,1}\right )$ 上单调递增，所以 $h\left ({u}\right )<h\left ({1}\right )=0$ ，
21. 故 $x{{}_{1}}+x{{}_{2}}+2=\frac {u+1}{u-1}\left [{\ln}u-\frac {2\left ({u-1}\right )}{u+1}\right ]>0$ ，
22. 所以 $f^{′}{\left ({x{{}_{1}}}\right )}+f^{′}{\left ({x{{}_{2}}}\right )}=a{\rm{e}}{^{x{{}_{1}}}}+2+a{\rm{e}}{^{x{{}_{2}}}}+2=-2\left ({x{{}_{1}}+x{{}_{2}}+2}\right )<0$ ，所以 $f^{′}{\left ({x{{}_{1}}}\right )}<-f^{′}{\left ({x{{}_{2}}}\right )}$ .
23. 又因为 $f^{′}{\left ({x{{}_{2}}}\right )}=a{\rm{e}}{^{x{{}_{2}}}}+2=-2\left ({x{{}_{2}}+1}\right )=2\left ({\frac {{\ln}u}{u-1}-1}\right )=-2\cdot \frac {{\ln}u-u+1}{u-1}$ .
24. 设 $p\left ({u}\right )={\ln}u-u+1$ ， $u\in \left ({0,1}\right )$ ，则 $p\left ({u}\right )=\frac {1}{u}-1>0$ ，
25. 所以 $p\left ({u}\right )$ 在 $\left ({0,1}\right )$ 上单调递增，所以 $p\left ({u}\right )<p\left ({1}\right )=0$ ，所以 $f^{′}{\left ({x{{}_{2}}}\right )}<0$ .
26. 综上， $\frac {f^{′}{\left ({x{{}_{1}}}\right )}}{f^{′}{\left ({x{{}_{2}}}\right )}}>-1$ .
27. 方法2： $x{{}_{1}}+1=\frac {u{\ln}u-u+1}{u-1}$ ， $x{{}_{2}}+1=\frac {{\ln}u-u+1}{u-1}$ ，
28. $\frac {f^{′}{\left ({x{{}_{1}}}\right )}}{f^{′}{\left ({x{{}_{2}}}\right )}}+1=\frac {a{\rm{e}}{^{x{{}_{1}}}}+2}{a{\rm{e}}{^{x{{}_{2}}}}+2}+1=\frac {-2\left ({x{{}_{1}}+1}\right )}{-2\left ({x{{}_{2}}+1}\right )}+1=\frac {u{\ln}u-u+1}{{\ln}u-u+1}+1=\frac {\left ({u+1}\right ){\ln}u-2u+2}{{\ln}u-u+1}$ .
29. 设 $k\left ({u}\right )=\left ({u+1}\right ){\ln}u-2u+2$ ， $u\in \left ({0,1}\right )$ ，则 $k^{′}{\left ({u}\right )}={\ln}u+\frac {1}{u}-1$ .
30. 设 $l\left ({u}\right )={\ln}u+\frac {1}{u}-1$ ， $u\in \left ({0,1}\right )$ ，
31. 则 $l^{′}{\left ({u}\right )}=\frac {u-1}{u{^{2}}}<0$ ， $l\left ({u}\right )$ 在 $\left ({0,1}\right )$ 上单调递减，所以 $k^{′}{\left ({u}\right )}=l\left ({u}\right )>l\left ({1}\right )=0$ ， $k\left ({u}\right )$ 在 $\left ({0,1}\right )$ 上单调递增，
32. 所以 $k\left ({u}\right )<k\left ({1}\right )=0$ .
33. 设 $p\left ({u}\right )={\ln}u-u+1$ ， $u\in \left ({0,1}\right )$ ，则 $p^{′}{\left ({u}\right )}=\frac {1}{u}-1>0$ ，所以 $p\left ({u}\right )$ 在 $\left ({0,1}\right )$ 上单调递增，
34. 所以 $p\left ({u}\right )<p\left ({1}\right )=0$ .
35. 所以 $\frac {f^{′}{\left ({x{{}_{1}}}\right )}}{f^{′}{\left ({x{{}_{2}}}\right )}}+1>0$ ，故 $\frac {f^{′}{\left ({x{{}_{1}}}\right )}}{f^{′}{\left ({x{{}_{2}}}\right )}}>-1$ .

## 知识点

**中文**:
  - 利用导数研究函数的单调性与单调区间
  - 利用导数解决函数零点问题

**English**:
  - Monotonicity and Monotonic Intervals
  - Solving Zero Point Problems

---
