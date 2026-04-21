# Mathematics - 题目 3942

**ID**: da32aa910c3b42358b5562aab48885f8
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\frac {a}{x}+x{\ln}x\left ({a\in R}\right )$ ．(1)当 $a=1$ 时，求曲线 $y=f\left ({x}\right )$ 在点 $\left ({1,f\left ({1}\right )}\right )$ 处的切线方程；​​​​​​​‌(2)若函数 $f\left ({x}\right )$ 有两个零点 $x_{1}$ ， $x_{2}$ ，证明： $x_{1}x_{2}>a$ ．

## 解答

1. （1）由题意知，当 $a=1$ 时， $f\left ({x}\right )=\frac {1}{x}+x{\ln}x$ ，则 $f\left ({1}\right )=1$ ，
2. 则 $f^{′}\left ({x}\right )=-\frac {1}{x^{2}}+{\ln}x+1$ ，所以 $f^{′}\left ({1}\right )=0$ ，
3. 故过点 $\left ({1,1}\right )$ 的切线方程为 $y=1$ ．
4. （2）由 $f\left ({x}\right )=\frac {1}{x}+x{\ln}x=x\left ({\frac {a}{x^{2}}+{\ln}x}\right )$ ， $\left ({a\in R}\right )$ ，
5. 则令 $g\left ({x}\right )=\frac {a}{x^{2}}+{\ln}x$ ， $\left ({a\in R}\right )$ ，
6. 则 $f\left ({x}\right )$ 有两个零点等同于 $g\left ({x}\right )$ 有两个零点 $x_{1}$ ， $x_{2}$ ，不妨设 $x_{1}<x_{2}$ ，
7. 所以 $g^{′}\left ({x}\right )=-\frac {2a}{x^{3}}+\frac {1}{x}=\frac {x^{2}-2a}{x^{3}}$ ，
8. 当 $a\leqslant 0$ 时， $g^{′}\left ({x}\right )>0$ ， $g\left ({x}\right )$ 单调递增，没有两个零点；
9. 当 $a>0$ 时，若 $g^{′}\left ({x}\right )<0$ ，则 $x\in \left ({0,\sqrt {2a}}\right )$ ；若 $g^{′}\left ({x}\right )>0$ ，则 $x\in \left ({\sqrt {2a},+\infty }\right )$ ，
10. 所以 $g\left ({x}\right )$ 在 $\left ({0,\sqrt {2a}}\right )$ 上单调递减，在 $\left ({\sqrt {2a},+\infty }\right )$ 上单调递增，
11. 又 $g\left ({x}\right )$ 有两个零点，
12. 则 $g\left ({\sqrt {2a}}\right )=\frac {1}{2}+\frac {1}{2}{\ln}2a<0$ ，解得 $0<a<\frac {1}{2{\rm{e}}}$ ，得 $a<\sqrt {2a}<\frac {1}{\sqrt {{\rm{e}}}}<1$ ，
13. 又 $g\left ({1}\right )=a>0$ ， $g\left ({a}\right )=\frac {1}{a}+{\ln}a$ ，
14. 由 $y=\frac {1}{a}+{\ln}a\left ({0<a<1}\right )$ ，则 $y^{′}=\frac {a-1}{a^{2}}<0$ ，
15. 所以 $g\left ({a}\right )>g\left ({\frac {1}{2{\rm{e}}}}\right )>\frac {1}{\frac {1}{2{\rm{e}}}}+{\ln}\frac {1}{2{\rm{e}}}=2{\rm{e}}-{\ln}2{\rm{e}}>0$ ，
16. 故函数 $g\left ({x}\right )$ 在 $\left ({0,1}\right )$ 区间上有两个零点，
17. 由 $g\left ({\frac {1}{\sqrt {{\rm{e}}}}}\right )=a{\rm{e}}-\frac {1}{2}<0$ ，则 $\sqrt {2a}<\frac {1}{\sqrt {{\rm{e}}}}<x_{2}<1$ ，则 $\frac {a}{x_{2}}<\frac {a}{\sqrt {2a}}=\frac {\sqrt {a}}{\sqrt {2}}<\sqrt {2a}$ ，
18. 要证 $x_{1}x_{2}>a$ ，只需证 $x_{1}>\frac {a}{x_{2}}$ ，只需证 $g\left ({\frac {a}{x_{2}}}\right )>g\left ({x_{1}}\right )=0$ ，
19. 又 $g\left ({x_{2}}\right )=\frac {a}{x_{2}^{2}}+{\ln}x_{2}=0$ ，则 $a=-x_{2}^{2}{\ln}x_{2}$ ，
20. 所以 $g\left ({\frac {a}{x_{2}}}\right )=\frac {x_{2}^{2}}{a}+{\ln}\frac {a}{x_{2}}=\frac {1}{-{\ln}x_{2}}+{\ln}\left ({-x_{2}{\ln}x_{2}}\right )=\frac {1}{-{\ln}x_{2}}+{\ln}x_{2}+{\ln}\left ({-{\ln}x_{2}}\right )$ ，
21. 令 $t=-{\ln}x_{2}$ ， $h\left ({t}\right )=\frac {1}{t}-t+{\ln}t\left ({0<t<1}\right )$ ，则 $h^{′}\left ({t}\right )=-\frac {1}{t^{2}}-1+\frac {1}{t}=\frac {-t^{2}+t-1}{t^{2}}<0$ ，
22. 所以 $h\left ({t}\right )=\frac {1}{t}-t+{\ln}t$ 在 $\left ({0,1}\right )$ 上单调递减，
23. 则 $h\left ({t}\right )>h\left ({1}\right )=0$ ，所以 $g\left ({\frac {a}{x_{2}}}\right )>0$ ，
24. 故 $x_{1}>\frac {a}{x_{2}}$ ， $x_{1}x_{2}>a$ ．

## 知识点

**中文**:
  - 利用导数解决函数零点问题
  - 导数几何意义的应用

**English**:
  - Solving Zero Point Problems
  - Applications of Geometric Meaning of Derivatives

---
