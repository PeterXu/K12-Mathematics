# Mathematics - 题目 93

**ID**: 095fdf3198884798a84159d2ad800ba6
**年级**: Grade 11
**难度**: Medium
**题型**: Fill-in-the-blank

## 题目
已知随机变量 $X$ ， $Y$ 相互独立，且 $X\sim N\left ({4,4}\right )$ ， $Y\sim B\left ({8,\frac {1}{2}}\right )$ ，则 $P\left ({X\leqslant 4,Y\leqslant 4}\right )=$；若 $Z=X+Y$ ，则 $\sum \limits_{t=1}^{15}\mathop{P\left ({Z\leqslant t}\right )}=$.​​​​​​​‌

## 解答

1. $X\sim N\left ({4,4}\right )$ ， $P\left ({X\leqslant 4}\right )=\frac {1}{2}$ ， $Y\sim B\left ({8,\frac {1}{2}}\right )$
2. $P\left ({Y\leqslant 4}\right )=P\left ({Y=0}\right )+P\left ({Y=1}\right )+P\left ({Y=2}\right )+P\left ({Y=3}\right )+P\left ({Y=4}\right )$
3. $={\left({\frac {1}{2}}\right)^{8}}+8{\left({\frac {1}{2}}\right)^{8}}+28\times {\left({\frac {1}{2}}\right)^{8}}+56{\left({\frac {1}{2}}\right)^{8}}+70{\left({\frac {1}{2}}\right)^{8}}=163\times {\left({\frac {1}{2}}\right)^{8}}$
4. $P\left ({X\leqslant 4,Y\leqslant 4}\right )=\frac {1}{2}\times 163\times {\left({\frac {1}{2}}\right)^{8}}=\frac {163}{512}$ .
5. $\sum \limits_{t=1}^{15}\mathop{P\left ({Z\leqslant t}\right )}=\sum \limits_{{\rm{t}}=1}^{15}\mathop{P\left ({X+Y\leqslant t}\right )=P\left ({Z\leqslant 1}\right )+P\left ({Z\leqslant 2}\right )+\cdot \cdot \cdot +P\left ({Z\leqslant 15}\right )}$
6. $=P\left ({X\leqslant 1,Y=0}\right )+P\left ({X\leqslant 0,Y=1}\right )+\cdot \cdot \cdot +P\left ({X\leqslant -7,Y=8}\right )+P\left ({X\leqslant 2,Y=0}\right )$
7. $+P\left ({X\leqslant 1,Y=1}\right )+\cdot \cdot \cdot +P\left ({X\leqslant -6,Y=8}\right )+\cdots +P\left ({X\leqslant 7,Y=0}\right )+P\left ({X\leqslant 6,Y=1}\right )+\cdot \cdot \cdot $
8. $+P\left ({X\leqslant -1,Y=8}\right )+\cdot \cdot \cdot +P\left ({X\leqslant 15,Y=0}\right )+P\left ({X\leqslant 14,Y=1}\right )+\cdot \cdot \cdot +P\left ({X\leqslant 7,Y=8}\right )$
9. 并利用 $P\left ({Y=k}\right )=P\left ({Y=8-k}\right )$ ， $P\left ({X\leqslant k}\right )+P\left ({X\leqslant 8-k}\right )=1$
10. 记原式 $=S$ ，
11. 倒序相加 $\Rightarrow 15\left [P\left ({Y=0}\right )+P\left ({Y=1}\right )+\cdot \cdot \cdot +P\left ({Y=8}\right )\right ]=2S\Rightarrow S=\frac {15}{2}$ .

## 知识点

**中文**:
  - 二项分布
  - 正态曲线及其特点

**English**:
  - Binomial Distribution
  - Normal Curve and Characteristics

---
