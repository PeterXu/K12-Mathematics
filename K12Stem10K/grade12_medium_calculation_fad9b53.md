# Mathematics - 题目 621

**ID**: fad9b535806443f2afe357d7e588bd97
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
给定正整数 $n\geqslant 2$ ，设集合 $M=\left \{α∣α=\left ({t{{}_{1}},t{{}_{2}},\cdots ,t{{}_{n}}}\right ),t{{}_{k}}\in \left \{0,1\right \},k=1,2,\cdots ,n\right \}$ .​​​​​​​‌对于集合 $M$ 中的任意元素 $β=\left ({x{{}_{1}},x{{}_{2}},\cdots ,x{{}_{n}}}\right )$ 和 $γ=\left ({y{{}_{1}},y{{}_{2}},\cdots ,y{{}_{n}}}\right )$ ，记 $β\cdot γ=x{{}_{1}}y{{}_{1}}+x{{}_{2}}y{{}_{2}}+\cdots +x{{}_{n}}y{{}_{n}}$ .设 $A\subseteq M$ ，且集合 $A=\left \{α{{}_{i}}∣α{{}_{i}}=\left ({t{{}_{i1}},t{{}_{i2}},\cdots ,t{{}_{in}}}\right ),i=1,2,\cdots ,n\right \}$ ，对于 $A$ 中任意元素 $α{{}_{i}},α{{}_{j}}$ ，若 $a{{}_{i}}\cdot a{{}_{j}}=\begin{cases}p,i=j,\\1,i\ne j,\end{cases}$ ，则称 $A$ 具有性质 $T\left ({n,p}\right )$ .(1)是否存在集合 $A$ 具有性质 $T\left ({2,1}\right )$ ，若存在，请写出 $A$ 的表达式，若不存在，请说明理由；(2)判断集合 $A=\left \{\left ({1,1,0}\right ),\left ({1,0,1}\right ),\left ({0,1,1}\right )\right \}$ 是否具有性质 $T\left ({3,2}\right )$ ？若具有，求 $\sum \limits_{i,j=1}^{3}\mathop{a{{}_{i}}}\cdot a{{}_{j}}$ 的值；若不具有，请说明理由；(3)是否存在具有性质 $T\left ({4,p}\right )$ 的集合 $A$ ？若存在，请找出来；若不存在，请说明理由.

## 解答

1. （1）由题意可知 $T\left ({2,1}\right )$ 表示集合 $A$ 有2个元素，且 $p=1$ ， $a{{}_{i}}\cdot a{{}_{i}}=1$ ，
2. 则 $a{{}_{i}}=\left ({1,0}\right )$ 或 $a{{}_{i}}=\left ({0,1}\right )$ ，均无法满足 $a{{}_{i}}\cdot a{{}_{j}}=1,\left ({i\ne j}\right )$ ，
3. 所以不存在集合 $A$ 具有性质 $T\left ({2,1}\right )$ .
4. （2）对于 $A=\{(1,1,0),(1,0,1),(0,1,1)\}$ ，
5. 则 $\left ({1,1,0}\right )\cdot \left ({1,1,0}\right )=1+1+0=2$ ，同理 $(1,0,1)\cdot (1,0,1)=(0,1,1)\cdot (0,1,1)=2$ ，
6. 而 $\left ({1,1,0}\right )\cdot \left ({1,0,1}\right )=1+0+0=1$ ，同理 $(1,1,0)\cdot (0,1,1)=(1,0,1)\cdot (0,1,1)=1$ ，
7. 所以 $A$ 具有性质 $T\left ({3,2}\right )$ .
8. 且 $\sum \limits_{i,j=1}^{3}\mathop{a{{}_{i}}}\cdot a{{}_{j}}=3\times 2+6\times 1=12$ .
9. （3）假设存在集合 $A$ 具有性质 $T\left ({4,p}\right )$ ，易知集合 $A$ 中有4个元素且 $p\in \{0,1,2,3,4\}$ .
10. ①若 $p=0$ ，则 $A=\left \{\left ({0,0,0,0}\right )\right \}$ ，不符合4个元素，舍去；
11. ②若 $p=1$ ，则 $A\subseteq \{\left ({1,0,0,0}\right ),\left ({0,1,0,0}\right )$ ， $\left ({0,0,1,0}\right ),\left ({0,0,0,1}\right )\}$ ，
12. 又 $\left ({1,0,0,0}\right )\cdot \left ({0,1,0,0}\right )=0$ ，
13. 所以不满足，舍去；
14. ③若 $p=2$ ，则 $A\subseteq \{(1,1,0,0),(1,0,1,0),(1,0,0,1),(0,1,1,0),(0,1,0,1),(0,0,1,1)\}$ ，
15. 又 $\left ({1,1,0,0}\right )\cdot \left ({0,0,1,1}\right )=\left ({1,0,1,0}\right )\cdot $  $\left ({0,1,0,1}\right )=\left ({1,0,0,1}\right )\cdot \left ({0,1,1,0}\right )=0$ ，
16. 所以这3组每组至多只能有一个包含于 $A$ ，所以 $A$ 至多只有3个元素，矛盾，舍去；
17. ④若 $p=3$ ，则 $A\subseteq \{\left ({1,1,1,0}\right ),\left ({1,1,0,1}\right )$ ， $\left ({1,0,1,1}\right ),\left ({0,1,1,1}\right )\}$ ，
18. 又 $\left ({1,1,1,0}\right )\cdot \left ({1,1,0,1}\right )=2$ ，
19. 所以不满足，舍去；
20. ⑤若 $p=4$ ，则 $A=\left \{\left ({1,1,1,1}\right )\right \}$ ，只有一个元素，舍去.
21. 综上，不存在具有性质 $T\left ({4,p}\right )$ 的集合 $A$ .

## 知识点

**中文**:
  - 集合的新定义问题

**English**:
  - New Definition Problems in Sets

---
