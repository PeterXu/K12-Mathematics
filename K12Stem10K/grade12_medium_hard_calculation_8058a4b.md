# Mathematics - 题目 2089

**ID**: 8058a4b531d64c93b2fe8124872309d7
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
某企业举办企业年会，并在年会中设计了抽奖环节和游戏环节．(1)抽奖环节：该企业每位员工在年会上都会得到相应的奖金X（单位：千元），其奖金的平均值为 $\bar X=30$ ，标准差为 $s=5$ ．经分析，X近似服从正态分布 $N\left ({μ,σ{^{2}}}\right )$ ，用奖金的平均值 $\bar X$ 作为 $μ$ 的近似值，用奖金的标准差s作为 $σ$ 的近似值，现任意抽取一位员工，求他所获得奖金在 $[35,40)$ 的概率；(2)游戏环节：从员工中随机抽取40名参加投掷游戏，每位员工只能参加一次，并制定游戏规则如下：参与者掷一枚骰子，初始分数为0，每次所得点数大于4，得2分，否则，得1分．连续投掷累计得分达到9或10时，游戏结束．①设员工在游戏过程中累计得n分的概率为 $P{{}_{n}}$ ，求 $P{{}_{n}}$ ；②得9分的员工，获得二等奖，奖金1000元，得10分的员工，获得一等奖，奖金2000元，估计该企业作为游戏奖励的预算资金（精确到1元）．（参考数据： $P(μ-σ\leqslant x\leqslant μ+σ)=0.​​​​​​​‌6827,P(μ-2σ\leqslant x\leqslant μ+2σ)=0.9545$ ， $P\left ({μ-3σ\leqslant x\leqslant μ+3σ)=0.9973,\frac {1}{3{^{8}}}=1.524\times 10{^{-1}},\frac {1}{3{^{9}}}=5.081\times 10{^{-{{5}}}},\frac {1}{3{^{10}}}=1.694\times 10{^{-5}}}\right )$ ．

## 解答

1. （1）由题意知 $X\sim N\left ({30,5{^{2}}}\right )$ ，
2. 则 $P(35\leqslant x<40)=P(u+σ\leqslant x<u+2σ)=\frac {0.9545-0.6827}{2}=0.1359$ ．
3. （2）①由题知，累计获得 $n$ 分时有可能是获得 $n-1$ 分时掷骰子点数小于等于4或获得 $n-2$ 分时掷骰子点数大于4，而掷骰子点数小于等于4的概率为 $\frac {2}{3}$ ，掷骰子点数大于4的概率为 $\frac {1}{3}$ ．
4. $P{{}_{n}}=\frac {2}{3}P{{}_{n-1}}+\frac {1}{3}P{{}_{n-2}}$  $\left ({n\geqslant 3}\right )$ ，
5. 则 $P{{}_{n}}-P{{}_{n-1}}=\frac {2}{3}P{{}_{n-1}}+\frac {1}{3}P{{}_{n-2}}-P{{}_{n-1}}=-\frac {1}{3}\left ({P{{}_{n-1}}-P{{}_{n-2}}}\right )$ ， $n\geqslant 3$
6. 故 $\left \{P{{}_{n}}-P{{}_{n-1}}\right \}$  $\left ({n\geqslant 2}\right )$ 为等比数列.
7. 由 $P{{}_{1}}=\frac {2}{3}$ ， $P{{}_{2}}=\frac {1}{3}+\frac {2}{3}\cdot \frac {2}{3}=\frac {7}{9}$ ，故首项为 $\frac {7}{9}-\frac {2}{3}=\frac {1}{9}$ .
8. 因此 $P{{}_{n}}-P{{}_{n-1}}=\frac {1}{9}{\left({-\frac {1}{3}}\right)^{n-1}}$ ， $P{{}_{n-1}}-P{{}_{n-2}}=\frac {1}{9}{\left({-\frac {1}{3}}\right)^{n-2}}$ …… $P{{}_{2}}-P{{}_{1}}=\frac {1}{9}$ ，
9. 将所有等式相加得 $P{{}_{n}}-P{{}_{1}}=\frac {1}{9}\cdot \frac {1\cdot \left ({1-{\left({-\frac {1}{3}}\right)^{n-1}}}\right )}{1-\left ({-\frac {1}{3}}\right )}=\frac {1-{\left({-\frac {1}{3}}\right)^{n-1}}}{12}$ ，
10. 所以 $P{{}_{n}}=\frac {1-{\left({-\frac {1}{3}}\right)^{n-1}}}{12}+\frac {2}{3}=\frac {3}{4}+\frac {1}{4}\times {\left({-\frac {1}{3}}\right)^{n}}\left ({1\leqslant n\leqslant 9}\right )$ ，
11. 当 $n=10$ 时， $P{{}_{10}}=\frac {1}{3}P{{}_{8}}=\frac {1}{3}\times \left ({\frac {3}{4}+\frac {1}{4}\times {\left({-\frac {1}{3}}\right)^{8}}}\right )=\frac {1}{4}-\frac {1}{4}\times {\left({-\frac {1}{3}}\right)^{9}}$
12. 综上 $P{{}_{n}}=-\begin{cases}\frac {3}{4}+\frac {1}{4}\times {\left({-\frac {1}{3}}\right)^{n}},1\leqslant n\leqslant 9\\\frac {1}{4}-\frac {1}{4}\times {\left({-\frac {1}{3}}\right)^{9}},n=10\end{cases}$ .
13. ② $S=1000\times 40\times P{{}_{9}}+2000\times 40\times P{{}_{10}}$
14. $=40000\times \left [\frac {3}{4}+\frac {1}{4}\left ({-5.081\times 10{^{-5}}}\right )\right ]+80000\times \left [\frac {1}{4}-\frac {1}{4}\left ({-5.081\times 10{^{-5}}}\right )\right ]\approx 50001$ 元．
15. 即估计游戏奖励的预算资金为50001元．

## 知识点

**中文**:
  - 数列通项求法之累加法
  - 正态曲线及其特点

**English**:
  - Accumulation Method (Telescoping Sums)
  - Normal Curve and Characteristics

---
