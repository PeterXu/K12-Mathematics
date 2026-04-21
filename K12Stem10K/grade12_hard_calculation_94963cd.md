# Mathematics - 题目 1556

**ID**: 94963cd54e9143d08f64262e7cd8b3ad
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=x\left ({{\ln}x-1}\right )$ .​​​​​​​‌（1）设曲线 $y=f\left ({x}\right )$ 在 $x=\frac {1}{e}$ 处的切线为 $y=g\left ({x}\right )$ ，求证： $f\left ({x}\right )\geqslant g\left ({x}\right )$ ；（2）若 $f\left ({x}\right )=a$ 有两个根 $x{{}_{1}}$ ， $x{{}_{2}}$ ，求证： $\left |{x{{}_{1}}-x{{}_{2}}}\right |<2a+e+\frac {1}{e}$ .

## 解答

1. 证明：（1）由于 $f^{′}{\left ({x}\right )}={\ln}x$ ，则 $f^{′}{\left ({\frac {1}{e}}\right )}=-1$ ，
2. 又 $f\left ({\frac {1}{e}}\right )=-\frac {2}{e}$ ，所以 $f\left ({x}\right )$ 在 $x=\frac {1}{e}$ 处的切线方程为 $y+\frac {2}{e}=-\left ({x-\frac {1}{e}}\right )$ ，
3. 即 $y=g\left ({x}\right )=-x-\frac {1}{e}$ ，
4. 令 $h\left ({x}\right )=f\left ({x}\right )-g\left ({x}\right )=x\left ({{\ln}x-1}\right )+x+\frac {1}{e}$ ，则 $h{^{\prime }}\left ({x}\right )={\ln}x+1$ ，
5. 于是当 $x\in \left ({0,\frac {1}{\mathrm{e}}}\right )$ 时， $h^{′}{\left ({x}\right )}<0$ ；
6. 当 $x\in \left ({\frac {1}{e},+\infty }\right )$ 时， $h^{′}{\left ({x}\right )}>0$ ，
7. 所以 $h\left ({x}\right )$ 在 $\left ({0,\frac {1}{\mathrm{e}}}\right )$ 上单调递减，在 $\left ({\frac {1}{e},+\infty }\right )$ 上单调递增，
8. 故 $h\left ({x}\right )\geqslant h\left ({\frac {1}{e}}\right )=0$ ，即 $f\left ({x}\right )\geqslant g\left ({x}\right )$ .
9. （2）不妨设 $x{{}_{1}}<x{{}_{2}}$ ，直线 $y=-x-\frac {1}{e}$ 与 $y=a$ 相交于点 $\left ({x{{}_{0}},a}\right )$ ，
10. 又由（1）知： $f\left ({x}\right )\geqslant g\left ({x}\right )$ ，则 $a=-x{{}_{0}}-\frac {1}{e}=f\left ({x{{}_{1}}}\right )\geqslant g\left ({x{{}_{1}}}\right )=-x{{}_{1}}-\frac {1}{e}$ ，
11. 从而 $x{{}_{1}}\geqslant x{{}_{0}}=-a-\frac {1}{e}$ ，当且仅当 $x{{}_{0}}=\frac {1}{e}$ ， $a=-\frac {2}{e}$ 时取等号.
12. 下证： $x{{}_{2}}\leqslant a+e$ .
13. 由于 $a=f\left ({x{{}_{2}}}\right )$ ，所以 $x{{}_{2}}\leqslant a+e\Leftrightarrow x{{}_{2}}\leqslant f\left ({x{{}_{2}}}\right )+e$ ，即证： $f\left ({x{{}_{2}}}\right )-x{{}_{2}}+e\geqslant 0$ ，
14. 令 $φ\left ({x}\right )=f\left ({x}\right )-x+e=x{\ln}x-2x+e$ ，则 $φ^{′}{\left ({x}\right )}={\ln}x-1$ ，
15. 当 $x\in \left ({0,e}\right )$ 时， $φ^{′}{\left ({x}\right )}<0$ ；
16. 当 $x\in \left ({e{\rm{,}}+\infty }\right )$ ， $φ^{′}{\left ({x}\right )}>0$ ；
17. 所以 $φ\left ({x}\right )$ 在 $\left ({0,e}\right )$ 上单调递减，在 $\left ({e,+\infty }\right )$ 上单调递增；
18. 故 $φ\left ({x}\right )\geqslant φ\left ({e}\right )=0$ ，即 $x{{}_{2}}\leqslant a+e$ 成立，当且仅当 $x{{}_{2}}=e$ ， $a=0$ 时取等号.
19. 由于等号成立的条件不能同时满足，
20. 所以 $\left |{x{{}_{1}}-x{{}_{2}}}\right |=x{{}_{2}}-x{{}_{1}}<\left ({a+e}\right )-\left ({-a-\frac {1}{e}}\right )=2a+e+\frac {1}{e}$ 此题考查导数的应用，考查导数的几何意义的应用，考查利用导数证明不等式，解题的关键是在第2问中设 $x{{}_{1}}<x{{}_{2}}$ ，直线 $y=-x-\frac {1}{e}$ 与 $y=a$ 相交于点 $\left ({x{{}_{0}},a}\right )$ ，
21. 又由（1）知： $f\left ({x}\right )\geqslant g\left ({x}\right )$ ，则 $a=-x{{}_{0}}-\frac {1}{e}=f\left ({x{{}_{1}}}\right )\geqslant g\left ({x{{}_{1}}}\right )=-x{{}_{1}}-\frac {1}{e}$ ，
22. 从而 $x{{}_{1}}\geqslant x{{}_{0}}=-a-\frac {1}{e}$ ，所以将问题转化为证 $x{{}_{2}}\leqslant a+e$ ，进一步转化为证明 $f\left ({x{{}_{2}}}\right )-x{{}_{2}}+e\geqslant 0$ ，然后构造函数 $φ\left ({x}\right )=f\left ({x}\right )-x+e=x{\ln}x-2x+e$ ，利用导数求其最值即可，考查计算能力和转化思想，属于较难题

## 知识点

**中文**:
  - 利用导数证明不等式

**English**:
  - Proving Inequalities using Derivatives

---
