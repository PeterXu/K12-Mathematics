# Mathematics - 题目 3914

**ID**: 7899a9a0dd754c228e55a6cf1be05564
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
一种掷骰子走跳棋的游戏：如图，棋盘上有编号依次为0，1，2，3，…，20的格子，共21个.​​​​​​​‌一枚棋子开始在0号格子中，玩家每掷一次骰子（一种质地均匀的正方体形状玩具，六个面分别标有数字1，2，3，4，5，6），棋子向前跳动一次.若掷出的骰子子点数不小于3点，则跳1格（从 $i$ 号格子跳到 $i+1$ 号格子， $i\in {\mathbf{N}}$ ）；否则，跳2格（从 $i$ 号格子跳到 $i+2$ 号格子， $i\in {\mathbf{N}}$ ）.当棋子跳到19号格子或20号格子时，游戏结束.（1）棋子跳动3次后，记棋子所在格子编号为 $X$ ，求 $X$ 的分布列；（2）设棋子跳到编号为 $n$ 的格子的概率为 $p{{}_{n}}(n\in {\mathbf{N}})$ ，其中规定 $p{{}_{0}}=1$ .①求证： $\left \{p{{}_{n+1}}-p{{}_{n}}\right \}(0\leqslant n\leqslant 18,n\in {\mathbf{N}})$ 为等比数列；②游戏组织者规定：跳到19号格子，游戏失败，玩家付给组织者 $3a(a>0)$ 元；跳到20号格子，游戏胜利，组织者付给玩家8a元.问此种规则对游戏组织者是否有利？说明理由.01234……1920

## 解答

1. （1）棋子跳1格的概率为 $\frac {4}{6}=\frac {2}{3}$ ，则跳2格的概率为 $1-\frac {2}{3}=\frac {1}{3}$ ，
2. 棋子跳动3次后， $X$ 的可能取值为： $3$ 、 $4$ 、 $5$ 、 $6$ ，
3. $P\left ({X=3}\right )={\left({\frac {2}{3}}\right)^{3}}=\frac {8}{27}$ ， $P\left ({X=4}\right )={\rm{C}}{{}_{3}^{1}}{\left({\frac {2}{3}}\right)^{2}}\cdot \frac {1}{3}=\frac {4}{9}$ ，
4. $P\left ({X=5}\right )={\rm{C}}{{}_{3}^{2}}\cdot \frac {2}{3}\cdot {\left({\frac {1}{3}}\right)^{2}}=\frac {2}{9}$ ， $P\left ({X=6}\right )={\left({\frac {1}{3}}\right)^{3}}=\frac {1}{27}$ ，
5. 则其分布列为：
6. $X$
7. $3$
8. $4$
9. $5$
10. $6$
11. $P$
12. $\frac {8}{27}$
13. $\frac {4}{9}$
14. $\frac {2}{9}$
15. $\frac {1}{27}$
16. （2）①由题意可得 $p{{}_{n+2}}=\frac {2}{3}p{{}_{n+1}}+\frac {1}{3}p{{}_{n}}\left ({0\leqslant n\leqslant 17,n\in {\mathbf{N}}}\right )$ ，
17. 即 $p{{}_{n+2}}-p{{}_{n+1}}=-\frac {1}{3}\left ({p{{}_{n+1}}-p{{}_{n}}}\right )$ ，又 $p{{}_{0}}=1$ ， $p{{}_{1}}=\frac {2}{3}$ ，则 $p{{}_{1}}-p{{}_{0}}=-\frac {1}{3}$ ，
18. 故数列 $\left \{p{{}_{n+1}}-p{{}_{n}}\right \}(0\leqslant n\leqslant 18,n\in {\mathbf{N}})$ 是等比数列；
19. ②由①可得当 $0\leqslant n\leqslant 18$ 时，有 $p{{}_{n+1}}-p{{}_{n}}=-\frac {1}{3}\cdot {\left({-\frac {1}{3}}\right)^{n}}={\left({-\frac {1}{3}}\right)^{n+1}}$ ，
20. 则 $p{{}_{n}}-p{{}_{n-1}}={\left({-\frac {1}{3}}\right)^{n}}$ 、 $p{{}_{n-1}}-p{{}_{n-2}}={\left({-\frac {1}{3}}\right)^{n-1}}$ 、 $\cdots $ 、 $p{{}_{1}}-p{{}_{0}}=-\frac {1}{3}$ ，
21. 累加有 $p{{}_{n}}-p{{}_{0}}=\frac {-\frac {1}{3}\left [1-{\left({-\frac {1}{3}}\right)^{n}}\right ]}{1-\left ({-\frac {1}{3}}\right )}=\frac {1}{4}\cdot {\left({-\frac {1}{3}}\right)^{n}}-\frac {1}{4}$ ，
22. 即 $p{{}_{n}}=\frac {1}{4}\cdot {\left({-\frac {1}{3}}\right)^{n}}-\frac {1}{4}+1=\frac {3}{4}+\frac {1}{4}\cdot {\left({-\frac {1}{3}}\right)^{n}}$ ，
23. 故 $p{{}_{19}}=\frac {3}{4}+\frac {1}{4}\cdot {\left({-\frac {1}{3}}\right)^{19}}$ ， $p{{}_{20}}=1-p{{}_{19}}$ ，
24. 有 $3a\cdot p{{}_{19}}-8a\cdot p{{}_{20}}=3a\cdot p{{}_{19}}-8a\cdot \left ({1-p{{}_{19}}}\right )=a\left ({11p{{}_{19}}-8}\right )$
25. $=a\left [\frac {33}{4}+\frac {11}{4}\cdot {\left({-\frac {1}{3}}\right)^{19}}-8\right ]=\frac {a}{4}\left [1+11\cdot {\left({-\frac {1}{3}}\right)^{19}}\right ]>0$ ，
26. 故此种规则对游戏组织者有利.

## 知识点

**中文**:
  - 数列通项求法之累加法
  - 等比数列的判定与证明
  - 离散型随机变量的分布列

**English**:
  - Accumulation Method (Telescoping Sums)
  - Determination and Proof
  - Probability Distribution Table

---
