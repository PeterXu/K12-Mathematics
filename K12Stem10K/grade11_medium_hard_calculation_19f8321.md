# Mathematics - 题目 2856

**ID**: 19f832186dae463dae847fa1ceae96c1
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
某篮球运动员练习罚篮 $n$ 次 $\left ({n\in {\mathbf{N}}{^{*}}}\right )$ ，假设每次投中的概率均为 $1-p\left ({0<p<1}\right )$ ，各次投中与否相互独立.​​​​​​​‌（1）若 $n=10$ ，记 $10$ 次罚篮中恰好命中 $8$ 次的概率为 $f\left ({p}\right )$ ，求 $f\left ({p}\right )$ 的极值点；（2）若 $n=16$ ， $p=0.1$ ，求该球员最有可能命中多少次；（3）记 $n$ 次罚篮中命中的次数为奇数的概率为 $P\left ({A}\right )$ ，证明：当 $\frac {1}{2}<p<1$ 时， $P\left ({A}\right )$ 随着 $n$ 的增大而增大.

## 解答

1. （1）由题意知 $f\left ({p}\right )={\rm{C}}{{}_{10}^{8}}p{^{2}}{\left({1-p}\right)^{8}}$ ，
2. $f^{′}{\left ({p}\right )}={\rm{C}}{{}_{10}^{8}}\left [2p{\left({1-p}\right)^{8}}-8p{^{2}}{\left({1-p}\right)^{7}}\right ]=2{\rm{C}}{{}_{10}^{2}}p{\left({1-p}\right)^{7}}\left ({1-5p}\right )$ ，
3. 当 $0<p<\frac {1}{5}$ 时， $f^{′}{\left ({p}\right )}>0$ ；当 $\frac {1}{5}<p<1$ 时， $f^{′}{\left ({p}\right )}<0$
4. 所以 $f\left ({p}\right )$ 在 $\left ({0,\frac {1}{5}}\right )$ 上单调递增，在 $\left ({\frac {1}{5},1}\right )$ 上单调递减，
5. 所以 $p=\frac {1}{5}$ 为 $f\left ({p}\right )$ 的极大值点.
6. （2）设命中 $k$ 次 $\left ({k\in {\mathbf{N}},0\leqslant k\leqslant 16}\right )$ 的概率为 $P{{}_{k}}$ ，
7. 则 $P{{}_{k}}={\rm{C}}{{}_{16}^{k}}0.9{^{k}}{\left({1-0.9}\right)^{16-k}}\left ({0\leqslant k\leqslant 16,k\in {\mathbf{N}}}\right )$ ，
8. 设 $P{{}_{k}}\left ({1\leqslant k\leqslant 15,k\in {\mathbf{N}}}\right )$ 最大，则 $\begin{cases}P{{}_{k}}\geqslant P{{}_{k-1}}\\P{{}_{k}}\geqslant P{{}_{k+1}}\end{cases}$ ，
9. 即 $\begin{cases}{\rm{C}}{{}_{16}^{k}}\cdot 0.9{^{k}}\cdot 0.1{^{16-k}}\geqslant {\rm{C}}{{}_{16}^{k-1}}\cdot 0.9{^{k-1}}\cdot 0.1{^{17-k}}\\{\rm{C}}{{}_{16}^{k}}\cdot 0.9{^{k}}\cdot 0.1{^{16-k}}\geqslant {\rm{C}}{{}_{16}^{k+1}}\cdot 0.9{^{k+1}}\cdot 0.1{^{15-k}}\end{cases}$ ，
10. 解得 $14.3\leqslant k\leqslant 15.3$ ，因为 $k\in {\mathbf{N}}$ ，故 $k=15$ ，故该球员最有可能命中 $15$ 次.
11. （3）设 $n$ 次罚篮中命中的次数为偶数的概率为 $P\left ({B}\right )$ ，
12. 由题意知 $P\left ({A}\right )={\rm{C}}{{}_{n}^{1}}p{^{n-1}}\left ({1-p}\right )+{\rm{C}}{{}_{n}^{3}}p{^{n-3}}{\left({1-p}\right)^{3}}+{\rm{C}}{{}_{n}^{5}}p{^{n-5}}{\left({1-p}\right)^{5}}+\cdots $ ，
13. $P\left ({B}\right )={\rm{C}}{{}_{n}^{0}}p{^{n}}{\left({1-p}\right)^{0}}+{\rm{C}}{{}_{n}^{2}}p{^{n-2}}{\left({1-p}\right)^{2}}+{\rm{C}}{{}_{n}^{4}}p{^{n-4}}{\left({1-p}\right)^{4}}+\cdots $ ，
14. 所以 $P\left ({B}\right )-P\left ({A}\right )={\rm{C}}{{}_{n}^{0}}p{^{n}}{\left({1-p}\right)^{0}}-{\rm{C}}{{}_{n}^{1}}p{^{n-1}}{\left({1-p}\right)^{1}}+{\rm{C}}{{}_{n}^{2}}p{^{n-2}}{\left({1-p}\right)^{2}}-{\rm{C}}{{}_{n}^{3}}p{^{n-3}}{\left({1-p}\right)^{3}}$
15. $+{\rm{C}}{{}_{n}^{4}}p{^{n-4}}{\left({1-p}\right)^{4}}+\cdots +{\left({-1}\right)^{n}}{\rm{C}}{{}_{n}^{n}}p{^{0}}{\left({1-p}\right)^{n}}=\left [p-\left ({1-p}\right )\right ]{^{n}}={\left({2p-1}\right)^{n}}$ ，
16. $P\left ({B}\right )+P\left ({A}\right )={\rm{C}}{{}_{n}^{0}}p{^{n}}{\left({1-p}\right)^{0}}+{\rm{C}}{{}_{n}^{1}}p{^{n-1}}{\left({1-p}\right)^{1}}+{\rm{C}}{{}_{n}^{2}}p{^{n-2}}{\left({1-p}\right)^{2}}+{\rm{C}}{{}_{n}^{3}}p{^{n-3}}{\left({1-p}\right)^{3}}$
17. $+{\rm{C}}{{}_{n}^{4}}p{^{n-4}}{\left({1-p}\right)^{4}}+\cdots +{\rm{C}}{{}_{n}^{n}}p{^{0}}{\left({1-p}\right)^{n}}=\left [p+\left ({1-p}\right )\right ]{^{n}}=1$ ，
18. 所以 $P\left ({A}\right )=\frac {1-{\left({2p-1}\right)^{n}}}{2}$ ，
19. 因为 $\frac {1}{2}<p<1$ ，所以 $0<2p-1<1$ ，故 $P\left ({A}\right )$ 随着 $n$ 的增大而增大.

## 知识点

**中文**:
  - 二项分布
  - 利用导数研究函数的极值

**English**:
  - Binomial Distribution
  - Extrema of Functions using Derivatives

---
