# Mathematics - 题目 2136

**ID**: c2cbd11d63fa4cb49ec79c0f8a6ce342
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
某班地理老师为提高学生学习地理的积极性，举办地理答题得奖品活动，答题规则如下：两人为一组，每次一人答题，若答对则得奖品且继续答题，未答对则换对方答题．该班王海与吴昊为一组参加该活动，第1次答题人选通过掷硬币确定，正面为王海，反面为吴昊，已知王海每题答对的概率为 $\frac {2}{3}$ ，吴昊每题答对的概率为 $\frac {3}{4}$ ．（1）已知第2次答题人是吴昊，求第1次答题人为王海的概率；​​​​​​​‌（2）求第n次答题人是王海的概率 $p{{}_{n}}$ ；（3）定义 $np{{}_{n}}$ 是第n次答题人为王海的期望，求第n次答题人为王海的期望的前n项和 $T{{}_{n}}$ ．

## 解答

1. （1）设事件 $A$ ：第1次答题人为王海，事件 $B$ ：第2次答题人为吴昊，
2. ∴第1次答题人为吴昊为事件 ${\overline{A}}$ ，
3. 由题知， $P\left ({A}\right )=P\left ({\bar A}\right )=\frac {1}{2}$ ， $P\left ({B|A}\right )=\frac {1}{3}$ ， $P\left ({B|\bar A}\right )=\frac {3}{4}$ ，
4. 由全概率知， $P\left ({B}\right )=P\left ({B|A}\right )P\left ({A}\right )+P\left ({B|\bar A}\right )P\left ({\bar A}\right )=\frac {1}{3}\times \frac {1}{2}+\frac {3}{4}\times \frac {1}{2}=\frac {13}{24}$ ，
5. $\therefore P\left ({A|B}\right )=\frac {P\left ({AB}\right )}{P\left ({B}\right )}=\frac {P\left ({B|A}\right )P\left ({A}\right )}{P\left ({B}\right )}=\frac {\frac {1}{3}\times \frac {1}{2}}{\frac {13}{24}}=\frac {4}{13}$ ，
6. ∴已知第2次答题人是吴昊，则第1次答题人为王海的概率为 $\frac {4}{13}$ ．
7. （2）设事件 $A{{}_{n}}$ ：第 $n$ 次答题人是王海，事件 $B{{}_{n}}$ ：第 $n$ 次答题人是吴昊，
8. 由题知， $P\left ({A{{}_{n}}|B{{}_{n-1}}}\right )=1-\frac {3}{4}=\frac {1}{4}$ ， $P\left ({A{{}_{n}}|A{{}_{n-1}}}\right )=\frac {2}{3}$ ， $P\left ({B{{}_{n-1}}}\right )=P\left ({{\overline{A{{}_{n-1}}}}}\right )=1-p{{}_{n-1}}$ ， $p{{}_{1}}=\frac {1}{2}$ ，
9. 由全概率公式知， $p{{}_{n}}=P\left ({A{{}_{n}}}\right )=P\left ({A{{}_{n}}|B{{}_{n-1}}}\right )P\left ({B{{}_{n-1}}}\right )+P\left ({A{{}_{n}}|A{{}_{n-1}}}\right )P\left ({A{{}_{n-1}}}\right )=\frac {1}{4}\times \left ({1-p{{}_{n-1}}}\right )+\frac {2}{3}p{{}_{n-1}}$ ，
10. $\therefore p{{}_{n}}=\frac {5}{12}p{{}_{n-1}}+\frac {1}{4}$ ， $\therefore p{{}_{n}}-\frac {3}{7}=\frac {5}{12}\left ({p{{}_{n-1}}-\frac {3}{7}}\right )$ ，
11. $\because p{{}_{1}}-\frac {3}{7}=\frac {1}{2}-\frac {3}{7}=\frac {1}{14}\ne 0$ ，∴数列 $\left \{p{{}_{n}}-\frac {3}{7}\right \}$ 是首项为 $\frac {1}{14}$ ，公比为 $\frac {5}{12}$ 的等比数列，
12. $\therefore p{{}_{n}}-\frac {3}{7}=\frac {1}{14}\times {\left({\frac {5}{12}}\right)^{n-1}}$ ，则 $p{{}_{n}}=\frac {1}{14}\times {\left({\frac {5}{12}}\right)^{n-1}}+\frac {3}{7}$ ．
13. （3）由（2）知， $np{{}_{n}}=\frac {n}{14}{\left({\frac {5}{12}}\right)^{n-1}}+\frac {3n}{7}$ ，
14. 设数列 $\left \{\frac {n}{14}{\left({\frac {5}{12}}\right)^{n-1}}\right \}$ 的前 $n$ 项和为 $S{{}_{n}}$ ，
15. $\therefore S{{}_{n}}=\frac {1}{14}\times {\left({\frac {5}{12}}\right)^{0}}+\frac {2}{14}\times \left ({\frac {5}{12}}\right )+\frac {3}{14}\times {\left({\frac {5}{12}}\right)^{2}}+\cdots +\frac {n}{14}\times {\left({\frac {5}{12}}\right)^{n-1}}$ ，①
16. $\frac {5}{12}S{{}_{n}}=\frac {1}{14}\times \left ({\frac {5}{12}}\right )+\frac {2}{14}\times {\left({\frac {5}{12}}\right)^{2}}+\cdots +\frac {n-1}{14}\times {\left({\frac {5}{12}}\right)^{n-1}}+\frac {n}{14}\times {\left({\frac {5}{12}}\right)^{n}}$ ，②
17. $①-②$ 得 $\frac {7}{12}S{{}_{n}}=\frac {1}{14}+\frac {1}{14}\times \frac {5}{12}+\frac {1}{14}\times {\left({\frac {5}{12}}\right)^{2}}+\cdots +\frac {1}{14}\times {\left({\frac {5}{12}}\right)^{n-1}}-\frac {n}{14}\times {\left({\frac {5}{12}}\right)^{n}}$
18. $=\frac {\frac {1}{14}\left [1-{\left({\frac {5}{12}}\right)^{n}}\right ]}{1-\frac {5}{12}}-\frac {n}{14}\times {\left({\frac {5}{12}}\right)^{n}}=\frac {6}{49}-\frac {7n+12}{98}\times {\left({\frac {5}{12}}\right)^{n}}$ ，
19. $\therefore S{{}_{n}}=\frac {72}{343}-\frac {42n+72}{343}\times {\left({\frac {5}{12}}\right)^{n}}$ ，∵等差数列 $\left \{\frac {3n}{7}\right \}$ 的前 $n$ 项和为 $\frac {3n\left ({n+1}\right )}{14}$ ，
20. $\therefore T{{}_{n}}=\frac {72}{343}-\frac {42n+72}{343}\times {\left({\frac {5}{12}}\right)^{n}}+\frac {3n\left ({n+1}\right )}{14}$ ．

## 知识点

**中文**:
  - 全概率公式
  - 数列求和方法之错位相减法
  - 条件概率

**English**:
  - Law of Total Probability
  - Offset Subtraction Method
  - Conditional Probability

---
