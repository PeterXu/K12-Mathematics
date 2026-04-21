# Mathematics - 题目 928

**ID**: 2068f481e303443e8ed355c184b2e930
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
为了合理配置旅游资源，管理部门对首次来武汉旅游的游客进行了问卷调查，据统计，其中 $\frac {1}{3}$ 的人计划只参观黄鹤楼，另外 $\frac {2}{3}$ 的人计划既参观黄鹤楼又游览晴川阁，每位游客若只参观黄鹤楼，则记1分；​​​​​​​‌若既参观黄鹤楼又游览晴川阁，则记2分．假设每位首次来武汉旅游的游客计划是否游览晴川阁相互独立，视频率为概率．(1)从游客中随机抽取2人，记这2人的合计得分为X，求X的分布列和数学期望；(2)从游客中随机抽取n人 $\left ({n\in {\mathbf{N}}{^{*}}}\right )$ ，记这n人的合计得分恰为 $n+1$ 分的概率为 $P{{}_{n}}$ ，求 $\sum \limits_{i=1}^{n}\mathop{P{{}_{i}}}$ ；(3)从游客中随机抽取若干人逐个统计，记这些人的合计得分出现n分的概率为 $a{{}_{n}}$ ，求数列 $\left \{a{{}_{n}}\right \}$ 的通项公式．

## 解答

1. （1） $\frac {1}{3}$ 的人计划只参观黄鹤楼，另外 $\frac {2}{3}$ 的人计划既参观黄鹤楼又游览晴川阁，每位游客若只参观黄鹤楼记1分；既参观黄鹤楼又游览晴川阁记2分．每位首次来武汉旅游的游客计划是否游览晴川阁相互独立，视频率为概率，
2. 则随机变量  $X$  的可能取值为 2，3，4，
3. 可得  $P\left ({X=2}\right )={\left({\frac {1}{3}}\right)^{2}}=\frac {1}{9}$  ， $P\left ({X=3}\right )={\rm{C}}{{}_{2}^{1}}\times \frac {1}{3}\times \frac {2}{3}=\frac {4}{9},$  $P\left ({X=4}\right )={\left({\frac {2}{3}}\right)^{2}}=\frac {4}{9}.$
4. 所以 $X$ 的分布列如下表所示：
5. $X$
6. 2
7. 3
8. 4
9. $P$
10. $\frac {1}{9}$
11. $\frac {4}{9}$
12. $\frac {4}{9}$
13. 所以数学期望为  $E\left ({X}\right )=2\times \frac {1}{9}+3\times \frac {4}{9}+4\times \frac {4}{9}=\frac {10}{3}$  .
14. （2）由这  $n$  人的合计得分为  $n+1$  分，
15. 则其中只有1人计划既参观黄鹤楼又游览晴川阁，
16. 所以 $P{{}_{n}}={\rm{C}}{{}_{n}^{1}}\frac {2}{3}{\left({\frac {1}{3}}\right)^{n-1}}=\frac {2n}{3{^{n}}},\sum\limits_{i=1}^{n}\mathop{}P{{}_{i}}=\frac {2}{3}+\frac {2\times 2}{3{^{2}}}$  $+\frac {2\times 3}{3{^{3}}}+\cdot \cdot \cdot +\frac {2n}{3{^{n}}}$ ，
17. 则  $\frac {1}{3}\times \sum \limits_{i=1}^{n}\mathop{P{{}_{i}}}=\frac {2}{3{^{2}}}+\frac {2\times 2}{3{^{3}}}+\frac {2\times 3}{3{^{4}}}+\ldots +\frac {2n}{3{^{n+1}}}$  ，
18. 由两式相减， 可得 $\frac {2}{3}\times \sum \limits_{i=1}^{n}\mathop{P{{}_{i}}}=\frac {2}{3}+\frac {2}{3{^{2}}}+\frac {2}{3{^{3}}}+\ldots +\frac {2}{3{^{n}}}-\frac {2n}{3{^{n+1}}}=$  $\frac {2}{3}\times \frac {1-\frac {1}{3{^{n}}}}{1-\frac {1}{3}}-\frac {2n}{3{^{n+1}}}$ ，
19. 所以 $\sum\limits_{i=1}^{n}\mathop{}P{{}_{i}}=\frac {3}{2}\left ({1-\frac {1}{3{^{n}}}}\right )-\frac {n}{3{^{n}}}$  .
20. （3）在随机抽取的若干人的合计得分为  $n-1$  分的基础上再抽取1人，
21. 则这些人的合计得分可能为  $n$  分或  $n+1$  分，
22. 记“合计得  $n$  分”为事件  $A$  ，“合计得  $n+1$  分”为事件  $B$  ， $A$  与  $B$  是对立事件，
23. 因为 $P\left ({A}\right )=a{{}_{n}},P\left ({B}\right )=\frac {2}{3}a{{}_{n-1}}$  ，
24. 所以 $a{{}_{n}}+\frac {2}{3}a{{}_{n-1}}=1\left ({n\geqslant 2}\right )$  ，即 $a{{}_{n}}-\frac {3}{5}=-\frac {2}{3}\left ({a{{}_{n-1}}-\frac {3}{5}}\right )\left ({n\geqslant 2}\right ),$
25. 因为 $a{{}_{1}}=\frac {1}{3},a{{}_{1}}-\frac {3}{5}=\frac {1}{3}-\frac {3}{5}=-\frac {4}{15}$  ，则数列  $\left \{a{{}_{n}}-\frac {3}{5}\right \}$  是首项为  $-\frac {4}{15}$  ，公比为  $-\frac {2}{3}$  的等比数列，
26. 所以 $a{{}_{n}}-\frac {3}{5}=-\frac {4}{15}{\left({-\frac {2}{3}}\right)^{n-1}}$  ，
27. 所以 $a{{}_{n}}=-\frac {4}{15}{\left({-\frac {2}{3}}\right)^{n-1}}+\frac {3}{5}$ .

## 知识点

**中文**:
  - 对立事件
  - 数列求和方法之错位相减法
  - 离散型随机变量的分布列

**English**:
  - Complementary Events
  - Offset Subtraction Method
  - Probability Distribution Table

---
