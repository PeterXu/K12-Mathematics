# Mathematics - 题目 2517

**ID**: 5bc9643746784e9d89d35da655e426e4
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Fill-in-the-blank

## 题目
知识卡片：一般地，如果 $f(x)$ 是区间 $[a,b]$ 上的连续函数，并且 $F^{′}(x)=f(x){\rm ，}$ 那么 $\int _{a}^{b}\mathop{}f(x){\rm{d}}x=\left .​​​​​​​‌{F(x)}\right |{{}_{a}^{b}}=F(b)-F(a)$ .这个结论叫做微积分基本定理，又叫做牛顿—莱布尼茨公式.当 $x\in {\mathbf{R}}{\rm ，}$  $|x|<1$ 时，有如下表达式： $1+x+x{^{2}}+\cdots +x{^{n}}+\cdots =\frac {1}{1-x}{\rm ，}$ 两边同时积分得： $\int _{0}^{\frac {1}{2}}\mathop{1}{\rm{d}}x+\int _{0}^{\frac {1}{2}}\mathop{x}{\rm{d}}x+\int _{0}^{\frac {1}{2}}\mathop{x{^{2}}}{\rm{d}}x+\cdots +\int _{0}^{\frac {1}{2}}\mathop{x{^{n}}}{\rm{d}}x+\cdots =\int _{0}^{\frac {1}{2}}\mathop{\frac {1}{1-x}}{\rm{d}}x{\rm ，}$ 从而得到如下等式： $1\times \frac {1}{2}+\frac {1}{2}\times {\left({\frac {1}{2}}\right)^{2}}+\frac {1}{3}\times {\left({\frac {1}{2}}\right)^{3}}+\cdots +\frac {1}{n+1}\times {\left({\frac {1}{2}}\right)^{n+1}}+\cdots ={\ln}2$ 请根据以上材料所蕴含的数学思想方法，由二项式定理 ${\rm{C}}{{}_{n}^{0}}+{\rm{C}}{{}_{n}^{1}}x+{\rm{C}}{{}_{n}^{2}}x{^{2}}+\cdots +{\rm{C}}{{}_{n}^{n}}x{^{n}}=(1+x){^{n}}$ 计算： ${\rm{C}}{{}_{n}^{0}}\times \frac {1}{2}+\frac {1}{2}{\rm{C}}{{}_{n}^{1}}\times {\left({\frac {1}{2}}\right)^{2}}+\frac {1}{3}{\rm{C}}{{}_{n}^{2}}\times {\left({\frac {1}{2}}\right)^{3}}+\cdots +\frac {1}{n+1}{\rm{C}}{{}_{n}^{n}}\times {\left({\frac {1}{2}}\right)^{n+1}}=$.

## 解答

1. 因为 ${\rm{C}}{{}_{n}^{{{0}}}}x{^{0}}+{\rm{C}}{{}_{n}^{{{1}}}}x{^{1}}+{\rm{C}}{{}_{n}^{{{2}}}}x{^{2}}+{\rm{C}}{{}_{n}^{{{3}}}}x{^{3}}+\cdots +{\rm{C}}{{}_{n}^{n}}x{^{n}}={\left({1+x}\right)^{n}}{\rm ，}$
2. 且 $\int _{0}^{\frac {1}{2}}\mathop{}{\rm{C}}{{}_{n}^{n}}x{^{n}}{\rm{d}}x=\frac {1}{n+1}{\rm{C}}{{}_{n}^{n}}x{^{n+1}}|{{}_{0}^{\frac {1}{2}}}=\frac {1}{n+1}{\rm{C}}{{}_{n}^{n}}{\left({\frac {1}{2}}\right)^{n+1}}-0=\frac {1}{n+1}{\rm{C}}{{}_{n}^{n}}{\left({\frac {1}{2}}\right)^{n+1}}{\rm ，}$
3. 所以 ${\rm{C}}{{}_{n}^{{{0}}}}\times \frac {1}{2}+\frac {1}{2}{\rm{C}}{{}_{n}^{{{1}}}}\times {\left({\frac {1}{2}}\right)^{2}}+\frac {1}{3}{\rm{C}}{{}_{n}^{{{2}}}}\times {\left({\frac {1}{2}}\right)^{3}}+\cdots +\frac {1}{n+1}{\rm{C}}{{}_{n}^{n}}\times {\left({\frac {1}{2}}\right)^{n+1}}$
4. ${\rm{=}}\int _{0}^{\frac {1}{2}}\mathop{{\rm{C}}{{}_{n}^{{{0}}}}x{^{0}}{\rm{d}}x}+\int _{0}^{\frac {1}{2}}\mathop{{\rm{C}}{{}_{n}^{1}}x{^{1}}{\rm{d}}x}+\int _{0}^{\frac {1}{2}}\mathop{{\rm{C}}{{}_{n}^{2}}x{^{2}}{\rm{d}}x}+\cdots +\int _{0}^{\frac {1}{2}}\mathop{{\rm{C}}{{}_{n}^{n}}x{^{n}}{\rm{d}}x}$ ；
5. $=\int _{0}^{\frac {1}{2}}\mathop{}(1+x){^{n}}{\rm{d}}x=\frac {1}{n+1}{\left({1+x}\right)^{n+1}}\left |{\hspace{-0.5em}\begin{array}{}\frac {1}{2}\\0\end{array}\hspace{-0.5em}}\right .=\frac {1}{n+1}\left [{\left({\frac {3}{2}}\right)^{n+1}}-1\right ]{\rm ，}$
6. 所以 ${\rm{C}}{{}_{n}^{0}}\times \frac {1}{2}+\frac {1}{2}{\rm{C}}{{}_{n}^{1}}\times {\left({\frac {1}{2}}\right)^{2}}+\frac {1}{3}{\rm{C}}{{}_{n}^{2}}\times {\left({\frac {1}{2}}\right)^{3}}+\cdots +\frac {1}{n+1}{\rm{C}}{{}_{n}^{n}}\times {\left({\frac {1}{2}}\right)^{n+1}}=\frac {1}{n+1}\left [{\left({\frac {3}{2}}\right)^{n+1}}-1\right ]$ .
7. 故答案为： $\frac {1}{n+1}\left [{\left({\frac {3}{2}}\right)^{n+1}}-1\right ]$

## 知识点

**中文**:
  - 二项展开式中各项的系数和

**English**:
  - Sum of Coefficients

---
