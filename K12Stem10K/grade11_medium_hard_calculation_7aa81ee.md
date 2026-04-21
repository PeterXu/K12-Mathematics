# Mathematics - 题目 280

**ID**: 7aa81ee35a8a484492b05fd8dd54cab7
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知在平面直角坐标系中， $O$ 为坐标原点，设点 $A\left ({x{{}_{1}},y{{}_{1}}}\right )$ ， $B\left ({x{{}_{2}},y{{}_{2}}}\right )$ ，记 $D\left ({A,B}\right )=\sqrt {{\left({x{{}_{1}}-x{{}_{2}}}\right)^{2}}+{\left({y{{}_{1}}-y{{}_{2}}}\right)^{2}}}$ ， $d\left ({A,B}\right )=\left |{x{{}_{1}}-x{{}_{2}}}\right |+\left |{y{{}_{1}}-y{{}_{2}}}\right |$ ．（1）若 $D\left ({O,A}\right )=d\left ({O,A}\right )=2$ ，求点 $A$ 的坐标；​​​​​​​‌（2）若点 $M\left ({2,1}\right )$ ，点 $N\left ({x,y}\right )$ ，且 $d\left ({M,N}\right )=1$ ，求 $D\left ({M,N}\right )$ 的最大值；（3）已知点 $P$ ， $Q$ 是直线 $l:y-1=k\left ({x-1}\right )$ 上的动点，是否存在直线 $l$ 使得 $d(O,P){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=D(O,Q){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}$ ？若存在，求出所有满足条件的直线 $l$ 的方程；若不存在，说明理由．

## 解答

1. （1）由 $D\left ({O,A}\right )=d\left ({O,A}\right )=2$ ，得 $\sqrt {x{{}_{1}^{2}}+y{{}_{1}^{2}}}=\left |{x{{}_{1}}}\right |+\left |{y{{}_{1}}}\right |=2$ ，
2. $\therefore x{{}_{1}^{2}}+y{{}_{1}^{2}}=x{{}_{1}^{2}}+y{{}_{1}^{2}}+2\left |{x{{}_{1}}y{{}_{1}}}\right |=4$ ，解得 $\begin{cases}x{{}_{1}}=\pm 2\\y{{}_{1}}=0\end{cases}$ 或 $\begin{cases}x{{}_{1}}=0\\y{{}_{1}}=\pm 2\end{cases}$ ，
3. 所以点 $A$ 的坐标为 $\left ({2,0}\right )$ 或 $\left ({-2,0}\right )$ 或 $\left ({0,2}\right )$ 或 $\left ({0,-2}\right )$ .
4. （2）由题， $d\left ({M,N}\right )=\left |{x-2}\right |+\left |{y-1}\right |=1$ ，
5. 当 $x\geqslant 2,y\geqslant 1$ 时，方程 $\left |{x-2}\right |+\left |{y-1}\right |=1$ 变为 $x+y-4=0$ ，
6. 当 $x>2,y<1$ 时，方程变为 $x-y-2=0$ ，
7. 当 $x<2,y>1$ 时，方程变为 $x-y=0$ ，
8. 当 $x<2,y<1$ 时，方程变为 $x+y-2=0$ ，
9. 所以方程 $\left |{x-2}\right |+\left |{y-1}\right |=1$ 表示的图形是正方形，如图，
10. 其中 $A\left ({2,0}\right ),B\left ({3,1}\right ),C\left ({2,2}\right ),D\left ({1,1}\right )$ ，即点 $N$ 在正方形 $ABCD$ 的边上运动，
11. 而 $D\left ({M,N}\right )=\sqrt {{\left({x-2}\right)^{2}}+{\left({y-1}\right)^{2}}}$ 表示点 $M,N$ 间的距离， $M$ 是正方形 $ABCD$ 的中心，
12. $\therefore D\left ({M,N}\right )\leqslant 1$ ，即 $D\left ({M,N}\right )$ 的最大值为1.
13. 
14. （3）因为点 $O$ 到直线 $l$ 的距离为 $\frac {\left |{1-k}\right |}{\sqrt {k{^{2}}+1}}$ ，所以 $D\left ({O,Q}\right ){{}_{{\rm \min }}}=\frac {\left |{1-k}\right |}{\sqrt {k{^{2}}+1}}$ ，
15. 设 $P\left ({x,kx-k+1}\right )$ ，则 $d\left ({O,P}\right )=\left |{x}\right |+\left |{kx-k+1}\right |$ ，令 $h\left ({x}\right )=\left |{x}\right |+\left |{kx-k+1}\right |$ ，
16. 当 $k=0$ 时， $d\left ({O,P}\right )=\left |{x}\right |+1\geqslant 1$ ，此时 $D\left ({O,Q}\right ){{}_{{\rm \min }}}=d\left ({O,P}\right ){{}_{{\rm \min }}}=1$ ，合题意；
17. 当 $k\ne 0$ 时， $d\left ({O,P}\right )=h\left ({x}\right )=\left |{x}\right |+\left |{kx-k+1}\right |=\left |{x}\right |+\left |{k}\right |\cdot \left |{x-\frac {k-1}{k}}\right |$ ，
18. 由分段函数性质可得 $d\left ({O,P}\right ){{}_{{\rm \min }}}={\rm \min }\left \{h\left ({0}\right ),h\left ({\frac {k-1}{k}}\right )\right \}$ ，
19. 又 $h\left ({0}\right )=\left |{1-k}\right |\geqslant \frac {\left |{1-k}\right |}{\sqrt {k{^{2}}+1}}$ ，且 $h\left ({\frac {k-1}{k}}\right )=\left |{\frac {1-k}{k}}\right |\geqslant \frac {\left |{1-k}\right |}{\sqrt {k{^{2}}+1}}$ 恒成立，当且仅当 $k=1$ 时，等号成立，
20. 综上，满足条件的直线 $l$ 有且只有两条 $y=x$ 和 $y=1$ .

## 知识点

**中文**:
  - 平面向量的新定义问题

**English**:
  - New Definition Problems

---
