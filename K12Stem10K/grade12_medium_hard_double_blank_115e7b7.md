# Mathematics - 题目 1681

**ID**: 115e7b7be31e4a4bbeb04b53d8516549
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: 双空题

## 题目
已知平面向量 $\overrightarrow {{a}},\overrightarrow {{b}},\overrightarrow {{c}}$ ， $\left |{\overrightarrow {{a}}}\right |=2,\left |{\overrightarrow {{b}}}\right |=3,\left |{\overrightarrow {{c}}}\right |=4,\overrightarrow {{a}}\cdot \overrightarrow {{b}}=\frac {3}{2}$ ，则 $\left |{\overrightarrow {{a}}\cdot \overrightarrow {{c}}}\right |+\left |{\overrightarrow {{b}}\cdot \overrightarrow {{c}}}\right |$ 的最大值是，最小值是.​​​​​​​‌

## 解答

1. 因为 $\left |{\overrightarrow {{a}}}\right |=2,\left |{\overrightarrow {{b}}}\right |=3,\left |{\overrightarrow {{c}}}\right |=4,\overrightarrow {{a}}\cdot \overrightarrow {{b}}=\frac {3}{2}$ ，可设 $\overrightarrow {{a}}=\left ({2,0}\right ),\overrightarrow {{c}}=\left ({4{\cos}θ,4{\sin}θ}\right ),\left \langle {\overrightarrow {{a}},\overrightarrow {{b}}}\right \rangle =α$ ， 易得 ${\cos}α=\frac {1}{4}$ ，则 ${\sin}α=\frac {\sqrt {15}}{4}$
2. 所以 $\left |{\overrightarrow {{a}}\cdot \overrightarrow {{c}}}\right |+\left |{\overrightarrow {{b}}\cdot \overrightarrow {{c}}}\right |=\left |{4\cdot 2\cdot {\cos}θ}\right |+\left |{4\cdot 3\cdot {\cos}\left ({α-θ}\right )}\right |$ 或  $\left |{\overrightarrow {{a}}\cdot \overrightarrow {{c}}}\right |+\left |{\overrightarrow {{b}}\cdot \overrightarrow {{c}}}\right |=\left |{4\cdot 2\cdot {\cos}θ}\right |+\left |{4\cdot 3\cdot {\cos}\left ({θ-α}\right )}\right |$ ，其外有绝对值，结果一样故后面只讨论前者，将其整理为 $\left |{\overrightarrow {{a}}\cdot \overrightarrow {{c}}}\right |+\left |{\overrightarrow {{b}}\cdot \overrightarrow {{c}}}\right |=\left |{8{\cos}θ}\right |+\left |{3{\cos}θ+3\sqrt {15}{\sin}θ}\right |$ ；
3. 从图象中可看出对顶角部分（无论阴影部分还是非阴影部分）是对称的，所以只讨论 $θ\in \left [0{^{\circ }},180{^{\circ }}\right ]$
4. 
5. ①当 $\overrightarrow {{c}}$ 与 $\overrightarrow {{a}},\overrightarrow {{b}}$ 的投影均非负时，显然以 $\overrightarrow {{c}}$ 与 $\overrightarrow {{a}}$ 垂直是第一个分界线，则 $θ\in \left [0{^{\circ }},90{^{\circ }}\right ]$
6. 则 $\left |{\overrightarrow {{a}}\cdot \overrightarrow {{c}}}\right |+\left |{\overrightarrow {{b}}\cdot \overrightarrow {{c}}}\right |=11{\cos}θ+3\sqrt {15}{\sin}θ=16{\sin}\left ({θ+φ}\right ),\left ({{\sin}φ=\frac {11}{16},{\cos}φ=\frac {3\sqrt {15}}{16}}\right )$
7. 因为 ${\sin}{^{2}}φ={\left({\frac {11}{16}}\right)^{2}}=\frac {121}{256}<\frac {128}{256}=\frac {1}{2}={\sin}{^{2}}45{^{\circ }}$ ，所以 $0{^{\circ }}<φ<45{^{\circ }}$
8. 由 $φ\leqslant θ+φ\leqslant 90{^{\circ }}+φ<135{^{\circ }}$ ，即 $\frac {11}{16}={\sin}φ\leqslant {\sin}\left ({θ+φ}\right )\leqslant 1$ ，则 $11\leqslant 16{\sin}\left ({θ+φ}\right )\leqslant 16$ ，所以最小值为11，最大值为16；
9. ②当 $\overrightarrow {{c}}$ 与 $\overrightarrow {{a}}$ 的投影为负，与 $\overrightarrow {{b}}$ 的投影为正时，显然以 $\overrightarrow {{c}}$ 与 $\overrightarrow {{b}}$ 垂直是第二个分界线，则 $θ\in \left ({90{^{\circ }},90{^{\circ }}+α}\right ]$
10. 则 $\left |{\overrightarrow {{a}}\cdot \overrightarrow {{c}}}\right |+\left |{\overrightarrow {{b}}\cdot \overrightarrow {{c}}}\right |=-5{\cos}θ+3\sqrt {15}{\sin}θ=4\sqrt {10}{\sin}\left ({θ-β}\right ),\left ({{\sin}β=-\frac {\sqrt {10}}{8},{\cos}β=\frac {3\sqrt {6}}{8}}\right )$
11. 显然 $β$ 在第四象限，因 ${\cos}{^{2}}\left ({-45{^{\circ }}}\right )=\frac {1}{2}<\frac {27}{32}={\cos}{^{2}}β$ ，所以 $-45{^{\circ }}<β<0{^{\circ }}$ ，即 $0{^{\circ }}<-β<45{^{\circ }}\Rightarrow 90{^{\circ }}<90{^{\circ }}-β<135{^{\circ }}\Rightarrow 90{^{\circ }}+α<90{^{\circ }}-β+α<135{^{\circ }}+α<225{^{\circ }}$ ，故 $90{^{\circ }}<90{^{\circ }}-β<θ-β\leqslant 90{^{\circ }}-β+α<225{^{\circ }}$ ，
12. 所以 $m=4\sqrt {10}{\sin}\left ({θ-β}\right )$ 在区间 $θ-β\in \left ({90{^{\circ }}-β,90{^{\circ }}-β+α}\right ]$ 上应单调递减，
13. 故 $m{{}_{{\rm \min }}}=4\sqrt {10}{\sin}\left ({90{^{\circ }}-β+α}\right )=4\sqrt {10}{\cos}\left ({α-β}\right )=4\sqrt {10}\left ({\frac {1}{4}\times \frac {3\sqrt {6}}{8}+\frac {\sqrt {15}}{4}\times \frac {\sqrt {10}}{8}}\right )=2\sqrt {15}$  $m{{}_{{\rm \max }}}=4\sqrt {10}{\sin}\left ({90{^{\circ }}-β}\right )=4\sqrt {10}{\cos}β=3\sqrt {15}$ ；
14. ③当 $\overrightarrow {{c}}$ 与 $\overrightarrow {{a}},\overrightarrow {{b}}$ 的投影均为负时，则 $θ\in \left ({90{^{\circ }}+α,180{^{\circ }}}\right ]$
15. 所以 $\left |{\overrightarrow {{a}}\cdot \overrightarrow {{c}}}\right |+\left |{\overrightarrow {{b}}\cdot \overrightarrow {{c}}}\right |=-11{\cos}θ-3\sqrt {15}{\sin}θ=-16{\sin}\left ({θ+φ}\right ),\left ({{\sin}φ=\frac {11}{16},{\cos}φ=\frac {3\sqrt {15}}{16}}\right )$
16. 由①中 $0{^{\circ }}<φ<45{^{\circ }}$ ，即 $90{^{\circ }}<90{^{\circ }}+α+φ<θ+φ\leqslant 180{^{\circ }}+φ<225{^{\circ }}$
17. 所以 $n=-16{\sin}\left ({θ+φ}\right )$ 在区间 $θ+φ\in \left ({90{^{\circ }}+α+φ,180{^{\circ }}+φ}\right ]$ 上应单调递减
18. 故 $n{{}_{{\rm \min }}}=-16{\sin}\left ({180{^{\circ }}+φ}\right )=16{\sin}φ=11$  $n{{}_{{\rm \max }}}=-16{\sin}\left ({90{^{\circ }}+α+φ}\right )=-16{\cos}\left ({α+φ}\right )=-16\left ({\frac {1}{4}\times \frac {3\sqrt {15}}{16}-\frac {\sqrt {15}}{4}\cdot \frac {11}{16}}\right )=2\sqrt {15}$ ；
19. 综上所述， $\left |{\overrightarrow {{a}}\cdot \overrightarrow {{c}}}\right |+\left |{\overrightarrow {{b}}\cdot \overrightarrow {{c}}}\right |$ 的最大值为16，最小值为 $2\sqrt {15}$ .
20. 故答案为：(1). $16$ ；(2). $2\sqrt {15}$

## 知识点

**中文**:
  - 数量积的计算

**English**:
  - Calculation of Scalar Product

---
