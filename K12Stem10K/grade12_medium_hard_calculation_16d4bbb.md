# Mathematics - 题目 1163

**ID**: 16d4bbb8c9c34d2d9ccead8897df93d0
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知双曲线 $C:\frac {x{^{2}}}{a{^{2}}}-\frac {y{^{2}}}{b{^{2}}}=1\left ({a>0,b>0}\right )$ 的离心率为 $\sqrt {2}$ ，右焦点为 $F\left ({2,0}\right )$ ．(1)求双曲线 $C$ 的标准方程；​​​​​​​‌(2)过点 $F$ 的直线 $l$ 与双曲线 $C$ 的右支交于 $A,B$ 两点，在 $x$ 轴上是否存在点 $P$ ， 使得 $\overrightarrow {{PA}}\cdot \overrightarrow {{PB}}$ 为定值？若存在，求出该定值；若不存在，请说明理由．

## 解答

1. （1）由题意可得 $\begin{cases}e=\frac {c}{a}=\sqrt {2}\\c=2\end{cases}$ ，所以 $a=\sqrt {2},c=2,b{^{2}}=c{^{2}}-a{^{2}}=2$ ，
2. 所以双曲线 $C$ 的标准方程为 $\frac {x{^{2}}}{2}-\frac {y{^{2}}}{2}=1$ ；
3. （2）依题意，直线 $l$ 的斜率不为0，设其方程为 $x=my+2$ ， $-1<m<1$ ，
4. 代入 $\frac {x{^{2}}}{2}-\frac {y{^{2}}}{2}=1$ 得 $\left ({m{^{2}}-1}\right )y{^{2}}+4my+2=0$ ，
5. 设 $A\left ({x{{}_{1}},y{{}_{1}}}\right )$ ， $B\left ({x{{}_{2}},y{{}_{2}}}\right )$ ， $P\left ({t,0}\right )$ ，
6. 则 $y{{}_{1}}+y{{}_{2}}=-\frac {4m}{m{^{2}}-1}$ ， $y{{}_{1}}y{{}_{2}}=\frac {2}{m{^{2}}-1}$ ，
7. ∴ $\overrightarrow {{PA}}\cdot \overrightarrow {{PB}}=\left ({x{{}_{1}}-t}\right )\left ({x{{}_{2}}-t}\right )+y{{}_{1}}y{{}_{2}}=\left ({my{{}_{1}}+2-t}\right )\left ({my{{}_{2}}+2-t}\right )+y{{}_{1}}y{{}_{2}}$
8. $=\left ({m{^{2}}+1}\right )y{{}_{1}}y{{}_{2}}+m\left ({2-t}\right )\left ({y{{}_{1}}+y{{}_{2}}}\right )+{\left({2-t}\right)^{2}}$
9. $=\left ({m{^{2}}+1}\right )\frac {2}{m{^{2}}-1}-m\left ({2-t}\right )\frac {4m}{m{^{2}}-1}+{\left({2-t}\right)^{2}}$
10. $=\frac {\left ({4t-6}\right )m{^{2}}+2}{m{^{2}}-1}+{\left({2-t}\right)^{2}}$ ，
11. 若要上式为定值，则必须有 $4t-6=-2$ ，即 $t=1$ ，
12. ∴ $\frac {\left ({4t-6}\right )m{^{2}}+2}{m{^{2}}-1}+{\left({2-t}\right)^{2}}=-2+1=-1$ ，
13. 故存在点 $P\left ({1,0}\right )$ 满足 $\overrightarrow {{PA}}\cdot \overrightarrow {{PB}}=-1$ .
14. 

## 知识点

**中文**:
  - 定点定值定直线问题
  - 由双曲线的性质探求方程
  - 直线与双曲线的位置关系

**English**:
  - Fixed Point, Value, Line Problems
  - Finding Equation from Properties
  - Line-Hyperbola Relationship

---
