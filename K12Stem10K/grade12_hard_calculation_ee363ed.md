# Mathematics - 题目 3805

**ID**: ee363edee6764aa38c5f278b34c2a55e
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
设 $f\left ({x}\right )={\rm{e}}{{}^{x}}$ ， $g\left ({x}\right )={\ln}x$ ，(1)证明： $xf\left ({x}\right )\geqslant x+g\left ({x}\right )+1$ ；(2)若存在直线 $y=t$ ，其与曲线 $y=\frac {x}{f\left ({x}\right )}$ 和 $y=\frac {g\left ({x}\right )}{x}$ 共有3个不同交点 $A\left ({x{{}_{1}},t}\right )$ ， $B\left ({x{{}_{2}},t}\right )$ ， $C\left ({x{{}_{3}},t}\right )$  $\left ({x{{}_{1}}<x{{}_{2}}<x{{}_{3}}}\right )$ ，求证： $x{{}_{1}}$ ， $x{{}_{2}}$ ， $x{{}_{3}}$ 成等比数列.​​​​​​​‌

## 解答

1. （1）因为 $f\left ({x}\right )={\rm{e}}{{}^{x}}$ ， $g\left ({x}\right )={\ln}x$ ，所以 $xf\left ({x}\right )\geqslant x+g\left ({x}\right )+1$ 等价于 $x{\rm{e}}{{}^{x}}\geqslant x+{\ln}x+1$ ，
2. 即 ${\rm{e}}{{}^{x+{\ln}x}}\geqslant x+{\ln}x+1$ ，
3. 令 $t=x+{\ln}x,t\in {\rm{R}}$ ，则只需证 ${\rm{e}}{{}^{t}}\mathrm{\geqslant }t+1$ ，
4. 设 $g(t)={\rm{e}}{{}^{t}}-t-1,t\in {\rm{R}}$ ，则 $g^{′}(t)={\rm{e}}{{}^{t}}-1,t\in {\rm{R}}$ ，
5. 当 $t<0$ 时， $g^{′}(t)<0$ ， $g(t)$ 单调递减；当 $t>0$ 时， $g^{′}(t)>0$ ， $g(t)$ 单调递增；
6. 故 $g(t)\geqslant g(0)=1-0-1=0$ ，即 ${\rm{e}}{{}^{t}}\mathrm{\geqslant }t+1$ 成立，
7. 所以 ${\rm{e}}{{}^{x+{\ln}x}}\geqslant x+{\ln}x+1$ 成立，即 $xf\left ({x}\right )\geqslant x+g\left ({x}\right )+1$ 得证；
8. （2）记 $F(x)=\frac {x}{f\left ({x}\right )}=\frac {x}{{\rm{e}}{{}^{x}}}$ ，则 $F{{}^{\prime }}(x)=\frac {1-x}{{\rm{e}}{{}^{x}}}$ ，
9. 当 $x\in (-∞,1)$ 时， $F^{′}(x)>0$ ；当 $x\in (1,+\infty )$ 时， $F^{′}(x)<0$ ．
10. 故 $F(x)$ 在 $(-\infty ,1)$ 内单调递增，在 $(1,+\infty )$ 内单调递减，故 $F(x){{}_{\max }}=F(1)=\frac {1}{{\rm{e}}}$ ；
11. 记 $G(x)=\frac {g\left ({x}\right )}{x}=\frac {{\ln}x}{x}$ ，则 $G{{}^{\prime }}(x)=\frac {1-{\ln}x}{x{{}^{2}}}$ ，
12. 当 $x\in (0,{\rm{e}})$ 时， $G{{}^{\prime }}(x)>0$ ，当 $x\in ({\rm{e}},+\infty )$ 时， $G{{}^{\prime }}(x)<0$ ，
13. 故 $G(x)$ 在 $(0,{\rm{e}})$ 内单调递增，在 $({\rm{e}},+\infty )$ 内单调递减，故 $G(x){{}_{\max }}=G({\rm{e}})=\frac {1}{{\rm{e}}}$ .
14. 所以函数 $F(x)$ 与函数 $G(x)$ 有相同的最大值，画出 $F(x)$ 与 $G(x)$ 的图象如下图：
15. 
16. 可知， $t<\frac {1}{{\rm{e}}}$ 且 $1<x{{}_{2}}<{\rm{e}}$ ，又当 $x\in (0,+\infty )$ 时， $F(x)>0$ ，故 $t>0$ ，
17. 当 $0<t<\frac {1}{{\rm{e}}}$ 时，直线 $y=t$ 与两条曲线 $y=F(x)$ 和 $y=G(x)$ 各有两个不同的交点，
18. 则直线 $y=t$ 与曲线 $y=F(x)$ 的两个交点分别位于区间 $(0,1)$ 和 $\left ({1,+\infty }\right )$ ，
19. 而直线 $y=t$ 与曲线 $y=G(x)$ 的两个交点分别位于区间 $(0,{\rm{e}})$ 和 $({\rm{e}},+\infty )$ ，
20. 构造 $H(x)=F(x)-G(x)=\frac {x}{{\rm{e}}{{}^{x}}}-\frac {{\ln}x}{x}$ ，当 $x\in (0,1)$ 时， $H(x)>0$ ；当 $x\in ({\rm{e}},+\infty )$ 时， $H(x)<0$ ，
21. 当 $x\in (1,{\rm{e}})$ 时，1-x<0， ${\ln}x\in (0,1)$ ， ${\ln}x-1<0$ ， $H^{′}(x)=\frac {1-x}{{\rm{e}}{{}^{x}}}+\frac {{\ln}x-1}{x{{}^{2}}}<0$ ，
22. 故 $H(x)$ 在 $(1,{\rm{e}})$ 内单调递减，又 $H(1)=\frac {1}{{\rm{e}}}>0$ ， $H({\rm{e}})=\frac {{\rm{e}}}{{\rm{e}}{{}^{{\rm{e}}}}}-\frac {1}{{\rm{e}}}=\frac {{\rm{e}}{{}^{2}}-{\rm{e}}{{}^{{\rm{e}}}}}{{\rm{e}}{{}^{{\rm{c}}+1}}}<0$ ，
23. 结合零点存在性定理可知： $H(x)$ 在 $(1,{\rm{e}})$ 内存在唯一零点，
24. 故曲线 $y=F(x)$ 和 $y=G(x)$ 在 $(1,{\rm{e}})$ 有唯一一个公共点，
25. 由图可得：若直线 $y=t$ 与两条曲线 $y=F(x)$ 和 $y=G(x)$ 共有三个不同的交点 $A\left ({x{{}_{1}},t}\right )$ ， $B\left ({x{{}_{2}},t}\right )$ ， $C\left ({x{{}_{3}},t}\right )$ ，其中 $F\left ({x{{}_{2}}}\right )=G\left ({x{{}_{2}}}\right )=t$ ，即 $\frac {x{{}_{2}}}{{\rm{e}}{{}^{x{{}_{2}}}}}=\frac {{\ln}x{{}_{2}}}{x{{}_{2}}}$ ，即 ${\rm{e}}{{}^{x{{}_{2}}}}\cdot {\ln}x{{}_{2}}=x{{}_{2}^{2}}$ ，
26. $F\left ({x{{}_{1}}}\right )=t$ ， $G\left ({x{{}_{3}}}\right )=t$ ， $x{{}_{1}}<x{{}_{2}}<x{{}_{3}}$ ，
27. 由 $F\left ({x{{}_{2}}}\right )=G\left ({x{{}_{2}}}\right )=F\left ({{\ln}x{{}_{2}}}\right )=F\left ({x{{}_{1}}}\right )$ ，又 $0<{\ln}x{{}_{2}}<1,0<x{{}_{1}}<1$ ，
28. 结合 $F(x)$ 在 $(-\infty ,1)$ 内单调递增，故 $x{{}_{1}}={\ln}x{{}_{2}}$ ，
29. 由 $f\left ({x{{}_{2}}}\right )=g\left ({x{{}_{2}}}\right )=g\left ({{\rm{e}}{{}^{x{{}_{2}}}}}\right )=g\left ({x{{}_{3}}}\right )$ ，又 ${\rm{e}}{{}^{x{{}_{2}}}}>{\rm{e}}$ ， $x{{}_{3}}>{\rm{e}}$ ，
30. 结合 $G(x)$ 在 $({\rm{e}},+\infty )$ 内单调递减，故 $x{{}_{3}}={\rm{e}}{{}^{x{{}_{2}}}}$ ，
31. 故 $x{{}_{1}}\cdot x{{}_{3}}={\rm{e}}{{}^{x{{}_{2}}}}\cdot {\ln}x{{}_{2}}=x{{}_{2}^{2}}$ ，故 $x{{}_{1}}$ ， $x{{}_{2}}$ ， $x{{}_{3}}$ 成等比数列.
32. 【点睛】关键点点睛：本题第二问的关键在于 $F\left ({x{{}_{2}}}\right )=G\left ({x{{}_{2}}}\right )=t$ ，即 $\frac {x{{}_{2}}}{{\rm{e}}{{}^{x{{}_{2}}}}}=\frac {{\ln}x{{}_{2}}}{x{{}_{2}}}$ ，利用 $F\left ({x{{}_{2}}}\right )=G\left ({x{{}_{2}}}\right )=F\left ({{\ln}x{{}_{2}}}\right )=F\left ({x{{}_{1}}}\right )$ ，且 $F(x)$ 在 $(-\infty ,1)$ 内单调递增，求得 $x{{}_{1}}={\ln}x{{}_{2}}$ ，同理利用 $F\left ({x{{}_{2}}}\right )=G\left ({x{{}_{2}}}\right )=G\left ({{\rm{e}}{{}^{x{{}_{2}}}}}\right )=G\left ({x{{}_{3}}}\right )$ ，且 $G(x)$ 在 $({\rm{e}},+\infty )$ 内单调递减，求得 $x{{}_{3}}={\rm{e}}{{}^{x{{}_{2}}}}$ ，即可用等比中项证明 $x{{}_{1}}$ ， $x{{}_{2}}$ ， $x{{}_{3}}$ 成等比数列.

## 知识点

**中文**:
  - 利用导数解决函数零点问题
  - 利用导数证明不等式
  - 等比数列的判定与证明

**English**:
  - Solving Zero Point Problems
  - Proving Inequalities using Derivatives
  - Determination and Proof

---
