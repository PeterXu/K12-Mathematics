# Mathematics - 题目 3290

**ID**: a1b5a23fca544379b38be269811aa1ce
**年级**: Grade 10
**难度**: Hard
**题型**: Calculation

## 题目
如果函数 $y=f(x)$ 的定义域为 ${\rm{R}}$ ，对于定义域内的任意x，存在实数a使得 $f(x+a)=f(-x)$ 成立，则称此函数具有“ $P(a)$ 性质”．（1）判断函数 $y=\sin x$ 是否具有“ $P(a)$ 性质”，若具有“ $P(a)$ 性质”求出所有a的值；​​​​​​​‌若不具有“ $P(a)$ 性质”，请说明理由．（2）已知 $y=f(x)$ 具有“ $P(0)$ 性质”，且当 $x\leqslant 0$ 时 $f(x)=(x+m){^{2}}$ ，求 $y=f(x)$ 在 $[0,1]$ 上的最大值．（3）设函数 $y=g(x)$ 具有“ $P(\pm 1)$ 性质”，且当 $-\frac {1}{2}\leqslant x\leqslant \frac {1}{2}$ 时， $g(x)=|x|$ ．若 $y=g(x)$ 与 $y=mx$ 交点个数为2023个，求m的值．

## 解答

1. （1）由 $\sin \left ({x+a}\right )=\sin \left ({-x}\right )=-\sin x$ ，所以 $a=2k{\rm{π}}+{\rm{π}},k\in {\rm{Z}}$ ，
2. 所以函数 $y=\sin x$ 具有“ $P(a)$ 性质”，其中 $a=2k{\rm{π}}+{\rm{π}},k\in {\rm{Z}}$ .
3. （2）因为 $y=f(x)$ 具有“ $P(0)$ 性质”，所以 $f\left ({x}\right )=f\left ({-x}\right )$ ，
4. 设 $x\geqslant 0$ ，则 $-x\leqslant 0$ ，所以 $f\left ({x}\right )=f\left ({-x}\right )={\left({-x+m}\right)^{2}}={\left({x-m}\right)^{2}}$ ，
5. 当 $m\leqslant 0$ 时， $f\left ({x}\right )$ 在 $[0,1]$ 为增函数，所以最大值为 $f\left ({1}\right )={\left({1-m}\right)^{2}}$ ；
6. 当 $0<m\leqslant \frac {1}{2}$ 时， $f\left ({x}\right )$ 在 $[0,m]$ 单调递减，在 $\left ({m,1}\right ]$ 单调递增，且 $f\left ({0}\right )\leqslant f\left ({1}\right )$ ，
7. 所以最大值为 $f\left ({1}\right )={\left({1-m}\right)^{2}}$ ；
8. 当 $\frac {1}{2}<m<1$ 时， $f\left ({x}\right )$ 在 $[0,m]$ 单调递减，在 $\left ({m,1}\right ]$ 单调递增，且 $f\left ({0}\right )>f\left ({1}\right )$ ，
9. 所以最大值为 $f\left ({0}\right )=m{^{2}}$ ；
10. 当 $m\geqslant 1$ 时， $f\left ({x}\right )$ 在 $[0,1]$ 为减函数，所以最大值为 $f\left ({0}\right )=m{^{2}}$ ；
11. 综上可知，当 $m>\frac {1}{2}$ 时，最大值为 $f\left ({0}\right )=m{^{2}}$ ；当 $m\leqslant \frac {1}{2}$ 时，最大值为 $f\left ({1}\right )={\left({1-m}\right)^{2}}$ .
12. （3）因为函数 $y=g(x)$ 具有“ $P(\pm 1)$ 性质”， 所以 $g\left ({1+x}\right )=g\left ({-x}\right )$ ， $g\left ({-1+x}\right )=g\left ({-x}\right )$ ；
13. 所以 $g\left ({x+2}\right )=g\left ({1+1+x}\right )=g\left ({-1-x}\right )=g\left ({x}\right )$ ，即 $g\left ({x}\right )$ 是以2为周期的函数，
14. 又设 $\frac {1}{2}\leqslant x\leqslant \frac {3}{2}$ ，则 $-\frac {1}{2}\leqslant 1-x\leqslant \frac {1}{2}$ ， $g\left ({x}\right )=g\left ({x-2}\right )=g\left ({-1+x-1}\right )=g\left ({1-x}\right )=\left |{1-x}\right |=\left |{x-1}\right |=g\left ({x-1}\right )$ .
15. 设 $n-\frac {1}{2}\leqslant x\leqslant n+\frac {1}{2}$ ， $n\in {\rm{Z}}$ ，
16. 当 $n=2k,k\in {\rm{Z}}$ 时， $2k-\frac {1}{2}\leqslant x\leqslant 2k+\frac {1}{2}$ ，即 $-\frac {1}{2}\leqslant x-2k\leqslant \frac {1}{2}$ ， $g\left ({x}\right )=g\left ({x-2k}\right )=\left |{x-2k}\right |=\left |{x-n}\right |$ ；
17. 当 $n=2k+1,k\in {\rm{Z}}$ 时， $2k+1-\frac {1}{2}\leqslant x\leqslant 2k+1+\frac {1}{2}$ ，即 $\frac {1}{2}\leqslant x-2k\leqslant \frac {3}{2}$ ， $g\left ({x}\right )=g\left ({x-2k}\right )=\left |{x-2k-1}\right |=\left |{x-n}\right |$ ；
18. 所以对于 $n-\frac {1}{2}\leqslant x\leqslant n+\frac {1}{2}$ ， $n\in {\rm{Z}}$ ，都有 $g\left ({x}\right )=\left |{x-n}\right |$ ，
19. 而 $n+1-\frac {1}{2}\leqslant x+1\leqslant n+1+\frac {1}{2}$ ，所以 $g\left ({x+1}\right )=\left |{\left ({x+1}\right )-\left ({n+1}\right )}\right |=\left |{x-n}\right |=g\left ({x}\right )$ ，
20. 综上可知 $g\left ({x}\right )$ 是以1为周期的函数.
21. 当 $m>0$ 时，要使 $y=g(x)$ 与 $y=mx$ 交点个数为2023个，只要 $y=g(x)$ 与 $y=mx$ 在区间 $\left [{0,1011}\right )$ 有2022个交点，而在 $\left [1011,1012\right ]$ 有一个公共点，
22. 所以 $y=mx$ 过 $\left ({\frac {2023}{2},\frac {1}{2}}\right )$ ，从而得 $m=\frac {1}{2023}$ ，部分简图如下；
23. 
24. 当 $m<0$ 时，要使 $y=g(x)$ 与 $y=mx$ 交点个数为2023个，只要 $y=g(x)$ 与 $y=mx$ 在区间 $\left ({-1011,0}\right ]$ 有2022个交点，而在 $\left [-1012,-1011\right ]$ 有一个公共点，
25. 所以 $y=mx$ 过 $\left ({-\frac {2023}{2},\frac {1}{2}}\right )$ ，从而得 $m=-\frac {1}{2023}$ ；
26. 当 $m=0$ 时，显然不合题意；
27. 综上可知 $m=\pm \frac {1}{2023}$ .

## 知识点

**中文**:
  - 函数新定义问题

**English**:
  - New Definition Problems in Functions

---
