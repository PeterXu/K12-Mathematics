# Mathematics - 题目 3517

**ID**: 7cc2a14bfa324606b9d1a0a75c34ae5b
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
对于定义在 ${\mathbf{R}}$ 上的函数 $y=f\left ({x}\right )$ 和 $y=g\left ({x}\right )$ ， $a\in {\mathbf{R}}$ ，设 $M{{}_{a}}=\left \{t\left |{t=f\left ({x}\right )-g\left ({a}\right ),x\geqslant a}\right .​​​​​​​‌\right \}$ .(1)若 $f\left ({x}\right )=2{^{x}}-1$ ， $g\left ({x}\right )={\rm{c}}{\rm{o}}{\rm{s}}x$ ，求 $M{{}_{0}}$ ；(2)若 $f\left ({x}\right )=x{^{3}}-3x{^{2}}$ ， $g\left ({x}\right )=-x$ ， $M{{}_{a}}\subseteq \left [{0,+\infty }\right )$ ，求实数 $a$ 的取值范围；(3)已知对任意 $a\in {\mathbf{R}}$ ，均有 $M{{}_{a}}=\left [{0,+\infty }\right )$ ，记 $h\left ({x}\right )=g\left ({x}\right )-a$ ，求证：“对任意 $a\in {\mathbf{R}}$ ，函数 $y=h\left ({x}\right )$ 零点个数均有限”的充要条件是“ $y=f\left ({x}\right )$ 在 ${\mathbf{R}}$ 上是严格增函数”.

## 解答

