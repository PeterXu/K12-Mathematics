# Mathematics - 题目 2476

**ID**: 27a34037a9d9447f92ee735711136b44
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
第九届亚洲冬季运动会，将于2025年2月7日至2月14日在黑龙江省哈尔滨市举办，这是继2022年北京冬奥会之后中国举办的又一重大国际综合性冰雪盛会，为加强学生对冰雪项目的了解，某省重点高中拟组织一次冰雪知识测试，该校从全校学生中随机抽取30人进行模拟测试，其中高一学年组12人，高二学年组10人，高三学年组8人，测试共分为两轮．（1）第一轮测试按高一、高二、高三3个小组顺次进行，若一切正常，则该小组完成测试的时间为20分钟；​​​​​​​‌若出现异常情况，则该小组需要延长5分钟才能完成测试．已知每一小组正常完成测试的概率均为 $\frac {3}{4}$ ，且各小组是否正常完成测试互不影响．记3个小组全部完成测试所需总时间为X，求X的分布列；（2）第二轮测试为面试，将3组同学一起进行排序，每位同学按排序顺次进行面试，且每人面试时间相等．①求最后一名同学来自高一学年组的条件下，高二学年组同学比高三学年组同学提前完成面试的概率；②若所有参加面试的同学都可以得到一枚“雪花摩天轮”冰箱贴，成绩优秀的同学还可以多得一枚“雪花摩天轮”冰箱贴，已知每一名同学面试成绩优秀的概率均为 $\frac {1}{4}$ ，设这30名同学所得冰箱贴总数恰好为n个的概率为 $P{{}_{n}}$ ，当 $P{{}_{n}}$ 取最大值时，求n的值．

## 解答

1. （1）由题意得，X的取值可以为 $60,65,70,75$ ，
2. $P\left ({X=60}\right )={\left({\frac {3}{4}}\right)^{3}}=\frac {27}{64}$ ， $P\left ({X=65}\right )={\rm{C}}{{}_{3}^{2}}\times {\left({\frac {3}{4}}\right)^{2}}\times \left ({1-\frac {3}{4}}\right )=\frac {27}{64}$ ，
3. $P\left ({X=70}\right )={\rm{C}}{{}_{3}^{1}}\times \frac {3}{4}\times {\left({1-\frac {3}{4}}\right)^{2}}=\frac {9}{64}$ ， $P\left ({X=75}\right )={\left({1-\frac {3}{4}}\right)^{3}}=\frac {1}{64}$ .
4. X的分布列：
5. X
6. 60
7. 65
8. 70
9. 75
10. P
11. $\frac {27}{64}$
12. $\frac {27}{64}$
13. $\frac {9}{64}$
14. $\frac {1}{64}$
15. （2）①设事件 $M$ ：最后一名同学来自高一学年组；事件 $N$ ：高二学年组同学比高三学年组同学提前完成面试，
16. 则 $P\left ({M}\right )=\frac {{\rm{C}}{{}_{12}^{1}}\cdot {\rm{A}}{{}_{29}^{29}}}{{\rm{A}}{{}_{30}^{30}}}=\frac {12\times 29!}{30!}$ ， $P\left ({NM}\right )=\frac {{\rm{C}}{{}_{12}^{1}}\cdot {\rm{A}}{{}_{29}^{11}}\cdot {\rm{A}}{{}_{17}^{10}}\cdot {\rm{A}}{{}_{8}^{8}}}{{\rm{A}}{{}_{30}^{30}}}=\frac {12\times \frac {29!}{18!}\times \frac {17!}{7!}\times 8!}{30!}=\frac {12\times 29!\times 17!\times 8!}{30!\times 18!\times 7!}$ ，
17. ∴ $P\left ({N/M}\right )=\frac {P\left ({NM}\right )}{P\left ({M}\right )}=\frac {\frac {12\times 29!\times 17!\times 8!}{30!\times 18!\times 7!}}{\frac {12\times 29!}{30!}}=\frac {8}{18}=\frac {4}{9}$ ，
18. ∴最后一名同学来自高一学年组的条件下，高二学年组同学比高三学年组同学提前完成面试的概率为 $\frac {4}{9}$ .
19. ②由题意得， $30\leqslant n\leqslant 60$ ， $n\in {\mathbf{N}}{^{*}}$ , $P{{}_{n}}={\rm{C}}{{}_{30}^{n-30}}\cdot {\left({\frac {1}{4}}\right)^{n-30}}\cdot {\left({\frac {3}{4}}\right)^{60-n}}=\frac {30!}{\left ({n-30}\right )!\left ({60-n}\right )!}\cdot {\left({\frac {1}{4}}\right)^{n-30}}\cdot {\left({\frac {3}{4}}\right)^{60-n}}$ ，
20. ∴ $\frac {P{{}_{n+1}}}{P{{}_{n}}}=\frac {\frac {30!}{\left ({n-29}\right )!\left ({59-n}\right )!}\cdot {\left({\frac {1}{4}}\right)^{n-29}}\cdot {\left({\frac {3}{4}}\right)^{59-n}}}{\frac {30!}{\left ({n-30}\right )!\left ({60-n}\right )!}\cdot {\left({\frac {1}{4}}\right)^{n-30}}\cdot {\left({\frac {3}{4}}\right)^{60-n}}}=\frac {60-n}{3\left ({n-29}\right )}$ ，
21. 由 $\frac {P{{}_{n+1}}}{P{{}_{n}}}>1$ 得， $n<36\frac {3}{4}$ ，由 $\frac {P{{}_{n+1}}}{P{{}_{n}}}<1$ 得， $n>36\frac {3}{4}$ ，
22. ∴当 $30\leqslant n\leqslant 36$ ， $n\in {\mathbf{N}}{^{*}}$ 时， $P{{}_{n+1}}>P{{}_{n}}$ ，当 $37\leqslant n\leqslant 59$ ， $n\in {\mathbf{N}}{^{*}}$ 时， $P{{}_{n+1}}<P{{}_{n}}$ ,
23. ∴当 $P{{}_{n}}$ 取最大值时， $n=37$ .

## 知识点

**中文**:
  - 二项分布
  - 离散型随机变量的分布列
  - 条件概率

**English**:
  - Binomial Distribution
  - Probability Distribution Table
  - Conditional Probability

---
