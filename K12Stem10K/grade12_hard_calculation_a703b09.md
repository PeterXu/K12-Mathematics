# Mathematics - 题目 3789

**ID**: a703b092955248258dd4fee0a80f410d
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
设函数 $f(x)={\rm{e}}{^{x}}{\cos}x$ ， $g(x)$ 为 $f\left ({x}\right )$ 的导函数．（Ⅰ）当 $x\in \left [\frac {π}{4},\frac {π}{2}\right ]$ 时，证明： $f(x)+g(x)\left ({\frac {\mathrm{π}}{2}-x}\right )\geqslant 0$ ；​​​​​​​‌（Ⅱ）设 $x{{}_{n}}$ 为函数 $u(x)=f(x)-1$ 在区间 $\left ({2n\mathrm{π}+\frac {\mathrm{π}}{4},2n\mathrm{π}+\frac {\mathrm{π}}{2}}\right )$ 内的零点，其中 $n\in \mathbf{N}$ ，证明： $2nπ+\frac {π}{2}-x{{}_{n}}<\frac {{\rm{e}}{^{-2nπ}}}{{\sin}x{{}_{0}}-{\cos}x{{}_{0}}}$ ．

## 解答

1. （Ⅰ）证明：记 $h(x)=f(x)+g(x)\left ({\frac {\mathrm{π}}{2}-x}\right )$ ．依题意有 $g(x)=\mathrm{e}{^{x}}({\cos}x-{\sin}x)$ ，从而 $g{^{^{′}}}(x)=-2\mathrm{e}{^{x}}{\sin}x$ ．当 $x\in \left ({\frac {\mathrm{π}}{4},\frac {\mathrm{π}}{2}}\right )$ 时， $g{^{^{′}}}(x)<0$ ，故
2. $h{^{^{′}}}(x)=f{^{^{′}}}(x)+g{^{^{′}}}(x)\left ({\frac {\mathrm{π}}{2}-x}\right )+g(x)(-1)=g{^{^{′}}}(x)\left ({\frac {\mathrm{π}}{2}-x}\right )<0$ ．
3. 因此， $h\left ({x}\right )$ 在区间 $\left [\frac {\mathrm{π}}{4},\frac {\mathrm{π}}{2}\right ]$ 上单调递减，进而 $h(x)\geqslant h\left ({\frac {\mathrm{π}}{2}}\right )=f\left ({\frac {\mathrm{π}}{2}}\right )=0$ ．
4. 所以，当 $x\in \left [\frac {π}{4},\frac {π}{2}\right ]$ 时， $f(x)+g(x)\left ({\frac {\mathrm{π}}{2}-x}\right )\geqslant 0$ ．
5. （Ⅱ）证明：依题意， $u\left ({x{{}_{n}}}\right )=f\left ({x{{}_{n}}}\right )-1=0$ ，即 $\mathrm{e}{^{x{{}_{n}}}}{\cos}x{{}_{n}}=1$ ．记 $y{{}_{n}}=x{{}_{n}}-2nπ$ ，则 $y{{}_{n}}\in \left ({\frac {π}{4},\frac {π}{2}}\right )$ ，且 $f\left ({y{{}_{n}}}\right )={\rm{e}}{^{y{{}_{n}}}}{\cos}y{{}_{n}}={\rm{e}}{^{x{{}_{n}}-2nπ}}{\cos}\left ({x{{}_{n}}-2n\mathrm{π}}\right )={\rm{e}}{^{-2n\mathrm{π}}}\left ({n\in \mathbf{N}}\right )$ ．
6. 因为 $f\left ({y{{}_{n}}}\right )=\mathrm{e}{^{-2n\mathrm{π}}}\leqslant 1=f\left ({y{{}_{0}}}\right )$ 及（Ⅰ），所以 $y{{}_{n}}\geqslant y{{}_{0}}$ ．
7. 由（I）知当 $x\in \left ({\frac {\mathrm{π}}{4},\frac {\mathrm{π}}{2}}\right )$ 时， $g^{′}\left ({x}\right )<0$ ，所以 $g\left ({x}\right )$ 在 $\left [\frac {\mathrm{π}}{4},\frac {\mathrm{π}}{2}\right ]$ 上为减函数，
8. 因此 $g\left ({y{{}_{n}}}\right )\leqslant g\left ({y{{}_{0}}}\right )<g\left ({\frac {\mathrm{π}}{4}}\right )=0$ ．又由（I）知， $f\left ({y{{}_{n}}}\right )+g\left ({y{{}_{n}}}\right )\left ({\frac {\mathrm{π}}{2}-y{{}_{n}}}\right )\geqslant 0$ ，
9. 故 $\frac {π}{2}-y{{}_{n}}\leqslant -\frac {f\left ({y{{}_{n}}}\right )}{g\left ({y{{}_{n}}}\right )}=-\frac {\mathrm{e}{^{-2nπ}}}{g\left ({y{{}_{n}}}\right )}\leqslant -\frac {\mathrm{e}{^{-2nπ}}}{g\left ({y{{}_{0}}}\right )}=\frac {\mathrm{e}{^{-2nπ}}}{\mathrm{e}{^{y{{}_{0}}}}\left ({{\sin}y{{}_{0}}-{\cos}y{{}_{0}}}\right )}<\frac {\mathrm{e}{^{-2nπ}}}{{\sin}x{{}_{0}}-{\cos}x{{}_{0}}}$ ．
10. 所以， $2nπ+\frac {π}{2}-x{{}_{n}}<\frac {{\rm e}{^{-2nπ}}}{{\sin}x{{}_{0}}-{\cos}x{{}_{0}}}$ ．

## 知识点

**中文**:
  - 利用导数证明不等式

**English**:
  - Proving Inequalities using Derivatives

---
