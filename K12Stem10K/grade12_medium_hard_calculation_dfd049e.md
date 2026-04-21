# Mathematics - 题目 3399

**ID**: dfd049e80cc14a5d98bc7d6221776711
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
某校开展科普知识团队接力闯关活动，该活动共有两关，每个团队由 $n\left ({n\in {\mathbf{N}}{^{*}}}\right )$ 位成员组成，成员按预先安排的顺序依次上场，具体规则如下：若某成员第一关闯关成功，则该成员继续闯第二关，否则该成员结束闯关并由下一位成员接力去闯第一关；​​​​​​​‌若某成员第二关闯关成功，则该团队接力闯关活动结束，否则该成员结束闯关并由下一位成员接力去闯第二关；当第二关闯关成功或所有成员全部上场参加了闯关，该团队接力闯关活动结束．已知A团队每位成员闯过第一关和第二关的概率均为 $\frac {{{1}}}{{{2}}}$ ，且每位成员闯关是否成功互不影响，每关结果也互不影响．(1)用随机变量X表示A团队第 $2(n\in {\mathbf{N}}*,n\geqslant 2)$ 位成员的闯关数，求X的分布列；(2)已知A团队第 $6(n\in {\mathbf{N}}*,n>6)$ 位成员上场并闯过第二关，求恰好是第3位成员闯过第一关的概率；(3)记随机变量 $Y{{}_{n}}$ 表示A团队第 $Y{{}_{n}}\left ({Y{{}_{n}}=1,2,\cdots ,n}\right )$ 位成员上场并结束闯关活动，证明 $E\left ({Y{{}_{n}}}\right )$ 单调递增，并求使 $E\left ({Y{{}_{n}}}\right )\leqslant \frac {11}{4}$ 的n的最大值．

## 解答

