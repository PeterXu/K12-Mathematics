# Mathematics - 题目 628

**ID**: 7e49e05da8f9447d82d45b602ac3a3f9
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知椭圆 $E:\frac {x{^{2}}}{a{^{2}}}+\frac {y{^{2}}}{b{^{2}}}=1\left ({a>b>0}\right )$ 的两个焦点和两个顶点四点共圆，且与直线 $x-\sqrt {6}y=4$ 相切.​​​​​​​‌（1）求椭圆 $E$ 的标准方程；（2）过点 $\left ({0,1}\right )$ 作斜率为 $k$ 的直线交椭圆 $E$ 于 $C$ 、 $D$ 两点，线段 $CD$ 的垂直平分线交 $y$ 轴于点为 $Q$ ，点 $Q$ 关于直线 $CD$ 的对称点为点 $P$ ，若四边形 $PCQD$ 为正方形，求 $k$ 的值.

## 解答

1. （1）因为椭圆 $E$ 的两个焦点和两个顶点四点共圆，所以 $b=c$ ，则 $a=\sqrt {b{^{2}}+c{^{2}}}=\sqrt {2}b$ ，
2. 所以椭圆 $E$ 的方程为 $\frac {x{^{2}}}{2b{^{2}}}+\frac {y{^{2}}}{b{^{2}}}=1$ ，
3. 由 $\begin{cases}x-\sqrt {6}y=4,\\\frac {x{^{2}}}{2b{^{2}}}+\frac {y{^{2}}}{b{^{2}}}=1\end{cases}$ 消去 $x$ ，得 $8y{^{2}}+8\sqrt {6}y+16-2b{^{2}}=0$ ，
4. 因为椭圆 $E$ 与直线 $x-\sqrt {6}y=4$ 相切，
5. 所以令 ${\rm{Δ}}={\left({8\sqrt {6}}\right)^{2}}-4\times 8\left ({16-2b{^{2}}}\right )=0$ ，解得 $b{^{2}}=2$ ，所以 $a{^{2}}=4$ ，
6. 所以椭圆 $E$ 的标准方程为 $\frac {x{^{2}}}{4}+\frac {y{^{2}}}{2}=1$ .
7. （2）设直线 $CD$ 的方程为 $y=kx+1$ ，设点 $C\left ({x{{}_{1}},y{{}_{1}}}\right )$ 、 $D\left ({x{{}_{2}},y{{}_{2}}}\right )$ ， $CD$ 的中点为 $M$ ，
8. 
9. 联立 $\begin{cases}y=kx+1\\\frac {x{^{2}}}{4}+\frac {y{^{2}}}{2}=1\end{cases}$ 消去 $y$ ，得 $\left ({2k{^{2}}+1}\right )x{^{2}}+4kx-2=0$ ，
10. ${\rm{Δ}}=16k{^{2}}+8\left ({2k{^{2}}+1}\right )>0$ ，
11. 由韦达定理得 $x{{}_{1}}+x{{}_{2}}=\frac {-4k}{2k{^{2}}+1}$ ， $x{{}_{1}}x{{}_{2}}=\frac {-2}{2k{^{2}}+1}$ ，
12. 所以 $x{{}_{M}}=\frac {x{{}_{1}}+x{{}_{2}}}{2}=\frac {-2k}{2k{^{2}}+1}$ ，代入 $y=kx+1$ ，解得 $y{{}_{M}}=\frac {1}{2k{^{2}}+1}$ ，
13. 故线段 $CD$ 的中点 $M$ 的坐标为 $\left ({\frac {-2k}{2k{^{2}}+1},\frac {1}{2k{^{2}}+1}}\right )$ ，
14. 所以线段 $CD$ 的垂直平分线的方程为 $y-\frac {1}{2k{^{2}}+1}=-\frac {1}{k}\left ({x-\frac {-2k}{2k{^{2}}+1}}\right )$ ，
15. 令 $x=0$ ，解得 $y{{}_{Q}}=-\frac {1}{2k{^{2}}+1}$ ，即 $Q\left ({0,-\frac {1}{2k{^{2}}+1}}\right )$ ，
16. 因为线段 $PQ$ 和线段 $CD$ 互相垂直平分，所以四边形 $PCQD$ 为菱形，
17. 要使四边形 $PCQD$ 为正方形，需满足 $QC\bot QD$ ，
18. 所以 $\overrightarrow {{QC}}\cdot \overrightarrow {{QD}}=\left ({x{{}_{1}},y{{}_{1}}+\frac {1}{2k{^{2}}+1}}\right )\cdot \left ({x{{}_{2}},y{{}_{2}}+\frac {1}{2k{^{2}}+1}}\right )$  $=x{{}_{1}}x{{}_{2}}+\left ({kx{{}_{1}}+1+\frac {1}{2k{^{2}}+1}}\right )\cdot \left ({kx{{}_{2}}+1+\frac {1}{2k{^{2}}+1}}\right )$
19. $=\left ({k{^{2}}+1}\right )x{{}_{1}}x{{}_{2}}+\frac {2k\left ({k{^{2}}+1}\right )\left ({x{{}_{1}}+x{{}_{2}}}\right )}{2k{^{2}}+1}+{\left({\frac {2k{^{2}}+2}{2k{^{2}}+1}}\right)^{2}}$
20. $=\frac {-2\left ({k{^{2}}+1}\right )}{2k{^{2}}+1}+\frac {2k\left ({k{^{2}}+1}\right )\cdot \left ({-\frac {4k}{2k{^{2}}+1}}\right )}{2k{^{2}}+1}+\frac {4{\left({k{^{2}}+1}\right)^{2}}}{{\left({2k{^{2}}+1}\right)^{2}}}=0$ ,
21. 即 $\left ({k{^{2}}+1}\right )\left ({4k{^{2}}-1}\right )=0$ ，解得 $k=\pm \frac {1}{2}$ ，则 $k$ 的值为 $\pm \frac {1}{2}$ .

## 知识点

**中文**:
  - 椭圆的标准方程及应用
  - 直线与椭圆的位置关系

**English**:
  - Standard Equation and Applications
  - Line-Ellipse Relationship

---
