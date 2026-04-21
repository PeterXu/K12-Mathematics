# Mathematics - 题目 3836

**ID**: d8782b2520044f6eb38dcfb08856031d
**年级**: Grade 11
**难度**: Hard
**题型**: Calculation

## 题目
设 $f\left ({x}\right )=x\sin x+{\cos}x,g\left ({x}\right )=x{^{2}}+4$ .​​​​​​​‌（1）讨论 $f\left ({x}\right )$ 在 $\left [-π,π\right ]$ 上的单调性；（2）令 $h\left ({x}\right )=g\left ({x}\right )-4f\left ({x}\right )$ ，试证明 $h\left ({x}\right )$ 在 $R$ 上有且仅有三个零点.

## 解答

1. （1）首先求导得到 $f^{′}(x)=x{\cos}x$ ，再根据导函数的正负性即可得到函数的单调区间.
2. （2）首先根据 $h(x)=x{^{2}}+4-4x\sin x-4{\cos}x$ ， $h(0)=0$ 得到 $x=0$ 是 $h(x)$ 的一个零点，再根据 $h(x)$ 是偶函数得到 $h(x)$ 在 $\mathbf{R}$ 上的零点个数，只需确定 $x>0$ 时， $h(x)$ 的零点个数即可，再求出 $h(x)$ 在 $x>0$ 时的单调性和最值，确定其零点个数即可.
3. $f^{′}(x)=\sin x+x{\cos}x-\sin x=x{\cos}x$ ，
4. 令 $f^{′}(x)=0$ ，则 $x=0$ 或 $x=\pm \frac {π}{2}$ .
5. $x\in \left ({-π,-\frac {π}{2}}\right )$ 时， $f^{′}(x)>0$ ， $f(x)$ 单调递增，
6. $x\in \left ({-\frac {π}{2},0}\right )$ 时 $f^{′}(x)<0$ ， $f(x)$ 单调递减，
7. $x\in \left ({0,\frac {π}{2}}\right )$ 时， $f^{′}(x)>0$ ， $f(x)$ 单调递增，
8. $x\in \left ({\frac {π}{2},π}\right )$ 时， $f^{′}(x)<0$ ， $f(x)$ 单调递减.
9. $\therefore f(x)$ 的单调递增区间是 $\left ({-π,-\frac {π}{2}}\right ),\left ({0,\frac {π}{2}}\right )$ ，
10. 递减区间是 $\left ({-\frac {π}{2},0}\right ),\left ({\frac {π}{2},π}\right )$ .
11. （2） $h(x)=x{^{2}}+4-4x\sin x-4{\cos}x$ ，
12. 因为 $h(0)=0$ ，所以 $x=0$ 是 $h(x)$ 的一个零点.
13. $h(-x)=(-x){^{2}}+4-4(-x)\sin (-x)-4{\cos}(-x)=x{^{2}}+4-4x\sin x-4{\cos}x=h(x)$
14. 所以 $h(x)$ 是偶函数，
15. 即要确定 $h(x)$ 在 $R$ 上的零点个数，需确定 $x>0$ 时， $h(x)$ 的零点个数即可.
16. ①当 $x>0$ 时， $h^{′}(x)=2x-4x{\cos}x=2x(1-2{\cos}x)$
17. 令 $h^{′}(x)=0$ ，即 ${\cos}x=\frac {1}{2}，x=\frac {π}{3}+2kx$ 或 $x=-\frac {π}{3}+2kx$  $(k\in \mathbf{N})$ .
18. $x\in (0,\frac {π}{3})$ 时， $h^{′}(x)<0,h(x)$ 单调递减，
19. 且 $h(\frac {π}{3})=\frac {π{^{2}}}{9}+2-\frac {2\sqrt {3}}{3}π<0$ ，
20. $x\in (\frac {π}{3},\frac {5}{3}π)$ 时， $h^{′}(x)>0$ ， $h(x)$ 单调递增，
21. 且 $h(\frac {5}{3}π)=\frac {25}{9}π{^{2}}+\frac {10\sqrt {3}}{3}π+2>0$
22. $\therefore h(x)$ 在 $(0,\frac {5}{3}π)$ 有唯一零点
23. ②当 $x\geqslant \frac {5}{3}π$ 时，由于 $\sin x\leqslant 1$ ， ${\cos}x\leqslant 1$ .
24. $h(x)=x{^{2}}+4-4x\sin x-4{\cos}x$
25. $\geqslant x{^{2}}+4-4x-4=x{^{2}}-4x=t(x)$
26. 而 $t(x)$ 在 $(\frac {5}{3}π,+\infty )$ 单调递增， $t(x)\geqslant t(\frac {5}{3}π)>0$
27. 所以 $h(x)>0$ 恒成立，故 $h(x)$ 在 $(\frac {5}{3}π,+\infty )$ 无零点，
28. 所以 $h(x)$ 在 $(0,+\infty )$ 有一个零点，
29. 由于 $h(x)$ 是偶函数，所以 $h(x)$ 在 $(-\infty ,0)$ 有一个零点，而 $h(0)=0$ ，
30. 综上 $h(x)$ 在 $R$ 有且仅有三个零点.

## 知识点

**中文**:
  - 利用导数研究函数的单调性与单调区间
  - 利用导数解决函数零点问题

**English**:
  - Monotonicity and Monotonic Intervals
  - Solving Zero Point Problems

---
