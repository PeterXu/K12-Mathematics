# Mathematics - 题目 1627

**ID**: 32f83f2e79474b74892f95d3f95a9760
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: 双空题

## 题目
某同学从两个笔筒中抽取使用的笔，蓝色笔筒里有6支蓝笔，4支黑笔，黑色笔筒里有6支黑笔，4支蓝笔.​​​​​​​‌第一次从黑笔筒中取出一支笔并放回，随后从与上次取出的笔颜色相同的笔筒中再取出一支笔，依此类推.记第 $n$ 次取出黑笔的概率为 $P{{}_{n}}$ ，则 $P{{}_{n}}=$， $\sum \limits_{1\leqslant i<j\leqslant n}\mathop{(P{{}_{i}}-\frac {1}{2})(P{{}_{j}}-\frac {1}{2})=}$.

## 解答

1. 解：第 $n$ 次取出黑笔的概率为 $P{{}_{n}}$ ，则取出蓝笔的概率为 $1-P{{}_{n}}$ ，
2. 所以第 $n+1$ 次取出黑笔的概率为 $P{{}_{n+1}}$ ，可能有两种情况，即第 $n$ 次取出的是黑笔或蓝笔，
3. 所以第 $n+1$ 次取出黑笔的概率为 $P{{}_{n+1}}=\frac {3}{5}P{{}_{n}}+\frac {2}{5}\left ({1-P{{}_{n}}}\right )$ ，即 $P{{}_{n+1}}=\frac {1}{5}P{{}_{n}}+\frac {2}{5}$ ， $n\in {\mathbf{N}^{*}}$ ，
4. 因为 $P{{}_{1}}=\frac {3}{5}$ ， $P{{}_{n+1}}-\frac {1}{2}=\frac {1}{5}\left ({P{{}_{n}}-\frac {1}{2}}\right )$ ， $n\in {\mathbf{N}^{*}}$
5. 所以数列 $\left \{P{{}_{n}}-\frac {1}{2}\right \}$ 为等比数列，公比为 $\frac {1}{5}$ ，首项为 $\frac {1}{10}$ ，
6. 所以 $P{{}_{n}}-\frac {1}{2}=\frac {1}{10}\times {\left({\frac {1}{5}}\right)^{n-1}}=\frac {1}{2}\times {\left({\frac {1}{5}}\right)^{n}}$ ，
7. 所以 $P{{}_{n}}=\frac {1}{2}\times {\left({\frac {1}{5}}\right)^{n}}+\frac {1}{2}$ .
8. 所以 $\sum \limits_{1\leqslant i<j\leqslant n}\mathop{\left ({P{{}_{i}}-\frac {1}{2}}\right )\left ({P{{}_{j}}-\frac {1}{2}}\right )=}\sum \limits_{i=1}^{n-1}\mathop{\frac {1}{2}{\left({\frac {1}{5}}\right)^{i}}\sum \limits_{j=i+1}^{n}\mathop{\frac {1}{2}{\left({\frac {1}{5}}\right)^{j}}}}=\sum \limits_{i=1}^{n-1}\mathop{\frac {1}{2}{\left({\frac {1}{5}}\right)^{i}}\times \frac {1}{8}\left [{\left({\frac {1}{5}}\right)^{i}}-{\left({\frac {1}{5}}\right)^{n}}\right ]}$
9. $=\sum \limits_{i=1}^{n-1}\mathop{\frac {1}{16}\left [{\left({\frac {1}{5}}\right)^{2i}}-{\left({\frac {1}{5}}\right)^{n}}\cdot {\left({\frac {1}{5}}\right)^{i}}\right ]}=\frac {1}{16}\left [\sum \limits_{i=1}^{n-1}\mathop{{\left({\frac {1}{5}}\right)^{2i}}}-{\left({\frac {1}{5}}\right)^{n}}\sum \limits_{i=1}^{n-1}\mathop{{\left({\frac {1}{5}}\right)^{i}}}\right ]=\frac {1}{16}\cdot \frac {\frac {1}{25}\left [1-{\left({\frac {1}{25}}\right)^{n-1}}\right ]}{1-\frac {1}{25}}-\frac {1}{16}\cdot {\left({\frac {1}{5}}\right)^{n}}\frac {\frac {1}{5}\left [1-{\left({\frac {1}{5}}\right)^{n-1}}\right ]}{1-\frac {1}{5}}$
10. $=\frac {1}{16}\times \frac {1}{24}\left [1-{\left({\frac {1}{25}}\right)^{n-1}}\right ]-\frac {1}{16}\times \frac {1}{4}\cdot {\left({\frac {1}{5}}\right)^{n}}\left [1-{\left({\frac {1}{5}}\right)^{n-1}}\right ]=\frac {1}{64}\left [\frac {1}{6}-\frac {1}{6}\times {\left({\frac {1}{5}}\right)^{2n-2}}-{\left({\frac {1}{5}}\right)^{n}}+{\left({\frac {1}{5}}\right)^{2n-1}}\right ]$
11. $=\frac {1}{64}\times \frac {1}{6}\left [1-{\left({\frac {1}{5}}\right)^{2n-2}}-6\times {\left({\frac {1}{5}}\right)^{n}}+6\times {\left({\frac {1}{5}}\right)^{2n-1}}\right ]=\frac {1}{384}\left [1-6\times {\left({\frac {1}{5}}\right)^{n}}+{\left({\frac {1}{5}}\right)^{2n-1}}\right ]=\frac {1}{384}\left [1-{\left({\frac {1}{5}}\right)^{n}}\right ]\left [1-{\left({\frac {1}{5}}\right)^{n-1}}\right ]$  $=\frac {(1-5{^{-n}})(1-5{^{1-n}})}{384}$ ，
12. 综上， $P{{}_{n}}=\frac {1}{2}\times {\left({\frac {1}{5}}\right)^{n}}+\frac {1}{2}$ ， $\sum \limits_{1\leqslant i<j\leqslant n}\mathop{(P{{}_{i}}-\frac {1}{2})(P{{}_{j}}-\frac {1}{2})=}\frac {(1-5{^{-n}})(1-5{^{1-n}})}{384}$
13. 故答案为： $\frac {1}{2}(1+\frac {1}{5{^{n}}})$ ； $\frac {(1-5{^{-n}})(1-5{^{1-n}})}{384}$

## 知识点

**中文**:
  - 数列的递推公式
  - 等比数列的概念与通项公式
  - 等比数列前n项和公式

**English**:
  - Recurrence Formula
  - Concept and Formula
  - Sum Formula

---
