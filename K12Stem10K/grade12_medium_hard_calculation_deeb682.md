# Mathematics - 题目 952

**ID**: deeb682454b847af9879dc474f573fe5
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
在概率统计中，我们常常通过观测到的实验结果应用极大似然估计法来估计某参数的取值．设 $X$ 为其分布列与未知参数 $m$ 有关的离散型随机变量，其中 $m$ 的取值范围为 $S$ ．若对已知结果 $X=k$ ，有 $m{{}_{0}}\in S$ ，且 $\forall m{{}_{1}}\in S$ ，有 $P\left ({\left .​​​​​​​‌{X=k}\right |m=m{{}_{0}}}\right )\mathrm{\geqslant }P\left ({\left .{X=k}\right |m=m{{}_{1}}}\right )$ 成立，则称 $m{{}_{0}}$ 为 $m$ 在 $X=k$ 下的一个极大似然估计．（1）（i）若 $X$ 服从二项分布 $B\left ({2,m}\right )$ ，求 $m$ 在 $X=1$ 下的极大似然估计；${\rm （ii）}$ 若 $X$ 服从二项分布 $B\left ({m,\frac {1}{2}}\right )$ ，求 $m$ 在 $X=3$ 下的极大似然估计．（2）若某台抽奖机上有一个按钮，参与者需要连续快速点击按钮来累积积分换取奖品．已知每次点击按钮后，获得1积分的概率为 $p(0<p<1)$ ，不获得积分的概率为 $1-p$ ．小丽参加这个抽奖活动后总共获得了 $k$ 积分，用极大似然估计的方法估计她点击按钮的总次数 $m$ 的取值为 $m{{}_{0}}$ ，证明： $m{{}_{0}}\mathrm{\leqslant }\frac {k}{p}$ ，并指出等号成立的条件．

## 解答

1. （1）（i）由题意可得 $P\left ({X=1}\right )=2m\left ({1-m}\right )$ ，
2. 故当 $m=\frac {1}{2}$ 时取最大值，其极大似然估计为 $\frac {1}{2}$ ．
3. ${\rm （ii）}$ 由题得 $m\in {\mathbf{N}}{^{{\rm{*}}}}$ ，且 $m\mathrm{\geqslant }3$ ，
4. $P\left ({X=3}\right )={\rm{C}}{{}_{m}^{3}}\frac {1}{2{^{m}}}=\frac {m!}{3!\cdot \left ({m-3}\right )!\cdot 2{^{m}}}=\frac {m\left ({m-1}\right )\left ({m-2}\right )}{6\cdot 2{^{m}}}$ ，
5. 令 $a{{}_{m}}=\frac {m\left ({m-1}\right )\left ({m-2}\right )}{6\cdot 2{^{m}}}$ ，则 $\frac {a{{}_{m+1}}}{a{{}_{m}}}=\frac {\frac {\left ({m+1}\right )m\left ({m-1}\right )}{6\cdot 2{^{m+1}}}}{\frac {m\left ({m-1}\right )\left ({m-2}\right )}{6\cdot 2{^{m}}}}=\frac {m+1}{2m-4}$ ，
6. 其中 $m\mathrm{\geqslant }3,2m-4>0$ ．当 $m<5$ 时， $m+1>2m-4$ ，则 $a{{}_{m+1}}>a{{}_{m}}$ ；
7. 当 $m=5$ 时，有 $a{{}_{5}}=a{{}_{6}}$ ；当 $m\mathrm{\geqslant }6$ 时， $a{{}_{m+1}}<a{{}_{m}}$ ，故 $a{{}_{m}}$ 在 $m=5$ 或 $m=6$ 有最大值，
8. 则 $m$ 在 $X=3$ 下的极大似然估计为5或6．
9. （2）显然有 $m>k$ ，设 $m$ 次点击后获得的积分为随机变量 $X$ ，由题可知 $X$ 服从二项分布 $B\left ({m,p}\right )$ ，
10. 则 $P\left ({X=k}\right )={\rm{C}}{{}_{m}^{k}}p{^{k}}(1-p){^{m-k}}$ ，
11. 同（1）（ii）设 $a{{}_{m}}={\rm{C}}{{}_{m}^{k}}p{^{k}}(1-p){^{m-k}}$ ，
12. 则 $\frac {a{{}_{m+1}}}{a{{}_{m}}}=\frac {{\rm{C}}{{}_{m+1}^{k}}p{^{k}}(1-p){^{m+1-k}}}{{\rm{C}}{{}_{m}^{k}}p{^{k}}(1-p){^{m-k}}}=\frac {\frac {\left ({m+1}\right )!}{k!\left ({m+1-k}\right )!}\cdot \left ({1-p}\right )}{\frac {m!}{k!\left ({m-k}\right )!}}=$  $\frac {\left ({m+1}\right )\left ({1-p}\right )}{m-k+1}$ ．
13. 当 $\left ({1-p}\right )m+1-p<m-k+1$ ，即 $m>\frac {k}{p}-1$ 时， $a{{}_{m+1}}<a{{}_{m}}$ ，
14. 当 $m<\frac {k}{p}-1$ 时， $a{{}_{m+1}}>a{{}_{m}}$ ，当 $m=\frac {k}{p}-1$ 时， $a{{}_{m+1}}=a{{}_{m}}$ ．
15. ①：若 $\frac {k}{p}-1$ 为整数，则对 $m$ 的极大似然估计 $m{{}_{0}}$ 为 $\frac {k}{p}-1$ 和 $\frac {k}{p}$ ，满足 $m{{}_{0}}\mathrm{\leqslant }\frac {k}{p}$ ，当 $\frac {k}{p}\in {\mathbf{N}}{^{{\rm{*}}}}$ 时等号成立，
16. ②：若 $\frac {k}{p}-1$ 不为整数，记 $N$ 为小于 $\frac {k}{p}-1$ 的最大整数，则 $N+1>\frac {k}{p}-1$ ，则 $m\mathrm{\leqslant }N<\frac {k}{p}-1$ 时， $a{{}_{m+1}}>a{{}_{m}}$ ；当 $m\mathrm{\geqslant }N+1>\frac {k}{p}-1$ 时， $a{{}_{m+1}}<a{{}_{m}}$ ，
17. 则 $m$ 的极大似然估计 $m{{}_{0}}$ 为 $N+1<\frac {k}{p}$ ，故 $m{{}_{0}}\mathrm{\leqslant }\frac {k}{p}$ ，综上可知：等号能成立的条件为 $\frac {k}{p}\in {\mathbf{N}}{^{{\rm{*}}}}$ ．

## 知识点

**中文**:
  - 二项分布
  - 超几何分布

**English**:
  - Binomial Distribution
  - Hypergeometric Distribution

---
