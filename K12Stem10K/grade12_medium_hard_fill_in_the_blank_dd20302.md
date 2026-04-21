# Mathematics - 题目 1813

**ID**: dd20302a906d4dffaaa8154a6df3df99
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Fill-in-the-blank

## 题目
箱子中装有4个红球，2个黄球（除颜色外完全相同），掷一枚质地均匀的骰子1次，如果点数为 $i\left ({i=1,2,3,4,5,6}\right )$ ，则从该箱子中一次性取出 $i$ 个球.​​​​​​​‌规定：依据 $i$ 个球中红球的个数，判定甲的得分 $X$ ，每一个红球记1分；依据 $i$ 个球中黄球的个数，判定乙的得分 $Y$ ，每一个黄球记2分.比如：若一次性取出了2个红球，2个黄球，则判定甲得分 $X=2$ ，乙得分 $Y=4$ .则在1次掷骰子取球的游戏中， $P\left ({X>Y}\right )=$.

## 解答

1. 设掷骰子得到的点数 $i$ 的概率为 $P\left ({i}\right )$ ，则 $P\left ({i}\right )=\frac {1}{6},i=1,2,\cdots ,6$ ，
2. 当 $i=1$ 时， $i=1$ 的概率为 $\frac {1}{6}$ ，若 $\mathrm{X}>\mathrm{Y}$ ，则需取出的1个球是红球的概率为 $P\left ({X>Y\left |{i=1}\right .}\right )=\frac {{\rm{C}}{{}_{4}^{1}}}{{\rm{C}}{{}_{6}^{1}}}=\frac {2}{3}$ ，
3. 所以 $P{{}_{1}}\left ({X>Y}\right )=P\left ({1}\right )P\left ({X>Y\left |{i=1}\right .}\right )=\frac {1}{6}\times \frac {2}{3}=\frac {1}{9}$ ，
4. 当 $i=2$ 时， $i=2$ 的概率为 $\frac {1}{6}$ ，若 $\mathrm{X}>\mathrm{Y}$ ，则需取出的2个球都是红球的概率为 $P\left ({X>Y\left |{i=2}\right .}\right )=\frac {{\rm{C}}{{}_{4}^{2}}}{{\rm{C}}{{}_{6}^{2}}}=\frac {2}{5}$ ，
5. 所以 $P{{}_{2}}\left ({X>Y}\right )=P\left ({2}\right )P\left ({X>Y\left |{i=2}\right .}\right )=\frac {1}{6}\times \frac {2}{5}=\frac {1}{15}$ ，
6. 当 $i=3$ 时， $i=3$ 的概率为 $\frac {1}{6}$ ，若 $\mathrm{X}>\mathrm{Y}$ ，则需取出的3个球都是红球的概率为
7. $P\left ({X>Y\left |{i=3}\right .}\right )=\frac {{\rm{C}}{{}_{4}^{3}}}{{\rm{C}}{{}_{6}^{3}}}=\frac {1}{5}$ ，所以 $P{{}_{3}}\left ({X>Y}\right )=P\left ({3}\right )P\left ({X>Y\left |{i=3}\right .}\right )=\frac {1}{6}\times \frac {1}{5}=\frac {1}{30}$ ，
8. 当 $i=4$ 时， $i=4$ 的概率为 $\frac {1}{6}$ ，若 $\mathrm{X}>\mathrm{Y}$ ，则有两种可能的情况：第一种情况为取出的4个球都是红球有 ${\rm{C}}{{}_{4}^{4}}$ 种，
9. 第二种情况为取出的4个球种有3个红球，1个黄球，有 ${\rm{C}}{{}_{4}^{3}}{\rm{C}}{{}_{2}^{1}}$ 种，所以概率为 $P\left ({X>Y\left |{i=4}\right .}\right )=\frac {{\rm{C}}{{}_{4}^{4}}+{\rm{C}}{{}_{4}^{3}}{\rm{C}}{{}_{2}^{1}}}{{\rm{C}}{{}_{6}^{4}}}=\frac {3}{5}$ ，
10. 所以 $P{{}_{4}}\left ({X>Y}\right )=P\left ({4}\right )P\left ({X>Y\left |{i=4}\right .}\right )=\frac {1}{6}\times \frac {3}{5}=\frac {1}{10}$
11. 当 $i=5$ 时， $i=5$ 的概率为 $\frac {1}{6}$ ，若 $\mathrm{X}>\mathrm{Y}$ ，则需取出全部4个红球，1个黄球，
12. 所以 $P\left ({X>Y\left |{i=5}\right .}\right )=\frac {{\rm{C}}{{}_{4}^{4}}{\rm{C}}{{}_{2}^{1}}}{{\rm{C}}{{}_{6}^{5}}}=\frac {1}{3}$ ，所以 $P{{}_{5}}\left ({X>Y}\right )=P\left ({5}\right )P\left ({X>Y\left |{i=5}\right .}\right )=\frac {1}{6}\times \frac {1}{3}=\frac {1}{18}$ ，
13. 当 $i=6$ 时， $X=Y$ 不满足题意，
14. 所以综上 $P\left ({X>Y}\right )=\frac {1}{9}+\frac {1}{15}+\frac {1}{30}+\frac {1}{10}+\frac {1}{18}=\frac {11}{30}$ .

## 知识点

**中文**:
  - 条件概率
  - 概率的性质

**English**:
  - Conditional Probability
  - Properties of Probability

---
