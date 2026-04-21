# Mathematics - 题目 4002

**ID**: cc291c3fbe7542e4b1a6844f8aa77271
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
若定义在 ${\rm{R}}$ 上的函数 $y=f(x)$ 和 $y=g(x)$ 分别存在导函数 $f\prime (x)$ 和 $g\prime (x)$ ．且对任意 $x$ 均有 $f\prime (x)\geqslant g\prime (x)$ ，则称函数 $y=f(x)$ 是函数 $y=g(x)$ 的“导控函数”．我们将满足方程 $f\prime (x)=g\prime (x)$ 的 $x{{}_{0}}$ 称为“导控点”．（1）试问函数 $y=x$ 是否为函数 $y=\sin x$ 的“导控函数”？（2）若函数 $y=\frac {2}{3}x{^{3}}+8x+1$ 是函数 $y=\frac {1}{3}x{^{3}}+bx{^{2}}+cx$ 的“导控函数”，且函数 $y=\frac {1}{3}x{^{3}}+bx{^{2}}+cx$ 是函数 $y=4x{^{2}}$ 的“导控函数”，求出所有的“导控点”；​​​​​​​‌（3）若 $p(x)={\rm{e}}{^{x}}+k{\rm{e}}{^{-x}}$ ，函数 $y=q(x)$ 为偶函数，函数 $y=p(x)$ 是函数 $y=q(x)$ 的“导控函数”，求证：“ $k=1$ ”的充要条件是“存在常数 $c$ 使得 $p(x)-q(x)=c$ 恒成立”．

## 解答

1. （1）由 $y=x$ ，得 $y^{′}=1$ ，由 $y=\sin x$ ，得 $y^{′}={\cos}x$ ，
2. 因为 $1\geqslant {\cos}x$ ，所以函数 $y=x$ 是函数 $y=\sin x$ 的“导控函数”；
3. （2）由 $y=\frac {2}{3}x{^{3}}+8x+1$ ，得 $y^{′}=2x{^{2}}+8$ ，
4. 由 $y=\frac {1}{3}x{^{3}}+bx{^{2}}+cx$ ，得 $y^{′}=x{^{2}}+2bx+c$ ，
5. 由 $y=4x{^{2}}$ ，得 $\bm{y}^{′}=8\bm{x}$ ，
6. 由题意可得 $8x\leqslant x{^{2}}+2bx+c\leqslant 2x{^{2}}+8$ 恒成立，
7. 令 $8x=2x{^{2}}+8$ ，解得 $x=2$ ，
8. 故 $16\leqslant 4+4b+c\leqslant 16$ ，从而有 $4+4b+c=16$ ，所以 $c=12-4b$ ，
9. 又 $2x{^{2}}+8\geqslant x{^{2}}+2bx+c$ 恒成立，即 $x{^{2}}-2bx+8-c=x{^{2}}-2bx+4b-4\geqslant 0$ 恒成立，
10. 所以 ${\rm{Δ}}=4b{^{2}}-4\left ({4b-4}\right )=4{\left({b-2}\right)^{2}}\leqslant 0$ ，所以 $b=2$ ，
11. 故 $b=2,c=4$ 且“导控点”为 $2$ ；
12. （3）充分性：若存在常数 $c$ 使得 $p(x)-q(x)=c$ 恒成立，
13. 则 $p\left ({x}\right )=q\left ({x}\right )+c$ 为偶函数，
14. 因为函数 $y=q(x)$ 为偶函数，所以 $q\left ({x}\right )=q\left ({-x}\right )$ ，
15. 则 $p\left ({x}\right )=p\left ({-x}\right )$ ，即 ${\rm{e}}{^{x}}+k{\rm{e}}{^{-x}}={\rm{e}}{^{-x}}+k{\rm{e}}{^{x}}$ ，
16. 所以 $\left ({k-1}\right )\left ({{\rm{e}}{^{x}}-{\rm{e}}{^{-x}}}\right )=0$ 恒成立，所以 $k=1$ ；
17. 必要性：若 $k=1$ ，则 $p\left ({x}\right )={\rm{e}}{^{x}}+{\rm{e}}{^{-x}}=p\left ({-x}\right )$ ，所以函数 $p\left ({x}\right )$ 为偶函数，
18. 函数 $y=p(x)$ 是函数 $y=q(x)$ 的“导控函数”，
19. 因此 $p^{′}{\left ({x}\right )}\geqslant q^{′}{\left ({x}\right )}$ ，
20. 又 $q\left ({-x}\right )=q\left ({x}\right ),p\left ({-x}\right )=p\left ({x}\right )$ ，
21. 因此函数 $y=p(-x)$ 是函数 $y=q(-x)$ 的“导控函数”，
22. 所以 $-p^{′}{\left ({-x}\right )}\geqslant -q^{′}{\left ({-x}\right )}$ ，即 $p^{′}{\left ({-x}\right )}\leqslant q^{′}{\left ({-x}\right )}$ 恒成立，
23. 用 $-x$ 代换 $x$ 有 $p^{′}{\left ({x}\right )}\leqslant q^{′}{\left ({x}\right )}$ ，
24. 综上可知 $p^{′}{\left ({x}\right )}=q^{′}{\left ({x}\right )}$ ，记 $h\left ({x}\right )=p\left ({x}\right )-q\left ({x}\right )$ ，
25. 则 $h^{′}{\left ({x}\right )}=p^{′}{\left ({x}\right )}-q^{′}{\left ({x}\right )}=0$ ，
26. 因此存在常数 $c$ 使得 $p(x)-q(x)=c$ 恒成立，
27. 综上可得，“ $k=1$ ”的充要条件是“存在常数 $c$ 使得 $p(x)-q(x)=c$ 恒成立”．

## 知识点

**中文**:
  - 利用导数解决新定义问题

**English**:
  - Solving New Definition Problems

---
