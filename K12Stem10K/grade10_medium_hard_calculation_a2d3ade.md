# Mathematics - 题目 1933

**ID**: a2d3adefdfec470798bea8c4e0d25e8c
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=ax{^{2}}+\left ({a{^{2}}-2}\right )x+b$ ，不等式 $f\left ({x}\right )>0$ 的解集为 $\left ({-1,2}\right )$ ，函数 $g\left ({x}\right )=cx+6$ ，（1）求函数 $y=f\left ({x}\right )$ 的解析式；（2）若对 $\forall x\in \left ({1,+∞}\right )$ ，都有 $f\left ({x}\right )<g\left ({x}\right )$ 恒成立，求实数 $c$ 的取值范围；（3）若对 $\forall x{{}_{1}}\in \left [0,1\right ],\exists x{{}_{2}}\in \left [{1,+∞}\right )$ ，使得不等式 $f\left ({x{{}_{1}}}\right )<g\left ({x{{}_{2}}}\right )$ 成立，求实数 $c$ 的取值范围.​​​​​​​‌

## 解答

1. （1）由于函数 $f\left ({x}\right )=ax{^{2}}+\left ({a{^{2}}-2}\right )x+b$ ，不等式 $f\left ({x}\right )>0$ 的解集为 $\left ({-1,2}\right )$ ，
2. 所以 $\begin{cases}a<0\\f(-1)=a-a{^{2}}+2+b=0\\f(2)=4a+2a{^{2}}-4+b=0\end{cases}$ ，解得： $\begin{cases}a=-2\\b=4\end{cases}$ ，
3. 所以  $f\left ({x}\right )=-2x{^{2}}+2x+4$
4. （2）对 $\forall x\in \left ({1,+\infty }\right )$ ，都有 $f\left ({x}\right )<g\left ({x}\right )$ 恒成立，即 $-2x{^{2}}+2x+4<cx+6$ ，
5. 即对 $\forall x\in \left ({1,+\infty }\right )$ ，都有 $c>-2x-\frac {2}{x}+2$ ，
6. 令 $h(x)=-2x-\frac {2}{x}+2$ ， $x\in \left ({1,+\infty }\right )$ ，
7. 由于当 $x>0$ ， $-\left ({2x+\frac {2}{x}}\right )+2\leqslant -2\sqrt {2x\cdot \frac {2}{x}}+2=-2$ ，当且仅当 $2x=\frac {2}{x}$ 时取等号，即 $x=1$ 时等号成立，
8. 所以当 $x>1$ 时， $h(x)=-2x-\frac {2}{x}+2<-2$ ，
9. 则要使对 $\forall x\in \left ({1,+\infty }\right )$ ，都有 $c>-2x-\frac {2}{x}+2$ ，则 $c\geqslant -2$ ，
10. 所以实数 $c$ 的取值范围 $\left [{-2,+\infty }\right )$
11. （3）对 $\forall x{{}_{1}}\in \left [0,1\right ],\exists x{{}_{2}}\in \left [{1,+∞}\right )$ ，使得不等式 $f\left ({x{{}_{1}}}\right )<g\left ({x{{}_{2}}}\right )$ 成立，
12. 当 $x\in \left [0,1\right ]$ 时， $f\left ({x}\right )=-2x{^{2}}+2x+4=-2(x-\frac {1}{2}){^{2}}+\frac {9}{2}$ ，所以 $f(x){{}_{{\rm \max }}}=f(\frac {1}{2})=\frac {9}{2}$ ，
13. 当 $c<0$ 时， $g\left ({x}\right )=cx+6$ 在 $\left [{1,+\infty }\right )$ 上单调递减，则 $g(x){{}_{{\rm \max }}}=g(1)=c+6$ ，
14. 则 $c+6>\frac {9}{2}$ ，解得： $-\frac {3}{2}<c<0$ ；
15. 当 $c=0$ 时， $g\left ({x}\right )=6$ 在 $\left [{1,+\infty }\right )$ 上恒成立，则满足 $g(x)>f(x){{}_{{\rm \max }}}$ ，
16. 当 $c>0$ 时， $g\left ({x}\right )=cx+6$ 在 $\left [{1,+\infty }\right )$ 上单调递增，则当 $x\to +\infty $ 时， $g(x)\to +\infty $ ，
17. 则满足对 $\forall x{{}_{1}}\in \left [0,1\right ],\exists x{{}_{2}}\in \left [{1,+∞}\right )$ ，使得不等式 $f\left ({x{{}_{1}}}\right )<g\left ({x{{}_{2}}}\right )$ 成立
18. 综上，实数 $c$ 的取值范围 $\left ({-\frac {3}{2},+\infty }\right )$

## 知识点

**中文**:
  - 一元二次不等式恒成立问题与有解问题

**English**:
  - Universally True and Solvable Problems

---
