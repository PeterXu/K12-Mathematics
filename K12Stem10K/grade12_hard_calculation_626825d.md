# Mathematics - 题目 3643

**ID**: 626825d3e5ed482584e989ef9c81dc98
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\frac {1}{2}x{\rm{s}}{\rm{i}}{\rm{n}}x-\frac {3}{4}$ ．(1)证明：当 $x\in \left [0,{\rm{π}}\right ]$ 时， ${\rm{e}}{^{x}}-x-\frac {7}{4}\geqslant f\left ({x}\right )$ ；​​​​​​​‌(2)求 $f\left ({x}\right )$ 在区间 $\left [0,{\rm{π}}\right ]$ 上的零点个数．

## 解答

1. （1）设 $g\left ({x}\right )={\rm{e}}{^{x}}-x-\frac {7}{4}-f\left ({x}\right )={\rm{e}}{^{x}}-x-1-\frac {1}{2}x{\rm{s}}{\rm{i}}{\rm{n}}x$ ，则 $g^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-1-\frac {1}{2}\left ({{\rm{s}}{\rm{i}}{\rm{n}}x+x{\rm{c}}{\rm{o}}{\rm{s}}x}\right )$ ．
2. 设 $m\left ({x}\right )=g^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-1-\frac {1}{2}\left ({{\rm{s}}{\rm{i}}{\rm{n}}x+x{\rm{c}}{\rm{o}}{\rm{s}}x}\right )$ ，
3. 则 $m^{′}{\left ({x}\right )}={\rm{e}}{^{x}}+\frac {1}{2}\left ({x{\rm{s}}{\rm{i}}{\rm{n}}x-2{\rm{c}}{\rm{o}}{\rm{s}}x}\right )={\rm{e}}{^{x}}-{\rm{c}}{\rm{o}}{\rm{s}}x+\frac {1}{2}x{\rm{s}}{\rm{i}}{\rm{n}}x$ ，
4. 因为 $y={\rm{e}}{^{x}}-{\rm{c}}{\rm{o}}{\rm{s}}x$ 在 $\left [0,{\rm{π}}\right ]$ 上单调递增，所以 ${\rm{e}}{^{x}}-{\rm{c}}{\rm{o}}{\rm{s}}x\geqslant {\rm{e}}{^{0}}-{\rm{c}}{\rm{o}}{\rm{s}}0=0$ ，
5. 又因为当 $x\in \left [0,{\rm{π}}\right ]$ 时， $\frac {1}{2}x{\rm{s}}{\rm{i}}{\rm{n}}x\geqslant 0$ ，所以 $m^{′}{\left ({x}\right )}\geqslant 0$ ，
6. 所以 $m\left ({x}\right )$ 在 $\left [0,{\rm{π}}\right ]$ 上单调递增，所以 $m\left ({x}\right )\geqslant m\left ({0}\right )=0$ ，
7. 所以 $g\left ({x}\right )$ 在 $\left [0,{\rm{π}}\right ]$ 上单调递增，所以 $g\left ({x}\right )\geqslant g\left ({0}\right )=0$ ，
8. 所以当 $x\in \left [0,{\rm{π}}\right ]$ 时， ${\rm{e}}{^{x}}-x-\frac {7}{4}\geqslant f\left ({x}\right )$ ．
9. （2） $f^{′}{\left ({x}\right )}=\frac {1}{2}\left ({{\rm{s}}{\rm{i}}{\rm{n}}x+x{\rm{c}}{\rm{o}}{\rm{s}}x}\right )$ ，当 $x\in \left [0,\frac {{\rm{π}}}{2}\right ]$ 时， $f^{′}{\left ({x}\right )}\geqslant 0$ ，所以 $f\left ({x}\right )$ 在 $\left [0,\frac {{\rm{π}}}{2}\right ]$ 上单调递增，
10. 因为 $f\left ({0}\right )=-\frac {3}{4}<0,f\left ({\frac {{\rm{π}}}{2}}\right )=\frac {{\rm{π}}-3}{4}>0$ ，所以由零点存在定理知 $f\left ({x}\right )$ 在 $\left [0,\frac {{\rm{π}}}{2}\right ]$ 上有且仅有一个零点．
11. 当 $x\in \left [\frac {{\rm{π}}}{2},{\rm{π}}\right ]$ 时，令 $h\left ({x}\right )=f^{′}{\left ({x}\right )}=\frac {1}{2}\left ({{\rm{s}}{\rm{i}}{\rm{n}}x+x{\rm{c}}{\rm{o}}{\rm{s}}x}\right )$ ，则 $h^{′}{\left ({x}\right )}=\frac {1}{2}\left ({2{\rm{c}}{\rm{o}}{\rm{s}}x-x{\rm{s}}{\rm{i}}{\rm{n}}x}\right )$ ，
12. 当 $x\in \left ({\frac {{\rm{π}}}{2},{\rm{π}}}\right )$ 时，有 $h^{′}{\left ({x}\right )}<0$ ，所以 $h\left ({x}\right )$ 在 $\left [\frac {{\rm{π}}}{2},{\rm{π}}\right ]$ 上单调递减，
13. 又因为 $h\left ({\frac {{\rm{π}}}{2}}\right )=\frac {1}{2}>0,h\left ({{\rm{π}}}\right )=-\frac {{\rm{π}}}{2}<0$ ，所以存在 $m\in \left ({\frac {{\rm{π}}}{2},{\rm{π}}}\right )$ 使得 $h\left ({m}\right )=0$ ，
14. 当 $x\in \left ({\frac {{\rm{π}}}{2},m}\right )$ 时， $h\left ({x}\right )>h\left ({m}\right )=0$ ，所以 $f\left ({x}\right )$ 在 $\left ({\frac {{\rm{π}}}{2},m}\right )$ 上单调递增，
15. 所以当 $x\in \left [\frac {{\rm{π}}}{2},m\right ]$ 时 $f\left ({x}\right )\geqslant f\left ({\frac {{\rm{π}}}{2}}\right )=\frac {{\rm{π}}-3}{4}>0$ ，故 $f\left ({x}\right )$ 在 $\left [\frac {{\rm{π}}}{2},m\right ]$ 上无零点，
16. 当 $x\in \left ({m,{\rm{π}}}\right )$ 时， $h\left ({x}\right )<h\left ({m}\right )=0$ ，所以 $f\left ({x}\right )$ 在 $\left ({m,{\rm{π}}}\right )$ 上单调递减，
17. 又 $f\left ({m}\right )>f\left ({\frac {{\rm{π}}}{2}}\right )>0,f\left ({{\rm{π}}}\right )=-\frac {3}{4}<0$ ，所以 $f\left ({x}\right )$ 在 $\left ({m,{\rm{π}}}\right )$ 上有且仅有一个零点．
18. 综上所述： $f\left ({x}\right )$ 在 $\left [0,{\rm{π}}\right ]$ 上有且只有2个零点．

## 知识点

**中文**:
  - 利用导数解决函数零点问题
  - 利用导数证明不等式

**English**:
  - Solving Zero Point Problems
  - Proving Inequalities using Derivatives

---
