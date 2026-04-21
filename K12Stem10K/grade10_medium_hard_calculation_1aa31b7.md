# Mathematics - 题目 3059

**ID**: 1aa31b773e534cd782903a887e2797f4
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
给定平面上一个图形D，以及图形D上的点 $P{{}_{1}},P{{}_{2}},\cdots ,P{{}_{n}}$ ，如果对于D上任意的点 ${\rm \mathit{P}，}\sum\limits_{i=1}^{n}\mathop{}\left |{\overrightarrow {{PP{{}_{i}}}}}\right |{^{2}}$ 为与P无关的定值，我们就称 $P{{}_{1}},P{{}_{2}},\cdots ,P{{}_{n}}$ 为关于图形D的一组稳定向量基点.​​​​​​​‌(1)已知 $P{{}_{1}}\left ({0,0}\right ),P{{}_{2}}\left ({2,0}\right ),P{{}_{3}}\left ({0,2}\right ),\vartriangle P{{}_{1}}P{{}_{2}}P{{}_{3}}$ 为图形D，判断点 $P{{}_{1}},P{{}_{2}},P{{}_{3}}$ 是不是关于图形D的一组稳定向量基点；(2)若图形D是边长为2的正方形， $P{{}_{1}},P{{}_{2}},P{{}_{3}},P{{}_{4}}$ 是它的4个顶点，P为该正方形上的动点，求 $\left |{\overrightarrow {{P{{}_{1}}P{{}_{2}}}}+\overrightarrow {{P{{}_{2}}P{{}_{3}}}}+\overrightarrow {{P{{}_{3}}P{{}_{4}}}}-\overrightarrow {{P{{}_{1}}P}}}\right |$ 的取值范围；(3)若给定单位圆 $E$ 及其内接正2024边形 $P{{}_{1}}P{{}_{2}}\cdots P{{}_{2024}},P$ 为该单位圆上的任意一点，证明 $P{{}_{1}},P{{}_{2}},\cdots ,P{{}_{2024}}$ 是关于圆 $E$ 的一组稳定向量基点，并求 $\sum\limits_{i=1}^{2024}\mathop{}\left |{\overrightarrow {{PP{{}_{i}}}}}\right |{^{2}}$ 的值.

## 解答

