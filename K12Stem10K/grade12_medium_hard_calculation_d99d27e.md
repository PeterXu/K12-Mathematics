# Mathematics - 题目 2366

**ID**: d99d27ee377546a4ad183c3b462ca989
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知 $f(x)$ 是定义在 ${\mathbf{R}}$ 上的奇函数，且当 $x<0$ 时， $f(x)=\frac {{\ln}(-ex)}{x}$ ．（1）若函数 $f(x)$ 在区间 $(a,a+2)(a>0)$ 上存在极值，求实数 $a$ 的取值范围；​​​​​​​‌（2）若 $f(x)-\frac {k}{x+1}\geqslant 0$ 对任意的 $x\in [1,+\infty )$ 恒成立，求实数 $k$ 的最大值．

## 解答

1. （1）依题意 $f(x)$ 是定义在 ${\mathbf{R}}$ 上的奇函数，当 $x>0$ 时， $-x<0$ ，所以
2. $f\left ({x}\right )=-f\left ({-x}\right )=-\frac {{\ln}\left ({ex}\right )}{-x}=\frac {{\ln}\left ({ex}\right )}{x}$ .
3. 即当 $x>0$ 时， $f\left ({x}\right )=\frac {{\ln}\left ({ex}\right )}{x}$ ，
4. $f{^{^{′}}}\left ({x}\right )=\frac {1-{\ln}\left ({ex}\right )}{x{^{2}}}$ ，
5. 所以 $f\left ({x}\right )$ 在区间 $\left ({0,1}\right )$ 上 $f{^{^{′}}}\left ({x}\right )>0,f\left ({x}\right )$ 递增，在 $\left ({1,+\infty }\right )$ 上 $f{^{^{′}}}\left ({x}\right )<0,f\left ({x}\right )$ 递减.
6. 所以 $x=1$ 是 $f\left ({x}\right )$ 的极大值点，也是 $f\left ({x}\right )$ 在区间 $\left ({0,+∞}\right )$ 上的唯一极值点.
7. 所以 $0<a<1<a+2$ ，即 $0<a<1$
8. （2）依题意 $f(x)-\frac {k}{x+1}\geqslant 0$ 对任意的 $x\in [1,+\infty )$ 恒成立，
9. 即 $k\leqslant \left ({x+1}\right )f\left ({x}\right )$ 对任意的 $x\in [1,+\infty )$ 恒成立.
10. $k\leqslant \left ({x+1}\right )f\left ({x}\right )=\left ({x+1}\right )\cdot \frac {{\ln}\left ({ex}\right )}{x}=\frac {\left ({x+1}\right )\cdot \left ({1+{\ln}x}\right )}{x}$ .
11. 令 $g\left ({x}\right )=\frac {\left ({x+1}\right )\cdot \left ({1+{\ln}x}\right )}{x}\left ({x\geqslant 1}\right )$ .
12. $g{^{^{′}}}\left ({x}\right )=\frac {\left [\left ({x+1}\right )\cdot \left ({1+{\ln}x}\right )\right ]{^{^{′}}}\cdot x-\left ({x+1}\right )\cdot \left ({1+{\ln}x}\right )\cdot x{^{^{′}}}}{x{^{2}}}$
13. $=\frac {x-{\ln}x}{x{^{2}}}$ ，
14. 令 $h\left ({x}\right )=x-{\ln}x\left ({x\geqslant 1}\right )$ ， $h{^{^{′}}}\left ({x}\right )=1-\frac {1}{x}=\frac {x-1}{x}$ ，
15. 所以 $h\left ({x}\right )$ 在区间 $\left ({1,+\infty }\right )$ 上 $h{^{^{′}}}\left ({x}\right )>0$ ， $h\left ({x}\right )$ 单调递增，
16. $h\left ({1}\right )=1$ ，所以 $h\left ({x}\right )\geqslant h\left ({1}\right )=1$ ，
17. 故 $g{^{^{′}}}\left ({x}\right )>0$ ， $g\left ({x}\right )$ 在 $\left ({1,+\infty }\right )$ 上递增，
18. $g\left ({x}\right )\geqslant g\left ({1}\right )=2$ ，
19. 所以 $k\leqslant 2$ .
20. 所以 $k$ 的最大值为 $2$ .

## 知识点

**中文**:
  - 利用导数求函数中的参数
  - 利用导数解决不等式恒成立问题

**English**:
  - Finding Parameters using Derivatives
  - Solving Universally True Inequalities

---
