# Mathematics - 题目 1102

**ID**: 141f6e6268474e33b833d97e7420cbbf
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
2006年，在国家节能减排的宏观政策指导下，科技部在“十一五”启动了“863”计划新能源汽车重大项目.​​​​​​​‌自2011年起，国家相关部门重点扶持新能源汽车的发展，也逐步得到消费者的认可.如下表是统计的2014年−2023年全国新能源汽车保有量(百万辆)数据：年份代码 $x{{}_{i}}$12345678910年份 $t{{}_{i}}$2014201520162017201820192020202120222023保有量 $y{{}_{i}}$0.120.501.091.602.613.814.927.8413.1020.41并计算得: $\sum \limits_{i=1}^{10}\mathop{x{{}_{i}^{2}}}=385,\sum \limits_{i=1}^{10}\mathop{y{{}_{i}^{2}}}\approx 699,\sum \limits_{i=1}^{10}\mathop{x{{}_{i}}}y{{}_{i}}\approx 466,\bar x=5.5,\bar y=5.6$ .(1)根据表中数据，求相关年份与全国新能源汽车保有量的样本相关系数(精确到0.01)；(2)现苏同学购买第1辆汽车时随机在新能源汽车和非新能源汽车中选择.如果第1辆购买新能源汽车，那么第2辆仍选择购买新能源汽车的概率为0.6；如果第1辆购买非新能源汽车，那么第2辆购买新能源汽车的概率为0.8，计算苏同学第2辆购买新能源汽车的概率；(3)某汽车网站为调查新能源汽车车主的用车体验，决定从12名候选车主中选3名车主进行访谈，已知有4名候选车主是新能源汽车车主，假设每名候选人都有相同的机会被选到，求被选到新能源汽车车主的分布列及数学期望.附:相关系数： $r=\frac {\sum \limits_{i=1}^{n}\mathop{\left ({x{{}_{i}}-\bar x}\right )}\left ({y{{}_{i}}-\bar y}\right )}{\sqrt {\sum \limits_{i=1}^{n}\mathop{{\left({x{{}_{i}}-\bar x}\right)^{2}}}\sum \limits_{i=1}^{n}\mathop{{\left({y{{}_{i}}-\bar y}\right)^{2}}}}},\sqrt {31795.5}\approx 178$ .

## 解答

1. （1）由 $\sum \limits_{i=1}^{10}\mathop{x{{}_{i}^{2}}}=385,\sum \limits_{i=1}^{10}\mathop{y{{}_{i}^{2}}}\approx 699,\sum \limits_{i=1}^{10}\mathop{x{{}_{i}}}y{{}_{i}}\approx 466,\bar x=5.5,\bar y=5.60$ ，
2. 则 $r=\frac {\sum\limits_{i=1}^{n}\mathop{}\left ({x{{}_{i}}-\bar x}\right )\left ({y{{}_{i}}-\bar y}\right )}{\sqrt {\sum\limits_{i=1}^{n}\mathop{}{\left({x{{}_{i}}-\bar x}\right)^{2}}\sum\limits_{i=1}^{n}\mathop{}{\left({y{{}_{i}}-\bar y}\right)^{2}}}}=\frac {\sum\limits_{i=1}^{n}\mathop{}x{{}_{i}}y{{}_{i}}-n\bar x\bar y}{\sqrt {\left ({\sum\limits_{i=1}^{n}\mathop{}x{{}_{i}^{2}}-n\bar x{^{2}}}\right )\left ({\sum\limits_{i=1}^{n}\mathop{}y{{}_{i}^{2}}-n\bar y{^{2}}}\right )}}=\frac {466-10\times 5.5\times 5.6}{\sqrt {\left ({385-10\times 5.5{^{2}}}\right )\left ({699-10\times 5.6{^{2}}}\right )}}\approx 0.89$ .
3. （2）设 $A{{}_{1}}=$ “第1辆购买新能源汽车”， $B{{}_{1}}=$ “第1辆购买非新能源汽车”，
4. $A{{}_{2}}=$ “第2辆购买新能源汽车”，
5. $P\left ({A{{}_{1}}}\right )=P\left ({B{{}_{1}}}\right )=0.5,P\left ({\left .{A{{}_{2}}}\right |A{{}_{1}}}\right )=0.6,P\left ({\left .{A{{}_{2}}}\right |B{{}_{1}}}\right )=0.8$ ，
6. 由全概率公式得， $P\left ({A{{}_{2}}}\right )=P\left ({A{{}_{1}}}\right )P\left ({\left .{A{{}_{2}}}\right |A{{}_{1}}}\right )+P\left ({B{{}_{1}}}\right )P\left ({\left .{A{{}_{2}}}\right |B{{}_{1}}}\right )=0.5\times 0.6+0.5\times 0.8=0.7$ ，
7. 所以苏同学第2辆购买新能源汽车的概率为 $0.7$ .
8. （3）设被选到新能源汽车车主人数为 $X$ ，则 $X$ 可能取值为 $0,1,2,3$ ，
9. $P\left ({X=0}\right )=\frac {{\rm{C}}{{}_{4}^{0}}{\rm{C}}{{}_{8}^{3}}}{{\rm{C}}{{}_{12}^{3}}}=\frac {14}{55},P\left ({X=1}\right )=\frac {{\rm{C}}{{}_{4}^{1}}{\rm{C}}{{}_{8}^{2}}}{{\rm{C}}{{}_{12}^{3}}}=\frac {28}{55}$ ，
10. $P\left ({X=2}\right )=\frac {{\rm{C}}{{}_{4}^{2}}{\rm{C}}{{}_{8}^{1}}}{{\rm{C}}{{}_{12}^{3}}}=\frac {12}{55},P\left ({X=3}\right )=\frac {{\rm{C}}{{}_{4}^{3}}{\rm{C}}{{}_{8}^{0}}}{{\rm{C}}{{}_{12}^{3}}}=\frac {1}{55}$ ，
11. 则被选到新能源汽车车主的分布列为，
12. $X$
13. 0
14. 1
15. 2
16. 3
17. $P$
18. $\frac {14}{55}$
19. $\frac {28}{55}$
20. $\frac {12}{55}$
21. $\frac {1}{55}$
22. 所以 $E\left ({X}\right )=0\times \frac {14}{55}+1\times \frac {28}{55}+2\times \frac {12}{55}+3\times \frac {1}{55}=1$ .

## 知识点

**中文**:
  - 全概率公式
  - 离散型随机变量的分布列
  - 相关系数r

**English**:
  - Law of Total Probability
  - Probability Distribution Table
  - Correlation Coefficient r

---
