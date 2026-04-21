# Mathematics - 题目 2028

**ID**: 9fba452519f04330aa423209264bdbed
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
某校园格局呈现四排八栋分布，学生从高一入学到高三毕业需踏着层层台阶登攀，这其中寓意着学校对学生的期盼与激励．现假设台阶标有第0，1，2，…，50级，有一位同学抛掷一枚均匀质地的骰子进行登攀台阶游戏，这位同学开始时位于第0级，若掷出偶数点，则向上一步登一级台阶，若掷出奇数点，则向上一步登两级台阶，直到登上第49级（成功）或第50级（失败），游戏结束．设 $X(n)$ 为登攀至第n级的步数 $(1\leqslant n\leqslant 50)$ ，这位同学登到第n级的概率为 $P{{}_{n}}$ ．（I）求 $X(3)$ 的分布列与数学期望；​​​​​​​‌（Ⅱ）证明： $\left \{P{{}_{n}}-P{{}_{n-1}}\right \}(2\leqslant n\leqslant 49)$ 为等比数列．

## 解答

1. （Ⅰ）由定义知， $X(3)$ 可能取值为2，3．
2. 根据条件概率计算公式得： $P(X(3)=2)=\frac {{\rm C}{_{2}^{1}}{\left({\frac {1}{2}}\right)^{1}}{\left({\frac {1}{2}}\right)^{1}}}{{\rm C}{_{2}^{1}}{\left({\frac {1}{2}}\right)^{1}}{\left({\frac {1}{2}}\right)^{1}}+{\left({\frac {1}{2}}\right)^{3}}}=\frac {\frac {1}{2}}{\frac {5}{8}}=\frac {4}{5}$ ， $P(X(3)=3)=\frac {{\left({\frac {1}{2}}\right)^{3}}}{{\rm C}{_{2}^{1}}{\left({\frac {1}{2}}\right)^{1}}{\left({\frac {1}{2}}\right)^{1}}+{\left({\frac {1}{2}}\right)^{3}}}=\frac {\frac {1}{8}}{\frac {5}{8}}=\frac {1}{5}$ ．
3. $\therefore X(3)$ 的分布列为
4. $X(3)$
5. $2$
6. $3$
7. $P$
8. $\frac {4}{5}$
9. $\frac {1}{5}$
10. ∴ $E(X(3))=2\times \frac {4}{5}+3\times \frac {1}{5}=\frac {11}{5}$ ．
11. （Ⅱ）证明：由题意， $P{{}_{n}}=\frac {1}{2}\left ({P{{}_{n-1}}+P{{}_{n-2}}}\right )$ ，则 $P{{}_{n}}-P{{}_{n-1}}=-\frac {1}{2}\left ({P{{}_{n-1}}-P{{}_{n-2}}}\right )(2\leqslant n\leqslant 49)$ ；
12. 又 $P{{}_{1}}-P{{}_{0}}{\rm{=}}\frac {1}{2}-1=-\frac {1}{2}$ ，
13. ∴数列 $\left \{P{{}_{n}}-P{{}_{n-1}}\right \}(1\leqslant n\leqslant 49)$ 是首项、公比均为 $-\frac {1}{2}$ 的等比数列．

## 知识点

**中文**:
  - 离散型随机变量的分布列
  - 等比数列的判定与证明

**English**:
  - Probability Distribution Table
  - Determination and Proof

---
