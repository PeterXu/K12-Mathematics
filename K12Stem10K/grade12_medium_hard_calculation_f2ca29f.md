# Mathematics - 题目 2467

**ID**: f2ca29f450b6458d8132f2096cc961a0
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
若变量 $x,y$ 满足： $x>0,y>0$ ，且 ${\left({\frac {x}{a}}\right)^{m}}+{\left({\frac {y}{b}}\right)^{m}}=1$ ，其中 $a>0,b>0,m\in {\mathbf{Z}}$ 且 $m\ne 0$ ，则称 $y$ 是 $x$ 的“ $m$ 型函数”.​​​​​​​‌(1)已知 $b=1,y$ 是 $x$ 的“2型函数”，求该函数在点 $\left ({1,\frac {\sqrt {3}}{2}}\right )$ 处的切线方程；(2)已知 $y$ 是 $x$ 的“ $-1$ 型函数”.${\rm （i）}$ 求 $x+y$ 的最小值；${\rm （ii）}$ 求证： $x{^{n}}+y{^{n}}\geqslant {\left({a{^{\frac {n}{n+1}}}+b{^{\frac {n}{n+1}}}}\right)^{n+1}}\left ({n\in {\mathbf{N}}{^{{\rm{*}}}}}\right )$ .

## 解答

1. （1）由题意，有 ${\left({\frac {1}{a}}\right)^{2}}+{\left({\frac {\sqrt {3}}{2}}\right)^{2}}=1$ ，得 $a=2$ ，
2. 有 $\frac {x{^{2}}}{4}+y{^{2}}=1$ ，有 $y=\sqrt {1-\frac {x{^{2}}}{4}}$ ，则 $y^{′}=\frac {-\frac {1}{4}\cdot 2x}{2\sqrt {1-\frac {x{^{2}}}{4}}}=\frac {-x}{4\sqrt {1-\frac {x{^{2}}}{4}}}$ ，
3. 有 $\left .{y^{′}}\right |{{}_{x=1}}=\frac {-1}{2\sqrt {3}}$ ，故该函数在点 $\left ({1,\frac {\sqrt {3}}{2}}\right )$ 处的切线方程为 $y-\frac {\sqrt {3}}{2}=\frac {-1}{2\sqrt {3}}\left ({x-1}\right )$ ，
4. 即 $x+2\sqrt {3}y-4=0$ ；
5. （2）因为 $y$ 是 $x$ 的“ $-1$ 型函数”，所以 $\frac {a}{x}+\frac {b}{y}=1$ ，
6. 由 $\frac {a}{x}<1,\frac {b}{y}<1$ ，有 $x>a,y>b$ .
7. ${\rm （i）}x+y=\left ({x+y}\right )\left ({\frac {a}{x}+\frac {b}{y}}\right )=a+b+\frac {bx}{y}+\frac {ay}{x}\geqslant a+b+2\sqrt {\frac {bx}{y}\cdot \frac {ay}{x}}=(\sqrt {a}+\sqrt {b}){^{2}}$ ，
8. 当且仅当 $\frac {a}{x}+\frac {b}{y}=1,\frac {bx}{y}=\frac {ay}{x}$ ，即 $x=a+\sqrt {ab},y=b+\sqrt {ab}$ 时“ $=$ ”成立.
9. ${\rm （ii）}$ 由 $\frac {a}{x}+\frac {b}{y}=1$ ，有 $y=\frac {bx}{x-a}$ ，
10. 记 $x{^{n}}+y{^{n}}=x{^{n}}+{\left({\frac {bx}{x-a}}\right)^{n}}=f\left ({x}\right )\left ({x>a}\right ){\rm{,}}$
11. $f^{′}{\left ({x}\right )}=nx{^{n-1}}+n{\left({\frac {bx}{x-a}}\right)^{n-1}}\frac {b\left ({x-a}\right )-bx}{(x-a){^{2}}}=\frac {nx{^{n-1}}}{(x-a){^{n+1}}}\left [(x-a){^{n+1}}-ab{^{n}}\right ]$ ，
12. 由 $f^{′}{\left ({x}\right )}=0$ ，得 $x=a+\sqrt[n+1]{ab{^{n}}}$ ，
13. 当 $x\in \left ({a,a+\sqrt[n+1]{ab{^{n}}}}\right )$ 时， $f^{′}{\left ({x}\right )}<0,f\left ({x}\right )$ 单调递减，
14. 当 $x\in \left ({a+\sqrt[n+1]{ab{^{n}}},+∞}\right )$ 时， $f^{′}{\left ({x}\right )}>0,f\left ({x}\right )$ 单调递增，
15. 因此，有
16. $f\left ({x}\right )\geqslant f\left ({a+\sqrt[n+1]{ab{^{n}}}}\right )={\left({a+\sqrt[n+1]{ab{^{n}}}}\right)^{n}}+\left [\frac {b\left ({a+\sqrt[n+1]{ab{^{n}}}}\right )}{a+\sqrt[n+1]{ab{^{n}}}-a}\right ]{^{n}}={\left({a+\sqrt[n+1]{ab{^{n}}}}\right)^{n}}\left [1+{\left({\frac {\sqrt[n+1]{b}}{\sqrt[n+1]{a}}}\right)^{n}}\right ]$
17. $={\left({\sqrt[n+1]{a{^{n}}}+\sqrt[n+1]{b{^{n}}}}\right)^{n}}\cdot \left [(\sqrt[n+1]{a}){^{n}}+(\sqrt[n+1]{b}){^{n}}\right ]={\left({a{^{\frac {n}{n+1}}}+b{^{\frac {n}{n+1}}}}\right)^{n}}\cdot \left ({a{^{\frac {n}{n+1}}}+b{^{\frac {n}{n+1}}}}\right )={\left({a{^{\frac {n}{n+1}}}+b{^{\frac {n}{n+1}}}}\right)^{n+1}}$
18. 这也就证明了 $x{^{n}}+y{^{n}}\geqslant {\left({a{^{\frac {n}{n+1}}}+b{^{\frac {n}{n+1}}}}\right)^{n+1}}\left ({n\in {\mathbf{N}}{^{{\rm{*}}}}}\right )$ .

## 知识点

**中文**:
  - 利用导数解决新定义问题

**English**:
  - Solving New Definition Problems

---
