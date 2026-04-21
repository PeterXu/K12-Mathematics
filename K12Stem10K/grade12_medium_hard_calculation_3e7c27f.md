# Mathematics - 题目 2912

**ID**: 3e7c27f826654a6593cd0a1fd99ce901
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
在”五四”来临之际，某学校团委组织以“春风吹，青春启航”为主题的知识竞赛，比赛分初赛和决赛两个阶段，甲、乙两人进入决赛争夺冠军，决赛规则如下：每轮答题获得 $1$ 分，其概率为 $\frac {1}{3}$ ，获得 $2$ 分，其概率为 $\frac {2}{3}$ .​​​​​​​‌最多进行 $20$ 轮答题，某同学累计得分为 $20$ 分时，比赛结束，该同学获得冠军，另一同学获得亚军.(1)当进行完 $3$ 轮答题后，甲同学总分为 $Y$ ，求 $Y$ 的分布列及 $E(Y)$ ；(2)若累计得分为 $m$ 的概率为 $P{{}_{m}}$ ，（初始得分为 $0$ 分， $p{{}_{0}}=1$ ）①求 $P{{}_{m}}-P{{}_{m-1}}$ 的表达式( $0\leqslant m\leqslant 19,m\in {\rm{N}}{^{*}}$ ).②求获得亚军的概率.

## 解答

1. （1）设进行完 $3$ 轮答题时，得 $1$ 分的次数为 $X$ ， $X\sim B(3,\frac {1}{3})$ .
2. $P\left ({X=k}\right )={\rm{C}}{{}_{3}^{k}}{\left({\frac {1}{3}}\right)^{k}}{\left({\frac {2}{3}}\right)^{3-k}}$ ， $k=0,1,2,3$ ，
3. 随机变量 $Y$ 表示甲同学的总分，其可能取值为 $3$ ， $4$ ， $5$ ， $6$ ，
4. $P\left ({Y=3}\right )=P\left ({X=3}\right )={\rm{C}}{{}_{3}^{3}}{\left({\frac {1}{3}}\right)^{3}}{\left({\frac {2}{3}}\right)^{0}}=\frac {1}{27}$ ，
5. $P\left ({Y=4}\right )=P\left ({X=2}\right )={\rm{C}}{{}_{3}^{2}}{\left({\frac {1}{3}}\right)^{2}}{\left({\frac {2}{3}}\right)^{1}}=\frac {2}{9}$ ，
6. $P\left ({Y=5}\right )=P\left ({X=1}\right )={\rm{C}}{{}_{3}^{1}}{\left({\frac {1}{3}}\right)^{1}}{\left({\frac {2}{3}}\right)^{2}}=\frac {4}{9}$ ，
7. $P\left ({Y=6}\right )=P\left ({X=0}\right )={\rm{C}}{{}_{3}^{0}}{\left({\frac {1}{3}}\right)^{0}}{\left({\frac {2}{3}}\right)^{3}}=\frac {8}{27}$
8. 所以 $Y$ 的分布列为：
9. $Y$
10. 3
11. 4
12. 5
13. 6
14. $P$
15. $\frac {1}{27}$
16. $\frac {2}{9}$
17. $\frac {4}{9}$
18. $\frac {8}{27}$
19. $E\left ({Y}\right )=3\times \frac {1}{27}+4\times \frac {2}{9}+5\times \frac {4}{9}+6\times \frac {8}{27}=5$ .
20. （2）①当 $m=1$ 时，即累计得分为 $1$ 分，是第一轮抢答得 $1$ 分， $P{{}_{1}}=\frac {1}{3}$ ，则 $P{{}_{1}}-P{{}_{0}}=\frac {1}{3}-1=-\frac {2}{3}$ ，
21. 累计得分为 $m$ 分的情况分两种：
22. ${\rm （i）}m=\left ({m-2}\right )+2$ ，即累计得分为 $m-2$ 分，又一轮抢答得 $2$ 分，其概率为 $\frac {2}{3}P{{}_{m-2}}$ .
23. ${\rm （ii）}m=\left ({m-1}\right )+1$ ，即累计得分为 $m-1$ 分，又一轮抢答得 $1$ 分，其概率为 $\frac {1}{3}P{{}_{m-1}}$ .
24. 则 $P{{}_{m}}=\frac {2}{3}P{{}_{m-2}}+\frac {1}{3}P{{}_{m-1}}\left ({m=2,3,\cdots ,19}\right )$ ，所以 $P{{}_{m}}-P{{}_{m-1}}=-\frac {2}{3}\left ({P{{}_{m-1}}-P{{}_{m-2}}}\right )$  $\left ({m=2,3,\cdots ,19}\right )$ .
25. 所以数列 $\left \{P{{}_{m}}-P{{}_{m-1}}\right \}\left ({m=1,2,3\cdots 19}\right )$ 是首项为 $-\frac {2}{3}$ ，公比为 $-\frac {2}{3}$ 的等比数列.
26. 所以 $P{{}_{m}}-P{{}_{m-1}}=\left ({-\frac {2}{3}}\right ){\left({-\frac {2}{3}}\right)^{m-1}}={\left({-\frac {2}{3}}\right)^{m}}\left ({m=1,2,3,\cdots ,19}\right )$ .
27. ②由①得 $P{{}_{1}}-P{{}_{0}}=-\frac {2}{3}$ ， $P{{}_{2}}-P{{}_{1}}={\left({-\frac {2}{3}}\right)^{2}}$ ， $\cdots $ ， $P{{}_{m}}-P{{}_{m-1}}={\left({-\frac {2}{3}}\right)^{m}}\left ({m=1,2,3,\cdots ,19}\right )$ ，
28. 各式累加得 $P{{}_{m}}-P{{}_{0}}=\left ({-\frac {2}{3}}\right )+{\left({-\frac {2}{3}}\right)^{2}}+\cdots +{\left({-\frac {2}{3}}\right)^{m}}=\frac {\left ({-\frac {2}{3}}\right )\left [1-{\left({-\frac {2}{3}}\right)^{m}}\right ]}{1-\left ({-\frac {2}{3}}\right )}=-\frac {2}{5}\left [1-{\left({-\frac {2}{3}}\right)^{m}}\right ]$ .
29. 而 $P{{}_{0}}=1$ ，所以 $P{{}_{m}}=1-\frac {2}{5}+\frac {2}{5}{\left({-\frac {2}{3}}\right)^{m}}=\frac {3}{5}+\frac {2}{5}{\left({-\frac {2}{3}}\right)^{m}}$ .
30. 所以获得冠军的概率为 $P{{}_{20}}=\frac {3}{5}+\frac {2}{5}{\left({-\frac {2}{3}}\right)^{20}}=\frac {3}{5}+\frac {2}{5}{\left({\frac {2}{3}}\right)^{20}}$ .
31. 所以获得亚军的概率为 $1-P{{}_{20}}=1-\left [\frac {3}{5}+\frac {2}{5}{\left({\frac {2}{3}}\right)^{20}}\right ]=\frac {2}{5}-\frac {2}{5}{\left({\frac {2}{3}}\right)^{20}}=\frac {2}{5}\left [1-{\left({\frac {2}{3}}\right)^{20}}\right ]$ .

## 知识点

**中文**:
  - 概率的性质
  - 离散型随机变量的分布列

**English**:
  - Properties of Probability
  - Probability Distribution Table

---
