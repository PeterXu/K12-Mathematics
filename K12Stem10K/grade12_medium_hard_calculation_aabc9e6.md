# Mathematics - 题目 849

**ID**: aabc9e60e53d4cdaaa90101288b79cf4
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知 $f(x)=e{^{x}}-2ax+{\sin}x$ ．（1）已知函数 $f(x)$ 在点 $(0,f(0))$ 的切线与圆 $x{^{2}}+y{^{2}}=\frac {1}{2}$ 相切，求实数a的值；​​​​​​​‌（2）当 $x\geqslant 0$ 时， $f(x)\geqslant 1$ ，求实数a的取值范围．

## 解答

1. （1）由题知， $f^{′}(x)={\rm e}^{x}-2a+{\cos}x$ ， $f(0)=1$ ．
2. $\therefore f(x)$ 在点 $(0,f(0))$ 的切线斜率为 $f^{′}(0)=2-2a$ ，
3. $\therefore f(x)$ 在点 $(0,f(0))$ 的切线方程为 $y=(2-2a)x+1$ ，
4. 即 $(2-2a)x-y+1=0$ ，
5. 由题意知， $\frac {1}{\sqrt {(2-2a){^{2}}+(-1){^{2}}}}=\frac {\sqrt {2}}{2}$ ，解得 $a=\frac {{\rm{1}}}{2}$ 或 $a=\frac {3}{2}$ ．
6. （2）设 $h(x)=f(x)-1={\rm e}^{x}-2ax+{\sin}x-1$
7. $\therefore h^{′}(x)={\rm e}^{x}-2a+{\cos}x$ ，
8. 设 $m(x)={\rm e}^{x}-2a+{\cos}x$ ， $\therefore m^{′}(x)={\rm e}^{x}-{\sin}x$ ，
9. $\because $ 当 $x\geqslant 0$ 时， ${\rm e}^{x}\geqslant 1$ ， $-1\leqslant {\sin}x\leqslant 1$ ， $\therefore m^{′}(x)\geqslant 0$ ，
10. $\therefore m(x)$ 即 $h{^{\prime }}(x)$ 在 $\left [{0,+\infty }\right )$ 上是增函数， $h^{′}(0)=2-2a$ ，
11. 当 $a\leqslant 1$ 时， $2-2a\geqslant 0$ ，
12. 则当 $x\geqslant 0$ 时， $h^{′}(x)\geqslant h^{′}(0)=2-2a\geqslant 0$ ，
13. $\therefore $ 函数 $h(x)$ 在 $\left [{0,+\infty }\right )$ 上是增函数，
14. $\therefore $ 当 $x\geqslant 0$ 时， $h(x)\geqslant h(0)=0$ ，满足题意，
15. 当 $a\mathrm{>}1$ 时， $h^{′}(0)=2-2a<0$ ，
16. $\because h^{′}(x)$ 在 $\left [{0,+\infty }\right )$ 上是增函数， $h^{′}({\ln}(2a+1))=1+{\cos}({\ln}(2a+1))>0$ ，
17. $\therefore $ 存在 $x{{}_{0}}\in \left ({0,+\infty }\right )$ 上，使 $h^{′}(x{{}_{0}})=0$ ，
18. 当 $0<x<x{{}_{0}}$ 时， $h^{′}(x)<h^{′}(x{{}_{0}})=0$ ，
19. $\therefore $ 函数 $h(x)$ 在 $\left ({0,x{{}_{0}}}\right )$ 是减函数
20. $\therefore $ 当 $0<x<x{{}_{0}}$ 时， $h(x)<h(0)=0$ ，不满足题意．
21. 综上所述，实数 $a$ 的取值范围为 $\left ({-\infty ,1}\right ]$ ．

## 知识点

**中文**:
  - 利用导数求函数中的参数

**English**:
  - Finding Parameters using Derivatives

---
