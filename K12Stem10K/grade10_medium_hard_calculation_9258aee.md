# Mathematics - 题目 3770

**ID**: 9258aeeb1ee045d7a700f1313f616538
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
定义 $\left [a,b\right ]\cup \left [c,d\right ]\left ({b<c}\right )$ 的“区间长度”为 $d-c+b-a$ ，设函数 $f\left ({x}\right )=\left ({2\sin x-t}\right )\left ({2t\sin x+1}\right )$ 的定义域为 $\left [0,2{\rm{\mathrm{π}}}\right ]$ ．（1）当 $t=-1$ 时，求关于x的不等式 $f\left ({x}\right )\leqslant 0$ 解集的“区间长度”；​​​​​​​‌（2）已知 $\frac {1}{2}<t<2$ ，设关于x的不等式 $f\left ({x}\right )\geqslant 0$ 解集的“区间长度”为I．（ⅰ）若 $I={\rm{\mathrm{π}}}$ ，求t；（ⅱ）求I的最大值．

## 解答

1. （1）当 $t=-1$ 时， $f\left ({x}\right )=\left ({2\sin x+1}\right )\left ({-2\sin x+1}\right )$ ，
2. 由 $f\left ({x}\right )\leqslant 0$ 解得 $\sin x\geqslant \frac {1}{2}$ 或 $\sin x\leqslant -\frac {1}{2}$ ，
3. 因 $x\in \left [0,2{\rm{\mathrm{π}}}\right ]$ ，可解得： $\frac {{\rm{\mathrm{π}}}}{6}\leqslant x\leqslant \frac {5{\rm{\mathrm{π}}}}{6}$ ，或 $\frac {7{\rm{\mathrm{π}}}}{6}\leqslant x\leqslant \frac {11{\rm{\mathrm{π}}}}{6}$ ，
4. 所以不等式 $f\left ({x}\right )\leqslant 0$ 解集的“区间长度”为 $\frac {11{\rm{\mathrm{π}}}}{6}-\frac {7{\rm{\mathrm{π}}}}{6}+\frac {5{\rm{\mathrm{π}}}}{6}-\frac {{\rm{\mathrm{π}}}}{6}=\frac {4{\rm{\mathrm{π}}}}{3}$ ．
5. （2）（ⅰ）因为 $\frac {1}{2}<t<2$ ， $\frac {t}{2}>-\frac {1}{2t}$ ，由 $f\left ({x}\right )\geqslant 0$ ，解得 $\sin x\geqslant \frac {t}{2}$ 或 $\sin x\leqslant -\frac {1}{2t}$ ，
6. 设 $\sin x-\frac {t}{2}=0$ 的两个根为 $x{{}_{1}}$ ， $x{{}_{2}}$ ，其中 $0<x{{}_{1}}<\frac {{\rm{\mathrm{π}}}}{2}<x{{}_{2}}<{\rm{\mathrm{π}}}$ ，且 $x{{}_{1}}+x{{}_{2}}={\rm{\mathrm{π}}}$ ，
7. 同理，设 $\sin x+\frac {1}{2t}=0$ 的两个根为 $x{{}_{3}}$ ， $x{{}_{4}}$ ，其中 ${\rm{\mathrm{π}}}<x{{}_{3}}<\frac {3{\rm{\mathrm{π}}}}{2}<x{{}_{4}}<2{\rm{\mathrm{π}}}$ ，且 $x{{}_{3}}+x{{}_{4}}=3{\rm{\mathrm{π}}}$ ，
8. 所以 $I=x{{}_{2}}-x{{}_{1}}+x{{}_{4}}-x{{}_{3}}=4{\rm{\mathrm{π}}}-2\left ({x{{}_{1}}+x{{}_{3}}}\right )$ ，
9. 又 $I={\rm{\mathrm{π}}}$ ，所以 $x{{}_{1}}+x{{}_{3}}=\frac {3{\rm{\mathrm{π}}}}{2}$ ，
10. 所以 $\sin x{{}_{1}}\sin x{{}_{3}}=\frac {t}{2}\times \frac {-1}{2t}=-\frac {1}{4}$ ，即 $\sin x{{}_{1}}\sin \left ({\frac {3{\rm{\mathrm{π}}}}{2}-x{{}_{1}}}\right )=-\frac {1}{4}$ ，
11. $-\frac {1}{2}\sin 2x{{}_{1}}=-\frac {1}{4}$ ，即 $\sin 2x{{}_{1}}=\frac {1}{2}$ ，解得 $x{{}_{1}}=\frac {{\rm{\mathrm{π}}}}{12}$ 或 $\frac {5{\rm{\mathrm{π}}}}{12}$ ，
12. 所以 $t=2\sin x{{}_{1}}=2\sin \left ({\frac {{\rm{\mathrm{π}}}}{4}-\frac {{\rm{\mathrm{π}}}}{6}}\right )=\frac {\sqrt {6}-\sqrt {2}}{2}$ 或 $t=2\sin \left ({\frac {{\rm{\mathrm{π}}}}{4}+\frac {{\rm{\mathrm{π}}}}{6}}\right )=\frac {\sqrt {6}+\sqrt {2}}{2}$ ．
13. （ⅱ）方法1：由（ⅰ）可得， $\sin x{{}_{1}}\sin x{{}_{3}}=-\frac {1}{4}$ ，
14. 则 $\sin {^{2}}x{{}_{1}}\sin {^{2}}x{{}_{3}}=\left ({1-{\cos}{^{2}}x{{}_{1}}}\right )\left ({1-{\cos}{^{2}}x{{}_{3}}}\right )=1-\left ({{\cos}{^{2}}x{{}_{1}}+{\cos}{^{2}}x{{}_{3}}}\right )+{\cos}{^{2}}x{{}_{1}}{\cos}{^{2}}x{{}_{3}}=\frac {1}{16}$ ，
15. 因为 ${\cos}x{{}_{1}}>0$ ， ${\cos}x{{}_{3}}<0$ ，
16. 所以 ${\cos}{^{2}}x{{}_{1}}+{\cos}{^{2}}x{{}_{3}}\geqslant -2{\cos}x{{}_{1}}{\cos}x{{}_{3}}$ ，
17. 所以 $1+2{\cos}x{{}_{1}}{\cos}x{{}_{3}}+{\cos}{^{2}}x{{}_{1}}{\cos}{^{2}}x{{}_{3}}\geqslant \frac {1}{16}$ ，即 ${\left({{\cos}x{{}_{1}}{\cos}x{{}_{3}}+1}\right)^{2}}\geqslant \frac {1}{16}$ ，
18. 所以 ${\cos}x{{}_{1}}{\cos}x{{}_{3}}+1\geqslant \frac {1}{4}$ ，或 ${\cos}x{{}_{1}}{\cos}x{{}_{3}}+1\leqslant -\frac {1}{4}$ （舍），
19. 所以 ${\cos}x{{}_{1}}{\cos}x{{}_{3}}\geqslant -\frac {3}{4}$ ，
20. 所以 ${\cos}\left ({x{{}_{3}}+x{{}_{1}}}\right )={\cos}x{{}_{1}}{\cos}x{{}_{3}}-\sin x{{}_{1}}\sin x{{}_{3}}\geqslant -\frac {3}{4}-\left ({-\frac {1}{4}}\right )=-\frac {1}{2}$ ，
21. 因为 $0<x{{}_{1}}<\frac {{\rm{\mathrm{π}}}}{2}$ ， ${\rm{\mathrm{π}}}<x{{}_{3}}<\frac {3{\rm{\mathrm{π}}}}{2}$ ，所以 ${\rm{\mathrm{π}}}<x{{}_{1}}+x{{}_{3}}<2{\rm{\mathrm{π}}}$ ，
22. 由 ${\cos}\left ({x{{}_{3}}+x{{}_{1}}}\right )\geqslant -\frac {1}{2}$ 可知，所以 $x{{}_{1}}+x{{}_{3}}\geqslant \frac {4{\rm{\mathrm{π}}}}{3}$ ，
23. 当且仅当 $\begin{cases}{\cos}x{{}_{1}}=-{\cos}x{{}_{3}}\\\sin x{{}_{1}}\sin x{{}_{3}}=-\frac {1}{4}\end{cases}$ ，即 $\begin{cases}x{{}_{1}}=\frac {{\rm{\mathrm{π}}}}{6}\\x{{}_{3}}=\frac {7{\rm{\mathrm{π}}}}{6}\end{cases}$ 时等号成立，
24. 所以 $I=4{\rm{\mathrm{π}}}-2\left ({x{{}_{1}}+x{{}_{3}}}\right )\leqslant \frac {4{\rm{\mathrm{π}}}}{3}{\rm ，\mathit{I}}$ 的最大值为 $\frac {4{\rm{\mathrm{π}}}}{3}$ ．
25. 方法2：由（ⅰ）可得， $\sin x{{}_{1}}\sin x{{}_{3}}=\frac {t}{2}\times \frac {-1}{2t}=-\frac {1}{4}$ ，
26. $\sin x{{}_{1}}\sin x{{}_{3}}=\sin x{{}_{1}}\sin \left ({x{{}_{3}}+x{{}_{1}}-x{{}_{1}}}\right )=\sin x{{}_{1}}\left [\sin \left ({x{{}_{3}}+x{{}_{1}}}\right ){\cos}x{{}_{1}}-{\cos}\left ({x{{}_{3}}+x{{}_{1}}}\right )\sin x{{}_{1}}\right ]$
27. $=\frac {\sin 2x{{}_{1}}\sin \left ({x{{}_{3}}+x{{}_{1}}}\right )}{2}-{\cos}\left ({x{{}_{3}}+x{{}_{1}}}\right )\frac {1-{\cos}2x{{}_{1}}}{2}$
28. $=\frac {\sin 2x{{}_{1}}\sin \left ({x{{}_{3}}+x{{}_{1}}}\right )+{\cos}2x{{}_{1}}{\cos}\left ({x{{}_{3}}+x{{}_{1}}}\right )}{2}-\frac {{\cos}\left ({x{{}_{3}}+x{{}_{1}}}\right )}{2}$
29. $=\frac {{\cos}\left ({x{{}_{3}}-x{{}_{1}}}\right )-{\cos}\left ({x{{}_{3}}+x{{}_{1}}}\right )}{2}$
30. 所以 $\frac {1}{2}\left [{\cos}\left ({x{{}_{3}}-x{{}_{1}}}\right )-{\cos}\left ({x{{}_{3}}+x{{}_{1}}}\right )\right ]=-\frac {1}{4}$ ，
31. 所以 ${\cos}\left ({x{{}_{3}}+x{{}_{1}}}\right )=\frac {1}{2}+{\cos}\left ({x{{}_{3}}-x{{}_{1}}}\right )$ ，
32. 因为 ${\cos}\left ({x{{}_{3}}-x{{}_{1}}}\right )\geqslant -1$ ，所以 ${\cos}\left ({x{{}_{3}}+x{{}_{1}}}\right )\geqslant -\frac {1}{2}$ ，
33. 因为 $0<x{{}_{1}}<\frac {{\rm{\mathrm{π}}}}{2}$ ， ${\rm{\mathrm{π}}}<x{{}_{3}}<\frac {3{\rm{\mathrm{π}}}}{2}$ ，所以 ${\rm{\mathrm{π}}}<x{{}_{1}}+x{{}_{3}}<2{\rm{\mathrm{π}}}$ ，
34. 由 ${\cos}\left ({x{{}_{3}}+x{{}_{1}}}\right )\geqslant -\frac {1}{2}$ 可知，所以 $x{{}_{1}}+x{{}_{3}}\geqslant \frac {4{\rm{\mathrm{π}}}}{3}$ ，
35. 当且仅当 $\begin{cases}{\cos}\left ({x{{}_{3}}-x{{}_{1}}}\right )=-1\\{\cos}\left ({x{{}_{3}}+x{{}_{1}}}\right )=-\frac {1}{2}\end{cases}$ ，即 $\begin{cases}x{{}_{1}}=\frac {{\rm{\mathrm{π}}}}{6}\\x{{}_{3}}=\frac {7{\rm{\mathrm{π}}}}{6}\end{cases}$ 时等号成立，
36. 所以 $I=4{\rm{\mathrm{π}}}-2\left ({x{{}_{1}}+x{{}_{3}}}\right )\leqslant \frac {4{\rm{\mathrm{π}}}}{3}{\rm ，\mathit{I}}$ 的最大值为 $\frac {4{\rm{\mathrm{π}}}}{3}$ ．

## 知识点

**中文**:
  - 三角函数中的新定义问题

**English**:
  - New Definition Problems

---
