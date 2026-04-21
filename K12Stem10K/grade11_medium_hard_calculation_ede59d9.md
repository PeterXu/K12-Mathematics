# Mathematics - 题目 397

**ID**: ede59d9986564f988281e901ba83439b
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
一只不透明的口袋中放有形状、大小完全相同的4个黑球和2个白球，若每次摸一个球后，观察其颜色，再放回袋中，摸到黑球得1分，摸到白球得 $-1$ 分，用随机变量 $η$ 表示k次摸球后得1分的总次数，用随机变量X表示k次摸球后总得分.​​​​​​​‌(1)若摸球100次.①求 $η$ 的数学期望；②求X的数学期望；(2)当摸球次数k为何值时， $X=4$ 的概率取得最大值.

## 解答

1. （1）①由题意可知：每次摸到黑球的概率均为 $p=\frac {4}{6}=\frac {2}{3}$ ，
2. 即得1分的概率均为 $p=\frac {2}{3}$ ，则 $η\sim B\left ({100,\frac {2}{3}}\right )$ ，
3. 所以 $η$ 的数学期望 $E\left ({η}\right )=\frac {2}{3}\times 100=\frac {200}{3}$ ；
4. ②因为 $X=η-\left ({100-η}\right )=2η-100$ ，
5. 所以X的数学期望 $E\left ({X}\right )=E\left ({2η-100}\right )=2E\left ({η}\right )-100=\frac {100}{3}$ ；
6. （2）设摸到白球的次数为 $m\in {\mathbf{N}}$ ，则摸到黑球的次数为 $m+4$ ，则 $k=2m+4$ ，
7. 则 $P\left ({X=4}\right )=P\left ({η=m+4}\right )={\rm{C}}{{}_{2m+4}^{m+4}}{\left({\frac {2}{3}}\right)^{m+4}}{\left({1-\frac {2}{3}}\right)^{m}}={\rm{C}}{{}_{2m+4}^{m+4}}{\left({\frac {2}{3}}\right)^{m+4}}{\left({\frac {1}{3}}\right)^{m}}$ ，
8. 由题意可得： $\begin{cases}{\rm{C}}{{}_{2m+6}^{m+5}}{\left({\frac {2}{3}}\right)^{m+5}}{\left({\frac {1}{3}}\right)^{m+1}}\leqslant {\rm{C}}{{}_{2m+4}^{m+4}}{\left({\frac {2}{3}}\right)^{m+4}}{\left({\frac {1}{3}}\right)^{m}}\\{\rm{C}}{{}_{2m+2}^{m+3}}{\left({\frac {2}{3}}\right)^{m+3}}{\left({\frac {1}{3}}\right)^{m-1}}\leqslant {\rm{C}}{{}_{2m+4}^{m+4}}{\left({\frac {2}{3}}\right)^{m+4}}{\left({\frac {1}{3}}\right)^{m}}\end{cases}$ ，
9. 解得 $2\sqrt {10}-5\leqslant m\leqslant 2\sqrt {10}-4$ ，且 $m\in {\mathbf{N}}{^{{\rm{*}}}}$ ，可得 $m=2$ ，
10. 所以当摸球次数 $k=2m+4=8$ 时， $X=4$ 的概率取得最大值.

## 知识点

**中文**:
  - 二项分布

**English**:
  - Binomial Distribution

---
