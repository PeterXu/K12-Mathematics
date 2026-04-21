# Mathematics - 题目 85

**ID**: ed404df67f4a4168abe1ee940e15ea82
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
已知函数 $f(x)=a{\ln}x+\frac {1}{x}+2x$ ，且曲线 $y=f(x)$ 在点 $(1,f(1))$ 处的切线与直线 $y=2x$ 平行.​​​​​​​‌（1）求函数 $f(x)$ 的单调区间；（2）若关于 $x$ 的不等式 $f(x)\geqslant 2x+\frac {m}{x}$ 恒成立，求实数 $m$ 的取值范围.

## 解答

1. （1）函数 $f\left ({x}\right )$ 的定义域为 $\left \{x|x>0\right \}$ ， $f^{′}{\left ({x}\right )}=\frac {a}{x}-\frac {1}{x{^{2}}}+2$ ，
2. 又曲线 $y=f\left ({x}\right )$ 在点 $\left ({1,f\left ({1}\right )}\right )$ 处的切线与直线 $y=2x$ 平行，
3. 所以 $f^{′}{\left ({1}\right )}=a-1+2=2$ ，即 $a=1$ .
4. 所以 $f\left ({x}\right )={\rm{l}}{\rm{n}}x+\frac {1}{x}+2x$ ， $f^{′}{\left ({x}\right )}=\frac {\left ({x+1}\right )\left ({2x-1}\right )}{x{^{2}}}\left ({x>0}\right )$
5. 由 $f^{′}{\left ({x}\right )}<0$ 且 $x>0$ ，得 $0<x<\frac {1}{2}$ ，即 $f\left ({x}\right )$ 的单调递减区间是 $\left ({0,\frac {1}{2}}\right )$ ，
6. 由 $f^{′}{\left ({x}\right )}>0$ 得 $x>\frac {1}{2}$ ，即 $f\left ({x}\right )$ 的单调递增区间是 $\left ({\frac {1}{2},+\infty }\right )$ .
7. （2）由（1）知不等式 $f\left ({x}\right )\geqslant 2x+\frac {m}{x}$ 恒成立，可化为 ${\rm{l}}{\rm{n}}x+\frac {1}{x}+2x\geqslant 2x+\frac {m}{x}$ 恒成立，
8. 即 $m\leqslant x\cdot {\rm{l}}{\rm{n}}x+1$ 恒成立，
9. 令 $g\left ({x}\right )=x\cdot {\rm{l}}{\rm{n}}x+1,则g^{′}{\left ({x}\right )}={\rm{l}}{\rm{n}}x+1$
10. 当 $x\in \left ({0,\frac {1}{{\rm{e}}}}\right )$ 时， $g^{′}{\left ({x}\right )}<0$ ， $g\left ({x}\right )$ 在 $\left ({0,\frac {1}{{\rm{e}}}}\right )$ 上单调递减.
11. 当 $x\in \left ({\frac {1}{{\rm{e}}},+\infty }\right )$ 时， $g^{′}{\left ({x}\right )}>0$ ， $g\left ({x}\right )$ 在 $\left ({\frac {1}{{\rm{e}}},+\infty }\right )$ 上单调递增.
12. 所以 $x=\frac {1}{{\rm{e}}}$ 时，函数 $g\left ({x}\right )$ 有最小值，
13. 由 $m\leqslant x\cdot {\rm{l}}{\rm{n}}x+1$ 恒成立，
14. 得 $m\leqslant 1-\frac {1}{{\rm{e}}}$ ，即实数 $m$ 的取值范围是 $\left ({-\infty ,1-\frac {1}{{\rm{e}}}}\right ]$ .

## 知识点

**中文**:
  - 利用导数研究函数的单调性与单调区间
  - 利用导数解决不等式恒成立问题

**English**:
  - Monotonicity and Monotonic Intervals
  - Solving Universally True Inequalities

---
