# Mathematics - 题目 256

**ID**: 4d60a56e19034fc983642a9cc1b1ee8c
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=a{\ln}x+\frac {2}{x+1}\left ({a\in {\rm{R}}}\right )$ ．(1)当 $a=1$ 时，求曲线 $y=f(x)$ 在点 $(1,f(1))$ 处的切线方程；​​​​​​​‌(2)若方程 $f(x)-1=0$ 有3个不同的实数解，求a的取值范围．

## 解答

1. （1）当 $a=1$ 时， $f(x)={\ln}x+\frac {2}{x+1}$ 的定义域为 $\left ({0,+∞}\right )$ ，
2. 所以 $f^{′}(x)=\frac {1}{x}-\frac {2}{{\left({x+1}\right)^{2}}}$ ， $f^{′}(1)=1-\frac {1}{2}=\frac {1}{2}$ ，
3. 又因为 $f(1)={\ln}1+\frac {2}{1+1}=1$ ，所以切点为 $(1,1)$ ，
4. 所以曲线 $y=f(x)$ 在点 $(1,f(1))$ 处的切线方程为： $y-1=\frac {1}{2}\left ({x-1}\right )$ ，
5. 化简可得： $x-2y+1=0$ .
6. （2）令 $g\left ({x}\right )=f(x)-1=a{\ln}x+\frac {2}{x+1}-1$ ，
7. 函数 $g\left ({x}\right )$ 的定义域为 $\left ({0,+∞}\right )$ ，
8. $g^{′}{\left ({x}\right )}=\frac {a}{x}-\frac {2}{{\left({x+1}\right)^{2}}}=\frac {a{\left({x+1}\right)^{2}}-2x}{x{\left({x+1}\right)^{2}}}=\frac {ax{^{2}}+\left ({2a-2}\right )x+a}{x{\left({x+1}\right)^{2}}}$ ．
9. ①当 $a\leqslant 0$ 时， $g^{′}{\left ({x}\right )}<0$ ，函数 $g\left ({x}\right )$ 在区间 $\left ({0,+∞}\right )$ 上单调递减，
10. 函数 $g\left ({x}\right )$ 至多一个零点，不合题意；
11. ②当 $a>0$ 时，设函数 $h\left ({x}\right )=ax{^{2}}+\left ({2a-2}\right )x+a$ ， ${\rm{Δ}}={\left({2a-2}\right)^{2}}-4a{^{2}}=-8a+4$ ，
12. 当 $a\geqslant \frac {1}{2}$ 时， ${\rm{Δ}}\leqslant 0$ ，即 $h\left ({x}\right )\geqslant 0$ 对任意的 $x>0$ 恒成立，即 $g^{′}{\left ({x}\right )}\geqslant 0$ ，
13. 所以函数 $g\left ({x}\right )$ 在区间 $\left ({0,+∞}\right )$ 上单调递增，函数 $g\left ({x}\right )$ 至多一个零点，不合题意；
14. 当 $0<a<\frac {1}{2}$ 时，因为 ${\rm{Δ}}=-8a+4>0$ ，所以方程 $ax{^{2}}+\left ({2a-2}\right )x+a=0$ 有两个实数根 $x{{}_{1}}$ 、 $x{{}_{2}}$ ，
15. 且满足 $x{{}_{1}}+x{{}_{2}}=\frac {2}{a}-2>0$ ， $x{{}_{1}}x{{}_{2}}=1$ ，
16. 不妨设 $x{{}_{1}}<x{{}_{2}}$ ，则 $0<x{{}_{1}}<1<x{{}_{2}}$ ， $f^{′}{\left ({x}\right )}$ 、 $f\left ({x}\right )$ 的情况如下：
17. $x$
18. $\left ({0,x{{}_{1}}}\right )$
19. $x{{}_{1}}$
20. $\left ({x{{}_{1}},x{{}_{2}}}\right )$
21. $x{{}_{2}}$
22. $\left ({x{{}_{2}},+∞}\right )$
23. $f^{′}{\left ({x}\right )}$
24. $+$
25. $0$
26. $-$
27. $0$
28. $+$
29. $f\left ({x}\right )$
30. 增
31. 极大值
32. 减
33. 极小值
34. 增
35. 所以函数 $f\left ({x}\right )$ 的单调递增区间是 $\left ({0,x{{}_{1}}}\right )$ 、 $\left ({x{{}_{2}},+∞}\right )$ ，单调递减区间是 $\left ({x{{}_{1}},x{{}_{2}}}\right )$ ．
36. 因为 $g\left ({1}\right )=0$ ，所以 $1$ 为 $g\left ({x}\right )$ 的一个零点．
37. 又 $g\left ({x{{}_{1}}}\right )>g\left ({1}\right )=0$ ， $0<{\rm{e}}{^{-\frac {1}{a}}}<1$ ，且 $f\left ({{\rm{e}}{^{-\frac {1}{a}}}}\right )=\frac {-2{\rm{e}}{^{-\frac {1}{a}}}}{{\rm{e}}{^{-\frac {1}{a}}}+1}<0$ ，
38. 所以存在唯一实数 $t{{}_{1}}\in \left ({0,1}\right )$ ，使得 $g\left ({t{{}_{1}}}\right )=0$ ．
39. 又 $g\left ({x{{}_{2}}}\right )<g\left ({1}\right )=0$ ， ${\rm{e}}{^{\frac {1}{a}}}>1$ ，且 $f\left ({{\rm{e}}{^{\frac {1}{a}}}}\right )=\frac {2}{{\rm{e}}{^{\frac {1}{a}}}+1}>0$ ，
40. 所以存在唯一实数 $t{{}_{2}}\in \left ({1,+∞}\right )$ ，使得 $g\left ({t{{}_{2}}}\right )=0$ ．
41. 所以函数 $g\left ({x}\right )$ 有 $3$ 个不同的零点，方程 $f(x)-1=0$ 有3个不同的实数解，
42. 综上， $a$ 的取值范围为 $\left ({0,\frac {1}{2}}\right )$ ．

## 知识点

**中文**:
  - 利用导数研究方程的根
  - 导数几何意义的应用

**English**:
  - Studying Equation Roots
  - Applications of Geometric Meaning of Derivatives

---
