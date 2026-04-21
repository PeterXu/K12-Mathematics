# Mathematics - 题目 3883

**ID**: 132cbd7e07954e7a96d37ac9c955e3b0
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
将数列 $\left \{a{{}_{n}}\right \}$ 中不同的两项 $a{{}_{i}}$ 与 $a{{}_{j}}$ 交换位置，其余项不变得到的数列称为 $\left \{a{{}_{n}}\right \}$ 的“ $\left ({i,j}\right )$ 对换数列”，若 $i<j$ 时， $a{{}_{i}}>a{{}_{j}}$ ，则称 $\left ({a{{}_{i}},a{{}_{j}}}\right )$ 为 $\left \{a{{}_{n}}\right \}$ 一个逆序对，例如：数列2，3，1的逆序对有： $\left ({2,1}\right )$ ， $\left ({3,1}\right )$ .​​​​​​​‌将数列 $\left \{a{{}_{n}}\right \}$ 中逆序对的个数称为 $\left \{a{{}_{n}}\right \}$ 的逆序数，记为 $N\left ({a{{}_{n}}}\right )$ ，记 ${\rm }{\rm {\rm sgn}}\left ({a{{}_{n}}}\right )=\left ({-1}\right ){^{N\left ({a{{}_{n}}}\right )}}{\rm }$ .（1）写出数列1，5，2，4，3，6的所有逆序对；（2）求数列 $1,2,3,\cdots ,n$ 的所有“ $\left ({i,j}\right )$ 对换数列”的逆序数之和 $f\left ({n}\right )$ ；（3）定义：将数列 $1,2,3,\cdots ,n$ 的所有项重新排列后得到的数列称为 $1,2,3,\cdots ,n$ 的一个“重排数列”.若 $\left \{a{{}_{n}}\right \}$ 是数列 $1,2,3,\cdots ,n$ 的一个“重排数列”， $\left \{b{{}_{n}}\right \}$ 是数列 $1,2,3,\cdots ,n$ 的一个“ $\left ({i,j}\right )$ 对换数列”，证明： ${\rm {\rm sgn}}\left ({a{{}_{b{{}_{n}}}}}\right )={\rm {\rm sgn}}\left ({a{{}_{n}}}\right )\cdot {\rm {\rm sgn}}\left ({b{{}_{n}}}\right )$ .（注： $1{^{2}}+2{^{2}}+3{^{2}}+\cdots +n{^{2}}=\frac {n\left ({n+1}\right )\left ({2n+1}\right )}{6}$ .）

## 解答

1. （1） $\left ({5,2}\right )$ ， $\left ({5,4}\right )$ ， $\left ({5,3}\right )$ ， $\left ({4,3}\right )$ ；
2. （2）因为交换 $i$ 与 $j$ 后共产生 $2\left ({j-i-1}\right )+1=2\left ({j-i}\right )-1$ 个逆序数， $1\leqslant i<j\leqslant n$ ，
3. 所以 $f\left ({n}\right )=\sum \limits_{j=2}^{n}\mathop{\left \{2\left [\left ({j-1}\right )+\left ({j-2}\right )+\cdots +\left ({j-\left ({j-1}\right )}\right )\right ]-\left ({j-1}\right )\right \}=\sum \limits_{j=2}^{n}\mathop{{\left({j-1}\right)^{2}}}}$
4. $=1{^{2}}+2{^{2}}+\cdots +{\left({n-1}\right)^{2}}=\frac {n\left ({n-1}\right )\left ({2n-1}\right )}{6}$ ；
5. （3）由（2）可知， ${\rm {\rm sgn}}\left ({b{{}_{n}}}\right )=\left ({-1}\right ){^{2\left ({j-i}\right )-1}}=-1$ ，
6. 因为 $\left \{a{{}_{b{{}_{n}}}}\right \}$ 是将 $\left \{a{{}_{n}}\right \}$ 中 $a{{}_{i}}$ 与 $a{{}_{j}}$ 两项交换所得，
7. 故 $a{{}_{i}}$ 之前的项 $a{{}_{1}},a{{}_{2}},\cdots ,a{{}_{i-1}}$ 及 $a{{}_{j}}$ 之后的项 $a{{}_{j+1}},a{{}_{j+2}},\cdots ,a{{}_{n}}$ 逆序数不变，
8. 对于 $a{{}_{i}}$ 与 $a{{}_{j}}$ 之间的项 $a{{}_{i+1}},a{{}_{i+2}},\cdots ,a{{}_{j-1}}$ ，
9. 只有满足 ${\rm \min }\left \{a{{}_{i}},a{{}_{j}}\right \}<k<{\rm \max }\left \{a{{}_{i}},a{{}_{j}}\right \}$ 的数 $k$ 才会发生逆序数的变化，
10. 设这样的数有 $m$ 个，由于这 $m$ 个数对 $a{{}_{i}}$ 与 $a{{}_{j}}$ 的顺序同时发生变化，
11. 产生 $2m$ 个逆序数，又 $a{{}_{i}}$ 与 $a{{}_{j}}$ 交换产生1个逆序数，
12. 则共产生 $2m+1$ 个逆序数，设 $N\left ({a{{}_{n}}}\right )=p$ ，
13. 则 $N\left ({a{{}_{b{{}_{n}}}}}\right )=2m+1+p$ ，
14. 则 ${\rm {\rm sgn}}\left ({a{{}_{b{{}_{n}}}}}\right )={\left({-1}\right)^{2m+1+p}}=-{\left({-1}\right)^{p}}={\rm {\rm sgn}}\left ({a{{}_{n}}}\right )\cdot {\rm {\rm sgn}}\left ({b{{}_{n}}}\right )$ .

## 知识点

**中文**:
  - 数列新定义问题

**English**:
  - New Definition Problems

---
