# Mathematics - 题目 2163

**ID**: 95f094c6656b44cf95b8e805f53010bb
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设椭圆方程为 $\frac {x{^{2}}}{4}+\frac {y{^{2}}}{b{^{2}}}=1\left ({b>0}\right )，F{{}_{1}}\left ({-c，0}\right )，F{{}_{2}}\left ({c，0}\right )$ 为其左右焦点，过椭圆上点 $Q\left ({c,y{{}_{Q}}}\right )$ 的椭圆切线方程为 $\sqrt {2}x+2y=4$（1）求出椭圆方程；​​​​​​​‌（2）设点 $C\left ({-2,t}\right )\left ({t\ne 0}\right ),M\left ({-2,\frac {t}{2}}\right )$ ，点 $B$ 为椭圆右顶点，过 $M$ 作椭圆的不与轴垂直的切线，切点为点 $P$ ，求证： $C､P､B$ 三点共线．

## 解答

1. （1）把 $Q\left ({c,y{{}_{Q}}}\right )$ 代入 $\sqrt {2}x+2y=4$ ，解得切点坐标为 $Q\left ({c,2-\frac {\sqrt {2}}{2}c}\right )$ ，
2. 代入椭圆方程得 $\begin{cases}\frac {c{^{2}}}{4}+\frac {(2-\frac {\sqrt {2}}{2}c){^{2}}}{b{^{2}}}=1\\4=c{^{2}}+b{^{2}}\end{cases}$ ，解得 $\begin{cases}b=\sqrt {2}\\c=\sqrt {2}\end{cases}$ ，
3. 则椭圆标准方程为 $\frac {x{^{2}}}{4}+\frac {y{^{2}}}{2}=1$ .
4. （2）
5. 
6. 方法一：如图所示，  $M\left ({-2,\frac {t}{2}}\right )$ ，设直线 $MP$ 为 $y-\frac {t}{2}=k(x+2)$ ，
7. 联立方程得 $\begin{cases}y=kx+2k+\frac {t}{2}\\\frac {x{^{2}}}{4}+\frac {y{^{2}}}{2}=1\end{cases},$ 消去 $y$ 得 $(1+2k{^{2}})x{^{2}}+(8k{^{2}}+2kt)x+(8k{^{2}}+4kt+\frac {t{^{2}}}{2}-4)=0$ .
8. 相切时 $\Delta =0$ ，可得 $(8k{^{2}}+2kt){^{2}}-4(1+2k{^{2}})(8k{^{2}}+4kt+\frac {t{^{2}}}{2}-4)=0$ .
9. 化简得 $16-16kt-2t{^{2}}=0$ ，解得 $k=\frac {t{^{2}}-8}{8t}$ ，故 $x{{}_{P}}=-\frac {4k{^{2}}+kt}{1+2k{^{2}}}=\frac {2t{^{2}}-16}{t{^{2}}+8}$ ,
10. 故得切点坐标 $P\left ({\frac {2t{^{2}}-16}{t{^{2}}+8},\frac {8t}{t{^{2}}+8}}\right )$ ，则 $K{{}_{BC}}=\frac {t}{-2-2}=-\frac {t}{4}$ ， $K{{}_{PC}}=\frac {\frac {8t}{t{^{2}}+8}-t}{\frac {2t{^{2}}-16}{t{^{2}}+8}+2}=-\frac {t}{4}$ ，可知 $K{{}_{BC}}=K{{}_{PC}}$ ，则 $C､P､B$ 三点共线．
11. 方法二：已知 $B(2,0),C(-2,t)$ ，可知直线 $BC$ 解析式为 $y=-\frac {t}{4}(x-2)$ ，
12. 联立直线方程和椭圆方程得 $\begin{cases}y=-\frac {t}{4}(x-2)\\\frac {x{^{2}}}{4}+\frac {y{^{2}}}{2}=1\end{cases}$ ，解得 $\begin{cases}x=\frac {2t{^{2}}-16}{t{^{2}}+8}\\y=\frac {8t}{t{^{2}}+8}\end{cases}$ ，
13. 则交点 $P$ 坐标为 $\left ({\frac {2t{^{2}}-16}{t{^{2}}+8},\frac {8t}{t{^{2}}+8}}\right )$ ，
14. 因为 $M(-2,\frac {t}{2})$ ，则直线 $MP$ 解析式为 $\frac {y-\frac {t}{2}}{\frac {8t}{t{^{2}}+8}-\frac {t}{2}}=\frac {x+2}{\frac {2t{^{2}}-16}{t{^{2}}+8}+2}$ ，
15. 化简得 $y=\frac {8-t{^{2}}}{8t}x+\frac {8+t{^{2}}}{4t}$ ，
16. 联立方程组得 $\begin{cases}y=\frac {8-t{^{2}}}{8t}x+\frac {8+t{^{2}}}{4t}\\\frac {x{^{2}}}{4}+\frac {y{^{2}}}{2}=1\end{cases}$ ，消去 $y$ 得 $\left ({t{^{4}}+16t{^{2}}+64}\right )x{^{2}}+4\left ({64-t{^{4}}}\right )x+4\left ({t{^{4}}-16t{^{2}}+64}\right )=0$ ，
17. 此时 ${\rm{Δ}}=16{\left({64-t{^{4}}}\right)^{2}}-16\left [{\left({t{^{4}}+64}\right)^{2}}-256t{^{4}}\right ]=0$ ,
18. 可知此时直线 $MP$ 与椭圆只有一个交点，直线 $MP$ 与椭圆相切，可得 $C､P､B$ 三点共线．
19. 方法三：因为 $\frac {x{^{2}}}{4}+\frac {y{^{2}}}{2}=1$ ，可得 $(\frac {x}{2}){^{2}}+(\frac {y}{\sqrt {2}}){^{2}}=1$ ，设 $\frac {x}{2}={\cos}θ，\frac {y}{\sqrt {2}}=\sin θ$ ，
20. 可知椭圆参数方程为 $\begin{cases}x=2{\cos}θ\\y=\sqrt {2}\sin θ\end{cases}$ ，
21. 则椭圆切线方程为 $\frac {x{\cos}θ}{2}+\frac {y\sin θ}{\sqrt {2}}=1$ ，代入 $M(-2,\frac {t}{2})$ 得 $-{\cos}θ+\frac {t\sin θ}{2\sqrt {2}}=1$ ，
22. 联立方程组 $\begin{cases}x=2{\cos}θ\\y=\sqrt {2}\sin θ\\-{\cos}θ+\frac {t\sin θ}{2\sqrt {2}}=1\end{cases}$ ，可知 ${\cos}θ=\frac {t\sin θ}{2\sqrt {2}}-1$ ，因为 $\sin {^{2}}θ+{\cos}{^{2}}θ=1$ ，
23. 所以 $\sin {^{2}}θ+{\left({\frac {t\sin θ}{2\sqrt {2}}-1}\right)^{2}}=1$ ，解得 $\sin θ=0$ （舍） $\sin θ=\frac {4\sqrt {2}t}{8+t{^{2}}}$ ，
24. 代入得 ${\cos}θ=\frac {t{^{2}}-8}{t{^{2}}+8}$ ，求得交点坐标 $P\left ({\frac {2t{^{2}}-16}{t{^{2}}+8},\frac {8t}{t{^{2}}+8}}\right )$ ，
25. 则 $K{{}_{BC}}=\frac {t}{-2-2}=-\frac {t}{4}$ ， $K{{}_{PC}}=\frac {\frac {8t}{t{^{2}}+8}-t}{\frac {2t{^{2}}-16}{t{^{2}}+8}+2}=-\frac {t}{4}$ ，
26. 可知 $K{{}_{BC}}=K{{}_{PC}}$ ，则 $C､P､B$ 三点共线．

## 知识点

**中文**:
  - 共线比例问题
  - 由椭圆的几何性质求方程
  - 直线与双曲线的位置关系

**English**:
  - Collinearity and Ratio Problems
  - Finding Equation from Properties
  - Line-Hyperbola Relationship

---
