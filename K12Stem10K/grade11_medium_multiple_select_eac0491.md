# Mathematics - 题目 226

**ID**: eac0491adb2340c6a926d77ad53cc8d6
**年级**: Grade 11
**难度**: Medium
**题型**: Multiple-select

## 题目
数列 $\left \{a{{}_{n}}\right \}$ 满足 $a{{}_{n}}+a{{}_{n+1}}=(-1){^{n+1}}\left ({n\in {\mathbf{N}}{^{{\rm{*}}}}}\right )$ ，且 $a{{}_{1}}=-3$ ，数列 $\left \{a{{}_{n}}\right \}$ 的前 $n$ 项和为 $S{{}_{n}}$ ，从 $\left \{a{{}_{n}}\right \}$ 的前 $2n$ 项中任取两项，它们的和为奇数的概率为 $P{{}_{2n}}$ ，则（      ）​​​​​​​‌

## 解答

1. $\because a{{}_{n}}+a{{}_{n+1}}=(-1){^{n+1}}$ ， $\therefore \frac {a{{}_{n}}}{{\left({-1}\right)^{n+1}}}+\frac {a{{}_{n+1}}}{{\left({-1}\right)^{n+1}}}=1$ ， $\therefore \frac {a{{}_{n+1}}}{{\left({-1}\right)^{n+1}}}-\frac {a{{}_{n}}}{{\left({-1}\right)^{n}}}=1$ ，
2. 又 $\frac {a{{}_{1}}}{-1}=3$ ，所以数列 $\left \{\frac {a{{}_{n}}}{{\left({-1}\right)^{n}}}\right \}$ 是首项为3，公差为1的等差数列.，
3. 即 $\frac {a{{}_{n}}}{{\left({-1}\right)^{n}}}=n+2$ ， $\therefore a{{}_{n}}=(-1){^{n}}\left ({n+2}\right )$ ，
4. 对于选项A： $a{{}_{4}}={\left({-1}\right)^{4}}\times \left ({4+2}\right )=6$ ，故A正确；
5. 对于选项B： $a{{}_{11}}+a{{}_{15}}=(-1){^{11}}\left ({11+2}\right )+(-1){^{15}}\left ({15+2}\right )=-30;a{{}_{13}}=(-1){^{13}}\left ({13+2}\right )=-15,$ 所以 $a{{}_{11}}+a{{}_{15}}=2a{{}_{13}}$ ，故B正确；
6. 对于选项C： $S{{}_{12}}=\left ({a{{}_{1}}+a{{}_{2}}}\right )+\left ({a{{}_{3}}+a{{}_{4}}}\right )+\cdots +\left ({a{{}_{11}}+a{{}_{12}}}\right )=1+1+1+1+1+1=6$ ，故C正确；
7. 对于选项D：显然 $n$ 为奇数时， $a{{}_{n}}$ 为奇数， $n$ 为偶数时， $a{{}_{n}}$ 为偶数，
8. 因此要满足两项之和为奇数，则取奇偶各一个，
9. 所以 $P{{}_{2n}}=\frac {{\rm{C}}{{}_{n}^{1}}\cdot {\rm{C}}{{}_{n}^{1}}}{{\rm{C}}{{}_{2n}^{2}}}=\frac {n}{2n-1}=\frac {1}{2}+\frac {1}{2}\cdot \frac {1}{2n-1}>\frac {1}{2}$ ，故D正确.
10. 故选ABD.

## 知识点

**中文**:
  - 数列的前n项和
  - 数列的递推公式
  - 数列的通项
  - 概率与计数原理相结合的应用题

**English**:
  - Sum of the First n Terms
  - Recurrence Formula
  - General Term
  - Combined Problems

---
