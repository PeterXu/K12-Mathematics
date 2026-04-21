# Mathematics - 题目 671

**ID**: dc2527656fa5402eba7a607438023d10
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
若函数 $f\left ({x}\right ),g\left ({x}\right )$ 的图象有公共点，且在公共点处的切线相同，则称该公共点为函数 $f\left ({x}\right )$ 与 $g\left ({x}\right )$ 的一个“公切点”.​​​​​​​‌(1)若函数 $f\left ({x}\right )=mx{^{2}}$ 与 $g\left ({x}\right )={\rm{l}}{\rm{n}}x$ 存在“公切点”，求实数 $m$ 的值；(2)设函数 $f\left ({x}\right )=x-1+k{\rm{l}}{\rm{n}}x\left ({k\ne 0}\right )$ ，直线 $l$ 是曲线 $y=f\left ({x}\right )$ 在点 $\left ({t,f\left ({t}\right )}\right )\left ({t>1}\right )$ 处的切线.求证:直线 $l$ 不经过点(1,0);(3)已知函数 $f\left ({x}\right )=x{^{2}}+a,g\left ({x}\right )=\frac {bx}{{\rm{e}}{^{x}}}$ ，对任意 $a>0$ ，判断是否存在 $b>0$ ，使函数 $f\left ({x}\right )$ 与 $g\left ({x}\right )$ 在区间 $\left ({0,+\infty }\right )$ 内存在“公切点”?并说明理由.

## 解答

1. （1）设 $\left ({x{{}_{0}}{\rm{,}}y{{}_{0}}}\right )$ 是 $f\left ({x}\right ),g\left ({x}\right )$ 的“公切点”，
2. 则由 $f\left ({x{{}_{0}}}\right )=g\left ({x{{}_{0}}}\right )$ 且 $f^{′}{\left ({x{{}_{0}}}\right )}=g^{′}{\left ({x{{}_{0}}}\right )}$ ，
3. 由于 $f^{′}{\left ({x}\right )}=2mx{\rm{,}}g^{′}{\left ({x}\right )}=\frac {1}{x}$ ，所以 $\begin{cases}mx{{}_{0}^{2}}={\ln}x{{}_{0}}\\2mx{{}_{0}}=\frac {1}{x{{}_{0}}}\end{cases}$ ，解得 ${\ln}x{{}_{0}}=\frac {1}{2}{\rm{,}}$ 所以 $x{{}_{0}}={\rm{e}}{^{\frac {1}{2}}}$ ，
4. 所以 $m=\frac {1}{2x{{}_{0}^{2}}}=\frac {1}{{{2}}{\rm{e}}}$ ，
5. 当 $m=\frac {{{1}}}{{{2}}{\rm{e}}}$ 时， $x{{}_{0}}={\rm{e}}{^{\frac {1}{2}}}$ 满足题意，
6. 故 $m=\frac {{{1}}}{{{2}}{\rm{e}}}$
7. （2）由于 $f(x)=x-1+k{\rm{l}}{\rm{n}}x(k\ne 0)$ ，所以 $f^{′}{\left ({x}\right )}=1+\frac {k}{x}$ ，
8. 故直线 $l$ 的斜率为 $1+\frac {k}{t}$ ，则直线 $l$ 的方程为 $y-f\left ({t}\right )=\left ({1+\frac {k}{t}}\right )\left ({x-t}\right ),\left ({t>1}\right )$ ，
9. 将点 $\left ({1,0}\right )$ 代入可得 $-f\left ({t}\right )=\left ({1+\frac {k}{t}}\right )\left ({1-t}\right )$ ，故 $f\left ({t}\right )=\left ({1+\frac {k}{t}}\right )\left ({t-1}\right ),\left ({t>1}\right )$ ，
10. 即 $t-1+k{\rm{l}}{\rm{n}}t=\left ({1+\frac {k}{t}}\right )\left ({t-1}\right ),t>1$ ，故 $k{\ln}t=\frac {k}{t}\left ({t-1}\right ){\rm{,}}t>1$ ，
11. 因为 $k\ne 0{\rm{,}}则{\ln}t=\frac {t-1}{t}\left ({t>1}\right )$ ，即 ${\ln}t-1+\frac {1}{t}=0\left ({t>1}\right )$ ，
12. 令 $F\left ({t}\right )={\ln}t-1+\frac {1}{t}\left ({t>1}\right )$ ，
13. 假设直线 $l$ 经过点 $\left ({1,0}\right )$ ，则 $F(t)$ 在 $(1,+\infty )$ 上存在零点，
14. 由 $F^{′}{\left ({t}\right )}=\frac {1}{t}-\frac {1}{t{^{2}}}=\frac {t-1}{t{^{2}}}>0\left ({t>1}\right )$ ，所以 $F(t)$ 在 $(1,+\infty )$ 上单调递增，
15. 所以 $F(t)>F(1)=0$ ，故 $F(t)$ 在 $(1,+\infty )$ 上无零点，这与假设矛盾，故直线 $l$ 不经过点 $\left ({1,0}\right )$ ，
16. （3）因为 $f\left ({x}\right )=x{^{2}}+a{\rm{,}}g\left ({x}\right )=\frac {bx}{{\rm{e}}{^{x}}}$ ，所以 $f^{′}{\left ({x}\right )}=2x{\rm{,}}g^{′}{\left ({x}\right )}=\frac {b\left ({1-x}\right )}{{\rm{e}}{^{x}}}$ ，
17. 由 $f(x)=g(x)$ 且 $f^{′}(x)=g^{′}(x)$ ，得 $\begin{cases}x{^{2}}+a=\frac {bx}{{\rm{e}}{^{x}}}\\2x=\frac {b\left ({1-x}\right )}{{\rm{e}}{^{x}}}\end{cases}$ ，
18. 两式相除可得 $x{^{3}}+x{^{2}}+ax-a=0$ ，
19. 设 $h\left ({x}\right )=x{^{3}}+x{^{2}}+ax-a\left ({a>0}\right )$ ，
20. 由于 $h(0)=-a<0{\rm{,}}h(1)=2>0$ ，且 $h(x)$ 的图象连续不断，所以存在 $x{{}_{0}}\in \left ({0{\rm{,}}1}\right ){\rm{,}}$ 使得 $h\left ({x{{}_{0}}}\right )=0$ ，
21. 则 $a=\frac {x{{}_{0}^{3}}+x{{}_{0}^{2}}}{1-x{{}_{0}}}$ ，将其代入 $x{^{2}}+a=\frac {bx}{{\rm{e}}{^{x}}}$ 可得 $b=\frac {2x{{}_{0}}{\rm{e}}{^{x}}}{1-x{{}_{0}}}>0$ ，
22. 此时 $x{{}_{0}}{\rm{,}}a{\rm{,}}b$ 满足方程组，即 $\left ({x{{}_{0}}{\rm{,}}f\left ({x{{}_{0}}}\right )}\right )$ 是函数 $f\left ({x}\right )$ 与 $g\left ({x}\right )$ 在区间 $\left ({0,1}\right )$ 内的一个“公切点”，
23. 因此，对任意 $a>0$ ，存在 $b>0$ ，使得 $f\left ({x}\right )$ 与 $g\left ({x}\right )$ 在区间 $\left ({0,+\infty }\right )$ 内存在“公切线”.

## 知识点

**中文**:
  - 利用导数解决新定义问题
  - 导数几何意义的应用

**English**:
  - Solving New Definition Problems
  - Applications of Geometric Meaning of Derivatives

---
