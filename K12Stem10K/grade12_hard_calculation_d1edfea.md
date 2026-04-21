# Mathematics - 题目 3703

**ID**: d1edfeaa3a1b429d98d847c250f0ab3a
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=x{\ln}\left ({2x+1}\right )-ax{^{2}}$ .​​​​​​​‌(1)求曲线 $y=f\left ({x}\right )$ 在点 $\left ({0,f\left ({0}\right )}\right )$ 处的切线方程；(2)当 $a<0$ 时，求证：函数 $f\left ({x}\right )$ 存在极小值；(3)求函数 $f\left ({x}\right )$ 的零点个数.

## 解答

1. （1）由函数 $f\left ({x}\right )=x{\ln}\left ({2x+1}\right )-ax{^{2}}$ 求导得： $f^{′}{\left ({x}\right )}={\ln}\left ({2x+1}\right )+\frac {2x}{2x+1}-2ax$ ，
2. 所以 $f^{′}(0)=0$ ，因为 $f(0)=0$ ，
3. 所以曲线 $y=f(x)$ 在点 $(0,f(0))$ 处的切线方程是 $y=0$ .
4. （2）函数 $f\left ({x}\right )=x{\ln}\left ({2x+1}\right )-ax{^{2}}$ 的定义域为 $(-\frac {1}{2},+\infty )$ ，由（1）知， $f^{′}{\left ({x}\right )}={\ln}\left ({2x+1}\right )+\frac {2x}{2x+1}-2ax$ ，
5. 因为 $a<0$ ，则当 $-\frac {1}{2}<x<0$ 时， ${\ln}(2x+1)<0$ ， $\frac {2x}{2x+1}<0$ ， $-2ax<0$ ，
6. 所以，有 $f^{′}(x)<0$ ，函数 $f(x)$ 在 $(-\frac {1}{2},0)$ 上单调递减，
7. 当 $x>0$ 时， ${\ln}(2x+1)>0$ ， $\frac {2x}{2x+1}>0$ ， $-2ax>0$ ，则有 $f^{′}(x)>0$ ，函数 $f(x)$ 在 $(0,+\infty )$ 上单调递增，
8. 所以，当 $x=0$ 时，函数 $f(x)$ 取得极小值，
9. 所以，当 $a<0$ 时，函数 $f(x)$ 存在极小值.
10. （3）函数 $f\left ({x}\right )=x{\ln}\left ({2x+1}\right )-ax{^{2}}$ 的定义域为 $(-\frac {1}{2},+\infty )$ ， $f\left ({x}\right )=0\Leftrightarrow x{\ln}\left ({2x+1}\right )=ax{^{2}}$ ，
11. 显然 $x=0$ 是函数 $f(x)$ 的零点，
12. 当 $x\ne 0$ 时，函数 $f(x)$ 的零点即为方程 $a=\frac {{\ln}(2x+1)}{x}$ 的解，
13. 令 $g\left ({x}\right )=\frac {{\ln}\left ({2x+1}\right )}{x},x\in \left ({-\frac {1}{2}{\rm{,}}0}\right )\cup \left ({0,+\infty }\right )$ ，则 $g^{′}{\left ({x}\right )}=\frac {\frac {2x}{2x+1}-{\ln}\left ({2x+1}\right )}{x{^{2}}}$ ，
14. 令 $h\left ({x}\right )=\frac {2x}{2x+1}-{\ln}\left ({2x+1}\right )$ ，则 $h^{′}{\left ({x}\right )}=\frac {2}{{\left({2x+1}\right)^{2}}}-\frac {2}{2x+1}=-\frac {4x}{{\left({2x+1}\right)^{2}}}$ ，
15. 当 $-\frac {1}{2}<x<0$ 时， $h^{′}(x)>0$ ，当 $x>0$ 时， $h^{′}(x)<0$ ，
16. 所以函数 $h(x)$ 在 $(-\frac {1}{2},0)$ 上单调递增，在 $(0,+\infty )$ 上单调递减，
17. $\forall x\in \left ({-\frac {1}{2},0}\right )\cup \left ({0,+\infty }\right )$ ， $h(x)<h(0)=0$ ，
18. 所以，有 $g^{′}(x)<0$ ， $g(x)$ 在 $(-\frac {1}{2},0)$ ， $(0,+\infty )$ 上都递减，
19. 令 $φ(x)={\ln}(2x+1)-2x$ ， $φ^{′}{\left ({x}\right )}=\frac {2}{2x+1}-2=-\frac {4x}{2x+1}$ ，
20. 当 $-\frac {1}{2}<x<0$ 时， $φ{^{\prime }}(x)>0$ ，当 $x>0$ 时， $φ{^{\prime }}(x)<0$ ，
21. 所以， $φ(x)$ 在 $(-\frac {1}{2},0)$ 上单调递增，在 $(0,+\infty )$ 上单调递减， $φ(x)\leqslant φ(0)=0$ ，
22. 所以， $\forall x\in (-\frac {1}{2},+\infty )$ ，恒有 ${\ln}(2x+1)\leqslant 2x$ ，当且仅当 $x=0$ 时取“=”，
23. 所以，当 $-\frac {1}{2}<x<0$ 时， $\frac {{\ln}(2x+1)}{x}>2$ ，当 $x>0$ 时， $0<\frac {{\ln}\left ({2x+1}\right )}{x}<2$ ，
24. 所以， $g\left ({x}\right )$ 在 $(-\frac {1}{2},0)$ 上单调递减， $g\left ({x}\right )$ 取值集合为 $(2,+\infty )$ ，
25. $g\left ({x}\right )$ 在 $(0,+\infty )$ 上单调递减， $g\left ({x}\right )$ 取值集合为 $(0,2)$ ，
26. 所以，当 $0<a<2$ 或 $a>2$ 时，方程 $a=\frac {{\ln}(2x+1)}{x}$ 有唯一解，
27. 当 $a\leqslant 0$ 或 $a=2$ 时，此方程无解，
28. 所以，当 $a\leqslant 0$ 或 $a=2$ 时，函数 $f(x)$ 有一个零点，
29. 当 $0<a<2$ 或 $a>2$ 时，函数 $f(x)$ 有两个零点.

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
