# Mathematics - 题目 2776

**ID**: f4bb632c6c4e42998c84f47fecc36ee8
**年级**: Grade 11
**难度**: Hard
**题型**: Calculation

## 题目
已知椭圆C： $\frac {x{^{2}}}{a{^{2}}}+\frac {y{^{2}}}{b{^{2}}}=1\left ({a>b>0}\right )$ 的左右焦点和上顶点构成边长为2的等边三角形.​​​​​​​‌（1）求椭圆C的方程；（2）关于圆的切线有这样的结论：“圆 $x{^{2}}+y{^{2}}=r{^{2}}$ 上点 $P\left ({x{{}_{0}},y{{}_{0}}}\right )$ 处的切线方程为 $x{{}_{0}}x+y{{}_{0}}y=$  $r{^{2}}$ ”，类比到椭圆也有这样的结论：“椭圆 $\frac {x{^{2}}}{a{^{2}}}+\frac {y{^{2}}}{b{^{2}}}=1\left ({a>b>0}\right )$ 上点 $P\left ({x{{}_{0}},y{{}_{0}}}\right )$ 处的切线方程为 $\frac {x{{}_{0}}x}{a{^{2}}}+\frac {y{{}_{0}}y}{b{^{2}}}=1$ ”.已知点M在直线 $x=4$ 上，过M作椭圆C的两条切线，切点分别为A，B，求证：直线 $AB$ 过定点；（3）对（2）中的A，B，在x轴上是否存在点N，使得 $\overrightarrow {{NA}}\cdot \overrightarrow {{NB}}$ 为定值？如果存在，求出此定值及点N的坐标；若不存在，请说明理由.

## 解答

1. （1）（1）由已知， $2c=2$ ， $b=\sqrt {3}c$ ，所以 $c=1$ ， $b=\sqrt {3}$ ， $a=2$ ，
2. 所以椭圆 $C$ 的方程为 $\frac {x{^{2}}}{4}+\frac {y{^{2}}}{3}=1$ .
3. （2）设 $A\left ({x{{}_{1}},y{{}_{1}}}\right )$ ， $B\left ({x{{}_{2}},y{{}_{2}}}\right )$ ， $M\left ({4,m}\right )$ ，
4. 则切线 $AM$ 的方程为 $3x{{}_{1}}x+4y{{}_{1}}y-12=0$ ，
5. 切线 $BM$ 的方程为 $3x{{}_{2}}x+4y{{}_{2}}y-12=0$ ，
6. ∵ $M\in AM$ ， $M\in BM$ ，
7. ∴ $\begin{cases}12x{{}_{1}}+4y{{}_{1}}m-12=0\\12x{{}_{2}}+4y{{}_{2}}m-12=0\end{cases}$ ，即A，B都在直线 $3x+my-3=0$ 上.
8. ∴直线 $AB$ 的方程为 $3x+my-3=0$ ，即 $my=-3\left ({x-1}\right )$ 所以直线 $AB$ 过定点.
9. （3）由（2）知直线 $AB$ 的斜率不为0，设 $AB$ 的方程为 $x=ty+1$ ，
10. 联立 $\begin{cases}x=ty+1\\\frac {x{^{2}}}{4}+\frac {y{^{2}}}{3}=1\end{cases}$ ，得 $\left ({3t{^{2}}+4}\right )y{^{2}}+6ty-9=0$ ，
11. ∴ $y{{}_{1}}+y{{}_{2}}=\frac {-6t}{3t{^{2}}+4}$ ， $y{{}_{1}}y{{}_{2}}=\frac {-9}{3t{^{2}}+4}$ ，
12. $x{{}_{1}}+x{{}_{2}}=t\left ({y{{}_{1}}+y{{}_{2}}}\right )+2=\frac {8}{3t{^{2}}+4}$ ， $x{{}_{1}}x{{}_{2}}=\left ({ty{{}_{1}}+1}\right )\left ({ty{{}_{2}}+1}\right )=\frac {-12t{^{2}}+4}{3t{^{2}}+4}$ ，
13. 设 $N\left ({n,0}\right )$ ，则 $\overrightarrow {{NA}}\cdot \overrightarrow {{NB}}=\left ({x{{}_{1}}-n}\right )\left ({x{{}_{2}}-n}\right )+y{{}_{1}}y{{}_{2}}=x{{}_{1}}x{{}_{2}}-n\left ({x{{}_{1}}+x{{}_{2}}}\right )+n{^{2}}+y{{}_{1}}y{{}_{2}}$
14. $=\frac {-12t{^{2}}+4-8n+\left ({3t{^{2}}+4}\right )n{^{2}}-9}{3t{^{2}}+4}=\frac {\left ({3n{^{2}}-12}\right )t{^{2}}+\left ({4n{^{2}}-8n-5}\right )}{3t{^{2}}+4}$ ，
15. 要使 $\overrightarrow {{NA}}\cdot \overrightarrow {{NB}}$ 为定值，则需 $\frac {3n{^{2}}-12}{3}=\frac {4n{^{2}}-8n-5}{4}$ ，
16. 解得 $n=\frac {11}{8}$ ，此时 $\overrightarrow {{NA}}\cdot \overrightarrow {{NB}}=-\frac {135}{64}$ ，
17. 所以存在点 $N\left ({\frac {11}{8},0}\right )$ ，使得 $\overrightarrow {{NA}}\cdot \overrightarrow {{NB}}$ 为定值 $-\frac {135}{64}$ .
18. 

## 知识点

**中文**:
  - 存在性或者探究性问题
  - 椭圆的标准方程及应用
  - 直线与椭圆的位置关系
  - 定点定值定直线问题

**English**:
  - Existence and Inquiry Problems
  - Standard Equation and Applications
  - Line-Ellipse Relationship
  - Fixed Point, Value, Line Problems

---
