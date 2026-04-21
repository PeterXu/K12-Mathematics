# Mathematics - 题目 2185

**ID**: 6611b878b0524a1cbefc7a29fc80579d
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
若函数 $F(x)$ 在开区间I内满足： $\exists x{{}_{i}}\in I(i=1,2,\cdot \cdot \cdot \cdot \cdot \cdot ,n)\left ({n\geqslant 2,n\in {\mathbf{N}}{^{*}}}\right )$ ， $y=F(x)$ 在 $x=x{{}_{i}}$ 处的切线的斜率均为 $m(m\in {\mathbf{R}})$ ，则称 $F(x)$ 为I内的“ $n-m$ 缘分函数”．（1）判断 $f(x)={\ln}x-x{^{2}}+2x$ 是否为 $(0,+\infty )$ 内的“ $2-3$ 缘分函数”，并说明理由；​​​​​​​‌（2）若 $g(x)=-{\ln}x-x{^{2}}+ax$ 为 $\left ({\frac {1}{3},1}\right )$ 内的“ $2-3$ 缘分函数”，求实数a的取值范围；（3）证明： $h(x)=\left ({x{^{2}}-2x+2}\right ){\rm e}{^{x}}-\frac {1}{2}x{^{2}}-2x{\ln}x+2x$ 不是 $(0,+\infty )$ 内的“ $n-1$ 缘分函数” $\left ({n\geqslant 2,n\in {\mathbf{N}}{^{*}}}\right )$ ．

## 解答

1. （1）求导得 $f(x)=\frac {1}{x}-2x+2$ ，
2. $f(x)={\ln}x-x{^{2}}+2x$ 为 $(0,+\infty )$ 内的“ $2-3$ 缘分函数”当且仅当方程 $f(x)=\frac {1}{x}-2x+2=3$ 在 $(0,+\infty )$ 内有两个不同的解，
3. 而 $y=\frac {1}{x},y=-2x+2$ 在 $(0,+\infty )$ 上单调递减，即 $f(x)=\frac {1}{x}-2x+2=3$ 在 $(0,+\infty )$ 上单调递减，
4. 故方程 $f(x)=\frac {1}{x}-2x+2=3$ 在 $(0,+\infty )$ 内最多有一个解，
5. 从而 $f(x)={\ln}x-x{^{2}}+2x$ 不是 $(0,+\infty )$ 内的“ $2-3$ 缘分函数”；
6. （2）原条件等价于 $g^{′}{\left ({x}\right )}=-\frac {1}{x}-2x+a=3$ 在 $\left ({\frac {1}{3},1}\right )$ 内有两个不同的解，
7. 即 $a=3+2x+\frac {1}{x}$ 在 $\left ({\frac {1}{3},1}\right )$ 内有两个不同的解，
8. 设 $u\left ({x}\right )=3+2x+\frac {1}{x},x\in \left [\frac {1}{3},1\right ]$ ，
9. 由对勾函数性质可知 $u\left ({x}\right )=3+2x+\frac {1}{x}$ 在 $\left [\frac {1}{3},\frac {\sqrt {2}}{2}\right ]$ 上单调递减，在 $\left [\frac {\sqrt {2}}{2},1\right ]$ 上单调递增，
10. 注意到 $u\left ({\frac {1}{3}}\right )=20,u\left ({1}\right )=6,u\left ({\frac {\sqrt {2}}{2}}\right )=3+2\sqrt {2}$ ，
11. 故所求为 $\left ({3+2\sqrt {2},6}\right )$ ；
12. （3）由题意只需证明 $h^{′}{\left ({x}\right )}=\left ({x{^{2}}-2x+2+2x-2}\right ){\rm e}{^{x}}-x-2{\ln}x-2+2=x{^{2}}{\rm e}{^{x}}-x-2{\ln}x=1$ 在 $(0,+\infty )$ 内最多有1个根，
13. 令 $v\left ({x}\right )=h^{′}{\left ({x}\right )}-1=x{^{2}}{\rm e}{^{x}}-x-2{\ln}x-1,x\in (0,+\infty )$ ，
14. 即证 $v\left ({x}\right )=h^{′}{\left ({x}\right )}-1=x{^{2}}{\rm e}{^{x}}-x-2{\ln}x-1,x\in (0,+\infty )$ 最多有一根，
15. 求导得 $v^{′}{\left ({x}\right )}=\left ({x{^{2}}+2x}\right ){\rm e}{^{x}}-1-\frac {2}{x}=x\left ({x+2}\right )\left ({{\rm e}{^{x}}-\frac {1}{x{^{2}}}}\right ),x\in (0,+\infty )$ ，
16. 当 $x>0$ 时， $x\left ({x+2}\right )>0,y={\rm e}{^{x}},y=-\frac {1}{x{^{2}}}$ 在 $(0,+\infty )$ 上都单调递增，
17. 设 $m\left ({x}\right )={\rm e}{^{x}}-\frac {1}{x{^{2}}},x\in (0,+\infty )$ ，注意到 $m\left ({\frac {1}{2}}\right )=\sqrt {{\rm e}}-4<0,m\left ({1}\right )={\rm e}-1>0$ ，
18. 从而当 $x>0$ 时，存在唯一的 $x{{}_{0}}\in \left ({\frac {1}{2},1}\right )$ ，使得 $m\left ({x{{}_{0}}}\right )={\rm e}{^{x{{}_{0}}}}-\frac {1}{x{{}_{0}^{2}}}=0$ ，即有 $x{{}_{0}}=-2{\ln}x{{}_{0}}$ 成立，
19. 当 $0<x<x{{}_{0}}$ 时， $v^{′}{\left ({x}\right )}<0$ ，当 $x>x{{}_{0}}$ 时， $v^{′}{\left ({x}\right )}>0$ ，
20. 所以 $v\left ({x}\right )$ 在 $\left ({0,x{{}_{0}}}\right )$ 上单调递减，在 $\left ({x{{}_{0}},+\infty }\right )$ 上单调递增，
21. 所以 $v\left ({x}\right )$ 有最小值 $v\left ({x}\right ){{}_{{\rm \min }}}=v\left ({x{{}_{0}}}\right )=x{{}_{0}^{2}}{\rm e}{^{x{{}_{0}}}}-x{{}_{0}}-2{\ln}x{{}_{0}}-1=1-x{{}_{0}}-\left ({-x{{}_{0}}}\right )-1=0$ ，
22. 这表明 $v\left ({x}\right )=h^{′}{\left ({x}\right )}-1=x{^{2}}{\rm e}{^{x}}-x-2{\ln}x-1,x\in (0,+\infty )$ 最多有一根，
23. 综上所述，命题得证.

## 知识点

**中文**:
  - 利用导数解决新定义问题

**English**:
  - Solving New Definition Problems

---
