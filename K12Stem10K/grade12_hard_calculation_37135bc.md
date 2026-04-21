# Mathematics - 题目 253

**ID**: 37135bcef9a741ffa7996a4fde70395a
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=ax-\frac {{\rm{l}}{\rm{n}}x}{x}$ ， $a>0$ ．(1)若 $f\left ({x}\right )$ 存在零点，求a的取值范围；​​​​​​​‌(2)若 $x{{}_{1}}$ , $x{{}_{2}}$ 为 $f\left ({x}\right )$ 的零点，且 $x{{}_{1}}<x{{}_{2}}$ ，证明： $a{\left({x{{}_{1}}+x{{}_{2}}}\right)^{2}}>2$ ．

## 解答

1. （1） $f\left ({x}\right )$ 的定义域为 $\left ({0,+\infty }\right )$ ，
2. 令 $f\left ({x}\right )=0$ ，即 $ax-\frac {{\rm{l}}{\rm{n}}x}{x}=0\left ({a>0}\right )$ ，等价于 $ax{^{2}}-{\rm{l}}{\rm{n}}x=0$ ，
3. 设 $g\left ({x}\right )=ax{^{2}}-{\rm{l}}{\rm{n}}x$ ，则 $g^{′}{\left ({x}\right )}=2ax-\frac {1}{x}=\frac {2ax{^{2}}-1}{x}$ （ $x>0$ ），
4. 令 $g^{′}{\left ({x}\right )}=0$ ，可得 $x=\frac {\sqrt {2a}}{2a}$ ，
5. 当 $x\in \left ({0,\frac {\sqrt {2a}}{2a}}\right )$ 时， $g^{′}{\left ({x}\right )}<0$ ， $g\left ({x}\right )$ 单调递减；
6. 当 $x\in \left ({\frac {\sqrt {2a}}{2a},+\infty }\right )$ 时， $g^{′}{\left ({x}\right )}>0$ ， $g\left ({x}\right )$ 单调递增，
7. 则 $g\left ({x}\right )$ 的最小值为 $g\left ({\frac {\sqrt {2a}}{2a}}\right )=\frac {1}{2}-{\rm{l}}{\rm{n}}\frac {\sqrt {2a}}{2a}=\frac {1}{2}\left ({1+{\rm{l}}{\rm{n}}2a}\right )$ ， $g\left ({1}\right )=a>0$ ，
8. 要使得 $g\left ({x}\right )=ax{^{2}}-{\rm{l}}{\rm{n}}x$ 存在零点，则 $g\left ({\frac {\sqrt {2a}}{2a}}\right )=\frac {1}{2}\left ({1+{\rm{l}}{\rm{n}}2a}\right )\leqslant 0$ ，
9. 即 $1+{\rm{l}}{\rm{n}}2a\leqslant 0$ ，得 $a\in \left ({0,\frac {1}{2{\rm{e}}}}\right ]$ ．
10. （2）由 $x{{}_{1}},x{{}_{2}}$ 为 $f\left ({x}\right )$ 的零点，得 $f\left ({x{{}_{1}}}\right )=f\left ({x{{}_{2}}}\right )=0$ ，
11. 即 $g\left ({x{{}_{1}}}\right )=g\left ({x{{}_{2}}}\right )=0$ ，即 $\begin{cases}ax{{}_{1}^{2}}-{\rm{l}}{\rm{n}}x{{}_{1}}=0,\\ax{{}_{2}^{2}}-{\rm{l}}{\rm{n}}x{{}_{2}}=0,\end{cases}$
12. 两式相减得 $a\left ({x{{}_{1}^{2}}-x{{}_{2}^{2}}}\right )-\left ({{\rm{l}}{\rm{n}}x{{}_{1}}-{\rm{l}}{\rm{n}}x{{}_{2}}}\right )=0$ ，即 $a=\frac {{\rm{l}}{\rm{n}}x{{}_{1}}-{\rm{l}}{\rm{n}}x{{}_{2}}}{\left ({x{{}_{1}}-x{{}_{2}}}\right )\left ({x{{}_{1}}+x{{}_{2}}}\right )}$ .
13. 要证当 $0<x{{}_{1}}<x{{}_{2}}$ 时， $a{\left({x{{}_{1}}+x{{}_{2}}}\right)^{2}}>2$ ，
14. 只需证 $\frac {{\rm{l}}{\rm{n}}x{{}_{1}}-{\rm{l}}{\rm{n}}x{{}_{2}}}{x{{}_{1}}-x{{}_{2}}}\left ({x{{}_{1}}+x{{}_{2}}}\right )>2$ ，只需证 ${\rm{l}}{\rm{n}}\frac {x{{}_{1}}}{x{{}_{2}}}<\frac {2\left ({x{{}_{1}}-x{{}_{2}}}\right )}{x{{}_{1}}+x{{}_{2}}}$ ， $0<x{{}_{1}}<x{{}_{2}}$ ，
15. ${\rm{l}}{\rm{n}}\frac {x{{}_{1}}}{x{{}_{2}}}-\frac {2\left ({\frac {x{{}_{1}}}{x{{}_{2}}}-1}\right )}{\frac {x{{}_{1}}}{x{{}_{2}}}+1}<0$ ， $0<x{{}_{1}}<x{{}_{2}}$ ．
16. 令 $t=\frac {x{{}_{1}}}{x{{}_{2}}}\left ({0<t<1}\right )$ ， $F\left ({t}\right )={\rm{l}}{\rm{n}}t-\frac {2\left ({t-1}\right )}{t+1}$ ，只需证 $F\left ({t}\right )<0$ ，
17. $F^{′}{\left ({t}\right )}=\frac {1}{t}-\frac {4}{{\left({t+1}\right)^{2}}}=\frac {{\left({t+1}\right)^{2}}-4t}{t{\left({t+1}\right)^{2}}}=\frac {{\left({t-1}\right)^{2}}}{t{\left({t+1}\right)^{2}}}>0$ ，则 $F\left ({t}\right )$ 在 $\left ({0,1}\right )$ 上单调递增，
18. 所以 $F\left ({t}\right )={\rm{l}}{\rm{n}}t-\frac {2\left ({t-1}\right )}{t+1}<F\left ({1}\right )=0$ ，即可得证.

## 知识点

**中文**:
  - 利用导数解决函数零点问题

**English**:
  - Solving Zero Point Problems

---
