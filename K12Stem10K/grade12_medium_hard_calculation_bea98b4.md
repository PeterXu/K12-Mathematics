# Mathematics - 题目 2860

**ID**: bea98b40e5f74976979428141b10c759
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f(x)=2mx-mx{\cos}x-{\sin}x(m\in R)$ ．(1)当 $m=1$ 时，求 $f(x)$ 在点 $\left ({{\rm{π}},f\left ({{\rm{π}}}\right )}\right )$ 处的切线方程；​​​​​​​‌(2)当 $x>0$ 时， $f(x)>0$ ，求实数m的取值范围．

## 解答

1. （1）因为 $f(x)=2x-x{\cos}x-{\sin}x$ ，所以 $f^{′}(x)=2-2{\cos}x+x{\sin}x$ ，
2. 因为 $f^{′}\left ({{\rm{π}}}\right )=4$ ， $f\left ({{\rm{π}}}\right )=3{\rm{π}}$ ，所以切线方程为 $y-3{\rm{π}}=4\left ({x-{\rm{π}}}\right )$ ，即 $y=4x-π$ ．
3. （2）方法一：i.若 $m\geqslant {\rm{1}}$ ，
4. 由 $2mx-mx{\cos}x-{\sin}x-(2x-x{\cos}x-{\sin}x)$  $=2(m-1)x-(m-1)x{\cos}x$  $=(m-1)x(2-{\cos}x)\geqslant 0$ ，可得 $f(x)\geqslant 2x-x{\cos}x-{\sin}x$ ，
5. 设 $g(x)=2x-x{\cos}x-{\sin}x$ ，则 $g^{′}(x)=2-2{\cos}x+x{\sin}x$ ，
6. 当 $x\in (0,π]$ 时， $g^{′}(x)>0$ ，所以 $g(x)$ 单调递增，则 $g(x)>g(0)=0$ ；
7. 当 $x\in (π,+\infty )$ 时， $g(x)=x(1-{\cos}x)+(x-{\sin}x)>0$ ，所以 $g(x)>0$ ，
8. 所以 $f(x)>0$ 恒成立，符合题意；
9. ii.若 $m\leqslant 0$ ， $f(x)=2mx-mx{\cos}x-{\sin}x$  $=mx(1-{\cos}x)+mx-{\sin}x$ ，
10. 当 $x\in \left ({0,\frac {{\rm{π}}}{2}}\right )$ 时， $f(x)<0$ ，不合题意．
11. iii.若 $0<m<1$ ， $f^{′}(x)=2m-(m+1){\cos}x+mx{\sin}x$ ，
12. 设 $h(x)=f^{′}(x)$ ，则 $h^{′}(x)=(2m+1){\sin}x+mx{\cos}x$ ，
13. 当 $x\in \left ({0,\frac {{\rm{π}}}{2}}\right )$ 时， $h^{′}(x)>0$ ，所以 $f^{\prime }(x)$ 在 $\left ({0,\frac {{\rm{π}}}{2}}\right )$ 上单调递增，
14. 因为 $f^{′}\left ({\frac {{\rm{π}}}{2}}\right )=\left ({2+\frac {{\rm{π}}}{2}}\right )m>0$ ， $f^{′}(0)<0$ ，所以存在 $x_{0}\in \left ({0,\frac {{\rm{π}}}{2}}\right )$ ，使得 $f^{′}\left ({x_{0}}\right )=0$ ，
15. 当 $x\in \left ({0,x_{0}}\right )$ 时， $f^{′}\left ({x}\right )<0$ ，则 $f(x)$ 在 $\left ({0,x_{0}}\right )$ 上单调递减， $f(x)<f(0)=0$ ，不合题意．
16. 综上所述，m的取值范围为 $[1,+\infty )$ ．
17. 方法二：由题知当 $m>0$ 时， $2mx-mx{\cos}x-{\sin}x>0$ ，即 $mx(2-{\cos}x)>{\sin}x$ ，
18. 因为 $2-{\cos}x>0$ ，所以 $mx>\frac {{\sin}x}{2-{\cos}x}$ ．
19. 设 $g(x)=\frac {{\sin}x}{2-{\cos}x}$ ，因为 $g(x+2π)=g(x)$ ，所以 $g(x)$ 为周期函数，且周期为 $2π$ ．
20. $g^{′}(x)=\frac {{\cos}x(2-{\cos}x)-{\sin}^{2}x}{(2-{\cos}x)^{2}}$  $=\frac {2{\cos}x-1}{(2-{\cos}x)^{2}}$ ，
21. 令 $g^{′}(x)=0$ ，则 $x=\frac {{\rm{π}}}{3}+2k{\rm{π}}$ 或 $x=\frac {5{\rm{π}}}{3}+2k{\rm{π}}$ ， $k\in Z$ ，
22. 所以当 $x\in \left ({-\frac {{\rm{π}}}{3}+2k{\rm{π}},\frac {{\rm{π}}}{3}+2k{\rm{π}}}\right )$ ， $k\in Z$ 时， $g^{′}(x)>0$ ，则 $g(x)$ 单调递增；
23. 当 $x\in \left ({\frac {{\rm{π}}}{3}+2kπ,\frac {5{\rm{π}}}{3}+2k{\rm{π}}}\right )$ ， $k\in Z$ 时， $g^{′}(x)<0$ ，则 $g(x)$ 单调递减．
24. 当 $x\in \left ({0,\frac {π}{3}}\right )$ 时，令 $h\left ({x}\right )=g^{′}(x)$ ，则 $h^{′}(x)=\frac {-2{\sin}x(1+{\cos}x)}{(2-{\cos}x)^{3}}<0$ ，则 $h\left ({x}\right )=g^{′}(x)$ 单调递减，∴ $g^{′}\left ({x}\right )<g^{′}(0)=1$ .
25. 当 $m=1$ 时，直线 $y=mx$ 与曲线 $y=g(x)$ 相切，如图，
26. 
27. 根据图象可知，要使 $mx>\frac {{\sin}x}{2-{\cos}x}$ ，只需 $m\geqslant 1$ ，故实数m的取值范围为 $[1,+\infty )$ ．

## 知识点

**中文**:
  - 利用导数证明不等式
  - 导数几何意义的应用

**English**:
  - Proving Inequalities using Derivatives
  - Applications of Geometric Meaning of Derivatives

---
