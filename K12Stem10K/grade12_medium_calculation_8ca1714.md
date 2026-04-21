# Mathematics - 题目 910

**ID**: 8ca1714cb1a44889b96aae2d82b67e3a
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
已知 $\vartriangle ABC$ 的内角A，B，C的对边分别为a，b，c，满足 $2{\cos}A{\cos}B=2{\sin}{^{2}}\frac {C}{2}$ ．(1)试判断 $\vartriangle ABC$ 的形状；​​​​​​​‌(2)若 $\vartriangle ABC$ 的外接圆半径为2，求 $\vartriangle ABC$ 周长的最大值．

## 解答

1. （1）由题意可知： $2{\cos}A{\cos}B=2{\sin}{^{2}}\frac {C}{2}=1-{\cos}C=1+{\cos}\left ({A+B}\right )$
2. $=1+{\cos}A{\cos}B-{\sin}A{\sin}B$ ，
3. 整理得 ${\cos}A{\cos}B+{\sin}A{\sin}B={\cos}\left ({A-B}\right )=1$ ，
4. 且 $A,B\in \left ({0,{\rm{π}}}\right )$ ，则 $A-B\in \left ({-{\rm{π}},{\rm{π}}}\right )$ ，可知 $A-B=0$ ，即 $A=B$ ，
5. 所以 $\vartriangle ABC$ 为等腰三角形.
6. （2）由正弦定理 $\frac {a}{{\sin}A}=\frac {b}{{\sin}B}=\frac {c}{{\sin}C}=4$ ，可得 $a=4{\sin}A,b=4{\sin}B,c=4{\sin}C$ ，
7. 则 $\vartriangle ABC$ 周长 $L=a+b+c=4{\sin}A+4{\sin}B+4{\sin}C=4{\sin}A+4{\sin}B+4{\sin}\left ({A+B}\right )$ ，
8. 由（1）可知： $A=B\in \left ({0,\frac {{\rm{π}}}{2}}\right )$ ，
9. 可得 $L=4{\sin}A+4{\sin}A+4{\sin}2A=8{\sin}A+4{\sin}2A$ ，
10. 构建函数 $f\left ({x}\right )=8{\sin}x+4{\sin}2x,x\in \left ({0,\frac {{\rm{π}}}{2}}\right )$ ，
11. 则 $f^{′}{\left ({x}\right )}=8{\cos}x+8{\cos}2x=8\left ({{\cos}x+1}\right )\left ({2{\cos}x-1}\right )$ ，
12. 因为 $x\in \left ({0,\frac {{\rm{π}}}{{{2}}}}\right )$ ，则 ${\cos}x\in \left ({0,1}\right )$ ，
13. 当 $x\in \left ({0,\frac {{\rm{π}}}{3}}\right )$ 时， ${\cos}x\in \left ({\frac {1}{2},1}\right )$ ，则 $f^{′}{\left ({x}\right )}>0$ ；
14. 当 $x\in \left ({\frac {{\rm{π}}}{3},\frac {{\rm{π}}}{2}}\right )$ 时， ${\cos}x\in \left ({0,\frac {1}{2}}\right )$ ，则 $f^{′}{\left ({x}\right )}<0$ ；
15. 可知 $f\left ({x}\right )$ 在 $\left ({0,\frac {{\rm{π}}}{3}}\right )$ 内单调递增，在 $\left ({\frac {{\rm{π}}}{3},\frac {{\rm{π}}}{2}}\right )$ 内单调递减，
16. 则 $f\left ({x}\right )\leqslant f\left ({\frac {{\rm{π}}}{3}}\right )=6\sqrt {3}$ ，
17. 所以当且仅当 $\vartriangle ABC$ 为等边三角形时， $\vartriangle ABC$ 周长取到最大值 $6\sqrt {3}$ .

## 知识点

**中文**:
  - 三角恒等变换的综合应用
  - 利用导数研究函数的单调性与单调区间
  - 正弦定理及其公式的变形

**English**:
  - Comprehensive Application of Identities
  - Monotonicity and Monotonic Intervals
  - Law of Sines and Formula Transformations

---
