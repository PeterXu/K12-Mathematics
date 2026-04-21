# Mathematics - 题目 2313

**ID**: b2a7203e4f7c4091ab3b678e080606aa
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
对于定义域为 $I$ 的函数 $f(x)$ ，如果存在区间 $[m,n]\subseteq I$ ，使得 $f(x)$ 在区间 $[m,n]$ 上是单调函数.​​​​​​​‌且函数 $y=f(x),x\in [m,n]$ 的值域是 $[m,n]$ ，则称区间 $[m,n]$ 是函数 $f(x)$ 的一个“优美区间”（1）判断函数 $y=x{^{2}}(x\in \mathbf{R})$ 和函数 $y=3-\frac {4}{x}(x>0)$ 是否存在“优美区间”？（直接写出结论，不要求证明）（2）如果 $[m,n]$ 是函数 $f(x)=\frac {(a{^{2}}+a)x-1}{a{^{2}}x}(a\ne 0)$ 的一个“优美区间”，求 $n-m$ 的最大值；（3）如果函数 $g(x)=x{^{2}}+a$ 在 $\mathbf{R}$ 上存在“优美区间”，求实数 $a$ 的取值范围.

## 解答

1. （1） $y=x{^{2}}\geqslant 0$ ， $y=x{^{2}}$ 在 $[0,+\infty )$ 上单调递增，由 $x{^{2}}=x$ 得 $x=0$ 或1，存在优美区间是 $[0,1]$ ，
2. $y=3-\frac {4}{x}(x>0)$ 是单调递增函数，若存在优美区间 $[m,n]$ ，则 $\begin{cases}3-\frac {4}{m}=m，\\3-\frac {4}{n}=n，\end{cases}$ 无解，不合题意，不存在优美区间.
3. （2） $f(x)=\frac {(a{^{2}}+a)x-1}{a{^{2}}x}=1+\frac {1}{a}-\frac {1}{a{^{2}}x}$ 在 $(-\infty ,0)$ 和 $(0,+\infty )$ 上都是单调递增函数，
4. 因此优美区间 $[m,n]\subseteq (-\mathrm{∞},0)$ 或 $[m,n]\subseteq (0,+\mathrm{∞})$ ，
5. 由题意 $\begin{cases}f(m)=m，\\f(n)=n，\end{cases}$ 所以 $f(x)=x$ 有两个同号的不等实根，
6. $f(x)=1+\frac {1}{a}-\frac {1}{a{^{2}}x}=x$ ， $a{^{2}}x{^{2}}-(a{^{2}}+a)x+1=0$ ，
7. $Δ=(a{^{2}}+a){^{2}}-4a{^{2}}>0$ ， $a{^{2}}(a+3)(a-1)>0$ ， $a<-3$ 或 $a>1$ ，
8. $x{{}_{1}}x{{}_{2}}=\frac {1}{a{^{2}}}>0$ ， $x{{}_{1}},x{{}_{2}}$ 同号，满足题意，
9. $x{{}_{1}}+x{{}_{2}}=\frac {a{^{2}}+a}{a{^{2}}}=\frac {a+1}{a}$ ，
10. $n-m=\left |{x{{}_{1}}-x{{}_{2}}}\right |=\sqrt {(x{{}_{1}}+x{{}_{2}}){^{2}}-4x{{}_{1}}x{{}_{2}}}=\sqrt {\frac {(a+1){^{2}}}{a{^{2}}}-\frac {4}{a{^{2}}}}=\sqrt {-\frac {3}{a{^{2}}}+\frac {2}{a}+1}$
11. $=\sqrt {-3(\frac {1}{a}-\frac {1}{3}){^{2}}+\frac {4}{3}}$ ，
12. 因为 $a<-3$ 或 $a>1$ ，所以当 $\frac {1}{a}=\frac {1}{3}$ ，即 $a=3$ 时， $(n-m){{}_{{\rm \max }}}=\sqrt {\frac {4}{3}}=\frac {2\sqrt {3}}{3}$ ．
13. （3）函数 $g(x)=x{^{2}}+a$ 在 $\mathbf{R}$ 上存在“优美区间”，设 $[m,n]$ 得其一个优美区间，
14. $g(x)$ 在 $(-\infty ,0)$ 上单调递减，在 $(0,+\infty )$ 上单调递增，
15. 若 $m\geqslant 0$ ，则 $\begin{cases}g(m)=m，\\g(n)=n，\end{cases}$ 即 $g(x)=x$ 有两个不等的非负根，
16. $x{^{2}}+a=x$ ， $x{^{2}}-x+a=0$ ， $Δ=1-4a>0$ ， $a<\frac {1}{4}$ ，
17. $\begin{cases}x{{}_{1}}+x{{}_{2}}=1，\\x{{}_{1}}x{{}_{2}}=a，\end{cases}$ 则 $a\geqslant 0$ ，所以 $0\leqslant a\mathrm{<}\frac {1}{4}$ ；
18. 若 $n\leqslant 0$ ，则 $\begin{cases}g(m)=n，\\g(n)=m，\end{cases}$ 即 $\begin{cases}m{^{2}}+a=n，\\n{^{2}}+a=m，\end{cases}$ 两式相减得 $(m+n)(m-n)=n-m$ ， $m+n=\mathrm{-}1$ ，
19. $\begin{cases}m{^{2}}+a=-1-m，\\n{^{2}}+a=-1-n，\end{cases}$ 所以方程 $x{^{2}}+a=-1-x$ 有两个不等的非正根，
20. 方程整理为 $x{^{2}}+x+a+1=0$ ，
21. $Δ=1-4(a+1)>0$ ， $a<-\frac {3}{4}$ ， $x{{}_{1}}+x{{}_{2}}=-1<0$ 满足题意， $x{{}_{1}}x{{}_{2}}=a+1\geqslant 0$ ， $a\geqslant -1$ ，
22. 所以 $-1\leqslant a<-\frac {3}{4}$ ；
23. 综上， $a$ 的取值范围是 $-1\leqslant a<-\frac {3}{4}$ 或 $0\leqslant a\mathrm{<}\frac {1}{4}$ ．

## 知识点

**中文**:
  - 二次函数的图象与性质
  - 函数新定义问题

**English**:
  - Graph and Properties of Quadratic Functions
  - New Definition Problems in Functions

---
