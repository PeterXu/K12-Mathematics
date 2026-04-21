# Mathematics - 题目 1112

**ID**: 199aa980a01744d9bb8b4153c477374f
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
帕德近似是法国数学家亨利帕德发明的用有理数多项式近似特定函数的方法，给定两个正整数 $m,n$ ，函数 $f\left ({x}\right )$ 在 $x=0$ 处的 $\left [m,n\right ]$ 阶帕德近似定义为 $\mathbf{R}\left ({x}\right )=\frac {a{{}_{0}}+a{{}_{1}}x+.​​​​​​​‌..+a{{}_{m}}x{^{m}}}{1+b{{}_{1}}x+...+b{{}_{n}}x{^{n}}}$ ，且满足： $f\left ({0}\right )=R\left ({0}\right )，f^{′}{\left ({0}\right )}=R^{′}{\left ({0}\right )},f^{′′}{\left ({0}\right )}=R^{′′}{\left ({0}\right )}{\rm .}$ . $f{^{\left ({m+n}\right )}}\left ({0}\right )=R{^{\left ({m+n}\right )}}\left ({0}\right )$ .已知 $f\left ({x}\right )={\ln}\left ({x+1}\right )$ 在 $x=0$ 处的 $\left [1,1\right ]$ 阶帕德近似为 $\mathbf{R}\left ({x}\right )=\frac {ax}{1+bx}$ .注： $f^{′′}{\left ({x}\right )}=\left [f^{′}{\left ({x}\right )}\right ]{^{\prime }},f^{′′′}{\left ({x}\right )}=\left [f^{′′}{\left ({x}\right )}\right ]{^{\prime }}$ ， $f{^{\left ({4}\right )}}x=\left [f^{′′′}{\left ({x}\right )}\right ]{^{\prime }},f{^{\left ({5}\right )}}x=\left [f{^{\left ({4}\right )}}x\right ]{^{\prime }}...$（1）求实数 $a,b$ 的值；（2）求证： $\left ({x+b}\right )f\left ({\frac {1}{x}}\right ){\rm{>}}1$ ；（3）求不等式 ${\left({1+\frac {1}{x}}\right)^{x}}{\rm{<}}{\rm{e}}{\rm{<}}\left ({1+\frac {1}{x}}\right ){^{x+\frac {1}{2}}}$ 的解集，其中， ${\rm{e}}=2.71828...$

## 解答

