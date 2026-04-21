# Mathematics - 题目 3934

**ID**: f1fc37ccb5d1463ba3bd8251bd7c953c
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
随机游走在空气中的烟雾扩散、股票市场的价格波动等动态随机现象中有重要应用.​​​​​​​‌在平面直角坐标系中，粒子从原点出发，每秒向左、向右、向上或向下移动一个单位，且向四个方向移动的概率均为 $\frac {1}{4}.$ 例如在1秒末，粒子会等可能地出现在 $\left ({1,0}\right ),\left ({-1,0}\right ),\left ({0,1}\right ),\left ({0,-1}\right )$ 四点处.(1)设粒子在第2秒末移动到点 $\left ({x,y}\right )$ ，记 $x+y$ 的取值为随机变量 $X$ ，求 $X$ 的分布列和数学期望 $E\left ({X}\right )$ ；(2)记第 $n$ 秒末粒子回到原点的概率为 $p{{}_{n}}$ .（i）已知  $\sum \limits_{k=0}^{n}\mathop{({\rm{C}}{{}_{n}^{k}}}){^{2}}={\rm{C}}{{}_{2n}^{n}}$ 求 $p{{}_{3}},p{{}_{4}}$ 以及 $p{{}_{2n}}$ ；（ii）令 $b{{}_{n}}=p{{}_{2n}}$ ，记 $S{{}_{n}}$ 为数列 $\left \{b{{}_{n}}\right \}$ 的前 $n$ 项和，若对任意实数 $M>0$ ，存在 $n\in {\rm{N}}*$ ，使得 $S{{}_{n}}>M$ ，则称粒子是常返的.已知  $\sqrt {2{\rm{π}}n}{\left({\frac {n}{{\rm{e}}}}\right)^{n}}<n!<\left ({\frac {6}{{\rm{π}}}}\right ){^{\frac {1}{4}}}\sqrt {2{\rm{π}}n}{\left({\frac {n}{{\rm{e}}}}\right)^{n}}，$ 证明：该粒子是常返的.

## 解答

