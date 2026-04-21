# Mathematics - 题目 3195

**ID**: 3ddef9f2c7754ba6bbac88a3c72bb1c2
**年级**: Grade 11
**难度**: Medium
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\left ({x-a}\right ){\rm{l}}{\rm{n}}x-x{\rm{l}}{\rm{n}}a+b$ .​​​​​​​‌（1）若 $a=1$ ，判断 $f\left ({x}\right )$ 的单调性；（2）已知 $f\left ({x}\right )$ 有两个零点 $x{{}_{1}}$ ， $x{{}_{2}}\left ({x{{}_{1}}<x{{}_{2}}}\right )$ .${\rm （i）}$ 证明： $b<a{\rm{l}}{\rm{n}}a$ ；${\rm （ii）}$ 证明： $x{{}_{1}}+x{{}_{2}}+2\sqrt {x{{}_{1}}x{{}_{2}}}>4a$ .

## 解答

1. （1）当 $a=1$ 时， $f\left ({x}\right )=\left ({x-1}\right ){\rm{l}}{\rm{n}}x+b$ ，易得 $f\left ({x}\right )$ 的定义域为 $\left ({0,+∞}\right )$ ，
2. 且 $f^{′}{\left ({x}\right )}=\frac {x-1}{x}+{\rm{l}}{\rm{n}}x$ ， $f^{′}{\left ({1}\right )}=0$ ，
3. $x>1$ 时， $f^{′}{\left ({x}\right )}>0$ ， $0<x<1$ 时， $f^{′}{\left ({x}\right )}<0$ ，
4. 所以 $f\left ({x}\right )$ 在区间 $\left ({0,1}\right )$ 上单调递减，在区间 $\left ({1,+∞}\right )$ 上单调递增；
5. （2）（i）由题设 $f^{′}{\left ({x}\right )}=\frac {x-a}{x}+{\ln}x-{\ln}a$ 且 $x>0,a>0$ ，则 $f^{′}{\left ({a}\right )}=0$ ，
6. 当 $0<x<a$ 时， $f^{′}{\left ({x}\right )}<0$ ， $x>a$ 时， $f^{′}{\left ({x}\right )}>0$ ，
7. $f\left ({x}\right )$ 在 $\left ({0,a}\right )$ 上单调递减，在 $\left ({a,+∞}\right )$ 上单调递增，则 $f\left ({x}\right )\geqslant f\left ({a}\right )=-a{\ln}a+b$ ，
8. 由 $x$ 趋向于 $0$ 或 $+\infty $ 时， $f\left ({x}\right )$ 都趋向于 $+\infty $ ，由 $f\left ({x}\right )$ 有两个零点，
9. 所以 $f\left ({x}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=-a{\rm{l}}{\rm{n}}a+b<0$ ，即 $b>a{\rm{l}}{\rm{n}}a$ ，命题得证；
10. ${\rm （ii）}$ 证明：由题意 $\begin{cases}\left ({x{{}_{1}}-a}\right ){\rm{l}}{\rm{n}}x{{}_{1}}-x{{}_{1}}{\rm{l}}{\rm{n}}a=-b\\\left ({x{{}_{2}}-a}\right ){\rm{l}}{\rm{n}}x{{}_{2}}-x{{}_{2}}{\rm{l}}{\rm{n}}a=-b\end{cases}$ ，即 $\begin{cases}\left ({\frac {x{{}_{1}}}{a}-1}\right ){\rm{l}}{\rm{n}}x{{}_{1}}-\frac {x{{}_{1}}}{a}{\rm{l}}{\rm{n}}a=-\frac {b}{a}\\\left ({\frac {x{{}_{2}}}{a}-1}\right ){\rm{l}}{\rm{n}}x{{}_{2}}-\frac {x{{}_{2}}}{a}{\rm{l}}{\rm{n}}a=-\frac {b}{a}\end{cases}$ ，
11. 所以 $\begin{cases}\left ({\frac {x{{}_{1}}}{a}-1}\right ){\rm{l}}{\rm{n}}\frac {x{{}_{1}}}{a}=-\frac {b}{a}+{\rm{l}}{\rm{n}}a\\\left ({\frac {x{{}_{2}}}{a}-1}\right ){\rm{l}}{\rm{n}}\frac {x{{}_{2}}}{a}=-\frac {b}{a}+{\rm{l}}{\rm{n}}a\end{cases}$ ，记 $g\left ({x}\right )=\left ({x-1}\right ){\rm{l}}{\rm{n}}x$ ，则 $g\left ({\frac {x{{}_{1}}}{a}}\right )=g\left ({\frac {x{{}_{2}}}{a}}\right )$ ，
12. 要证 $x{{}_{1}}+x{{}_{2}}+2\sqrt {x{{}_{1}}x{{}_{2}}}>4a$ ，即证 $\frac {x{{}_{1}}}{a}+\frac {x{{}_{2}}}{a}+2\sqrt {\frac {x{{}_{1}}x{{}_{2}}}{a{^{2}}}}>4$ ，即证 $\sqrt {\frac {x{{}_{1}}}{a}}+\sqrt {\frac {x{{}_{2}}}{a}}>2$ ，
13. 记 $t{{}_{1}}=\sqrt {\frac {x{{}_{1}}}{a}}$ ， $t{{}_{2}}=\sqrt {\frac {x{{}_{2}}}{a}}$ ，则 $g\left ({t{{}_{1}^{2}}}\right )=g\left ({t{{}_{2}^{2}}}\right )$ ，
14. 记 $h\left ({x}\right )=g\left ({x{^{2}}}\right )=2\left ({x{^{2}}-1}\right ){\rm{l}}{\rm{n}}x$ ，则 $h\left ({t{{}_{1}}}\right )=h\left ({t{{}_{2}}}\right )$ ，
15. 同（1）分析得， $g\left ({x}\right )$ 在区间 $\left ({0,1}\right )$ 上单调递减，在区间 $\left ({1,+∞}\right )$ 上单调递增，
16. 所以 $h\left ({x}\right )$ 在区间 $\left ({0,1}\right )$ 上单调递减，在区间 $\left ({1,+∞}\right )$ 上单调递增；
17. 下证 $t{{}_{1}}+t{{}_{2}}>2$ ，由 $0<t{{}_{1}}<1<t{{}_{2}}$ ，由于 $t{{}_{2}}\geqslant 2$ 时， $t{{}_{1}}+t{{}_{2}}>2$ 显然成立，
18. 故只需考虑 $1<t{{}_{2}}<2$ 时， $t{{}_{1}}+t{{}_{2}}>2$ 是否成立，要证 $t{{}_{1}}+t{{}_{2}}>2$ ，即证 $t{{}_{1}}>2-t{{}_{2}}$ ，
19. 由 $h\left ({x}\right )$ 在区间 $\left ({0,1}\right )$ 上单调递减，即证 $h\left ({t{{}_{1}}}\right )=h\left ({t{{}_{2}}}\right )<h\left ({2-t{{}_{2}}}\right )$ ，
20. 即证 $2\left ({t{{}_{2}^{2}}-1}\right ){\rm{l}}{\rm{n}}t{{}_{2}}<2\left [{\left({2-t{{}_{2}}}\right)^{2}}-1\right ]{\rm{l}}{\rm{n}}\left ({2-t{{}_{2}}}\right )$ ，即证 $\left ({t{{}_{2}}+1}\right ){\rm{l}}{\rm{n}}t{{}_{2}}<\left ({t{{}_{2}}-3}\right ){\rm{l}}{\rm{n}}\left ({2-t{{}_{2}}}\right )$ ，
21. 记 $t\left ({x}\right )=\left ({x+1}\right ){\rm{l}}{\rm{n}}x-\left ({x-3}\right ){\rm{l}}{\rm{n}}\left ({2-x}\right )$ ， $x\in \left ({1,2}\right )$ ， $t^{′}{\left ({x}\right )}=\frac {1}{x}+{\rm{l}}{\rm{n}}\frac {x}{2-x}-\frac {1}{2-x}$ ，
22. 记 $m\left ({x}\right )=t^{′}{\left ({x}\right )}$ ， $x\in \left ({1,2}\right )$ ， $m^{′}{\left ({x}\right )}=\frac {-4{\left({x-1}\right)^{2}}}{x{^{2}}{\left({x-2}\right)^{2}}}<0$ ，所以 $m\left ({x}\right )$ 在 $\left ({1,2}\right )$ 上单调递减，
23. 又 $m\left ({1}\right )=0$ ，所以 $m\left ({x}\right )<0\left ({1<x<2}\right )$ ，所以 $t\left ({x}\right )$ 在区间 $\left ({1,2}\right )$ 上单调递减，
24. 又 $t\left ({1}\right )=0$ ，所以 $t\left ({x}\right )<0$ ，故 $x{{}_{1}}+x{{}_{2}}+2\sqrt {x{{}_{1}}x{{}_{2}}}>4a$ .

## 知识点

**中文**:
  - 利用导数研究函数的单调性与单调区间
  - 利用导数证明不等式
  - 利用导数解决函数零点问题

**English**:
  - Monotonicity and Monotonic Intervals
  - Proving Inequalities using Derivatives
  - Solving Zero Point Problems

---