1. （1）∵ $R\left ({x}\right )=\frac {ax}{1+bx}$  ∴ $R^{′}{\left ({x}\right )}=\frac {a}{{\left({1+bx}\right)^{2}}},R^{′′}{\left ({x}\right )}=\frac {-2ab}{{\left({1+bx}\right)^{3}}}$
2. ∵ $f\left ({x}\right )={\ln}\left ({x+1}\right )$ ，则 $f^{′}{\left ({x}\right )}=\frac {1}{x+1}$ ， $f^{′′}{\left ({x}\right )}=-\frac {1}{{\left({x+1}\right)^{2}}}$
3. 由题意得： $f\left ({0}\right )=R\left ({0}\right )，f^{′}{\left ({0}\right )}=R^{′}{\left ({0}\right )},f^{′′}{\left ({0}\right )}=R^{′′}{\left ({0}\right )}$
4. ∴ $\begin{cases}a=1\\-2ab=-1\end{cases}$ 解得： $\begin{cases}a=1\\b=\frac {1}{2}\end{cases}$ ；
5. （2）由（1）知，即证 $\left ({x+\frac {1}{2}}\right ){\ln}\left ({1+\frac {1}{x}}\right )>1$
6. 令 $t=1+\frac {1}{x}$ ，则 $t>0$ 且 $t\ne 1$
7. 即证 $t\in \left ({0,1}\right )\cup \left ({1,+\infty }\right )$ 时 $\frac {t+1}{2\left ({t-1}\right )}\cdot {\ln}t>{{1}}$ ，记 $φ\left ({t}\right )={\ln}t-\frac {2\left ({t-1}\right )}{t+1},t\in \left ({0,1}\right )\cup \left ({1,+\infty }\right )$
8. 则 $φ^{′}{\left ({t}\right )}=\frac {1}{t}-\frac {4}{{\left({t+1}\right)^{2}}}=\frac {{\left({t-1}\right)^{2}}}{t{\left({t+1}\right)^{2}}}{\rm{>}}0$
9. ∴ $φ\left ({t}\right )$ 在 $\left ({0，1}\right )$ 上单调递增，在 $\left ({1，+\infty }\right )$ 和 $\left ({1，+\infty }\right )$ 上单调递增
10. 当 $t\in \left ({0,1}\right )$ 时， $φ\left ({t}\right )<φ\left ({1}\right )=0$ ，即 ${\ln}t<\frac {2\left ({t-1}\right )}{t+1}$ ，即 $\frac {t+1}{2\left ({t-1}\right )}\cdot {\ln}t>1$ 成立，
11. 当 $t\in \left ({1，+\infty }\right )$ 时， $φ\left ({t}\right ){\rm{>}}φ\left ({1}\right )=0$ ，即 ${\ln}t>\frac {2\left ({t-1}\right )}{t+1}$ ，即 $\frac {t+1}{2\left ({t-1}\right )}\cdot {\ln}t>1$ 成立，
12. 综上所述， $t\in \left ({0,1}\right )\cup \left ({1,+\infty }\right )$ 时， $\frac {t+1}{2\left ({t-1}\right )}\cdot {\ln}t>{{1}}$
13. ∴ $\left ({x+\frac {1}{2}}\right ){\ln}\left ({1+\frac {1}{x}}\right )>1$ 成立，即 $\left ({x+b}\right )f\left ({\frac {1}{x}}\right )>1$ 成立.
14. （3）由题意得：欲使得不等式 ${\left({1+\frac {1}{x}}\right)^{x}}<{\rm{e}}{\rm{<}}\left ({1+\frac {1}{x}}\right ){^{x+\frac {1}{2}}}$ 成立，则至少有 $1+\frac {1}{x}>0$ ，即 $x>0$ 或 $x<-1$
15. 首先考虑 ${\rm{e}}{\rm{<}}\left ({1+\frac {1}{x}}\right ){^{x+\frac {1}{2}}}$ ，该不等式等价于 ${\ln}\left ({1+\frac {1}{x}}\right ){^{x+\frac {1}{2}}}>1$ ，即 $\left ({x+\frac {1}{2}}\right ){\ln}\left ({1+\frac {1}{x}}\right ){\rm{>}}{{1}}$ ，
16. 又由（2）知 $\left ({x+\frac {1}{2}}\right ){\ln}\left ({1+\frac {1}{x}}\right )>1$ 成立，
17. ∴使得 ${\rm{e}}<\left ({1+\frac {1}{x}}\right ){^{x+\frac {1}{2}}}$ 成立的 $x$ 的取值范围是 $\left ({-\infty ，-1}\right )\cup \left ({0，+\infty }\right )$
18. 再考虑 ${\left({1+\frac {1}{x}}\right)^{x}}<{\rm{e}}$ ，该不等式等价于 $x{\ln}\left ({1+\frac {1}{x}}\right )<1$ ，
19. 记 $h\left ({x}\right )={\ln}x-x+1,x\in \left ({0,1}\right )\cup \left ({1,+\infty }\right )$ ，则 $h{^{\prime }}\left ({x}\right )=\frac {1}{x}-1=\frac {1-x}{x}$ ，
20. ∴当 $0<x<1$ 时， $h^{′}{\left ({x}\right )}>0,x>1$ 时， $h^{′}\left ({x}\right )<0$
21. ∴ $h\left ({x}\right )$ 在 $\left ({0，1}\right )$ 上单调递增，在 $\left ({1，+\infty }\right )$ 上单调递减
22. ∴ $h\left ({x}\right )<h\left ({1}\right )=0$ ，即 ${\ln}x<x-1$ ， $x\in \left ({0,1}\right )\cup \left ({1,+\infty }\right )$
23. ∴ ${\ln}\left ({1+\frac {1}{x}}\right ){\rm{<}}\frac {1}{x}$ ， $x\in \left ({-\infty ,-1}\right )\cup \left ({0,+\infty }\right )$
24. 当 $x\in \left ({0,+\infty }\right )$ 时由 ${\ln}\left ({1+\frac {1}{x}}\right ){\rm{<}}\frac {1}{x}$ ，可知 $x{\ln}\left ({1+\frac {1}{x}}\right )<1$ 成立；
25. 当 $x\in \left ({-\infty ,-1}\right )$ 时由 ${\ln}\left ({1+\frac {1}{x}}\right ){\rm{<}}\frac {1}{x}$ ，可知 $x{\ln}\left ({1+\frac {1}{x}}\right )<1$ 不成立；
26. 所以使得 ${\left({1+\frac {1}{x}}\right)^{x}}{\rm{<}}{\rm{e}}$ 成立的 $x$ 的取值范围是 $\left ({0，+\infty }\right )$
27. 综上可得：不等式 ${\left({1+\frac {1}{x}}\right)^{x}}{\rm{<}}{\rm{e}}{\rm{<}}\left ({1+\frac {1}{x}}\right ){^{x+\frac {1}{2}}}$ 的解集为 $\left ({0,+∞}\right )$ .

## 知识点

**中文**:
  - 利用导数解决新定义问题

**English**:
  - Solving New Definition Problems

---
