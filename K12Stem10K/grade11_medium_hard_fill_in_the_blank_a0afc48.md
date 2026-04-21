# Mathematics - 题目 2336

**ID**: a0afc4850ec24b86894d4f28e72095ee
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Fill-in-the-blank

## 题目
已知函数 $f\left ({x}\right )={\rm{e}}{^{kx}}+1$ ， $g\left ({x}\right )=\left ({1+\frac {1}{x}}\right ){\ln}x$ .​​​​​​​‌若 $kf\left ({x}\right )\geqslant g\left ({x}\right )$ ，则k的取值范围为.

## 解答

1. 因为 $f\left ({x}\right )={\rm{e}}{^{kx}}+1$ ，所以 $kf\left ({x}\right )=k\left ({{\rm{e}}{^{kx}}+1}\right )$ .
2. 由 $kf\left ({x}\right )\geqslant g\left ({x}\right )$ 得 $k\left ({{\rm{e}}{^{kx}}+1}\right )\geqslant \left ({1+\frac {1}{x}}\right ){\ln}x$  $\left ({x>0}\right )$ ，
3. 即 $kx\left ({{\rm{e}}{^{kx}}+1}\right )\geqslant \left ({1+x}\right ){\ln}x$  $\left ({x>0}\right )$ ，
4. 即 ${\ln}{\rm{e}}{^{kx}}\cdot \left ({{\rm{e}}{^{kx}}+1}\right )\geqslant \left ({1+x}\right ){\ln}x$  $\left ({x>0}\right )$ .
5. 构造函数 $h\left ({x}\right )=\left ({1+x}\right ){\ln}x$  $\left ({x>0}\right )$ ，
6. 则 ${\ln}{\rm{e}}{^{kx}}\cdot \left ({{\rm{e}}{^{kx}}+1}\right )\geqslant \left ({1+x}\right ){\ln}x$  $\left ({x>0}\right )$ 可化为 $h\left ({{\rm{e}}{^{kx}}}\right )\geqslant h\left ({x}\right )$  $\left ({x>0}\right )$ .
7. 因为 $h^{′}{\left ({x}\right )}={\ln}x+\frac {1}{x}+1$  $\left ({x>0}\right )$ ，
8. 令 $t\left ({x}\right )={\ln}x+\frac {1}{x}+1$  $\left ({x>0}\right )$ ，则 $t^{′}{\left ({x}\right )}=\frac {1}{x}-\frac {1}{x{^{2}}}=\frac {x-1}{x{^{2}}}\left ({x>0}\right )$ ，
9. 令 $t^{′}{\left ({x}\right )}=0$ ，解得 $x=1$ ，
10. 当 $x\in \left ({0,1}\right )$ 时， $t{^{\prime }}\left ({x}\right )<0$ ， $t\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上单调递减，
11. 当 $x\in \left ({1,+\infty }\right )$ 时， $t^{′}{\left ({x}\right )}>0$ ， $t\left ({x}\right )$ 在 $\left ({1,+\infty }\right )$ 上单调递增，
12. 所以 $x=1$ 时， $t\left ({x}\right )$ 取得最小值，即 $t\left ({x}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=t\left ({1}\right )=2>0$ ，
13. 所以 $t\left ({x}\right )>0$ 在 $x\in \left ({0,+\infty }\right )$ 上恒成立，
14. 即 $h^{′}{\left ({x}\right )}>0$ 在 $x\in \left ({0,+\infty }\right )$ 上恒成立，所以 $h\left ({x}\right )$ 在 $x\in \left ({0,+\infty }\right )$ 上单调递增.
15. 因为 $h\left ({{\rm{e}}{^{kx}}}\right )\geqslant h\left ({x}\right )$  $\left ({x>0}\right )$ ，所以 ${\rm{e}}{^{kx}}\geqslant x$  $\left ({x>0}\right )$ ，
16. 即 $kx\geqslant {\ln}x$  $\left ({x>0}\right )$ ，即 $k\geqslant \frac {{\ln}x}{x}$  $\left ({x>0}\right )$ .
17. 令 $m\left ({x}\right )=\frac {{\ln}x}{x}\left ({x>0}\right )$ ，则 $m^{′}{\left ({x}\right )}=\frac {1-{\ln}x}{x{^{2}}}$  $\left ({x>0}\right )$ ，
18. 令 $m^{′}{\left ({x}\right )}=0$ ，即 $1-{\ln}x=0$ ，解得 $x={\rm{e}}$ ，
19. 当 $x\in \left ({0,{\rm{e}}}\right )$ 时， $m^{′}{\left ({x}\right )}>0$ ， $m\left ({x}\right )$ 在 $\left ({0,{\rm{e}}}\right )$ 上单调递增，
20. 当 $x\in \left ({{\rm{e}}{\rm{,}}{{+}}\infty }\right )$ 时， $m^{′}{\left ({x}\right )}<0$ ， $m\left ({x}\right )$ 在 $\left ({0,{\rm{e}}}\right )$ 上单调递减，
21. 所以 $x={\rm{e}}$ 时， $m\left ({x}\right )$ 取得最大值，即 $m\left ({x}\right ){{}_{{\rm \max }}}=m\left ({{\rm{e}}}\right )=\frac {1}{{\rm{e}}}$ ，
22. 所以 $m\left ({x}\right )\leqslant \frac {1}{{\rm{e}}}$ ，所以 $k\mathrm{\geqslant }\frac {1}{{\rm{e}}}$ .

## 知识点

**中文**:
  - 构造同构函数问题

**English**:
  - Constructing Isomorphic Functions

---
