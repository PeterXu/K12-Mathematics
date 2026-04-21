# Mathematics - 题目 2818

**ID**: d68fe5457a0d48e58d596ecc9d441e7f
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f(x)=a({\ln}x+1)+\frac {1}{x{^{3}}}(a>0)$ ．(1)求证： $1+x{\ln}x>0$ ；​​​​​​​‌(2)若 $x{{}_{1}},x{{}_{2}}$ 是 $f(x)$ 的两个相异零点，求证： $\left |{x{{}_{2}}-x{{}_{1}}}\right |<1-\sqrt {\frac {1}{a}}$ ．

## 解答

1. （1）令 $g(x)=1+x{\ln}x,x\in (0,+\infty )$ ，则 $g{^{\prime }}(x)=1+{\ln}x$ ．
2. 令 $g^{′}(x)>0$ ，得 $x>\frac {1}{{\rm{e}}}$ ；令 $g^{′}(x)<0$ ，得 $0<x<\frac {1}{{\rm{e}}}$ ，
3. 所以 $g(x)$ 在 $\left ({0,\frac {1}{{\rm{e}}}}\right )$ 上单调递减，在 $\left ({\frac {1}{{\rm{e}}},+\infty }\right )$ 上单调递增，
4. 所以 $g(x){{}_{{\rm \min }}}=g\left ({\frac {1}{{\rm{e}}}}\right )=1-\frac {1}{{\rm{e}}}>0$ ，所以 $1+x{\ln}x>0$ ．
5. （2）易知函数 $f(x)$ 的定义域是 $(0,+\infty )$ ．
6. 由 $f(x)=a({\ln}x+1)+\frac {1}{x{^{3}}}$ ，可得 $f{^{\prime }}(x)=\frac {a}{x}-\frac {3}{x{^{4}}}=\frac {ax{^{3}}-3}{x{^{4}}}$ ．
7. 令 $f^{′}(x)>0$ 得 $x>\sqrt[3]{\frac {3}{a}}$ ；令 $f^{′}(x)<0$ 得 $0<x<\sqrt[3]{\frac {3}{a}}$ ，
8. 所以 $f^{′}(x)>0$ 在 $\left ({0,\sqrt[3]{\frac {3}{a}}}\right )$ 上单调递减，在 $\left ({\sqrt[3]{\frac {3}{a}},+\infty }\right )$ 上单调递增，
9. 所以 $f(x){{}_{{\rm \min }}}=f\left ({\sqrt[3]{\frac {3}{a}}}\right )=\frac {a}{3}\left ({{\ln}\frac {3}{a}+3}\right )+\frac {a}{3}$ ．
10. ①当 $\frac {a}{3}\left ({{\ln}\frac {3}{a}+3}\right )+\frac {a}{3}\geqslant 0$ ，即 $0<a\leqslant 3{\rm{e}}{^{4}}$ 时， $f(x)$ 至多有1个零点，故不满足题意．
11. ②当 $\frac {a}{3}\left ({{\ln}\frac {3}{a}+3}\right )+\frac {a}{3}<0$ ，即 $a>3{\rm{e}}{^{4}}$ 时， $\sqrt[3]{\frac {3}{a}}<\sqrt[3]{\frac {1}{{\rm{e}}{^{4}}}}<1$ ．
12. 因为 $f(x)$ 在 $\left ({\sqrt[3]{\frac {3}{a}},+\infty }\right )$ 上单调递增，且 $f(1)=a+1>0$ ，所以 $f(1)\cdot f\left ({\sqrt[3]{\frac {3}{a}}}\right )<0$ ，
13. 所以 $f(x)$ 在 $\left ({\sqrt[3]{\frac {3}{a}},+\infty }\right )$ 上有且只有1个零点，不妨记为 $x{{}_{1}}$ ，且 $\sqrt[3]{\frac {3}{a}}<x{{}_{1}}<1$ ．
14. 由（1）知 ${\ln}x>-\frac {1}{x}$ ，所以 $f\left ({\sqrt {\frac {1}{a}}}\right )=a\left ({{\ln}\sqrt {\frac {1}{a}}+1}\right )+a{^{\frac {3}{2}}}>a(-\sqrt {a}+1)+a{^{\frac {3}{2}}}=a>0$ ．
15. 因为 $f(x)$ 在 $\left ({0,\sqrt[3]{\frac {3}{a}}}\right )$ 上单调递减， $\sqrt {\frac {1}{a}}<\sqrt[3]{\frac {3}{a}},f\left ({\sqrt {\frac {1}{a}}}\right )\cdot f\left ({\sqrt[3]{\frac {3}{a}}}\right )<0$ ，
16. 所以 $f(x)$ 在 $\left ({0,\sqrt[3]{\frac {3}{a}}}\right )$ 上有且只有1个零点，记为 $x{{}_{2}}$ ，且 $\sqrt {\frac {1}{a}}<x{{}_{2}}<\sqrt[3]{\frac {3}{a}}$ ，
17. 所以 $\sqrt {\frac {1}{a}}<x{{}_{2}}<\sqrt[3]{\frac {3}{a}}<x{{}_{1}}<1$ ，所以 $\sqrt {\frac {1}{a}}-1<x{{}_{2}}-x{{}_{1}}<0$ ．
18. 同理，若记 $x{{}_{1}}\in \left ({\sqrt {\frac {1}{a}},\sqrt[3]{\frac {3}{a}}}\right ),x{{}_{2}}\in \left ({\sqrt[3]{\frac {3}{a}},1}\right )$ ，
19. 则有 $0<x{{}_{2}}-x{{}_{1}}<1-\sqrt {\frac {1}{a}}$ ，
20. 综上所述， $\left |{x{{}_{2}}-x{{}_{1}}}\right |<1-\sqrt {\frac {1}{a}}$ ．

## 知识点

**中文**:
  - 利用导数证明不等式

**English**:
  - Proving Inequalities using Derivatives

---
