# Mathematics - 题目 3576

**ID**: ef4e55b4900441c087ef29ce8231fd4e
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Fill-in-the-blank

## 题目
定义：如果甲队赢了乙队，乙队赢了丙队，而丙队又赢了甲队，则称甲乙丙为一个“友好组”.​​​​​​​‌如果20支球队参加单循环比赛，则友好组个数的最大值为.

## 解答

1. 当 $m$ 为偶数时，令 $m=2n$ ，则总共有 ${\rm{C}}_{2n}^{2}$ 场比赛.
2. 不妨设有 $x$ 个友好组，考虑其反面，若甲乙丙三对为非友好组，不妨设甲队赢了乙队和丙队，此时，记甲队为非友好组的组长.对甲队而言，可以在赢的所有队伍中任意选择两队构成非友好组.
3. 因此，若队 $A_{i}\left ({i=1,2,\cdots ,2n}\right )$ 在比赛中赢了 $k_{i}$ 场，则 $\sum \limits_{i=1}^2n{k_{i}}={\rm{C}}_{2n}^{2}$ ，且以 $A_{i}$ 为组长的非友好组有 ${\rm{C}}_{k_{i}}^{2}$ 个（补充定义：，于是所有非友好组的个数为 $\sum \limits_{i=1}^2n{{\rm{C}}_{k_{i}}^{2}}$ .
4. 下求 $\sum \limits_{i=1}^2n{{\rm{C}}_{k_{i}}^{2}}$ 最小值.
5. 若在 $k_{1},k_{2},\cdots ,k_{2n}$ 中，有 $k_{j}-k_{i}\geqslant 2$ .
6. 则令 $k_{i}^{{\rm{*}}}=k_{i}+1,k_{j}^{{\rm{*}}}=k_{j}-1$ ，其余 $k_{j}^{{\rm{*}}}=k_{i}(1\leqslant l\leqslant 2n$ 且 $l\ne i,j)$ ，
7. ${\rm{C}}_{k_{i}^{{\rm{*}}}}^{2}+{\rm{C}}_{k_{j}^{{\rm{*}}}}^{2}-{\rm{C}}_{k_{i}}^{2}-{\rm{C}}_{k_{j}}^{2}={\rm{C}}_{k_{i}+1}^{2}+{\rm{C}}_{k_{j}-1}^{2}-{\rm{C}}_{k_{i}}^{2}-{\rm{C}}_{k_{j}}^{2}=k_{i}-k_{j}+1\leqslant -1$ ，
8. 故调整后 $\sum \limits_{i=1}^2n{{\rm{C}}_{k_{i}}^{2}}$ 的总和变小.重复上述操作，直至任意两个数的差最多为1.
9. 不妨设有 $y$ 个 $a,2n-y$ 个 $a+1$ ，则有 $ya+\left ({2n-y}\right )\left ({a+1}\right )=C_{2n}^{2}=n\left ({2n-1}\right ),$
10. 整理有 $a-\frac {y}{2n}=\left ({n-1}\right )-\frac {1}{2}$ .
11. 由于 $1\leqslant y\leqslant 2n-1$ ，故 $\frac {y}{2n}\in \left ({0,1}\right )$ .由等式两边对应相等可知， $a=n-1,y=n$ ，
12. 即调整后有 $n$ 个 $n-1,n$ 个 $n$ .此时的值 $\sum \limits_{i=1}^2n{{\rm{C}}_{k_{i}}^{2}}$ 为 $n(n-1)^{2}$ ，
13. 则 $x\leqslant {\rm{C}}_{2n}^{3}-n(n-1)^{2}=\frac {n\left ({n-1}\right )\left ({n+1}\right )}{3}$ ，
14. 故友好组个数的最大值为 $\frac {n\left ({n-1}\right )\left ({n+1}\right )}{3}$ ，即 $\frac {m\left ({m-2}\right )\left ({m+2}\right )}{24}$ .
15. 下面为取到最大值的例子：设在 $A_{1},A_{2},\cdots ,A_{2n}$ .共 $2n$ 支球队中，当 $1\leqslant i\leqslant n$ 时，队 $A_{i}$ 胜 $A_{i+1},A_{i+2},\cdots A_{i+n}$ ；当 $n+1\leqslant i\leqslant 2n$ 时，队 $A_{i}$ 胜 $A_{i+1},A_{i+2},\cdots ,A_{i+n-1}$ ，下标均是在模 $2n$ 的意义下.
16. 综上所述，当 $m$ 为偶数时，友好组个数的最大值为 $\frac {m\left ({m-2}\right )\left ({m+2}\right )}{24}$ .故如果20支球队参加单循环比赛，友好组个数的最大值为330.
17. 故答案为：330

## 知识点

**中文**:
  - 其它有限制条件的组合问题

**English**:
  - Other Restricted Combination Problems

---
