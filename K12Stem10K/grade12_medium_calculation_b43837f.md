# Mathematics - 题目 3010

**ID**: b43837fa8b23420c829889d8edbf1a43
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
某学校号召学生参加“每天锻炼1小时”活动，为调查学生课后体育锻炼的情况，学校采用简单随机抽样的方法抽取80名学生，得到了表中数据：不经常锻炼经常锻炼合计男生103040女生202040合计305080（1）根据小概率值 $α=0.​​​​​​​‌01$ 的独立性检验，能否认为性别因素与学生锻炼的经常性有关系？（2）根据上表，从经常锻炼的学生中利用分层抽样的方法抽取5人，再从这5人中随机选取3人，设这3人中女生的人数为 $X$ ，求 $X$ 的分布列和期望．附： $χ{^{2}}=\frac {n{\left({ad-bc}\right)^{2}}}{\left ({a+b}\right )\left ({c+d}\right )\left ({a+c}\right )\left ({b+d}\right )},n=a+b+c+d$ ．$α$$0.1$$0.01$$0.001$$x{{}_{α}}$$2.706$$6.635$$10.828$

## 解答

1. （1）零假设为 $H{{}_{0}}$ ：性别因素与锻炼的经常性无关，
2. 因为 $χ{^{2}}=\frac {n{\left({ad-bc}\right)^{2}}}{\left ({a+b}\right )\left ({c+d}\right )\left ({a+c}\right )\left ({b+d}\right )},\,n=a+b+c+d$ ，所以 $n=80$ ， $a=10$ ， $b=30$ ， $c=20$ ， $d=20$ ，
3. 则 $ad-bc=10\times 20-30\times 20=-400$ ，则 ${\left({ad-bc}\right)^{2}}=160000$ ，
4. $a+b=40$ ， $c+d=40$ ， $a+c=30$ ， $b+d=50$ ，所以 $\left ({a+b}\right )\left ({c+d}\right )\left ({a+c}\right )\left ({b+d}\right )=40\times 40\times 30\times 50=2400000$ ，
5. 则 $χ{^{2}}=\frac {n{\left({ad-bc}\right)^{2}}}{\left ({a+b}\right )\left ({c+d}\right )\left ({a+c}\right )\left ({b+d}\right )}=\frac {80\times 160000}{2400000}\approx 5.333$ ，
6. 根据小概率值 $α=0.01$ 的独立性检验为6.635，由 $χ{^{2}}\approx 5.333<6.635$ ，
7. 因此可以认为 $H{{}_{0}}$ 成立，即不能认为性别因素与同学锻炼的经常性有关系.
8. （2）经常锻炼的学生为50人（男生30人，女生20人），按比例抽取5人，其中男生抽取3人，女生抽取2人.
9. 则 $X$ 的可能取值为：0，1，2，则：
10. $P\left ({X=0}\right )=\frac {{\rm{C}}{{}_{3}^{3}}}{{\rm{C}}{{}_{5}^{3}}}=\frac {1}{10}$ ， $P\left ({X=1}\right )=\frac {{\rm{C}}{{}_{3}^{2}}{\rm{C}}{{}_{2}^{1}}}{{\rm{C}}{{}_{5}^{3}}}=\frac {3}{5}$ ， $P\left ({X=2}\right )=\frac {{\rm{C}}{{}_{3}^{1}}{\rm{C}}{{}_{2}^{2}}}{{\rm{C}}{{}_{5}^{3}}}=\frac {3}{10}$ ，
11. 所以 $X$ 的分布列为：
12. $X$
13. 0
14. 1
15. 2
16. $P$
17. $\frac {1}{10}$
18. $\frac {3}{5}$
19. $\frac {3}{10}$
20. $E\left ({X}\right )=0\times \frac {1}{10}+1\times \frac {3}{5}+2\times \frac {3}{10}=\frac {6}{5}=1.2$

## 知识点

**中文**:
  - 独立性检验的应用
  - 离散型随机变量的分布列

**English**:
  - Applications of Independence Test
  - Probability Distribution Table

---
