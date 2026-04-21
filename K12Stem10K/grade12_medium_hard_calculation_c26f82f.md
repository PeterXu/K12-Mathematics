# Mathematics - 题目 3809

**ID**: c26f82f0d3ac494fa1b6149cf6ca2144
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=ax^{2}+\left ({a-2}\right )x-x{\ln}x$ ．(1)设 $a=0$ ．①求曲线 $y=f\left ({x}\right )$ 在点 $\left ({1,f\left ({1}\right )}\right )$ 处的切线方程．②试问 $f\left ({x}\right )$ 有极大值还是极小值？并求出该极值．(2)若 $f\left ({x}\right )$ 在 $\left ({0,{\rm{e}}}\right )$ 上恰有两个零点，求a的取值范围．​​​​​​​‌

## 解答

1. （1）①当 $a=0$ 时， $f\left ({x}\right )=-2x-x{\ln}x$ ，则 $f^{′}\left ({x}\right )=-2-(1+{\ln}x)=-3-{\ln}x$ ，
2. 所以 $f\left ({1}\right )=-2,f^{′}\left ({1}\right )=-3$ ，所以曲线 $y=f\left ({x}\right )$ 在点 $\left ({1,f\left ({1}\right )}\right )$ 处的切线方程为 $y+2=(-3)\left ({x-1}\right )$ ，
3. 即 $y=-3x+1$ ．
4. ②令 $f^{′}\left ({x}\right )=0$ 得 $x{\rm{=}}{\rm{e}}^{-3}$ ，令 $f^{′}\left ({x}\right )>0$ 得 $0<x<{\rm{e}}^{-3}$ ，令 $f^{′}\left ({x}\right )<0$ 得 $x>{\rm{e}}^{-3}$ ，
5. 所以 $f\left ({x}\right )$ 在 $(0,{\rm{e}}^{-3})$ 上单调递增，在 $({\rm{e}}^{-3},+∞)$ 上单调递减，
6. 由极值的定义知，当 $x{\rm{=}}{\rm{e}}^{-3}$ 时，函数 $f\left ({x}\right )$ 有极大值 $f\left ({{\rm{e}}^{-3}}\right )=-2{\rm{e}}^{-3}-{\rm{e}}^{-3}{\ln}{\rm{e}}^{-3}={\rm{e}}^{-3}$ ，无极小值.
7. （2）因为函数 $f\left ({x}\right )$ 在 $\left ({0,{\rm{e}}}\right )$ 上恰有两个零点，所以方程 $ax^{2}+\left ({a-2}\right )x-x{\ln}x=0$ 在 $\left ({0,{\rm{e}}}\right )$ 上有两个解，
8. 即 $a=\frac {2+{\ln}x}{x+1}$ 在 $\left ({0,{\rm{e}}}\right )$ 上有两个解，
9. 记 $h(x)=\frac {2+{\ln}x}{x+1}$ ， $x\in \left ({0,{\rm{e}}}\right )$ ，则直线 $y=a$ 与函数 $h(x)=\frac {2+{\ln}x}{x+1}$ ， $x\in \left ({0,{\rm{e}}}\right )$ 有两个交点，
10. 则 $h^{′}(x)=\frac {\frac {1}{x}(x+1)-(2+{\ln}x)}{(x+1)^{2}}=\frac {1-x-x{\ln}x}{x(x+1)^{2}}$ ，
11. 记 $m(x)=1-x-x{\ln}x$ ，则 $m^{′}(x)=-1-(1+{\ln}x)=-2-{\ln}x$ ，
12. 令 $m^{\prime }\left ({x}\right )>0$ 得 $0<x<{\rm{e}}^{-2}$ ，令 $m^{′}\left ({x}\right )<0$ 得 ${\rm{e}}^{-2}<x<{\rm{e}}$ ，
13. 所以 $m(x)$ 在 $(0,{\rm{e}}^{-2})$ 上单调递增，在 $({\rm{e}}^{-2},{\rm{e}})$ 上单调递减，
14. 令 $m(x)=0$ 得 $x=1$ ，又 $m\left ({{\rm{e}}^{-2}}\right )=1+{\rm{e}}^{-2}>0,m\left ({{\rm{e}}}\right )=1-2{\rm{e}}<0$ ，
15. 所以当 $0<x<1$ 时， $m(x)>0$ ， $h^{′}(x)>0$ ，函数 $h(x)$ 单调递增，
16. 当 $1<x<{\rm{e}}$ 时， $m(x)<0$ ， $h^{′}(x)<0$ ，函数 $h(x)$ 单调递减，
17. 又 $h({\rm{e}}^{-2})=0$ ， $h(1)=1,h({\rm{e}})=\frac {3}{{\rm{e}}+1}$ ，
18. 如图，
19. 
20. 由图知，要使直线 $y=a$ 与函数 $h(x)=\frac {2+{\ln}x}{x+1}$ ， $x\in \left ({0,{\rm{e}}}\right )$ 有两个交点，则 $\frac {3}{{\rm{e}}+1}<a<{\rm{1}}$ ，
21. 所以函数 $f\left ({x}\right )$ 在 $\left ({0,{\rm{e}}}\right )$ 上恰有两个零点时，a的取值范围为 $\frac {3}{{\rm{e}}+1}<a<{\rm{1}}$ .

## 知识点

**中文**:
  - 利用导数研究函数的极值
  - 导数几何意义的应用
  - 利用导数解决函数零点问题

**English**:
  - Extrema of Functions using Derivatives
  - Applications of Geometric Meaning of Derivatives
  - Solving Zero Point Problems

---
