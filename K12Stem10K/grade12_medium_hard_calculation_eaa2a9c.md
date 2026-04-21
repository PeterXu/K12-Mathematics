# Mathematics - 题目 3998

**ID**: eaa2a9c771e54b36adfd16e2231f33e5
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设 $f(x)=\sin {^{n}}x+{\cos}{^{n}}x,n\in \{n|n=2k,k\in {\mathbf{N}}{{}_{+}}\}$ .​​​​​​​‌（1）当 $n=2,4$ 时，分别求 $f(x)$ 的值域；（2）求 $f(x)$ 的值域（用 $k$ 表示）.

## 解答

1. （1）当 $n\mathrm{=}2$ 时， $f(x)=\sin {^{2}}x+{\cos}{^{2}}x=1$ ； $f(x)$ 的值域为 $\{1\}$
2. 当 $n=4$ 时， $f(x)=\sin {^{4}}x+{\cos}{^{4}}x={\left({\sin {^{2}}x+{\cos}{^{2}}x}\right)^{2}}-2\sin {^{2}}x{\cos}{^{2}}x=1-\frac {1}{2}\sin {^{2}}2x$ ，
3. $0\leqslant \sin {^{2}}2x\leqslant 1$ ，则 $\frac {1}{2}\leqslant f(x)\leqslant 1$ ；所以 $f(x)$ 的值域为 $[\frac {1}{2},1]$
4. （2）猜想 $f(x)$ 的值域为 $\{y|\frac {1}{2{^{k-1}}}\leqslant y\leqslant 1\}\left ({k\in {\mathbf{N}}{{}_{+}}}\right )$ ．
5. 证明：由（1）知，当 $k=1$ 时，结论成立；
6. 当  $k>1$ 时， $f\left ({x}\right )=\left [{\rm{s}}{\rm{i}}{\rm{n}}{^{2}}x\right ]{^{k}}+\left [{\rm{c}}{\rm{o}}{\rm{s}}{^{2}}x\right ]{^{k}}$  ，
7. 令 $\sin {^{2}}x=\frac {1}{2}-t,{\cos}{^{2}}x=\frac {1}{2}+t$    $F\left ({t}\right )={\left({\frac {1}{2}-t}\right)^{k}}+{\left({\frac {1}{2}+t}\right)^{k}}$  ，
8. 其中 $t\in \left [-\frac {1}{2}{\rm{,}}\frac {1}{2}\right ]$ ，则  $F^{′}{\left ({t}\right )}=k\left [{\left({\frac {1}{2}+t}\right)^{k-1}}-{\left({\frac {1}{2}-t}\right)^{k-1}}\right ]$  ．
9. 由 $F^{′}{\left ({t}\right )}=0$ ，得  $t=0$  ，又  $F^{′}{\left ({t}\right )}$  在  $\left [-\frac {1}{2}{\rm{,}}\frac {1}{2}\right ]$  上单调递增，
10. 所以  $t\in \left ({-\frac {1}{2}{\rm{,}}0}\right )$  时， $F^{′}{\left ({t}\right )}<F^{′}{\left ({0}\right )}=0$ ， $F\left ({t}\right )$ 单调递减；
11. $t\in \left ({0{\rm{,}}\frac {1}{2}}\right )$ 时， $F^{′}{\left ({t}\right )}>F^{′}{\left ({0}\right )}=0$ ， $F\left ({t}\right )$ 单调递增．
12. 因此 $F\left ({t}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=F\left ({0}\right )=\frac {1}{2{^{k-1}}},F\left ({t}\right ){{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}=F\left ({-\frac {1}{2}}\right )=F\left ({\frac {1}{2}}\right )=1$ .
13. 所以 $F\left ({t}\right )$  的值域为  $\left \{y|\frac {1}{2{^{k-1}}}\leqslant y\leqslant 1\right \}\left ({k\in {\mathbf{N}}{{}_{+}}}\right )$  ，
14. 综上， $f(x)$  的值域为 $\{y|\frac {1}{2{^{k-1}}}\leqslant y\leqslant 1\}\left ({k\in {\mathbf{N}}{{}_{+}}}\right )$  .

## 知识点

**中文**:
  - 二倍角的正弦
  - 利用导数研究函数的最值
  - 正弦函数的最大值与最小值

**English**:
  - Double Angle Sine
  - Global Extrema (Max/Min) using Derivatives
  - Max and Min of Sine Function

---
