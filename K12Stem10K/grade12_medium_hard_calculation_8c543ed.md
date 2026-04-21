# Mathematics - 题目 2437

**ID**: 8c543ed9aec14d7f9f92b44ad6c27ffd
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知双曲线 $C:\frac {x{^{2}}}{a{^{2}}}-\frac {y{^{2}}}{b{^{2}}}=1\left ({a>0,\,b>0}\right )$ 的一条渐近线的方程为 $x-2y=0$ ，点 $D\left ({4,\,\sqrt {3}}\right )$ 在 $C$ 上．过直线 $l:x=1$ 上一点 $T\left ({1,\,t}\right )\left ({t\ne \pm \frac {1}{2}}\right )$ 作 $C$ 的两条切线，切点 $A,B$ 都在 $C$ 的右支上．直线 $AB$ 与 $x$ 轴交于点 $M$ ．（参考结论：二次曲线 $mx{^{2}}+ny{^{2}}=1$ 在曲线上某点 $\left ({x{{}_{0}},\,y{{}_{0}}}\right )$ 处的切线方程为 $mx{{}_{0}}x+ny{{}_{0}}y=1$ ）（1）求双曲线 $C$ 的方程；​​​​​​​‌（2）设 $A,B$ 在直线 $l$ 上的投影分别为 $P,\,Q$ ．记 $\vartriangle AMP$ ， $\vartriangle PMQ$ ， $\vartriangle QMB$ 的面积分别为 $S{{}_{1}},S{{}_{2}},S{{}_{3}}$ ，证明： $S{{}_{1}},\frac {1}{2}S{{}_{2}},S{{}_{3}}$ 成等比数列．

## 解答

1. （1）由题意得 $\frac {b}{a}=\frac {1}{2},\frac {16}{a{^{2}}}-\frac {3}{b{^{2}}}=1$ ，解得 $a=2,\,b=1$ ．
2. 所以双曲线 $C$ 的方程为 $\frac {x{^{2}}}{4}-y{^{2}}=1$ ；
3. （2）设 $A\left ({x{{}_{1}},\,y{{}_{1}}}\right ),\,B\left ({x{{}_{2}},\,y{{}_{2}}}\right ),\,T\left ({1,\,t}\right )\left ({t\ne \pm \frac {1}{2}}\right )$ ，
4. 
5. 由参考结论，切线 $TA$ 的方程为 $\frac {x{{}_{1}}x}{4}-y{{}_{1}}y=1$ ，
6. 将 $T\left ({1,\,t}\right )$ 代入得 $\frac {x{{}_{1}}}{4}-y{{}_{1}}t=1$ ，同理可得 $\frac {x{{}_{2}}}{4}-y{{}_{2}}t=1$ ，
7. 所以直线 $AB$ 的方程为 $\frac {x}{4}-ty=1$ ，令 $y=0$ ，解得 $x=4$ ，则 $M\left ({4,\,0}\right )$ ．
8. 联立直线 $AB$ ： $\frac {x}{4}-ty=1$ 与双曲线 $C$ 的方程 $\frac {x{^{2}}}{4}-y{^{2}}=1$ ，
9. 消去 $x$ 得： $\left ({4t{^{2}}-1}\right )y{^{2}}+8ty+3=0,4t{^{2}}-1\ne 0$ ，
10. 所以 $y{{}_{1}}+y{{}_{2}}=-\frac {8t}{4t{^{2}}-1},y{{}_{1}}y{{}_{2}}=\frac {3}{4t{^{2}}-1}$ ，
11. 由题知 $P\left ({1,\,y{{}_{1}}}\right ),\,Q\left ({1,\,y{{}_{2}}}\right )$ ，
12. 所以 $S{{}_{1}}=\frac {1}{2}\left |{AP}\right |\cdot \left |{y{{}_{1}}}\right |=\frac {1}{2}\left |{x{{}_{1}}-1}\right |\cdot \left |{y{{}_{1}}}\right |=\frac {1}{2}\left |{4ty{{}_{1}}+3}\right |\cdot \left |{y{{}_{1}}}\right |$ ，
13. 同理 $S{{}_{3}}=\frac {1}{2}\left |{4ty{{}_{2}}+3}\right |\cdot \left |{y{{}_{2}}}\right |$ ，
14. 又 $S{{}_{2}}=\frac {1}{2}\times \left ({4-1}\right )\cdot \left |{y{{}_{1}}-y{{}_{2}}}\right |=\frac {3}{2}\left |{y{{}_{1}}-y{{}_{2}}}\right |$ ，
15. 而 ${\left({\frac {1}{2}S{{}_{2}}}\right)^{2}}=\frac {9}{16}\left |{y{{}_{1}}-y{{}_{2}}}\right |{^{2}}=\frac {9}{16}\left [{\left({\frac {8t}{4t{^{2}}-1}}\right)^{2}}-\frac {12}{4t{^{2}}-1}\right ]=\frac {9\left ({4t{^{2}}+3}\right )}{4{\left({4t{^{2}}-1}\right)^{2}}}\ne 0$ ，
16. 又 $S{{}_{1}}S{{}_{3}}=\frac {1}{4}\left |{y{{}_{1}}y{{}_{2}}}\right |\cdot \left |{16t{^{2}}y{{}_{1}}y{{}_{2}}+12t\left ({y{{}_{1}}+y{{}_{2}}}\right )+9}\right |=\frac {1}{4}\left |{\frac {3}{4t{^{2}}-1}}\right |\cdot \left |{16t{^{2}}\cdot \frac {3}{4t{^{2}}-1}-12t\cdot \frac {8t}{4t{^{2}}-1}+9}\right |$
17. $=\frac {3}{4{\left({4t{^{2}}-1}\right)^{2}}}\left |{-12t{^{2}}-9}\right |=\frac {9\left ({4t{^{2}}+3}\right )}{4{\left({4t{^{2}}-1}\right)^{2}}}$ ，
18. 所以 $S{{}_{1}}S{{}_{3}}={\left({\frac {1}{2}S{{}_{2}}}\right)^{2}}\ne 0$ ，即 $S{{}_{1}},\frac {1}{2}S{{}_{2}},S{{}_{3}}$ 成等比数列．

## 知识点

**中文**:
  - 由双曲线的性质探求方程
  - 等比数列的性质
  - 直线与双曲线的位置关系

**English**:
  - Finding Equation from Properties
  - Properties
  - Line-Hyperbola Relationship

---
