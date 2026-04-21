# Mathematics - 题目 900

**ID**: b438c801d012418dbdf96316ad641ed5
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设 $n\in \mathbf{N}{^{*}}$ ，集合 $E{{}_{n}}=\{1,2,\cdots ,n\}$ ，若 $k$ 个互不相同的非空集合， $A{{}_{1}},A{{}_{2}},\cdots ,A{{}_{k}}$ 同时满足下面两个条件，则称 $A{{}_{1}},A{{}_{2}},\cdots ,A{{}_{k}}$ 是集合 $E{{}_{n}}$ 的“规范 $k-$ 子集组”① $A{{}_{i}}\subseteq E{{}_{n}}(i=1,2,\cdots ,k)$ ；②对任意的 $A{{}_{i}},A{{}_{j}}(1\leqslant i<j\leqslant k)$ ，要么 $A{{}_{i}}\cap A{{}_{j}}=\varnothing $ ，要么 $A{{}_{i}},A{{}_{j}}$ 中的一个是另一个的子集．（1）直接写出集合 $E{{}_{2}}$ 的一个“规范 $2-$ 子集组”；（2）若 $A{{}_{1}},A{{}_{2}},\cdots ,A{{}_{k}}$ 是集合 $E{{}_{n}}$ 的“规范 $k-$ 子集组”.​​​​​​​‌（ⅰ）求证： $A{{}_{1}},A{{}_{2}},\cdots ,A{{}_{k}}$ 中至多有1个集合对 $\left \{A{{}_{i}},A{{}_{j}}\right \}$ ，满足 $A{{}_{i}}\cap A{{}_{j}}=\varnothing $ 且 $A{{}_{i}}\cup A{{}_{j}}=E{{}_{n}}$ ；（ⅱ）求 $k$ 的最大值.

## 解答

