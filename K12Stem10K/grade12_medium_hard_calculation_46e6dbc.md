# Mathematics - 题目 805

**ID**: 46e6dbc1960447d08fba315e1bf320d6
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设 $\left \{a{{}_{n}}\right \}$ 和 $\left \{b{{}_{n}}\right \}$ 均为各项互不相等的N项数列，其中 $a{{}_{i}},b{{}_{i}}\in \left \{1,2,\cdots ,N\right \}$ ， $i=1,2,\cdots ,N$ ．记数列C： $c{{}_{1}}$ ， $c{{}_{2}}$ ，…， $c{{}_{N}}$ ，其中 $c{{}_{k}}=a{{}_{k}}-b{{}_{k}}$ ， $k=1,2,\cdots ,N$ ．（1）写出所有满足条件的数列 $\left \{a{{}_{n}}\right \}$ 和 $\left \{b{{}_{n}}\right \}$ ，使得数列 $C:-1,-1,0,2$ ；​​​​​​​‌（2）若 $N=2024{\rm ，\mathit{C}}$ 是公差不为0的等差数列，求证： $a{{}_{i}}+b{{}_{i}}$ 为定值；（3）若C为各项互不相等的数列，记C中最大的数为P，最小的数为Q，求 $P-Q$ 的最小值．

## 解答

1. （1）显然 $N=4$ ，因为 $\left ({a{{}_{1}}}\right ){{}_{{\rm \min }}}=1$ ，
2. 根据 $C:-1,-1,0,2$ ， $c{{}_{k}}=a{{}_{k}}-b{{}_{k}}$ ，则 $\left ({a{{}_{1}}}\right ){{}_{{\rm \min }}}=1$ ， $\left ({a{{}_{1}}}\right ){{}_{{\rm \max }}}=3$ ， $\left ({b{{}_{4}}}\right ){{}_{{\rm \min }}}=1,\left ({b{{}_{4}}}\right ){{}_{{\rm \max }}}=2$ ，
3. 从而满足条件的答案有4组，分别为：
4. $\left \{a{{}_{n}}\right \}:1,2,4,3,\left \{b{{}_{n}}\right \}:2,3,4,1$ ； $\left \{a{{}_{n}}\right \}:2,1,4,3,\left \{b{{}_{n}}\right \}:3,2,4,1$ ；
5. $\left \{a{{}_{n}}\right \}:2,3,1,4,\left \{b{{}_{n}}\right \}:3,4,1,2$ ； $\left \{a{{}_{n}}\right \}:3,2,1,4,\left \{b{{}_{n}}\right \}:4,3,1,2$ .
6. （2）记等差数列 $C$ 的公差为 $d(d\ne 0)$ ，
7. 由 $a{{}_{i}},b{{}_{i}}\in \{1,2,\cdots ,2024\},c{{}_{k}}=a{{}_{k}}-b{{}_{k}},\quad k=1,2,\cdots ,2024$ ，
8. 得 $-2023\leqslant c{{}_{1}}\leqslant 2023$ ，则 $-4046\leqslant c{{}_{2024}}-c{{}_{1}}\leqslant 4046$ .
9. 由 $c{{}_{2024}}-c{{}_{1}}=2023d$ ，得 $d\in \{-2,-1,1,2\}$ .
10. 因为 $a{{}_{i}},b{{}_{i}}\in \left \{1,2,\cdots ,2024\right \}$ ，且 $\left \{a{{}_{n}}\right \}$ 和 $\left \{b{{}_{n}}\right \}$ 均为各项互不相等的2024项数列，
11. 所以 $\sum \limits_{i=1}^{2024}\mathop{c{{}_{i}}}=\sum \limits_{i=1}^{2024}\mathop{a{{}_{i}}}-\sum \limits_{i=1}^{2024}\mathop{b{{}_{i}}}=0$ ，
12. 所以 $\sum\limits_{i=1}^{2024}\mathop{}c{{}_{i}}=\frac {2024\left ({c{{}_{1}}+c{{}_{2024}}}\right )}{2}=0$ ，即 $c{{}_{1}}+c{{}_{2024}}=c{{}_{1012}}+c{{}_{1013}}=0$ .
13. 所以公差 $d=c{{}_{1013}}-c{{}_{1012}}=\pm 2$ .
14. 不妨设公差 $d=2$ ，则 $C:-2023,-2021,\cdots ,2021,2023$ ，
15. 而 $\pm 2023$ 只能由1和2024得到，去除两端的数后 $\pm 2021$ 只能由2和2023得到 $\cdots \cdots $
16. 以此类推，于是 $a{{}_{i}}+b{{}_{i}}$ 总为定值2025.
17. （3）由题意，数列 $C$ 中有 $N$ 个不同的整数，则 $P-Q\geqslant $  $N-1$ ，当且仅当数列 $C$ 为 $N$ 个连续整数时取等号，
18. 当 $N$ 为偶数时，若存在数列 $C$ ，使得 $P-Q=N-1$ ，则 $\sum\limits_{i=1}^{N}\mathop{}c{{}_{i}}=\frac {N\left ({c{{}_{1}}+c{{}_{i}}+N-1}\right )}{2}$ .
19. 由 $N$ 为偶数，知 $c{{}_{1}}+c{{}_{i}}+N-1$ 为奇数，则 $\sum\limits_{i=1}^{N}\mathop{}c{{}_{i}}$ 不可能为0.
20. 这与 $\sum \limits_{i=1}^{N}\mathop{c{{}_{i}}}=\sum \limits_{i=1}^{N}\mathop{a{{}_{i}}}-\sum \limits_{i=1}^{N}\mathop{b{{}_{i}}}=0$ 矛盾，
21. 所以当 $N$ 为偶数时， $P-Q\geqslant N$ .
22. 当 $N$ 为偶数时，如果数列 $\left \{a{{}_{n}}\right \}:1,2,3,\cdots ,\frac {N}{2}-1,\frac {N}{2},\frac {N}{2}+1,\frac {N}{2}+2,\cdots ,N-1,N$ ；
23. 数列 $\left \{b{{}_{n}}\right \}:2,4,6,\cdots ,N-2,N,1,3,\cdots ,N-3,N-1$ ；
24. 那么数列 $C:-1,-2,-3,\cdots ,-\frac {N}{2}+1,-\frac {N}{2},\frac {N}{2},\frac {N}{2}-1,\cdots ,2,1$ ，此时满足 $P-Q=N$ .
25. 当 $N$ 为奇数时，如果数列 $\left \{a{{}_{n}}\right \}:1,2,3,\cdots ,\frac {N-1}{2}-1,\frac {N-1}{2},\frac {N-1}{2}+1,\frac {N-1}{2}+2,\cdots ,N-2,N-1,N$ ；
26. 数列 $\left \{b{{}_{n}}\right \}:2,4,6,\cdots ,N-3,N-1,1,3,\cdots ,N-4,N-2,N$ ；
27. 那么数列 $C:-1,-2,\cdots ,-\frac {N-1}{2}+1,-\frac {N-1}{2},\frac {N-1}{2},\frac {N-1}{2}-1,\cdots ,2,1,0$ ，此时 $P-Q=N-1$ .
28. 综上，当 $N$ 为偶数时， $P-Q$ 最小值为 $N$ ；当 $N$ 为奇数时， $P-Q$ 最小值为 $N-1$ .

## 知识点

**中文**:
  - 数列新定义问题

**English**:
  - New Definition Problems

---
