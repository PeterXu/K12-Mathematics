# Mathematics - 题目 100

**ID**: dad9017d06144b5eb427d1e170dcb081
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
平面直角坐标系中有 $n$ 只蚂蚁，分别位于点 $P{{}_{1}}(1,0),P{{}_{2}}(2,0),\cdots ,P{{}_{n}}(n,0)$ ．定义一次操作如下：将每只蚂蚁进行一次移动，等可能地朝上、下、左、右四个方向移动一个单位，各只蚂蚁的移动互不影响，移动后允许有多只蚂蚁在同一点处．若该点没有蚂蚁，则称这个点为“空点”．设随机变量 $X$ 为一次操作后 $P{{}_{i}}$ （ $1\leqslant i\leqslant n$ 且 $i\in {\rm{N}}{^{*}}$ ）中的“空点”数目．(1)若 $n=2$ ，求 $X$ 的分布列；​​​​​​​‌(2)定义随机变量 $Y{{}_{i}}=\begin{cases}1,若一次操作后P{{}_{i}}为“空点”\\0,若一次操作后P{{}_{i}}不为“空点”\end{cases}$ ，当 $n\geqslant 3$ 时，求 $Y{{}_{i}}$ 的分布列与期望 $E\left ({Y{{}_{i}}}\right )$ ；(3)当 $n\geqslant 3$ 时，求 $n$ 的最小值，使得 $E(X)<\frac {5}{8}n$ ．（参考公式：若 $ξ=η{{}_{1}}+η{{}_{2}}+\cdots +η{{}_{n}}$ ，则 $E(ξ)=E\left ({η{{}_{1}}}\right )+E\left ({η{{}_{2}}}\right )+\cdots +E\left ({η{{}_{n}}}\right )$ ）

## 解答

1. （1）当 $n=2$ 时 $X$ 的可能取值为 $0$ 、 $1$ 、 $2$ ，
2. $P\left ({X=0}\right )=\frac {1}{4}\times \frac {1}{4}=\frac {1}{16}$ ， $P\left ({X=1}\right )={\rm{C}}{{}_{2}^{1}}\times \frac {1}{4}\times \left ({1-\frac {1}{4}}\right )=\frac {3}{8}$ ，
3. $P\left ({X=2}\right )=\left ({1-\frac {1}{4}}\right )\times \left ({1-\frac {1}{4}}\right )=\frac {9}{16}$ ，
4. 所以 $X$ 的分布列为：
5. $X$
6. $0$
7. $1$
8. $2$
9. $P$
10. $\frac {1}{16}$
11. $\frac {3}{8}$
12. $\frac {9}{16}$
13. （2）对于 $i\in \left \{2,3,\cdots ,n-1\right \}$ ，则 $P\left ({Y{{}_{i}}=1}\right )={\left({\frac {3}{4}}\right)^{2}}=\frac {9}{16}$ ， $P\left ({Y{{}_{i}}=0}\right )=1-{\left({\frac {3}{4}}\right)^{2}}=\frac {7}{16}$ ，
14. 所以 $Y{{}_{i}}$ 的分布列为：
15. $Y{{}_{i}}$
16. $1$
17. $0$
18. $P$
19. $\frac {9}{16}$
20. $\frac {7}{16}$
21. 所以期望 $E\left ({Y{{}_{i}}}\right )=0\times \frac {7}{16}+1\times \frac {9}{16}=\frac {9}{16}$  $\left ({i\in \left \{2,3,\cdots ,n-1\right \}}\right )$ ；
22. 对于 $i\in \left \{1,n\right \}$ ，则 $P\left ({Y{{}_{i}}=1}\right )=\frac {3}{4}$ ， $P\left ({Y{{}_{i}}=0}\right )=1-\frac {3}{4}=\frac {1}{4}$ ，
23. 所以 $Y{{}_{i}}$ 的分布列为：
24. $Y{{}_{i}}$
25. $1$
26. $0$
27. $P$
28. $\frac {3}{4}$
29. $\frac {1}{4}$
30. 所以期望 $E\left ({Y{{}_{i}}}\right )=0\times \frac {1}{4}+1\times \frac {3}{4}=\frac {3}{4}$  $\left ({i\in \left \{1,n\right \}}\right )$ ；
31. （3）依题意可得 $X=Y{{}_{1}}+Y{{}_{2}}+\cdots +Y{{}_{n}}$ ，
32. 所以 $E\left ({X}\right )=E\left ({Y{{}_{1}}}\right )+E\left ({Y{{}_{2}}}\right )+\cdots +E\left ({Y{{}_{n}}}\right )=2\times \frac {3}{4}+\left ({n-2}\right )\times \frac {9}{16}=\frac {9n+6}{16}$ ，
33. 由 $E(X)<\frac {5}{8}n$ ，即 $\frac {9n+6}{16}<\frac {5}{8}n$ ，解得 $n>6$ ，又 $n\in {\rm{N}}*$ ，所以 $n$ 的最小值为 $7$ .

## 知识点

**中文**:
  - 离散型随机变量的分布列

**English**:
  - Probability Distribution Table

---
