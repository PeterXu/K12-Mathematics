# Mathematics - 题目 375

**ID**: dbe090e56ffc4a7c94816a81ac8a167b
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
第24届冬奥会于2022年2月4日在北京市和张家口市联合举行，此项赛事大大激发了国人冰雪运动的热情．某滑雪场在冬奥会期间开业，下表统计了该滑雪场开业第 ${\rm \mathit{x}}$ 天的滑雪人数y（单位：百人）的数据．天数代码 ${\rm \mathit{x}}$1234567滑雪人数y（百人）11131615202123(1)根据第1至7天的数据分析，可用线性回归模型拟合 ${\rm \mathit{y}}$ 与 ${\rm \mathit{x}}$ 的关系，请用相关系数加以说明（保留两位有效数字）；(2)经过测算，若一天中滑雪人数超过3000人时，当天滑雪场可实现盈利，请建立 ${\rm \mathit{y}}$ 关于 ${\rm \mathit{x}}$ 的回归方程，并预测该滑雪场开业的第几天开始盈利．附注：参考公式： $\sum\limits_{i=1}^{7}{x}_{i}{y}_{i}=532{\rm ，}$  $\sqrt{\sum\limits_{i=1}^{7}{\left({x}_{i}-\overline{x}\right)^{2}}\sum\limits_{i=1}^{7}{\left({y}_{i}-\overline{y}\right)^{2}}}\approx 57.​​​​​​​‌5$ ．参考公式：①对于一组数据 $({u}_{1},{v}_{1}){\rm ，}$  $({u}_{2},{v}_{2}){\rm ，}$ $\cdots$ ${\rm ，}({u}_{n},{v}_{n}){\rm ，}$ 其相关系数 $r=\frac{\sum\limits_{i=1}^{n}({u}_{i}-\overline{u})({v}_{i}-\overline{v})}{\sqrt{\sum\limits_{i=1}^{n}{\left({u}_{i}-\overline{u}\right)^{2}}\sum\limits_{i=1}^{n}{\left({v}_{i}-\overline{v}\right)^{2}}}}$ ；②对于一组数据 $({u}_{1},{v}_{1}){\rm ，}$  $({u}_{2},{v}_{2}){\rm ，}$ $\cdots$${\rm ，}({u}_{n},{v}_{n}){\rm ，}$ 其回归直线 $\hat{v}=\hat{a}+\hat{b}u$ 的斜率和截距的最小二乘估计分别为 $\hat{b}=\frac{\sum\limits_{i=1}^{n}({u}_{i}-\overline{u})({v}_{i}-\overline{v})}{\sum\limits_{i=1}^{n}{\left({u}_{i}-\overline{u}\right)^{2}}}{\rm ，}$  $\hat{a}=\overline{v}-\hat{b}\overline{u}$ ．

## 解答

1. （1）根据表中数据可得${\overline{x}}=4{\rm ，}$  $\overline{y}=17{\rm ，}$
2. 所以 $\sum\limits_{i=1}^{7}({x}_{i}-\bar{x})({y}_{i}-\bar{y})=\sum\limits_{i=1}^{7}{x}_{i}{y}_{i}-7\overline{x}·\overline{y}=532-7×4×17=56{\rm ，}$
3. 所以 $r=\frac{\sum_{i=1}^7(x_i-\overline x)(y_i-\overline y)}{\sqrt{\sum_{i=17}\left(x_i-\overline x\right)^2\sum_{i=1}^7\left(y_i-\overline y\right)^2}}\approx\frac{56}{57.5}\approx0.97，$
4. 因为样本相关系数 $\left|r\right|$ 接近于1，
5. 所以可以推断 ${\rm \mathit{x}}$ 和 ${\rm \mathit{y}}$ 这两个变量线性相关，且相关程度很强．
6. （2）因为 $\sum\limits_{i=1}^{7}{\left({x}_{i}-\overline{x}\right)^{2}}={\left(1-4\right)^{2}}+{\left(2-4\right)^{2}}+{\left(3-4\right)^{2}}+\cdot \cdot \cdot +{\left(7-4\right)^{2}}=28{\rm ，}$
7. 所以 $\hat{b}=\frac{\sum\limits_{i=1}^{7}({x}_{i}-\overline{x})({y}_{i}-\overline{y})}{\sum\limits_{i=1}^{7}{\left({x}_{i}-\overline{x}\right)^{2}}}=\frac{56}{28}=2{\rm ，}$
8. 因为 $\hat{a}=\overline{y}-\hat{b}\overline{x}=17-2×4=9{\rm ，}$
9. 所以经验回归方程为 $\hat{y}=2x+9{\rm ，}$
10. 因为一天中滑雪人数超过3000人时，当天滑雪场可实现盈利，
11. 即 $2x+9>30$ 时，可实现盈利，解得 $x>10.5{\rm ，}$
12. 所以根据经验回归方程预测，该滑雪场开业的第11天开始盈利．

## 知识点

**中文**:
  - 回归直线与回归方程
  - 相关系数r

**English**:
  - Regression Line and Equation
  - Correlation Coefficient r

---
