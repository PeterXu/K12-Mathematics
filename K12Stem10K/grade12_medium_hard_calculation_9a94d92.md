# Mathematics - 题目 281

**ID**: 9a94d92aeec64604bf909daeb109f825
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=x{\ln}x$ ．（1）若直线l过点 $\left ({1,0}\right )$ ，并且与曲线 $y=f\left ({x}\right )$ 相切，求直线的方程；​​​​​​​‌（2）设函数 $g\left ({x}\right )=f\left ({x}\right )-a\left ({x-1}\right )$ 在 $\left [1,{\rm{e}}\right ]$ 上有且只有一个零点，求a的取值范围．（其中 $a\in {\rm{R}}{\rm ，e}$ 为自然对数的底数）

## 解答

1. （1）由题可得 $f^{′}{\left ({x}\right )}={\ln}x+1$ ，
2. 设切点坐标为 $\left ({x{{}_{0}},y{{}_{0}}}\right )$ ，则切线的斜率为 ${\ln}x{{}_{0}}+1$ ，
3. 所以切线l的方程为 $y-x{{}_{0}}{\ln}x{{}_{0}}=\left ({{\ln}x{{}_{0}}+1}\right )\left ({x-x{{}_{0}}}\right )$ ，
4. 又切线l过点 $\left ({1,0}\right )$ ，
5. 所以有 $-x{{}_{0}}{\ln}x{{}_{0}}=\left ({{\ln}x{{}_{0}}+1}\right )\left ({1-x{{}_{0}}}\right )$ ，即 ${\ln}x{{}_{0}}=x{{}_{0}}-1$ ，
6. 设 $h\left ({x}\right )={\ln}x-x+1$ ，则 $h^{′}{\left ({x}\right )}=\frac {1-x}{x}$ ，
7. 当 $x\in \left ({0,1}\right )$ 时， $h^{′}{\left ({x}\right )}>0$ ， $h\left ({x}\right )$ 单调递增，
8. 当 $x\in \left ({1,+∞}\right )$ 时， $h^{′}{\left ({x}\right )}<0$ ， $h\left ({x}\right )$ 单调递减，
9. 所以 $h\left ({x}\right ){{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}=h\left ({1}\right )=0$ ，
10. 即 $h\left ({x}\right )=0$ 只有唯一解，所以 $x{{}_{0}}=1$ ， $y{{}_{0}}=0$ ．
11. 所以直线l的方程为 $y=x-1$ ．
12. （2）因为 $g\left ({x}\right )=x{\ln}x-a\left ({x-1}\right )$ ，注意到 $g\left ({1}\right )=0$ ，
13. 所以所求问题等价于函数 $g\left ({x}\right )=x{\ln}x-a\left ({x-1}\right )$ 在 $\left ({1,{\rm{e}}}\right ]$ 上没有零点．
14. 因为 $g^{′}{\left ({x}\right )}={\ln}x+1-a$ ．
15. 所以由 $g^{′}{\left ({x}\right )}<0$ ，得 ${\ln}x+1-a<0$ ，即 $0<x<{\rm{e}}{^{a-1}}$ ，
16. 由 $g^{′}{\left ({x}\right )}>0$ ，得 $x>{\rm{e}}{^{a-1}}$ ，
17. 所以 $g\left ({x}\right )$ 在 $\left ({0,{\rm{e}}{^{a-1}}}\right )$ 上单调递减，在 $\left ({{\rm{e}}{^{a-1}},+∞}\right )$ 上单调递增．
18. ①当 ${\rm{e}}{^{a-1}}\leqslant 1$ ，即 $a\leqslant 1$ 时， $g\left ({x}\right )$ 在 $\left ({1,{\rm{e}}}\right ]$ 上单调递增，所以 $g\left ({x}\right )>g\left ({1}\right )=0$ ．
19. 此时函数 $g\left ({x}\right )$ 在 $\left ({1,{\rm{e}}}\right ]$ 上没有零点，
20. ②当 $1<{\rm{e}}{^{a-1}}<{\rm{e}}$ ，即 $1<a<2$ 时， $g\left ({x}\right )$ 在 $\left [{1,{\rm{e}}{^{a-1}}}\right )$ 上单调递减，在 $\left ({{\rm{e}}{^{a-1}},{\rm{e}}}\right ]$ 上单调递增，
21. 又因为 $g\left ({1}\right )=0$ ， $g\left ({{\rm{e}}}\right )={\rm{e}}-a{\rm{e}}+a$ ，
22. $g\left ({x}\right )$ 在 $\left ({1,{\rm{e}}}\right ]$ 上的最小值为 $g\left ({{\rm{e}}{^{a-1}}}\right )=a-{\rm{e}}{^{a-1}}$ ，
23. 所以当 $1<a\leqslant \frac {{\rm{e}}}{{\rm{e}}-1}$ 时， $g\left ({x}\right )$ 在 $(1,{\rm{e}}{\rm{]}}$ 上的最大值 $g\left ({{\rm{e}}}\right )\geqslant 0$ ，即此时函数 $g\left ({x}\right )$ 在 $\left ({1,{\rm{e}}}\right ]$ 上有零点．
24. 当 $\frac {{\rm{e}}}{{\rm{e}}-1}<a<2$ 时， $g\left ({{\rm{e}}}\right )<0$ ，此时函数 $g\left ({x}\right )$ 在 $\left ({1,{\rm{e}}}\right ]$ 上没有零点，
25. ③当 ${\rm{e}}\leqslant {\rm{e}}{^{a-1}}$ ，即 $a\geqslant 2$ 时， $g\left ({x}\right )$ 在 $\left [1,{\rm{e}}\right ]$ 上单调递减，
26. 所以 $g\left ({x}\right )$ 在 $(1,{\rm{e}}{\rm{]}}$ 上满足 $g\left ({x}\right )<g\left ({1}\right )=0$ ，
27. 此时函数 $g\left ({x}\right )$ 在 $\left ({1,{\rm{e}}}\right ]$ 上没有零点．
28. 综上，所求的a的取值范围是 $a\leqslant 1$ 或 $a>\frac {{\rm{e}}}{{\rm{e}}-1}$ ．

## 知识点

**中文**:
  - 利用导数解决函数零点问题
  - 导数几何意义的应用

**English**:
  - Solving Zero Point Problems
  - Applications of Geometric Meaning of Derivatives

---
