# Mathematics - 题目 1960

**ID**: d86f97cd4d7a4c8b98936c435d09ea65
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=x+\frac {a+1}{x}-a{\ln}x$ ， $a\in {\mathbf{R}}$ .​​​​​​​‌（1）求 $f\left ({x}\right )$ 的单调性；（2）若 $a>0$ ，且 $f\left ({x}\right )$ 的最小值小于 $4-2{\ln}3$ ，求 $a$ 的取值范围.

## 解答

1. 解：（1） $f\prime (x)=1-\frac {a+1}{x{^{2}}}-\frac {a}{x}=\frac {x{^{2}}-ax-(a+1)}{x{^{2}}}=\frac {(x+1)[x-(a+1)]}{x{^{2}}}$ ， $(x>0)$ ，
2. ①当 $a\mathrm{\leqslant }-1$ 时， $f\prime (x)\mathrm{\geqslant }0$ 恒成立， $\therefore f(x)$ 在 $(0,+\infty )$ 上单调递增，
3. ②当 $a>-1$ 时，令 $f\prime (x)<0$ ，则 $0<x<a+1$ ，令 $f\prime (x)>0$ ，则 $x>a+1$ ，
4. $\therefore f(x)$ 在 $(0,a+1)$ 上单调递减，在 $(a+1,+\infty )$ 上单调递增，
5. 综上：当 $a\mathrm{\leqslant }-1$ 时， $f(x)$ 在 $(0,+\infty )$ 上单调递增，
6. 当 $a>-1$ 时， $f(x)$ 在 $(0,a+1)$ 上单调递减，在 $(a+1,+\infty )$ 上单调递增，
7. （2）由（1）知 $f(x){{}_{\min }}=f(a+1)=a+1+1-a\ln (a+1)$ ，则 $a-a\ln (a+1)<2-2\ln 3$ ，
8. 令 $g(x)=x-x\ln (x+1)$ ，则 $g\prime (x)=1-\ln (x+1)-\frac {x}{x+1}=-\ln (x+1)+\frac {1}{x+1}$ ，
9. 令 $h(x)=-\ln (x+1)+\frac {1}{x+1}$ ， $\because h\prime (x)=-\frac {1}{x+1}-\frac {1}{(x+1){^{2}}}<0$ ，
10. $\therefore h(x)$ 在 $(-1,+\infty )$ 上单调递减，又 $h(0)=1>0$ ，  $h\left ({1}\right )=\frac {1}{2}-\ln 2<0$ ，
11. $\therefore $ 存在 $x{{}_{0}}\in (0,1)$ ，使得 $h(x{{}_{0}})=0$ ，
12. 即 $g\prime (x{{}_{0}})=0$ ， $g(x)$ 在 $(0,x{{}_{0}})$ 上单调递增，在 $(x{{}_{0}}$ ， $+\infty )$ 上单调递减，
13. 又 $g(0)=0>2-2\ln 3$ ，  $g\left ({2}\right )=2-2\ln 3$ ，
14. $\therefore $  $g\left ({a}\right )<2-2\ln 3\Leftrightarrow a>2$ ．
15. $\therefore a$ 的取值范围为 $(2,+\infty )$ ．

## 知识点

**中文**:
  - 利用导数求函数中的参数
  - 利用导数研究函数的单调性与单调区间
  - 利用导数研究函数的最值

**English**:
  - Finding Parameters using Derivatives
  - Monotonicity and Monotonic Intervals
  - Global Extrema (Max/Min) using Derivatives

---
