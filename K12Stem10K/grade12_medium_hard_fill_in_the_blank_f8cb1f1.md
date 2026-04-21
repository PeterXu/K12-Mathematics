# Mathematics - 题目 3096

**ID**: f8cb1f1eb6374f96830a4030a1c2012c
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Fill-in-the-blank

## 题目
三棱锥 $P-ABC$ 的底面是以 $AC$ 为底边的等腰直角三角形，且 $AC=2\sqrt {2}$ ，各侧棱长均为3，点 $E$ 为棱 $PA$ 的中点，点 $Q$ 是线段 $CE$ 上的动点，则 $E$ 到平面 $ABC$ 的距离为；设 $Q$ 到平面 $PBC$ 的距离为 $d{{}_{1}},Q$ 到直线 $AB$ 的距离为 $d{{}_{2}}$ ，则 $d{{}_{1}}+d{{}_{2}}$ 的最小值为.​​​​​​​‌

## 解答

1. 取 $AC$ 中点 $O$ ，连接 $PO,BO$ ，
2. 因为 $PA=PC=3$ ， $AC=2\sqrt {2}$ ，所以 $PO\bot AC$ ，且 $PO=\sqrt {3{^{2}}-2}=\sqrt {7}$ ，
3. 因为 $\vartriangle ABC$ 是等腰直角三角形，所以 $BO\bot AC$ ，且 $BO=\sqrt {2}$ ，
4. 又 $PB=3$ ，满足 $PB{^{2}}=PO{^{2}}+BO{^{2}}$ ，所以 $PO\bot BO$ ，
5. 因为 $AC\cap BO=O$ ，所以 $PO\bot $ 平面 $ABC$ ，
6. 因为点 $E$ 为棱 $PA$ 的中点，所以 $E$ 到平面 $ABC$ 的距离为 $\frac {1}{2}PO=\frac {\sqrt {7}}{2}$ ；
7. 如图，以 $O$ 为原点建立空间直角坐标系，设 $\overrightarrow {{CQ}}=λ\overrightarrow {{CE}}\left ({0\leqslant λ\leqslant 1}\right )$ ,
8. 则 $C\left ({0,\sqrt {2},0}\right ),E\left ({0,-\frac {\sqrt {2}}{2},\frac {\sqrt {7}}{2}}\right ),P\left ({0,0,\sqrt {7}}\right ),A\left ({0,-\sqrt {2},0}\right ),B\left ({\sqrt {2},0,0}\right )$ ，
9. 则 $\overrightarrow {{PB}}=\left ({\sqrt {2},0,-\sqrt {7}}\right ),\overrightarrow {{PC}}=\left ({0,\sqrt {2},-\sqrt {7}}\right ),\overrightarrow {{AB}}=\left ({\sqrt {2},\sqrt {2},0}\right ),\overrightarrow {{CE}}=\left ({0,-\frac {3\sqrt {2}}{2},\frac {\sqrt {7}}{2}}\right )$ ，
10. 设 $\overrightarrow {{CQ}}=λ\overrightarrow {{CE}}\left ({0\leqslant λ\leqslant 1}\right )$ ，则可得 $\overrightarrow {{CQ}}=\left ({0,-\frac {3\sqrt {2}}{2}λ,\frac {\sqrt {7}}{2}λ}\right )$ ，
11. 则 $Q\left ({0,-\frac {3\sqrt {2}}{2}λ+\sqrt {2},\frac {\sqrt {7}}{2}λ}\right )$ ，则 $\overrightarrow {{AQ}}=\left ({0,2\sqrt {2}-\frac {3\sqrt {2}}{2}λ,\frac {\sqrt {7}}{2}λ}\right )$ ，
12. 所以 ${\cos}\angle QAB=\frac {\overrightarrow {{AQ}}\cdot \overrightarrow {{AB}}}{\left |{\overrightarrow {{AQ}}}\right |\cdot \left |{\overrightarrow {{AB}}}\right |}=\frac {4-3λ}{\sqrt {25λ{^{2}}-48λ+32}}$ ，
13. 所以 $\sin \angle QAB=\sqrt {\frac {16λ{^{2}}-24λ+16}{25λ{^{2}}-48λ+32}}$ ,
14. 所以 $d{{}_{2}}=\left |{AQ}\right |\cdot \sin \angle QAB=\sqrt {4λ{^{2}}-6λ+4}$ ,
15. 设平面 $PBC$ 的法向量为 $\overrightarrow {{n}}=\left ({x,y,z}\right )$ ，
16. 则 $\begin{cases}\overrightarrow {{n}}\cdot \overrightarrow {{PB}}=0\\\overrightarrow {{n}}\cdot \overrightarrow {{PC}}=0\end{cases}$ ，即 $\begin{cases}\sqrt {2}x-\sqrt {7}z=0\\\sqrt {2}y-\sqrt {7}z=0\end{cases}$ ，令 $x=\sqrt {7}$ ，可得 $\overrightarrow {{n}}=\left ({\sqrt {7},\sqrt {7},\sqrt {2}}\right )$ ，
17. 则 $d{{}_{1}}=\frac {\left |{\overrightarrow {{CQ}}\cdot \overrightarrow {{n}}}\right |}{\left |{\overrightarrow {{n}}}\right |}=\frac {\sqrt {14}}{4}λ$ ，
18. 所以 $d{{}_{1}}+d{{}_{2}}=f\left ({λ}\right )=\sqrt {4λ{^{2}}-6λ+4}+\frac {\sqrt {14}}{4}λ,0\leqslant λ\leqslant 1$ ，
19. 所以 $f^{′}{\left ({λ}\right )}=\frac {4λ-3}{\sqrt {4λ{^{2}}-6λ+4}}+\frac {\sqrt {14}}{4}$ ，令 $f^{′}{\left ({λ}\right )}=0$ ，解得 $λ{\rm{=}}\frac {2}{5}$ ，
20. 又 $f^{′′}{\left ({λ}\right )}=\frac {7}{\left ({4λ{^{2}}-6λ+4}\right )\sqrt {4λ{^{2}}-6λ+4}}>0$ ，所以 $f^{′}{\left ({λ}\right )}$ 在 $\left [0,1\right ]$ 单调递增，
21. 所以当 $λ\in \left ({0,\frac {2}{5}}\right )$ 时， $f^{′}{\left ({λ}\right )}<0$ ， $f\left ({λ}\right )=0$ 单调递减，当 $λ\in \left ({\frac {2}{5},1}\right )$ 时， $f^{′}{\left ({λ}\right )}>0$ ， $f\left ({λ}\right )=0$ 单调递增，
22. 所以 $f\left ({λ}\right ){{}_{{\rm \min }}}=f\left ({\frac {2}{5}}\right )=\frac {\sqrt {14}}{2}$ ，即 $d{{}_{1}}+d{{}_{2}}$ 的最小值为 $\frac {\sqrt {14}}{2}$ .
23. 

## 知识点

**中文**:
  - 向量法求距离-点线距离
  - 点与面之间的距离
  - 向量法求距离-点面距离

**English**:
  - Point-Line Distance
  - Point-Plane Distance
  - Point-Plane Distance

---
