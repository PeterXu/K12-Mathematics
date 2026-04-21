# Mathematics - 题目 344

**ID**: 6f61fd3b82334ffda8f1d76859c2b15c
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
某学校举行知识竞赛，第一轮选拔共设有A，B，C，D四个问题，规则如下：①每位参加者计分器的初始分均为10分，答对问题A，B，C，D分别加1分，2分，3分，6分，答错任一题减2分；​​​​​​​‌②每回答一题，计分器显示累计分数，当累计分数小于8分时，答题结束，淘汰出局；当累计分数大于或等于14分时，答题结束，进入下一轮；当答完四题，累计分数仍不足14分时，答题结束，淘汰出局，当累计分数大于或等于14分时，答题结束，进入下一轮；③每位参加者按问题A，B，C，D顺序作答，直至答题结束．假设甲同学对问题A，B，C，D回答正确的概率依次为 $\frac {3}{4}$ ， $\frac {1}{2}$ ， $\frac {1}{3}$ ， $\frac {1}{4}$ ，且各题回答正确与否相互之间没有影响．（1）求甲同学能进入下一轮的概率；（2）用 ${\rm \mathit{ξ}}$ 表示甲同学本轮答题结束时答题的个数，求 ${\rm \mathit{ξ}}$ 的分布列和数学期望E(ξ)．

## 解答

1. 设A，B，C，D分别为第一，二，三，四个问题．用Mi(i＝1，2，3，4)表示甲同学第i个问题回答正确，用Ni(i＝1，2，3，4)表示甲同学第i个问题回答错误，则Mi与Ni是对立事件 ${\rm (\mathit{i}＝1，2，3，4)}$ ．由题意得， ${\rm \mathit{P}(\mathit{M}\mathit{_{1}})＝}\frac {3}{4}{\rm ，\mathit{P}(\mathit{M}\mathit{_{2}})＝}$  $\frac {1}{2}{\rm ，\mathit{P}(\mathit{M}\mathit{_{3}})＝}$  $\frac {1}{3}{\rm ，\mathit{P}(\mathit{M}\mathit{_{4}})＝}$  $\frac {1}{4}$ ，
2. 所以 ${\rm \mathit{P}(\mathit{N}\mathit{_{1}})＝}\frac {1}{4}{\rm ，\mathit{P}(\mathit{N}\mathit{_{2}})＝}$  $\frac {1}{2}{\rm ，\mathit{P}(\mathit{N}\mathit{_{3}})＝}$  $\frac {2}{3}{\rm ，\mathit{P}(\mathit{N}\mathit{_{4}})＝}$  $\frac {3}{4}$ .
3. （1）记“甲同学能进入下一轮”为事件Q，
4. Q＝M_{1}M_{2}M_{3}＋N_{1}M_{2}M_{3}M_{4}＋M_{1}N_{2}M_{3}M_{4}＋M_{1}M_{2}N_{3}M_{4}＋N_{1}M_{2}N_{3}M_{4}，
5. P(Q)＝P(M_{1}M_{2}M_{3}＋N_{1}M_{2}M_{3}M_{4}＋M_{1}N_{2}M_{3}M_{4}＋M_{1}M_{2}N_{3}M_{4}＋N_{1}M_{2}N_{3}M_{4})
6. ${\rm ＝\mathit{P}(\mathit{M}\mathit{_{1}}\mathit{M}\mathit{_{2}}\mathit{M}\mathit{_{3}})＋\mathit{P}(\mathit{N}\mathit{_{1}}\mathit{M}\mathit{_{2}}\mathit{M}\mathit{_{3}}\mathit{M}\mathit{_{4}})＋\mathit{P}(\mathit{M}\mathit{_{1}}\mathit{N}\mathit{_{2}}\mathit{M}\mathit{_{3}}\mathit{M}\mathit{_{4}})＋\mathit{P}(\mathit{M}\mathit{_{1}}\mathit{M}\mathit{_{2}}\mathit{N}\mathit{_{3}}\mathit{M}\mathit{_{4}})＋\mathit{P}(\mathit{N}\mathit{_{1}}\mathit{M}\mathit{_{2}}\mathit{N}\mathit{_{3}}\mathit{M}\mathit{_{4}})}$
7. ${\rm ＝}\frac {3}{4}{\rm ×}$  $\frac {1}{2}{\rm ×}$  $\frac {1}{3}{\rm ＋}$  $\frac {1}{4}{\rm ×}$  $\frac {1}{2}{\rm ×}$  $\frac {1}{3}{\rm ×}$  $\frac {1}{4}{\rm ＋}$  $\frac {3}{4}{\rm ×}$  $\frac {1}{2}{\rm ×}$  $\frac {1}{3}{\rm ×}$  $\frac {1}{4}{\rm ＋}$  $\frac {3}{4}{\rm ×}$  $\frac {1}{2}{\rm ×}$  $\frac {2}{3}{\rm ×}$  $\frac {1}{4}{\rm ＋}$  $\frac {1}{4}{\rm ×}$  $\frac {1}{2}{\rm ×}$  $\frac {2}{3}{\rm ×}$  $\frac {1}{4}{\rm ＝}$  $\frac {1}{4}$ .
8. （2）由题意，随机变量 ${\rm \mathit{ξ}}$ 的可能取值为2，3，4.由于每题答题结果相互独立，
9. 所以 ${\rm \mathit{P}(\mathit{ξ}＝2)＝}\frac {1}{8}$ ，
10. ${\rm \mathit{P}(\mathit{ξ}＝3)＝}\frac {3}{4}{\rm ×}$  $\frac {1}{2}{\rm ×}$  $\frac {1}{3}{\rm ＋}$  $\frac {3}{4}{\rm ×}$  $\frac {1}{2}{\rm ×}$  $\frac {2}{3}{\rm ＝}$  $\frac {3}{8}$ ，
11. ${\rm \mathit{P}(\mathit{ξ}＝4)＝1－\mathit{P}(\mathit{ξ}＝1)－\mathit{P}(\mathit{ξ}＝2)＝}\frac {1}{2}$ .
12. 随机变量 ${\rm \mathit{ξ}}$ 的分布列为
13. ${\rm \mathit{ξ}}$
14. 2
15. 3
16. 4
17. P
18. $\frac {1}{8}$
19. $\frac {3}{8}$
20. $\frac {1}{2}$
21. 所以 ${\rm \mathit{E}(\mathit{ξ})＝2×}\frac {1}{8}{\rm ＋3×}$  $\frac {3}{8}{\rm ＋4×}$  $\frac {1}{2}{\rm ＝}$  $\frac {27}{8}$ .
22. 【命题意图】本题考查了相互独立事件同时发生的概率、考查了离散型随机变量的分布列以及数学期望的知识，考查了同学们利用所学知识解决实际问题的能力．

## 知识点

**中文**:
  - 概率乘法公式
  - 离散型随机变量的分布列

**English**:
  - Multiplication Rule of Probability
  - Probability Distribution Table

---
