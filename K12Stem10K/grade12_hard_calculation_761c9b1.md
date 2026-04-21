# Mathematics - 题目 301

**ID**: 761c9b14aad5499d95de469ce6f1f88b
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=x{\rm{e}}{{}^{-x}}+a{\rm{l}}{\rm{n}}\left ({1-x}\right ),a\in {\rm{R}}$(1)讨论函数 $f\left ({x}\right )$ 的单调性；(2)当 $a>0$ 时，对任意的买数 $x{{}_{1}},x{{}_{2}}<0$ ，证明： $f\left ({x{{}_{1}}+x{{}_{2}}}\right )<f\left ({x{{}_{1}}}\right )+f\left ({x{{}_{2}}}\right )$ .​​​​​​​‌

## 解答

1. （1） $f^{′}{\left ({x}\right )}=\frac {1-x}{{\rm{e}}{{}^{x}}}-\frac {a}{1-x}=\frac {(1-x){{}^{2}}-a{\rm{e}}{{}^{x}}}{\left ({1-x}\right ){\rm{e}}{{}^{x}}},(x<1)$
2. ①当 $a\leqslant 0$ 时， $f^{′}{\left ({x}\right )}>0$ ，此时， $f\left ({x}\right )$ 在 $\left ({-\infty ,1}\right )$ 单调递增；
3. ②当 $a>0$ 时，令 $g\left ({x}\right )=(1-x){{}^{2}}-a{\rm{e}}{{}^{x}}$ ，
4. 可以判断 $g\left ({x}\right )$ 在 $\left ({-\infty ,1}\right )$ 是单调递减的
5. 注意到： $g\left ({-a-1}\right )=(a+2){{}^{2}}-a{\rm{e}}{{}^{-a-1}}>(a+2){{}^{2}}-a>0$
6. $g\left ({1}\right )=-a{\rm{e}}<0$
7. 则必存在 $x{{}_{0}}\in \left ({-\infty ,1}\right )$ 使得 $g\left ({x{{}_{0}}}\right )=0$ ，即 $\left ({1-x{{}_{0}}}\right ){{}^{2}}-a{\rm{e}}{{}^{x{{}_{0}}}}=0$
8. 且当 $x\in \left ({-\infty ,x{{}_{0}}}\right )$ 时， $g\left ({x}\right )>0$ ，于是 $f^{′}{\left ({x}\right )}>0$ ，
9. 此时 $f\left ({x}\right )$ 在 $\left ({-\infty ,x{{}_{0}}}\right )$ 单调递增；
10. 当 $x\in \left ({x{{}_{0}},1}\right )$ 时， $g\left ({x}\right )<0$ ，于是 $f^{′}{\left ({x}\right )}<0$ ，此时 $f\left ({x}\right )$ 在 $\left ({x{{}_{0}},1}\right )$ 单调递减；
11. （2）当 $a>0$ 时，令 $h\left ({x}\right )=f^{′}{\left ({x}\right )}$ ，则：
12. $h^{′}{\left ({x}\right )}=\frac {(x-1){{}^{2}}\left ({x-2}\right )-a{\rm{e}}{{}^{x}}}{(x-1){{}^{2}}{\rm{e}}{{}^{x}}}<0$ 于是： $f^{′}{\left ({x}\right )}$ 在 $\left ({-\infty ,1}\right )$ 是递减的
13. 对于给定的 $x{{}_{2}}\in \left ({-\infty ,0}\right )$ ，令 $φ\left ({x}\right )=f\left ({x+x{{}_{2}}}\right )-f\left ({x}\right )-f\left ({x{{}_{2}}}\right ),x{{}_{2}}\in \left ({-∞,0}\right )$
14. 则 $φ^{′}{\left ({x}\right )}=f^{′}{\left ({x+x{{}_{2}}}\right )}-f^{′}{\left ({x}\right )}$
15. 因为 $x+x{{}_{2}}<x$ ，所以 $f^{′}{\left ({x+x{{}_{2}}}\right )}>f^{′}{\left ({x}\right )}$ ，即 $φ^{′}{\left ({x}\right )}>0$
16. 因此 $φ\left ({x}\right )$ 在 $\left ({-∞,0}\right )$ 是递增的
17. 于是， $φ\left ({x}\right )<φ\left ({0}\right )=-f\left ({0}\right )=0$ ，
18. 即： $f\left ({x+x{{}_{2}}}\right )<f\left ({x}\right )+f\left ({x{{}_{2}}}\right )$
19. 进而 $f\left ({x{{}_{1}}+x{{}_{2}}}\right )<f\left ({x{{}_{1}}}\right )+f\left ({x{{}_{2}}}\right )$
20. 方法二：
21. 当 $a>0$ 时，对于给定的 $x{{}_{2}}\in \left ({-\infty ,0}\right )$ ，令 $φ\left ({x}\right )=f\left ({x+x{{}_{2}}}\right )-f\left ({x}\right )-f\left ({x{{}_{2}}}\right ),x{{}_{2}}\in \left ({-∞,0}\right )$
22. 则 $φ^{′}{\left ({x}\right )}=f^{′}{\left ({x+x{{}_{2}}}\right )}-f^{′}{\left ({x}\right )}=\frac {1-x-x{{}_{2}}}{{\rm{e}}{{}^{x+x{{}_{2}}}}}-\frac {a}{1-x-x{{}_{2}}}-\frac {1-x}{{\rm{e}}{{}^{x}}}+\frac {a}{1-x}$
23. $=\frac {1-x-x{{}_{2}}-\left ({1-x}\right ){\rm{e}}{{}^{x{{}_{2}}}}}{{\rm{e}}{{}^{x+x{{}_{2}}}}}+a\left ({\frac {1}{1-x}-\frac {1}{1-x-x{{}_{2}}}}\right )$
24. $>\frac {1-x-x{{}_{2}}-\left ({1-x}\right )}{{\rm{e}}{{}^{x+x{{}_{2}}}}}+a\left ({\frac {1}{1-x}-\frac {1}{1-x-x{{}_{2}}}}\right )=\frac {-x{{}_{2}}}{{\rm{e}}{{}^{x+x{{}_{2}}}}}+a\left ({\frac {1}{1-x}-\frac {1}{1-x-x{{}_{2}}}}\right )>0$
25. 因此 $φ\left ({x}\right )$ 在 $\left ({-∞,0}\right )$ 是递增的，
26. 于是， $φ\left ({x}\right )<φ\left ({0}\right )=-f\left ({0}\right )=0$ ，即： $f\left ({x+x{{}_{2}}}\right )<f\left ({x}\right )+f\left ({x{{}_{2}}}\right )$
27. 进而 $f\left ({x{{}_{1}}+x{{}_{2}}}\right )<f\left ({x{{}_{1}}}\right )+f\left ({x{{}_{2}}}\right )$

## 知识点

**中文**:
  - 利用导数研究函数的单调性与单调区间
  - 利用导数证明不等式

**English**:
  - Monotonicity and Monotonic Intervals
  - Proving Inequalities using Derivatives

---
