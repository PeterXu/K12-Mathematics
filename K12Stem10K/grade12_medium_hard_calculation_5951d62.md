# Mathematics - 题目 36

**ID**: 5951d62a590d4451a6adc68b786d2153
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
某次比赛中，甲乙二人进入决赛并争夺冠军.​​​​​​​‌比赛规则为：①每局比赛后，胜者获得3分，负者获得1分，比赛没有平局；②连续2局获胜或积分率先达到11分者可获得冠军，比赛结束.已知在单局比赛中，甲乙获胜的概率均为 $\frac {1}{2}$ .(1)求甲乙决出冠军时比赛局数 $X$ 的分布列与数学期望 $E\left ({X}\right )$ ；(2)求在甲获得冠军的条件下其积分达到11分的概率 $P$ .

## 解答

1. （1）由比赛规则可知， $1$ 局比赛后，甲乙双方共获得 $4$ 分，若比赛进行了 $4$ 局还未结束，
2. 则双方共计 $16$ 分，此时双方均为 $8$ 分，则第 $5$ 局比赛后必定有一人积分可达到 $11$ 分，
3. 故比赛次数不会超过 $5$ ；
4. 由比赛规则可知，若比赛共进行了 $n$ 局， $\left ({2\leqslant n\leqslant 5}\right )$ ，
5. 则前 $n-1$ 局不可能出现某人连胜 $2$ 次（否则 $2$ 连胜后比赛结束），
6. 故前 $n-1$ 局必定甲乙二人胜负交替，
7. 综上可知：比赛决出冠军时，二人比赛过程中的胜负情况有以下三种可能：
8. 第一，比赛进行 $n$ 局 $\left ({2\leqslant n\leqslant 4}\right )$ ，前 $n-1$ 局二人胜负交替，第 $n$ 局与第 $n-1$ 局胜者相同，此人达成 $2$ 连胜并获得冠军（其积分不超过 $3\times 3+1=10$ ，故未达11分）；
9. 第二，比赛进行了 $5$ 局，二人始终胜负交替，其中第 $5$ 局获胜者获得 $11$ 分，另一方 $9$ 分，此时获胜者仅积分率先达到11分并获得冠军；
10. 第三，比赛进行了 $5$ 局，前 $4$ 局二人胜负交替，但第 $4$ 局的获胜者在第 $5$ 局连续获胜，则他同时完成 $2$ 连胜且积分率先达到11分并获得冠军.
11. 即随机事件 $A{{}_{i}}=$ “第 $i$ 局比赛中甲获胜” $i\in \left \{1,2,3,4,5\right \}$ ， $B=$ “甲达成 $2$ 连胜”， $C=$ “甲先获得 $11$ 积分”；
12. 根据题意， $X$ 的可能取值为 $2,3,4,5$ ，
13. $P\left ({X=2}\right )=P\left ({A{{}_{1}}A{{}_{2}}}\right )+P\left ({{\overline{A{{}_{1}}}}{\overline{A{{}_{2}}}}}\right )={\left({\frac {1}{2}}\right)^{2}}+{\left({\frac {1}{2}}\right)^{2}}=\frac {1}{2}$ ，
14. $P\left ({X=3}\right )=P\left ({{\overline{A{{}_{1}}}}A{{}_{2}}A{{}_{3}}}\right )+P\left ({A{{}_{1}}{\overline{A{{}_{2}}}}{\overline{A{{}_{3}}}}}\right )={\left({\frac {1}{2}}\right)^{3}}+{\left({\frac {1}{2}}\right)^{3}}=\frac {1}{4}$ ，
15. $P\left ({X=4}\right )=P\left ({A{{}_{1}}{\overline{A{{}_{2}}}}A{{}_{3}}A{{}_{4}}}\right )+P\left ({{\overline{A{{}_{1}}}}A{{}_{2}}{\overline{A{{}_{3}}}}{\overline{A{{}_{4}}}}}\right )={\left({\frac {1}{2}}\right)^{4}}+{\left({\frac {1}{2}}\right)^{4}}=\frac {1}{8}$ ，
16. $P\left ({X=5}\right )=1-P\left ({X=2}\right )-P\left ({X=3}\right )-P\left ({X=4}\right )=1-\frac {1}{2}-\frac {1}{4}-\frac {1}{8}=\frac {1}{8}$ .
17. 于是 $X$ 的分布列为：
18. $X$
19. $2$
20. $3$
21. $4$
22. $5$
23. $P$
24. $\frac {1}{2}$
25. $\frac {1}{4}$
26. $\frac {1}{8}$
27. $\frac {1}{8}$
28. 故 $E\left ({X}\right )=2\times \frac {1}{2}+3\times \frac {1}{4}+4\times \frac {1}{8}+5\times \frac {1}{8}=\frac {23}{8}$ ；
29. （2）根据以上分析可知： $P\left ({B\bar C}\right )=P\left ({A{{}_{1}}A{{}_{2}}}\right )+P\left ({{\overline{A{{}_{1}}}}A{{}_{2}}A{{}_{3}}}\right )+P\left ({A{{}_{1}}{\overline{A{{}_{2}}}}A{{}_{3}}A{{}_{4}}}\right )={\left({\frac {1}{2}}\right)^{2}}+{\left({\frac {1}{2}}\right)^{3}}+{\left({\frac {1}{2}}\right)^{4}}=\frac {7}{16}$ ，
30. $P\left ({\bar BC}\right )=P\left ({A{{}_{1}}{\overline{A{{}_{2}}}}A{{}_{3}}{\overline{A{{}_{4}}}}A{{}_{5}}}\right )={\left({\frac {1}{2}}\right)^{5}}=\frac {1}{32}$ ， $P\left ({BC}\right )=P\left ({{\overline{A{{}_{1}}}}A{{}_{2}}{\overline{A{{}_{3}}}}A{{}_{4}}A{{}_{5}}}\right )={\left({\frac {1}{2}}\right)^{5}}=\frac {1}{32}$ ，
31. 故 $P=P\left ({C|\left ({B\cup C}\right )}\right )=\frac {P\left ({C}\right )}{P\left ({B\cup C}\right )}=\frac {P\left ({\bar BC}\right )+P\left ({BC}\right )}{P\left ({B\bar C}\right )+P\left ({\bar BC}\right )+P\left ({BC}\right )}=\frac {\frac {1}{32}+\frac {1}{32}}{\frac {7}{16}+\frac {1}{32}+\frac {1}{32}}=\frac {1}{8}$ .

## 知识点

**中文**:
  - 条件概率
  - 离散型随机变量的分布列

**English**:
  - Conditional Probability
  - Probability Distribution Table

---
