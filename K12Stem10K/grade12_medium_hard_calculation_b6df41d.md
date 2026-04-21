# Mathematics - 题目 274

**ID**: b6df41da00e84b8a9d659f0f16af1d48
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
某公司拟对某种材料进行应用改造，产品的成本由原料成本及非原料成本组成，每件产品的非原料成本y（元）与生产该产品的数量x（千件）有关，经统计得到如下数据：x12345678y1126144.​​​​​​​‌53560.5282524对历史数据对比分析，考虑用函数模型① $y=a+\frac {b}{x}$ ，② $y=c{\rm e}^{dx}$ 分别对两个变量的关系进行拟合，令模型①中 $u=\frac {1}{x}$ ，模型②中 $w={\ln}y$ ，对数据作了初步处理，已计算得到如下数据：${\overline{u}}$${\overline{y}}$${\overline{u}}{^{2}}$$\sum \limits_{i=1}^{8}\mathop{y{{}_{i}^{2}}}$$\sum \limits_{i=1}^{8}\mathop{u{{}_{i}^{2}}}$$\sum \limits_{i=1}^{8}\mathop{u{{}_{i}}}y{{}_{i}}$$\sqrt {0.61\times 6185.5}$$\mathrm{e}{^{-2}}$0.34450.11522385.51.53183.461.40.135(1)设u和y的样本相关系数为 $r{{}_{1}}$ ，x和w的样本相关系数为 $r{{}_{2}}$ ，已经计算得出 $r{{}_{2}}=-0.94$ ，请从样本相关系数（精确到0.01）的角度判断，哪个模型拟合效果更好？(2)根据（1）的选择及表中数据，建立y关于x的非线性回归方程，并用其估计当每件产品的非原料成本为21元时，产量约为多少千件？参考公式：对于一组数据 $\left ({u{{}_{1}},v{{}_{1}}}\right )$ ， $\left ({u{{}_{2}},v{{}_{2}}}\right )$ ，…， $\left ({u{{}_{n}},v{{}_{n}}}\right )$ 其回归直线 $\widehat {v}=\widehat {a}+\widehat {β}u$ 的斜率和截距的最小二乘估计分别为： $\widehat {β}=\frac {\sum \limits_{i=1}^{n}\mathop{u{{}_{i}}}v{{}_{i}}-n{\overline{u}}\cdot {\overline{v}}}{\sum \limits_{i=1}^{n}\mathop{u{{}_{i}^{2}}}-n{\overline{u}}{^{2}}}$ ， $\widehat {a}=\widehat {v}-\widehat {β}{\overline{u}}$ ，相关系数 $r=\frac {\sum \limits_{i=1}^{n}\mathop{u{{}_{i}}}v{{}_{i}}-n{\overline{u}}\cdot {\overline{v}}}{\sqrt {\left ({\sum \limits_{i=1}^{n}\mathop{u{{}_{i}^{2}}}-n{\overline{u}}{^{2}}}\right )\cdot \left ({\sum \limits_{i=1}^{n}\mathop{v{{}_{i}^{2}}}-n{\overline{v}}{^{2}}}\right )}}$ ．

## 解答

1. (1)
2. 令 $u=\frac {1}{x}$ ，则 $y=\widehat {a}+\widehat {b}u$ ，且 ${\overline{y}}=45$ ，
3. y与u的相关系数： $r{{}_{1}}=\frac {\sum \limits_{i=1}^{8}\mathop{u{{}_{i}}}y{{}_{i}}-8{\overline{u}}\cdot {\overline{y}}}{\sqrt {\left ({\sum \limits_{i=1}^{8}\mathop{u{{}_{i}^{2}}}-8{\overline{u}}{^{2}}}\right )\left ({\sum \limits_{i=1}^{8}\mathop{y{{}_{i}^{2}}}-8{\overline{y}}{^{2}}}\right )}}$  $=\frac {61}{\sqrt {0.61\times 6185.5}}=\frac {61}{61.4}\approx 0.99$ ，
4. 所以 $\left |{r{{}_{1}}}\right |>\left |{r{{}_{2}}}\right |$ ，故用模型①拟合效果更好.
5. (2)
6. 由 $\widehat {b}=\frac {\sum \limits_{i=1}^{8}\mathop{u{{}_{i}}}y{{}_{i}}-8{\overline{u}}\cdot {\overline{y}}}{\sum \limits_{i=1}^{8}\mathop{u{{}_{i}^{2}}}-8{\overline{u}}{^{2}}}=\frac {183.4-8\times 0.34\times 45}{1.53-8\times 0.115}=\frac {61}{0.61}=100$ ，则 $\widehat {a}={\overline{y}}-\widehat {b}{\overline{u}}=45-100\times 0.34=11$ ，
7. 所以y关于x的回归方程为 $\widehat {y}=11+\frac {100}{x}$ ，
8. 当 $\widehat {y}=21$ 时， $\widehat {y}=11+\frac {100}{x}=21$ （元），解得 $x=10$ 千件.
9. 所以当每件产品的非原料成本为21元，预计产量约为10千件．

## 知识点

**中文**:
  - 最小二乘法
  - 相关系数r
  - 非线性回归问题

**English**:
  - Least Squares Method
  - Correlation Coefficient r
  - Non-linear Regression

---
