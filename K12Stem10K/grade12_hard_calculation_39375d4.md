# Mathematics - 题目 3947

**ID**: 39375d451dc24a84a8f09d2d3e61e726
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
将数列 $\left \{n\right \}\left ({n\in {\mathbf{N}}{^{{\rm{*}}}}}\right )$ 中的各项随机排列后构成一个数列为 $\left \{k{{}_{i}}\right \}\left ({1\leqslant i\leqslant n,i\in {\mathbf{N}}{^{{\rm{*}}}}}\right )$ ，则称 $\left \{k{{}_{i}}\right \}$ 是 $\left \{n\right \}$ 的一个“随机数列”；若 $\left \{k{{}_{i}}\right \}$ 中的各项均满足 $k{{}_{i}}\ne i$ ，则称 $\left \{k{{}_{i}}\right \}$ 是 $\left \{n\right \}$ 的“完全随机数列”，记 $\left \{n\right \}$ 的“完全随机数列”的个数为 $a{{}_{n}}$ .​​​​​​​‌(1)直接用 $n$ 表示 $\sum \limits_{i=1}^{n}\mathop{i}k{{}_{i}}$ 的最小值和最大值；（不需要写出过程）(2)分别计算 $a{{}_{1}},a{{}_{2}},a{{}_{3}},a{{}_{4}}$ ，并证明： $\left \{a{{}_{n}}-na{{}_{n-1}}\right \}\left ({n\geqslant 2}\right )$ 是公比为 $-1$ 的等比数列；(3)若从 $\left \{k{{}_{i}}\right \}$ 中随机选取一个数列，记此数列是 $\left \{n\right \}$ 的“完全随机数列”的概率为 $P{{}_{n}}$ ，证明： $P{{}_{n}}=\sum \limits_{i=0}^{n}\mathop{\frac {(-1){^{i}}}{i!}}$ .

## 解答

1. （1）最小值为 $\sum \limits_{i=1}^{n}\mathop{i}(n+1-i)=\frac {n(n+1)(n+2)}{6}$ ，
2. 最大值为 $\sum \limits_{i=1}^{n}\mathop{i{^{2}}}=\frac {n(n+1)(2n+1)}{6}$ .
3. （2）显然 $a{{}_{1}}=0$ ；
4. 当 $n\mathrm{=}2$ 时， $\left \{n\right \}$ 为数列1，2，
5. 则其完全随机数列必为2，1，
6. 故 $a{{}_{2}}=1$ ；
7. 当 $n=3$ 时， $\left \{n\right \}$ 为数列 $1,2,3$ ，
8. 则完全随机数列可以为 $2,3,1$ 或 $3,1,2$ ，
9. 故 $a{{}_{3}}=2$ ；
10. 当 $n=4$ 时， $\left \{n\right \}$ 为数列 $1,2,3,4$ ，为得到数列 $1,2,3,4$ 的完全随机数列，
11. 可先排1，有3种排法，比如1排到2的位置，那就再排2，也有3种排法，剩下的两个数字只有1种排法，
12. 由乘法计数原理可得 $a{{}_{4}}=3\times 3\times 1\times 1=9$ .
13. 当数列 $\left \{n\right \}$ 有 $n+1$ 项时，其“完全随机数列”的排法可以分为两个步骤：
14. 第一步：随机排 $n+1$ 且不排在第 $n+1$ 项的位置，有 $n$ 种排法；
15. 第二步：随机排其余 $n$ 项，根据第一步的排法，可以分为两类；
16. 第一类：若 ${\rm .}n+1$ 排在第 $i\left ({i=1,2,\cdots ,n}\right )$ 项的位置，但 $i$ 不排在第 $n+1$ 项的位置，这样的排法有 $a{{}_{n}}$ 种；
17. 第二类：若 $n+1$ 排在第 $i\left ({i=1,2,\cdots ,n}\right )$ 项的位置， $i$ 排在第 $n+1$ 项的位置，这样的排法有 $a{{}_{n-1}}$ 种，
18. 所以由计数原理得 $a{{}_{n+1}}=n\left ({a{{}_{n}}+a{{}_{n-1}}}\right )\left ({n\geqslant 2}\right )$ ，又 $a{{}_{2}}-2a{{}_{1}}=1$ ，
19. 所以 $\frac {a{{}_{n+1}}-\left ({n+1}\right )a{{}_{n}}}{a{{}_{n}}-na{{}_{n-1}}}=\frac {n\left ({a{{}_{n}}+a{{}_{n-1}}}\right )-\left ({n+1}\right )a{{}_{n}}}{a{{}_{n}}-na{{}_{n-1}}}$  $=\frac {-a{{}_{n}}+na{{}_{n-1}}}{a{{}_{n}}-na{{}_{n-1}}}=-1$ ，
20. 所以数列 $\left \{a{{}_{n}}-na{{}_{n-1}}\right \}\left ({n\geqslant 2}\right )$ 是公比为 $-1$ 的等比数列.
21. （3）证明：由（2）得 $a{{}_{n}}-na{{}_{n-1}}=(-1){^{n}}$ ，
22. 所以 $\frac {a{{}_{n}}}{n!}-\frac {a{{}_{n-1}}}{\left ({n-1}\right )!}=\frac {(-1){^{n}}}{n!}$ ，
23. $\frac {a{{}_{n-1}}}{\left ({n-1}\right )!}-\frac {a{{}_{n-2}}}{\left ({n-2}\right )!}=\frac {(-1){^{n-1}}}{\left ({n-1}\right )!}$ ，
24. $\frac {a{{}_{n-2}}}{\left ({n-2}\right )!}-\frac {a{{}_{n-3}}}{\left ({n-3}\right )!}=\frac {(-1){^{n-2}}}{\left ({n-2}\right )!}$ ，
25. $\cdots $
26. $\frac {a{{}_{2}}}{2!}-\frac {a{{}_{1}}}{1!}=\frac {1}{2!}$ ，
27. 以上各式相加可得 $\frac {a{{}_{n}}}{n!}-\frac {a{{}_{1}}}{1!}=\frac {1}{2!}-\frac {1}{3!}+\frac {1}{4!}-\frac {1}{5!}+\cdots +\frac {(-1){^{n}}}{n!}$ ，
28. 所以 $\frac {a{{}_{n}}}{n!}=\frac {1}{2!}-\frac {1}{3!}+\frac {1}{4!}-\frac {1}{5!}+\cdots +\frac {(-1){^{n}}}{n!}$ ，
29. 又数列 $\left \{n\right \}$ 的随机数列的个数为 $n!$ ，
30. 所以 $P{{}_{n}}=\frac {a{{}_{n}}}{n!}=1-1+\frac {1}{2!}-\frac {1}{3!}+\frac {1}{4!}-\frac {1}{5!}+\cdots +\frac {(-1){^{n}}}{n!}=\sum \limits_{i=0}^{n}\mathop{\frac {(-1){^{i}}}{i!}}$ .

## 知识点

**中文**:
  - 数列新定义问题
  - 等比数列的判定与证明

**English**:
  - New Definition Problems
  - Determination and Proof

---
