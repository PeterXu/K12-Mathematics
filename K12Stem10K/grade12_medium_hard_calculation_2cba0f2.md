# Mathematics - 题目 1027

**ID**: 2cba0f2fbb13436fb041997cc85c5f14
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知双曲线 $C:\frac {x{^{2}}}{a{^{2}}}-\frac {y{^{2}}}{b{^{2}}}=1\left ({a>0,b>0}\right )$ 的右焦点为 $F$ ，右顶点为 $A,O$ 为坐标原点，且 $\left |{OA}\right |=\left |{AF}\right |=1$ .​​​​​​​‌（1）求 $C$ 的方程；（2）过点 $F$ 的直线 $l$ 与 $C$ 的右支交于 $M,N$ 两点，记 $C$ 的左顶点为 $B$ ，证明： $BM\bot BN$ .

## 解答

1. （1）解：由 $\left |{OA}\right |=\left |{AF}\right |$ ，可得 $a=c-a=1$ ，即 $c=2a=2$ ，
2. 则 $b{^{2}}=c{^{2}}-a{^{2}}=3$ ，
3. 所以 $C$ 的方程为 $x{^{2}}-\frac {y{^{2}}}{3}=1$ ；
4. （2）
5. 
6. 解法一：证明：由题可知， $l$ 的斜率不为0，
7. 可设 $l$ 的方程为 $x=ty+2$ ， $M\left ({x{{}_{1}},y{{}_{1}}}\right ),N\left ({x{{}_{2}},y{{}_{2}}}\right )$
8. 由 $\begin{cases}x=ty+2\\x{^{2}}-\frac {y{^{2}}}{3}=1\end{cases}$ ，可得 $\left ({3t{^{2}}-1}\right )y{^{2}}+12ty+9=0$ ，
9. 则 $3t{^{2}}-1\ne 0$ ， $y{{}_{1}}+y{{}_{2}}=-\frac {12t}{3t{^{2}}-1}$ ， $y{{}_{1}}y{{}_{2}}=\frac {9}{3t{^{2}}-1}$ ，
10. 由题可知 $B\left ({-1,0}\right )$ ，则 $\overrightarrow {{BM}}=\left ({x{{}_{1}}+1,y{{}_{1}}}\right )$ ， $\overrightarrow {{BN}}=\left ({x{{}_{2}}+1,y{{}_{2}}}\right )$ ，
11. $\overrightarrow {{BM}}\cdot \overrightarrow {{BN}}=\left ({x{{}_{1}}+1}\right )\left ({x{{}_{2}}+1}\right )+y{{}_{1}}y{{}_{2}}=\left ({ty{{}_{1}}+3}\right )\left ({ty{{}_{2}}+3}\right )+y{{}_{1}}y{{}_{2}}$ ，
12. $=\left ({t{^{2}}+1}\right )y{{}_{1}}y{{}_{2}}+3t\left ({y{{}_{1}}+y{{}_{2}}}\right )+9=\frac {9\left ({t{^{2}}+1}\right )}{3t{^{2}}-1}-\frac {36t{^{2}}}{3t{^{2}}-1}+9=0$ ，
13. 所以 $BM\bot BN$ .
14. 解法二：若 $l$ 的斜率不存在，则可得 $M\left ({2,3}\right ),N\left ({2,-3}\right )$ ，由题可知 $B\left ({-1,0}\right )$ ，
15. 则 $\overrightarrow {{BM}}=\left ({3,3}\right ),\overrightarrow {{BN}}=\left ({3,-3}\right ),\overrightarrow {{BM}}\cdot \overrightarrow {{BN}}=9-9=0$ ，则 $BM\bot BN$
16. 若 $l$ 的斜率存在，则可设 $l$ 的方程为 $y=k\left ({x-2}\right )$ ， $M\left ({x{{}_{1}},y{{}_{1}}}\right ),N\left ({x{{}_{2}},y{{}_{2}}}\right )$ .
17. 由 $\begin{cases}y=k\left ({x-2}\right )\\x{^{2}}-\frac {y{^{2}}}{3}=1\end{cases}$ 可得 $\left ({3-k{^{2}}}\right )x{^{2}}+4k{^{2}}x-4k{^{2}}-3=0$ ，
18. 则 $3-k{^{2}}\ne 0$ ， $x{{}_{1}}+x{{}_{2}}=-\frac {4k{^{2}}}{3-k{^{2}}}$ ， $x{{}_{1}}x{{}_{2}}=-\frac {4k{^{2}}+3}{3-k{^{2}}}$ .
19. $\overrightarrow {{BM}}=\left ({x{{}_{1}}+1,y{{}_{1}}}\right ),\overrightarrow {{BN}}=\left ({x{{}_{2}}+1,y{{}_{2}}}\right )$ ，
20. 则 $\overrightarrow {{BM}}\cdot \overrightarrow {{BN}}=\left ({x{{}_{1}}+1}\right )\left ({x{{}_{2}}+1}\right )+y{{}_{1}}y{{}_{2}}=\left ({x{{}_{1}}+1}\right )\left ({x{{}_{2}}+1}\right )+k{^{2}}\left ({x{{}_{1}}-2}\right )\left ({x{{}_{2}}-2}\right )$ ，
21. $=\left ({1+k{^{2}}}\right )x{{}_{1}}x{{}_{2}}+\left ({1-2k{^{2}}}\right )\left ({x{{}_{1}}+x{{}_{2}}}\right )+1+4k{^{2}}$ ，
22. $=\frac {\left ({1+k{^{2}}}\right )\left ({-4k{^{2}}-3}\right )-4k{^{2}}\left ({1-2k{^{2}}}\right )+\left ({3-k{^{2}}}\right )\left ({1+4k{^{2}}}\right )}{3-k{^{2}}}=0$ ，
23. 所以 $BM\bot BN$ .

## 知识点

**中文**:
  - 双曲线标准方程及其应用
  - 直线与双曲线的位置关系
  - 垂直平分问题

**English**:
  - Standard Equation and Applications
  - Line-Hyperbola Relationship
  - Perpendicular Bisector Problems

---
