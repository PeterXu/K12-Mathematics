# Mathematics - 题目 1074

**ID**: 221d1f75bd594d1ca4ab8b6719c781f4
**年级**: Grade 12
**难度**: Medium
**题型**: 解答题：共6小题，共85分．解答应写出文字说明，演算步骤或证明过程．

## 题目
已知函数 $f\left ({x}\right )={\rm{e}}{^{x}}(x-a){^{2}}$ ．（1）若 $f\left ({x}\right )$ 在 $x=-1$ 处的切线与 $x$ 轴平行，求 $a$ 的值；​​​​​​​‌（2） $f\left ({x}\right )$ 有两个极值点 $x{{}_{1}},x{{}_{2}}$ ，比较 $f\left ({\frac {x{{}_{1}}+x{{}_{2}}}{2}}\right )$ 与 $\frac {f\left ({x{{}_{1}}}\right )+f\left ({x{{}_{2}}}\right )}{2}$ 的大小；（3）若 $f\left ({x}\right )$ 在 $\left [-1,1\right ]$ 上的最大值为 $4{\rm{e}}$ ，求 $a$ 的值．

## 解答

1. （1） $f^{′}{\left ({x}\right )}={\rm{e}}{^{x}}(x-a){^{2}}+{\rm{e}}{^{x}}\cdot 2(x-a)={\rm{e}}{^{x}}\left [x{^{2}}+(2-2a)x+a{^{2}}-2a\right ]$ ，
2. 由 $f^{′}{\left ({-1}\right )}={\rm{e}}{^{-1}}\left [1-(2-2a)+a{^{2}}-2a\right ]=0$ ，解得 $a=\pm 1$ ，
3. 当 $a=1$ 时， $f\left ({x}\right )={\rm{e}}{^{x}}(x-{{1}}){^{2}}$ ， $f\left ({-1}\right )=4{\rm{e}}{^{-1}}$ ，符合题意；
4. 当 $a=-1$ 时， $f\left ({x}\right )={\rm{e}}{^{x}}(x+{{1}}){^{2}}$ ， $f\left ({-1}\right )=0$ ，此时切线与x轴重合，不符合题意；
5. 所以 $a=1$ ；
6. （2）由（1）知： $f^{′}{\left ({x}\right )}={\rm{e}}{^{x}}\left [x{^{2}}+(2-2a)x+a{^{2}}-2a\right ]={\rm{e}}{^{x}}\left ({x-a}\right )\left [x-(a-2)\right ]$ ，令 $f^{′}(x)=0$ 可得 $x=a$ 或 $a-2$ ，
7. 则 $f\left ({x}\right )$ 在 $\left ({-\infty ,a-2}\right ),(a,+\infty )$ 单增，在 $\left ({a-2,a}\right )$ 上单减，则 $a-2,a$ 是 $f\left ({x}\right )$ 的两个极值点，不妨设 $x{{}_{1}}=a-2,x{{}_{2}}=a$ ，
8. 则 $f\left ({\frac {x{{}_{1}}+x{{}_{2}}}{2}}\right )=f\left ({\frac {a-2+a}{2}}\right )=f(a-1)={\rm e}{^{a-1}}$ ， $\frac {f\left ({x{{}_{1}}}\right )+f\left ({x{{}_{2}}}\right )}{2}=\frac {f\left ({a-2}\right )+f\left ({a}\right )}{2}=\frac {4{\rm e}{^{a-2}}+0}{2}=2{\rm e}{^{a-2}}$ ，
9. 又 ${\rm }{\rm e}{^{a-1}}={\rm e}\cdot {\rm e}{^{a-2}}>2{\rm e}{^{a-2}}{\rm }$ ，即 $f\left ({\frac {x{{}_{1}}+x{{}_{2}}}{2}}\right )>\frac {f\left ({x{{}_{1}}}\right )+f\left ({x{{}_{2}}}\right )}{2}$ ；
10. （3）由（2）知： $f\left ({x}\right )$ 在 $\left ({-\infty ,a-2}\right ),(a,+\infty )$ 单增，在 $\left ({a-2,a}\right )$ 上单减．
11. 当 $a\geqslant 3$ 时， $a-2\geqslant 1$ ，则 $f\left ({x}\right )$ 在 $\left [-1,1\right ]$ 上单增，则 $f\left ({x}\right ){{}_{{\rm \max }}}=f(1)={\rm{e}}(1-a){^{2}}=4{\rm{e}}$ ，解得 $a=3$ 或 $-1$ ，故 $a=3$ ；
12. 当 $1<a<3$ 时， $-1<a-2<1$ ，则 $f\left ({x}\right )$ 在 $\left [{-1,a-2}\right )$ 上单增，在 $\left ({a-2,1}\right ]$ 上单减，
13. 则 $f\left ({x}\right ){{}_{{\rm \max }}}=f(a-2)=4{\rm{e}}{^{a-2}}=4{\rm{e}}$ ，解得 $a=3$ ，不满足 $1<a<3$ ，不合题意；
14. 当 $a=1$ 时， $a-2=-1$ ，则 $f\left ({x}\right )$ 在 $\left [-1,1\right ]$ 上单减，则 $f\left ({x}\right ){{}_{{\rm \max }}}=f(-1)={\rm{e}}{^{-1}}(-1-a){^{2}}=\frac {4}{{\rm e}}\ne 4{\rm{e}}$ ，不合题意；
15. 当 $-1<a<1$ 时， $a-2<-1$ ，则 $f\left ({x}\right )$ 在 $\left [{-1,a}\right )$ 上单减，在 $\left ({a,1}\right ]$ 上单增，则 $f\left ({x}\right ){{}_{{\rm \max }}}=\left \{f(-1),f(1)\right \}{{}_{{\rm \max }}}$ ，
16. 若 $f(-1)\geqslant f(1)$ ，则 $f\left ({x}\right ){{}_{{\rm \max }}}=f(-1)={\rm{e}}{^{-1}}(-1-a){^{2}}=4{\rm{e}}$ ，解得 $a=2{\rm e}-1$ 或 $-2{\rm e}-1$ ，不满足 $-1<a<1$ ，不合题意，
17. 若 $f(1)>f(-1)$ ，则 $f\left ({x}\right ){{}_{{\rm \max }}}=f(1)={\rm{e}}(1-a){^{2}}=4{\rm{e}}$ ，解得 $a=3$ 或 $-1$ ，不满足 $-1<a<1$ ，不合题意；
18. 当 $a\leqslant -1$ 时，则 $f\left ({x}\right )$ 在 $\left [-1,1\right ]$ 上单增，则 $f\left ({x}\right ){{}_{{\rm \max }}}=f(1)={\rm{e}}(1-a){^{2}}=4{\rm{e}}$ ，解得 $a=3$ 或 $-1$ ，故 $a=-1$ ；
19. 综上： $a=3$ 或 $-1$ ．

## 知识点

**中文**:
  - 利用导数研究函数的最值
  - 导数几何意义的应用
  - 利用导数研究函数的极值

**English**:
  - Global Extrema (Max/Min) using Derivatives
  - Applications of Geometric Meaning of Derivatives
  - Extrema of Functions using Derivatives

---
