# Mathematics - 题目 241

**ID**: 2f7cf7acf3f94c43bcc1fc4446fa341c
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f(x)=x{\rm{e}}{{}^{x}}-a$ .​​​​​​​‌(1)讨论函数 $f(x)$ 在 $\left [-2,1\right ]$ 上的零点个数；(2)当 $a=0$ 且 $x\in (-1,0)\cup (0,+\infty )$ 时，记 $M(x)=\left [\frac {f(x)}{x}-1\right ]\cdot \frac {{\ln}(x+1)}{x{{}^{2}}}$ ，探究 $M(x)$ 与1的大小关系，并说明理由.

## 解答

1. （1） $f^{′}(x)=\left ({1+x}\right ){\rm{e}}{{}^{x}}$ ， $x\in \left [-2,1\right ]$ ，
2. 当 $-2{\rm{<}}x{\rm{<}}-1$ 时， $f^{′}(x)<0$ ，当 $-1<x<1$ 时， $f^{′}(x)>0$ ，
3. 故 $f\left ({x}\right )$ 在 $\left ({-2,-1}\right )$ 上单调递减，在 $\left ({-1,1}\right )$ 上单调递增，
4. 又 $f(-1)=-{\rm{e}}{{}^{-1}}-a$ ， $f(-2)=-2{\rm{e}}{{}^{-2}}-a$ ， $f(1)={\rm{e}}-a$ ，其中 $-2{\rm{e}}{{}^{-2}}-a<{\rm{e}}-a$ ，
5. 若 $f(-1)=-{\rm{e}}{{}^{-1}}-a>0$ ，即 $a<-{\rm{e}}{{}^{-1}}$ 时， $f\left ({x}\right )$ 零点个数为0，
6. 若 $f(-1)=-{\rm{e}}{{}^{-1}}-a=0$ ，即 $a=-{\rm{e}}{{}^{-1}}$ 时， $f\left ({x}\right )$ 零点个数为1，
7. 若 $\left \{\hspace{-0.5em}\begin{array}{l}f(-1)=-{\rm{e}}{{}^{-1}}-a<0\\f(-2)=-{\rm{e}}{{}^{-2}}-a\geqslant 0\end{array}\hspace{-0.5em}\right.$ ，即 $-{\rm{e}}{{}^{-1}}<a\leqslant -{\rm{e}}{{}^{-2}}$ 时， $f\left ({x}\right )$ 零点个数为2，
8. 若 $\left \{\hspace{-0.5em}\begin{array}{l}f(1)={\rm{e}}-a\geqslant 0\\f(-2)=-{\rm{e}}{{}^{-2}}-a<0\end{array}\hspace{-0.5em}\right.$ ，即 $-{\rm{e}}{{}^{-2}}<a\leqslant {\rm{e}}$ 时， $f\left ({x}\right )$ 零点个数为1，
9. 若 $f(1)={\rm{e}}-a<0$ ，即 $a>{\rm{e}}$ 时， $f\left ({x}\right )$ 零点个数为0，
10. 综上：当 $a<-{\rm{e}}{{}^{-1}}$ 或 $a>{\rm{e}}$ 时， $f\left ({x}\right )$ 零点个数为0，
11. 当 $a=-{\rm{e}}{{}^{-1}}$ 或 $-{\rm{e}}{{}^{-2}}<a\leqslant {\rm{e}}$ 时， $f\left ({x}\right )$ 零点个数为1，
12. 当 $-{\rm{e}}{{}^{-1}}<a\leqslant -{\rm{e}}{{}^{-2}}$ 时， $f\left ({x}\right )$ 零点个数为2.
13. （2） $M(x)>1$ ，理由如下：
14. $M(x)=\left ({{\rm{e}}{{}^{x}}-1}\right )\cdot \frac {{\ln}(x+1)}{x{{}^{2}}}$ ， $x\in (-1,0)\cup (0,+\infty )$ ，
15. 当 $x\in \left ({-1,0}\right )$ 时， ${\ln}\left ({x+1}\right )<0$ ，故 $\frac {x}{{\ln}\left ({x+1}\right )}>0$ ，
16. 当 $x\in \left ({0,+\infty }\right )$ 时， ${\ln}\left ({x+1}\right )>0$ ，故 $\frac {x}{{\ln}\left ({x+1}\right )}>0$ ，
17. 要证 $\left ({{\rm{e}}{{}^{x}}-1}\right )\cdot \frac {{\ln}(x+1)}{x{{}^{2}}}>1$ ，即证 $\frac {{\rm{e}}{{}^{x}}-1}{x}>\frac {x}{{\ln}\left ({x+1}\right )}$ ，其中 $\frac {x}{{\ln}\left ({x+1}\right )}=\frac {{\rm{e}}{{}^{{\ln}\left ({x+1}\right )}}-1}{{\ln}\left ({x+1}\right )}$ ，
18. 故即证 $\frac {{\rm{e}}{{}^{x}}-1}{x}>\frac {{\rm{e}}{{}^{{\ln}\left ({x+1}\right )}}-1}{{\ln}\left ({x+1}\right )}$ ，
19. 令 $h\left ({x}\right )=\frac {{\rm{e}}{{}^{x}}-1}{x}$ ， $x\in \left ({-\infty ,0}\right )\cup \left ({0,+∞}\right )$ ，即证 $h\left ({x}\right )>h\left [{\ln}\left ({x+1}\right )\right ]$ ，
20. $h^{′}{\left ({x}\right )}=\frac {x{\rm{e}}{{}^{x}}-{\rm{e}}{{}^{x}}+1}{x{{}^{2}}}$ ，
21. 令 $φ\left ({x}\right )=x{\rm{e}}{{}^{x}}-{\rm{e}}{{}^{x}}+1$ ，则 $φ^{′}{\left ({x}\right )}=x{\rm{e}}{{}^{x}}$ ，
22. 当 $x>0$ 时， $φ^{′}{\left ({x}\right )}=x{\rm{e}}{{}^{x}}>0$ ，当 $x\in \left ({-\infty ,0}\right )$ 时， $φ^{′}{\left ({x}\right )}=x{\rm{e}}{{}^{x}}<0$ ，
23. 故 $φ\left ({x}\right )=x{\rm{e}}{{}^{x}}-{\rm{e}}{{}^{x}}+1$ 在 $x\in \left ({-\infty ,0}\right )$ 上单调递减，在 $x\in \left ({0,+\infty }\right )$ 上单调递增，
24. 故 $φ\left ({x}\right )>φ\left ({0}\right )=0$ 在 $x\in \left ({-\infty ,0}\right )\cup \left ({0,+∞}\right )$ 上恒成立，
25. 所以 $h^{′}{\left ({x}\right )}>0$ 在 $x\in \left ({-\infty ,0}\right )\cup \left ({0,+∞}\right )$ 上恒成立，
26. 则 $h\left ({x}\right )=\frac {{\rm{e}}{{}^{x}}-1}{x}$ 在 $\left ({-\infty ,0}\right ),\left ({0,+∞}\right )$ 上单调递增，
27. 则 $x>{\ln}\left ({x+1}\right )$ ，
28. 令 $t\left ({x}\right )=x-{\ln}\left ({x+1}\right )$ ， $x\in (-1,0)\cup (0,+\infty )$ ，
29. $t^{′}{\left ({x}\right )}=1-\frac {1}{x+1}=\frac {x}{x+1}$ ，当 $x>0$ 时， $t^{′}{\left ({x}\right )}>0$ ，当 $x\in \left ({-1,0}\right )$ 时， $t{{}^{\prime }}\left ({x}\right )<0$ ，
30. 故 $t\left ({x}\right )=x-{\ln}\left ({x+1}\right )$ 在 $x\in \left ({-1,0}\right )$ 上单调递减，在 $x\in \left ({0,+\infty }\right )$ 上单调递增，
31. 故 $t\left ({x}\right )>t\left ({0}\right )=0$ ，即 $x>{\ln}\left ({x+1}\right )$ ，结论得证.
32. 【点睛】导函数求解参数取值范围，当函数中同时出现 ${\rm{e}}{{}^{x}}$ 与 ${\ln}x$ ，通常使用同构来进行求解，本题难点是 $\frac {{\rm{e}}{{}^{x}}-1}{x}>\frac {x}{{\ln}\left ({x+1}\right )}$ 变形得到 $\frac {x}{{\ln}\left ({x+1}\right )}=\frac {{\rm{e}}{{}^{{\ln}\left ({x+1}\right )}}-1}{{\ln}\left ({x+1}\right )}$ ，从而构造 $h\left ({x}\right )=\frac {{\rm{e}}{{}^{x}}-1}{x}$ 进行求解.

## 知识点

**中文**:
  - 利用导数解决函数零点问题
  - 利用导数证明不等式
  - 构造同构函数问题

**English**:
  - Solving Zero Point Problems
  - Proving Inequalities using Derivatives
  - Constructing Isomorphic Functions

---
