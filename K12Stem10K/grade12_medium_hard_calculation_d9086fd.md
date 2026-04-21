# Mathematics - 题目 2521

**ID**: d9086fd7ae2f45f98d5ee2a82bc38524
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )={\rm{l}}{\rm{n}}\left ({\frac {x+1}{x}}\right )-\frac {2a}{2x+1}\left ({a\in {\mathbf{R}}}\right )$ .​​​​​​​‌（1）证明：曲线 $y=f\left ({x}\right )$ 关于点 $\left ({-\frac {1}{2},0}\right )$ 中心对称；（2）当 $x>0$ 时， $f\left ({x}\right )>0$ ，求 $a$ 的取值范围；（3）证明：对于任意的 $n\in {\mathbf{N}}{^{{\rm{*}}}},2{\rm{l}}{\rm{n}}\left ({n!}\right )+2n<\left ({2n+1}\right ){\rm{l}}{\rm{n}}\left ({n+1}\right )$ .

## 解答

1. （1）由题意可得 $\begin{cases}\frac {x+1}{x}>0\\2x+1\ne 0\end{cases}$ ，解得 $x<-1$ 或 $x>0$ ，
2. 即 $y=f\left ({x}\right )$ 的定义域为 $\left ({-∞,-1}\right )\cup \left ({0,+∞}\right )$ ，
3. $f\left ({x}\right )+f\left ({-x-1}\right )={\rm{l}}{\rm{n}}\left ({\frac {x+1}{x}}\right )-\frac {2a}{2x+1}+{\rm{l}}{\rm{n}}\left ({\frac {-x-1+1}{-x-1}}\right )-\frac {2a}{2\left ({-x-1}\right )+1}$
4. $={\rm{l}}{\rm{n}}\left ({\frac {x+1}{x}}\right )-\frac {2a}{2x+1}+{\rm{l}}{\rm{n}}\left ({\frac {x}{x+1}}\right )+\frac {2a}{2x+1}={\rm{l}}{\rm{n}}\left [\left ({\frac {x+1}{x}}\right )\cdot \left ({\frac {x}{x+1}}\right )\right ]={\ln}1=0$ ，
5. 即 $f\left ({x}\right )+f\left ({-x-1}\right )=0$ ，故曲线 $y=f\left ({x}\right )$ 关于点 $\left ({-\frac {1}{2},0}\right )$ 中心对称；
6. （2）由 $x>0$ ，则 $\frac {x+1}{x}=1+\frac {1}{x}>1$ ，令 $t=1+\frac {1}{x}>1$ ，则 $x=\frac {1}{t-1}$ ，
7. 则 $f\left ({x}\right )={\rm{l}}{\rm{n}}\left ({\frac {x+1}{x}}\right )-\frac {2a}{2x+1}={\ln}t-\frac {2a}{2\left ({\frac {1}{t-1}}\right )+1}={\ln}t-\frac {2a\left ({t-1}\right )}{t+1}$ ，
8. 令 $g\left ({x}\right )={\ln}x-\frac {2a\left ({x-1}\right )}{x+1}$ ， $x>1$ ，
9. 则 $g^{′}{\left ({x}\right )}=\frac {1}{x}-2a\cdot \frac {x+1-x+1}{{\left({x+1}\right)^{2}}}=\frac {x{^{2}}+\left ({2-4a}\right )x+1}{x{\left({x+1}\right)^{2}}}$ ，
10. 若 $a\leqslant 1$ ，由 $x>1$ ，则 $\left ({2-4a}\right )x\geqslant -2x$ ，
11. 故 $g^{′}{\left ({x}\right )}=\frac {x{^{2}}+\left ({2-4a}\right )x+1}{x{\left({x+1}\right)^{2}}}\geqslant \frac {x{^{2}}-2x+1}{x{\left({x+1}\right)^{2}}}=\frac {{\left({x-1}\right)^{2}}}{x{\left({x+1}\right)^{2}}}>0$
12. 则 $g\left ({x}\right )$ 在 $\left ({1,+∞}\right )$ 上单调递增，又 $g\left ({1}\right )={\ln}1-0=0$ ，故 $g\left ({x}\right )>0$ 恒成立，符合要求；
13. 若 $a>1$ ，有 $g^{′}{\left ({1}\right )}=\frac {1+\left ({2-4a}\right )+1}{4}=1-a<0$ ，
14. 则存在 $ε>0$ ，使得 $x\in \left ({1,ε}\right )$ 时， $g^{′}{\left ({x}\right )}<0$ ，
15. 即 $g\left ({x}\right )$ 在 $\left ({1,ε}\right )$ 上单调递减，又 $g\left ({1}\right )=0$ ，
16. 则当 $x\in \left ({1,ε}\right )$ 时， $g\left ({x}\right )<0$ ，故不符；
17. 综上所述， $a\leqslant 1$ ；
18. （3）由（2）可得， ${\rm{l}}{\rm{n}}\left ({\frac {x+1}{x}}\right )-\frac {2}{2x+1}>0$ 对任意 $x>0$ 恒成立，
19. 则 ${\ln}\left ({\frac {x+1}{x}}\right )>\frac {2}{2x+1}$ 对任意 $x>0$ 恒成立，
20. 故当 $x=1$ 时，有 ${\ln}2>\frac {2}{3}$ ，即 $3{\ln}2>2$ ，
21. 令 $h\left ({n}\right )=2{\rm{l}}{\rm{n}}\left ({n!}\right )+2n-\left ({2n+1}\right ){\rm{l}}{\rm{n}}\left ({n+1}\right )$ ， $n\in {\mathbf{N}}{^{{\rm{*}}}}$ ，
22. 则 $h\left ({1}\right )=2{\rm{l}}{\rm{n}}1+2-\left ({2+1}\right ){\rm{l}}{\rm{n}}\left ({1+1}\right )=2-3{\ln}2<0$ ，
23. 即当 $n=1$ 时， $2{\rm{l}}{\rm{n}}\left ({n!}\right )+2n<\left ({2n+1}\right ){\rm{l}}{\rm{n}}\left ({n+1}\right )$ ，
24. 当 $n\mathrm{\geqslant }2$ 时，
25. $h\left ({n}\right )-h\left ({n-1}\right )=2{\rm{l}}{\rm{n}}\left ({n!}\right )+2n-\left ({2n+1}\right ){\rm{l}}{\rm{n}}\left ({n+1}\right )-2{\rm{l}}{\rm{n}}\left [\left ({n-1}\right )!\right ]-2\left ({n-1}\right )+\left ({2n-1}\right ){\ln}n$
26. $=2{\rm{l}}{\rm{n}}\left [\frac {n!}{\left ({n-1}\right )!}\right ]-2n{\rm{l}}{\rm{n}}\left ({n+1}\right )-{\rm{l}}{\rm{n}}\left ({n+1}\right )+2n{\ln}n-{\ln}n+2$
27. $={\ln}n-2n{\ln}\frac {n+1}{n}-{\ln}\left ({n+1}\right )+2=2-{\ln}\frac {n+1}{n}-2n{\ln}\frac {n+1}{n}=2-\left ({2n+1}\right ){\ln}\frac {n+1}{n}$ ，
28. 由 ${\ln}\left ({\frac {x+1}{x}}\right )>\frac {2}{2x+1}$ 对任意 $x>0$ 恒成立，则 ${\ln}\left ({\frac {n+1}{n}}\right )>\frac {2}{2n+1}$ ，
29. 故 $h\left ({n}\right )-h\left ({n-1}\right )=2-\left ({2n+1}\right ){\ln}\frac {n+1}{n}<2-\left ({2n+1}\right )\cdot \frac {2}{2n+1}=0$ ，
30. 即 $h\left ({n}\right )<h\left ({n-1}\right )$ ，又 $h\left ({1}\right )<0$ ，则对任意 $n\in {\mathbf{N}}{^{{\rm{*}}}}$ ，有 $h\left ({n}\right )<0$ ，
31. 即对于任意的 $n\in {\mathbf{N}}{^{{\rm{*}}}},2{\rm{l}}{\rm{n}}\left ({n!}\right )+2n<\left ({2n+1}\right ){\rm{l}}{\rm{n}}\left ({n+1}\right )$ .

## 知识点

**中文**:
  - 函数对称性
  - 利用导数证明不等式
  - 利用导数解决不等式恒成立问题

**English**:
  - Symmetry of Functions
  - Proving Inequalities using Derivatives
  - Solving Universally True Inequalities

---
