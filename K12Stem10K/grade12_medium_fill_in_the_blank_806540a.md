# Mathematics - 题目 1188

**ID**: 806540a93bf648e0a3f904e517107ed0
**年级**: Grade 12
**难度**: Medium
**题型**: Fill-in-the-blank

## 题目
袋中装有6个相同的球，分别标有数字 $1,2,3,4,5,6$ ，从中一次性随机取出两个球，设两球标号为 $x{{}_{1}}$ 和 $y{{}_{1}}$ ，并记 $u{{}_{1}}=x{{}_{1}}+y{{}_{1}},v{{}_{1}}=\left |{x{{}_{1}}-y{{}_{1}}}\right |$ .​​​​​​​‌将球放回袋中，重复上述操作，得到 $u{{}_{2}}$ 和 $v{{}_{2}}$ .记 $t{{}_{i}}=\frac {u{{}_{i}}}{v{{}_{i}}}$ ，其中 $i=1,2$ ，则 $t{{}_{1}}=t{{}_{2}}$ 的概率为.

## 解答

1. 每一次取球时，标号组合 $\left ({x,y}\right )$ 都有 ${\rm{C}}{{}_{6}^{2}}=15$ 种等可能的组合情况，
2. 其对应的样本空间为：
3. ${\rm{Ω}}=\left \{\left ({1,2}\right ),\left ({1,3}\right ),\left ({1,4}\right ),\left ({1,5}\right ),\left ({1,6}\right ),\left ({2,3}\right ),\left ({2,4}\right ),\left ({2,5}\right ),\left ({2,6}\right ),\left ({3,4}\right ),\left ({3,5}\right ),\left ({3,6}\right ),\left ({4,5}\right ),\left ({4,6}\right ),\left ({5,6}\right )\right \}$ .
4. 下面分析每一个样本点对应的情况：
5. $\left ({1,2}\right ):u=3,v=1,t=3;\left ({1,3}\right ):u=4,v=2,t=2{\rm{;}}$
6. $\left ({1,4}\right ):u=5,v=3,t=\frac {5}{3};\left ({1,5}\right ):u=6,v=4,t=\frac {3}{2}$ ；
7. $\left ({1,6}\right ):u=7,v=5,t=\frac {7}{5};\left ({2,3}\right ):u=5,v=1,t=5$ ；
8. $\left ({2,4}\right ):u=6,v=2,t=3;\left ({2,5}\right ):u=7,v=3,t=\frac {7}{3};$
9. $\left ({2,6}\right ):u=8,v=4,t=2;\left ({3,4}\right ):u=7,v=1,t=7$ ；
10. $\left ({3,5}\right ):u=8,v=2,t=4;\left ({3,6}\right ):u=9,v=3,t=3$ ；
11. $\left ({4,5}\right ):u=9,v=1,t=9;\left ({4,6}\right ):u=10,v=2,t=5$ ；
12. $\left ({5,6}\right ):u=11,v=1,t=11$ .
13. 记 $t{{}_{1}}=t{{}_{2}}$ 为事件 $\mathrm{A}$ ，则 $P\left ({A}\right )=P\left ({t{{}_{1}}=t{{}_{2}}=3}\right )+\left [P\left ({t{{}_{1}}=t{{}_{2}}=2}\right )+P\left ({t{{}_{1}}=t{{}_{2}}=5}\right )\right ]+$  $[P\left ({t{{}_{1}}=t{{}_{2}}=\frac {5}{3}}\right )+P\left ({t{{}_{1}}=t{{}_{2}}=\frac {3}{2}}\right )+P\left ({t{{}_{1}}=t{{}_{2}}=\frac {7}{5}}\right )+P\left ({t{{}_{1}}=t{{}_{2}}=\frac {7}{3}}\right )$
14. $+P\left ({t{{}_{1}}=t{{}_{2}}=7}\right )+P\left ({t{{}_{1}}=t{{}_{2}}=4}\right )+P\left ({t{{}_{1}}=t{{}_{2}}=9}\right )+P\left ({t{{}_{1}}=t{{}_{2}}=11}\right )]$
15. $={\left({\frac {3}{15}}\right)^{2}}+{\left({\frac {2}{15}}\right)^{2}}\times 2+{\left({\frac {1}{15}}\right)^{2}}\times 8=\frac {1}{9}$ .
16. 故答案为： $\frac {1}{9}$

## 知识点

**中文**:
  - 古典概型的概率计算

**English**:
  - Calculation of Classical Probability

---
