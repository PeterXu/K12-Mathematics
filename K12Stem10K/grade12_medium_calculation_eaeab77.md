# Mathematics - 题目 2143

**ID**: eaeab77186c24b61a35057e76938df46
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
已知 $n\in N^{*}$ ，抛物线 $y=-x^{2}+n$ 与 $x$ 轴正半轴相交于点 $A$ ．设 $a_{n}$ 为该拋物线在点 $A$ 处的切线在 $y$ 轴上的截距．(1)求数列 $\left\{\begin{array}{l}a_{n}\end{array}\right \}$ 的通项公式；​​​​​​​‌(2)设 $b_{n}=\frac {na_{n}}{2}$ ， 求证：  $\frac {1}{b_{1}}+\frac {1}{b_{2}}+\cdots +\frac {1}{b_{n}}<2-\frac {1}{n}$ （ $n\in N^{*}$ 且 $n\geqslant 2$ ）．

## 解答

1. （1）由题意，令 $y=-x^{2}+n=0$ ，解得 $x=\pm \sqrt {n}$
2. 又 $A$ 在 $x$ 轴正半轴，故 $A(\sqrt {n},0)$
3. $y^{′}=-2x$ ，故切线斜率 $k=-2\sqrt {n}$
4. 抛物线在点 $A(\sqrt {n},0)$ 处的切线方程为 $y=-2\sqrt {n}(x-\sqrt {n})$
5. 令 $x=0,y=2n$
6. 所以它在 $y$ 轴上的截距 $a_{n}=2n$ ．
7. （2）由题意， $b_{n}=n^{2}$
8. 故 $\frac {1}{b_{1}}+\frac {1}{b_{2}}+\cdots +\frac {1}{b_{n}}=\frac {1}{1^{2}}+\frac {1}{2^{2}}+...+\frac {1}{n^{2}}$
9. 又对 $n\in N^{*}$ 且 $n\geqslant 2$ 时
10. $\frac {1}{n^{2}}<\frac {1}{n(n-1)}=\frac {1}{n-1}-\frac {1}{n}$
11. $\therefore \frac {1}{b_{1}}+\frac {1}{b_{2}}+\cdots +\frac {1}{b_{n}}<1+\frac {1}{1\times 2}+\frac {1}{2\times 3}+\cdots +\frac {1}{(n-1)n}=1+1-\frac {1}{2}+\frac {1}{2}-\frac {1}{3}+...+\frac {1}{n-1}-\frac {1}{n}=2-\frac {1}{n}$ 得证

## 知识点

**中文**:
  - 导数几何意义的应用
  - 数列求和方法之裂项相消法

**English**:
  - Applications of Geometric Meaning of Derivatives
  - Telescoping Series Method

---
