# Mathematics - 题目 1257

**ID**: 6ccd3041d39a4963aa6038e967ac9f0c
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
高血压（也称血压升高），是血液在流动时对血管壁造成的压力值持续高于正常范围的现象，典型症状包括头痛、疲倦或不安、心律失常、心悸耳鸣等．最新的调查显示，中国成人高血压的患病率为 $27.​​​​​​​‌9{\rm{\%}}$ ，大概每三位成人中就有一位是高血压患者．改善生活方式和药物治疗是最常用的治疗方式，同时适当锻炼可以使血压水平下降，高血压发病率降低，控制高血压的发展．（1）某社区为鼓励和引导辖区居民积极参加体育健身活动，养成良好的锻炼习惯，开展“低碳万步走，健康在脚下”徒步走活动．下表为开展活动后近5个季度社区高血压患者的血压情况统计．季度 $x$12345血压明显降低（或治愈）人数 $y$320270210150100若血压明显降低（或治愈）人数 $y$ 与季度变量 $x$ （季度变量 $x$ 依次为 $1,2,3,4,5,\cdot \cdot \cdot $ ）具有线性相关关系，请预测第6季度血压明显降低（或治愈）的大约有多少人？（2）社区将参加徒步走活动的队员分成了甲、乙、丙三组进行挑战赛，其规则：挑战权在任何一组，该组都可向另外两组发起挑战，首先由甲组先发起挑战，挑战乙组、丙组的概率均为 $\frac {1}{2}$ ，若甲组挑战乙组，则下次挑战权在乙组．若挑战权在乙组，则挑战甲组、丙组的概率分别为 $\frac {2}{3}$ ， $\frac {1}{3}$ ；若挑战权在丙组，则挑战甲组、乙组的概率分别为 $\frac {2}{3}$ ， $\frac {1}{3}$ ．（ⅰ）经过3次挑战，求挑战权在乙组的次数 $X$ 的分布列与数学期望；（ⅱ）定义：已知数列 $\left \{a{{}_{n}}\right \}$ ，若对于任意给定的正数 $ε$ （不论它多么小），总存在正整数 $N{{}_{0}}$ ，使得当 $n>N{{}_{0}}$ 时， $\left |{a{{}_{n}}-A}\right |<ε$ （ $\mathrm{A}$ 是一个确定的实数），则称数列 $\left \{a{{}_{n}}\right \}$ 为“聚点数列”， $\mathrm{A}$ 称为数列 $\left \{a{{}_{n}}\right \}$ 的聚点．经过 $n$ 次挑战后，挑战权在甲组的概率为 $a{{}_{n}}$ ，证明数列 $\left \{a{{}_{n}}\right \}$ 为“聚点数列”，并求出聚点 $\mathrm{A}$ 的值．附：回归方程 $\hat y=\hat bx+\hat a$ 中斜率和截距的最小二乘估计公式分别为 $\hat b=\frac {\sum \limits_{i=1}^{n}\mathop{\left ({x{{}_{i}}-{\overline{x}}}\right )}\left ({y{{}_{i}}-{\overline{y}}}\right )}{\sum \limits_{i=1}^{n}\mathop{{\left({x{{}_{i}}-{\overline{x}}}\right)^{2}}}}=\frac {\sum \limits_{i=1}^{n}\mathop{x{{}_{i}}y{{}_{i}}}-n{\overline{x}}\cdot {\overline{y}}}{\sum \limits_{i=1}^{n}\mathop{x{{}_{i}^{2}}}-n{\overline{x}}{^{2}}}$ ， $\hat a={\overline{y}}-\hat b{\overline{x}}$ ．

## 解答

