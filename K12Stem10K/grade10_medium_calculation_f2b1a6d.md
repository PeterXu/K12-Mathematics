# Mathematics - 题目 1135

**ID**: f2b1a6da34b346b49b8811b0432a00b9
**年级**: Grade 10
**难度**: Medium
**题型**: Calculation

## 题目
在数学中，布劳威尔不动点定理是拓扑学里一个非常重要的不动点定理，它可应用到有限维空间，并构成一般不动点定理的基石，布劳威尔不动点定理得名于荷兰数学家鲁伊兹•布劳威尔（ ${\rm{L}}{{.​​​​​​​‌}}{\rm{E}}{{.}}{\rm{J}}{{.}}{\rm{B}}{\rm{r}}{\rm{o}}{\rm{u}}{\rm{w}}{\rm{e}}{\rm{r}}$ ），简单的讲就是对于满足一定条件的图象不间断的函数 $f\left ({x}\right )$ ，存在点 $x{{}_{0}}$ ，使 $f\left ({x{{}_{0}}}\right )=x{{}_{0}}$ ，那么我们称该函数为“不动点函数”， $x{{}_{0}}$ 为函数的不动点.（1）若定义在 ${\mathbf{R}}$ 上仅有一个不动点的函数 $f\left ({x}\right )$ 满足 $f\left ({f\left ({x}\right )-2x{^{2}}+x}\right )=f\left ({x}\right )-2x{^{2}}+x$ ，试求函数 $f\left ({x}\right )$ 的解析式；（2）若对任意的实数 $b$ ，若函数 $g\left ({x}\right )=ax{^{2}}-\left ({3b-1}\right )x-2b+\frac {1}{3}\left ({a\ne 0}\right )$ 恒有两个不动点，且满足如下条件：① $y=g\left ({x}\right )$ 图象上两个不同点 $M,N$ 的横坐标是函数 $g\left ({x}\right )$ 的不动点；②点 $M,N$ 关于函数 $h\left ({x}\right )=-x+\frac {a}{3a{^{2}}+4a+2}$ 的图象对称.试求 $b$ 的取值范围.（注：两个点 $M\left ({x{{}_{1}},y{{}_{1}}}\right ),N\left ({x{{}_{2}},y{{}_{2}}}\right )$ 的中点 $C$ 的坐标公式为 $C\left ({\frac {x{{}_{1}}+x{{}_{2}}}{2},\frac {y{{}_{1}}+y{{}_{2}}}{2}}\right )$ ）

## 解答

1. （1）设函数 $f\left ({x}\right )$ 的唯一不动点为 $t$ ，即 $f\left ({t}\right )=t$ ，
2. ∵ $f\left ({f\left ({x}\right )-2x{^{2}}+x}\right )=f\left ({x}\right )-2x{^{2}}+x$ ，
3. ∴ $f\left ({x}\right )-2x{^{2}}+x=t$ ，
4. ∴ $f\left ({t}\right )-2t{^{2}}+t=t$ ，得 $t-2t{^{2}}+t=t$ ，解得 $t=0$ 或 $t=\frac {1}{2}$ ，
5. 当 $t=0$ 时， $f\left ({x}\right )=2x{^{2}}-x$ ，
6. 由 $f\left ({x}\right )=x$ ，得 $2x{^{2}}-x=x$ ，解得 $x=0$ 或 $x=1$ ，
7. 此时 $f\left ({x}\right )$ 有两个不动点，不合题意；
8. 当 $t=\frac {1}{2}$ 时， $f\left ({x}\right )=2x{^{2}}-x+\frac {1}{2}$ ，
9. 由 $f\left ({x}\right )=x$ ，得 $2x{^{2}}-x+\frac {1}{2}=x$ ，解得 $x=\frac {1}{2}$ ，
10. 此时 $f\left ({x}\right )$ 只有一个不动点，符合题意，
11. 综上，函数 $f\left ({x}\right )$ 的解析式为 $f\left ({x}\right )=2x{^{2}}-x+\frac {1}{2}$ ．
12. （2）由 $g\left ({x}\right )=x$ ，得 $ax{^{2}}-3bx-2b+\frac {1}{3}=0$ ，
13. ∵对任意的实数 $b$ ，函数 $g\left ({x}\right )$ 恒有两个不动点，
14. ∴对任意的实数 $b$ ， $\Delta =9b{^{2}}+8ab-\frac {4a}{3}>0$ 恒成立，
15. 于是 ${\rm{Δ}}{{}_{1}}={\left({8a}\right)^{2}}-4\times 9\times \left ({-\frac {4a}{3}}\right )<0$ ，即 $4a{^{2}}+3a<0$ ，又 $a\ne 0$ ，解得 $-\frac {3}{4}<a<0$ ，
16. 设函数 $g\left ({x}\right )$ 的两个不动点为 $x{{}_{1}},x{{}_{2}}$ ，则 $M\left ({x{{}_{1}},x{{}_{1}}}\right ),N\left ({x{{}_{2}},x{{}_{2}}}\right )$ ，又 $x{{}_{1}}+x{{}_{2}}=\frac {3b}{a}$ ，
17. 于是线段 $MN$ 的中点 $C\left ({\frac {x{{}_{1}}+x{{}_{2}}}{2},\frac {x{{}_{1}}+x{{}_{2}}}{2}}\right )$ ，即 $C\left ({\frac {3b}{2a},\frac {3b}{2a}}\right )$ ，
18. 由题意，点 $C$ 在函数 $h\left ({x}\right )=-x+\frac {a}{3a{^{2}}+4a+2}$ 的图象上，得 $-\frac {3b}{2a}+\frac {a}{3a{^{2}}+4a+2}=\frac {3b}{2a}$ ，整理得 $b=\frac {1}{3}\cdot \frac {a{^{2}}}{3a{^{2}}+4a+2}$ ，
19. ∴ $b=\frac {1}{3}\cdot \frac {1}{2{\left({\frac {1}{a}}\right)^{2}}+\frac {4}{a}+3}=\frac {1}{3}\cdot \frac {1}{2{\left({\frac {1}{a}+1}\right)^{2}}+1}$ ，
20. ∵ $-\frac {3}{4}<a<0$ ，∴ $\frac {1}{a}<-\frac {4}{3}$ ， $\frac {1}{a}+1<-\frac {1}{3}$ ，
21. ∴ ${\left({\frac {1}{a}+1}\right)^{2}}>\frac {1}{9}$ ， $2{\left({\frac {1}{a}+1}\right)^{2}}+1>\frac {11}{9}$ ， $0<\frac {1}{2{\left({\frac {1}{a}+1}\right)^{2}}+1}<\frac {9}{11}$ ，
22. ∴ $0<b<\frac {3}{11}$ ．

## 知识点

**中文**:
  - 函数新定义问题

**English**:
  - New Definition Problems in Functions

---
