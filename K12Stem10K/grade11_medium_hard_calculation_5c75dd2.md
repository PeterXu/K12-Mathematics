# Mathematics - 题目 3731

**ID**: 5c75dd22bafa44d09f56714cfae39a17
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知动点 $M\left ({x,y}\right )$ 与定点 $R\left ({2\sqrt {2},0}\right )$ 的距离和 $M$ 到定直线 $l:x=4\sqrt {2}$ 的距离之比是常数 $\frac {\sqrt {2}}{2}$ .​​​​​​​‌（1）求点 $M$ 的轨迹 $C$ 的方程；（2）已知定点 $E\left ({0,\sqrt {2}}\right )$ ，直线 $l{{}_{1}}$ 的方程为 $x+y-4\sqrt {2}=0$ ，直线 $l{{}_{1}}$ 上有一动点 $H$ ，轨迹 $C$ 上有一动点 $G$ ，求 $\left |{EH}\right |+\left |{GH}\right |-\left |{GR}\right |$ 的最小值；（3）若 $A$ ， $B$ 为轨迹 $C$ 上不同的两点，线段 $AB$ 的中点为 $Q$ ，当 $\vartriangle AOB$ 面积取最大值时，是否存在两定点S，T，使 $\left |{QS}\right |+\left |{QT}\right |$ 为定值？若存在，求出这个定值，若不存在，请说明理由.

## 解答

