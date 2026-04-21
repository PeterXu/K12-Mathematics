# Mathematics - 题目 1580

**ID**: d531b5c952ed458a95b49108b75f957f
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\left ({1+x}\right ){\rm e}{^{-2x}}$ ， $g\left ({x}\right )=ax+\frac {x{^{3}}}{2}+1+2x{\cos}x$ ，当 $x\in \left [0,1\right ]$ 时，（1）若函数 $g\left ({x}\right )$ 在 $x=0$ 处的切线与 $x$ 轴平行，求实数 $a$ 的值；​​​​​​​‌（2）求证： $1-x\leqslant f\left ({x}\right )\leqslant \frac {1}{1+x}$ ；（3）若 $f\left ({x}\right )\geqslant g\left ({x}\right )$ 恒成立，求实数 $a$ 的取值范围．

## 解答

1. 解：（1） $g\prime \left ({x}\right )=a+\frac {3}{2}x{^{2}}+2\left ({{\cos}x-x{\sin}x}\right )$ ，
2. 函数 $g\left ({x}\right )$ 在 $x=0$ 处的切线与 $x$ 轴平行，则 $g^{′}{\left ({0}\right )}=a+2=0$ ，得 $a=-2$ ．
3. （2）证明：①当 $x\in \left [0,1\right ]$ 时， $\left ({1+x}\right ){\rm e}{^{-2x}}\geqslant 1-x\Leftrightarrow \left ({1+x}\right ){\rm e}{^{-x}}\geqslant \left ({1-x}\right ){\rm e}^{x}$ ，
4. 令 $h\left ({x}\right )=\left ({1+x}\right ){\rm e}{^{-x}}-\left ({1-x}\right ){\rm e}^{x}$ ，则 $h\prime \left ({x}\right )=x\left ({{\rm e}^{x}-{\rm e}{^{-x}}}\right )$ ．当 $x\in \left [0,1\right ]$ 时， $h\prime \left ({x}\right )\geqslant 0$ ，
5. ∴ $h\left ({x}\right )$ 在 $\left [0,1\right ]$ 上是增函数，∴ $h\left ({x}\right )\geqslant h\left ({0}\right )=0$ ，即 $f\left ({x}\right )\geqslant 1-x$ ．
6. ②当 $x\in \left [0,1\right ]$ 时， $f\left ({x}\right )\leqslant \frac {1}{1+x}\Leftrightarrow {\rm e}^{x}\geqslant 1+x$ ，令 $u\left ({x}\right )={\rm e}^{x}-1-x$ ，则 $u\prime \left ({x}\right )={\rm e}^{x}-1$ ．
7. 当 $x\in \left [0,1\right ]$ 时， $u\prime \left ({x}\right )\geqslant 0$ ，∴ $u\left ({x}\right )$ 在 $\left [{0,1}\right )$ 单调递增，∴ $u\left ({x}\right )\geqslant u\left ({0}\right )=0$ ，
8. ∴ $f\left ({x}\right )\leqslant \frac {1}{1+x}$ ，综上可知： $1-x\leqslant f\left ({x}\right )\leqslant \frac {1}{1+x}$ ；
9. （3）解：设 $G\left ({x}\right )=f\left ({x}\right )-g\left ({x}\right )=\left ({1+x}\right ){\rm e}{^{-2x}}-\left ({ax+\frac {1}{2}x{^{3}}+1+2x{\cos}x}\right )$
10. $\geqslant 1-x-ax-1-\frac {1}{2}x{^{3}}-2x{\cos}x=-x\left ({a+1+\frac {x{^{2}}}{2}+2{\cos}x}\right )$ ．
11. 令 $H\left ({x}\right )=\frac {x{^{2}}}{2}+2{\cos}x$ ，则 $H\prime \left ({x}\right )=x-2{\sin}x$ ，
12. 令 $K\left ({x}\right )=x-2{\sin}x$ ，则 $K\prime \left ({x}\right )=1-2{\cos}x$ ．
13. 当 $x\in \left [0,1\right ]$ 时， $K\prime \left ({x}\right )<0$ ，可得 $H\prime \left ({x}\right )$ 是 $\left [{0,1}\right )$ 上的减函数，
14. ∴ $H\prime \left ({x}\right )\leqslant H\prime \left ({0}\right )=0$ ，故 $H\left ({x}\right )$ 在 $\left [{0,1}\right )$ 单调递减，
15. ∴ $H\left ({x}\right )\leqslant H\left ({0}\right )=2$ ．∴ $a+1+H\left ({x}\right )\leqslant a+3$ ．
16. ∴当 $a\leqslant -3$ 时， $f\left ({x}\right )\geqslant g\left ({x}\right )$ 在 $\left [{0,1}\right )$ 上恒成立．
17. 下面证明当 $a>-3$ 时， $f\left ({x}\right )\geqslant g\left ({x}\right )$ 在 $\left [{0,1}\right )$ 上不恒成立．
18. $f\left ({x}\right )-g\left ({x}\right )\leqslant \frac {1}{1+x}-\left ({1+ax+\frac {1}{2}x{^{3}}+2x{\cos}x}\right )=-x\left ({\frac {1}{1+x}+a+\frac {x{^{2}}}{2}+2{\cos}x}\right )$ ．
19. 令 $v\left ({x}\right )=\frac {1}{1+x}+a+\frac {x{^{2}}}{2}+2{\cos}x=\frac {1}{1+x}+a+H\left ({x}\right )$ ，则 $v\prime \left ({x}\right )=\frac {-1}{{\left({1+x}\right)^{2}}}+H\prime \left ({x}\right )$ ．
20. 当 $x\in \left [0,1\right ]$ 时， $v^{′}{\left ({x}\right )}\leqslant 0$ ，故 $v\left ({x}\right )$ 在 $\left [0,1\right ]$ 上是减函数，
21. ∴ $v\left ({x}\right )\in \left ({a+1+2{\cos}1,a+3}\right ]$ ．
22. 当 $a>-3$ 时， $a+3>0$ ．∴存在 $x{{}_{0}}\in \left ({0,1}\right )$ ，使得 $v\left ({x{{}_{0}}}\right )>0$ ，此时， $f\left ({x{{}_{0}}}\right )<g\left ({x{{}_{0}}}\right )$ ．
23. 即 $f\left ({x}\right )\geqslant g\left ({x}\right )$ 在 $\left [{0,1}\right )$ 不恒成立．综上实数 $a$ 的取值范围是 $\left ({-\infty ,-3}\right ]$ ．

## 知识点

**中文**:
  - 利用导数解决不等式恒成立问题
  - 导数几何意义的应用
  - 利用导数证明不等式

**English**:
  - Solving Universally True Inequalities
  - Applications of Geometric Meaning of Derivatives
  - Proving Inequalities using Derivatives

---
