# Mathematics - 题目 1127

**ID**: 56ebd80cb987463b828db8d7b44a8532
**年级**: Grade 11
**难度**: Hard
**题型**: Calculation

## 题目
定义：若函数 $f\left ({x}\right )$ 与 $g\left ({x}\right )$ 的图象在 $x\in C$ 上有且仅有一个交点，则称函数 $f\left ({x}\right )$ 与 $g\left ({x}\right )$ 在 $x\in C$ 上单交，此交点被称为“单交点”.​​​​​​​‌已知函数 $f\left ({x}\right )=2{\rm{e}}{^{x}}-ax$ ， $a\in {\mathbf{R}}$ ， $g\left ({x}\right )=x{\rm{e}}{^{x}}+2$ .(1)讨论函数 $f\left ({x}\right )$ 的单调性；(2)当 $0\leqslant a<1$ 时，${\rm （i）}$ 求证：函数 $f\left ({x}\right )$ 与 $g\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上存在“单交点” $\left ({x{{}_{0}},f\left ({x{{}_{0}}}\right )}\right )$ ；（ⅱ）对于 ${\rm （i）}$ 中的正数 $x{{}_{0}}$ ，证明： ${\ln}\left [x{{}_{0}}\left ({a+1}\right )\right ]<1$ .

## 解答

1. （1） $f^{′}{\left ({x}\right )}=2{\rm{e}}{^{x}}-a$ ，
2. 当 $a\leqslant 0$ 时， $f^{′}{\left ({x}\right )}>0$ 对任意 $x\in {\mathbf{R}}$ 恒成立，故函数 $f\left ({x}\right )$ 在 ${\mathbf{R}}$ 上单调递增；
3. 当 $a>0$ 时，令 $f^{′}{\left ({x}\right )}<0$ ，得 $x<{\ln}\frac {a}{2}$ ；令 $f^{′}{\left ({x}\right )}>0$ ，得 $x>{\ln}\frac {a}{2}$ ，
4. 故函数 $f\left ({x}\right )$ 在 $\left ({-\mathrm{∞},{\ln}\frac {a}{2}}\right )$ 上单调递减，在 $\left ({{\ln}\frac {a}{2},+\mathrm{∞}}\right )$ 上单调递增；
5. （2）（i）令 $f\left ({x}\right )=g\left ({x}\right )$ ，得 $2{\rm{e}}{^{x}}-ax=x{\rm{e}}{^{x}}+2$ ，得 $\left ({2-x}\right ){\rm{e}}{^{x}}-ax-2=0$ ，
6. 设 $k\left ({x}\right )=\left ({2-x}\right ){\rm{e}}{^{x}}-ax-2$ ，则 $k^{′}{\left ({x}\right )}=\left ({1-x}\right ){\rm{e}}{^{x}}-a$ ，
7. 设 $m\left ({x}\right )=\left ({1-x}\right ){\rm{e}}{^{x}}-a$ ，则 $m^{′}{\left ({x}\right )}=-x{\rm{e}}{^{x}}$ ，
8. 当 $x\in \left ({0,+\mathrm{∞}}\right )$ 时， $m^{′}{\left ({x}\right )}<0$ ， $m\left ({x}\right )$ 单调递减，
9. 即 $k^{′}{\left ({x}\right )}$ 在 $\left ({0,+\mathrm{∞}}\right )$ 上单调递减，且 $k^{′}{\left ({0}\right )}=1-a>0$ ， $k^{′}{\left ({1}\right )}=-a\leqslant 0$ ，
10. 故 $\exists x{{}_{1}}\in \left ({0,1}\right ]$ ，使得 $k^{′}{\left ({x{{}_{1}}}\right )}=0$ ，
11. 当 $x\in \left ({0,x{{}_{1}}}\right )$ 时， $k^{′}{\left ({x}\right )}>0$ ，函数 $k\left ({x}\right )$ 单调递增，
12. 当 $x\in \left ({x{{}_{1}},+∞}\right )$ 时， $k^{′}{\left ({x}\right )}<0$ ，函数 $k\left ({x}\right )$ 单调递减，
13. 因为 $k\left ({0}\right )=0$ ， $k\left ({2}\right )=-2a-2<0$ ，
14. 所以 $k\left ({x}\right )$ 在 $\left ({0,2}\right )$ 上只有一个零点 $x{{}_{0}}$ ，故函数 $k\left ({x}\right )$ 在 $\left ({0,+\mathrm{∞}}\right )$ 上只有一个零点 $x{{}_{0}}$ ，
15. 即函数 $f\left ({x}\right )$ 与 $g\left ({x}\right )$ 在 $\left ({0,+\mathrm{∞}}\right )$ 上存在“单交点” $\left ({x{{}_{0}},f\left ({x{{}_{0}}}\right )}\right )$ ；
16. ${\rm （ii）}$ 因为 $0<x{{}_{0}}<2$ ，所以要证 ${\ln}\left [x{{}_{0}}\left ({a+1}\right )\right ]<1$ ，即证 $x{{}_{0}}\left ({a+1}\right )<{\rm{e}}$ ，
17. 即证 $ax{{}_{0}}+x{{}_{0}}\mathrm{-}{\rm{e}}\mathrm{<}0$ ，只需证 $ax{{}_{0}}+2\mathrm{-}{\rm{e}}\leqslant 0$ ，
18. 因为 $k\left ({x{{}_{0}}}\right )=\left ({2-x{{}_{0}}}\right ){\rm{e}}{^{x{{}_{0}}}}-ax{{}_{0}}-2=0$ ，得 $\left ({2-x{{}_{0}}}\right ){\rm{e}}{^{x{{}_{0}}}}=ax{{}_{0}}+2$ ，
19. 所以只需证 $\left ({2-x{{}_{0}}}\right ){\rm{e}}{^{x{{}_{0}}}}-{\rm{e}}\leqslant 0$ 即可，
20. 令 $h\left ({x}\right )=\left ({2-x}\right ){\rm{e}}{^{x}}-{\rm{e}}$ ， $0<x<2$ ，则 $h^{′}{\left ({x}\right )}=\left ({1-x}\right ){\rm{e}}{^{x}}$ ，
21. 当 $x\in \left ({0,1}\right )$ 时， $h^{′}{\left ({x}\right )}>0$ ， $h\left ({x}\right )$ 单调递增，
22. 当 $x\in \left ({1,2}\right )$ 时， $h^{′}{\left ({x}\right )}<0$ ， $h\left ({x}\right )$ 单调递减，
23. 故 $h\left ({x}\right ){{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}=h\left ({1}\right )=0$ ，即 $\left ({2-x{{}_{0}}}\right ){\rm{e}}{^{x{{}_{0}}}}-{\rm{e}}\leqslant 0$ ，
24. 原不等式即证.
25. 【关键点睛】最后一问关键点在于借助 $k\left ({x{{}_{0}}}\right )=\left ({2-x{{}_{0}}}\right ){\rm{e}}{^{x{{}_{0}}}}-ax{{}_{0}}-2=0$ ，从而消去参数 $a$ ，将 $x{{}_{0}}\left ({a+1}\right )<{\rm{e}}$ 转化为 $\left ({2-x{{}_{0}}}\right ){\rm{e}}{^{x{{}_{0}}}}-{\rm{e}}\leqslant 0$ .

## 知识点

**中文**:
  - 利用导数解决新定义问题
  - 利用导数证明不等式

**English**:
  - Solving New Definition Problems
  - Proving Inequalities using Derivatives

---
