# Mathematics - 题目 3325

**ID**: 17f34f46bfbc4959ad68076bbe4620df
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
Matlab是一种数学软件，用于数据分析、无线通信、深度学习、图象处理与计算机视觉、信号处理、量化金融与风险管理、人工智能机器人和控制系统等领域，推动了人类基础教育和基础科学的发展.​​​​​​​‌某学校举行了相关Matlab专业知识考试，试卷中只有两道题目，已知甲同学答对每题的概率都为p，乙同学答对每题的概率都为 $q\left ({p>q}\right )$ ，且在考试中每人各题答题结果互不影响．已知每题甲、乙同时答对的概率为 $\frac {1}{2}$ ，恰有一人答对的概率为 $\frac {5}{12}$ ．(1)求 $p$ 和 $q$ 的值；(2)试求两人共答对3道题的概率．

## 解答

1. （1）由题意可得 $\begin{cases}pq=\frac {1}{2},\\p(1-q)+q(1-p)=\frac {5}{12},\end{cases}$
2. 即 $\begin{cases}pq=\frac {1}{2},\\p+q=\frac {17}{12}.\end{cases}$ 解得 $\begin{cases}p=\frac {3}{4},\\q=\frac {2}{3},\end{cases}$ 或 $\begin{cases}p=\frac {2}{3},\\q=\frac {3}{4}.\end{cases}$
3. 由于 $p>q$ ，所以 $p=\frac {3}{4},q=\frac {2}{3}$ ．
4. （2）设 $A{{}_{i}}=\{$ 甲同学答对了i道题 $\},B{{}_{i}}=\{$ 乙同学答对了i道题 $\},i=0,1,2$ ．
5. 由题意得， $P\left ({A{{}_{1}}}\right )=\frac {1}{4}\times \frac {3}{4}+\frac {3}{4}\times \frac {1}{4}=\frac {3}{8},P\left ({A{{}_{2}}}\right )=\frac {3}{4}\times \frac {3}{4}=\frac {9}{16}$ ， $P\left ({B{{}_{1}}}\right )=\frac {2}{3}\times \frac {1}{3}+\frac {1}{3}\times \frac {2}{3}=\frac {4}{9},P\left ({B{{}_{2}}}\right )=\frac {2}{3}\times \frac {2}{3}=\frac {4}{9}$ ．
6. 设 $E=\{$ 甲、乙二人共答对3道题 $\}$ ，则 $E=A{{}_{1}}B{{}_{2}}+A{{}_{2}}B{{}_{1}}$ ．
7. 由于 $A{{}_{i}}$ 和 $B{{}_{i}}$ 相互独立， $A{{}_{1}}B{{}_{2}}$ 与 $A{{}_{2}}B{{}_{1}}$ 互斥，
8. 所以 $P(E)=P\left ({A{{}_{1}}B{{}_{2}}}\right )+P\left ({A{{}_{2}}B{{}_{1}}}\right )=P\left ({A{{}_{1}}}\right )P\left ({B{{}_{2}}}\right )+P\left ({A{{}_{2}}}\right )P\left ({B{{}_{1}}}\right )=\frac {3}{8}\times \frac {4}{9}+\frac {9}{16}\times \frac {4}{9}=\frac {5}{12}.$
9. 所以甲、乙两人共答对3道题的概率为 $\frac {5}{12}$ .

## 知识点

**中文**:
  - 事件的相互独立性

**English**:
  - Independence of Events

---
