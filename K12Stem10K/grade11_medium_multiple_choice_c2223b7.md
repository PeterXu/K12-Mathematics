# Mathematics - 题目 3332

**ID**: c2223b71ec9a457d8b30b4d505ebb386
**年级**: Grade 11
**难度**: Medium
**题型**: Multiple-choice

## 题目
已知 $f(x)=\frac {1}{2}ax{^{2}}-{\rm e}{^{x}}+(a+1)x$ ，对任意 $x{{}_{1}},x{{}_{2}}\in (0,+\infty )$ 都有 $\frac {f\left ({x{{}_{1}}}\right )-f\left ({x{{}_{2}}}\right )}{x{{}_{1}}-x{{}_{2}}}<a$ ，则实数 $a$ 的取值范围是（      ）​​​​​​​‌

## 解答

1. 解：由题意，不妨设 $x{{}_{1}}>x{{}_{2}}$ ，
2. 因为 $\frac {f\left ({x{{}_{1}}}\right )-f\left ({x{{}_{2}}}\right )}{x{{}_{1}}-x{{}_{2}}}<a$ ，
3. 所以 $f\left ({x{{}_{1}}}\right )-f\left ({x{{}_{2}}}\right )<a\left ({x{{}_{1}}-x{{}_{2}}}\right )$ ，即 $f\left ({x{{}_{1}}}\right )-ax{{}_{1}}<f\left ({x{{}_{2}}}\right )-ax{{}_{2}}$ ，
4. 令 $g(x)=f\left ({x}\right )-ax=\frac {1}{2}ax{^{2}}-{\rm e}{^{x}}+x\left ({x>0}\right )$ ，
5. 则 $g(x{{}_{1}})<g(x{{}_{2}})$ ，所以 $g(x)$ 在 $(0,+\infty )$ 上为减函数，
6. 所以 $g^{′}(x)=ax-{\rm e}{^{x}}+1\leqslant 0$ 在 $(0,+\infty )$ 上恒成立，
7. 因为 $g^{′′}(x)=a-{\rm e}{^{x}}$ 在 $(0,+\infty )$ 上单调递减，所以 $g^{′′}(x)<g^{′′}(0)=a-1$ ，
8. 当 $a\leqslant 1$ 时， $g^{′′}(x)<0$ ，所以 $g{^{\prime }}(x)$ 在 $(0,+\infty )$ 上单调递减，
9. 所以 $g^{′}(x)<g^{′}(0)=0$ 成立，符合题意；
10. 当 $a>1$ 时，令 $g^{′′}(x)>0$ ，得 $0<x<{\ln}a$ ，
11. 所以 $g{^{\prime }}(x)$ 在 $\left ({0,{\ln}a}\right )$ 上单调递增，
12. 所以当 $x\in \left ({0,{\ln}a}\right )$ 时， $g^{′}(x)>g^{′}(0)=0$ ，不符合题意.
13. 综上，实数 $a$ 的取值范围是 $a\leqslant 1$ .
14. 故选C.

## 知识点

**中文**:
  - 利用导数解决不等式恒成立问题

**English**:
  - Solving Universally True Inequalities

---