1. （1）由已知可得 ${\overline{x}}=\frac {1+2+3+4+5}{5}=3$ ，
2. ${\overline{y}}=\frac {320+270+210+150+100}{5}=210$ ．
3. 又因为 $\sum \limits_{i=1}^{5}\mathop{x{{}_{i}}}y{{}_{i}}=1\times 320+2\times 270+3\times 210+4\times 150+5\times 100=2590$ ，
4. $\sum \limits_{i=1}^{5}\mathop{x{{}_{i}^{2}}}=1{^{2}}+2{^{2}}+3{^{2}}+4{^{2}}+5{^{2}}=55$ ，
5. 所以 $\hat b=\frac {\sum \limits_{i=1}^{5}\mathop{x{{}_{i}}}y{{}_{i}}-5{\overline{x}}{\overline{y}}}{\sum \limits_{i=1}^{5}\mathop{x{{}_{i}^{2}}}-5{\overline{x}}{^{2}}}=\frac {2590-3150}{55-45}=-56$ ，
6. 所以 $\hat a={\overline{y}}-\hat b{\overline{x}}=210+56\times 3=378$ ，
7. 所以 $\hat y=-56x+378$ ，
8. 当 $x=6$ 时， $\hat y=-56\times 6+378=42$ ，
9. 所以预测第6季度血压明显降低（或治愈）的大约有42人．
10. （2）（ⅰ）由题知 $X$ 的所有可能取值为0，1，2，
11. $P\left ({X=0}\right )=\frac {1}{2}\times \frac {2}{3}\times \frac {1}{2}=\frac {1}{6}$ ；
12. $P\left ({X=1}\right )=\frac {1}{2}\times \frac {2}{3}\times \frac {1}{2}+\frac {1}{2}\times \frac {1}{3}\times \frac {2}{3}+\frac {1}{2}\times \frac {1}{3}+\frac {1}{2}\times \frac {2}{3}\times \frac {1}{2}=\frac {11}{18}$ ；
13. $P\left ({X=2}\right )=\frac {1}{2}\times \frac {2}{3}\times \frac {1}{2}+\frac {1}{2}\times \frac {1}{3}\times \frac {1}{3}=\frac {2}{9}$ ，
14. 所以 $X$ 的分布列为
15. $X$
16. 0
17. 1
18. 2
19. $P$
20. $\frac {1}{6}$
21. $\frac {11}{18}$
22. $\frac {2}{9}$
23. 所以 $E\left ({X}\right )=0\times \frac {1}{6}+1\times \frac {11}{18}+2\times \frac {2}{9}=\frac {19}{18}$ ．
24. （ⅱ）设经过 $n$ 次挑战后，挑战权在乙、丙组的概率分别为 $b{{}_{n}}$ ， $c{{}_{n}}$ ，
25. 则当 $n\mathrm{\geqslant }2$ 时， $a{{}_{n}}=\frac {2}{3}b{{}_{n-1}}+\frac {2}{3}c{{}_{n-1}}$ ， $b{{}_{n}}=\frac {1}{2}a{{}_{n-1}}+\frac {1}{3}c{{}_{n-1}}$ ， $c{{}_{n}}=\frac {1}{2}a{{}_{n-1}}+\frac {1}{3}b{{}_{n-1}}$ ，
26. 由后两个等式相加，得 $b{{}_{n}}+c{{}_{n}}=a{{}_{n-1}}+\frac {1}{3}\left ({b{{}_{n-1}}+c{{}_{n-1}}}\right )$ ．  ①
27. 因为 $a{{}_{n}}=\frac {2}{3}b{{}_{n-1}}+\frac {2}{3}c{{}_{n-1}}$ ，所以 $b{{}_{n-1}}+c{{}_{n-1}}=\frac {3}{2}a{{}_{n}}$ ， $b{{}_{n}}+c{{}_{n}}=\frac {3}{2}a{{}_{n+1}}$ ，
28. 代入①式得 $\frac {3}{2}a{{}_{n+1}}=a{{}_{n-1}}+\frac {1}{2}a{{}_{n}}$ ，
29. 即 $a{{}_{n+1}}=\frac {1}{3}a{{}_{n}}+\frac {2}{3}a{{}_{n-1}}\left ({n\geqslant 2}\right )$ ，
30. 所以 $a{{}_{n+1}}+\frac {2}{3}a{{}_{n}}=a{{}_{n}}+\frac {2}{3}a{{}_{n-1}}=\cdot \cdot \cdot =a{{}_{2}}+\frac {2}{3}a{{}_{1}}$ ．
31. 因为 $a{{}_{1}}=0$ ， $a{{}_{2}}=\frac {1}{2}\times \frac {2}{3}+\frac {1}{2}\times \frac {2}{3}=\frac {2}{3}$ ，
32. 所以 $a{{}_{n+1}}+\frac {2}{3}a{{}_{n}}=\frac {2}{3}$ ，
33. 所以$a{{}_{n+1}}-\frac {2}{5}=-\frac {2}{3}\left ({a{{}_{n}}-\frac {2}{5}}\right )$ ，
34. 所以数列 $\left \{a{{}_{n}}-\frac {2}{5}\right \}$ 是首项为 $-\frac {2}{5}$ ，公比为 $-\frac {2}{3}$ 的等比数列，
35. 所以 $a{{}_{n}}-\frac {2}{5}=\left ({-\frac {2}{5}}\right ){\left({-\frac {2}{3}}\right)^{n-1}}$ ，
36. 即 $a{{}_{n}}=\frac {2}{5}-\frac {2}{5}{\left({-\frac {2}{3}}\right)^{n-1}}$ ，
37. 所以由 $\left |{a{{}_{n}}-\frac {2}{5}}\right |<ε$ ，得 $\frac {2}{5}{\left({\frac {2}{3}}\right)^{n-1}}<ε$ ，即 $n-1>{\rm{l}}{\rm{o}}{\rm{g}}{{}_{\frac {2}{3}}}\left ({\frac {5}{2}ε}\right )$ ，
38. 所以对任意给定的正数 $ε$ （不论它多么小），总存在正整数 $N{{}_{0}}=\left [{\rm{l}}{\rm{o}}{\rm{g}}{{}_{\frac {2}{3}}}\left ({\frac {5}{2}ε}\right )+1\right ]$ （ $\left [x\right ]$ 表示不超过 $x$ 的最大整数），使得当 $n>N{{}_{0}}$ 时， $\left |{a{{}_{n}}-\frac {2}{5}}\right |=$  $\left |{\frac {2}{5}\cdot {\left({\frac {2}{3}}\right)^{n-1}}}\right |<\frac {2}{5}\cdot \left ({\frac {2}{3}}\right ){^{{\rm{l}}{\rm{o}}{\rm{g}}{{}_{\frac {2}{3}}}\left ({\frac {5}{2}ε}\right )}}=ε$ ，
39. 所以数列 $\left \{a{{}_{n}}\right \}$ 为“聚点数列”，聚点 $\mathrm{A}$ 的值为 $\frac {2}{5}$ ．

## 知识点

**中文**:
  - 回归直线与回归方程
  - 数列新定义问题
  - 离散型随机变量的分布列
  - 最小二乘法

**English**:
  - Regression Line and Equation
  - New Definition Problems
  - Probability Distribution Table
  - Least Squares Method

---