1. （1）设 $E{{}_{2}}=\{1,2\}$ ，令 $A{{}_{1}}=\{1\},A{{}_{2}}=\{1,2\}$ ，则满足 $A{{}_{1}}\subseteq E{{}_{2}},A{{}_{2}}\subseteq E{{}_{2}}$ 且 $A{{}_{1}}\subseteq A{{}_{2}}$ ，
2. 所以 $E{{}_{2}}=\{1,2\}$ 的一个“规范 $2-$ 子集组”为 $\left \{A{{}_{1}},A{{}_{2}}\right \}$ .
3. （2）（ⅰ）利用反证法证明：
4. 假设“存在两个不同的集合对 $\left \{A{{}_{i}},A{{}_{j}}\right \}$ ； $\left \{A{{}_{μ}},A{{}_{v}}\right \}$ ”，
5. 依题意即 $A{{}_{i}},A{{}_{j}}$ 互补，不妨设对“规范k-子集组 $A{{}_{1}},A{{}_{2}},\cdots ,A{{}_{n}}$ ”来讲：
6. 一方面， $1\leqslant λ<μ\leqslant k$ 时， $Card\left ({A{{}_{λ}}}\right )\leqslant Card\left ({A{{}_{μ}}}\right )$ ，
7. 另一方面，其中存在两个不同的集合对 $\left \{A{{}_{i}},A{{}_{j}}\right \}$ ； $\left \{A{{}_{μ}},A{{}_{v}}\right \}$ 满足 $\begin{cases}1\leqslant i<j\leqslant k,\\1\leqslant μ<v\leqslant k,\\i\leqslant μ,\\A{{}_{i}}与A{{}_{j}}互补；A{{}_{μ}}与A{{}_{v}}互补,\end{cases}$
8. 不妨设 $i<μ$ ，即 $Card\left ({A{{}_{i}}}\right )\leqslant Card\left ({A{{}_{μ}}}\right )$ ，再由“ $A{{}_{j}}=\mathrm{∁}{{}_{E{{}_{n}}}}A{{}_{i}},A{{}_{v}}=\mathrm{∁}{{}_{E{{}_{n}}}}A{{}_{μ}}$ ”，得 $Card\left ({A{{}_{v}}}\right )\leqslant Card\left ({A{{}_{j}}}\right )$ ，
9. 此时，要么 $A{{}_{i}}\cap A{{}_{μ}}=\varnothing $ ，要么 $A{{}_{i}}$ 是 $A{{}_{μ}}$ 的真子集，
10. 若 $A{{}_{i}}\cap A{{}_{μ}}=\varnothing $ ，则 $\begin{cases}A{{}_{i}}\subseteq A{{}_{v}};A{{}_{μ}}\subseteq A{{}_{j}},\\A{{}_{j}}\cap A{{}_{v}}\ne \varnothing \end{cases}$  $\Rightarrow A{{}_{v}}\subseteq A{{}_{j}}$ ，
11. 故 $A{{}_{i}}\subseteq A{{}_{v}}\subseteq A{{}_{j}}$ ，这与与 $A{{}_{j}}=\mathrm{∁}{{}_{E{{}_{n}}}}A{{}_{i}}$ 矛盾；
12. 若 $A{{}_{i}}$ 是 $A{{}_{μ}}$ 的真子集，则 $A{{}_{v}}$ 是 $A{{}_{j}}$ 的真子集，
13. 此时 $A{{}_{j}}\cap A{{}_{μ}}\ne \varnothing $ ，且彼此都不是对方的子集，
14. 综上，假设“存在两个不同的集合对 $\left \{A{{}_{i}},A{{}_{j}}\right \}$ ； $\left \{A{{}_{μ}},A{{}_{v}}\right \}$ ”不成立，所以原结论成立，证毕.
15. （ⅱ）设 $E{{}_{n}}=\left \{1,2,\cdots ,n\right \}$ ，
16. 当 $1\leqslant i\leqslant n$ 时，令 $A{{}_{i}}=\left \{i\right \}$ ，
17. 当 $n+1\leqslant i\leqslant 2n-1$ 时，令 $A{{}_{i}}=\left \{x\in E∣1\leqslant x\leqslant i-n+1\right \}$ ，
18. 这样取出的 $2n-1$ 个集合 $A{{}_{i}}$ 满足题意，
19. 下面用数学归纳法证明 $k\leqslant 2n-1$ ，
20. 当 $n=1$ 时，结论成立；
21. 假设当 $n\leqslant m-1$ 时，结论成立，
22. 当 $n=m$ 时，考虑 $A{{}_{1}},A{{}_{2}},\cdots ,A{{}_{k}}$ 中不为全集且元素个数最多的集合（记为 $A{{}_{1}}$ ，并设 $A{{}_{1}}$ 中有 $t$ 个元素），则 $t\leqslant m-1$ ，
23. 将 $A{{}_{1}},A{{}_{2}},\cdots ,A{{}_{k}}$ 分为三类：
24. ①全集；
25. ②不为全集，且与 $A{{}_{1}}$ 的交集不为空集；
26. ③与 $A{{}_{1}}$ 的交集为空集.
27. 由 $A{{}_{1}}$ 的选取，知②中的集合均为 $A{{}_{1}}$ 的子集，且依然满足条件，由归纳假设可知②中的集合的个数不超过 $2t-1$ ，
28. 而③中的集合均为 $E\backslash A{{}_{1}}$ 的子集，有归纳假设可知集合的个数不超过 $2\left ({m-t}\right )-1$ ，
29. 所以 $k\leqslant 1+\left ({2t-1}\right )+2\left ({m-t}\right )-1=2m-1$ ，
30. 即当 $n=m$ 时，结论成立，
31. 所以均有 $k\leqslant 2n-1,n\in \mathbf{N}{{}_{+}}$ ，
32. 即 $k$ 的最大值为 $2n-1,n\in \mathbf{N}{{}_{+}}$ .

## 知识点

**中文**:
  - 集合的新定义问题

**English**:
  - New Definition Problems in Sets

---
