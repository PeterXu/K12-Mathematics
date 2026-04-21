# Mathematics - 题目 1150

**ID**: a7dc0c200a454192b04844ed363cebab
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=x{\ln}x-\frac {a}{2}x{^{2}}$ ．（1）若 $f\left ({x}\right )<2x$ 恒成立，求实数a的取值范围；​​​​​​​‌（2）判断1是否为函数 $f\left ({x}\right )$ 的极值点，并说明理由．

## 解答

1. （1）由 $f\left ({x}\right )<2x$ 可得 ${\ln}x-\frac {a}{2}x<2$ ，进而可得 $\frac {2{\ln}x-4}{x}<a$ 恒成立，
2. 令 $g(x)=\frac{2\ln x-4}{x}$ ，则 ${g}^{\prime }(x)=\frac{\frac{2}{x}x-2\ln x+4}{{x}^{2}}=\frac{6-2\ln x}{{x}^{2}}$ ，
3. 故当 $0<x<{e}^{3},{g}^{\prime }(x)>0,g(x)$ 在 $(0,{e}^{3})$ 单调递增，
4. 当 $x>{e}^{3},{g}^{\prime }(x)<0,g(x)$ 在 $({e}^{3},+\infty )$ 单调递减，
5. 故 $g{(x)}_{\max }=g({e}^{3})=\frac{2}{{e}^{3}}$ ，
6. 故 $a>\frac {2}{{\rm{e}}{^{{{3}}}}}$ ，
7. （2） ${f}^{\prime }(x)=\ln x+1-ax$
8. 假设1是函数 $f\left ({x}\right )$ 的极值点，则 ${f}^{\prime }(1)=\ln 1+1-a=0$ ，则 $a=1$ ，
9. 当 $a=1$ 时， ${f}^{\prime }(x)=\ln x+1-x$ ，
10. 令 $h\left ({x}\right )={\ln}x+1-x$ ，则 $h^{′}{\left ({x}\right )}=\frac {1}{x}-1=\frac {1-x}{x}$ ，
11. 故当 $0<x\left \langle {1,h^{′}{\left ({x}\right )}}\right \rangle 0,h\left ({x}\right )$ 在 $\left ({0,1}\right )$ 单调递增，
12. 当 $x>1,{h}^{\prime }(x)<0,h(x)$ 在 $\left ({1,+∞}\right )$ 单调递减，
13. 故 $h\left ({x}\right ){{}_{{\rm \max }}}=h\left ({1}\right )=0$ ，
14. 故 $f^{′}{\left ({x}\right )}\leqslant 0$ 在 $\left ({0,+∞}\right )$ 恒成立，故 $f\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 单调递减，此时 $f\left ({x}\right )$ 无极值，
15. 故1不是函数 $f\left ({x}\right )$ 的极值点.

## 知识点

**中文**:
  - 利用导数研究函数的极值
  - 利用导数解决不等式恒成立问题

**English**:
  - Extrema of Functions using Derivatives
  - Solving Universally True Inequalities

---
