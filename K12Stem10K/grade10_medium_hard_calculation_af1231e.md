# Mathematics - 题目 1069

**ID**: af1231e514a943d5b6a023ba14ea2149
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $y=F\left ({x}\right )$ 与 $y=f\left ({x}\right )$ 的定义域均为 ${\mathbf{R}}$ ，若对任意区间 $\left [u,v\right ]\subseteq {\mathbf{R}}$ ，存在 $p\in \left [u,v\right ]$ 且 $q\in \left [u,v\right ]$ ，使 $f\left ({p}\right )\leqslant \frac {F\left ({u}\right )-F\left ({v}\right )}{u-v}\leqslant f\left ({q}\right )$ ，则 $y=f\left ({x}\right )$ 是 $y=F\left ({x}\right )$ 的生成函数.​​​​​​​‌（1）求证： $f\left ({x}\right )=2x-1$ 是 $F\left ({x}\right )=x{^{2}}-x-1$ 的生成函数；（2）若 $f\left ({x}\right )=\left |{x+2}\right |$ 是 $y=F\left ({x}\right )$ 的生成函数，判断并证明 $y=F\left ({x}\right )$ 的单调性；（3）若 $y=f\left ({x}\right )$ 是 $y=F\left ({x}\right )$ 的生成函数，实数 $a\ne 0$ ，求 $y=F\left ({ax+b}\right )$ 的一个生成函数.

## 解答

1. （1） $\forall u,v\in {\mathbf{R}}$ ，且 $u<v$ ，
2. $\frac {F\left ({u}\right )-F\left ({v}\right )}{u-v}=\frac {u{^{2}}-u-1-\left ({v{^{2}}-v-1}\right )}{u-v}=\frac {\left ({u{^{2}}-v{^{2}}}\right )-\left ({u-v}\right )}{u-v}=\frac {\left ({u-v}\right )\left ({u+v-1}\right )}{u-v}$  $=u+v-1$ ，
3. $\because u<v$ ， $\therefore 2u-1<u+v-1<2v-1$ ，
4. $\therefore \exists p=u$ ， $q=v$ ，使得 $f\left ({p}\right )=2u-1$ ， $f\left ({q}\right )=2v-1$ ，满足 $f\left ({p}\right )\leqslant \frac {F\left ({u}\right )-F\left ({v}\right )}{u-v}\leqslant f\left ({q}\right )$ ，
5. $\therefore f\left ({x}\right )=2x-1$ 是 $F\left ({x}\right )=x{^{2}}-x-1$ 的生成函数.
6. （2） $\because f\left ({x}\right )=\left |{x+2}\right |$ 是 $y=F\left ({x}\right )$ 的生成函数，
7. $\therefore $ 对任意区间 $\left [u,v\right ]\subseteq {\mathbf{R}}$ ，存在 $p\in \left [u,v\right ]$ 且 $q\in \left [u,v\right ]$ ， $f\left ({p}\right )\leqslant \frac {F\left ({u}\right )-F\left ({v}\right )}{u-v}\leqslant f\left ({q}\right )$ ，
8. 即 $\left |{p+2}\right |\leqslant \frac {F\left ({u}\right )-F\left ({v}\right )}{u-v}\leqslant \left |{q+2}\right |$ ，
9. $\because u<v$ ， $\therefore u-v<0$ ， $\therefore \left |{q+2}\right |\left ({u-v}\right )\leqslant F\left ({u}\right )-F\left ({v}\right )\leqslant \left ({u-v}\right )\left |{p+2}\right |$ ，
10. 又 $\left ({u-v}\right )\left |{p+2}\right |<0$ ， $\therefore F\left ({u}\right )-F\left ({v}\right )<0$ ，即 $F\left ({u}\right )<F\left ({v}\right )$ ，
11. $\therefore y=F\left ({x}\right )$ 在 ${\mathbf{R}}$ 上单调递增.
12. （3） $\forall u,v\in {\mathbf{R}}$ ，且 $u<v$ ，设 $m=au+b$ ， $n=av+b$ ，
13. 则 $m-n=a\left ({u-v}\right )$ ， $\therefore \frac {F\left ({au+b}\right )-F\left ({av+b}\right )}{u-v}=\frac {F\left ({m}\right )-F\left ({n}\right )}{m-n}\cdot a$ ，
14. 当 $a>0$ 时， $y=ax+b\left ({x\in \left [u,v\right ]}\right )$ 的值域为 $\left [m,n\right ]$ ，
15. 对任意区间 $\left [m,n\right ]\subseteq {\mathbf{R}}$ ，存在 $p\in \left [u,v\right ]$ 且 $q\in \left [u,v\right ]$ ，使得 $ap+b\in \left [m,n\right ]$ 且 $aq+b\in \left [m,n\right ]$ ，满足 $f\left ({ap+b}\right )\leqslant \frac {F\left ({m}\right )-F\left ({n}\right )}{m-n}\leqslant f\left ({aq+b}\right )$ ，
16. 即 $af\left ({ap+b}\right )\leqslant \frac {F\left ({m}\right )-F\left ({n}\right )}{m-n}\cdot a\leqslant af\left ({aq+b}\right )$ ，此时 $y=af\left ({ax+b}\right )$ 是 $y=F\left ({x}\right )$ 的一个生成函数；
17. 当 $a<0$ 时， $y=ax+b\left ({x\in \left [u,v\right ]}\right )$ 的值域为 $\left [m,n\right ]$ ，
18. 对任意区间 $\left [m,n\right ]\subseteq {\mathbf{R}}$ ，存在 $p\in \left [u,v\right ]$ 且 $q\in \left [u,v\right ]$ ，使得 $ap+b\in \left [m,n\right ]$ 且 $aq+b\in \left [m,n\right ]$ ，满足 $f\left ({aq+b}\right )\leqslant \frac {F\left ({m}\right )-F\left ({n}\right )}{m-n}\leqslant f\left ({ap+b}\right )$ ，
19. 即 $af\left ({ap+b}\right )\leqslant \frac {F\left ({m}\right )-F\left ({n}\right )}{m-n}\cdot \leqslant af\left ({aq+b}\right )$ ，此时 $y=af\left ({ax+b}\right )$ 是 $y=F\left ({x}\right )$ 的一个生成函数；
20. 综上所述： $y=af\left ({ax+b}\right )$ 是 $y=F\left ({x}\right )$ 的一个生成函数.

## 知识点

**中文**:
  - 函数新定义问题

**English**:
  - New Definition Problems in Functions

---
