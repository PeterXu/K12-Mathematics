# Mathematics - 题目 3717

**ID**: d91b5d27d0ee4f65b23385e558bd686c
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
已知函数 $f(x)=a{^{x}}+2{^{x}}-2$ ，其中 $a>0$ 且 $a\ne 1$ ．(1)若 $f\left ({x}\right )$ 是偶函数，求a的值；​​​​​​​‌(2)若 $x>0$ 时， $f\left ({x}\right )>0$ ，求a的取值范围．

## 解答

1. （1）由题意， $f\left ({-1}\right )=f\left ({1}\right )$ ，即 $\frac {1}{a}+\frac {1}{2}-2=a+2-2$ ，
2. 解得， $a=\frac {1}{2}$ 或 $a=-2$ （舍），经检验 $a=\frac {1}{2}$ 时， $f\left ({x}\right )$ 是偶函数，
3. 所以a的值为 $\frac {1}{2}$ ；
4. （2）当 $a=\frac {1}{2}$ 时， $\forall x>0$ ， $f(x)={\left({\frac {1}{2}}\right)^{x}}+2{^{x}}-2>2\sqrt {{\left({\frac {1}{2}}\right)^{x}}\cdot 2{^{x}}}-2=0$ 成立；
5. 当 $a>\frac {1}{2}$ 且 $a\ne 1$ 时， $\forall x>0$ ， $f(x)=a{^{x}}+2{^{x}}-2>{\left({\frac {1}{2}}\right)^{x}}+2{^{x}}-2$ ，
6. 又 ${\left({\frac {1}{2}}\right)^{x}}+2{^{x}}-2>0$ 已证，故此时符合题意；
7. 当 $0<a<\frac {1}{2}$ 时， $f^{′}(x)=a{^{x}}{\ln}a+2{^{x}}{\ln}2$ ，
8. 因为函数 $y=a{^{x}}{\ln}a,y=2{^{x}}{\ln}2$ 都是增函数，
9. 所以函数 $f^{′}{\left ({x}\right )}$ 在 $\mathbf{R}$ 上单调递增，且 $f^{′}(0)={\ln}(2a)<0$ ，
10. 故存在 $x{{}_{0}}>0$ ，使得当 $x\in (0,x{{}_{0}})$ 时， $f^{′}(x)<0$ ，从而 $f\left ({x}\right )$ 单调递减，
11. 所以，存在 $\frac {x{{}_{0}}}{2}>0$ ，使得 $f\left ({\frac {x{{}_{0}}}{2}}\right )<f(0)=0$ ，此时不合题意．
12. 综上所述， $a\geqslant \frac {1}{2}$ 且 $a\ne 1$ ．

## 知识点

**中文**:
  - 函数奇偶性的应用
  - 利用导数研究函数的单调性与单调区间
  - 利用导数解决不等式恒成立问题

**English**:
  - Applications of Parity
  - Monotonicity and Monotonic Intervals
  - Solving Universally True Inequalities

---
