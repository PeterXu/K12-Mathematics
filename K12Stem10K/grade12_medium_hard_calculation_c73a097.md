# Mathematics - 题目 3064

**ID**: c73a0971ec474ff5b63a36748c63f552
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知  $F{{}_{1}}\mathrm{，}F{{}_{2}}$  分别为双曲线  $C:\frac {x{^{2}}}{a{^{2}}}-\frac {y{^{2}}}{b{^{2}}}=1\left ({a>0，b>0}\right )$  的左、右焦点，  $F{{}_{1}}$  关于双曲线  $C$  的一条渐近线  $l:y=-\frac {b}{a}x$  的对称点  $E$  在  $C$  上.​​​​​​​‌（1）求双曲线  $C$  的离心率；（2）若  $a=1$  ，双曲线  $C$  的左、右顶点分别为  $A{{}_{1}}，A{{}_{2}}$  ，过左顶点  $A{{}_{1}}$  作实轴的垂线交渐近线  $l$  于点  $T$  ，过  $T$  作直线分别交双曲线  $C$  的左、右两支于  $P，Q$  两点，直线  $A{{}_{2}}P，A{{}_{2}}Q$  分别交  $l$  于  $M，N$  两点. 证明: 四边形  $A{{}_{1}}MA{{}_{2}}N$  为平行四边形.

## 解答

