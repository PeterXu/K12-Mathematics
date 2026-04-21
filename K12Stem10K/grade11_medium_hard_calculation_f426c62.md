# Mathematics - 题目 2344

**ID**: f426c627be574e24b17179b76bae108a
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知圆 $M$ 与直线 $3x-\sqrt {7}y+4=0$ 相切于点 $\left ({1,\sqrt {7}}\right )$ ，圆心 $M$ 在 $x$ 轴上.​​​​​​​‌（1）求圆 $M$ 的标准方程；（2）若过点 $\left ({1,1}\right )$ 的直线 $l$ 与圆 $M$ 交于 $P,Q$ 两点，当 $\left |{PQ}\right |=2\sqrt {7}$ 时，求直线 $l$ 的一般式方程；（3）过点 $M$ 且不与 $x$ 轴重合的直线与圆 $M$ 相交于 $A,B$ 两点， $O$ 为坐标原点，直线 $OA,OB$ 分别与直线 $x=8$ 相交于 $C,D$ 两点，记 $\vartriangle OAB,\vartriangle OCD$ 的面积为 $S{{}_{1}},S{{}_{2}}$ ，求 $\frac {S{{}_{1}}}{S{{}_{2}}}$ 的最大值.

## 解答

1. （1）由题可知，设圆的方程为 ${\left({x-a}\right)^{2}}+y{^{2}}=r{^{2}},r>0$ ，圆心为 $(a,0)$ ，
2. 由直线 $3x-\sqrt {7}y+4=0$ 与圆相切于点 $\left ({1,\sqrt {7}}\right )$ ，
3. 得 $\begin{cases}(1-a){^{2}}+7=r{^{2}}\\\frac {\sqrt {7}}{1-a}\times \frac {3}{\sqrt {7}}=-1\end{cases}$ ，解得 $a=4,r=4$ ，
4. 所以圆的方程为 $(x-4){^{2}}+y{^{2}}=16$ ；
5. （2）设圆心 $M(4,0)$ 到直线 $l$ 的距离为d，
6. ∵ $\left |{PQ}\right |=2\sqrt {r{^{2}}-d{^{2}}}$ ，∴ $2\sqrt {7}=2\sqrt {16-d{^{2}}}$ ， $\therefore d=3$ .
7. ①当直线 $l$ 斜率不存在时， $x=1$ ，满足 $M(4,0)$ 到直线 $x=1$ 的距离 $d=3$ ；
8. ②当直线 $l$ 斜率存在时：设 $l$ 方程： $y-1=k\left ({x-1}\right )$ ，即 $kx-y+1-k=0$ ，
9. $\therefore d=\frac {|4k+1-k|}{\sqrt {k{^{2}}+1}}=3$ ，整理得 $(3k+1){^{2}}=9(k{^{2}}+1)$ ，解得 $k=\frac {4}{3}$ ，
10. $\therefore l:y-1=\frac {4}{3}(x-1)$ ，即 $4x-3y-1=0$ ，
11. 综上：直线 $l$ 的一般式方程为 $x=1$ 或 $4x-3y-1=0$ ；
12. （3）由题意知， $\angle AOB=\frac {{\rm{\mathrm{π}}}}{2}$ ，
13. 
14. 设直线 $OA$ 的斜率为 $k\left ({k\ne 0}\right )$ ，则直线 $OA$ 的方程为 $y=kx$ ，
15. 由 $\begin{cases}y=kx\\x{^{2}}+y{^{2}}-8x=0\end{cases}$ ，得 $\left ({1+k{^{2}}}\right )x{^{2}}-8x=0$ ，
16. 解得 $\begin{cases}x=0\\y=0\end{cases}$ 或 $\begin{cases}x=\frac {8}{1+k{^{2}}}\\y=\frac {8k}{1+k{^{2}}}\end{cases}$ ，则点A的坐标为 $\left ({\frac {8}{1+k{^{2}}},\frac {8k}{1+k{^{2}}}}\right )$ ，
17. 又直线 $OB$ 的斜率为 $-\frac {1}{k}$ ，同理可得：点 $B$ 的坐标为 $\left ({\frac {8k{^{2}}}{1+k{^{2}}},-\frac {8k}{1+k{^{2}}}}\right )$ ，
18. 由题可知： $C\left ({8,8k}\right ),D\left ({8,-\frac {8}{k}}\right )$ ，
19. $\therefore \frac {S{{}_{1}}}{S{{}_{2}}}=\frac {\left |{OA}\right |\left |{OB}\right |}{\left |{OD}\right |\left |{OC}\right |}=\frac {\left |{OA}\right |}{\left |{OC}\right |}\cdot \frac {\left |{OB}\right |}{\left |{OD}\right |}$ ，
20. 又 $\because \frac {\left |{OA}\right |}{\left |{OC}\right |}=\frac {x{{}_{A}}}{x{{}_{C}}}=\frac {\frac {8}{1+k{^{2}}}}{8}=\frac {1}{1+k{^{2}}}$ ，同理 $\frac {\left |{OB}\right |}{\left |{OD}\right |}=\frac {k{^{2}}}{1+k{^{2}}}$ ，
21. $\therefore \frac {S{{}_{1}}}{S{{}_{2}}}=\frac {k{^{2}}}{(k{^{2}}+1){^{2}}}=\frac {k{^{2}}}{k{^{4}}+2k{^{2}}+1}=\frac {1}{k{^{2}}+\frac {1}{k{^{2}}}+2}\leqslant \frac {1}{2\sqrt {k{^{2}}\cdot \frac {1}{k{^{2}}}}+2}=\frac {1}{4}$ ，
22. 当且仅当 $\left |{k}\right |=1$ 时等号成立，
23. $\therefore \frac {S{{}_{1}}}{S{{}_{2}}}$ 的最大值为 $\frac {1}{4}$ .

## 知识点

**中文**:
  - 弦长与弦心距
  - 直线与圆相切及圆的切线方程
  - 直线与圆相交

**English**:
  - Chord Length and Apothem
  - Tangency and Tangent Equations
  - Line Intersection with Circle

---
