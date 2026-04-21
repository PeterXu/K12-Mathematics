# Mathematics - 题目 1757

**ID**: aa8428ff7221459abfc126336ec3df97
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知平行四边形 $OADB$ （O为坐标原点）的面积 $S=1$ ，其中 $OB$ 所在直线为 $y=2x$ ， $OA$ 所在直线为 $y=-2x$ ，动点 $D$ 的轨迹为双曲线 $C$ ，且双曲线 $C$ 与 $y$ 轴没有交点.​​​​​​​‌(1)求双曲线 $C$ 的方程；(2)设点 $P\left ({1,0}\right )$ ， $Q\left ({0,λ}\right )$ ， $E\left ({0,4-λ}\right )$ ，直线 $PQ$ ， $PE$ 与双曲线 $C$ 分别交于点 $M,N$ （其中 $M,N$ 不与点 $P$ 重合）， $G$ 为直线 $MN$ 上一点，且 $PG\bot MN$ ，求 $\left |{OG}\right |$ 的最大值.

## 解答

1. （1）设点 $D\left ({x{{}_{0}},y{{}_{0}}}\right )$ ，则点 $D$ 到直线 $OB$ 的距离 $d=\frac {\left |{2x{{}_{0}}-y{{}_{0}}}\right |}{\sqrt {2{^{2}}+{\left({-1}\right)^{2}}}}=\frac {\left |{2x{{}_{0}}-y{{}_{0}}}\right |}{\sqrt {5}}$ ，
2. 由 $DB//OA$ 得， $k{{}_{DB}}=-2$ ，∴直线 $DB$ 的方程为 $y-y{{}_{0}}=-2\left ({x-x{{}_{0}}}\right )$ ，整理得 $y=-2x+2x{{}_{0}}+y{{}_{0}}$ .
3. 由 $\begin{cases}y=2x\\y=-2x+2x{{}_{0}}+y{{}_{0}}\end{cases}$ 得 $x{{}_{B}}=\frac {2x{{}_{0}}+y{{}_{0}}}{4}$ ， $y{{}_{B}}=\frac {2x{{}_{0}}+y{{}_{0}}}{2}$ ，
4. ∴ $\left |{OB}\right |=\sqrt {x{{}_{B}^{2}}+y{{}_{B}^{2}}}=\frac {\sqrt {5}}{4}\left |{2x{{}_{0}}+y{{}_{0}}}\right |$ ，
5. ∴平行四边形 $OADB$ 的面积 $S=\left |{OB}\right |\cdot d=\frac {\sqrt {5}}{4}\left |{2x{{}_{0}}+y{{}_{0}}}\right |\cdot \frac {\left |{2x{{}_{0}}-y{{}_{0}}}\right |}{\sqrt {5}}=1$ ，整理得 $x{{}_{0}^{2}}-\frac {y{{}_{0}^{2}}}{4}=\pm 1$ .
6. ∵动点 $D$ 的轨迹为双曲线 $C$ ，且双曲线 $C$ 与 $y$ 轴没有交点，
7. ∴双曲线 $C$ 的焦点在 $x$ 轴上，即双曲线 $C$ 的方程为 $x{^{2}}-\frac {y{^{2}}}{4}=1$ .
8. （2）
9. 
10. 由（1）得，点 $P\left ({1,0}\right )$ 为双曲线 $C$ 的右焦点，双曲线渐近线方程为 $y=\pm \frac {b}{a}x=\pm 2x$ .
11. 当直线 $MN$ 斜率不存在时，可得直线 $PM,PN$ 关于 $x$ 轴对称，即直线 $PQ,PE$ 关于 $x$ 轴对称，
12. 不妨设点 $Q$ 在点 $E$ 上方，此时 $Q\left ({2,0}\right )$ ， $k{{}_{PQ}}=\frac {2-0}{0-1}=-2$ ，直线 $PQ$ 与双曲线的一条渐近线平行，直线 $PQ$ 与双曲线只有一个交点 $P$ ，不合题意，故直线 $MN$ 的斜率存在.
13. 设直线 $MN$ ： $y=mx+n$ ， $M\left ({x{{}_{1}},y{{}_{1}}}\right )$ ， $N\left ({x{{}_{2}},y{{}_{2}}}\right )$ ，
14. 由方程组 $\begin{cases}x{^{2}}-\frac {y{^{2}}}{4}=1\\y=mx+n\end{cases}$ 得 $\left ({4-m{^{2}}}\right )x{^{2}}-2mnx-\left ({n{^{2}}+4}\right )=0\left ({m\ne \pm 2}\right )$ ，
15. 则 ${\rm{Δ}}=16\left ({4+n{^{2}}-m{^{2}}}\right )>0$ ①， $x{{}_{1}}+x{{}_{2}}=-\frac {2mn}{m{^{2}}-4}$ ， $x{{}_{1}}x{{}_{2}}=\frac {n{^{2}}+4}{m{^{2}}-4}$ ②.
16. ∵ $k{{}_{PM}}=\frac {y{{}_{1}}}{x{{}_{1}}-1}$ ，∴直线 $PM$ 方程为： $y=\frac {y{{}_{1}}}{x{{}_{1}}-1}\left ({x-1}\right )$ ，
17. 令 $x=0$ ，得 $y{{}_{Q}}=λ=-\frac {y{{}_{1}}}{x{{}_{1}}-1}$ ，同理得 $y{{}_{E}}=4-λ=-\frac {y{{}_{2}}}{x{{}_{2}}-1}$ ，故 $\frac {y{{}_{1}}}{x{{}_{1}}-1}+\frac {y{{}_{2}}}{x{{}_{2}}-1}=-4$ ，
18. 将 $y{{}_{1}}=mx{{}_{1}}+n$ ， $y{{}_{2}}=mx{{}_{2}}+n$ 代入上式，整理得： $\left ({2m+4}\right )x{{}_{1}}x{{}_{2}}+\left ({n-m-4}\right )\left ({x{{}_{1}}+x{{}_{2}}}\right )+4-2n=0$ ，
19. 将②代入得 $m{^{2}}+2mn+n{^{2}}+2m+2n=0$ ，整理得 $\left ({m+n}\right )\left ({m+n+2}\right )=0$ ，
20. 若 $m+n=0$ ，则直线 $MN$ ： $y=m\left ({x-1}\right )$ ，恒过点 $P\left ({1,0}\right )$ ，不合题意；
21. 若 $m+n+2=0$ ，则 $n=-m-2$ ，故直线 $MN$ ： $y=m\left ({x-1}\right )-2$ ，恒过点 $H\left ({1,-2}\right )$ .
22. ∵直线 $MN$ 恒过点 $H\left ({1,-2}\right )$ ，且与双曲线 $C:x{^{2}}-\frac {y{^{2}}}{4}=1$ 始终有两个交点，
23. ∴ $\begin{cases}{\rm{Δ}}=16\left ({4+n{^{2}}-m{^{2}}}\right )=16\left ({8+4m}\right )>0\\m\ne \pm 2\end{cases}$ ，解得 $m>-2$ 且 $m\ne 2$ .
24. ∵ $P\left ({1,0}\right )$ ， $PG\bot MN$ ，垂足为 $G$ ，∴点 $G$ 在以 $PH$ 为直径的圆上，
25. 设 $PH$ 的中点为 $T$ ，则圆心 $T\left ({1,-1}\right )$ ，半径为1，圆 $T$ 方程为 ${\left({x-1}\right)^{2}}+{\left({y+1}\right)^{2}}=1$ ，
26. ∴ $\left |{OG}\right |\leqslant \left |{OT}\right |+1=\sqrt {2}+1$ ，当且仅当点 $G$ 在线段 $OT$ 的延长线上时，等号成立，
27. 由 $O\left ({0,0}\right ),T\left ({1,-1}\right )$ 得直线 $OT$ 方程为 $y=-x$ ，与圆 $T$ 方程联立得 $\begin{cases}x=1+\frac {\sqrt {2}}{2}\\y=-1-\frac {\sqrt {2}}{2}\end{cases}$ 或 $\begin{cases}x=1-\frac {\sqrt {2}}{2}\\y=-1+\frac {\sqrt {2}}{2}\end{cases}$ ，
28. ∴ $G\left ({1+\frac {\sqrt {2}}{2},-1-\frac {\sqrt {2}}{2}}\right )$ ，故 $k{{}_{PG}}=\frac {-1-\frac {\sqrt {2}}{2}}{1+\frac {\sqrt {2}}{2}-1}=-\sqrt {2}-1$ ，
29. ∴直线 $MN$ 的斜率 $m=-\frac {1}{k{{}_{PG}}}=\sqrt {2}-1$ ，满足题意，
30. ∴ $\left |{OG}\right |$ 的最大值为 $\sqrt {2}+1$ .

## 知识点

**中文**:
  - 由双曲线的性质探求方程
  - 直线与双曲线的位置关系
  - 范围最值问题

**English**:
  - Finding Equation from Properties
  - Line-Hyperbola Relationship
  - Range and Extrema Problems

---
