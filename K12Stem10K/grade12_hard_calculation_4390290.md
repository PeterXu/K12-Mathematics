# Mathematics - 题目 12

**ID**: 4390290beb7d4e27acec709dc4706116
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=2x-a{\rm{l}}{\rm{n}}x$ .​​​​​​​‌(1)若 $f\left ({x}\right )>0$ 恒成立，求 $a$ 的取值范围；(2)当 $a=1$ 时，若 $\frac {f\left ({x{{}_{1}}}\right )}{\sqrt {x{{}_{1}}}}=\frac {f\left ({x{{}_{2}}}\right )}{\sqrt {x{{}_{2}}}}=\sqrt {m}$ ，其中 $x{{}_{1}}<x{{}_{2}}$ ，证明： $x{{}_{2}}-x{{}_{1}}<\frac {\sqrt {m{{}^{2}}-16}}{2}$ .

## 解答

1. （1）因为 $f\left ({x}\right )=2x-a{\rm{l}}{\rm{n}}x\left ({x>0}\right )$ ，
2. 所以 $f^{′}{\left ({x}\right )}=2-\frac {a}{x}=\frac {2x-a}{x}$ ，
3. 当 $a=0$ 时， $f\left ({x}\right )=2x$ ，显然 $f\left ({x}\right )>0$ 恒成立，
4. 当 $a{\rm{<}}{\rm{0}}$ 时，易得 $f\left ({{\rm{e}}{{}^{\frac {2}{a}}}}\right )=2{\rm{e}}{{}^{\frac {2}{a}}}-a{\rm{l}}{\rm{n}}{\rm{e}}{{}^{\frac {2}{a}}}<2{\rm{e}}{{}^{0}}-2=0$ ，不合题意；
5. 当 $a>0$ 时，令 $f^{′}{\left ({x}\right )}<0$ ，得 $0<x<\frac {a}{2}$ ；令 $f^{′}{\left ({x}\right )}>0$ ，得 $x>\frac {a}{2}$ ；
6. $f\left ({x}\right )$ 在 $\left ({0,\frac {a}{2}}\right )$ 上单调递减，在 $\left ({\frac {a}{2},+\infty }\right )$ 上单调递增，
7. 故 $f(x){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=a-a{\rm{l}}{\rm{n}}\frac {a}{2}>0$ ，所以 $0<a<2{\rm{e}}$ ；
8. 综上： $0\leqslant a<2{\rm{e}}$ .
9. （2）当 $a=1$ 时，令 $g\left ({x}\right )=\frac {(2x-{\rm{l}}{\rm{n}}x){{}^{2}}}{x},g^{′}{\left ({x}\right )}=\frac {\left ({2x-{\rm{l}}{\rm{n}}x}\right )\left ({2x-2+{\rm{l}}{\rm{n}}x}\right )}{x{{}^{2}}}$ ，
10. 由（1）知 $2x-{\rm{l}}{\rm{n}}x>0$ ，
11. 令 $p\left ({x}\right )=2x+{\rm{l}}{\rm{n}}x-2$ ，由于 $y=2x-2$ 与 $y={\ln}x$ 在 $\left ({0,+∞}\right )$ 上单调递增，
12. 所以 $p\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上单调递增且 $p\left ({1}\right )=0$ ，
13. 由此令 $g^{′}{\left ({x}\right )}<0$ ，得 $0<x<1$ ；令 $g^{′}{\left ({x}\right )}>0$ ，得 $x>1$ ；
14. 故 $g\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上单调递减，在 $\left ({1,+\infty }\right )$ 上单调递增，故 $g\left ({x}\right )\geqslant g\left ({1}\right )=4$ ，
15. 已知 $g\left ({x{{}_{1}}}\right )=g\left ({x{{}_{2}}}\right )=m$ ，则 $m>4$ ，且 $0<x{{}_{1}}<1<x{{}_{2}}$
16. 下证： $g\left ({x}\right )=\frac {(2x-{\rm{l}}{\rm{n}}x){{}^{2}}}{x}\geqslant h\left ({x}\right )=2\left ({x+\frac {1}{x}}\right )$ ，即证 $(2x-{\rm{l}}{\rm{n}}x){{}^{2}}\geqslant 2x{{}^{2}}+2$ ，
17. 设 $φ\left ({x}\right )=(2x-{\rm{l}}{\rm{n}}x){{}^{2}}-2x{{}^{2}}-2$ ，则 $φ^{′}{\left ({x}\right )}=\frac {2\left ({2x{{}^{2}}-2x-2x{\rm{l}}{\rm{n}}x+{\rm{l}}{\rm{n}}x}\right )}{x}$ ，
18. 令 $m\left ({x}\right )=x-1-{\ln}x\left ({x>0}\right )$ ，则 $m^{′}{\left ({x}\right )}=1-\frac {1}{x}=\frac {x-1}{x}$ ，
19. 当 $0<x<1$ 时， $m^{′}{\left ({x}\right )}<0$ ；当 $x>1$ 时， $m{{}^{\prime }}\left ({x}\right )>0$ ；
20. 所以 $m\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上单调递减，在 $\left ({1,+\infty }\right )$ 上单调递增，
21. 故 $m\left ({x}\right )\geqslant m\left ({1}\right )=0$ ，即 $x-1\geqslant {\ln}x$ ，则 $-2{\ln}x\geqslant -2\left ({x-1}\right )$ ，
22. 设 $q\left ({x}\right )=2x{{}^{2}}-2x-2x{\rm{l}}{\rm{n}}x+{\rm{l}}{\rm{n}}x$ ，
23. 则 $q^{′}{\left ({x}\right )}=\frac {4x{{}^{2}}-2x{\rm{l}}{\rm{n}}x-4x+1}{x}=4x+\frac {1}{x}-2{\rm{l}}{\rm{n}}x-4\geqslant 4x+\frac {1}{x}-2\left ({x-1}\right )-4$   $=2x+\frac {1}{x}-2\geqslant 2\sqrt {2x\cdot \frac {1}{x}}-2>0$ ，
24. 当且仅当 $2x=\frac {1}{x}$ ，即 $x=\frac {\sqrt {2}}{2}$ 时，等号成立，
25. 于是 $q\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上单调递增，且 $q\left ({1}\right )=0$ ，
26. 所以当 $x\in \left ({0,1}\right )$ 时， $φ^{′}{\left ({x}\right )}<0$ ，当 $x\in \left ({1,+\infty }\right )$ 时， $φ^{′}{\left ({x}\right )}>0$ ，
27. 故 $φ\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上单调递减，在 $\left ({1,+\infty }\right )$ 上单调递增， $φ\left ({x}\right )\geqslant φ\left ({1}\right )=0$ ，故 $g\left ({x}\right )\geqslant h\left ({x}\right )$ .
28. 设方程 $h\left ({x}\right )=m$ 的两个不等根为 $x{{}_{3}}<x{{}_{4}}$ ，
29. 由 $2\left ({x+\frac {1}{x}}\right )=m$ ，可得 $2x{{}^{2}}-mx+2=0$ ，故 $x{{}_{4}}-x{{}_{3}}=\frac {\sqrt {m{{}^{2}}-16}}{2}$ ，
30. 由 $g\left ({x}\right )\geqslant h\left ({x}\right )=2\left ({x+\frac {1}{x}}\right )$ ，可知 $x{{}_{2}}-x{{}_{1}}<x{{}_{4}}-x{{}_{3}}=\frac {\sqrt {m{{}^{2}}-16}}{2}$ ，结论成立.
31. 【点睛】方法点睛：导数是研究函数的单调性、极值(最值)最有效的工具，对导数的应用的考查主要从以下几个角度进行：
32. （1）考查导数的几何意义，往往与解析几何、微积分相联系．
33. （2）利用导数求函数的单调区间，判断单调性；已知单调性，求参数．
34. （3）利用导数求函数的最值(极值)，解决生活中的优化问题．
35. （4）考查数形结合思想的应用．

## 知识点

**中文**:
  - 利用导数解决不等式恒成立问题
  - 利用导数证明不等式

**English**:
  - Solving Universally True Inequalities
  - Proving Inequalities using Derivatives

---
