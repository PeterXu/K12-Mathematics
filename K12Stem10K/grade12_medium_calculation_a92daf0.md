# Mathematics - 题目 1511

**ID**: a92daf0e354a4b2d87dbb8b0fad1abf1
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
已知函数 $f(x)=a{\rm e}^{x}-x{^{2}}$ .​​​​​​​‌（1）若曲线 $f(x)$ 存在与 $y$ 轴垂直的切线，求 $a$ 的取值范围.（2）当 $a\geqslant 1$ 时，证明： $f(x)\mathrm{\geqslant }1+x-\frac {3}{2}x{^{2}}$ .

## 解答

1. （1）由题可得， $f^{′}(x)=a{\rm e}^{x}-2x=0$ 在 $x\in \mathbf{R}$ 上有解，
2. 则 $a=\frac {2x}{{\rm e}^{x}}$ ，令 $g(x)=\frac {2x}{{\rm e}^{x}}$ ， $g^{′}(x)=\frac {2-2x}{{\rm e}^{x}}$ ，
3. 当 $x<1$ 时， $g^{′}(x)>0,g(x)$ 单调递增；当 $x>1$ 时， $g^{′}(x)<0,g(x)$ 单调递减.
4. 所以 $x=1$ 是 $g(x)$ 的最大值点，所以 $a\mathrm{\leqslant }\frac {2}{e}$ .
5. （2）由 $a\mathrm{\geqslant }1,\therefore a{\rm e}^{x}\mathrm{\geqslant }{\rm e}^{x}$ ，所以 $f(x)\mathrm{\geqslant }{\rm e}^{x}-x{^{2}}$ ，
6. 要证明 $f(x)\mathrm{\geqslant }1+x-\frac {3}{2}x{^{2}}$ ，只需证 ${\rm e}^{x}-x{^{2}}\mathrm{\geqslant }1+x-\frac {3}{2}x{^{2}}$ ，即证 ${\rm e}^{x}+\frac {1}{2}x{^{2}}-x-1\mathrm{\geqslant }0$ .
7. 记 $h(x)={\rm e}^{x}+\frac {1}{2}x{^{2}}-x-1,h^{′}(x)={\rm e}^{x}+x-1,h^{′}(x)$ 在 $\mathbf{R}$ 上单调递增，且 $h^{′}(0)=0$ ，
8. 当 $x<0$ 时， $h{^{\prime }}(x)<0,h(x)$ 单调递减；当 $x>0$ 时， $h{^{\prime }}(x)>0,h(x)$ 单调递增.
9. 所以 $x=0$ 是 $h(x)$ 的最小值点， $h(x)\mathrm{\geqslant }h(0)=0$ ，则 ${\rm e}^{x}+\frac {1}{2}x{^{2}}-x-1\mathrm{\geqslant }0$ ，
10. 故 $f(x)\mathrm{\geqslant }1+x-\frac {3}{2}x{^{2}}$ .

## 知识点

**中文**:
  - 利用导数证明不等式
  - 导数几何意义的应用

**English**:
  - Proving Inequalities using Derivatives
  - Applications of Geometric Meaning of Derivatives

---