1. （1）X的所有可能取值为0，1，2，
2. $P(X=0)=\frac {1}{4}$ ， $P(X=1)=\left ({1-\frac {1}{2}}\right )\times \left ({1-\frac {1}{2}}\right )+\frac {1}{2}\times \left ({1-\frac {1}{2}}\right )=\frac {1}{2}$ ，
3. $P(X=2)=\left ({1-\frac {1}{2}}\right )\times \frac {1}{2}=\frac {1}{4}$ ，
4. $所以X$ 的分布列如下：
5. X
6. 0
7. 1
8. 2
9. P
10. $\frac {1}{4}$
11. $\frac {1}{2}$
12. $\frac {1}{4}$
13. （2）记A团队第 $k\left ({1\leqslant k\leqslant n-1,k\in {\mathbf{N}}{^{{\mathbf{*}}}}}\right )$ 位成员上场且闯过第二关的概率为 $P{{}_{k}}$ ，
14. 若前面 $k-1$ 人都没有一人闯过第一关，其概率为 $P{{}_{k}}{^{\prime }}={\left({\frac {1}{2}}\right)^{k+1}}$ ，
15. 若前面 $k-1$ 人有一人闯过第一关，其概率为 $P{{}_{k}}{^{\prime \prime }}={\rm{C}}{{}_{k-1}^{1}}{\left({\frac {1}{2}}\right)^{k+1}}=(k-1){\left({\frac {1}{2}}\right)^{k+1}}$ ，
16. 所以 $P{{}_{k}}=P{{}_{k}}{^{\prime }}+P{{}_{k}}{^{\prime \prime }}=k{\left({\frac {1}{2}}\right)^{k+1}}$ ，
17. $M=$ “第6位成员上场且闯过第二关”， $N=$ “第3位成员闯过第一关”，
18. 所以 $P\left ({MN}\right )={\left({1-\frac {1}{2}}\right)^{2}}\times \frac {1}{2}\times {\left({1-\frac {1}{2}}\right)^{3}}\times \frac {1}{2}={\left({\frac {1}{2}}\right)^{7}}$ ，
19. $P\left ({N∣M}\right )=\frac {P\left ({MN}\right )}{P\left ({M}\right )}=\frac {1}{6}$ ．
20. （3）由（2）知， $P\left ({Y{{}_{n}}=k}\right )=P{{}_{k}}{^{\prime }}+P{{}_{k}}{^{\prime \prime }}=k{\left({\frac {1}{2}}\right)^{k+1}}\left ({1\leqslant k\leqslant n-1,k\in {\mathbf{N}}{^{{\mathbf{*}}}}}\right )$ ．
21. 当 $Y{{}_{n}}=n$ 时，若前面 ${\rm{n}}-1$ 人都没有一人闯过第一关，其概率为 $P^{′}{{{}_{n}}}={\left({\frac {1}{2}}\right)^{n-1}}$ ，
22. 若前面 $n-1$ 人有一人闯过第一关，其概率为 $P{{}_{n}}{^{\prime \prime }}=(n-1){\left({\frac {1}{2}}\right)^{n}}$ ，
23. 所以 $P\left ({Y{{}_{n}}=n}\right )=P{{}_{n}}{^{\prime }}+P{{}_{n}}{^{\prime \prime }}=(n+1){\left({\frac {1}{2}}\right)^{n}}$ ．
24. 所以 $E\left ({Y{{}_{n}}}\right )=\sum\limits_{k=1}^{n-1}\mathop{}k{^{2}}{\left({\frac {1}{2}}\right)^{k+1}}+n(n+1){\left({\frac {1}{2}}\right)^{n}}\left ({n\in {\mathbf{N}}{^{{\mathbf{*}}}},n\geqslant 2}\right )$ ．
25. $E\left ({Y{{}_{n+1}}}\right )-E\left ({Y{{}_{n}}}\right )=n{^{2}}{\left({\frac {1}{2}}\right)^{n+1}}+(n+1)(n+2){\left({\frac {1}{2}}\right)^{n+1}}-n(n+1){\left({\frac {1}{2}}\right)^{n}}$  $=(n+2){\left({\frac {1}{2}}\right)^{n+1}}>0$ ，即 $E\left ({Y{{}_{n}}}\right )$ 单调递增；又 $E\left ({Y{{}_{2}}}\right )=\frac {7}{4}$ ，
26. 故 $E\left ({Y{{}_{n}}}\right )=E\left ({Y{{}_{2}}}\right )+\left [E\left ({Y{{}_{3}}}\right )-E\left ({Y{{}_{2}}}\right )\right ]+\left [E\left ({Y{{}_{4}}}\right )-E\left ({Y{{}_{3}}}\right )\right ]+\cdots +\left [E\left ({Y{{}_{n}}}\right )-E\left ({Y{{}_{n-1}}}\right )\right ]$ ，
27. 所以 $E\left ({Y{{}_{n}}}\right )=\frac {7}{4}+4\times {\left({\frac {1}{2}}\right)^{3}}+5\times {\left({\frac {1}{2}}\right)^{4}}+\cdots +n{\left({\frac {1}{2}}\right)^{n-1}}+(n+1){\left({\frac {1}{2}}\right)^{n}}$ ，①
28. $\frac {1}{2}E\left ({Y{{}_{n}}}\right )=\frac {7}{8}+4\times {\left({\frac {1}{2}}\right)^{4}}+\cdots +(n-1){\left({\frac {1}{2}}\right)^{n-1}}+n{\left({\frac {1}{2}}\right)^{n}}+(n+1){\left({\frac {1}{2}}\right)^{n+1}}$ ，②
29. $①-②$ 得 $\frac {1}{2}E\left ({Y{{}_{n}}}\right )=\frac {11}{8}+{\left({\frac {1}{2}}\right)^{4}}+{\left({\frac {1}{2}}\right)^{5}}+\cdots +{\left({\frac {1}{2}}\right)^{n}}-(n+1){\left({\frac {1}{2}}\right)^{n+1}}=\frac {3}{2}-\frac {n+3}{2}{\left({\frac {1}{2}}\right)^{n}}$ ，
30. 故 $E\left ({Y{{}_{n}}}\right )=3-(n+3){\left({\frac {1}{2}}\right)^{n}}<3$ ．
31. 由 $3-(n+3){\left({\frac {1}{2}}\right)^{n}}\leqslant \frac {11}{4}$ ，得 $(n+3){\left({\frac {1}{2}}\right)^{n}}\geqslant \frac {1}{4}$ ，
32. 设 $a{{}_{n}}=(n+3){\left({\frac {1}{2}}\right)^{n}}$ ，则 $a{{}_{n+1}}-a{{}_{n}}=(n+4){\left({\frac {1}{2}}\right)^{n+1}}-(n+3){\left({\frac {1}{2}}\right)^{n}}=(-n-2){\left({\frac {1}{2}}\right)^{n+1}}<0$ ，
33. 所以 $\left \{a{{}_{n}}\right \}$ 单调递减， $a{{}_{5}}=\frac {1}{4}$ ，所以满足题意的n的最大值为5．

## 知识点

**中文**:
  - 数列求和方法之错位相减法
  - 离散型随机变量的分布列
  - 条件概率

**English**:
  - Offset Subtraction Method
  - Probability Distribution Table
  - Conditional Probability

---