1. （1）粒子在第 $2$ 秒可能运动到点 $\left ({1,1}\right ),\left ({2,0}\right ),\left ({0,2}\right )$ 或 $\left ({0,0}\right ),\left ({1,-1}\right ),\left ({-1,1}\right )$ 或 $\left ({-1,-1}\right ),\left ({-2,0}\right ),\left ({0,-2}\right )$ 的位置， $X$ 的可能取值为： $-2,0,2$ ，
2. $P\left ({X=-2}\right )=\frac {4}{16}=\frac {1}{4}$ ， $P\left ({X=0}\right )=\frac {8}{16}=\frac {1}{2}$ ， $P\left ({X=2}\right )=\frac {4}{16}=\frac {1}{4}$ ，
3. 所以 $X$ 的分布列为：
4. $X$
5. $-2$
6. $0$
7. $2$
8. $P$
9. $\frac {1}{4}$
10. $\frac {1}{2}$
11. $\frac {1}{4}$
12. $E\left ({X}\right )=\left ({-2}\right )\times \frac {1}{4}+0\times \frac {1}{2}+2\times \frac {1}{4}=0$ .
13. （2）（i）粒子奇数秒不可能回到原点，故 $p{{}_{3}}=0$ ，
14. 粒子在第4秒回到原点，分两种情况考虑：
15. $\left ({a}\right )$ 每一步分别是四个不同方向的排列，例如“上下左右”，共有 ${\rm{A}}{{}_{{{4}}}^{{{4}}}}$ 种情形；
16. $\left ({b}\right )$ 每一步分别是两个相反方向的排列，例如“左左右右、上上下下”，共有 ${{2}}{\rm{C}}{{}_{{{4}}}^{2}}$ 种情形；
17. 于是 $p{{}_{4}}=\frac {{\rm{A}}{{}_{{{4}}}^{{{4}}}}{{+}}{{2}}{\rm{C}}{{}_{4}^{2}}}{4{^{4}}}=\frac {9}{64}$ ，
18. 第 $2n$ 秒末粒子要回到原点，则必定向左移动 $k$ 步，向右移动 $k$ 步，向上移动 $n-k$ 步，
19. 向下移动 $n-k$ 步，故 $p{{}_{2n}}=\sum\limits_{k=0}^{n}\mathop{}\frac {{\rm{C}}{{}_{2n}^{k}}{\rm{C}}{{}_{2n-k}^{k}}{\rm{C}}{{}_{2n-2k}^{n-k}}}{4{^{2n}}}=\frac {1}{4{^{2n}}}\sum\limits_{k=0}^{n}\mathop{}\frac {\left ({2n}\right )!}{{\left({k!}\right)^{2}}\left [\left ({n-k}\right )!\right ]{^{2}}}$
20. $=\frac {1}{4{^{2n}}}\frac {\left ({2n}\right )!}{{\left({n!}\right)^{2}}}\sum\limits_{k=0}^{n}\mathop{}\frac {{\left({n!}\right)^{2}}}{{\left({k!}\right)^{2}}\left [\left ({n-k}\right )!\right ]{^{2}}}=\frac {1}{4{^{2n}}}\cdot {\rm{C}}{{}_{2n}^{n}}\sum\limits_{k=0}^{n}\mathop{}{\rm{C}}{{}_{n}^{k}}{\rm{C}}{{}_{n}^{n-k}}$
21. $=\frac {1}{4{^{2n}}}\cdot {\rm{C}}{{}_{2n}^{n}}\sum\limits_{k=0}^{n}\mathop{}{\left({{\rm{C}}{{}_{n}^{k}}}\right)^{2}}=\frac {1}{4{^{2n}}}\cdot {\left({{\rm{C}}{{}_{2n}^{n}}}\right)^{2}}$ .
22. 故 $p{{}_{2n}}=\frac {1}{4{^{2n}}}\cdot {\left({{\rm{C}}{{}_{2n}^{n}}}\right)^{2}}=\frac {1}{16{^{n}}}{\left({{\rm{C}}{{}_{2n}^{n}}}\right)^{2}}=\frac {1}{16{^{n}}}\frac {\left [\left ({2n}\right )!\right ]{^{2}}}{{\left({n!}\right)^{4}}}$ .
23. （ii）利用 $\sqrt {2{\rm{π}}n}{\left({\frac {n}{{\rm{e}}}}\right)^{n}}<n!<\left ({\frac {6}{{\rm{π}}}}\right ){^{\frac {1}{4}}}\sqrt {2{\rm{π}}n}{\left({\frac {n}{{\rm{e}}}}\right)^{n}}$ 可知：
24. ${\rm{C}}{{}_{2n}^{n}}=\frac {\left ({2n}\right )!}{{\left({n!}\right)^{2}}}>\frac {\sqrt {4{\rm{π}}n}{\left({\frac {2n}{{\rm{e}}}}\right)^{2n}}}{\left [\left ({\frac {6}{{\rm{π}}}}\right ){^{\frac {1}{4}}}\sqrt {2{\rm{π}}n}{\left({\frac {n}{{\rm{e}}}}\right)^{n}}\right ]{^{2}}}=\frac {4{^{n}}}{\sqrt {6n}}$ ，
25. 于是 $p{{}_{2n}}=\frac {1}{4{^{2n}}}\cdot {\left({{\rm{C}}{{}_{2n}^{n}}}\right)^{2}}>\frac {1}{6n}$ ，
26. 令 $f\left ({x}\right )=x-{\ln}\left ({1+x}\right ),x>0$ ， $f^{′}{\left ({x}\right )}=1-\frac {1}{1+x}=\frac {x}{1+x}>0$ ，
27. 故 $f\left ({x}\right )$ 在 $\left ({0,+\infty }\right )$ 上单调递增，
28. 则 $f\left ({x}\right )>f\left ({0}\right )=0$ ，于是 $x>{\ln}\left ({1+x}\right )\left ({x>0}\right )$ ，
29. 从而有： $S{{}_{n}}=\sum\limits_{k=1}^{n}\mathop{}p{{}_{2k}}>\sum\limits_{k=1}^{n}\mathop{}\frac {1}{6k}>\frac {1}{6}\sum\limits_{k=1}^{n}\mathop{}{\ln}\left ({1+\frac {1}{k}}\right )=\frac {1}{6}{\ln}\left ({n+1}\right )$ ，
30. 即 $\left [x\right ]$ 为不超过 $x$ 的最大整数，则对任意常数 $M>0$ ，当 $n\geqslant \left [{\rm{e}}{^{6M}}\right ]$ 时，
31. $n>{\rm{e}}{^{6M}}-1$ ，于是 $S{{}_{n}}>\frac {1}{6}{\ln}\left ({n+1}\right )>M$ ,
32. 综上所述，当 $n\geqslant \left [{\rm{e}}{^{6M}}\right ]$ 时， $S{{}_{n}}>M$ 成立，因此该粒子是常返的.

## 知识点

**中文**:
  - 古典概型的概率计算
  - 排列与组合的综合应用
  - 离散型随机变量的分布列

**English**:
  - Calculation of Classical Probability
  - Comprehensive Applications
  - Probability Distribution Table

---