1. （1）记 $F(x)=f(x)-g(0)=2{^{x}}-1-{\cos}0=2{^{x}}-2$ ，
2. 函数 $y=F(x),x\geqslant 0$ 上的值域为 $[-1,+\infty )$ ，即 $M{{}_{0}}=[-1,+\infty )$ ．
3. （2）设 $G(x)=f(x)-g(a)=x{^{3}}-3x{^{2}}+a$ 在 $x\in [a,+\infty )$ 上的最小值 $G{{}_{{\rm \min }}}\geqslant 0$ ．
4. $G^{′}(x)=3x{^{2}}-6x=3x(x-2)$ .
5. 当 $x\in (-\infty ,0)$ 时， $G{^{\prime }}(x)>0,G(x)$ 严格增；当 $x\in (0,2)$ 时， $G{^{\prime }}(x)<0,G(x)$ 严格减；
6. 当 $x\in (2,+\infty )$ 时， $G{^{\prime }}(x)>0,G(x)$ 严格增．当 $x=2$ 时 $G(x)$ 取得极小值．
7. 当 $a\leqslant 2$ 时， $\left \{\hspace{-0.5em}\begin{array}{l}G(a)\geqslant 0\\G(2)\geqslant 0\end{array}\hspace{-0.5em}\Rightarrow \left \{\hspace{-0.5em}\begin{array}{l}a{^{3}}-3a{^{2}}+a\geqslant 0\\-4+a\geqslant 0\end{array}\hspace{-0.5em}\Rightarrow \left \{\hspace{-0.5em}\begin{array}{l}a\left ({a{^{2}}-3a+1}\right )\geqslant 0,\\a\geqslant 4,\end{array}\hspace{-0.5em}\right.\right.\right.$ 舍去．
8. 当 $a>2$ 时， $G(a)\geqslant 0\Rightarrow a\left ({a{^{2}}-3a+1}\right )\geqslant 0,a\geqslant \frac {3+\sqrt {5}}{2}$ ．
9. 综上， $a\geqslant \frac {3+\sqrt {5}}{2}$ ．
10. （3）（充分性）若 $y=f(x)$ 是严格增函数，
11. 则 $y=f(x)-g(a),x\geqslant a$ 的最小值为 $f(a)-g(a)$ ，而 $M{{}_{a}}=[0,+\infty )$ ，
12. 故对任意 $a\in {\mathbf{R}}$ ，都有 $f(a)=g(a)$ ，即 $y=g(x)$ 与 $y=f(x)$ 是相同函数．
13. 故 $y=g(x)$ 是严格增函数，所以 $y=h(x)$ 严格增函数，故对任意 $a\in {\mathbf{R}},h(x)=g(x)-a$ 的零点个数有限．
14. （必要性）对任意 $a\in {\mathbf{R}}$ ，都有 $M{{}_{a}}=[0,+\infty )$ ，故 $y=f(x),x\geqslant a$ 的值域为 $[g(a),+\infty )$ ，
15. 即 $y=f(x)$ 在 $x\in [a,+\infty )$ 上的最小值为 $g(a)$ ．
16. 先证 $y=g(x)$ 是严格增函数．
17. 对任意 $a{{}_{1}}<a{{}_{2}}$ ，函数 $y=f(x),x\geqslant a{{}_{1}}$ 和 $y=f(x),x\geqslant a{{}_{2}}$ 的最小值分别为 $g\left ({a{{}_{1}}}\right )$ 和 $g\left ({a{{}_{2}}}\right )$ ，
18. 则由最小值的定义， $g\left ({a{{}_{1}}}\right )\leqslant g\left ({a{{}_{2}}}\right )$ ，故函数 $y=g(x)$ 是增函数．
19. 假设存在 $a{{}_{1}}<a{{}_{2}}$ ，使得 $g\left ({a{{}_{1}}}\right )=g\left ({a{{}_{2}}}\right )$ ，则对任意 $x\in \left [a{{}_{1}},a{{}_{2}}\right ]$ ，均有 $g\left ({a{{}_{1}}}\right )\leqslant g(x)\leqslant g\left ({a{{}_{2}}}\right )$ ，
20. 从而方程 $g(x)=g\left ({a{{}_{2}}}\right )$ 的解有无限多个，与条件＂对任意 $a\in {\mathbf{R}}$ ，函数 $y=h(x)$ 零点个数均有限＂矛盾．
21. 故假设不成立，从而 $y=g(x)$ 是严格增函数．
22. 再证对任意 $a\in {\mathbf{R}}$ ，函数 $y=f(x),x\geqslant a$ 的最小值为 $f(a)$ ．
23. 假设存在 $x{{}_{0}}>a$ 使得 $f\left ({x{{}_{0}}}\right )=g(a)$ ，取 $c\in \left ({a,x{{}_{0}}}\right )$ ，则 $y=f(x),x\geqslant c$ 的最小值为 $g(c)$ ．
24. 由于 $y=g(x)$ 严格增，知 $g(c)>g(a)$ ．而 $x{{}_{0}}\in [c,+\infty )$ ，故 $f\left ({x{{}_{0}}}\right )\geqslant g(c)>g(a)$ ，矛盾．
25. 所以假设不成立，对任意 $a\in {\mathbf{R}}$ ，函数 $y=f(x),x\geqslant a$ 的最小值为 $f(a)$ ．
26. 另证：再证对任意 $a\in {\mathbf{R}}$ ，函数 $y=f(x),x\geqslant a$ 的最小值为 $f(a)$ ．
27. $f(a)\geqslant g(a)$ ．假设 $f(a)>g(a)$ ，则由 $y=f(x)$ 在 $x\in [a,+\infty )$ 上的最小值为 $g(a)$ ，
28. 存在 $x{{}_{0}}>a$ 使得 $f\left ({x{{}_{0}}}\right )=g(a)$ ，故 $y=f(x)$ 在 $x\in \left [{x{{}_{0}},+\infty }\right )$ 上的最小值为 $g(a)$ ．
29. 取 $c\in \left ({a,x{{}_{0}}}\right )$ ，则 $y=f(x)$ 在 $x\in [c,+\infty )$ 上的最小值为 $g(c)$ ，
30. 故 $g(a)=g(c)$ ．但由 $y=g(x)$ 为严格增函数，知 $g(c)>g(a)$ ，矛盾．
31. 所以假设不成立，所以 $f(a)=g(a)$ ．
32. 即对任意 $a\in {\mathbf{R}}$ ，函数 $y=f(x),x\geqslant a$ 的最小值为 $f(a)$ ．
33. 而对任意 $a\in {\mathbf{R}},y=f(x),x\geqslant a$ 的值域为 $[g(a),+\infty )$ ，故 $f(a)=g(a)$ ．
34. 于是 $y=g(x)$ 与 $y=f(x)$ 是相同函数，所以 $y=f(x)$ 是严格增函数．

## 知识点

**中文**:
  - 充要条件
  - 指数函数的值域
  - 函数零点的概念
  - 利用导数研究函数的最值

**English**:
  - Necessary and Sufficient Condition
  - Range of Exponential Functions
  - Concept of Zero Points
  - Global Extrema (Max/Min) using Derivatives

---
