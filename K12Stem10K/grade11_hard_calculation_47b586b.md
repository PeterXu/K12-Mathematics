# Mathematics - 题目 585

**ID**: 47b586b2d277491fa43d04939ea69bfe
**年级**: Grade 11
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )={\ln}x+ax{^{2}}+\left ({2a+1}\right )x\left ({a\in {\mathbf{R}}}\right )$ ．(1)当 $a=-1$ 时，求 $f\left ({x}\right )$ 的极值．(2)讨论 $f\left ({x}\right )$ 的单调性；​​​​​​​‌(3)当 $a=\frac {1}{2}$ 时，求证： $\left [f^{′}{\left ({x}\right )}-2\right ]{^{n}}-f^{′}{\left ({x{^{n}}}\right )}\geqslant 2{^{n}}-4\left ({x\in {\mathbf{N}}{^{*}}}\right )$ ．

## 解答

1. （1）当 $a=-1$ 时， $f\left ({x}\right )={\ln}x-x{^{2}}-x$ ，其中 $x>0$ ，
2. 则 $f^{′}{\left ({x}\right )}=\frac {1}{x}-2x-1=-\frac {2x{^{2}}+x-1}{x}=-\frac {\left ({2x-1}\right )\left ({x+1}\right )}{x}$ ，
3. 令 $f^{′}{\left ({x}\right )}=0$ 可得 $x=\frac {1}{2}$ ，列表如下：
4. $x$
5. $\left ({0,\frac {1}{2}}\right )$
6. $\frac {1}{2}$
7. $\left ({\frac {1}{2},+\infty }\right )$
8. $f^{′}{\left ({x}\right )}$
9. $+$
10. $0$
11. $-$
12. $f\left ({x}\right )$
13. 单调递增
14. 极大值
15. 单调递减
16. 所以，函数 $f\left ({x}\right )$ 的增区间为 $\left ({0,\frac {1}{2}}\right )$ ，减区间为 $\left ({\frac {1}{2},+\infty }\right )$ ，
17. 所以，函数 $f\left ({x}\right )$ 的极大值为 $f\left ({\frac {1}{2}}\right )={\ln}\frac {1}{2}-\frac {3}{4}=-{\ln}2-\frac {3}{4}$ ，无极小值.
18. （2） $f\left ({x}\right )={\ln}x+ax{^{2}}+\left ({2a+1}\right )x\left ({a\in {\mathbf{R}}}\right )$ 的定义域为 $\left ({0,+\mathrm{∞}}\right )$ ，
19. $f^{′}{\left ({x}\right )}=2ax+\left ({2a+1}\right )+\frac {1}{x}=\frac {\left ({2ax+1}\right )\left ({x+1}\right )}{x}$ ，
20. 当 $a\geqslant 0$ 时，对任意的 $x>0$ ， $f^{′}{\left ({x}\right )}>0$ ，此时，函数 $f\left ({x}\right )$ 的增区间为 $\left ({0,+\mathrm{∞}}\right )$ ，无减区间；
21. 当 $a<0$ 时，由 $f^{′}{\left ({x}\right )}>0$ 可得 $0<x<-\frac {1}{2a}$ ，由 $f^{′}{\left ({x}\right )}<0$ 可得 $x>-\frac {1}{2a}$ ，
22. 此时，函数 $f\left ({x}\right )$ 的增区间为 $\left ({0,-\frac {1}{2a}}\right )$ ，减区间为 $\left ({-\frac {1}{2a},+\infty }\right )$ .
23. 综上所述，当 $a\geqslant 0$ 时，函数 $f\left ({x}\right )$ 的增区间为 $\left ({0,+\mathrm{∞}}\right )$ ，无减区间；
24. 当 $a<0$ 时，函数 $f\left ({x}\right )$ 的增区间为 $\left ({0,-\frac {1}{2a}}\right )$ ，减区间为 $\left ({-\frac {1}{2a},+\infty }\right )$ .
25. （3）当 $a=\frac {1}{2}$ 时， $f\left ({x}\right )=\frac {1}{2}x{^{2}}+2x+{\ln}x$ ，其中 $x>0$ ，则 $f^{′}{\left ({x}\right )}=x+2+\frac {1}{x}=\frac {{\left({x+1}\right)^{2}}}{x}$ ，
26. $\left [f^{′}{\left ({x}\right )}-2\right ]{^{n}}-f^{′}{\left ({x{^{n}}}\right )}={\left({x+\frac {1}{x}}\right)^{n}}-\left ({x{^{n}}+\frac {1}{x{^{n}}}+2}\right )$
27. $={\rm{C}}{{}_{n}^{1}}\cdot x{^{n-1}}\cdot \frac {1}{x}+{\rm{C}}{{}_{n}^{2}}\cdot x{^{n-2}}\cdot \frac {1}{x{^{2}}}+\cdots +{\rm{C}}{{}_{n}^{n-1}}\cdot x\cdot \frac {1}{x{^{n-1}}}-2$
28. $={\rm{C}}{{}_{n}^{1}}\cdot x{^{n-2}}+{\rm{C}}{{}_{n}^{2}}\cdot x{^{n-4}}+\cdots +{\rm{C}}{{}_{n}^{n-1}}\cdot \frac {1}{x{^{n-2}}}-2$ ，
29. 记 $S={\rm{C}}{{}_{n}^{1}}\cdot x{^{n-2}}+{\rm{C}}{{}_{n}^{2}}\cdot x{^{n-4}}+\cdots +{\rm{C}}{{}_{n}^{n-1}}\cdot \frac {1}{x{^{n-2}}}-2$ ，
30. 则 $2S={\rm{C}}{{}_{n}^{1}}\left ({x{^{n-2}}+\frac {1}{x{^{n-2}}}}\right )+{\rm{C}}{{}_{n}^{2}}\left ({x{^{n-4}}+\frac {1}{x{^{n-4}}}}\right )+\cdots +{\rm{C}}{{}_{n}^{n-1}}\left ({x{^{n-2}}+\frac {1}{x{^{n-2}}}}\right )-4$
31. $\geqslant 2{\rm{C}}{{}_{n}^{1}}\sqrt {x{^{n-2}}\cdot \frac {1}{x{^{n-2}}}}+2{\rm{C}}{{}_{n}^{2}}\sqrt {x{^{n-4}}\cdot \frac {1}{x{^{n-4}}}}+\cdots +2{\rm{C}}{{}_{n}^{n-1}}\sqrt {x{^{n-2}}\cdot \frac {1}{x{^{n-2}}}}-4$
32. $=2\left ({{\rm{C}}{{}_{n}^{1}}+{\rm{C}}{{}_{n}^{2}}+\cdots +{\rm{C}}{{}_{n}^{n-1}}}\right )-4=2\left ({{\rm{C}}{{}_{n}^{0}}+{\rm{C}}{{}_{n}^{1}}+{\rm{C}}{{}_{n}^{2}}+\cdots +{\rm{C}}{{}_{n}^{n-1}}+{\rm{C}}{{}_{n}^{n}}}\right )-8$
33. $=2\times 2{^{n}}-8=2{^{n+1}}-8$ ，当且仅当 $x=1$ 时，等号成立，
34. 故 $S\geqslant 2{^{n}}-4$ ，故 $\left [f^{′}{\left ({x}\right )}-2\right ]{^{n}}-f^{′}{\left ({x{^{n}}}\right )}\geqslant 2{^{n}}-4\left ({x\in {\mathbf{N}}{^{*}}}\right )$ .

## 知识点

**中文**:
  - 利用导数研究函数的单调性与单调区间
  - 利用导数研究函数的极值
  - 利用导数证明不等式

**English**:
  - Monotonicity and Monotonic Intervals
  - Extrema of Functions using Derivatives
  - Proving Inequalities using Derivatives

---
