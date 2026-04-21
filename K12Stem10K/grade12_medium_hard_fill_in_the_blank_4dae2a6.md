# Mathematics - 题目 1500

**ID**: 4dae2a6d219f4834a9a81f55efd3544b
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Fill-in-the-blank

## 题目
已知  $f\left ({x}\right )=x{^{2}}-2x+a\left ({{\ln}x-x}\right )$ ，若存在 $x{{}_{0}}\in \left ({0,{\rm{e}}}\right ]$ ，使得 $f\left ({x{{}_{0}}}\right )\leqslant 0$ 成立，则实数 $a$ 的取值范围是.​​​​​​​‌

## 解答

1. 设 $g\left ({x}\right )=x-{\ln}x$ ，则 $g^{′}{\left ({x}\right )}=1-\frac {1}{x}=\frac {x-1}{x}$ ，
2. 从而当 $0<x<1$ 时 $g^{′}{\left ({x}\right )}<0$ ，当 $x>1$ 时 $g^{′}{\left ({x}\right )}>0$ ，
3. 所以 $g\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上单调递减，在 $\left ({1,+\infty }\right )$ 上单调递增，
4. 故对任意 $x>0$ 有 $x-{\ln}x=g\left ({x}\right )\geqslant g\left ({1}\right )=1$ ，即 $x-{\ln}x-1\geqslant 0$ .
5. 一方面，当 $a\geqslant -1$ 时，由于 $f\left ({1}\right )=1-2-a=-1-a\leqslant 0$ ，
6. 因此存在 $x{{}_{0}}=1$ 使得 $f\left ({x{{}_{0}}}\right )\leqslant 0$ 成立；
7. 另一方面，当 $a<-1$ 时，
8. 由于对任意 $x\in \left ({0,{\rm{e}}}\right ]$ 都有
9. $f\left ({x}\right )=x{^{2}}-2x+a\left ({{\ln}x-x}\right )$
10. $={\left({x-1}\right)^{2}}-1+a\left ({{\ln}x-x}\right )$
11. $={\left({x-1}\right)^{2}}+\left ({-a}\right )\left ({x-{\ln}x}\right )-1$
12. $={\left({x-1}\right)^{2}}+\left ({-a}\right )\left ({x-{\ln}x-1}\right )+\left ({-a-1}\right )$
13. $\geqslant 0+0+\left ({-a-1}\right )$ （这里用到 ${\left({x-1}\right)^{2}}\geqslant 0$ ， $-a>0$ ， $x-{\ln}x-1\geqslant 0$ ）
14. $=-a-1>0$ ，
15. 因此对任意 $x\in \left ({0,{\rm{e}}}\right ]$ 都有 $f\left ({x}\right )>0$ .
16. 综上， $a$ 的取值范围是 $\left [{-1,+\infty }\right )$ .
17. 故答案为： $\left [{-1,+\infty }\right )$ .

## 知识点

**中文**:
  - 利用导数解决不等式能成立问题

**English**:
  - Solving Solvable Inequality Problems

---
