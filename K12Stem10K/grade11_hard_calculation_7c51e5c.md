# Mathematics - 题目 3178

**ID**: 7c51e5ca632941fa81d07b89da0b5eeb
**年级**: Grade 11
**难度**: Hard
**题型**: Calculation

## 题目
用数学的眼光看世界就能发现很多数学之“美”，现代建筑讲究线条感，曲线之美让人称奇，衡量曲线弯曲程度的重要指标是曲率，曲线的曲率定义如下：若 $f^{′}{\left ({x}\right )}$ 是 $f\left ({x}\right )$ 的导函数，  $f^{′′}{\left ({x}\right )}$ 是 $f^{′}{\left ({x}\right )}$ 的导函数，则曲线 $y=f\left ({x}\right )$ 在点 $\left ({x,f\left ({x}\right )}\right )$ 处的曲率 $K=\frac {\left |{f^{′′}{\left ({x}\right )}}\right |}{\left ({1+\left [f^{′}{\left ({x}\right )}\right ]{^{2}}}\right ){^{\frac {3}{2}}}}$  .​​​​​​​‌(1)求曲线 $f\left ({x}\right )={\ln}x$ 在 $\left ({1,0}\right )$ 的曲率；(2)已知函数 $g\left ({x}\right )={\cos}x+1$  $\left ({x\in \mathbf{R}}\right )$ ，求 $g\left ({x}\right )$ 曲率的平方的最大值；(3)函数 $h\left ({x}\right )=\left ({x-2}\right ){\rm{e}}{^{x}}+\left ({\frac {3+m}{2}-\frac {x}{3}-{\ln}x}\right )x{^{2}}$ ，若 $h\left ({x}\right )$ 在两个不同的点处曲率为0，求实数m的取值范围.

## 解答

1. （1）因为 $f\left ({x}\right )={\ln}x$ ，则 $f^{′}{\left ({x}\right )}=\frac {1}{x}$ ， $f^{′′}{\left ({x}\right )}=-\frac {1}{x{^{2}}}$ ，
2. 所以 $K=\frac {\left |{f^{′′}{\left ({1}\right )}}\right |}{\left ({1+\left [f^{′}{\left ({1}\right )}\right ]{^{2}}}\right ){^{\frac {3}{2}}}}=\frac {1}{\left ({1+1{^{2}}}\right ){^{\frac {3}{2}}}}=\frac {\sqrt {2}}{4}$ .
3. （2）因为 $g\left ({x}\right )={\cos}x+1$ （ $x\mathrm{∈}\mathbf{R}$ ），则 $g^{′}{\left ({x}\right )}=-\sin x$ ， $g^{′′}{\left ({x}\right )}=-{\cos}x$ ，
4. 所以 $K=\frac {\left |{g^{′′}{\left ({x}\right )}}\right |}{\left ({1+\left [g^{′}{\left ({x}\right )}\right ]{^{2}}}\right ){^{\frac {3}{2}}}}=\frac {\left |{-{\cos}x}\right |}{\left ({1+\sin {^{2}}x}\right ){^{\frac {3}{2}}}}$ ，
5. 则 $K{^{2}}=\frac {{\cos}{^{2}}x}{{\left({1+\sin {^{2}}x}\right)^{3}}}=\frac {{\cos}{^{2}}x}{{\left({2-{\cos}{^{2}}x}\right)^{3}}}$ ，
6. 令 $t=2-{\cos}{^{2}}x$ ，则 $t\in \left [1,2\right ]$ ， $K{^{2}}=\frac {2-t}{t{^{3}}}$ ，
7. 设 $p\left ({t}\right )=\frac {2-t}{t{^{3}}}$ ，则 $p^{′}{\left ({t}\right )}=\frac {-t{^{3}}-3t{^{2}}\left ({2-t}\right )}{t{^{6}}}=\frac {2t-6}{t{^{4}}}$ ，
8. 显然当 $t\in \left [1,2\right ]$ 时， $p^{′}{\left ({t}\right )}\mathrm{<}0$ ， $p\left ({t}\right )$ 单调递减，
9. 所以 $p\left ({t}\right ){{}_{{\rm{m}}{\rm{a}}{\rm{x}}{\rm{\;}}}}=p\left ({1}\right )=1$ ，所以 $K{^{2}}$ 最大值为1.
10. （3）∵ $h\left ({x}\right )=\left ({x-2}\right ){\rm{e}}{^{x}}+\left ({\frac {3+m}{2}-\frac {x}{3}-{\ln}x}\right )x{^{2}}$ ， $x>0$ ，
11. ∴ $h^{′}{\left ({x}\right )}=\left ({x-1}\right ){\rm{e}}{^{x}}+\left ({3+m}\right )x-x{^{2}}-\left ({x+2x{\ln}x}\right )$ ，
12. ∴ $h^{′′}{\left ({x}\right )}=x{\rm{e}}{^{x}}-2\left ({{\ln}x+x}\right )+m={\rm{e}}{^{{\ln}x+x}}-2\left ({{\ln}x+x}\right )+m$ ， $x>0$ ，
13. 因为 $h\left ({x}\right )$ 在两个不同的点处曲率为0，
14. 所以 $h^{′′}{\left ({x}\right )}=0$ 有两个大于0的不同实数解，
15. 即 $h^{′′}{\left ({x}\right )}={\rm{e}}{^{{\ln}x+x}}-2\left ({{\ln}x+x}\right )+m$ 有两个不同的零点,
16. 令 $t\left ({x}\right )={\ln}x+x$  $(x>0)$ ，
17. ∵ $t^{′}{\left ({x}\right )}=\frac {1}{x}+1>0$ ，
18. ∴ $t\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上单调递增，且值域为R，
19. 所以 $m=-{\rm{e}}{^{{\ln}x+x}}+2\left ({{\ln}x+x}\right )$ 有两个大于0的实数解，
20. 等价于 $m=2t-{\rm{e}}{^{t}}$ ， $t\in \mathbf{R}$ 有两个不同的实数解,
21. 令 $G\left ({t}\right )=2t-{\rm{e}}{^{t}}$ ， $t\in \mathbf{R}$ ，则 $G^{′}{\left ({t}\right )}=2-{\rm{e}}{^{t}}$ ，
22. 令 $G^{′}{\left ({t}\right )}=0$ 得 $t={\ln}2$ ，
23. $t\in \left ({-\infty ,{\ln}2}\right )$ 时， $G^{′}{\left ({t}\right )}>0$ ，即 $G\left ({t}\right )$ 单调递增；
24. $t\in \left ({{\ln}2,+\infty }\right )$ 时， $G^{′}{\left ({t}\right )}<0$ ，即 $G\left ({t}\right )$ 单调递减；
25. 所以 $G\left ({t}\right ){{}_{{\rm \max }}}=G\left ({{\ln}2}\right )=2{\ln}2-2$ ，
26. 又因为当 $t\to -\infty $ 时， $G\left ({t}\right )\to -\infty $ ；
27. 当 $t\to +\infty $ 时， $G\left ({t}\right )\to -\infty $ ；
28. $G\left ({t}\right )$ 的图象如下所示：
29. 
30. 又因为 $m=G(t)$ 有两个实数解，
31. 所以 $m\in \left ({-\infty ,2{\ln}2-2}\right )$ .
32. 所以m的取值范围为 $\left ({-\infty ,2{\ln}2-2}\right )$ .

## 知识点

**中文**:
  - 利用导数解决新定义问题

**English**:
  - Solving New Definition Problems

---
