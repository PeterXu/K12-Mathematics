# Mathematics - 题目 1926

**ID**: f8e18a26b09449619e86afd74e0d0867
**年级**: Grade 10
**难度**: Hard
**题型**: Calculation

## 题目
定义：对于函数 $y=f(x)$ ， $x\in D$ .​​​​​​​‌如果存在正常数 $t\in D$ ，使得当 $x$ 取其定义域 $D$ 中任意值时，有 $x+t\in D$ ，且成立 $|f(x+t)-f(x)|\leqslant f(t)$ ，则称 $y=f(x)$ 是“一致变化函数”，而这个常数 $t$ 就叫做函数 $y=f(x)$ 的“一致变化系数”.(1)给出 $f{{}_{1}}(x)={\left({\frac {1}{2}}\right)^{x}}$ ， $x\in (0,+\infty )$ .判断函数 $y=f{{}_{1}}(x)$ 是否为“一致变化函数”，并说明理由；(2)给出 $f{{}_{2}}(x)={\ln}x$ ， $x\in [a,+\infty )$ .若 $y=f{{}_{2}}(x)$ 是“一致变化函数”，求“一致变化系数” $t$ 与 $a$ 之和 $a+t$ 的最小值；(3)给出 $f{{}_{3}}(x)=\frac {1}{1+|x|}$ ， $x\in \mathbf{R}$ .求证：函数 $y=f{{}_{3}}(x)$ 是“一致变化函数”，并求“一致变化系数” $t$ 的取值范围.

## 解答