1. （1）点 $P{{}_{1}}\left ({0,0}\right ),P{{}_{2}}\left ({2,0}\right ),P{{}_{3}}\left ({0,2}\right )$ 不是关于 $D$ 的一组稳定向量基点，理由如下：
2. 当 $P$ 与 $P{{}_{1}}\left ({0,0}\right )$ 重合时，有 $\left |{\overrightarrow {{PP{{}_{1}}}}}\right |{^{2}}+\left |{\overrightarrow {{PP{{}_{2}}}}}\right |{^{2}}+\left |{\overrightarrow {{PP{{}_{3}}}}}\right |{^{2}}=8$ ，
3. 当 $P$ 与 $P{{}_{2}}\left ({2,0}\right )$ 重合时，有 $\left |{\overrightarrow {{PP{{}_{1}}}}}\right |{^{2}}+\left |{\overrightarrow {{PP{{}_{2}}}}}\right |{^{2}}+\left |{\overrightarrow {{PP{{}_{3}}}}}\right |{^{2}}=12\ne 8$ ，
4. 故 $P{{}_{1}}\left ({0,0}\right ),P{{}_{2}}\left ({2,0}\right ),P{{}_{3}}\left ({0,2}\right )$ 不是关于 $D$ 的一组稳定向量基点.
5. （2）因为 $\overrightarrow {{P{{}_{1}}P{{}_{2}}}}+\overrightarrow {{P{{}_{2}}P{{}_{3}}}}+\overrightarrow {{P{{}_{3}}P{{}_{4}}}}-\overrightarrow {{P{{}_{1}}P}}=\overrightarrow {{P{{}_{1}}P{{}_{4}}}}-\overrightarrow {{P{{}_{1}}P}}=\overrightarrow {{PP{{}_{4}}}}$ ，
6. 所以 $\left |{\overrightarrow {{P{{}_{1}}P{{}_{2}}}}+\overrightarrow {{P{{}_{2}}P{{}_{3}}}}+\overrightarrow {{P{{}_{3}}P{{}_{4}}}}-\overrightarrow {{P{{}_{1}}P}}}\right |=\left |{\overrightarrow {{PP{{}_{4}}}}}\right |$ ，故由正方形结构性质得：
7. 当 $P$ 与 $P{{}_{2}}$ 重合时， $\left |{\overrightarrow {{PP{{}_{4}}}}}\right |$ 取得最大值 $2\sqrt {2}$ ；当 $P$ 与 $P{{}_{4}}$ 重合时， $\left |{\overrightarrow {{PP{{}_{4}}}}}\right |$ 取得最小值0.
8. 所以 $\left |{\overrightarrow {{P{{}_{1}}P{{}_{2}}}}+\overrightarrow {{P{{}_{2}}P{{}_{3}}}}+\overrightarrow {{P{{}_{3}}P{{}_{4}}}}-\overrightarrow {{P{{}_{1}}P}}}\right |$ 的取值范围为 $\left [0,2\sqrt {2}\right ]$ .
9. （3）设单位圆 $E$ 的圆心为 $O$ ，
10. 则 $\left |{\overrightarrow {{PP{{}_{i}}}}}\right |{^{2}}={\left({\overrightarrow {{OP{{}_{i}}}}-\overrightarrow {{OP}}}\right)^{2}}=\overrightarrow {{OP{{}_{i}}}}{^{2}}-2\overrightarrow {{OP{{}_{i}}}}\cdot \overrightarrow {{OP}}+\overrightarrow {{OP}}{^{2}}$ ，
11. 
12. 所以 $\sum\limits_{i=1}^{2024}\mathop{}\left |{\overrightarrow {{PP{{}_{i}}}}}\right |{^{2}}=\sum\limits_{i=1}^{2024}\mathop{}{\left({\overrightarrow {{OP{{}_{i}}}}-\overrightarrow {{OP}}}\right)^{2}}=\sum\limits_{i=1}^{2024}\mathop{}\left |{\overrightarrow {{OP{{}_{i}}}}}\right |{^{2}}+2024|\overrightarrow {{OP}}|{^{2}}-2\overrightarrow {{OP}}\cdot \sum\limits_{i=1}^{2024}\mathop{}\overrightarrow {{OP{{}_{i}}}}$ ，
13. 因为多边形 $P{{}_{1}}P{{}_{2}}\cdots P{{}_{2024}}$ 是正2024边形，
14. 所以由偶数边的正多边形图形结构性质可知 $\sum \limits_{i=1}^{2024}\mathop{\overrightarrow {{OP{{}_{i}}}}}=\overrightarrow 0$ ，故 $\overrightarrow {{OP}}\cdot \sum \limits_{i=1}^{2024}\mathop{\overrightarrow {{OP{{}_{i}}}}}=\overrightarrow 0$ ，
15. 又 $\left |{\overrightarrow {{OP}}}\right |=\left |{\overrightarrow {{OP{{}_{i}}}}}\right |=1$ ，所以 $\sum\limits_{i=1}^{2024}\mathop{}\left |{\overrightarrow {{PP{{}_{i}}}}}\right |{^{2}}=4048$ ，
16. 故 $P{{}_{1}},P{{}_{2}},\cdots ,P{{}_{2024}}$ 是关于圆 $E$ 的一组稳定向量基点，且 $\sum\limits_{i=1}^{2024}\mathop{}\left |{\overrightarrow {{P{{}_{i}}}}}\right |{^{2}}=4048$ .

## 知识点

**中文**:
  - 平面向量运算中最值与范围的求解

**English**:
  - Extrema and Range Problems

---
