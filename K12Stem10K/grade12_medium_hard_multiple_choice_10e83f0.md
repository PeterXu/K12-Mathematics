# Mathematics - 题目 3906

**ID**: 10e83f0f41f34ebeb48fcd93cac7cad5
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Multiple-choice

## 题目
已知函数 $f\left ({x}\right )=\left \{\hspace{-0.​​​​​​​‌5em}\begin{array}{l}{\ln}x,x\geqslant 1\\1-\frac {x}{2},x<1\end{array}\hspace{-0.5em}\right.$ ，若 $F\left ({x}\right )=f\left [f\left ({x}\right )+1\right ]+m$ 有两个零点 $x{{}_{1}},x{{}_{2}}$ ，则 $x{{}_{1}}+x{{}_{2}}$ 的取值范围是（      ）

## 解答

1. 当 $x\geqslant {\rm{1}}$ 时， $f\left ({x}\right )+1={\ln}x+1\geqslant 1$ ， $\therefore f\left [f\left ({x}\right )+1\right ]={\ln}\left [f\left ({x}\right )+1\right ]$ ；
2. 当 $x<1$ 时， $f\left ({x}\right )+1=1-\frac {x}{2}+1>\frac {3}{2}>1$ ， $\therefore f\left [f\left ({x}\right )+1\right ]={\ln}\left [f\left ({x}\right )+1\right ]$ ，
3. 综上，对 $\forall x\in R,f\left [f\left ({x}\right )+1\right ]={\ln}\left [f\left ({x}\right )+1\right ]$ .
4. $\therefore F\left ({x}\right )=f\left [f\left ({x}\right )+1\right ]+m$ 有两个零点 $x{{}_{1}},x{{}_{2}}$ ，即方程 ${\ln}\left [f\left ({x}\right )+1\right ]+m=0$ 有两个根 $x{{}_{1}},x{{}_{2}}$ ，
5. 即方程 $f\left ({x}\right )=e{{}^{-m}}-1$ 有两个根 $x{{}_{1}},x{{}_{2}}$ ，不妨设 $x{{}_{1}}<x{{}_{2}}$ .
6. 易知函数 $f\left ({x}\right )$ 在 $\left ({-∞,1}\right )$ 上单调递减，在 $\left [{1,+\infty }\right )$ 上单调递增，
7. $\therefore $ 当 $x\geqslant {\rm{1}}$ 时， ${\ln}x{{}_{2}}=e{{}^{-m}}-1$ ；当 $x<1$ 时， $1-\frac {x{{}_{1}}}{2}=e{{}^{-m}}-1$ .
8. 令 $t=e{{}^{-m}}-1,\because 1-\frac {x{{}_{1}}}{2}>\frac {1}{2},\therefore t>\frac {1}{2}$ .
9. $\therefore x{{}_{2}}={\rm e}^{t},x{{}_{1}}=2-2t,\therefore x{{}_{1}}+x{{}_{2}}={\rm e}^{t}-2t+2,t>\frac {1}{2}$ .
10. 令 $g\left ({t}\right )={\rm e}^{t}-2t+2,t>\frac {1}{2}$ ，
11. $\therefore g{{}^{^{′}}}\left ({t}\right )={\rm e}^{t}-2$ ，令 $g{{}^{^{′}}}\left ({t}\right )=0,\therefore t={\ln}2$ .
12. $\therefore \frac {1}{2}<t<{\ln}2$ 时， $g{{}^{^{′}}}\left ({t}\right )<0$ ； $t>{\ln}2$ 时， $g{{}^{^{′}}}\left ({t}\right )>0$ ，
13. $\therefore $ 函数 $g\left ({t}\right )$ 在 $\left ({\frac {1}{2},{\ln}2}\right )$ 上单调递减，在 $\left ({{\ln}2,+\infty }\right )$ 上单调递增，
14. $\therefore $ 当 $t={\ln}2$ 时， $g\left ({t}\right ){{}_{\min }}=g\left ({{\ln}2}\right )=e{{}^{{\ln}2}}-2{\ln}2+2=4-2{\ln}2$ .
15. $\therefore $ 函数 $g\left ({t}\right )$ 的值域为 $\left [{4-2{\ln}2,+\infty }\right )$ ，即 $x{{}_{1}}+x{{}_{2}}$ 的取值范围是 $\left [{4-2{\ln}2,+\infty }\right )$ .
16. 故选： A  .

## 知识点

**中文**:
  - 利用导数解决函数零点问题

**English**:
  - Solving Zero Point Problems

---
