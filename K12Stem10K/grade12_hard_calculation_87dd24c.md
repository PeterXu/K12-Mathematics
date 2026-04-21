# Mathematics - 题目 662

**ID**: 87dd24c07a8d44908519654bdeaaeea9
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $g\left ({x}\right )=2{\rm{l}}{\rm{n}}\left ({-x-1}\right )+{\rm{c}}{\rm{o}}{\rm{s}}\left ({-x-2}\right )$ .​​​​​​​‌(1)函数 $f\left ({x}\right )$ 与 $g\left ({x}\right )$ 的图象关于 $x=-1$ 对称，求 $f\left ({x}\right )$ 的解析式；(2) $f\left ({x}\right )-1\leqslant ax$ 在定义域内恒成立，求 $a$ 的值；(3)求证： $\sum\limits_{k=n+1}^{2n}\mathop{}f\left ({\frac {1}{k}-\frac {1}{2}}\right )<{\rm{l}}{\rm{n}}4$ ， $n\in {\mathbf{N}}{^{{\rm{*}}}}$ .

## 解答

1. （1）解：依题意，设 $f\left ({x}\right )$ 图象上任意一点的坐标为，
2. 则其关于 $x=-1$ 对称的点 $\left ({-2-x{{}_{0}},y{{}_{0}}}\right )$ 在 $g\left ({x}\right )$ 的图象上，
3. 则 $y{{}_{0}}=f\left ({x{{}_{0}}}\right )=g\left ({-2-x{{}_{0}}}\right )$ ，
4. 则 $f\left ({x{{}_{0}}}\right )=g\left ({-x{{}_{0}}-2}\right )=2{\rm{l}}{\rm{n}}\left ({x{{}_{0}}+1}\right )+{\rm{c}}{\rm{o}}{\rm{s}}x{{}_{0}}$  $\left ({x{{}_{0}}>-1}\right )$ ，
5. 故 $f\left ({x}\right )=2{\rm{l}}{\rm{n}}\left ({x+1}\right )+{\rm{c}}{\rm{o}}{\rm{s}}x$  $(x>-1)$ .
6. （2）解：令 $h\left ({x}\right )=f\left ({x}\right )-1-ax=2{\rm{l}}{\rm{n}}\left ({x+1}\right )+{\rm{c}}{\rm{o}}{\rm{s}}x-1-ax$  $(x>-1)$ ，
7. 则 $h\left ({x}\right )\leqslant 0$ 在 $x\in \left ({-1,+\infty }\right )$ 上恒成立，又 $h\left ({0}\right )=0$ ，
8. 且 $h\left ({x}\right )$ 在 $x\in \left ({-1,+\infty }\right )$ 上是连续函数，则 $x=0$ 为 $h\left ({x}\right )$ 的一个极大值点，
9. $h^{′}{\left ({x}\right )}=\frac {2}{x+1}-{\rm{s}}{\rm{i}}{\rm{n}}x-a$ ， $h^{′}{\left ({0}\right )}=2-a=0\Rightarrow a=2$ ，
10. 下证当 $a=2$ 时， $h\left ({x}\right )\leqslant 0$ 在 $x\in \left ({-1,+\infty }\right )$ 上恒成立.
11. 令 $φ\left ({x}\right )={\rm{l}}{\rm{n}}\left ({x+1}\right )-x$ ，则 $φ^{′}{\left ({x}\right )}=\frac {1}{x+1}-1=-\frac {x}{x+1}$ ，
12. 当 $x\in \left ({-1,0}\right )$ ， $φ^{′}{\left ({x}\right )}>0$ ， $φ\left ({x}\right )$ 在 $\left ({-1,0}\right )$ 上单调递增，
13. 当 $x\in \left ({0,+∞}\right )$ ， $φ^{′}{\left ({x}\right )}<0$ ， $φ\left ({x}\right )$ 在 $\left ({0,+\infty }\right )$ 上单调递减，
14. 故 $φ\left ({x}\right )\leqslant φ\left ({0}\right )=0$ ， ${\rm{l}}{\rm{n}}\left ({x+1}\right )\leqslant x$ 在 $\left ({-1,+\infty }\right )$ 上恒成立，又 ${\rm{c}}{\rm{o}}{\rm{s}}x\leqslant 1$ ，
15. 则 $a=2$ 时， $h\left ({x}\right )=f\left ({x}\right )-1-ax=2\left [{\rm{l}}{\rm{n}}\left ({x+1}\right )-x\right ]+\left ({{\rm{c}}{\rm{o}}{\rm{s}}x-1}\right )\leqslant 0$ 恒成立，
16. 综上， $a=2$ .
17. （3）证明：由（2）可知 $f\left ({x}\right )-1\leqslant 2x$ ，则 $f\left ({\frac {1}{k}-\frac {1}{2}}\right )-1\leqslant 2\left ({\frac {1}{k}-\frac {1}{2}}\right )$ ，即 $f\left ({\frac {1}{k}-\frac {1}{2}}\right )\leqslant \frac {2}{k}$ ，
18. 则.
19. 又由（2）可知 ${\rm{l}}{\rm{n}}\left ({x+1}\right )\leqslant x$ 在 $\left ({-1,+\infty }\right )$ 上恒成立，
20. 则 ${\rm{l}}{\rm{n}}x\leqslant x-1$ 在 $\left ({0,+\infty }\right )$ 上恒成立,当且仅当 $x=1$ 时取等，
21. 令 $x=\frac {n}{n+1}$  $\in \left ({0,1}\right )$ ， $n\in {\mathbf{N}}{^{{\rm{*}}}}$ ，则 ${\rm{l}}{\rm{n}}\frac {n}{n+1}<\frac {n}{n+1}-1=\frac {-1}{n+1}$ ，
22. 即 $\frac {1}{n+1}<-{\rm{l}}{\rm{n}}\frac {n}{n+1}={\rm{l}}{\rm{n}}\frac {n+1}{n}={\rm{l}}{\rm{n}}\left ({n+1}\right )-{\rm{l}}{\rm{n}}n$ ，
23. 则 $\frac {1}{n+1}+\frac {1}{n+2}+\cdots +\frac {1}{2n}<{\rm{l}}{\rm{n}}\left ({n+1}\right )-{\rm{l}}{\rm{n}}n+{\rm{l}}{\rm{n}}\left ({n+2}\right )-{\rm{l}}{\rm{n}}\left ({n+1}\right )$
24. $+\cdots +{\rm{l}}{\rm{n}}\left ({2n}\right )-{\rm{l}}{\rm{n}}\left ({2n-1}\right )$  $={\rm{l}}{\rm{n}}\left ({2n}\right )-{\rm{l}}{\rm{n}}n={\rm{l}}{\rm{n}}2$ ，
25. 综上， $\sum\limits_{k=n+1}^{2n}\mathop{}f\left ({\frac {1}{k}-\frac {1}{2}}\right )<2{\rm{l}}{\rm{n}}2={\rm{l}}{\rm{n}}4$ ，得证.

## 知识点

**中文**:
  - 函数对称性
  - 利用导数证明不等式
  - 利用导数解决不等式恒成立问题

**English**:
  - Symmetry of Functions
  - Proving Inequalities using Derivatives
  - Solving Universally True Inequalities

---