1. （1）取 $t=1$ ， $\left |{f{{}_{1}}(x+1)-f{{}_{1}}(x)}\right |={\left({\frac {1}{2}}\right)^{x}}-{\left({\frac {1}{2}}\right)^{x+1}}={\left({\frac {1}{2}}\right)^{x+1}}\leqslant \frac {1}{2}=f(1)$ ，
2. 所以函数 $y=f{{}_{1}}(x)$ 是“一致变化函数”.
3. （2） $f{{}_{2}}(x)={\ln}x$ 定义域为 $\left ({0,+\infty }\right )$ ，因为 $y=f{{}_{2}}(x)$ 是“一致变化函数”，其中 $t>0$ ，
4. $\left |{f{{}_{2}}(x+t)-f{{}_{2}}(x)}\right |=\left |{{\ln}(x+t)-{\ln}x}\right |=\left |{{\ln}\left ({1+\frac {t}{x}}\right )}\right |={\ln}\left ({1+\frac {t}{x}}\right )\leqslant f(t)={\ln}t$ 对一切 $x\in [a,+\infty )$ 成立，故有 $t>1$ .因为 $\left ({{\ln}\left ({1+\frac {t}{x}}\right )}\right ){{}_{{\rm{m}}{\rm{a}}{\rm{x}}{\rm{\;}}}}={\ln}\left ({1+\frac {t}{a}}\right )$ ，
5. 所以不等式恒成立等价于 ${\ln}\left ({1+\frac {t}{a}}\right )\leqslant {\ln}t$ 成立，所以 $1+\frac {t}{a}\leqslant t$ ，故而 $\frac {t}{t-1}\leqslant a$ ，
6. 所以 $a+t\geqslant \frac {t}{t-1}+t$ ，令 $t-1=u$ ，故 $t=1+u$ 且 $u\in [0,+\infty )$ ，
7. 所以 $a+t\geqslant \frac {t}{t-1}+t=\frac {1+u}{u}+1+u=\frac {1}{u}+u+2\geqslant 2\sqrt {\frac {1}{u}\cdot u}+2=4$ ，当且仅当 $u=1$ ，
8. 即 $t=1+u=2$ ， $a=\frac {t}{t-1}=2$ 时等号同时取到.所以 $a+t$ 的最小值为4.
9. （3）取 $t=1$ ， $f{{}_{3}}(1)=\frac {1}{2}$ ，
10. $\left |{f{{}_{3}}(x+1)-f{{}_{3}}(x)}\right |=\left |{\frac {1}{1+\left |{1+x}\right |}-\frac {1}{1+\left |{x}\right |}}\right |=\frac {\left |{\left |{x}\right |-\left |{1+x}\right |}\right |}{\left ({1+\left |{1+x}\right |}\right )\left ({1+\left |{x}\right |}\right )}$  $=\frac {1}{\left ({1+\left |{1+x}\right |}\right )\left ({1+\left |{x}\right |}\right )}\leqslant \frac {1}{1\times 2}=\frac {1}{2}$ ，
11. 所以函数 $y=f{{}_{3}}(x)$ 是“一致变化函数”.
12. $t>0$ ， $\left |{f{{}_{3}}(x+t)-f{{}_{3}}(x)}\right |=\left |{\frac {1}{1+|x+t|}-\frac {1}{1+|x|}}\right |$ ，
13. 因为 $f{{}_{3}}(x)=\frac {1}{1+|x|}$ 为偶函数且在 $[0,+\infty )$ 上为减函数，
14. 所以①当 $x<x+t\leqslant 0$ 时，有 $0\leqslant -x-t<-x=(-x-t)+t$ ，设 $u=-x-t$ ，
15. 即 $0\leqslant u<u+t$ ， $\left |{f{{}_{3}}(x+t)-f{{}_{3}}(x)}\right |=\left |{f{{}_{3}}(-x)-f{{}_{3}}(-x-t)}\right |=\left |{f{{}_{3}}(u+t)-f{{}_{3}}(u)}\right |=f{{}_{3}}(u)-f{{}_{3}}(u+t)$ ，
16. ②当 $x\leqslant 0<x+t$ 时，有 $0\leqslant -x<t$ ， $0<x+t\leqslant t$ ，
17. $\left |{f{{}_{3}}(x+t)-f{{}_{3}}(x)}\right |=\left |{f{{}_{3}}(x+t)-f{{}_{3}}(-x)}\right |\leqslant f{{}_{3}}(0)-f{{}_{3}}(0+t)$ ，
18. ③当 $0<x<x+t$ 时， $\left |{f{{}_{3}}(x+t)-f{{}_{3}}(x)}\right |=f{{}_{3}}(x)-f{{}_{3}}(x+t)$ ；
19. 综上，等价于研究 $f{{}_{3}}(x)-f{{}_{3}}(x+t)\leqslant f{{}_{3}}(t)$ 对 $x\geqslant 0$ 恒成立时 $t$ 的取值范围，
20. $f{{}_{3}}(x)-f{{}_{3}}(x+t)=\frac {1}{1+x}-\frac {1}{1+(x+t)}\leqslant f{{}_{3}}(t)=\frac {1}{1+t}$ 对 $x\geqslant 0$ 恒成立，
21. $\frac {1}{1+x}-\frac {1}{1+(x+t)}\leqslant \frac {1}{1+t}$ 恒成立， $(1+x+t)-(1+x)\leqslant \frac {(1+x+t)(1+x)}{1+t}$ 恒成立，
22. $t(1+t)\leqslant (1+x+t)(1+x)$ 对 $x\geqslant 0$ 恒成立，
23. $(1+x){^{2}}+(1+x)t-t(1+t)\geqslant 0$ 对 $x\geqslant 0$ 恒成立，
24. 令 $1+x=m$ ， $g(m)=m{^{2}}+mt-t(1+t)\geqslant 0$ 对 $m\geqslant 1$ 恒成立，
25. 又 $-\frac {t}{2}\leqslant 0$ ，所以 $g(m)=m{^{2}}+mt-t(1+t)$ 在 $m\in [1,+\infty )$ 上为严格增函数，
26. 只需 $g(1)=1{^{2}}+t-t(1+t)\geqslant 0$ 即可，解得 $t\in (0,1]$ .

## 知识点

**中文**:
  - 函数新定义问题

**English**:
  - New Definition Problems in Functions

---
