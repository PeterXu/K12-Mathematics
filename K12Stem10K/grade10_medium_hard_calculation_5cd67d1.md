# Mathematics - 题目 2472

**ID**: 5cd67d1a43ae44bea341aa38a7a7a5c8
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
某学校有一四边形地块，为了提高校园土地的利用率，现把其中的一部分作为学校生物综合实践基地．如图所示， $AB=BC=AC=2{\rm{k}}{\rm{m}}$ ， $M$ 是 $BC$ 中点，E，F分别在边 $AB$ ， $AC$ 上， $\vartriangle CMF$ 拟作为花草种植区，四边形 $AEMF$ 拟作为景观欣赏区， $\vartriangle BME$ 拟作为谷物蔬菜区， $ME$ 和 $MF$ 拟建造快速通道， $\angle EMF=60{}\degree $ ，记 $\angle CMF=θ$ ．（快速通道的宽度忽略不计）(1)若 $θ=60{}\degree $ ，求景观欣赏区所在四边形 $AEMF$ 的面积；​​​​​​​‌(2)当 $θ$ 取何值时，可使快速通道 $E-M-F$ 的路程最短?最短路程是多少?

![images/2472_b9bf1f231e912670.png](images/2472_b9bf1f231e912670.png)

## 解答

1. （1）当 $θ=60{}\degree $ 时， $ME//AC$ ，此时 $ME$ 为 $\vartriangle ABC$ 中位线，
2. $S{{}_{四边形AEMF}}=S{{}_{\vartriangle EMF}}+S{{}_{\vartriangle AEF}}=\frac {1}{2}\times 1\times 1\times \sin 60{^{0}}+\frac {1}{2}\times 1\times 1\times \sin 60{}\degree =\frac {\sqrt {3}}{2}$ ；
3. （2）在 $\vartriangle BME$ 中， $\angle BME={\rm{π}}-\frac {{\rm{π}}}{3}-θ=\frac {2{\rm{π}}}{3}-θ$ ， $\angle BEM={\rm{π}}-\frac {{\rm{π}}}{3}-\left ({\frac {2{\rm{π}}}{3}-θ}\right )=θ$ ， $BM=1$ ，
4. 由正弦定理得， $\frac {ME}{\sin \frac {{\rm{π}}}{3}}=\frac {1}{\sin θ}$ ，∴ $ME=\frac {\sqrt {3}}{2\sin θ}$ ．
5. 在 $\vartriangle CMF$ 中， $\angle MFC=\frac {2{\rm{π}}}{3}-θ$ ， $\angle MCF=\frac {{\rm{π}}}{3}$ ， $MC=1$ ，
6. 由正弦定理得， $\frac {MF}{\sin \frac {{\rm{π}}}{3}}=\frac {1}{\sin \left ({\frac {2{\rm{π}}}{3}-θ}\right )}$ ，∴ $MF=\frac {\sqrt {3}}{2\sin \left ({\frac {2{\rm{π}}}{3}-θ}\right )}$
7. ∴ $ME+MF=\frac {\sqrt {3}}{2\sin θ}+\frac {\sqrt {3}}{2\sin \left ({\frac {2{\rm{π}}}{3}-θ}\right )}=\frac {\sqrt {3}}{2}\frac {\sin θ+\sin \left ({\frac {2{\rm{π}}}{3}-θ}\right )}{\sin θ\sin \left ({\frac {2{\rm{π}}}{3}-θ}\right )}$
8. $=\frac {\sqrt {3}}{2}\frac {\frac {3}{2}\sin θ+\frac {\sqrt {3}}{2}{\cos}θ}{\frac {\sqrt {3}}{2}\sin θ{\cos}θ+\frac {1}{2}\sin {^{2}}θ}=\frac {\sqrt {3}}{2}\frac {\sqrt {3}\sin \left ({θ+\frac {{\rm{π}}}{6}}\right )}{\frac {\sqrt {3}}{4}\sin 2θ+\frac {1}{4}\left ({1-{\cos}2θ}\right )}$
9. $=\frac {3\sin \left ({θ+\frac {{\rm{π}}}{6}}\right )}{\sin \left ({2θ-\frac {{\rm{π}}}{6}}\right )+\frac {1}{2}}=\frac {3\sin \left ({θ+\frac {{\rm{π}}}{6}}\right )}{\sin \left ({2θ+\frac {{\rm{π}}}{3}-\frac {{\rm{π}}}{2}}\right )+\frac {1}{2}}$
10. $=\frac {3\sin \left ({θ+\frac {{\rm{π}}}{6}}\right )}{\frac {1}{2}-{\cos}\left ({2θ+\frac {{\rm{π}}}{3}}\right )}=\frac {3\sin \left ({θ+\frac {{\rm{π}}}{6}}\right )}{\frac {1}{2}-\left [1-2\sin {^{2}}\left ({θ+\frac {{\rm{π}}}{6}}\right )\right ]}$
11. $=\frac {3\sin \left ({θ+\frac {{\rm{π}}}{6}}\right )}{2\sin {^{2}}\left ({θ+\frac {{\rm{π}}}{6}}\right )-\frac {1}{2}}$ ，其中 $\frac {{\rm{π}}}{6}<θ<\frac {{\rm{π}}}{2}$ ，
12. 令 $t=\sin \left ({θ+\frac {{\rm{π}}}{6}}\right )$ ，∵ $θ+\frac {{\rm{π}}}{6}\in \left ({\frac {{\rm{π}}}{3},\frac {2{\rm{π}}}{3}}\right )$ ，∴ $t\in \left ({\frac {\sqrt {3}}{2},1}\right ]$ ，
13. 则 $ME+MF=\frac {3t}{2t{^{2}}-\frac {1}{2}}=\frac {3}{2t-\frac {1}{2t}}$
14. ∵ $y=2t$ 在 $\left ({\frac {\sqrt {3}}{2},1}\right ]$ 单调递增， $y=\frac {1}{2t}$ 在 $\left ({\frac {\sqrt {3}}{2},1}\right ]$ 单调递减，
15. ∴ $y=2t-\frac {1}{2t}$ 在 $\left ({\frac {\sqrt {3}}{2},1}\right ]$ 单调递增，∴当 $t=1$ ，即 $θ+\frac {{\rm{π}}}{6}=\frac {{\rm{π}}}{2}$ ， $θ=\frac {{\rm{π}}}{3}$ 时，
16. $\left ({ME+MF}\right ){{}_{{\rm \min }}}=\frac {3}{2-\frac {1}{2}}=2$ ，
17. 所以当 $θ$ 取 $\frac {{\rm{π}}}{{{3}}}$ 时，可使快速通道 $E-M-F$ 路程最短，最短距离为 $2{\rm{k}}{\rm{m}}$ ．

## 知识点

**中文**:
  - 复杂图形（多个三角形拼接、四边形）求解
  - 正、余弦定理的实际应用-测量距离问题

**English**:
  - Solving Complex Shapes (Combined Triangles, Quadrilaterals)
  - Measuring Distance

---
