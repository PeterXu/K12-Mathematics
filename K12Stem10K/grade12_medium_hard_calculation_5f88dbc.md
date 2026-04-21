# Mathematics - 题目 122

**ID**: 5f88dbc1ddb54b8aad04a5731d23841f
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知点 $P$ 是抛物线 $C:y=\frac {1}{4}x{^{2}}-3$ 的顶点， $A$ ， $B$ 是 $C$ 上的两个动点，且 $\overrightarrow {{PA}}\cdot \overrightarrow {{PB}}=-4$ .​​​​​​​‌（1）判断点 $D\left ({0,1}\right )$ 是否在直线 $AB$ 上？说明理由；（2）设点 $M$ 是△ $PAB$ 的外接圆的圆心，点 $M$ 到 $x$ 轴的距离为 $d$ ，点 $N\left ({1,0}\right )$ ，求 $\left |{MN}\right |-d$ 的最大值.

## 解答

1. （1）设直线方程 $y=kx+b$ ， $A\left ({x{{}_{1}},y{{}_{1}}}\right ),B\left ({x{{}_{2}},y{{}_{2}}}\right )$
2. 根据题意可知直线斜率一定存在， $P\left ({0,-3}\right )$
3. 则 $\begin{cases}y=kx+b\\y=\frac {1}{4}x{^{2}}-3\end{cases}\Rightarrow x{^{2}}-4kx-4\left ({3+b}\right )=0$
4. $x{{}_{1}}x{{}_{2}}=-4\left ({3+b}\right ),x{{}_{1}}+x{{}_{2}}=4k$
5. $\Delta ={\left({-4k}\right)^{2}}+16b+48$
6. $\overrightarrow {{PA}}=\left ({x{{}_{1}},y{{}_{1}}+3}\right ),\overrightarrow {{PB}}=\left ({x{{}_{2}},y{{}_{2}}+3}\right )$
7. 则 $\overrightarrow {{PA}}\cdot \overrightarrow {{PB}}=x{{}_{1}}x{{}_{2}}+\left ({y{{}_{1}}+3}\right )\left ({y{{}_{2}}+3}\right )$
8. $\overrightarrow {{PA}}\cdot \overrightarrow {{PB}}=x{{}_{1}}x{{}_{2}}+y{{}_{1}}y{{}_{2}}+3\left ({y{{}_{1}}+y{{}_{2}}}\right )+9$
9. $y{{}_{1}}y{{}_{2}}=\left ({kx{{}_{1}}+b}\right )\left ({kx{{}_{2}}+b}\right )=k{^{2}}x{{}_{1}}x{{}_{2}}+kb\left ({x{{}_{1}}+x{{}_{2}}}\right )+b{^{2}}$
10. $y{{}_{1}}+y{{}_{2}}=kx{{}_{1}}+b+kx{{}_{2}}+b=k\left ({x{{}_{1}}+x{{}_{2}}}\right )+2b$
11. $\overrightarrow {{PA}}\cdot \overrightarrow {{PB}}=\left ({k{^{2}}+1}\right )x{{}_{1}}x{{}_{2}}+\left ({3k+kb}\right )\left ({x{{}_{1}}+x{{}_{2}}}\right )+b{^{2}}+6b+9$
12. 由 $\overrightarrow {{PA}}\cdot \overrightarrow {{PB}}=-4$
13. 所以 $\left ({k{^{2}}+1}\right )x{{}_{1}}x{{}_{2}}+\left ({3k+kb}\right )\left ({x{{}_{1}}+x{{}_{2}}}\right )+b{^{2}}+6b+9=-4$
14. 将 $x{{}_{1}}x{{}_{2}}=-4\left ({3+b}\right ),x{{}_{1}}+x{{}_{2}}=4k$ 代入上式
15. 化简可得 $b{^{2}}+2b+1=0$ ，所以 $b=-1$
16. 则直线方程为 $y=kx-1$ ，
17. 所以直线过定点 $\left ({0,-1}\right )$ ， $\Delta ={\left({-4k}\right)^{2}}+16b+48>0$
18. 所以可知点 $D\left ({0,1}\right )$ 不在直线上.
19. （2）设 $M\left ({x{{}_{M}},y{{}_{M}}}\right )$
20. 线段 $PA$ 的中点为 $E\left ({\frac {x{{}_{1}}}{2},\frac {y{{}_{1}}-3}{2}}\right )$
21. 线段 $PB$ 的中点为 $G\left ({\frac {x{{}_{2}}}{2},\frac {y{{}_{2}}-3}{2}}\right )$
22. 则直线 $PA$ 的斜率为 $k{{}_{PA}}=\frac {y{{}_{1}}+3}{x{{}_{1}}}$ ，
23. 直线 $PB$ 的斜率为 $k{{}_{PB}}=\frac {y{{}_{2}}+3}{x{{}_{2}}}$
24. 可知线段 $PA$ 的中垂线的方程为 $y-\frac {y{{}_{1}}-3}{2}=-\frac {x{{}_{1}}}{y{{}_{1}}+3}\left ({x-\frac {x{{}_{1}}}{2}}\right )$
25. 由 $y{{}_{1}}=\frac {1}{4}x{{}_{1}^{2}}-3$ ，所以上式化简为 $y=-\frac {4}{x{{}_{1}}{^{2}}}x+\frac {x{{}_{1}}{^{2}}}{8}-1$
26. 即线段 $PA$ 的中垂线的方程为 $y=-\frac {4}{x{{}_{1}}{^{2}}}x+\frac {x{{}_{1}}{^{2}}}{8}-1$
27. 同理可得：
28. 线段 $PB$ 的中垂线的方程为 $y=-\frac {4}{x{{}_{2}}{^{2}}}x+\frac {x{{}_{2}}{^{2}}}{8}-1$
29. 则 $\begin{cases}y=-\frac {4}{x{{}_{2}}{^{2}}}x+\frac {x{{}_{2}}{^{2}}}{8}-1\\y=-\frac {4}{x{{}_{1}}{^{2}}}x+\frac {x{{}_{1}}{^{2}}}{8}-1\end{cases}\Rightarrow \begin{cases}x{{}_{M}}=-\frac {x{{}_{1}}x{{}_{2}}\left ({x{{}_{1}}+x{{}_{2}}}\right )}{32}\\y{{}_{M}}=\frac {x{{}_{1}}{^{2}}+x{{}_{2}}{^{2}}+x{{}_{1}}x{{}_{2}}-8}{32}\end{cases}$
30. 由（1）可知： $x{{}_{1}}+x{{}_{2}}=4k,x{{}_{1}}x{{}_{2}}=-4\left ({3+b}\right )=-8$
31. 所以 $\begin{cases}x{{}_{M}}=-\frac {x{{}_{1}}x{{}_{2}}\left ({x{{}_{1}}+x{{}_{2}}}\right )}{32}\\y{{}_{M}}=\frac {x{{}_{1}}{^{2}}+x{{}_{2}}{^{2}}+x{{}_{1}}x{{}_{2}}-8}{32}\end{cases}\Rightarrow \begin{cases}x{{}_{M}}=k\\y{{}_{M}}=2k{^{2}}\end{cases}$
32. 即 $M\left ({k,2k{^{2}}}\right )$ ，所以点 $M$ 轨迹方程为 $y=2x{^{2}}$
33. 焦点为 $F\left ({0,\frac {1}{8}}\right )$ ，
34. 所以 $\left |{MN}\right |-d=\left |{MN}\right |-\left ({\left |{MF}\right |-\frac {1}{8}}\right )=\left |{MN}\right |-\left |{MF}\right |+\frac {1}{8}$
35. 当 $M,N,F$ 三点共线时， $\left |{MN}\right |-d$ 有最大
36. 所以 $\left |{MN}\right |-d=\left |{MN}\right |-\left |{MF}\right |+\frac {1}{8}\leqslant \left |{NF}\right |+\frac {1}{8}=\frac {\sqrt {65}+1}{8}$

## 知识点

**中文**:
  - 与抛物线有关的距离问题、轨迹问题
  - 直线与抛物线的位置关系
  - 范围最值问题

**English**:
  - Distance and Locus Problems
  - Line-Parabola Relationship
  - Range and Extrema Problems

---
