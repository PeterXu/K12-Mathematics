# Mathematics - 题目 300

**ID**: 8685aa705ebb4052810962c74ae6488a
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f(x)={\ln}x+\frac {a}{2}x{^{2}}$ ， $g(x)=(a+1)x$ .​​​​​​​‌（1）若 $a=-1$ ，求 $f(x)$ 的最大值；（2）若函数 $h(x)=f(x)-g(x)$ ，讨论 $h(x)$ 的单调性；（3）若函数 $m(x)=f(x)-g(x)+x$ 有两个极值点 $x{{}_{1}}$ ， $x{{}_{2}}$ （ $x{{}_{1}}<x{{}_{2}}$ ），求证： $m\left ({x{{}_{1}}}\right )-m\left ({x{{}_{2}}}\right )<\frac {a}{2}-{\ln}a$ .

## 解答

1. （1）当 $a=-1$ 时， $f^{′}(x)=\frac {1-x{^{2}}}{x}$ ， $x\in \left ({0,+\infty }\right )$ ，
2. 当 $x\in \left ({0,1}\right )$ 时， $f^{′}(x)>0$ ，∴ $f(x)$ 单调递增，
3. 当 $x\in (1,+\infty )$ 时， $f^{′}(x)<0$ ，∴ $f(x)$ 单调递减，
4. 所以 $f(x)$ 的最大值为 $f(1)=-\frac {1}{2}$ ；
5. （2）由已知得 $h(x)=f(x)-g(x)={\ln}x+\frac {a}{2}x{^{2}}-(a+1)x$ ， $x\in \left ({0,+\infty }\right )$ ，
6. $h^{′}(x)=\frac {1}{x}+ax-\left ({a+1}\right )=\frac {ax{^{2}}-\left ({a+1}\right )x+1}{x}=\frac {(ax-1)(x-1)}{x}$ .
7. ①当 $a\leqslant 0$ 时，由 $x\in \left ({0,+\infty }\right )$ 得 $ax-1<0$
8. 所以当 $x\in \left ({0,1}\right )$ 时， $h^{′}(x)>0$ ， $h(x)$ 单调递增，
9. 当 $x\in (1,+\infty )$ 时， $h^{′}(x)<0$ ， $h(x)$ 单调递；
10. ②当 $a=1$ 时， $h{^{\prime }}(x)\geqslant 0$ ，所以当 $x\in (0,+\infty )$ 时， $h(x)$ 单调递增；
11. ③当 $0<a<1$ 时，由 $h^{′}(x)=\frac {(ax-1)(x-1)}{x}=0$ ，得 $x=1$ 或 $x=\frac {1}{a}>1$ ，
12. 所以当 $x\in \left ({0,1}\right )$ 与 $x\in \left ({\frac {1}{a},+\infty }\right )$ 时， $h^{′}(x)>0$ ， $h(x)$ 单调递增，
13. 当 $x\in \left ({1,\frac {1}{a}}\right )$ 时， $h^{′}(x)<0$ ， $h(x)$ 单调递减；
14. ④当 $a\mathrm{>}1$ 时，由 $h^{′}(x)=\frac {(ax-1)(x-1)}{x}=0$ ，得 $x=1$ 或 $x=\frac {1}{a}<1$ ，
15. 因而当 $x\in \left ({0,\frac {1}{a}}\right )$ 与 $x\in (1,+\infty )$ 时， $h^{′}{\left ({x}\right )}>0$ ， $h\left ({x}\right )$ 单调递增，
16. 当 $x\in \left ({\frac {1}{a},1}\right )$ 时， $h^{′}{\left ({x}\right )}<0$ ， $h(x)$ 单调递减.
17. 综上所述，当 $a\leqslant 0$ 时， $h(x)$ 在 $\left ({0,1}\right )$ 上单调递增，在 $(1,+\infty )$ 上单调递减；
18. 当 $0<a<1$ 时， $h(x)$ 在 $\left ({0,1}\right )$ 与 $\left ({\frac {1}{a},+\infty }\right )$ 上单调递增，在 $\left ({1,\frac {1}{a}}\right )$ 上单调递减；
19. 当$a=1$ 时， $h(x)$ 在 $(0,+\infty )$ 上单调递增；
20. 当 $a\mathrm{>}1$ 时， $h(x)$ 在 $\left ({0,\frac {1}{a}}\right )$ 与 $(1,+\infty )$ 上单调递增，在 $\left ({\frac {1}{a},1}\right )$ 上单调递减.
21. （3）证明： $m(x)={\ln}x+\frac {a}{2}x{^{2}}-ax$ ，则 $m(x)$ 的定义域为 $(0,+\infty )$ ，
22. $m{^{\prime }}(x)=\frac {ax{^{2}}-ax+1}{x}$ ，
23. 若 $m(x)$ 有两个极值点 $x{{}_{1}}$ ， $x{{}_{2}}$ （ $x{{}_{1}}<x{{}_{2}}$ ），
24. 则方程 $ax{^{2}}-ax+1=0$ 的判别式 $\Delta =a{^{2}}-4a>0$ ，且 $x{{}_{1}}\mathrm{+}x{{}_{2}}=1$ ， $x{{}_{1}}x{{}_{2}}=\frac {1}{a}>0$ ， $a>4$ ，
25. 又∵ $x{{}_{1}}<x{{}_{2}}$ ，∴ $x{{}_{1}^{2}}<x{{}_{1}}x{{}_{2}}=\frac {1}{a}$ ，即 $0<x{{}_{1}}<\frac {1}{\sqrt {a}}$ ，
26. $m\left ({x{{}_{1}}}\right )-m\left ({x{{}_{2}}}\right )={\ln}x{{}_{1}}-{\ln}\left ({\frac {1}{ax{{}_{1}}}}\right )+\frac {a}{2}\left [x{{}_{1}^{2}}-{\left({1-x{{}_{1}}}\right)^{2}}\right ]-a\left [x{{}_{1}}-\left ({1-x{{}_{1}}}\right )\right ]$
27. $={\ln}x{{}_{1}}+{\ln}\left ({ax{{}_{1}}}\right )+\frac {a}{2}-ax{{}_{1}}$ ，
28. 设 $p(t)={\ln}t+{\ln}(at)+\frac {a}{2}-at$ ，其中 $t=x{{}_{1}}\in \left ({0,\frac {1}{\sqrt {a}}}\right )$ ，
29. 由 $p^{′}(t)=\frac {2}{t}-a=0$ 得 $t=\frac {2}{a}$ ，
30. 由于 $\frac {2}{a}-\frac {1}{\sqrt {a}}=\frac {2-\sqrt {a}}{a}<0$ ，即 $\frac {2}{a}<\frac {1}{\sqrt {a}}$ ，
31. ∴ $p(t)$ 在 $\left ({0,\frac {2}{a}}\right )$ 上单调递增，在 $\left ({\frac {2}{a},\frac {1}{\sqrt {a}}}\right )$ 上单调递减，
32. 即 $p(t)$ 的最大值为 $p\left ({\frac {2}{a}}\right )=2\left ({{\ln}2-1}\right )+\frac {a}{2}-{\ln}a<\frac {a}{2}-{\ln}a$ ，
33. 从而 $m\left ({x{{}_{1}}}\right )-m\left ({x{{}_{2}}}\right )<\frac {a}{2}-{\ln}a$ 成立.

## 知识点

**中文**:
  - 利用导数研究函数的单调性与单调区间
  - 利用导数研究函数的极值
  - 利用导数研究函数的最值
  - 利用导数证明不等式

**English**:
  - Monotonicity and Monotonic Intervals
  - Extrema of Functions using Derivatives
  - Global Extrema (Max/Min) using Derivatives
  - Proving Inequalities using Derivatives

---
