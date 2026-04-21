# Mathematics - 题目 514

**ID**: ee48829964794efe8c81467215c8b165
**年级**: Grade 11
**难度**: Hard
**题型**: Calculation

## 题目
定义：若函数 $f\left ({x}\right )$ 图象上恰好存在相异的两点 $P{\rm ，}$  $\mathbf{Q}$ 满足曲线 $y=f\left ({x}\right )$ 在 $P$ 和 $\mathbf{Q}$ 处的切线重合，则称 $P{\rm ，}$  $\mathbf{Q}$ 为曲线 $y=f\left ({x}\right )$ 的“双重切点”，直线 $PQ$ 为曲线 $y=f\left ({x}\right )$ 的“双重切线”．(1)直线 $y=2x$ 是否为曲线 $f\left ({x}\right )=x{^{3}}+\frac {1}{x}$ 的“双重切线”，请说明理由；​​​​​​​‌(2)已知函数 $g\left ({x}\right )=\begin{cases}{\rm{e}}{^{x}}-\frac {2}{{\rm{e}}},x\leqslant 0,\\{\ln}x,x>0,\end{cases}$ 求曲线 $y=g\left ({x}\right )$ 的“双重切线”的方程；(3)已知函数 $h\left ({x}\right )=\sin x{\rm ，}$ 直线 $PQ$ 为曲线 $y=h\left ({x}\right )$ 的“双重切线”，记直线 $PQ$ 的斜率所有可能的取值为 $k{{}_{1}}{\rm ，}$  $k{{}_{2}}{\rm ，}$ … ${\rm ，}k{{}_{n}}{\rm ，}$ 若 $k{{}_{1}}>k{{}_{2}}>k{{}_{i}}$ （ $i=3,4,5,\cdot \cdot \cdot ,n$ ），证明： $\frac {k{{}_{1}}}{k{{}_{2}}}<\frac {15}{8}$ ．

## 解答

