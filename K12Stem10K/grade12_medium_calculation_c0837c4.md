# Mathematics - 题目 1159

**ID**: c0837c41e8ed4ed5a795c1f73f8d296f
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
数学的发展推动着科技的进步，正是基于线性代数、群论等数学知识的极化码原理的应用，华为的5G技术领先世界．目前某区域市场中5G智能终端产品的制造由A公司及B公司提供技术支持．据市场调研预测，5G商用初期，该区域市场中采用A公司与B公司技术的智能终端产品分别占比 $a_{0}=55\%$ 及 $b_{0}=45\%$ ，假设两家公司的技术更新周期一致，且随着技术优势的体现每次技术更新后，上一周期采用B公司技术的产品中有20%转而采用A公司技术，采用A公司技术的仅有5%转而采用B公司技术，设第n次技术更新后，该区域市场中采用A公司与B公司技术的智能终端产品占比分别为 $a_{n}$ 及 $b_{n}$ ，不考虑其它因素的影响．(1)用 $b_{n}$ 表示 $b_{n+1}$ ，并求实数 $λ$ ，使 $\left\{\begin{array}{l}b_{n}-λ\end{array}\right \}$ 是等比数列；(2)经过若干次技术更新后，该区域市场采用A公司技术的智能终端产品占比能否达到75%以上？若能，至少需要经过几次技术更新；若不能，说明理由？（参考数据： ${\lg}2\approx 0.​​​​​​​‌301,{\lg}3\approx 0.477$ ）

## 解答

1. （1）由题意，可设5G商用初期，该区域市场中采用A公司与B公司技术的智能终端产品的占比分别为 $a_{0}=55\%=\frac {11}{20},\quad b_{0}=45\%=\frac {9}{20}$ ．
2. 易知经过 $n$ 次技术更新后 $a_{n}+b_{n}=1$ ，
3. 则 $b_{n+1}=(1-20\%)b_{n}+5\%\cdot a_{n}=\frac {4}{5}b_{n}+\frac {1}{20}\left ({1-b_{n}}\right )=\frac {3}{4}b_{n}+\frac {1}{20}$ ，即 $b_{n+1}=\frac {3}{4}b_{n}+\frac {1}{20}$ ，
4. 由题意，可设 $b_{n+1}-λ=\frac {3}{4}\left ({b_{n}-λ}\right )\Leftrightarrow b_{n+1}=\frac {3}{4}b_{n}+\frac {λ}{4}$ ，
5. 所以 $\frac {λ}{4}=\frac {1}{20}\Rightarrow λ=\frac {1}{5}$ ，
6. 又 $b_{1}=\frac {3}{4}b_{0}+\frac {1}{20}=\frac {3}{4}\times \frac {9}{20}+\frac {1}{20}=\frac {31}{80},b_{1}-\frac {1}{5}=\frac {31}{80}-\frac {1}{5}=\frac {3}{16}$ ，
7. 从而当 $λ{\rm{=}}\frac {1}{5}$ 时， $\left\{\begin{array}{l}b_{n}-\frac {1}{5}\end{array}\right \}$ 是以 $\frac {3}{16}$ 为首项， $\frac {3}{4}$ 为公比的等比数列．
8. （2）由（1）可知 $b_{n}-\frac {1}{5}=\frac {3}{16}\cdot \left ({\frac {3}{4}}\right )^{n-1}=\frac {1}{4}\cdot \left ({\frac {3}{4}}\right )^{n}$ ， $b_{n}=\frac {1}{5}+\frac {1}{4}\cdot \left ({\frac {3}{4}}\right )^{n}$ ，
9. 又 $a_{n}+b_{n}=1$ ，则 $a_{n}=\frac {4}{5}-\frac {1}{4}\cdot \left ({\frac {3}{4}}\right )^{n}$ ，
10. 所以经过 $n$ 次技术更新后，该区域市场采用A公司技术的智能终端产品占比 $a_{n}=\frac {4}{5}-\frac {1}{4}\cdot \left ({\frac {3}{4}}\right )^{n}$ ．
11. 由题意，令 $a_{n}>75\%$ ，得 $\frac {4}{5}-\frac {1}{4}\cdot \left ({\frac {3}{4}}\right )^{n}>\frac {3}{4}\Leftrightarrow \left ({\frac {3}{4}}\right )^{n}<\frac {1}{5}\Leftrightarrow n{\lg}\frac {3}{4}<{\lg}\frac {1}{5}$ ，
12. 则 $n>\frac {-{\lg}5}{{\lg}3-2{\lg}2}=\frac {{\lg}5}{2{\lg}2-{\lg}3}=\frac {1-{\lg}2}{2{\lg}2-{\lg}3}\approx \frac {1-0.301}{2\times 0.301-0.477}$  $=\frac {0.699}{0.125}=5.592$ ，
13. 故 $n\geqslant 6$ ，即至少经过6次技术更新，该区域市场采用A公司技术的智能终端产品占比能达到75%以上．

## 知识点

**中文**:
  - 等比数列模型

**English**:
  - Geometric Sequence Models

---
