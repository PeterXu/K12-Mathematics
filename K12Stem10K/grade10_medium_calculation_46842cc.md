# Mathematics - 题目 1332

**ID**: 46842cc47fef435ea9f84e0acaa403b0
**年级**: Grade 10
**难度**: Medium
**题型**: Calculation

## 题目
在研究某市交通情况时，道路密度是指该路段一定时间内通过的车辆除以时间，车辆密度是该路段一定时间内通过的车辆数除以该路段的长度，现定义交通流量为 $F=\frac {q}{x}$ ， $x$ 为道路密度， $q$ 为车辆密度.​​​​​​​‌已知某道路的交通流量 $F=f\left ({x}\right )=\left \{\hspace{-0.5em}\begin{array}{}100-45\cdot {\left({\frac {1}{3}}\right)^{x}},0<x<40\\-k\left ({x-40}\right )+85,40\leqslant x\leqslant 80\end{array}\hspace{-0.5em}(k>0)\right.$  ，(1)若交通流量 $F>95$ ，求道路密度 $x$ 的取值范围；(2)若道路密度 $x=80$ 时，测得交通流量， $F=50$ ，求车辆密度 $q$ 的最大值.

## 解答

1. （1）由题知 $k>0$ ，所以当 $40\leqslant x\leqslant 80$ 时， $-k(x-40)+85\leqslant 85$ ，不符题意；
2. 当 $0<x<40$ 时，由 $100-45\cdot {\left({\frac {1}{3}}\right)^{x}}>95$ ，整理得到 $\frac {1}{9}>{\left({\frac {1}{3}}\right)^{x}}$ ，即 ${\left({\frac {1}{3}}\right)^{2}}>{\left({\frac {1}{3}}\right)^{x}}$ ，解得 $x>2$ ，即 $2<x<40$ ，
3. 所以交通流量 $F>95$ ，道路密度 $x$ 的取值范围为 $(2,40)$ .
4. （2）由题意得 $x=80$ 时， $F=f(80)=-k(80-40)+85=50$ ，得到 $k=\frac {7}{8}$ ，
5. 当 $0<x<40$ 时， $q=x\left [100-45\cdot {\left({\frac {1}{3}}\right)^{x}}\right ]<100\cdot x<4000$ ，
6. 当 $40\leqslant x\leqslant 80$ 时， $q=-\frac {7}{8}x{^{2}}+120x=-\frac {7}{8}{\left({x-\frac {480}{7}}\right)^{2}}+\frac {28800}{7}\leqslant \frac {28800}{7}$ ，
7. 由于 $40<\frac {480}{7}<80$ ，所以当 $x=\frac {480}{7}$ 时， $q$ 取得最大值 $\frac {28800}{7}$ ，
8. 又 $\frac {28800}{7}>4000$ ，所以车辆密度 $q$ 的最大值为 $\frac {28800}{7}$ .

## 知识点

**中文**:
  - 分段函数模型及应用

**English**:
  - Piecewise Function Model

---
