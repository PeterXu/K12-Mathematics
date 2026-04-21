# Mathematics - 题目 3901

**ID**: b8041c4e9a0e467993219d4c51b3b49b
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=x-{\rm{l}}{\rm{n}}x-2$ .​​​​​​​‌（1）求曲线 $y=f\left ({x}\right )$ 在点 $\left ({1,f\left ({1}\right )}\right )$ 处的切线方程；（2）函数 $f\left ({x}\right )$ 在区间 $\left ({k,k+1}\right )\left ({k\in {\rm{N}}}\right )$ 上有零点，求 $k$ 的值；（3）记函数 $g\left ({x}\right )=\frac {1}{2}x{^{2}}-bx-2-f\left ({x}\right )$ ，设 $x{{}_{1}}$ ， $x{{}_{2}}(x{{}_{1}}<x{{}_{2}})$ 是函数 $g\left ({x}\right )$ 的两个极值点，若 $b\geqslant \frac {3}{2}$ ，且 $g\left ({x{{}_{1}}}\right )-g\left ({x{{}_{2}}}\right )\geqslant k$ 恒成立，求实数 $k$ 的最大值.

## 解答

1. （1）因为 $f(x)=x-{\ln}x-2$ ，所以 $f{^{\prime }}(x)=1-\frac {1}{x}$ ，则切线斜率为 $f^{′}{\left ({1}\right )}=0$ ，
2. 又 $f\left ({1}\right )=-1$ ，切点为 $\left ({1,-1}\right )$ ，所以切线方程为 $y=-1$ ；
3. （2） $\because f^{′}(x)=\frac {x-1}{x}$ ， $x\in \left ({0,+∞}\right )$ ，
4. 当 $0<x<1$ 时， $f^{′}(x)<0$ ，函数 $f(x)$ 单调递减；
5. 当 $x>1$ 时， $f^{′}(x)>0$ ，函数 $f(x)$ 单调递增，
6. 所以 $f(x)$ 的极小值为 $f\left ({1}\right )=-1<0$ ， $f({\rm{e}}{^{-2}})={\rm{e}}{^{-2}}-{\ln}{\rm{e}}{^{-2}}-2={\rm{e}}{^{-2}}>0$ ，
7. $\therefore f(x)$ 在区间 $(0,1)$ 上存在一个零点 $x{{}_{3}}$ ，此时 $k=0$ ；
8. 又 $f\left ({3}\right )=3-{\ln}3-2=1-{\ln}3<0$ ， $f\left ({4}\right )=4-{\ln}4-2=2-2{\ln}2=2(1-{\ln}2)>0$ ，
9. $\therefore f(x)$ 在区间 $(3,4)$ 上存在一个零点 $x{{}_{4}}$ ，此时 $k=3$ ，
10. 综上， $k$ 的值为 $0$ 或 $3$ ；
11. （3）函数 $g(x)=\frac {1}{2}x{^{2}}-bx-2-f(x)={\ln}x+\frac {1}{2}x{^{2}}-(b+1)x$ ， $x\in \left ({0,+∞}\right )$ ，
12. 所以 $g^{′}(x)=\frac {1}{x}+x-(b+1)=\frac {x{^{2}}-(b+1)x+1}{x}$ ，
13. 由 $g^{′}(x)=0$ 得 $x{^{2}}-(b+1)x+1=0$ ，依题意方程 $x{^{2}}-(b+1)x+1=0$ 有两不相等的正实根 $x{{}_{1}}$ 、 $x{{}_{2}}$ ，
14. 则 $\begin{cases}{\rm{Δ}}=\left [-\left ({b+1}\right )\right ]{^{2}}-4>0\\x{{}_{1}}+x{{}_{2}}=b+1>0\\x{{}_{1}}x{{}_{2}}=1>0\end{cases}$ ，所以 $b>1$ ，
15. $\therefore x{{}_{1}}+x{{}_{2}}=b+1$ ， $x{{}_{1}}x{{}_{2}}=1$ ， $\therefore $  $x{{}_{2}}=\frac {1}{x{{}_{1}}}$ ，
16. 又 $b\geqslant \frac {3}{2}$ ， $x{{}_{1}}+\frac {1}{x{{}_{1}}}=b+1\geqslant \frac {5}{2}$ ， $0<x{{}_{1}}<x{{}_{2}}=\frac {1}{x{{}_{1}}}$ ，解得 $0<x{{}_{1}}\mathrm{\leqslant }\frac {1}{2}$ ，
17. $\therefore g(x{{}_{1}})-g(x{{}_{2}})={\ln}\frac {x{{}_{1}}}{x{{}_{2}}}+\frac {1}{2}(x{{}_{1}^{2}}-x{{}_{2}^{2}})-(b+1)(x{{}_{1}}-x{{}_{2}})=2{\ln}x{{}_{1}}-\frac {1}{2}(x{{}_{1}^{2}}-\frac {1}{x{{}_{1}^{2}}})$ ，
18. 构造函数 $F(x)=2{\ln}x-\frac {1}{2}(x{^{2}}-\frac {1}{x{^{2}}})$ ， $x\in \left ({0,\frac {1}{2}}\right ]$ ，
19. 所以 $F^{′}(x)=\frac {2}{x}-x-\frac {1}{x{^{3}}}=\frac {-(x{^{2}}-1){^{2}}}{x{^{3}}}<0$ ，
20. $\therefore F(x)$ 在 $\left ({0,\frac {1}{2}}\right ]$ 上单调递减，
21. 所以当 $x=\frac {1}{2}$ 时， $F(x){{}_{{\rm \min }}}=F(\frac {1}{2})=\frac {15}{8}-2{\ln}2$ ，
22. 因为 $g\left ({x{{}_{1}}}\right )-g\left ({x{{}_{2}}}\right )\geqslant k$ 恒成立，
23. 所以 $k\leqslant \frac {15}{8}-2{\ln}2$ ，则 $k$ 的最大值为 $\frac {15}{8}-2{\ln}2$ ．

## 知识点

**中文**:
  - 利用导数解决不等式恒成立问题
  - 导数几何意义的应用
  - 利用导数解决函数零点问题

**English**:
  - Solving Universally True Inequalities
  - Applications of Geometric Meaning of Derivatives
  - Solving Zero Point Problems

---
