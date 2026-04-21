# Mathematics - 题目 1962

**ID**: 684cc2318d0d4bcfa915fc6864d58a2f
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设 $f\left ({x}\right )=x{^{2}}-2tx+1$ ， $g(x)=-x{^{2}}+4tx+1$ ，其中 $t>0$ ，记 $F(x)={\rm \min }\{f(x),g(x)\}$ ．（1）若 $t=1$ ，求 $F\left ({x}\right )$ 的值域；​​​​​​​‌（2）若 $t>0$ ，记函数 $h(x)=f(x)-1+t{^{2}}$ 对任意 $x\in [2t-1,2t]$ ，总存在 $m\in [0,9]$ ，使得 $h\left ({x}\right )=m$ 成立，求实数t的取值范围；（3）若 $\forall x\in [0,3]{\rm{,}}\left |{F(x)-\frac {1}{2}}\right |\leqslant \frac {3}{2}$ ，求实数t的取值范围．

## 解答

1. （1）当 $t=1$ 时， $f\left ({x}\right )=x{^{2}}-2x+1$ ， $g(x)=-x{^{2}}+4x+1$ ，
2. 当 $f(x)\leqslant g(x)$ 时， $x{^{2}}-2x+1\leqslant -x{^{2}}+4x+1$ ，解得 $0\leqslant x\leqslant 3$ ，
3. 此时 $F(x)=\begin{cases}-x{^{2}}+4x+1,x\in (-\mathrm{∞},0)\cup (3,+\mathrm{∞})，\\x{^{2}}-2x+1,x\in [0,3]，\end{cases}$
4. 当 $x\in (-\infty ,0)$ 时 $F(x)<1$ ，当 $x\in [0,3]$ 时 $0\leqslant F(x)\leqslant 4$ 当 $x\in (3,+\infty )$ 时 $F(x)\leqslant 4$ ，
5. 所以 $F\left ({x}\right )$ 的值域为 $(-\infty ，4]$ .
6. （2） $h(x)=f(x)-1+t{^{2}}=x{^{2}}-2tx+t{^{2}}=(x-t){^{2}}$ ，可知 $h(x)$ 是以 $x=t$ 为对称轴，开口向上的二次函数.
7. 当 $t>0$ ，函数 $h(x)=(x-t){^{2}}$ 对任意 $x\in [2t-1,2t]$ ，总存在 $m\in [0,9]$ ，使得 $h\left ({x}\right )=m$ 成立，即函数 $h(x)$ 在 $[2t-1,2t]$ 上的值域与区间 $[0,9]$ 的子集即可，
8. 当 $2t-1\leqslant t\leqslant 2t$ 时， $h(x)$ 在 $x=t$ 时取得最小， $h(t)=0$ ，则 $\begin{cases}h(2t-1)\leqslant 9，\\h(2t)\leqslant 9\end{cases}$ 满足条件即可，即 $\begin{cases}{\left({t-1}\right)^{2}}\leqslant 9，\\t{^{2}}\leqslant 9，\end{cases}$ 解得 $0\leqslant t\leqslant 1$ .
9. 当 $2t-1>t$ 时，即 $t>1$ 时， $h(x)$ 在 $[2t-1,2t]$ 上单调递增，则 $\begin{cases}h(2t-1)\geqslant 0，\\h(2t)\leqslant 9\end{cases}$ 满足条件即可，则 $\begin{cases}{\left({t-1}\right)^{2}}\geqslant 0，\\t{^{2}}\leqslant 9，\end{cases}$ 解得 $1<t\leqslant 3$ .
10. 综上所述， $t$ 的取值范围为 $[0,3]$ .
11. （3）已知 $\left |{F(x)-\frac {1}{2}}\right |\leqslant \frac {3}{2}$ ，解得 $-1\leqslant F(x)\leqslant 2$ ，
12. 当 $f(x)\leqslant g(x)$ 时， $x{^{2}}-2tx+1\leqslant -x{^{2}}+4tx+1$ ，解得 $0\leqslant x\leqslant 3t$ ，
13. 可得 $F(x)=\begin{cases}-x{^{2}}+4tx+1,x\in (-\mathrm{∞},0)\cup (3t,+\mathrm{∞})，\\x{^{2}}-2tx+1,x\in [0,3t]，\end{cases}$
14. 当 $0<t<1$ 时， $0<3t\leqslant 3$ ， $F(x)=\begin{cases}-x{^{2}}+4tx+1,x\in (3t,3]，\\x{^{2}}-2tx+1,x\in [0,3t]，\end{cases}$
15. 此时满足 $\begin{cases}f(t)\geqslant -1，\\g(3t)\leqslant 2，\\g(3)\geqslant -1\end{cases}$ 即可，代入得 $\begin{cases}t{^{2}}-2t{^{2}}+1\geqslant -1，\\-{\left({3t}\right)^{2}}+4t\times \left ({3t}\right )+1\leqslant 2，\\-3{^{2}}+4t\times 3+1\geqslant -1，\end{cases}$ 无解
16. 当 $t=1$ 时，  $F(x)=x{^{2}}-2x+1=(x-1){^{2}},x\in [0,3]$ ，此时最小值为 $F(1)=0$ ，最大值 $F(3)=4$ ，不符合题意，舍去.
17. 当 $t>1$ 时， $3t>3$ ， $F(x)=x{^{2}}-2tx+1,x\in [0,3]$ .
18. 当 $1<t<\frac {3}{2}$ 时，满足 $\begin{cases}f(t)\geqslant -1\\f(3)\leqslant 2\end{cases}$ 即可，代入得 $\begin{cases}t{^{2}}-2t{^{2}}+1\geqslant -1，\\3{^{2}}-2t\times 3+1\leqslant 2，\end{cases}$ 解得 $\frac {4}{3}\leqslant t\leqslant \sqrt {2}$ ，
19. 当 $t\geqslant \frac {3}{2}$ 时，满足 $f(t)\geqslant -1$ 即可，代入得 $t{^{2}}-2t{^{2}}+1\geqslant -1$ ，无解，
20. 综上所述， $t$ 的范围为 $[\frac {4}{3},\sqrt {2}]$ .

## 知识点

**中文**:
  - 二次函数与一元二次方程、不等式的综合问题

**English**:
  - Quadratic Functions, Equations and Inequalities

---
