# Mathematics - 题目 2090

**ID**: 9c03707d667142439910fa3882d54c6a
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
（1）在平面直角坐标系 $xOy$ 中， $O$ 为坐标原点，定义集合 $A=\left \{\left .​​​​​​​‌{\left ({x,y}\right )}\right |\left |{x}\right |+2\left |{y-1}\right |=4\right \}$ ，点 $\mathbf{Q}\left ({0,2}\right )$ ，对任意的点 $M\left ({x,y}\right )\in A$ ，求 $\left |{MQ}\right |$ 的取值范围；（2）在空间直角坐标系 $O-xyz$ 中，定义集合 $B=\left \{\left .{\left ({x,y,z}\right )}\right |\left |{x-1}\right |+\left |{y-1}\right |+\left |{z-1}\right |=2\right \}$ ， $\mathbf{Q}\left ({1,1,1}\right )$ ，点 $\mathbf{N}\left ({x,y,z}\right )$ 是集合 $B$ 内任意一点．①求 $\left |{NQ}\right |$ 的最小值；②求点 $N$ 的轨迹形成图形的全面积．注：若平面 $α$ 的法向量为 $\overrightarrow n=\left ({a,b,c}\right )\left ({a{^{2}}+b{^{2}}+c{^{2}}\ne 0}\right )$ ，点 $P{{}_{0}}\left ({x{{}_{0}},y{{}_{0}},z{{}_{0}}}\right )$ 是平面 $α$ 上一定点，则对于平面 $α$ 上任一点 $P\left ({x,y,z}\right )$ ，点 $P$ 满足方程： $ax+by+cz-\left ({ax{{}_{0}}+by{{}_{0}}+cz{{}_{0}}}\right )=0$ ．

## 解答

1. （1）将 $x$ 替换成 $-x$ ，原方程不变，于是点M形成的轨迹关于y轴对称，
2. 不妨令 $x\geqslant 0$ ， $x+2\left |{y-1}\right |=4$ ，
3. 若 $y\geqslant 1$ ，则 $x+2(y-1)=4$ ，即 $x+2y-6=0$ ，点M的轨迹是一条线段；
4. 若 $y\leqslant 1$ ，则 $x+2(1-y)=4$ ，即 $x-2y-2=0$ ，点M的轨迹是另一条线段；
5. 再利用图象关于y轴对称，最终点M形成的轨迹图形如下：
6. 
7. 由 $\begin{cases}x+2y-6=0\\x-2y-2=0\end{cases}$ 得 $\begin{cases}x=4\\y=1\end{cases}$ ，即 $A(4,1)$ ,
8. 则点M形成的轨迹图形关于点 $(0,1)$ 成中心对称图形且该图形为菱形，
9. 由图及对称性可知， $\left |{MQ}\right |$ 最短距离是点Q到直线 $x+2y-6=0$ 的距离 $d=\frac {\left |{0+4-6}\right |}{\sqrt {5}}=\frac {2\sqrt {5}}{5}$ ；
10. 而 $\left |{MQ}\right |$ 最大距离是点Q到 $A(4,1)$ 的距离， $\left |{AQ}\right |=\sqrt {(0-4){^{2}}+(2-1){^{2}}}=\sqrt {17}$ ，
11. 所以 $\left |{MQ}\right |$ 的取值范围为 $\left [\frac {2\sqrt {5}}{5},\sqrt {17}\right ]$ ；
12. （2）①先证明柯西不等式：
13. 设 $\overrightarrow a=\left ({x{{}_{1}},y{{}_{1}},z{{}_{1}}}\right )$ ， $\overrightarrow b=\left ({x{{}_{2}},y{{}_{2}},z{{}_{2}}}\right )$ ，由于 $\left |{\overrightarrow a\cdot \overrightarrow b}\right |=\left |{\overrightarrow a}\right |\cdot \left |{\overrightarrow b}\right |\cdot \left |{{\cos}\overrightarrow a,\overrightarrow b}\right |\leqslant \left |{\overrightarrow a}\right |\cdot \left |{\overrightarrow b}\right |$ ，
14. 于是 $\sqrt {x{{}_{1}^{2}}+y{{}_{1}^{2}}+z{{}_{1}^{2}}}\cdot \sqrt {x{{}_{2}^{2}}+y{{}_{2}^{2}}+z{{}_{2}^{2}}}\geqslant \left |{x{{}_{1}}x{{}_{2}}+y{{}_{1}}y{{}_{2}}+z{{}_{1}}z{{}_{2}}}\right |$ ，当且仅当 $\left ({x{{}_{1}},y{{}_{1}},z{{}_{1}}}\right ){\rm{/}}{\rm{/}}{\rm{(}}x{{}_{2}},y{{}_{2}},z{{}_{2}}{\rm{)}}$ 时，等号成立，
15. 于是令 $\overrightarrow a=\left ({\left |{x-1}\right |,\left |{y-1}\right |,\left |{z-1}\right |}\right )$ ， $\overrightarrow b=\left ({1,1,1}\right )$ ，则 $\left |{\overrightarrow {{NQ}}}\right |\cdot \sqrt {3}=\sqrt {{\left({x-1}\right)^{2}}+{\left({y-1}\right)^{2}}+{\left({z-1}\right)^{2}}}\sqrt {1{^{2}}+1{^{2}}+1{^{2}}}\geqslant \left |{x-1}\right |·1+\left |{y-1}\right |·1+\left |{z-1}\right |·1=2$ ，
16. 所以 $\left |{\overrightarrow {{NQ}}}\right |$  $\geqslant \frac {2\sqrt {3}}{3}$ ，当且仅当 $\left |{x-1}\right |=\left |{y-1}\right |=\left |{z-1}\right |$ 取等号，所以 $\left |{\overrightarrow {{NQ}}}\right |$ 的最小值为 $\frac {2\sqrt {3}}{3}$ ；
17. ②将x替换成 $2-x$ ，原方程不变，于是点N形成的轨迹关于平面 $x=1$ 对称，
18. 将y替换成 $2-y$ ，原方程不变，于是点N形成的轨迹关于平面 $y=1$ 对称，
19. 将z替换成 $2-z$ ，原方程不变，于是点N形成的轨迹关于平面 $z=1$ 对称，
20. 于是点N形成的轨迹关于点 $Q\left ({1,1,1}\right )$ 成中心对称图形，
21. $\left |{x-1}\right |+\left |{y-1}\right |+\left |{z-1}\right |=2$ 去绝对值后可以得到8个平面的方程，
22. 当 $x,y,z\geqslant 1$ 时，为 $x+y+z=5$ ,
23. 与三个平面 $x=1,y=1,z=1$ 围城三角形，顶点为 $R(1,1,3),S(1,3,1),T(3,1,1)$ ，
24. 则 $\vartriangle RST$ 为正三角形，边长 $|RS|=2\sqrt {2}$ ，其面积为 $\frac {\sqrt {3}}{4}|RS|{^{2}}=2\sqrt {3}$  ，
25. 则最终点 $N$ 的轨迹形成图形的全面积为 $8\times 2\sqrt {3}=16\sqrt {3}$ .

## 知识点

**中文**:
  - 点到直线的距离公式
  - 集合的新定义问题
  - 空间两点间距离公式

**English**:
  - Point-to-Line Distance
  - New Definition Problems in Sets
  - Distance Formula

---
