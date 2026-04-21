# Mathematics - 题目 2931

**ID**: 02eef14f375d480cad331b2f8cbd0ef1
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
一设随机变量 $X$ 所有可能的取值为 $x{{}_{1}}，x{{}_{2}}，\cdots ，x{{}_{n}}，P\left ({X=x{{}_{i}}}\right )=p{{}_{i}}>0\left ({i=1，2，\cdots ，n}\right )$ ，且 $p{{}_{1}}+p{{}_{2}}\cdots +p{{}_{n}}=1$ .​​​​​​​‌定义事件 $X=x{{}_{i}}$ 的信息量为 $H{{}_{i}}=-{\rm{l}}{\rm{n}}p{{}_{i}}$ ，称 $X$ 的平均信息量 $H\left ({X}\right )=-\left ({p{{}_{1}}{\rm{l}}{\rm{n}}p{{}_{1}}+p{{}_{2}}{\rm{l}}{\rm{n}}p{{}_{2}}+\cdots +p{{}_{n}}{\rm{l}}{\rm{n}}p{{}_{n}}}\right )$ 为信息熵.(1)若 $n=3，p{{}_{k+1}}=2p{{}_{k}}\left ({k=1，2}\right )$ ，求此时的信息熵;(2)最大熵原理:对一个随机事件的概率分布进行预测时，要使得信息熵最大.信息熵最大就是事物可能的状态数最多，复杂程度最大，概率分布最均匀，这才是风险最小（最合理）的决定.证明: $H\left ({X}\right )\leqslant {\rm{l}}{\rm{n}}n$ ，并解释等号成立时的实际意义.（参考不等式:若 $f\left ({x}\right )={\rm{l}}{\rm{n}}x$ ，则 $\sum\limits_{i=1}^{n}\mathop{}p{{}_{i}}f\left ({x{{}_{i}}}\right )\leqslant f\left ({\sum\limits_{i=1}^{n}\mathop{}p{{}_{i}}x{{}_{i}}}\right )$ ）

## 解答

1. （1）当 $n=3$ 时， $p{{}_{1}}+p{{}_{2}}+p{{}_{3}}=1$ ，且 $p{{}_{2}}=2p{{}_{1}},p{{}_{3}}=2p{{}_{2}}$ ，
2. ∴ $p{{}_{1}}=\frac {1}{7},p{{}_{2}}=\frac {2}{7},p{{}_{3}}=\frac {4}{7}$ ，
3. ∴ $H\left ({X}\right )=-\left ({p{{}_{1}}{\rm{l}}{\rm{n}}p{{}_{1}}+p{{}_{2}}{\rm{l}}{\rm{n}}p{{}_{2}}+p{{}_{3}}{\rm{l}}{\rm{n}}p{{}_{3}}}\right )=-\left ({\frac {1}{7}{\rm{l}}{\rm{n}}\frac {1}{7}+\frac {2}{7}{\rm{l}}{\rm{n}}\frac {2}{7}+\frac {4}{7}{\rm{l}}{\rm{n}}\frac {4}{7}}\right )=-\frac {1}{7}{\rm{l}}{\rm{n}}\frac {2{^{10}}}{7{^{7}}}={\ln}7-\frac {10}{7}{\rm{l}}{\rm{n}}{{2}}$
4. （2）令 $f\left ({x}\right )={\ln}x$ ，则 $p{{}_{i}}{\ln}p{{}_{i}}=p{{}_{i}}f\left ({p{{}_{i}}}\right )$ ，
5. ∴ $H\left ({X}\right )=-\left ({p{{}_{1}}{\rm{l}}{\rm{n}}p{{}_{1}}+p{{}_{2}}{\rm{l}}{\rm{n}}p{{}_{2}}+\cdots +p{{}_{n}}{\rm{l}}{\rm{n}}p{{}_{n}}}\right )=-\sum \limits_{i=1}^{n}\mathop{p{{}_{i}}f\left ({p{{}_{i}}}\right )}\leqslant -f\left ({\sum \limits_{i=0}^{n}\mathop{p{{}_{i}^{2}}}}\right )$
6. 有题意可知当 $p{{}_{i}}=\frac {1}{n}$ 时，风险最小（最合理）的决定，
7. ∴ $H\left ({X}\right )\leqslant -f\left ({\sum \limits_{i=0}^{n}\mathop{p{{}_{i}^{2}}}}\right )=-f\left ({n{\left({\frac {1}{n}}\right)^{2}}}\right )=-f\left ({\frac {1}{n}}\right )={\ln}n$
8. 当随机变量中每个变量发生的概率相同的时候，这时事物中每一个结果发生的可能性相同，情况分析是最复杂的，也是最合理的.

## 知识点

**中文**:
  - 概率的性质

**English**:
  - Properties of Probability

---