1. （1）由题意得 $\sqrt {{\left({x-2\sqrt {2}}\right)^{2}}+y{^{2}}}=\frac {\sqrt {2}}{2}\left |{x-4\sqrt {2}}\right |$ ，
2. 两边平方得 $2{\left({x-2\sqrt {2}}\right)^{2}}+2y{^{2}}={\left({x-4\sqrt {2}}\right)^{2}}$ ，
3. 整理得，点 $M$ 的轨迹 $C$ 的方程为 $\frac {x{^{2}}}{16}+\frac {y{^{2}}}{8}=1$ ；
4. （2） $\frac {x{^{2}}}{16}+\frac {y{^{2}}}{8}=1$ 中， $a{^{2}}=16,b{^{2}}=8$ ，则 $c=\sqrt {16-8}=2\sqrt {2}$ ，
5. $R\left ({2\sqrt {2},0}\right )$ 为 $\frac {x{^{2}}}{16}+\frac {y{^{2}}}{8}=1$ 的右焦点，设 $R^{′}{\left ({-2\sqrt {2},0}\right )}$ 为 $\frac {x{^{2}}}{16}+\frac {y{^{2}}}{8}=1$ 的左焦点，
6. 连接 $GR^{′}$ ，则 $\left |{GR^{′}}\right |+\left |{GR}\right |=2a=8$ ， $\left |{GR}\right |=8-\left |{GR^{′}}\right |$ ，
7. 则 $\left |{EH}\right |+\left |{GH}\right |-\left |{GR}\right |=\left |{EH}\right |+\left |{GH}\right |+\left |{GR^{′}}\right |-8$ ，
8. 其中当 $R^{′},G,H$ 三点共线时， $\left |{GH}\right |+\left |{GR^{′}}\right |$ 取得最小值 $\left |{HR^{′}}\right |$ ，
9. 问题转化为在直线 $l{{}_{1}}$ 上找到一点 $H$ ，使得 $\left |{HR^{′}}\right |+\left |{EH}\right |-8$ 最小，
10. 设点 $E\left ({0,\sqrt {2}}\right )$ 关于直线 $l{{}_{1}}$ 的对称点为 $E^{′}{\left ({n,t}\right )}$ ，
11. 则 $\begin{cases}\frac {t-\sqrt {2}}{n}=1\\\frac {n}{2}+\frac {t+\sqrt {2}}{2}-4\sqrt {2}=0\end{cases}$ ，解得 $\begin{cases}n=3\sqrt {2}\\t=4\sqrt {2}\end{cases}$ ，
12. 故 $E^{′}{\left ({3\sqrt {2},4\sqrt {2}}\right )}$ ，连接 $E^{′}R^{′}$ ，与直线 $l{{}_{1}}$ 的交点即为所求点 $H$ ，
13. 使得 $\left |{HR^{′}}\right |+\left |{EH}\right |-8$ 最小，最小值为 $\left |{E^{′}R^{′}}\right |-8=\sqrt {{\left({3\sqrt {2}+2\sqrt {2}}\right)^{2}}+{\left({4\sqrt {2}}\right)^{2}}}-8=\sqrt {82}-8$ ，
14. 故 $\left |{EH}\right |+\left |{GH}\right |-\left |{GR}\right |$ 的最小值为 $\sqrt {82}-8$ .
15. 
16. （3）存在两定点S，T，使 $\left |{QS}\right |+\left |{QT}\right |$ 为定值 $4\sqrt {2}$ ,理由如下：
17. 当直线 $AB$ 的斜率存在时，设直线 $AB$ 方程为 $y=kx+m$ ， $m\ne 0$ ，
18. 联立直线 $AB$ 与椭圆方程 $\frac {x{^{2}}}{16}+\frac {y{^{2}}}{8}=1$ 得 $\left ({1+2k{^{2}}}\right )x{^{2}}+4kmx+2m{^{2}}-16=0$ ，
19. $Δ=16k{^{2}}m{^{2}}-4\left ({1+2k{^{2}}}\right )\left ({2m{^{2}}-16}\right )>0$ ，即 $16k{^{2}}+8>m{^{2}}$ ，
20. 设 $A\left ({x{{}_{1}},y{{}_{1}}}\right ),B\left ({x{{}_{2}},y{{}_{2}}}\right )$ ，则 $x{{}_{1}}+x{{}_{2}}=-\frac {4km}{1+2k{^{2}}},x{{}_{1}}x{{}_{2}}=\frac {2m{^{2}}-16}{1+2k{^{2}}}$ ，
21. 故 $S{{}_{\vartriangle AOB}}=\frac {1}{2}\left |{m}\right |\cdot \left |{x{{}_{2}}-x{{}_{1}}}\right |=\frac {1}{2}\left |{m}\right |\cdot \sqrt {{\left({x{{}_{1}}+x{{}_{2}}}\right)^{2}}-4x{{}_{1}}x{{}_{2}}}=\frac {1}{2}\left |{m}\right |\sqrt {{\left({-\frac {4km}{1+2k{^{2}}}}\right)^{2}}-4\cdot \frac {2m{^{2}}-16}{1+2k{^{2}}}}$
22. $=\left |{m}\right |\frac {\sqrt {16\left ({1+2k{^{2}}}\right )-2m{^{2}}}}{1+2k{^{2}}}=\sqrt {2}\sqrt {-{\left({\frac {m{^{2}}}{1+2k{^{2}}}}\right)^{2}}+8\frac {m{^{2}}}{1+2k{^{2}}}}=\sqrt {2}\sqrt {-{\left({\frac {m{^{2}}}{1+2k{^{2}}}-4}\right)^{2}}+16}$ ，
23. 故当 $\frac {m{^{2}}}{1+2k{^{2}}}=4$ 时， $S{{}_{\vartriangle AOB}}$ 取得最大值，最大值为 $4\sqrt {2}$ ，
24. 此时 $m{^{2}}=4+8k{^{2}}$ ，满足 $16k{^{2}}+8>m{^{2}}$ ，
25. 因为 $x{{}_{1}}+x{{}_{2}}=-\frac {4km}{1+2k{^{2}}}$ ，所以 $y{{}_{1}}+y{{}_{2}}=k\left ({x{{}_{1}}+x{{}_{2}}}\right )+2m=\frac {2m}{1+2k{^{2}}}$ ，
26. 故 $\frac {x{{}_{1}}+x{{}_{2}}}{2}=-\frac {2km}{1+2k{^{2}}}$ ， $\frac {y{{}_{1}}+y{{}_{2}}}{2}=\frac {m}{1+2k{^{2}}}$
27. 故 $Q\left ({-\frac {2km}{1+2k{^{2}}},\frac {m}{1+2k{^{2}}}}\right )$ ，
28. 令 $\begin{cases}x=-\frac {2km}{1+2k{^{2}}}\\y=\frac {m}{1+2k{^{2}}}\end{cases}$ ，两式相除得 $\frac {x}{y}=-2k$ ，故 $\frac {x}{-2y}=k$ ，
29. 将其代入 $y=\frac {m}{1+2k{^{2}}}$ 得 $m=y+\frac {x{^{2}}}{2y}$ ，结合 $m{^{2}}=4+8k{^{2}}$ 得 ${\left({y+\frac {x{^{2}}}{2y}}\right)^{2}}=4+8{\left({\frac {x}{-2y}}\right)^{2}}$ ，
30. 化简得 ${\left({x{^{2}}+2y{^{2}}}\right)^{2}}=8\left ({x{^{2}}+2y{^{2}}}\right )$ ，
31. 因为 $m\ne 0$ ，所以 $x{^{2}}+2y{^{2}}>0$ ，故 $x{^{2}}+2y{^{2}}=8$ ，即 $\frac {x{^{2}}}{8}+\frac {y{^{2}}}{4}=1$ ，
32. 当直线 $AB$ 的斜率不存在时，设 $A\left ({4{\cos}θ,2\sqrt {2}\sin θ}\right )$ ，则 $B\left ({4{\cos}θ,-2\sqrt {2}\sin θ}\right )$ ，
33. 则 $S{{}_{\vartriangle AOB}}=\frac {1}{2}\times 4\sqrt {2}\sin θ\cdot 4{\cos}θ=8\sqrt {2}\sin θ{\cos}θ=4\sqrt {2}\sin 2θ$ ，
34. 不妨设点 $A$ 在第一象限，则当 $θ=\frac {{\rm{\mathrm{π}}}}{4}$ 时， $S{{}_{\vartriangle AOB}}$ 取得最大值 $4\sqrt {2}$ ，
35. 此时 $AB$ 的中点坐标为 $\left ({2\sqrt {2},0}\right )$ ，满足 $\frac {x{^{2}}}{8}+\frac {y{^{2}}}{4}=1$ ，
36. 故当 $S{{}_{\vartriangle AOB}}$ 取得最大值时，点 $Q$ 的轨迹方程为椭圆 $\frac {x{^{2}}}{8}+\frac {y{^{2}}}{4}=1$ ，
37. 两焦点坐标为 $\left ({2,0}\right ),\left ({-2,0}\right )$ ，
38. 由椭圆定义可知，存在两定点S，T，分别为 $\left ({-2,0}\right ),\left ({2,0}\right )$ 或 $\left ({2,0}\right ),\left ({-2,0}\right )$ ，
39. 使 $\left |{QS}\right |+\left |{QT}\right |=2\times 2\sqrt {2}=4\sqrt {2}$ 为定值.
40. 

## 知识点

**中文**:
  - 存在性或者探究性问题
  - 椭圆的定义
  - 曲线与方程

**English**:
  - Existence and Inquiry Problems
  - Definition of Ellipse
  - Curves and Equations

---
