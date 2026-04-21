# Mathematics - 题目 613

**ID**: a54fd455760341a68b7182e58f3f43d9
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知椭圆 $C{{}_{1}}:\frac {x{^{2}}}{b{^{2}}}+\frac {y{^{2}}}{a{^{2}}}=1$ 与双曲线 $C{{}_{2}}:\frac {x{^{2}}}{a{^{2}}}-\frac {y{^{2}}}{b{^{2}}}=1\left ({a>b>0}\right ),C{{}_{1}}$ 的焦点与 $C{{}_{2}}$ 的焦点间的距离为 $2\sqrt {2},b=1$ .​​​​​​​‌(1)求 $C{{}_{1}}$ 与 $C{{}_{2}}$ 的方程；(2)过坐标轴上的点 $P$ 可以作两条 $C{{}_{1}}$ 与 $C{{}_{2}}$ 的公切线.${\rm （i）}$ 求点 $P$ 的坐标.${\rm （ii）}$ 当点 $P$ 在 $y$ 轴上时，是否存在过点 $P$ 的直线 $l$ ，使 $l$ 与 $C{{}_{1}},C{{}_{2}}$ 均有两个交点？若存在，请求出 $l$ 的方程；若不存在，请说明理由.

## 解答

1. （1）由题意可得 $\sqrt {a{^{2}}-1+a{^{2}}+1}=2\sqrt {2}$ ，解得 $a{^{2}}=4$ .
2. 所以 $C{{}_{1}}:x{^{2}}+\frac {y{^{2}}}{4}=1,C{{}_{2}}:\frac {x{^{2}}}{4}-y{^{2}}=1$ .
3. （2）（i）显然公切线的斜率存在且不为0，设公切线 $l{{}_{0}}:y=kx+m\left ({k\ne 0}\right )$ ，
4. 
5. 联立 $\begin{cases}y=kx+m,\\x{^{2}}+\frac {y{^{2}}}{4}=1,\end{cases}$ 得 $\left ({k{^{2}}+4}\right )x{^{2}}+2kmx+m{^{2}}-4=0$ ，
6. 则 $Δ{{}_{1}}=4k{^{2}}m{^{2}}-4\left ({m{^{2}}-4}\right )\left ({k{^{2}}+4}\right )=4k{^{2}}m{^{2}}-\left ({4k{^{2}}m{^{2}}+16m{^{2}}-16k{^{2}}-64}\right )=16\left ({k{^{2}}-m{^{2}}+4}\right )=0$ ，
7. 即 $k{^{2}}+4=m{^{2}}$ ①
8. 联立 $\begin{cases}y=kx+m,\\\frac {x{^{2}}}{4}-y{^{2}}=1,\end{cases}$ 得 $\left ({1-4k{^{2}}}\right )x{^{2}}-8kmx-\left ({4m{^{2}}+4}\right )=0$ ，
9. 则 $Δ{{}_{2}}=64k{^{2}}m{^{2}}+4\left ({4m{^{2}}+4}\right )\left ({1-4k{^{2}}}\right )=64k{^{2}}m{^{2}}+16\left ({m{^{2}}+1}\right )\left ({1-4k{^{2}}}\right )=16\left ({m{^{2}}-4k{^{2}}+1}\right )=0$ ，即 $4k{^{2}}-1=m{^{2}}$ ②
10. 联立①②得 $k{^{2}}=\frac {5}{3},m{^{2}}=\frac {17}{3}$ ，所以公切线为 $l{{}_{0}}:y=\pm \frac {\sqrt {15}}{3}x+\frac {\sqrt {51}}{3}$ 或 $y=\pm \frac {\sqrt {15}}{3}x-\frac {\sqrt {51}}{3}$ .
11. 公切线的交点即点 $P$ 的坐标，
12. 由 $\begin{cases}y=\frac {\sqrt {15}}{3}x+\frac {\sqrt {51}}{3}\\y=-\frac {\sqrt {15}}{3}x+\frac {\sqrt {51}}{3}\end{cases}$ ，解得 $P\left ({0,\frac {\sqrt {51}}{3}}\right )$ ，由 $\begin{cases}y=\frac {\sqrt {15}}{3}x-\frac {\sqrt {51}}{3}\\y=-\frac {\sqrt {15}}{3}x-\frac {\sqrt {51}}{3}\end{cases}$ ，解得 $P\left ({0,-\frac {\sqrt {51}}{3}}\right )$ ，
13. 由 $\begin{cases}y=-\frac {\sqrt {15}}{3}x+\frac {\sqrt {51}}{3}\\y=+\frac {\sqrt {15}}{3}x-\frac {\sqrt {51}}{3}\end{cases}$ ，解得 $P\left ({\frac {\sqrt {765}}{15},0}\right )$ ， $\begin{cases}y=+\frac {\sqrt {15}}{3}x+\frac {\sqrt {51}}{3}\\y=-\frac {\sqrt {15}}{3}x-\frac {\sqrt {51}}{3}\end{cases}$ ，解得 $P\left ({0,-\frac {\sqrt {51}}{3}}\right )$ ，
14. 综上所述： $P\left ({0,\frac {\sqrt {51}}{3}}\right )$ 或 $P\left ({0,-\frac {\sqrt {51}}{3}}\right )$ 或 $P\left ({\frac {\sqrt {765}}{15},0}\right )$ 或 $P\left ({-\frac {\sqrt {765}}{15},0}\right )$ .
15. ${\rm （ii）}$ 当点 $P$ 在 $y$ 轴上时， $m{^{2}}=\frac {17}{3}$ ，
16. 假设存在直线 $l:y=tx\pm \frac {\sqrt {51}}{3}$ 与 $C{{}_{1}},C{{}_{2}}$ 均有两个交点，
17. 由 ${\rm （i）}$ 知 $\begin{cases}t{^{2}}-m{^{2}}+4=t{^{2}}-\frac {5}{3}>0\\m{^{2}}-4t{^{2}}+1=4\left ({\frac {5}{3}-t{^{2}}}\right )>0\end{cases}$ ，不等式组无解，
18. 所以不存在过点 $P$ 的直线 $l$ 与 $C{{}_{1}},C{{}_{2}}$ 均有两个交点.

## 知识点

**中文**:
  - 存在性或者探究性问题
  - 由椭圆的几何性质求方程
  - 由双曲线的性质探求方程
  - 直线与椭圆的位置关系
  - 直线与双曲线的位置关系

**English**:
  - Existence and Inquiry Problems
  - Finding Equation from Properties
  - Finding Equation from Properties
  - Line-Ellipse Relationship
  - Line-Hyperbola Relationship

---
