# Mathematics - 题目 266

**ID**: b92616ab834b4e4592f3be7a684c238a
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知点 $A(1,0)$ ，点 $B$ 是圆 $O{{}_{1}}:(x+1){^{2}}+y{^{2}}=16$ 上的动点，线段 $AB$ 的垂直平分线与 $BO{{}_{1}}$ 相交于点 $C$ ，点 $C$ 的轨迹为曲线 $E$ .​​​​​​​‌（1）求 $E$ 的方程（2）过点 $O{{}_{1}}$ 作倾斜角互补的两条直线 $l{{}_{1}},l{{}_{2}}$ ，若直线 $l{{}_{1}}$ 与曲线 $E$ 交于 $M,N$ 两点，直线 $l{{}_{2}}$ 与圆 $O{{}_{1}}$ 交于 $P,Q$ 两点，当 $M,N,P,Q$ 四点构成四边形，且四边形 $MPNQ{\rm{\;}}$ 的面积为 $8\sqrt {3}$ 时，求直线 $l{{}_{1}}$ 的方程.

## 解答

1. （1） $\because C$ 在线段 $AB$ 的垂直平分线上， $\therefore CA=CB$ ，
2. 又 $C$ 在 $BO{{}_{1}}$ 上， $\therefore O{{}_{1}}B=O{{}_{1}}C+CB=O{{}_{1}}C+CA=4$ ，
3. 则可得点 $C$ 的轨迹是以 $O{{}_{1}},A$ 为焦点的椭圆，
4. 则 $2a=4$ ，即 $a=2$ ， $c=1$ ， $b{^{2}}=a{^{2}}-c{^{2}}=3$ ，
5. 故 $E$ 的方程为 $\frac {x{^{2}}}{4}+\frac {y{^{2}}}{3}=1$ ；
6. （2）若 $l{{}_{1}}\bot x$ 轴时，如图，此时 $PQ=8$ ， $MO{{}_{1}}=\frac {3}{2}$ ，则 $S{{}_{MPNQ}}=8\times \frac {3}{2}=12$ ，不符合题意；
7. 
8. 若 $l{{}_{2}}\bot x$ 轴时，如图，此时 $MN=4$ ， $OP=4$ ，则 $S{{}_{MPNQ}}=4\times 4=16$ ，不符合题意；
9. 
10. 当 $l{{}_{1}},l{{}_{2}}$ 都不与坐标轴垂直时，如图，
11. 
12. 设 $l{{}_{1}}$ 斜率分别为 $k$ ，由于 $l{{}_{1}},l{{}_{2}}$ 倾斜角互补，则 $l{{}_{2}}$ 斜率为 $-k$ ，
13. 则直线 $l{{}_{1}}$ 方程为 $y=k\left ({x+1}\right )$ ，直线 $l{{}_{2}}$ 方程为 $y=-k\left ({x+1}\right )$ ，
14. 联立直线 $l{{}_{1}}$ 与椭圆 $\begin{cases}y=k\left ({x+1}\right )\\\frac {x{^{2}}}{4}+\frac {y{^{2}}}{3}=1\end{cases}$ ，可得 $\left ({3+4k{^{2}}}\right )x{^{2}}+8k{^{2}}x+4k{^{2}}-12=0$ ，
15. 设 $M\left ({x{{}_{1}},y{{}_{1}}}\right ),N\left ({x{{}_{2}},y{{}_{2}}}\right )$ ，则 $x{{}_{1}}+x{{}_{2}}=-\frac {8k{^{2}}}{3+4k{^{2}}}$ ， $x{{}_{1}}x{{}_{2}}=\frac {4k{^{2}}-12}{3+4k{^{2}}}$ ，
16. 则点 $M$ 到直线 $l{{}_{2}}$ 的距离为 $d{{}_{1}}=\frac {\left |{kx{{}_{1}}+y{{}_{1}}+k}\right |}{\sqrt {k{^{2}}+1}}=\frac {\left |{2kx{{}_{1}}+2k}\right |}{\sqrt {k{^{2}}+1}}=\frac {2\left |{k}\right |\left |{x{{}_{1}}+1}\right |}{\sqrt {k{^{2}}+1}}$ ，
17. 同理可得点 $N$ 到直线 $l{{}_{2}}$ 的距离为 $d{{}_{2}}=\frac {2\left |{k}\right |\left |{x{{}_{2}}+1}\right |}{\sqrt {k{^{2}}+1}}$ ，
18. 则 $S{{}_{MPNQ}}=\frac {1}{2}\left |{PQ}\right |\left ({d{{}_{1}}+d{{}_{2}}}\right )=\frac {1}{2}\times 8\times \left ({\frac {2\left |{k}\right |\left |{x{{}_{1}}+1}\right |}{\sqrt {k{^{2}}+1}}+\frac {2\left |{k}\right |\left |{x{{}_{2}}+1}\right |}{\sqrt {k{^{2}}+1}}}\right )$
19. $=\frac {1}{2}\times 8\times \frac {2\left |{k}\right |}{\sqrt {k{^{2}}+1}}\left ({\left |{x{{}_{1}}+1}\right |+\left |{x{{}_{2}}+1}\right |}\right )=\frac {8\left |{k}\right |}{\sqrt {k{^{2}}+1}}\left |{x{{}_{1}}-x{{}_{2}}}\right |$
20. $=\frac {8\left |{k}\right |}{\sqrt {k{^{2}}+1}}\sqrt {{\left({x{{}_{1}}+x{{}_{2}}}\right)^{2}}-4x{{}_{1}}x{{}_{2}}}=\frac {8\left |{k}\right |}{\sqrt {k{^{2}}+1}}\sqrt {{\left({-\frac {8k{^{2}}}{3+4k{^{2}}}}\right)^{2}}-4\times \frac {4k{^{2}}-12}{3+4k{^{2}}}}$
21. $=\frac {96\left |{k}\right |}{3+4k{^{2}}}=8\sqrt {3}$ ，解得 $k=\pm \frac {\sqrt {3}}{2}$ ，
22. 故直线 $l{{}_{1}}$ 的方程为 $y=\frac {\sqrt {3}}{2}x+\frac {\sqrt {3}}{2}$ 或 $y=-\frac {\sqrt {3}}{2}x-\frac {\sqrt {3}}{2}$ .

## 知识点

**中文**:
  - 圆锥曲线与直线、圆相结合的问题
  - 弦长面积问题

**English**:
  - Combined Problems with Lines and Circles
  - Chord Length and Area Problems

---
