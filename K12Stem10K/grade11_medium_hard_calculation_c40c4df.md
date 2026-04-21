# Mathematics - 题目 1385

**ID**: c40c4dfab0354e438be21e97cafaee20
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
$n$ 个有次序的实数 $a{{}_{1}}$ ， $a{{}_{2}}$ ，…， $a{{}_{n}}$ 所组成的有序数组 $\left ({a{{}_{1}},a{{}_{2}},\cdots ,a{{}_{n}}}\right )$ 称为一个 $n$ 维向量，其中 $a{{}_{i}}\left ({i=1,2,\mathrm{⋯},n}\right )$ 称为该向量的第 $i$ 个分量.​​​​​​​‌特别地，对一个 $n$ 维向量 $\overrightarrow a=\left ({a{{}_{1}},a{{}_{2}}\ldots ,a{{}_{n}}}\right )$ ，若 $\left |{a{{}_{i}}}\right |=1$ ， $i=1,2\cdots ,n$ ，称 $\overrightarrow a$ 为 $n$ 维信号向量.设 $\overrightarrow a=\left ({a{{}_{1}},a{{}_{2}}\ldots ,a{{}_{n}}}\right )\overrightarrow b=\left ({b{{}_{1}},b{{}_{2}}\ldots ,b{{}_{n}}}\right )$ ，则 $\overrightarrow a$ 和 $\overrightarrow b$ 的内积定义为 $\overrightarrow a\cdot \overrightarrow {{b}}=\sum \limits_{i=1}^{n}\mathop{a{{}_{i}}b{{}_{i}}}$ ，且 $\overrightarrow a\bot \overrightarrow {{b}}\Leftrightarrow \overrightarrow a\cdot \overrightarrow {{b}}=0$ .(1)写出所有3维信号向量；(2)直接写出4个两两垂直的4维信号向量；(3)证明：不存在14个两两垂直的14维信号向量；

## 解答

1. （1）所有3维信号向量如下：
2. $\left ({1,1,1}\right ),\left ({1,1,-1}\right ),\left ({1,-1,1}\right ),\left ({-1,1,1}\right ),\left ({1,-1,-1}\right ),\left ({-1,1,-1}\right ),\left ({-1,-1,1}\right ),\left ({-1,-1,-1}\right )$ .
3. （2）设4维信号向量为 $\overrightarrow a=\left ({a{{}_{1}},a{{}_{2}},a{{}_{3}},a{{}_{4}}}\right ),\overrightarrow b=\left ({b{{}_{1}},b{{}_{2}},b{{}_{3}},b{{}_{4}}}\right )$ ， $\left |{a{{}_{i}}}\right |=1,\left |{b{{}_{i}}}\right |=1$ ， $i=1,2\cdot \cdot \cdot ,n$ ，
4. 可知 $\left |{a{{}_{i}}b{{}_{i}}}\right |=1$ ，
5. 若 $\overrightarrow {{a}}\bot \overrightarrow {{b}}$ ，等价于 $\overrightarrow {{a}}\cdot \overrightarrow {{b}}=a{{}_{1}}b{{}_{1}}+a{{}_{2}}b{{}_{2}}+a{{}_{3}}b{{}_{3}}+a{{}_{4}}b{{}_{4}}=0$ ，
6. 可知 $a{{}_{i}}b{{}_{i}}$ 中有2个1，2个 $-1$ ，
7. 代入可知, $\left ({1,1,1,1}\right ),\left ({-1,-1,1,1}\right ),\left ({-1,1,-1,1}\right ),\left ({-1,1,1,-1}\right )$ 符合上式，
8. 两两垂直的4维信号向量可以为 $\left ({1,1,1,1}\right )$ ， $\left ({-1,-1,1,1}\right )$ ， $\left ({-1,1,-1,1}\right )$ ， $\left ({-1,1,1,-1}\right )$ .
9. （3）假设存在14个两两垂直的14维信号向量 $\overrightarrow {{y{{}_{1}}}},\overrightarrow {{y{{}_{2}}}},\cdot \cdot \cdot ,\overrightarrow {{y{{}_{14}}}}$ ，
10. 因为将这14个向量的某个分量同时变号或将某两个位置的分量同时互换位置，任意两个向量的内积不变，
11. 所以不妨设 $\overrightarrow {{y{{}_{1}}}}=\left ({1,1,\cdot \cdot \cdot ,1}\right ),\overrightarrow {{y{{}_{2}}}}=\left ({1,1,1,1,1,1,1,-1,-1,-1,-1,-1,-1,-1}\right )$ ，
12. 因为 $\overrightarrow {{y{{}_{1}}}}\cdot \overrightarrow {{y{{}_{3}}}}=0$ ，所以 $\overrightarrow {{y{{}_{3}}}}$ 有7个分量为 $-1$ ，
13. 设 $\overrightarrow {{y{{}_{3}}}}$ 的前7个分量中有 $r$ 个 $-1$ ，则后7个分量中有 $7-r$ 个 $-1$ ，
14. 所以 $\overrightarrow {{y{{}_{2}}}}\cdot \overrightarrow {{y{{}_{3}}}}=r\cdot \left ({-1}\right )+\left ({7-r}\right )+\left ({7-r}\right )+r\cdot \left ({-1}\right )=0$ ，可得 $r=\frac {7}{2}$ ，矛盾，
15. 所以不存在14个两两垂直的14维信号向量.

## 知识点

**中文**:
  - 空间向量新定义问题

**English**:
  - New Definition Problems

---
