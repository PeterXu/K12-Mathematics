# Mathematics - 题目 1686

**ID**: 58267fd0715e42f98181994149ae73b9
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Multiple-choice

## 题目
若存在一实数 $a$ ，使得对于任意实数 $x$ 和任意 $θ\in \left [0,\frac {{\rm{π}}}{2}\right ]$ 恒有 ${\left({x+3+2\sin θ{\cos}θ}\right)^{2}}+{\left({x+a\sin θ+a{\cos}θ}\right)^{2}}\mathrm{\geqslant }\frac {1}{8}$ ，则 $a$ 的取值范围是（      ）​​​​​​​‌

## 解答

1. 先给出公式： $2\left ({a{^{2}}+b{^{2}}}\right )\geqslant {\left({a-b}\right)^{2}}$ ，等号成立条件为 $a=-b$ ，证明如下：
2. $2\left ({a{^{2}}+b{^{2}}}\right )-{\left({a-b}\right)^{2}}=2a{^{2}}+2b{^{2}}-\left ({a{^{2}}+b{^{2}}-2ab}\right ){\rm{=}}a{^{2}}+b{^{2}}{{+}}2ab={\left({a+b}\right)^{2}}\geqslant 0$ ，
3. 等号成立时 $a=-b$ ，
4. 则 $\left ({a{^{2}}+b{^{2}}}\right )\geqslant \frac {{\left({a-b}\right)^{2}}}{2}$ ，等号成立条件为 $a=-b$ ；
5. 则 ${\left({x+3+2\sin θ{\cos}θ}\right)^{2}}+{\left({x+a\sin θ+a{\cos}θ}\right)^{2}}$
6. $\geqslant \frac {\left [\left ({x+3+2\sin θ{\cos}θ}\right )-\left ({x+a\sin θ+a{\cos}θ}\right )\right ]{^{2}}}{2}$
7. $=\frac {\left [\left ({3+2\sin θ{\cos}θ}\right )-\left ({a\sin θ+a{\cos}θ}\right )\right ]{^{2}}}{2}$
8. 等号成立条件为 $x=-\frac {3+2\sin θ{\cos}θ+a\sin θ+a{\cos}θ}{2}$ ，
9. 因 ${\left({x+3+2\sin θ{\cos}θ}\right)^{2}}+{\left({x+a\sin θ+a{\cos}θ}\right)^{2}}\geqslant \frac {1}{8}$ 对任意 $x\in {\rm{R}}$ 恒成立，
10. 则 $\frac {\left [\left ({3+2\sin θ{\cos}θ}\right )-\left ({a\sin θ+a{\cos}θ}\right )\right ]{^{2}}}{2}\geqslant \frac {1}{8}$ ，
11. 即 $\left [3+2\sin θ{\cos}θ-a\left ({\sin θ+{\cos}θ}\right )\right ]{^{2}}\geqslant \frac {1}{4}$ 对任意 $θ\in \left [0,\frac {{\rm{π}}}{2}\right ]$ 恒成立，
12. 令 $t=\sin θ+{\cos}θ=\sqrt {2}\sin \left ({θ+\frac {{\rm{π}}}{4}}\right )$ ，
13. 因 $θ\in \left [0,\frac {{\rm{π}}}{2}\right ]$ ，则 $θ+\frac {{\rm{π}}}{4}\in \left [\frac {{\rm{π}}}{4},\frac {{{3}}{\rm{π}}}{4}\right ]$ ，则 $\sin \left ({θ+\frac {{\rm{π}}}{4}}\right )\in \left [\frac {\sqrt {2}}{2},1\right ]$ ，则 $t\in \left [1,\sqrt {2}\right ]$ ，
14. 因 $t{^{2}}={\left({\sin θ+{\cos}θ}\right)^{2}}=1+2\sin θ{\cos}θ$ ，则 $2\sin θ{\cos}θ=t{^{2}}-1$ ，
15. 则 ${\left({t{^{2}}-at+2}\right)^{2}}\geqslant \frac {1}{4}$ 对任意 $t\in \left [1,\sqrt {2}\right ]$ 恒成立，
16. 则 $t{^{2}}-at+2\geqslant \frac {1}{2}$ 或 $t{^{2}}-at+2\leqslant -\frac {1}{2}$ ，
17. 即 $a\leqslant t+\frac {3}{2t}$ 或 $a\geqslant t+\frac {5}{2t}$ 对任意 $t\in \left [1,\sqrt {2}\right ]$ 恒成立，
18. 因 $t+\frac {3}{2t}\geqslant 2\sqrt {t\cdot \frac {3}{2t}}=\sqrt {6}$ ，等号成立条件为 $t=\frac {3}{2t}$ ，即 $t=\frac {\sqrt {6}}{2}$ ，则 $a\leqslant \left ({t+\frac {3}{2t}}\right ){{}_{{\rm \min }}}=\sqrt {6}$ ，
19. 因对勾函数 $y=t+\frac {5}{2t}$ 在 $\left [1,\sqrt {2}\right ]$ 上单调递减，则 $y{{}_{{\rm \max }}}=1+\frac {5}{2}=\frac {7}{2}$ ，
20. 则 $a\geqslant \left ({t+\frac {5}{2t}}\right ){{}_{{\rm \max }}}=\frac {7}{2}$ ，
21. 则 $a\leqslant \sqrt {6}$ 或 $a\geqslant \frac {7}{2}$ ，
22. 综上所述， $a$ 的取值范围是 $\left ({-∞,\sqrt {6}}\right ]\cup \left [{\frac {7}{2},+∞}\right )$ .
23. 故选A

## 知识点

**中文**:
  - 一元二次不等式恒成立问题与有解问题

**English**:
  - Universally True and Solvable Problems

---
