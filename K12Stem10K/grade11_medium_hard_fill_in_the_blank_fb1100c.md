# Mathematics - 题目 2960

**ID**: fb1100c246ff451bbce2b3cdfe3afc68
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Fill-in-the-blank

## 题目
已知函数 $f\left ({x}\right )=\begin{cases}{\rm{e}}{^{x}}-kx,x\geqslant 0\\kx{^{2}}-x+1,x<0\end{cases}$ ，若 $k=0$ ，则不等式 $f(x)<2$ 的解集为；​​​​​​​‌若 $f(x)$ 恰有两个零点，则 $k$ 的取值范围为．

## 解答

1. 第一空：若 $k=0$ ，则 $f\left ({x}\right )=\begin{cases}{\rm{e}}{^{x}},x\geqslant 0\\-x+1,x<0\end{cases}$ ，当 $x\geqslant 0$ 时，由 ${\rm{e}}{^{x}}<2$ 解得 $x<{\ln}2$ ，则 $0\leqslant x<{\ln}2$ ；
2. 当 $x<0$ 时，由 $-x+1<2$ ，解得 $x>-1$ ，则 $-1<x<0$ ；综上可得不等式 $f(x)<2$ 的解集为 $\left ({-1,{\ln}2}\right )$ ；
3. 第二空： $f(x)$ 恰有两个零点等价于 ${\rm{e}}{^{x}}=kx(x\geqslant 0)$ 和 $kx{^{2}}-x+1=0(x<0)$ 的实数根的个数为2.
4. 当 $k=0$ 时， ${\rm{e}}{^{x}}=0$ 显然无解； $-x+1=0(x<0)$ 解得 $x=1$ （舍去），也无解，不合题意；
5. 当 $k<0$ 时， ${\rm{e}}{^{x}}=kx\leqslant 0$ 显然无解； $kx{^{2}}-x+1=0(x<0)$ 的判别式 $\Delta =1-4k>0$ ，设 $kx{^{2}}-x+1=0$ 的两根为 $x{{}_{1}},x{{}_{2}}$ ，
6. 则 $x{{}_{1}}+x{{}_{2}}=\frac {1}{k}<0,x{{}_{1}}x{{}_{2}}=\frac {1}{k}<0$ ，显然两根一正一负，即 $kx{^{2}}-x+1=0(x<0)$ 有1个实根，不合题意；
7. 当 $k>0$ 时，令 $g\left ({x}\right )=kx{^{2}}-x+1(x<0)$ 的对称轴为 $x=\frac {1}{2k}>0$ ，则 $g\left ({x}\right )$ 在 $\left ({-\infty ,0}\right )$ 单减，则 $g\left ({x}\right )>g\left ({0}\right )=1$ ，则 $kx{^{2}}-x+1=0(x<0)$ 无解；
8. ${\rm{e}}{^{x}}=kx(x\geqslant 0)$ ，显然 $x=0$ 时不成立，则 $k=\frac {{\rm{e}}{^{x}}}{x}(x>0)$ ，令 $h\left ({x}\right )=\frac {{\rm e}{^{x}}}{x}$ ，则 $h^{′}{\left ({x}\right )}=\frac {{\rm e}{^{x}}\left ({x-1}\right )}{x{^{2}}}$ ，显然 $h\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上单减，在 $\left ({1,+\infty }\right )$ 单增，
9. 则 $h\left ({x}\right )\geqslant h\left ({1}\right )={\rm{e}}$ ，又 $x\to 0,h\left ({x}\right )\to +\infty $ ， $x\to +\infty ,h\left ({x}\right )\to +\infty $ ，则 $k>{\rm e}$ 时， $k=\frac {{\rm{e}}{^{x}}}{x}(x>0)$ 有2个根，即 $f(x)$ 恰有两个零点；
10. 综上： $k\in \left ({{\rm{e}}{\rm{,}}{{+}}\infty }\right )$ .

## 知识点

**中文**:
  - 函数零点的存在性定理及应用
  - 利用导数解决函数零点问题

**English**:
  - Existence Theorem of Zero Points and Applications
  - Solving Zero Point Problems

---
