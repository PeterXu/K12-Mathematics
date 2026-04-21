# Mathematics - 题目 2104

**ID**: 8f38214f80a047b1b1541ad7f1d0983f
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
进行独立重复试验，设每次成功的概率为 $p\left ({0<p<1}\right )$ ，将试验进行到首次成功时结束，以 $X$ 表示试验次数，则称 $X$ 服从以 $p$ 为参数的几何分布，记为 $X\sim Geo\left ({p}\right )$ ，其中 $E\left ({X}\right )=\frac {1}{p}$ ， $D\left ({X}\right )=\frac {1-p}{p{^{2}}}$ ．（1）若 $X\sim Geo\left ({\frac {1}{3}}\right )$ ，${\rm （i）}$ 求 $P\left ({X=4}\right )$ 和 $P\left ({X>6}\right )$ ；​​​​​​​‌${\rm （ii）}\sum\limits_{1=1}^{n}\mathop{}P\left ({X=i}\right )$ ；（2）若 $X\sim Geo\left ({p}\right )$ ， $\forall x$ ， $s\in {\rm{N}}{^{{\rm{*}}}}$ ，求证： $P\left ({X>x+sX|\rangle x}\right )=P\left ({X>s}\right )$ ．

## 解答

1. （1）（i）若 $X\sim Geo\left ({\frac {1}{3}}\right )$ ，
2. 则 $P\left ({X=4}\right )={\left({\frac {2}{3}}\right)^{3}}\times \frac {1}{3}=\frac {8}{81}$ ，
3. $P\left ({X>6}\right )={\left({\frac {2}{3}}\right)^{6}}=\frac {64}{729}$ ；
4. ${\rm （ii）}\sum\limits_{i=1}^{n}\mathop{}P\left ({X=i}\right )=P\left ({X=1}\right )+P\left ({X=2}\right )+P\left ({X=3}\right )+\cdots +P\left ({X=n}\right )$
5. $=\frac {1}{3}+\frac {2}{3}\times \frac {1}{3}+(\frac {2}{3}){^{2}}\times \frac {1}{3}+\cdots +(\frac {2}{3}){^{n-1}}\times \frac {1}{3}$
6. $=\frac {\frac {1}{3}[1-\left ({\frac {2}{3}){^{n}}}\right ]}{1-\frac {2}{3}}=1-(\frac {2}{3}){^{n}}$
7. （2）由题意可得 $P\left ({X>s}\right )={\left({1-p}\right)^{s}}$ ，
8. $P(X＞x+s|X＞x)=\frac {P\left ({X＞x+s}\right )}{P\left ({X＞x}\right )}$
9. $=\frac {(1-p){^{x+s}}}{(1-p){^{x}}}=(1-p){^{s}}$ ，
10. 所以 $P\left ({X>x+sX|\rangle x}\right )=P\left ({X>s}\right )$ ．

## 知识点

**中文**:
  - 条件概率

**English**:
  - Conditional Probability

---