1. （1）连接 $F{{}_{2}}E$ ,
2. 由于 $F{{}_{1}},E$ 关于直线 $l:y=-\frac {b}{a}x$ 对称，又 $\left |{OF{{}_{1}}}\right |=\left |{OF{{}_{2}}}\right |$ ，所以 $EF{{}_{2}}//l$ ，
3. $F{{}_{1}}\left ({-c,0}\right )$ 到直线 $l:y=-\frac {b}{a}x$ 的距离为 $d=\frac {\left |{-\frac {b}{a}\cdot \left ({-c}\right )}\right |}{\sqrt {1{^{2}}+{\left({-\frac {b}{a}}\right)^{2}}}}=b$ ，
4. 因此 $\left |{F{{}_{1}}E}\right |=2b$ ，故 $\left |{F{{}_{2}}E}\right |=\sqrt {{\left({2c}\right)^{2}}-{\left({2b}\right)^{2}}}=2a$ ，
5. 由双曲线定义可得 $\left |{F{{}_{1}}E}\right |-\left |{F{{}_{2}}E}\right |=2b-2a=2a$ ，故 $b=2a$ ，
6. 因此离心率为 $e=\frac {c}{a}=\sqrt {1+{\left({\frac {b}{a}}\right)^{2}}}=\sqrt {5}$ .
7. （2）当 $a=1$ 时，则 $b=2$ ，故双曲线的方程为 $x{^{2}}-\frac {y{^{2}}}{4}=1$ ，
8. $A{{}_{1}}\left ({-1,0}\right )$ ，直线 $l:y=-2x$ ，故 $T\left ({-1,2}\right )$ ，
9. 由题意可知直线 $PQ$ 有斜率，故设 $PQ:y=k\left ({x+1}\right )+2$ ，
10. 联立 $PQ:y=k\left ({x+1}\right )+2$ 与 $x{^{2}}-\frac {y{^{2}}}{4}=1$ 可得 $\left ({k{^{2}}-4}\right )x{^{2}}+2k\left ({k+2}\right )x+k{^{2}}+4k+8=0$ ，
11. 设 $P\left ({x{{}_{1}},y{{}_{1}}}\right ),Q\left ({x{{}_{2}},y{{}_{2}}}\right )$ ，则 $\begin{cases}x{{}_{1}}+x{{}_{2}}=\frac {-2k\left ({k+2}\right )}{k{^{2}}-4},\\x{{}_{1}}x{{}_{2}}=\frac {k{^{2}}+4k+8}{k{^{2}}-4},\\Δ=\left [2k\left ({k+2}\right )\right ]{^{2}}-4\left ({k{^{2}}-4}\right )\left ({k{^{2}}+4k+8}\right )>0,\end{cases}$
12. 则直线 $A{{}_{2}}P:y=\frac {y{{}_{1}}}{x{{}_{1}}-1}\left ({x-1}\right )$ ，联立与 $l:y=-2x$ 方程可得 $-2x=\frac {y{{}_{1}}}{x{{}_{1}}-1}\left ({x-1}\right )$ ，
13. 解得 $x=\frac {y{{}_{1}}}{2x{{}_{1}}+y{{}_{1}}-2}$ ， $y=\frac {-2y{{}_{1}}}{2x{{}_{1}}+y{{}_{1}}-2}$ ，所以 $M\left ({\frac {y{{}_{1}}}{2x{{}_{1}}+y{{}_{1}}-2},\frac {-2y{{}_{1}}}{2x{{}_{1}}+y{{}_{1}}-2}}\right )$ ,
14. 同理可得 $N\left ({\frac {y{{}_{2}}}{2x{{}_{2}}+y{{}_{2}}-2},\frac {-2y{{}_{2}}}{2x{{}_{2}}+y{{}_{2}}-2}}\right )$ ,
15. $\overrightarrow {{A{{}_{1}}M}}=\left ({\frac {y{{}_{1}}}{2x{{}_{1}}+y{{}_{1}}-2}+1,\frac {-2y{{}_{1}}}{2x{{}_{1}}+y{{}_{1}}-2}}\right )$ , $\overrightarrow {{NA{{}_{2}}}}=\left ({1-\frac {y{{}_{2}}}{2x{{}_{2}}+y{{}_{2}}-2},\frac {2y{{}_{2}}}{2x{{}_{2}}+y{{}_{2}}-2}}\right )$ ,
16. $\frac {-2y{{}_{1}}}{2x{{}_{1}}+y{{}_{1}}-2}-\frac {2y{{}_{2}}}{2x{{}_{2}}+y{{}_{2}}-2}=\frac {-2y{{}_{1}}\left ({2x{{}_{2}}+y{{}_{2}}-2}\right )-2y{{}_{2}}\left ({2x{{}_{1}}+y{{}_{1}}-2}\right )}{\left ({2x{{}_{1}}+y{{}_{1}}-2}\right )\left ({2x{{}_{2}}+y{{}_{2}}-2}\right )}$
17. $-y{{}_{1}}\left ({2x{{}_{2}}+y{{}_{2}}-2}\right )-y{{}_{2}}\left ({2x{{}_{1}}+y{{}_{1}}-2}\right )=-\left [k\left ({x{{}_{1}}+1}\right )+2\right ]\left [2x{{}_{2}}+k\left ({x{{}_{2}}+1}\right )+2-2\right ]-\left [k\left ({x{{}_{2}}+1}\right )+2\right ]\left [2x{{}_{1}}+k\left ({x{{}_{1}}+1}\right )+2-2\right ]$  $=-\left [kx{{}_{1}}+k+2\right ]\left [\left ({2+k}\right )x{{}_{2}}+k\right ]-\left [kx{{}_{2}}+k+2\right ]\left [\left ({2+k}\right )x{{}_{1}}+k\right ]$
18. $=-\left [2k\left ({k+2}\right )x{{}_{1}}x{{}_{2}}+\left ({2k{^{2}}+4k+4}\right )\left ({x{{}_{1}}+x{{}_{2}}}\right )+2k\left ({k+2}\right )\right ]$
19. $=-\left [2k\left ({k+2}\right )\frac {k{^{2}}+4k+8}{k{^{2}}-4}+\left ({2k{^{2}}+4k+4}\right )\left ({\frac {-2k\left ({k+2}\right )}{k{^{2}}-4}}\right )+2k\left ({k+2}\right )\right ]$
20. $=-2k\left ({k+2}\right )\left [\frac {k{^{2}}+4k+8}{k{^{2}}-4}-\frac {2k{^{2}}+4k+4}{k{^{2}}-4}+1\right ]$
21. $=-2k\left ({k+2}\right )\left [\frac {k{^{2}}+4k+8}{k{^{2}}-4}-\frac {2k{^{2}}+4k+4}{k{^{2}}-4}+\frac {k{^{2}}-4}{k{^{2}}-4}\right ]=0$ ，
22. 所以 $\frac {-2y{{}_{1}}}{2x{{}_{1}}+y{{}_{1}}-2}=\frac {2y{{}_{2}}}{2x{{}_{2}}+y{{}_{2}}-2}$ ，即 $\frac {-y{{}_{1}}}{2x{{}_{1}}+y{{}_{1}}-2}=\frac {y{{}_{2}}}{2x{{}_{2}}+y{{}_{2}}-2}$ ，
23. 因此 $1-\frac {y{{}_{2}}}{2x{{}_{2}}+y{{}_{2}}-2}=1+\frac {y{{}_{1}}}{2x{{}_{1}}+y{{}_{1}}-2}$ ，因此 $\overrightarrow {{A{{}_{1}}M}}=\overrightarrow {{NA{{}_{2}}}}$ ,
24. 故四边形 $A{{}_{1}}MA{{}_{2}}N$  为平行四边形.
25. 

## 知识点

**中文**:
  - 共线比例问题
  - 双曲线的离心率
  - 直线与双曲线的位置关系

**English**:
  - Collinearity and Ratio Problems
  - Eccentricity
  - Line-Hyperbola Relationship

---
