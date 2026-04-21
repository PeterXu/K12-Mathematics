# Mathematics - 题目 2481

**ID**: 87cf29cfb03e41cc9730ca59905f3353
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
某公司为了解旗下某产品的客户反馈情况，随机抽选了250名客户体验该产品并进行评价，评价结果为“喜欢”和“不喜欢”，整理得到如下列联表.​​​​​​​‌不喜欢喜欢合计男50100150女5050100合计100150250(1)是否有 $99{\rm{\%}}$ 的把握认为客户对该产品评价结果与性别因素有关系？(2)公司为进一步了解客户对产品的反馈，现从参与评价的女性客户中，按评价结果用分层抽样的方法随机抽取了4人，收集对该产品改进建议．已知评价结果为“喜欢”的客户的建议被采用的概率为 $\frac {2}{3}$ ，评价结果为“不喜欢”的客户的建议被采用的概率为 $\frac {1}{2}$ ．若“建议”被采用，则赠送价值200元的纪念品，“建议”未被采用，则赠送价值100元的纪念品．记这4人获得的纪念品的总金额为 $ξ$ ，求 $ξ$ 的分布列及数学期望．附： $K{^{2}}=\frac {n(ad-bc){^{2}}}{\left ({a+b}\right )\left ({c+d}\right )\left ({a+c}\right )\left ({b+d}\right )}$ ，$P\left ({K{^{2}}\geqslant k}\right )$0.100.050.0100.001$k$2.7063.8416.63510.828

## 解答

1. （1）解：由题意，根据 $2\times 2$ 的列联表中的数据，
2. 可得 $K{^{2}}=\frac {250(50\times 50-50\times 100){^{2}}}{100\times 150\times 150\times 100}\approx 6.94>6.635$ ，
3. 所以有 $99{\rm{\%}}$ 的把握认为客户对该产品评价结果与性别因素有关系．
4. （2）解：由题意知，选取的4人中，评价结果为“喜欢”和“不喜欢”的分别有2人，
5. 所以 $ξ$ 的所有可能取值为 $400,500,600,700,800$ ，
6. 则 $P\left ({ξ=400}\right )={\left({\frac {1}{3}}\right)^{2}}\times {\left({\frac {1}{2}}\right)^{2}}=\frac {1}{36}$ ，
7. $P\left ({ξ=500}\right )={\rm{C}}{{}_{2}^{1}}\times \frac {1}{3}\times \frac {2}{3}\times {\left({\frac {1}{2}}\right)^{2}}+{\left({\frac {1}{3}}\right)^{2}}\times {\rm{C}}{{}_{2}^{1}}\times {\left({\frac {1}{2}}\right)^{2}}=\frac {6}{36}=\frac {1}{6}$ ,
8. $P\left ({ξ=600}\right )={\rm{C}}{{}_{2}^{1}}\times \frac {1}{3}\times \frac {2}{3}\times {\rm{C}}{{}_{2}^{1}}{\left({\frac {1}{2}}\right)^{2}}+{\left({\frac {2}{3}}\right)^{2}}\times {\left({\frac {1}{2}}\right)^{2}}+{\left({\frac {1}{3}}\right)^{2}}\times {\left({\frac {1}{2}}\right)^{2}}=\frac {13}{36}$ ，
9. $P\left ({ξ=700}\right )={\rm{C}}{{}_{2}^{1}}\times \frac {1}{3}\times \frac {2}{3}\times {\left({\frac {1}{2}}\right)^{2}}+{\left({\frac {2}{3}}\right)^{2}}\times {\rm{C}}{{}_{2}^{1}}\times {\left({\frac {1}{2}}\right)^{2}}=\frac {12}{36}=\frac {1}{3}$ ，
10. $P\left ({ξ=800}\right )={\left({\frac {2}{3}}\right)^{2}}\times {\left({\frac {1}{2}}\right)^{2}}=\frac {4}{36}=\frac {1}{9}$ ，
11. 则随机变量 $ξ$ 的分布列为
12. $ξ$
13. 400
14. 500
15. 600
16. 700
17. 800
18. $P$
19. $\frac {1}{36}$
20. $\frac {1}{6}$
21. $\frac {13}{36}$
22. $\frac {1}{3}$
23. $\frac {1}{9}$
24. 所以数学期望为 $E\left ({ξ}\right )=400\times \frac {1}{36}+500\times \frac {6}{36}+600\times \frac {13}{36}+700\times \frac {12}{36}+800\times \frac {4}{36}=\frac {1900}{3}$ ．

## 知识点

**中文**:
  - 独立性检验的应用
  - 离散型随机变量的分布列

**English**:
  - Applications of Independence Test
  - Probability Distribution Table

---
