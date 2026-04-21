# Mathematics - 题目 3768

**ID**: fd392a9878514cc688192ea33954c03d
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设函数 $f\left ({x}\right )=m{\ln}x\left ({m\in R}\right )$ ， $g\left ({x}\right )={\cos}x$ ．（1）当 $m=2$ 时，求曲线 $y=f\left ({x}\right )$ 在点 $\left ({e,f\left ({e}\right )}\right )$ 处的切线方程；​​​​​​​‌（2）若对任意的 $x\in \left ({π,\frac {3π}{2}}\right )$ ，不等式 $f\left ({x}\right )+g\left ({x}\right )\geqslant 0$ 恒成立，求 $m$ 的取值范围；（3）设 $m>0$ ，点 $P\left ({x{{}_{0}},y{{}_{0}}}\right )$ 是函数 $f\left ({x}\right )$ 与 $g\left ({x}\right )$ 的一个交点，且函数 $f\left ({x}\right )$ 与 $g\left ({x}\right )$ 在点 $P$ 处的切线互相垂直，求证：存在唯一的 $x{{}_{0}}$ 满足题意，且 $x{{}_{0}}\in \left ({1,\frac {π}{2}}\right )$ ．

## 解答

1. （1）当 $m=2$ 时， $f\left ({x}\right )=2{\ln}x$ ， $f(e)=2$ ，
2. $f^{′}(x)=\frac {2}{x}$ ，所以 $f^{′}(e)=\frac {2}{e}$ ，
3. 所以曲线 $y=f\left ({x}\right )$ 在点 $\left ({e,f\left ({e}\right )}\right )$ 处的切线方程为 $y-2=\frac {2}{e}(x-e)$ ，即 $y=\frac {2}{e}x$ .
4. （2）因为 $f\left ({x}\right )+g\left ({x}\right )\geqslant 0$ 对任意的 $x\in \left ({π,\frac {3π}{2}}\right )$ 恒成立，
5. 即 $m{\ln}x+{\cos}x\geqslant 0$ 对任意的 $x\in \left ({π,\frac {3π}{2}}\right )$ 恒成立，
6. 令 $h(x)=m{\ln}x+{\cos}x$ ， $x\in \left ({π,\frac {3π}{2}}\right )$ ，则 $h^{′}(x)=\frac {m}{x}-\sin x$ ，
7. 当 $m\leqslant 0$ 时，因为 $x\in \left ({π,\frac {3π}{2}}\right )$ ，所以 ${\ln}x<0,{\cos}x<0$ ，
8. 所以 $h(x)<0$ ，不合题意；
9. 当 $m>0$ 时，因为 $x\in \left ({π,\frac {3π}{2}}\right )$ ，所以 $\sin x<0$ ，所以 $h^{′}(x)>0$ ，
10. 所以 $h(x)$ 在 $(π,\frac {3π}{2})$ 上单调递增，
11. 故要使 $h(x)\geqslant 0$ 对任意的 $x\in \left ({π,\frac {3π}{2}}\right )$ 恒成立，只需 $h(π)\geqslant 0$ ，
12. 即 $m{\ln}π+{\cos}π\geqslant 0$ ，得 $m\geqslant $  $\frac {1}{{\ln}π}$ .
13. 所以 $m$ 的取值范围为 $[\frac {1}{{\ln}π},+\infty )$ .
14. （3）因为 $f^{′}(x)=\frac {m}{x}$ ， $g^{′}(x)=-\sin x$ ，
15. 且函数 $f\left ({x}\right )$ 与 $g\left ({x}\right )$ 在点 $P\left ({x{{}_{0}},y{{}_{0}}}\right )$ 处的切线互相垂直，
16. 所以 $\frac {m}{x{{}_{0}}}\cdot (-\sin x{{}_{0}})=-1$ ，即 $m\sin x{{}_{0}}=x{{}_{0}}$ ，①
17. 又点 $P\left ({x{{}_{0}},y{{}_{0}}}\right )$ 是函数 $f\left ({x}\right )$ 与 $g\left ({x}\right )$ 的一个交点，所以 $m{\ln}x{{}_{0}}={\cos}x{{}_{0}}$ ，②
18. 联立①②消去 $m$ 得 $x{{}_{0}}{\ln}x{{}_{0}}=\sin x{{}_{0}}{\cos}x{{}_{0}}$ ，即 $x{{}_{0}}{\ln}x{{}_{0}}-\frac {1}{2}\sin 2x{{}_{0}}=0$
19. 当 $x{{}_{0}}\in (0,1]$ ，因为 $m>0$ ，所以 $m{\ln}x{{}_{0}}\leqslant 0$ ，且 ${\cos}x{{}_{0}}>0$ ，这与②式相矛盾，
20. 所以在 $(0,1]$ 上没有 $x{{}_{0}}$ 满足题意；
21. 当 $x\in (1,+\infty )$ 时，设 $φ(x)=$  $x{\ln}x-\frac {1}{2}\sin 2x$ ，
22. 则 $φ^{′}(x)={\ln}x+1-{\cos}2x$  $>0$ ，
23. 所以函数 $φ(x)$ 在 $(1,+\infty )$ 上单调递增，
24. 所以函数 $φ(x)$ 在 $(1,+\infty )$ 上至多有一个零点，
25. 因为 $φ(1)={\ln}1-\frac {1}{2}\sin 2=-\frac {1}{2}\sin 2<0$ ，
26. $φ(\frac {π}{2})=\frac {π}{2}{\ln}\frac {π}{2}-\frac {1}{2}\sin π=\frac {π}{2}{\ln}\frac {π}{2}>0$ ，
27. 因为函数 $φ(x)$ 的图象在 $(1,+\infty )$ 连续不断，
28. 所以函数 $φ(x)$ 在 $(1,+\infty )$ 上有唯一一个零点，
29. 即只有唯一的 $x{{}_{0}}\in (1,+\infty )$ ，
30. 使得 $x{{}_{0}}{\ln}x{{}_{0}}-\frac {1}{2}\sin 2x{{}_{0}}=0$ 成立，且 $x{{}_{0}}\in (1,\frac {π}{2})$ ，
31. 综上所述：存在唯一的 $x{{}_{0}}$ 满足题意，且 $x{{}_{0}}\in \left ({1,\frac {π}{2}}\right )$ ．

## 知识点

**中文**:
  - 利用导数解决不等式恒成立问题
  - 导数几何意义的应用
  - 利用导数解决函数零点问题

**English**:
  - Solving Universally True Inequalities
  - Applications of Geometric Meaning of Derivatives
  - Solving Zero Point Problems

---
