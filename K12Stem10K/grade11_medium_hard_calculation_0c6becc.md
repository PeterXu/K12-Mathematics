# Mathematics - 题目 1246

**ID**: 0c6becc6437f4051974d87bd1b76bb26
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知某篮球队有五名队员，其中甲是主要得分手，乙是组织后卫.​​​​​​​‌如果球在乙手中，则他传球给甲的概率为 $\frac {1}{2}$ ，传球给其他队员的概率均为 $\frac {1}{6}$ ；如果球不在乙手中，则这名队员传球给任何队友的概率都是 $\frac {1}{4}$ .开始进攻时，球在乙手中.（1）求经过2次传球并由甲执行投篮的条件下，球有经过丙之手的概率；（2）经过 $n$ 次传球后，球回到乙手中的概率；（3）记经过 $n$ 次传球后，球到甲的手中的概率为 $P{{}_{n}}$ ，求证：满足 $P{{}_{n}}>\frac {6}{25}$ 的 $n$ 的个数不少于满足 $P{{}_{n}}<\frac {6}{25}$ 的 $n$ 的个数.

## 解答

1. （1）记事件 $A=$ “经过2次传球并由甲执行投篮”， ${\rm{B}}=$ “球有经过丙之手”，则
2. $P\left ({B∣A}\right )=\frac {P\left ({AB}\right )}{P\left ({A}\right )}=\frac {\frac {1}{6}\times \frac {1}{4}}{\frac {1}{2}\times \frac {1}{4}}=\frac {1}{3}$ .
3. （2）记事件 $C{{}_{n}}=$ “ $n$ 传球后球回到乙手中”， $P\left ({C{{}_{n}}}\right )=a{{}_{n}}$ ，则 $a{{}_{1}}=0$ ，
4. $\because P\left ({C{{}_{n}}}\right )=P\left ({{\overline{C{{}_{n-1}}}}}\right )P\left ({C{{}_{n}}∣{\overline{C{{}_{n-1}}}}}\right ),\therefore a{{}_{n}}=\left ({1-a{{}_{n-1}}}\right )\cdot \frac {1}{4}$ ，
5. 即 $a{{}_{n}}-\frac {1}{5}=-\frac {1}{4}\left ({a{{}_{n-1}}-\frac {1}{5}}\right )$ ，
6. 所以数列 $\left \{a{{}_{n}}-\frac {1}{5}\right \}$ 是首项为 $-\frac {1}{5}$ ，公比为 $-\frac {1}{4}$ 的等比数列，
7. $\therefore a{{}_{n}}-\frac {1}{5}=-\frac {1}{5}{\left({-\frac {1}{4}}\right)^{n-1}}$ ，即 $a{{}_{n}}=\frac {1}{5}-\frac {1}{5}{\left({-\frac {1}{4}}\right)^{n-1}}$ .
8. （3）事件 $E{{}_{n}}=$ “ $n$ 传球后球到甲手中”，事件 $D{{}_{n}}=$ “ $n$ 传球后球不在甲和乙手中”
9. 则 $P\left ({E{{}_{n}}}\right )=P\left ({C{{}_{n-1}}}\right )P\left ({E{{}_{n}}∣C{{}_{n-1}}}\right )+P\left ({D{{}_{n-1}}}\right )P\left ({E{{}_{n}}∣D{{}_{n-1}}}\right )$ ，
10. $\therefore P{{}_{n}}=\frac {1}{2}a{{}_{n-1}}+\frac {1}{4}\left ({1-a{{}_{n-1}}-P{{}_{n-1}}}\right )$ ，
11. $\therefore P{{}_{n}}=-\frac {1}{4}P{{}_{n-1}}+\frac {1}{4}a{{}_{n-1}}+\frac {1}{4}=-\frac {1}{4}P{{}_{n-1}}+\frac {1}{20}{\left({-\frac {1}{4}}\right)^{n-2}}+\frac {3}{10}$ ，两边同时乘以 ${\left({-4}\right)^{n}}$ ，
12. $\therefore {\left({-4}\right)^{n}}P{{}_{n}}={\left({-4}\right)^{n-1}}P{{}_{n-1}}+\frac {3}{10}{\left({-4}\right)^{n}}+\frac {4}{5}$ ，
13. 设 $B{{}_{n}}={\left({-4}\right)^{n}}P{{}_{n}}$ ，则有 $B{{}_{n}}=B{{}_{n-1}}+\frac {3}{10}{\left({-4}\right)^{n}}+\frac {4}{5}$ ，而 $B{{}_{1}}=-4\cdot P{{}_{1}}=-2$ ，
14. 叠加得 $B{{}_{n}}=B{{}_{1}}+\frac {\frac {24}{5}\left [1-{\left({-4}\right)^{n-1}}\right ]}{5}+\frac {4}{5}\left ({n-1}\right )=-\frac {24}{25}{\left({-4}\right)^{n-1}}-\frac {20n+6}{25}$ ，
15. $\therefore P{{}_{n}}=\frac {6}{25}-\frac {20n+6}{25{\left({-4}\right)^{n}}}$     ，
16. 显然，当 $n$ 为奇数时， $P{{}_{n}}>\frac {6}{25}$ ，当 $n$ 为偶数时， $P{{}_{n}}<\frac {6}{25}$ ，
17. 因此 $P{{}_{n}}>\frac {6}{25}$ 的 $n$ 的个数不少于满足 $P{{}_{n}}<\frac {6}{25}$ 的 $n$ 的个数.
18. 解法二： $\therefore P{{}_{n}}=\frac {1}{2}a{{}_{n-1}}+\frac {1}{4}\left ({1-a{{}_{n-1}}-P{{}_{n-1}}}\right )=-\frac {1}{4}P{{}_{n-1}}-\frac {1}{20}{\left({-\frac {1}{4}}\right)^{n-2}}+\frac {3}{10}$ ，
19. 假设结论不成立，则至少有两个连续的自然数 $n$ ， $n-1$ ，使得 $P{{}_{n}}<\frac {6}{25}$ 且 $P{{}_{n-1}}<\frac {6}{25}$ .
20. 若 $n$ 为偶数，且 $P{{}_{n}}<\frac {6}{25}$ 则有：
21. $P{{}_{n+1}}=-\frac {1}{4}P{{}_{n}}-\frac {1}{20}{\left({-\frac {1}{4}}\right)^{n-1}}+\frac {3}{10}>-\frac {3}{50}+\frac {3}{10}-\frac {1}{20}{\left({-\frac {1}{4}}\right)^{n-1}}=\frac {6}{25}+\frac {1}{5}{\left({-\frac {1}{4}}\right)^{n}}>\frac {6}{25}$ ，
22. 若 $n$ 为奇数，且 $P{{}_{n}}>\frac {6}{25}$ ，则有
23. $P{{}_{n+1}}=-\frac {1}{4}P{{}_{n}}-\frac {1}{20}{\left({-\frac {1}{4}}\right)^{n-1}}+\frac {3}{10}<-\frac {3}{50}+\frac {3}{10}-\frac {1}{20}{\left({-\frac {1}{4}}\right)^{n-1}}=\frac {6}{25}+\frac {1}{5}{\left({-\frac {1}{4}}\right)^{n}}<\frac {6}{25}$ ，
24. $p{{}_{1}}=\frac {1}{2}>\frac {6}{25}$ ， $\therefore P{{}_{2}}<\frac {6}{25}$ .如此连续，
25. 故不存在连续的两个自然数 $n$ ， $n-1$ ，使得 $P{{}_{n}}<\frac {6}{25}$ 且 $P{{}_{n-1}}<\frac {6}{25}$ .

## 知识点

**中文**:
  - 条件概率
  - 等比数列的概念与通项公式
  - 等比数列的判定与证明

**English**:
  - Conditional Probability
  - Concept and Formula
  - Determination and Proof

---
