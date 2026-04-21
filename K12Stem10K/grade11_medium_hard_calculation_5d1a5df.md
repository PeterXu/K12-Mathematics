# Mathematics - 题目 2876

**ID**: 5d1a5dfa302d41acbf9fcf90f45bd93d
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
甲、乙两人进行一场网球比赛，比赛采用三局两胜制，每局都没有平局，且甲第一局获胜的概率为 $p(0<p<1)$ .​​​​​​​‌从第二局开始，若上一局甲获胜，则下一局甲获胜的概率为 $p{^{2}}$ ，若上一局甲未获胜，则下一局甲获胜的概率为 $1-p$ .（1）当 $p=\frac {1}{2}$ 时，求甲第二局获胜的概率.（2）设甲第一局未获胜且第二局获胜的概率为 $\frac {1}{9}$ .①求 $p$ ；②记这场比赛需要进行的局数为 $X$ ，求 $X$ 的分布列与期望.

## 解答

1. （1）设 $A{{}_{i}}=$ “甲第 $i$ 局获胜”，其中 $i=1,2,3$ ，依题意得 $P\left ({A{{}_{1}}}\right )=p$ ，
2. 当 $p=\frac {1}{2}$ 时，由全概率公式得 $P\left ({A{{}_{2}}}\right )=P\left ({A{{}_{1}}A{{}_{2}}}\right )+P\left ({{\overline{A{{}_{1}}}}A{{}_{2}}}\right )=P\left ({A{{}_{1}}}\right )P\left ({A{{}_{2}}∣A{{}_{1}}}\right )+P\left ({{\overline{A{{}_{1}}}}}\right )$ . $P\left ({A{{}_{2}}∣{\overline{A{{}_{1}}}}}\right )$
3. $=p\cdot p{^{2}}+(1-p){^{2}}={\left({\frac {1}{2}}\right)^{3}}+{\left({1-\frac {1}{2}}\right)^{2}}=\frac {3}{8}$ ，
4. 所以甲第二局获胜的概率为 $\frac {3}{8}$ .
5. （2）①甲第一局未获胜且第二局获胜的概率为 $(1-p){^{2}}$ ，
6. 依题意得 $(1-p){^{2}}=\frac {1}{9}$ ，解得 $p=\frac {2}{3}$ .
7. ② $X$ 的可能取值为2，3.
8. $P\left ({X=2}\right )=P\left ({A{{}_{1}}A{{}_{2}}}\right )+P\left ({{\overline{A{{}_{1}}}}{\overline{A{{}_{2}}}}}\right )=p\cdot p{^{2}}+\left ({1-p}\right )p={\left({\frac {2}{3}}\right)^{3}}+\frac {1}{3}\times \frac {2}{3}=\frac {14}{27},$
9. $P\left ({X=3}\right )=P\left ({A{{}_{1}}{\overline{A{{}_{2}}}}A{{}_{3}}}\right )+P\left ({{\overline{A{{}_{1}}}}A{{}_{2}}A{{}_{3}}}\right )+P\left ({A{{}_{1}}{\overline{A{{}_{2}}}}{\overline{A{{}_{3}}}}}\right )+P\left ({{\overline{A{{}_{1}}}}A{{}_{2}}{\overline{A{{}_{3}}}}}\right )$
10. $=p\left ({1-p{^{2}}}\right )\left ({1-p}\right )+\left ({1-p}\right )\left ({1-p}\right )p{^{2}}+p\left ({1-p{^{2}}}\right )p+\left ({1-p}\right )\left ({1-p}\right )\left ({1-p{^{2}}}\right )=1-p{^{3}}+$
11. $p{^{2}}-p=1-{\left({\frac {2}{3}}\right)^{3}}+{\left({\frac {2}{3}}\right)^{2}}-\frac {2}{3}=\frac {13}{27}$ ，
12. 所以 $X$ 的分布列为
13. $X$
14. 2
15. 3
16. $P$
17. $\frac {14}{27}$
18. $\frac {13}{27}$
19. $E\left ({X}\right )=2\times \frac {14}{27}+3\times \frac {13}{27}=\frac {67}{27}$ .

## 知识点

**中文**:
  - 全概率公式
  - 离散型随机变量的分布列

**English**:
  - Law of Total Probability
  - Probability Distribution Table

---
