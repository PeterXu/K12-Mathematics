# Mathematics - 题目 1521

**ID**: e0f734196fc840958b4d87c5fcadfb32
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f(x)=a{\rm{e}}{^{x}}-{\cos}(a-1)$ ， $a\in \mathbf{R}$ .​​​​​​​‌（1）若 $a=1$ ，求曲线 $y=f(x)$ 在点 $(0,f(0))$ 处的切线方程；（2）设 $g(x)=f(x)-{\ln}(x+1)$ ，若 $g(x)\geqslant 0$ ，求 $a$ 的取值范围．

## 解答

1. （1）当 $a=1$ 时， $f(x)={\rm{e}}{^{x}}-1$ ，则 $f^{′}(x)={\rm{e}}{^{x}}$ ， $\therefore f^{′}(0)=1$ ，
2. 又 $f(0)=0$ ，故切点为 $(0,0)$
3. 所以曲线 $y=f(x)$ 在点 $(0,f(0))$ 处的切线方程为 $x-y=0$ ．
4. （2） $g(x)=a{\rm{e}}{^{x}}-{\ln}(1+x)-{\cos}(a-1)$ ，定义域为 $(-1,+\infty )$ ，
5. 令 $t(a)=a-{\cos}(a-1)(a\in \mathbf{R})$ ，求导 $t^{′}(a)=1+{\sin}(a-1)\geqslant 0$ ，
6. 所以 $t(a)$ 在 $(-\infty ,+\infty )$ 上单调递增，且 $t(1)=1-{\cos}(1-1){\rm{=}}0$ ，
7. 若 $g(x)\geqslant 0$ ，则当 $x=0$ 时， $g(0)=a-{\cos}(a-1)\geqslant 0$ 恒成立，即 $t(a)\geqslant t(1)$ ，所以 $a\geqslant 1$ ．
8. 因为 $g^{′}(x)=a{\rm{e}}{^{x}}-\frac {1}{1+x}$ ，
9. 当 $a\geqslant 1$ 时，令 $m(x)=g^{′}(x)$ ，则 $m^{′}(x)=a{\rm{e}}{^{x}}+\frac {1}{(1+x){^{2}}}>0$ ，
10. 所以 $m(x)$ 在 $(-1,+\infty )$ 上单调递增，且 $m(0)=a-1\geqslant 0$ ， $m\left ({\frac {1}{a}-1}\right )=a{\rm{e}}{^{\frac {1}{a}-1}}-a\leqslant a-a=0$ ，
11. 所以存在 $x{{}_{0}}\in (-1,0]$ ，使得 $m(x{{}_{0}})=0$ ，即 $a{\rm{e}}{^{x{{}_{0}}}}-\frac {1}{1+x{{}_{0}}}=0$ ， ${\ln}(1+x{{}_{0}})=-x{{}_{0}}-{\ln}a$ ，
12. 当 $x\in (-1,x{{}_{0}})$ 时， $g^{′}(x)<0$ ， $g(x)$ 在 $(-1,x{{}_{0}})$ 上单调递减；
13. 当 $x\in (x{{}_{0}},+\infty )$ 时， $g^{′}(x)>0$ ， $g(x)$ 在 $(x{{}_{0}},+\infty )$ 上单调递增，
14. 所以 $g(x)\geqslant g(x{{}_{0}})=a{\rm{e}}{^{x{{}_{0}}}}-{\ln}(1+x{{}_{0}})-{\cos}(a-1)$  $=\frac {1}{1+x{{}_{0}}}+x{{}_{0}}+{\ln}a-{\cos}(a-1)$
15. $=\frac {1}{1+x{{}_{0}}}+1+x{{}_{0}}+{\ln}a-{\cos}(a-1)-1\geqslant 1+{\ln}a-{\cos}(a-1)\geqslant 0$ ．
16. 综上，所求 $a$ 的取值范围为 $[1,+\infty )$ .

## 知识点

**中文**:
  - 利用导数解决不等式恒成立问题
  - 导数几何意义的应用

**English**:
  - Solving Universally True Inequalities
  - Applications of Geometric Meaning of Derivatives

---