1. ${\rm （1）}f\left ({x}\right )=x{^{3}}+\frac {1}{x}$ 的定义域为 $\left ({-\infty ,0}\right )\cup \left ({0,+\infty }\right ){\rm ，}$ 求导得 $f^{′}{\left ({x}\right )}=3x{^{2}}-\frac {1}{x{^{2}}}{\rm ，}$ 直线 $y=2x$ 的斜率为2，
2. 令 $f^{′}{\left ({x}\right )}=3x{^{2}}-\frac {1}{x{^{2}}}=2{\rm ，}$ 解得 $x=\pm 1{\rm ，}$ 不妨设切点 $P\left ({-1,-2}\right ),Q\left ({1,2}\right ){\rm ，}$
3. 则点 $P$ 处的切线方程为 $y+2=2\left ({x+1}\right ){\rm ，}$ 即 $y=2x{\rm ，}$
4. 点 $Q$ 处的切线方程为 $y-2=2\left ({x-1}\right ){\rm ，}$ 即 $y=2x{\rm ，}$
5. 所以直线 $y=2x$ 是曲线 $f\left ({x}\right )=x{^{3}}+\frac {1}{x}$ 的“双重切线”.
6. （2）函数 $g\left ({x}\right )=\begin{cases}{\rm{e}}{^{x}}-\frac {2}{{\rm{e}}},x\leqslant 0\\{\ln}x,x>0\end{cases}{\rm ，}$ 求导得 $g^{′}{\left ({x}\right )}=\begin{cases}{\rm{e}}{^{x}},x\leqslant 0\\\frac {1}{x},x>0\end{cases}{\rm ，}$
7. 显然函数 $y={\rm{e}}{^{x}}$ 在 $\left ({-\infty ,0}\right )$ 上单调递增，函数 $y=\frac {1}{x}$ 在 $\left ({0,+\infty }\right )$ 上单调递减，
8. 设切点 $P\left ({x{{}_{1}},y{{}_{1}}}\right ),Q\left ({x{{}_{2}},y{{}_{2}}}\right ){\rm ，}$ 则存在 $x{{}_{1}}<0<x{{}_{2}}{\rm ，}$ 使得 $f^{′}{\left ({x{{}_{1}}}\right )}=f^{′}{\left ({x{{}_{2}}}\right )}{\rm ，}$
9. 则在点 $P$ 处的切线方程为 $y-({\rm{e}}{^{x{{}_{1}}}}-\frac {2}{{\rm{e}}})={\rm{e}}{^{x{{}_{1}}}}(x-x{{}_{1}}){\rm ，}$ 在点 $Q$ 处的切线方程为 $y-{\ln}x{{}_{2}}=\frac {1}{x{{}_{2}}}\left ({x-x{{}_{2}}}\right ){\rm ，}$
10. 因此 $\begin{cases}{\rm{e}}{^{x{{}_{1}}}}=\frac {1}{x{{}_{2}}}\\{\rm{e}}{^{x{{}_{1}}}}-{\rm{e}}{^{x{{}_{1}}}}x{{}_{1}}-\frac {2}{{\rm{e}}}={\ln}x{{}_{2}}-1\end{cases}{\rm ，}$ 消去 $x{{}_{2}}$ 可得 ${\rm{e}}{^{x{{}_{1}}}}-x{{}_{1}}{\rm{e}}{^{x{{}_{1}}}}+x{{}_{1}}-\frac {2}{{\rm{e}}}+1=0{\rm ，}$
11. 令 $k\left ({x}\right )={\rm{e}}{^{x}}-x{\rm{e}}{^{x}}+x-\frac {2}{{\rm{e}}}+1\left ({x<0}\right ){\rm ，}$ 求导得 $k^{′}(x)={\rm{e}}{^{x}}-(1+x){\rm{e}}{^{x}}+1=-x{\rm{e}}{^{x}}+1>0{\rm ，}$
12. 则函数 $k\left ({x}\right )$ 在 $\left ({-\infty ,0}\right )$ 上单调递增，又 $k\left ({-1}\right )=0{\rm ，}$ 函数 $k\left ({x}\right )$ 的零点为 $-1{\rm ，}$ 因此 $x{{}_{1}}=-1,x{{}_{2}}={\rm{e}}{\rm ，}$
13. 所以曲线 $y=g\left ({x}\right )$ 的“双重切线”的方程为 $y=\frac {x}{{\rm{e}}}$ .
14. （3）设 $k{{}_{1}}$ 对应的切点为 $(t{{}_{1}},\sin t{{}_{1}}),(s{{}_{1}},\sin s{{}_{1}}),t{{}_{1}}<s{{}_{1}}{\rm ，}$  $k{{}_{2}}$ 对应的切点为 $(t{{}_{2}},\sin t{{}_{2}}),(s{{}_{2}},\sin s{{}_{2}}),t{{}_{2}}<s{{}_{2}}{\rm ，}$
15. 由 $\left ({\sin x}\right ){^{\prime }}={\cos}x{\rm ，}$ 得 $k{{}_{1}}={\cos}t{{}_{1}}={\cos}s{{}_{1}}{\rm ，}$  $k{{}_{2}}={\cos}t{{}_{2}}={\cos}s{{}_{2}}{\rm ，}$
16. 由诱导公式及余弦函数的周期性知，只需考虑 $t{{}_{1}}+s{{}_{1}}=2{\rm{π}}{\rm ，}$  $t{{}_{2}}+s{{}_{2}}=4{\rm{π}}{\rm ，}$ 其中 $t{{}_{1}},t{{}_{2}}\in (-\frac {{\rm{π}}}{2},0){\rm ，}$
17. 由 $k{{}_{1}}>k{{}_{2}}$ 及余弦函数在 $\left ({-\frac {{\rm{π}}}{2},0}\right )$ 上递增知 ${\rm ，}-\frac {{\rm{π}}}{2}<t{{}_{2}}<t{{}_{1}}<0{\rm ，}$
18. 则 $k{{}_{1}}=\frac {\sin s{{}_{1}}-\sin t{{}_{1}}}{s{{}_{1}}-t{{}_{1}}}=\frac {\sin \left ({2{\rm{π}}-t{{}_{1}}}\right )-\sin t{{}_{1}}}{\left ({2{\rm{π}}-t{{}_{1}}}\right )-t{{}_{1}}}=-\frac {2\sin t{{}_{1}}}{2{\rm{π}}-2t{{}_{1}}}=-\frac {\sin t{{}_{1}}}{{\rm{π}}-t{{}_{1}}}{\rm ，}$
19. $k{{}_{2}}=\frac {\sin s{{}_{2}}-\sin t{{}_{2}}}{s{{}_{2}}-t{{}_{2}}}=\frac {\sin \left ({{{4}}{\rm{π}}-t{{}_{2}}}\right )-\sin t{{}_{2}}}{\left ({{{4}}{\rm{π}}-t{{}_{2}}}\right )-t{{}_{2}}}=-\frac {2\sin t{{}_{2}}}{{{4}}{\rm{π}}-2t{{}_{2}}}=-\frac {\sin t{{}_{2}}}{{{2}}{\rm{π}}-t{{}_{2}}}{\rm ，}$
20. 因此 $\frac {k{{}_{1}}}{k{{}_{2}}}=\frac {\sin t{{}_{1}}}{\sin t{{}_{2}}}\cdot \frac {2{\rm{π}}-t{{}_{2}}}{{\rm{π}}-t{{}_{1}}}{\rm ，}$ 又 $k{{}_{1}}={\cos}t{{}_{1}}=-\frac {\sin t{{}_{1}}}{{\rm{π}}-t{{}_{1}}}{\rm ，}$  $k{{}_{2}}={\cos}t{{}_{2}}=-\frac {\sin t{{}_{2}}}{{{2}}{\rm{π}}-t{{}_{2}}}{\rm ，}$
21. 则 $\sin t{{}_{1}}=(t{{}_{1}}-{\rm{π}}){\cos}t{{}_{1}}\Leftrightarrow {\tan}t{{}_{1}}-t{{}_{1}}+{\rm{π}}=0{\rm ，}$ 同理 ${\tan}t{{}_{2}}-t{{}_{2}}+2{\rm{π}}=0{\rm ，}$
22. 令 $F\left ({x}\right )={\tan}x-x+{\rm{π}}(-\frac {{\rm{π}}}{2}<x<0){\rm ，}$ 求导得 $F^{′}{\left ({x}\right )}=\frac {1}{{\cos}{^{2}}x}-1=\frac {\sin {^{2}}x}{{\cos}{^{2}}x}={\tan}{^{2}}x>0{\rm ，}$
23. 则 $F\left ({x}\right )$ 在 $(-\frac {{\rm{π}}}{2},0)$ 上单调递增，显然 $F(-\frac {{\rm{π}}}{3})>0{\rm ，}$ 且 $F(x)<{\tan}x+\frac {3{\rm{π}}}{2}{\rm ，}$
24. 函数 $y={\tan}x+\frac {3{\rm{π}}}{2}$ 在 $(-\frac {{\rm{π}}}{2},0)$ 上的值域为 $(-\infty ,\frac {3{\rm{π}}}{2}){\rm ，}$ 即函数 $F(x)$ 在 $(-\frac {{\rm{π}}}{2},0)$ 上存在零点，则有 $-\frac {{\rm{π}}}{2}<t{{}_{1}}<-\frac {{\rm{π}}}{3}{\rm ，}$
25. 由 ${\tan}t{{}_{2}}-t{{}_{2}}+2{\rm{π}}=0{\rm ，}$ 同理可得 $-\frac {{\rm{π}}}{2}<t{{}_{2}}<-\frac {{\rm{π}}}{3}{\rm ，}$ 而 $t{{}_{2}}<t{{}_{1}}{\rm ，}$ 因此 $-\frac {{\rm{π}}}{2}<t{{}_{2}}<t{{}_{1}}<-\frac {{\rm{π}}}{3}{\rm ，}$
26. 于是 $\sin t{{}_{2}}<\sin t{{}_{1}}<0{\rm ，}$ 即有 $0<\frac {\sin t{{}_{1}}}{\sin t{{}_{2}}}<1{\rm ，}$
27. 所以 $\frac {k{{}_{1}}}{k{{}_{2}}}=\frac {\sin t{{}_{1}}}{\sin t{{}_{2}}}\cdot \frac {2{\rm{π}}-t{{}_{2}}}{{\rm{π}}-t{{}_{1}}}<\frac {2{\rm{π}}-t{{}_{2}}}{{\rm{π}}-t{{}_{1}}}<\frac {2{\rm{π}}+\frac {{\rm{π}}}{2}}{{\rm{π}}+\frac {{\rm{π}}}{3}}=\frac {15}{8}{\rm ，}$ 即 $\frac {k{{}_{1}}}{k{{}_{2}}}<\frac {15}{8}$ .

## 知识点

**中文**:
  - 利用导数解决函数零点问题
  - 导数几何意义的应用
  - 利用导数解决新定义问题

**English**:
  - Solving Zero Point Problems
  - Applications of Geometric Meaning of Derivatives
  - Solving New Definition Problems

---
