# Mathematics - 题目 498

**ID**: 1f76e259072d455fb8bf7b75ba64b7b8
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f(x)={\log}{{}_{4}}\left ({4{^{x}}+1}\right )-{\log}{{}_{4}}2{^{x}}$ ， $g(x)={\log}{{}_{4}}\left ({a\cdot 2{^{x-1}}-\frac {2}{3}a}\right )$ .​​​​​​​‌(1)若 $\forall x{{}_{1}}\in {\mathbf{R}}$ ，对 $\exists x{{}_{2}}\in [-1,1]$ ，使得 $f\left ({x{{}_{1}}}\right )+4{^{x{{}_{2}}}}-m2{^{x{{}_{2}}}}\geqslant 0$ 成立，求实数 $m$ 的取值范围；(2)若函数 $f(x)$ 与 $g(x)$ 的图象有且只有一个公共点，求实数 $a$ 的取值范围.

## 解答

1. （1） $f\left ({x{{}_{1}}}\right )+4{^{x{{}_{2}}}}-m\cdot 2{^{x{{}_{2}}}}\geqslant 0$ ，即 $f\left ({x{{}_{1}}}\right )\geqslant m\cdot 2{^{x{{}_{2}}}}-4{^{x{{}_{2}}}}$ ，
2. 若 $\forall x{{}_{1}}\in {\mathbf{R}}$ ，使得 $f\left ({x{{}_{1}}}\right )+4{^{x{{}_{2}}}}-m\cdot 2{^{x{{}_{2}}}}\geqslant 0$ 成立，只需要 $f(x){{}_{{\rm \min }}}\geqslant m\cdot 2{^{x{{}_{2}}}}-4{^{x{{}_{2}}}}$ 成立.
3. 因为 $f(x)={\log}{{}_{4}}\left ({4{^{x}}+1}\right )-{\log}{{}_{4}}2{^{x}}={\log}{{}_{4}}\frac {4{^{x}}+1}{2{^{x}}}={\log}{{}_{4}}\left ({2{^{x}}+\frac {1}{2{^{x}}}}\right )$ ，
4. 由基本不等式可得 $2{^{x}}+\frac {1}{2{^{x}}}\geqslant 2\sqrt {2{^{x}}\cdot \frac {1}{2{^{x}}}}=2$ ，当且仅当 $x=0$ 时，等号成立，
5. 所以 $f(x){{}_{{\rm \min }}}=f(0)={\log}{{}_{4}}2=\frac {1}{2}$ ，则 $m\cdot 2{^{x{{}_{2}}}}-4{^{x{{}_{2}}}}\leqslant \frac {1}{2}$ ，
6. 因为 $x{{}_{2}}\in [-1,1]$ ，令 $p=2{^{x{{}_{2}}}}\in \left [\frac {1}{2},2\right ]$ ，分离参数可得 $m\leqslant \frac {1}{2p}+p$ ，
7. 令 $h(p)=p+\frac {1}{2p}$ ，其中 $p\in \left [\frac {1}{2},2\right ]$ ，
8. 函数 $h(p)$ 在 $\left [\frac {1}{2},\frac {\sqrt {2}}{2}\right ]$ 上单调递减，在 $\left [\frac {\sqrt {2}}{2},2\right ]$ 上单调递增，
9. 故 $h(p){{}_{{\rm \max }}}={\rm \max }\left \{h\left ({\frac {1}{2}}\right ),h(2)\right \}=h(2)=\frac {9}{4}$ ，所以 $m\leqslant \frac {9}{4}$ .
10. 所以实数 $m$ 的取值范围为 $\left ({-\infty ,\frac {9}{4}}\right ]$ .
11. （2）由（1）可得 $f(x)={\log}{{}_{4}}\left ({4{^{x}}+1}\right )-{\log}{{}_{4}}2{^{x}}={\log}{{}_{4}}\frac {4{^{x}}+1}{2{^{x}}}={\log}{{}_{4}}\left ({2{^{x}}+\frac {1}{2{^{x}}}}\right )$ ，
12. 由题意知，方程 ${\log}{{}_{4}}\left ({2{^{x}}+2{^{-x}}}\right )={\log}{{}_{4}}\left ({a\cdot 2{^{x-1}}-\frac {2}{3}a}\right )$ 有且只有一个实根，
13. 即方程 $2{^{x}}+2{^{-x}}=a\cdot 2{^{x-1}}-\frac {2}{3}a$ 有且只有一个实根，
14. 令 $t=2{^{x}}>0$ ，则方程 $t+\frac {1}{t}=\frac {a}{2}t-\frac {2}{3}a$ 有且只有一个正根，
15. 即方程 $\left ({\frac {a}{2}-1}\right )t{^{2}}-\frac {2}{3}at-1=0$ 有且只有一个正根，构造函数 $φ(t)=\left ({\frac {a}{2}-1}\right )t{^{2}}-\frac {2}{3}at-1$ .
16. ①当 $a=2$ 时， $φ(t)=-\frac {4}{3}t-1$ ，令 $φ(t)=0$ ，解得 $t=-\frac {3}{4}$ ，不合乎题意；
17. ②当 $a<2$ 时，则 $\frac {a}{2}-1<0$ ，二次函数 $φ(t)$ 的图象开口向下，对称轴为直线 $t=\frac {2a}{3(a-2)}$ ，
18. $Δ={\left({-\frac {2}{3}a}\right)^{2}}+4\left ({\frac {a}{2}-1}\right )=\frac {4}{9}a{^{2}}+2a-4=\frac {2}{9}\left ({2a{^{2}}+9a-18}\right )=\frac {2}{9}(2a-3)(a+6)$ ，
19. 因为 $φ(0)=-1<0$ ，要使得方程 $\left ({\frac {a}{2}-1}\right )t{^{2}}-\frac {2}{3}at-1=0$ 有且只有一个正根，
20. 则 $\begin{cases}Δ=0\\\frac {2a}{3\left ({a-2}\right )}>0\end{cases}$ ，解得 $a=-6$ ；
21. ③当 $a>2$ 时，则 $\frac {a}{2}-1>0,Δ=\frac {2}{9}(2a-3)(a+6)>0$ ，
22. 设方程 $\left ({\frac {a}{2}-1}\right )t{^{2}}-\frac {2}{3}at-1=0$ 的两根分别为 $t{{}_{1}}$ ， $t{{}_{2}}$ ，
23. 由韦达定理可得 $t{{}_{1}}t{{}_{2}}=-\frac {2}{a-2}<0$ ，则方程 $\left ({\frac {a}{2}-1}\right )t{^{2}}-\frac {2}{3}at-1=0$ 有且只有一个正根.
24. 综上所述，实数 $a$ 的取值范围是 $\{-6\}\cup (2,+\infty )$ .

## 知识点

**中文**:
  - 指数函数与对数函数的综合应用

**English**:
  - Integrated Applications

---
