# Mathematics - 题目 1707

**ID**: 04010f4752b74f2a80aae949d57e70e7
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知双曲线E： $\frac {x{^{2}}}{a{^{2}}}-\frac {y{^{2}}}{b{^{2}}}=1$ （ $a>0$ ， $b>0$ ）一个顶点为 $A\left ({-2,0}\right )$ ，直线l过点 $Q\left ({3,0}\right )$ 交双曲线右支于M，N两点，记 $△AMN$ ， $△AOM$ ， $\mathrm{△}AON$ 的面积分别为 ${\rm \mathit{S}，}S{{}_{{{1}}}}$ ， $S{{}_{{{2}}}}$ .​​​​​​​‌当l与x轴垂直时， $S{{}_{{{1}}}}$ 的值为 $\frac {\sqrt {15}}{2}$ .(1)求双曲线E的标准方程；(2)若l交y轴于点 ${\rm \mathit{P}，}\overrightarrow {{PM}}=λ\overrightarrow {{MQ}}$ ， $\overrightarrow {{PN}}=μ\overrightarrow {{NQ}}$ ，求证： $λ+μ$ 为定值；(3)在（2）的条件下，若 $\frac {16}{25}S=μS{{}_{1}}+mS{{}_{2}}$ ，当 $5<λ\mathrm{\leqslant }8$ 时，求实数m的取值范围.

## 解答

1. （1）由题意得 $a{\rm{=}}{{2}}$ ， $\left |{OA}\right |=2$ ，
2. 则当l与x轴垂直时，不妨设 $M\left ({3,y{{}_{1}}}\right )$ ，
3. 由 $S{{}_{1}}=\frac {1}{2}\left |{OA}\right |\cdot \left |{y{{}_{1}}}\right |=\frac {\sqrt {15}}{2}$ ，得 $\left |{y{{}_{1}}}\right |=\frac {\sqrt {15}}{2}$ ，
4. 将 $M\left ({3,y{{}_{1}}}\right )$ 代入方程 $\frac {x{^{2}}}{4}-\frac {y{^{2}}}{b{^{2}}}=1$ ，得 $\frac {9}{4}-\frac {\frac {15}{4}}{b{^{2}}}=1$ ，解得 $b{^{2}}=3$ ，
5. 所以双曲线E的方程为 $\frac {x{^{2}}}{4}-\frac {y{^{2}}}{3}=1$ ．
6. （2）设 $M\left ({x{{}_{1}},y{{}_{1}}}\right )$ ， $N\left ({x{{}_{2}},y{{}_{2}}}\right )$ ， $P\left ({0,y{{}_{0}}}\right )$ ，
7. 由 $\overrightarrow {{PM}}=λ\overrightarrow {{MQ}}$ 与 $Q\left ({3,0}\right )$ ，得 $\left ({x{{}_{1}},y{{}_{1}}-y{{}_{0}}}\right )=λ\left ({3-x{{}_{1}},-y{{}_{1}}}\right )$ ，
8. 即 $x{{}_{1}}=\frac {3λ}{1+λ}$ ， $y{{}_{1}}=\frac {y{{}_{0}}}{1+λ}$ ，将 $M\left ({\frac {3λ}{1+λ},\frac {y{{}_{0}}}{1+λ}}\right )$ 代入E的方程得： $\frac {{\left({\frac {3λ}{1+λ}}\right)^{2}}}{4}-\frac {{\left({\frac {y{{}_{0}}}{1+λ}}\right)^{2}}}{3}=1$ ，
9. 整理得： $15λ{^{2}}-24λ-4y{{}_{0}^{2}}-12=0$ ①，
10. 同理由 $\overrightarrow {{PN}}=μ\overrightarrow {{NQ}}$ 可得 $15μ{^{2}}-24μ-4y{{}_{0}^{2}}-12=0$ ②．
11. 由①②知， $λ$ ， $μ$ 是方程 $15x{^{2}}-24x-4y{{}_{0}^{2}}-12=0$ 的两个不等实根．
12. 由韦达定理知 $λ+μ=\frac {24}{15}=\frac {8}{5}$ ，所以 $λ+μ$ 为定值．
13. （3）又 $\frac {16}{25}S=μS{{}_{1}}+mS{{}_{2}}$ ，即 $\frac {16}{25}\cdot \frac {1}{2}\cdot \left |{AQ}\right |\cdot \left |{y{{}_{1}}-y{{}_{2}}}\right |=μ\frac {1}{2}\cdot 2\cdot \left |{y{{}_{1}}}\right |+m\cdot \frac {1}{2}\cdot 2\cdot \left |{y{{}_{2}}}\right |$ ，
14. 整理得： $\frac {8}{5}\left |{y{{}_{1}}-y{{}_{2}}}\right |=μ\left |{y{{}_{1}}}\right |+m\left |{y{{}_{2}}}\right |$ ，
15. 又 $y{{}_{1}}y{{}_{2}}<0$ ，不妨设 $y{{}_{2}}<0<y{{}_{1}}$ ，则 $\frac {8}{5}\left ({y{{}_{1}}-y{{}_{2}}}\right )=μy{{}_{1}}-my{{}_{2}}$ ，
16. 整理得 $m=\frac {8}{5}-\left ({\frac {8}{5}-μ}\right )\frac {y{{}_{1}}}{y{{}_{2}}}$ ，又 $λ+μ=\frac {8}{5}$ ，故 $m=\frac {8}{5}-λ\frac {y{{}_{1}}}{y{{}_{2}}}$ ，
17. 而由（2）知 $y{{}_{1}}=\frac {y{{}_{0}}}{1+λ}$ ， $y{{}_{2}}=\frac {y{{}_{0}}}{1+μ}$ ，故 $\frac {y{{}_{1}}}{y{{}_{2}}}=\frac {1+μ}{1+λ}$ ，
18. 代入 $m=\frac {8}{5}-λ\cdot \frac {1+μ}{1+λ}=\frac {8}{5}-\frac {λ\left ({\frac {13}{5}-λ}\right )}{1+λ}$ ，
19. 令 $1+λ=t$  $\left ({t\in \left ({6,9}\right ]}\right )$ ，得 $m=\frac {8}{5}-\frac {\left ({t-1}\right )\left ({\frac {18}{5}-t}\right )}{t}=-3+t+\frac {\frac {18}{5}}{t}$ ，
20. 由双勾函数 $y=t+\frac {\frac {18}{5}}{t}$ 在 $\left ({6,9}\right ]$ 上单调递增，得 $m=-3+t+\frac {\frac {18}{5}}{t}\in \left ({\frac {18}{5},\frac {32}{5}}\right ]$ ，
21. 所以m的取值范围为 $\left ({\frac {18}{5},\frac {32}{5}}\right ]$ ．
22. .

## 知识点

**中文**:
  - 定点定值定直线问题
  - 由双曲线的性质探求方程
  - 范围最值问题

**English**:
  - Fixed Point, Value, Line Problems
  - Finding Equation from Properties
  - Range and Extrema Problems

---
