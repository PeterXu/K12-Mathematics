# Mathematics - 题目 1874

**ID**: 8c37febe915645bfbc4aa23f2e6fd1a0
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
新冠抗疫期间，我们经历了太多悲恸，也收获了不少感动．某数学小组希望通过将所学的知识应用于我们的抗疫，决定以数学实验的方式探索新冠的传染和防控．过程如下：假设小盒中有 $8$ 个黑球， $2$ 个红球．模型①：若取出黑球，则放回小盒中，不作任何改变；若取出红球后，则放回小盒并往小盒里加入 $2$ 倍的红球．此模型可以解释为“传染模型”，即若发现一个新冠感染者，若不作任何处理，则会产生 $2$ 倍的新的感染者；模型②：若取出黑球，则放回小盒中，不作任何改变；若取出红球，则用黑球替换该红球重新放回小盒中，此模型可以解释为“安全模型”，即若发现一个新冠患者，则移出将其隔离进行诊治．（注：考虑样本容量足够大和治愈率的可能性，故用黑球代替红球）（1）分别计算在两种模型下，取出一次球后，第二次取到红球的概率；（2）在模型②的前提下：（i）记在第 $n\left ({n\geqslant 2}\right )$ 次时，刚好抽到第二个红球，试用 $n$ 表示刚好第 $n$ 次抽到第二个红球对应的概率；（ii）若规定无论第 $10$ 次是否能够抽到红球或第二个红球，当进行到第 $10$ 次时，即停止抽球；记抽到第二个红球时所需要的次数为 $X$ ，求 $X$ 的数学期望．（精确到个位）参考数据： $\sum \limits_{k=2}^{9}\mathop{\left ({{\left({\frac {9}{10}}\right)^{k}}-{\left({\frac {4}{5}}\right)^{k}}}\right )\approx 1.​​​​​​​‌95}$ ， $\sum \limits_{k=2}^{10}\mathop{\left ({{\left({\frac {9}{10}}\right)^{k}}-{\left({\frac {4}{5}}\right)^{k}}}\right )\approx 2.19}$ ， $\sum \limits_{k=2}^{9}\mathop{k\left ({{\left({\frac {9}{10}}\right)^{k-1}}-{\left({\frac {4}{5}}\right)^{k-1}}}\right )\approx 11.17}$ ， $\sum \limits_{k=2}^{10}\mathop{k\left ({{\left({\frac {9}{10}}\right)^{k-1}}-{\left({\frac {4}{5}}\right)^{k-1}}}\right )\approx 13.58}$ ．

## 解答

1. （1）记在模型①下，取到红球的概率为 $p{{}_{1}}$ ，则 $p{{}_{1}}=\frac {4}{5}\times \frac {1}{5}+\frac {1}{5}\times \frac {4}{12}=\frac {17}{75}$ ；
2. 记在模型②下，取到红球的概率为 $p{{}_{2}}$ ，则 $p{{}_{2}}=\frac {4}{5}\times \frac {1}{5}+\frac {1}{5}\times \frac {1}{10}=\frac {9}{50}$ ；
3. （2）（i）若第 $k$ 次是第一次取到红球，第 $n$ 次是第二次取到红球．
4. 则对应地有： $P={\left({\frac {4}{5}}\right)^{k-1}}\cdot \frac {1}{5}\cdot {\left({\frac {9}{10}}\right)^{n-k-1}}\cdot \frac {1}{10}$ ．
5. 则两次红球都被取出的所有可能情况的概率和为：
6. ${\left({\frac {4}{5}}\right)^{0}}\cdot \frac {1}{5}\cdot {\left({\frac {9}{10}}\right)^{n-2}}\cdot \frac {1}{10}+\frac {4}{5}\cdot \frac {1}{5}\cdot {\left({\frac {9}{10}}\right)^{n-3}}\cdot \frac {1}{10}+\cdots +{\left({\frac {4}{5}}\right)^{k-1}}\cdot \frac {1}{5}\cdot {\left({\frac {9}{10}}\right)^{n-k-1}}\cdot \frac {1}{10}+\cdots $  $+{\left({\frac {4}{5}}\right)^{n-2}}\cdot \frac {1}{5}\cdot {\left({\frac {9}{10}}\right)^{0}}\cdot \frac {1}{10}$
7. 利用等比数列求和公式即可得：
8. ${\left({\frac {4}{5}}\right)^{0}}\cdot \frac {1}{5}\cdot {\left({\frac {9}{10}}\right)^{n-2}}\cdot \frac {1}{10}\cdot \left [1+\frac {4}{5}\cdot \frac {10}{9}+{\left({\frac {4}{5}\cdot \frac {10}{9}}\right)^{2}}+\cdots +{\left({\frac {4}{5}\cdot \frac {10}{9}}\right)^{n-2}}\right ]$
9. $={\left({\frac {4}{5}}\right)^{0}}\cdot \frac {1}{5}\cdot {\left({\frac {9}{10}}\right)^{n-2}}\cdot \frac {1}{10}\cdot \frac {1-{\left({\frac {4}{5}\cdot \frac {10}{9}}\right)^{n-1}}}{1-\frac {4}{5}\cdot \frac {10}{9}}=\frac {1}{5}\cdot {\left({\frac {9}{10}}\right)^{n-1}}-\frac {1}{5}\cdot {\left({\frac {4}{5}}\right)^{n-1}}=\frac {1}{5}\left ({{\left({\frac {9}{10}}\right)^{n-1}}-{\left({\frac {4}{5}}\right)^{n-1}}}\right )$ ；
10. （ii）由题意可知， $X$ 的取值依次是 $2$ 、 $3$ 、 $\cdots $ 、 $9$ 、 $10$ ，
11. 特别地，当 $X=10$ 时，对应的 $P\left ({X=10}\right )=1-\left ({P\left ({X=2}\right )+P\left ({X=3}\right )+\cdots +P\left ({X=9}\right )}\right )$ ，
12. 由参考数据可得： $P\left ({X=10}\right )=1-\frac {1}{5}\times 1.95\approx 0.61$ ．
13. 对应的数学期望为： $E\left ({X}\right )=\frac {1}{5}\left ({2\cdot \frac {9}{10}+3\cdot {\left({\frac {9}{10}}\right)^{2}}+\cdots +9\cdot {\left({\frac {9}{10}}\right)^{n-1}}-\left ({2\cdot \frac {4}{5}+3\cdot {\left({\frac {4}{5}}\right)^{2}}+\cdots +9\cdot {\left({\frac {4}{5}}\right)^{n-1}}}\right )}\right )$
14. $+10\cdot 0.61$ ．
15. 由参考数据可得： $E\left ({X}\right )\approx \frac {1}{5}\cdot 11.17+10\cdot 0.61\approx 8$ ．
16. 本题考查条件概率（全概率公式）、数学期望、数据分析、数学运算、数学的应用性，数学源于生活应用于生活，社会热点，考查计算能力，属于难题.

## 知识点

**中文**:
  - 概率乘法公式
  - 概率的性质
  - 离散型随机变量的分布列

**English**:
  - Multiplication Rule of Probability
  - Properties of Probability
  - Probability Distribution Table

---
