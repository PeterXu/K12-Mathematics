# Mathematics - 题目 842

**ID**: efd8b32f77b24f4ebfb8a12afeaab728
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Multiple-select

## 题目
在 $\vartriangle ABC$ 中， $AC+AB=4$ ，且 ${\rm{c}}{\rm{o}}{\rm{s}}A+2{\rm{c}}{\rm{o}}{\rm{s}}\left ({A+\frac {3{\rm{π}}}{4}}\right ){\rm{s}}{\rm{i}}{\rm{n}}\left ({A+\frac {3{\rm{π}}}{4}}\right )=0$ ，若 $D$ 是 $\vartriangle ABC$ 边 $BC$ 上的一点，满足 $\frac {\overrightarrow {{AB}}\cdot \overrightarrow {{AD}}}{\left |{\overrightarrow {{AB}}}\right |}=\frac {\overrightarrow {{AD}}\cdot \overrightarrow {{AC}}}{\left |{\overrightarrow {{AC}}}\right |}$ ，则（      ）​​​​​​​‌

## 解答

1. 因为 $\cos A+2\cos (A+\frac{3\pi }{4})\sin (A+\frac{3\pi }{4})=0$ ，
2. 所以化简得 $\cos A+\sin (2A+\frac{3\pi }{2})=0$ ，即 $2{\cos}{^{2}}A-{\cos}A-1=0$ .
3. 解得 $\cos A=\frac{1±\sqrt{1+8}}{4}=\frac{1±3}{4}$ ，即 ${\cos}A=1$ （舍去）或 ${\cos}A=-\frac {1}{2}$ .
4. 所以 $A=\frac {2{\rm{π}}}{3}$ ，所以A错误；
5. 因为 $AC+AB=4\geqslant 2\sqrt{AC·AB}$ ，所以 $AC·AB\leqslant 4$
6. 当且仅当 $AB=AC=2$ 时等号成立.
7. 所以 $\vartriangle ABC$ 的面积为 $S=\frac{1}{2}×AB×AC×\sin A\leqslant \frac{1}{2}×4×\frac{\sqrt{3}}{2}=\sqrt{3}$ ，
8. 此时其面积的最大值为 $\sqrt {3}{\rm ，B}$ 正确；
9. 因为 $\frac{\overrightarrow {AB}·\overrightarrow {AD}}{\left|\overrightarrow {AB}\right|}=\frac{\overrightarrow {AC}·\overrightarrow {AD}}{\left|\overrightarrow {AC}\right|}$ ，所以 $\frac{\left|\overrightarrow {AB}\right|\left|\overrightarrow {AD}\right|\cos \angle BAD}{\left|\overrightarrow {AB}\right|}=\frac{\left|\overrightarrow {AC}\right|\left|\overrightarrow {AD}\right|\cos \angle CAD}{\left|\overrightarrow {AC}\right|}$ ，
10. 所以 $\cos \angle BAD=\cos \angle CAD$ ，即 $\angle BAD=\angle CAD=\frac {{\rm{π}}}{3}$ .
11. 根据 $S{{}_{\vartriangle ABC}}=S{{}_{\vartriangle ABD}}+S{{}_{\vartriangle ACD}}$ 得， $\frac{1}{2}×AB×AC×\sin A=\frac{1}{2}×AB×AD×\sin \angle BAD+\frac{1}{2}×AC×AD×\sin \angle CAD$ ，
12. 化简得 $AB·AC=AD(AB+AC)=4AD$ ，所以C错误；
13. 根据角平分线定理可得 $\frac {BD}{CD}=\frac {AB}{AC}$ ，设 $AB=x,AC=y$ ，则 $x+y=4$ .
14. 则 $BD=\frac{x}{x+y}BC,CD=\frac{y}{x+y}BC$ ，所以 $\frac{1}{BD}+\frac{1}{CD}=\frac{x+y}{xBC}+\frac{x+y}{yBC}=\frac{{\left(x+y\right)^{2}}}{xyBC}$ .
15. 根据余弦定理得 $B{C}^{2}=A{B}^{2}+A{C}^{2}-2AB×AC×\cos A={x}^{2}+{y}^{2}+xy=16-xy$ .
16. 所以 $BC=\sqrt{16-xy}$ .
17. 所以 $\frac{1}{BD}+\frac{1}{CD}=\frac{16}{xy\sqrt{16-xy}}=\frac{16}{\sqrt{{x}^{2}{y}^{2}(16-xy)}}$ .
18. 设 $t=xy$ ，则由 $xy\leqslant 4$ 得 $0<t\leqslant 4$ .
19. 令 $f(t)={t}^{2}(16-t)=-{t}^{3}+16{t}^{2}$ ，求导得 ${f}^{\prime }(t)=-3{t}^{2}+32t=t(-3t+32)$ .
20. 所以 $f\left ({t}\right )$ 在 $t\in (0,4]$ 上单调递增，所以 $\sqrt{f(t)}\leqslant \sqrt{f(4)}=\sqrt{192}=8\sqrt{3}$ .
21. 所以 $\sqrt {f\left ({t}\right )}$ 的最大值为 $8\sqrt {3}$ ，此时 $\frac {1}{BD}+\frac {1}{CD}$ 的最小值为 $\frac{16}{8\sqrt{3}}=\frac{2\sqrt{3}}{3}$ ，所以D正确.
22. 故选BD.
23. 

## 知识点

**中文**:
  - 二倍角的正弦
  - 周长与面积最值或范围
  - 证明等式或不等式

**English**:
  - Double Angle Sine
  - Perimeter and Area: Extrema or Range
  - Proving Equalities or Inequalities

---
