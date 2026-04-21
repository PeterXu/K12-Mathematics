# Mathematics - 题目 3243

**ID**: b44f186db620476ba642fca2c293c3b9
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f(x)=({\log}{{}_{2}}x-2){\log}{{}_{2}}\frac {x}{2}$ ．（1）求函数 $f(x)$ 的最小值；​​​​​​​‌（2）若对于 $x\in [2,16]$ ， $f(x)<m{\log}{{}_{4}}x$ 恒成立，求 $m$ 的取值范围；（3）若关于 $x$ 的方程 $\left |{f(x)}\right |=b$ 有两个不同的实数解，直接写出实数 $b$ 的取值范围．

## 解答

1. （1）由题意，函数 $y=f(x)$ 的定义域为 $(0,+\infty )$ ，
2. $f(x)=({\log}{{}_{2}}x-2){\log}{{}_{2}}\frac {x}{2}=({\log}{{}_{2}}x-2)({\log}{{}_{2}}x-1)$ ，
3. 令 $t={\log}{{}_{2}}x$ ，则 $t\in {\rm{R}}$ ，则 $y=(t-2)(t-1)=t{^{2}}-3t+2$ ．
4. 因为二次函数 $y=t{^{2}}-3t+2$ 开口向上，且对称轴为 $t=\frac {3}{2}$ ，
5. 所以函数 $y=t{^{2}}-3t+2$ 在 $t\in \left ({-∞,\frac {3}{2}}\right ]$ 上单调递减，在 $t\in \left [{\frac {3}{2},+∞}\right )$ 上单调递增；
6. 由 ${\log}{{}_{2}}x=\frac {3}{2}$ ，得 ${\log}{{}_{2}}x={\log}{{}_{2}}2{^{\frac {3}{2}}}={\log}{{}_{2}}\left ({2\sqrt {2}}\right )$ ，解得 $x=2\sqrt {2}$ ，
7. 又因为对数函数 $t={\log}{{}_{2}}x$ 是增函数，
8. 所以根据复合函数的单调性判断方法可知：
9. 函数 $y=f(x)$ 在 $\left ({0,2\sqrt {2}}\right ]$ 上单调递减，在 $\left [{2\sqrt {2},+\infty }\right )$ 上单调递增．
10. 因此当 $x=2\sqrt {2}$ 时， $f(x)$ 有最小值，最小值为 $f\left ({2\sqrt {2}}\right )=-\frac {1}{4}$ ；
11. （2）由 $f(x)<m{\log}{{}_{4}}x$ ，得 $({\log}{{}_{2}}x-2)({\log}{{}_{2}}x-1)<\frac {m}{2}{\log}{{}_{2}}x$ ．
12. 令 $t={\log}{{}_{2}}x$ ，由 $x\in [2,16]$ ，得 $t\in [1,4]$ ．
13. 由题意可知，对于 $t\in [1,4]$ ， $(t-2)(t-1)<\frac {m}{2}t$ 恒成立，即 $t+\frac {2}{t}-3<\frac {m}{2}$ 恒成立．
14. 令 $h(t)=t+\frac {2}{t}-3$ ，则 $h{{}_{{\rm \max }}}(t)<\frac {m}{2}$ ， $t\in [1,4]$ ．
15. 由对勾函数的单调性可知 $h(t)$ 在 $\left [1,\sqrt {2}\right ]$ 上单调递减，在 $\left [\sqrt {2},4\right ]$ 上单调递增，
16. 且 $h(1)=0$ ， $h(4)=\frac {3}{2}$ ，
17. 所以当 $t\in [1,4]$ 时， $h{{}_{{\rm \max }}}(t)=h(4)=\frac {3}{2}$ ．
18. 因此 $\frac {3}{2}<\frac {m}{2}$ ，解得 $m>3$ ，即 $m\in (3,+\infty )$ ．
19. （3）结合（1）可画出函数 $\left |{f(x)}\right |=\left |{({\log}{{}_{2}}x-2){\log}{{}_{2}}\frac {x}{2}}\right |$ 的大致图象如下：
20. 
21. 如图所示，函数 $y=\left |{f(x)}\right |$ 在区间 $\left ({0,2}\right )$ 上单调递减，在区间 $\left ({2,2\sqrt {2}}\right )$ 上单调递增，
22. 在区间 $\left ({2\sqrt {2},4}\right )$ 上单调递减，在区间 $\left ({4,+∞}\right )$ 上单调递增，
23. 并且 $\left |{f\left ({2}\right )}\right |=\left |{f\left ({4}\right )}\right |=0$ ， $\left |{f\left ({2\sqrt {2}}\right )}\right |=\frac {1}{4}$ ，
24. 因此当 $b\in \left \{0\right \}\cup \left ({\frac {1}{4},+∞}\right )$ 时，关于 $x$ 的方程 $\left |{f(x)}\right |=b$ 有两个不同的实数解.

## 知识点

**中文**:
  - 对数函数性质的综合应用
  - 对数函数的最值
  - 对数型复合函数

**English**:
  - Comprehensive Application of Logarithmic Function Properties
  - Extrema of Logarithmic Functions
  - Logarithmic Composite Functions

---
