# Mathematics - 题目 3420

**ID**: d7eb9315dccf47d08a7d1fe54caa955f
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Fill-in-the-blank

## 题目
若函数 $f(x)=\frac {x}{{\rm{e}}{^{ax}}}-ax-1+{\ln}x$ 有两个不同的零点，则实数 $a$ 的取值范围是.​​​​​​​‌

## 解答

1. 函数 $f(x)=x{\rm{e}}{^{-ax}}-ax+{\ln}x-1={\rm{e}}{^{-ax+{\ln}x}}-ax+{\ln}x-1$ ，令 $t=-ax+{\ln}x$ ，
2. 则 $h(t)={\rm{e}}{^{t}}+t-1$ ，显然函数 $h(t)$ 在R上单调递增，而 $h(0)=0$ ，
3. 由 $f(x)=0$ ，得 $h(t)=0$ ，于是 $t=0$ ，即 $-ax+{\ln}x=0\Leftrightarrow a=\frac {{\ln}x}{x}$ ，令 $g(x)=\frac {{\ln}x}{x}$ ，
4. 依题意，函数 $f(x)$ 有两个不同零点，即方程 $a=\frac {{\ln}x}{x}$ 有两个不等的正根，
5. 亦即直线 $y=a$ 与函数 $y=g(x)$ 的图象有两个公共点，由 $g(x)=\frac {{\ln}x}{x}$ ，求导得 $g^{′}(x)=\frac {1-{\ln}x}{x{^{2}}}$ ，
6. 当 $0<x<{\rm{e}}$ 时， $g^{′}(x)>0$ ，当 $x>{\rm{e}}$ 时， $g^{′}(x)<0$ ，函数 $g(x)$ 在 $(0,{\rm{e}})$ 上递增，在 $({\rm{e}},+\infty )$ 上递减，
7. 因此 $g(x){{}_{{\rm \max }}}=g({\rm{e}})=\frac {1}{{\rm{e}}}$ ，且 $g(1)=0$ ，当 $x>{\rm{e}}$ 时， $g(x)>0$ 恒成立，
8. 从而当 $0<a<\frac {1}{{\rm{e}}}$ 时，直线 $y=a$ 与函数 $y=g(x)$ 的图象有两个公共点，
9. 所以实数 $a$ 的取值范围是 $(0,\frac {1}{{\rm{e}}})$ .

## 知识点

**中文**:
  - 利用导数解决函数零点问题

**English**:
  - Solving Zero Point Problems

---
