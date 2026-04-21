# Mathematics - 题目 2265

**ID**: f048131cb9fd413daa8740444881da37
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=ax+x{\rm{l}}{\rm{n}}\left ({1+\frac {x}{2}}\right )-\left ({1+x}\right ){\rm{l}}{\rm{n}}\left ({1+x}\right )$ .​​​​​​​‌(1)若曲线 $y=f\left ({x}\right )$ 在点 $\left ({0,f\left ({0}\right )}\right )$ 处的切线与 $x$ 轴平行，求 $a$ 的值；(2)设函数 $g\left ({x}\right )=xf\left ({\frac {1}{x}}\right )$ ，给出 $g\left ({x}\right )$ 的定义域，并证明：曲线 $y=g\left ({x}\right )$ 是轴对称图形；(3)证明： ${\left({1+\frac {1}{n}}\right)^{n}}<{\rm{e}}\left ({1-\frac {1}{2n+2}}\right )\left ({n\in {\mathbf{N}}{^{{\rm{*}}}}}\right )$ .

## 解答

1. （1）因为 $f\left ({x}\right )=ax+x{\rm{l}}{\rm{n}}\left ({1+\frac {x}{2}}\right )-\left ({1+x}\right ){\rm{l}}{\rm{n}}\left ({1+x}\right )$ ，
2. 则 $f^{′}{\left ({x}\right )}=a+{\ln}\frac {x+2}{2}+\frac {x}{2}\cdot \frac {1}{1+\frac {x}{2}}-{\ln}\left ({1+x}\right )-1=\frac {x}{x+2}+{\ln}\frac {x+2}{2x+2}+a-1$ ，
3. 由题意可知， $f^{′}{\left ({0}\right )}=a-1=0$ ，解得 $a=1$ .
4. （2） $g\left ({x}\right )=xf\left ({\frac {1}{x}}\right )=x\left [\frac {a}{x}+\frac {1}{x}{\ln}\left ({1+\frac {1}{2x}}\right )-\left ({1+\frac {1}{x}}\right ){\ln}\left ({1+\frac {1}{x}}\right )\right ]=a+{\ln}\left ({1+\frac {1}{2x}}\right )-\left ({x+1}\right ){\ln}\left ({1+\frac {1}{x}}\right )$ ，
5. 对于函数 $f\left ({x}\right )=ax+x{\rm{l}}{\rm{n}}\left ({1+\frac {x}{2}}\right )-\left ({1+x}\right ){\rm{l}}{\rm{n}}\left ({1+x}\right )$ ，
6. 有 $\begin{cases}x+1>0\\1+\frac {x}{2}>0\end{cases}$ ，解得 $x>-1$ ，即函数 $f\left ({x}\right )$ 的定义域为 $\left ({-1,+\infty }\right )$ ，
7. 对于函数 $g\left ({x}\right )=xf\left ({\frac {1}{x}}\right )$ ，则 $\frac {1}{x}>-1$ ，可得 $\frac {x+1}{x}>0$ ，解得 $x<-1$ 或 $x>0$ ，
8. 所以，函数 $g\left ({x}\right )$ 的定义域为 $\left ({-\infty ,-1}\right )\cup \left ({0,+\infty }\right )$ ，故该定义域关于直线 $x=-\frac {1}{2}$ 对称，
9. 因为 $g\left ({-1-x}\right )=a+{\ln}\left ({1+\frac {1}{-2x-2}}\right )+x{\ln}\left ({1+\frac {1}{-x-1}}\right )=a+{\ln}\frac {2x+1}{2x+2}+x{\ln}\frac {x}{x+1}$
10. $=a+{\ln}\left ({2x+1}\right )-{\ln}\left ({x+1}\right )-{\ln}2+x{\ln}x-x{\ln}\left ({x+1}\right )$
11. $=a+{\ln}\left ({2x+1}\right )-{\ln}2x-{\ln}\left ({x+1}\right )+\left ({x+1}\right ){\ln}x-x{\ln}\left ({x+1}\right )$
12. $=a+{\ln}\left ({1+\frac {1}{2x}}\right )+\left ({x+1}\right ){\ln}x-\left ({x+1}\right ){\ln}\left ({x+1}\right )$
13. $=a+{\ln}\left ({1+\frac {1}{2x}}\right )-\left ({x+1}\right ){\ln}\left ({1+\frac {1}{x}}\right )=g\left ({x}\right )$ ，
14. 故函数 $g\left ({x}\right )$ 的图象关于直线 $x=-\frac {1}{2}$ 对称，所以曲线 $y=g\left ({x}\right )$ 是轴对称图形.
15. （3）当 $a=1$ 时， $f\left ({x}\right )=x+x{\ln}\left ({1+\frac {x}{2}}\right )-\left ({x+1}\right ){\ln}\left ({x+1}\right )$ ，
16. 则 $f^{′}{\left ({x}\right )}=\frac {x}{x+2}+{\ln}\frac {x+2}{2x+2}$ ，令 $h\left ({x}\right )=\frac {x}{x+2}+{\ln}\frac {x+2}{2x+2}$ ，
17. 则 $h^{′}{\left ({x}\right )}=\frac {2}{{\left({x+2}\right)^{2}}}-\frac {2x+2}{x+2}\cdot \frac {1}{2{\left({x+1}\right)^{2}}}=\frac {x}{\left ({x+1}\right ){\left({x+2}\right)^{2}}}$ ，
18. 当 $x>0$ 时， $h^{′}{\left ({x}\right )}>0$ ，则函数 $h\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上为增函数，此时， $h\left ({x}\right )>h\left ({0}\right )=0$ ，
19. 即 $f^{′}{\left ({x}\right )}>0$ ，所以，函数 $f\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上为增函数，此时， $f\left ({x}\right )>f\left ({0}\right )=0$ ，
20. 取 $x=\frac {1}{n}$ ，可得 $f\left ({\frac {1}{n}}\right )=\frac {1}{n}+\frac {1}{n}{\ln}\left ({1+\frac {1}{2n}}\right )-\left ({1+\frac {1}{n}}\right ){\ln}\left ({1+\frac {1}{n}}\right )>0$ ，
21. 于是 $1+{\ln}\left ({1+\frac {1}{2n}}\right )-\left ({n+1}\right ){\ln}\left ({1+\frac {1}{n}}\right )>0$ ，即 ${\ln}\left [{\rm{e}}\left ({1+\frac {1}{2n}}\right )\right ]>{\ln}{\left({1+\frac {1}{n}}\right)^{n+1}}$ ，
22. 所以， ${\rm{e}}\left ({1+\frac {1}{2n}}\right )>{\left({1+\frac {1}{n}}\right)^{n+1}}$ ，
23. 故 ${\left({1+\frac {1}{n}}\right)^{n}}<{\rm{e}}\cdot \frac {2n+1}{2n}\cdot \frac {n}{n+1}={\rm{e}}\cdot \frac {2n+1}{2n+2}={\rm{e}}\left ({1-\frac {1}{2n+2}}\right )\left ({n\in {\mathbf{N}}{^{∗}}}\right )$ .

## 知识点

**中文**:
  - 利用导数研究函数的图象
  - 导数几何意义的应用
  - 利用导数证明不等式

**English**:
  - Studying Function Graphs
  - Applications of Geometric Meaning of Derivatives
  - Proving Inequalities using Derivatives

---
