# Mathematics - 题目 1267

**ID**: 70116295e3184fb680b1dd5d30c3f97c
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Fill-in-the-blank

## 题目
定义:  ${\rm{m}}{\rm{a}}{\rm{x}}A，{\rm{m}}{\rm{i}}{\rm{n}}A$  分别表示数集 $\mathrm{A}$ 中的最大数、最小数.​​​​​​​‌ 已知  $x{{}_{1}}，x{{}_{2}}，x{{}_{3}}，\cdots ，x{{}_{2n}}$ 为 $1，2，3，\cdots ，2n\left ({n\in {\mathbf{N}}{^{{\rm{*}}}}}\right )$  的任意排列，设  $X={\rm{m}}{\rm{i}}{\rm{n}}\left \{{\rm{m}}{\rm{a}}{\rm{x}}\left \{x{{}_{1}},x{{}_{2}},x{{}_{3}},\cdots ,x{{}_{n}}\right \},{\rm{m}}{\rm{a}}{\rm{x}}\left \{x{{}_{n+1}},x{{}_{n+2}},x{{}_{n+3}},\cdots ,x{{}_{2n}}\right \}\right \}$ ，  $Y={\rm{m}}{\rm{a}}{\rm{x}}\left \{{\rm{m}}{\rm{i}}{\rm{n}}\left \{x{{}_{1}},x{{}_{2}},x{{}_{3}},\cdots ,x{{}_{n}}\right \},{\rm{m}}{\rm{i}}{\rm{n}}\left \{x{{}_{n+1}},x{{}_{n+2}},x{{}_{n+3}},\cdots ,x{{}_{2n}}\right \}\right \}$   ，则  $\mathrm{X}>\mathrm{Y}$  的概率为. （用含  $n$  的式子表示）

## 解答

1. $x{{}_{1}}，x{{}_{2}}，x{{}_{3}}，\ldots ，x{{}_{2n}}\left ({n\in {\mathbf{N}}{^{*}}}\right )$ 的任意排列共有 $(2n)!$ 种情况，其中： $n\leqslant X\leqslant 2n-1，2\leqslant Y\leqslant n+1$ ；
2. 考虑 $X\leqslant Y$ 的情况：①当 $X=n$ ， $Y=n$ 时，此情况不存在；
3. ②当 $X=n$ ， $Y=n+1$ 时， $X<Y\,，\,\,x{{}_{1}}{\rm{,}}x{{}_{2}}{\rm{,}}x{{}_{3}},\cdots ,x{{}_{n}}$ 为1，2，3，…，n的任意一个排列，共有n!种情况， $x{{}_{n+1}}，x{{}_{n+2}}，x{{}_{n+3}}，…，x{{}_{2n}}$ 为 $n+1，n+2，n+3，…，2n$ 的任意一个排列，共有n!种情况，所以 $P(X<Y)=\frac {2\times n!\times n!}{(2n)!}=\frac {2}{{\rm{C}}{{}_{2n}^{n}}}$ ；
4. ③当 $X=n+1$ ， $Y=n+1$ 时，此情况不存在；
5. 所以 $P(X>Y)=1-P(X\leqslant Y)=1-\frac {2\times n!\times n!}{(2n)!}=1-\frac {2}{{\rm{C}}{{}_{2n}^{n}}}$ ．

## 知识点

**中文**:
  - 互斥事件

**English**:
  - Mutually Exclusive Events

---
