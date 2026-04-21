# Mathematics - 题目 1549

**ID**: e66e93fb4721457b8fe738806780dba7
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
（1）过 $\vartriangle ABC$ 的重心G作直线l，若l与边 $BC$ 平行，与 $AB,AC$ 分别交于D，E两点，求 $\vartriangle ADE$ 与 $\vartriangle ABC$ 的面积比；​​​​​​​‌（2）在 $\vartriangle ABC$ 中，若 $\overrightarrow {{BF}}=m\overrightarrow {{BC}},\overrightarrow {{AO}}=n\overrightarrow {{AF}}$ ，其中 $m,n\in (0,1)$ ，过O作直线l，与线段 $AB,AC$ 分别交于D，E两点，求证： $(1-m)\frac {AB}{AD}+m\frac {AC}{AE}=\frac {1}{n}$ ；（3）在等腰直角 $\vartriangle ABC$ 中， $\angle C=\frac {{\rm{π}}}{2}$ ， $D,E$ 分别为 $AB,AC$ 的中点，将 $\vartriangle ADE$ 沿 $DE$ 折起，得到四棱锥 $S-BCED$ ，在二面角 $S-DE-B$ 处于 $\left [\frac {{\rm{π}}}{3},\frac {2{\rm{π}}}{3}\right ]$ 过程中，作 $\angle SBE$ 的角平分线交 $SE$ 于点M，记 $BM$ 与平面 $SCD$ 的交点为N，过N作直线l，与线段 $SC,SD$ 分别交于P，Q两点，记四棱锥 $S-BPMQ$ 的体积为 $V{{}_{1}}$ ，四棱锥 $S-BCED$ 的体积为V，求 $\frac {V{{}_{1}}}{V}$ 的最小值．

## 解答

1. （1）不妨设过 $\vartriangle ABC$ 重心的直线l与 $BC$ 平行，且与 $AB,AC$ 分别交于D，E两点，则 $\frac {AD}{AB}=\frac {AE}{AC}=\frac {2}{3}$ ，所以 $\frac {S{{}_{\mathrm{△}ADE}}}{S{{}_{\mathrm{△}ABC}}}=\frac {\frac {1}{2}AD\cdot AE\cdot \sin A}{\frac {1}{2}AB\cdot AC\cdot \sin A}=\frac {2}{3}\cdot \frac {2}{3}=\frac {4}{9}$
2. （2）证明：由 $\overrightarrow {{AO}}=n\overrightarrow {{AF}}=n(\overrightarrow {{AB}}+\overrightarrow {{BF}})=n\overrightarrow {{AB}}+nm\overrightarrow {{BC}}$
3. $=n\overrightarrow {{AB}}+nm(\overrightarrow {{AC}}-\overrightarrow {{AB}})=n(1-m)\overrightarrow {{AB}}+nm\overrightarrow {{AC}}$
4. $=n(1-m)\frac {AB}{AD}\overrightarrow {{AD}}+nm\frac {AC}{AE}\overrightarrow {{AE}}$
5. 因为D，O，E三点共线，所以 $n(1-m)\frac {AB}{AD}+nm\frac {AC}{AE}=1$ ，
6. 即 $(1-m)\frac {AB}{AD}+m\frac {AC}{AE}=\frac {1}{n}$
7. 
8. （3）不妨设等腰直角 $\vartriangle ABC$ 两条直角边长为2，则 $BE=\sqrt {5}$ ，
9. 因为 $\angle C=\frac {{\rm{π}}}{2}$ ， $D,E$ 分别为 $AB,AC$ 的中点，
10. 所以 $DE//BC$ ， $DE\bot SE,DE\bot CE$ ，
11. 所以 $\angle SEC$ 为二面角 $A-DE-B$ 的平面角，
12. 记二面角 $A-DE-B$ 的所成角为 $θ$ ．则 $θ\in \left [\frac {{\rm{π}}}{3},\frac {2{\rm{π}}}{3}\right ]$ ，
13. 因为 $DE\bot SE,DE\bot CE$ ， $SE,CE\subset $ 平面 $SCE$ ， $SE\cap CE=E$ ，
14. 所以 $DE\bot $ 平面 $SCE$ ， $DE\subset $ 平面 $BCED$ ，
15. 所以平面 $SCE\bot $ 平面 $BCED$ ，平面 $SCE\cap $ 平面 $BCED=CE$ ，
16. 过 $\mathrm{S}$ 点作 $CE$ 所在直线的垂线，垂足为T，则 $ST=\sin θ,CT=1-{\cos}θ$
17. 因为 $ST\subset $ 平面 $SCE$ ，所以 $ST\bot $ 平面 $BCED$ ， $BT\subset $ 平面 $BCED$ ，
18. 所以 $ST\bot BT$
19. 所以 $SB=\sqrt {2{^{2}}+(1-{\cos}θ){^{2}}+\sin {^{2}}θ}=\sqrt {6-2{\cos}θ}$ ，
20. 由 $BM$ 是 $\angle SBE$ 的平分线，所以 $\frac {SM}{ME}=\frac {SB}{BE}=\frac {\sqrt {6-2{\cos}θ}}{\sqrt {5}}$ ，
21. 所以 $\frac {ME}{SM}+1=\frac {ME+SM}{SM}=\frac {SE}{SM}=\frac {\sqrt {5}}{\sqrt {6-2{\cos}θ}}+1=\frac {\sqrt {5}+\sqrt {6-2{\cos}θ}}{\sqrt {6-2{\cos}θ}}$ ，
22. 设 $λ=\frac {SM}{SE}=\frac {\sqrt {6-2{\cos}θ}}{\sqrt {6-2{\cos}θ}+\sqrt {5}}$ ，即 $\overrightarrow {{SM}}=λ\overrightarrow {{SE}}$
23. 连接 $CD$ 和 $BE$ ，记 $CD\cap BE=O$ ，则 $\overrightarrow {{BO}}=\frac {2}{3}\overrightarrow {{BE}},\overrightarrow {{DO}}=\frac {1}{3}\overrightarrow {{DC}}$
24. 连接 $SO$ ，则面 $SBE\cap $ 面 $SCD=SO$
25. 又记 $BM$ 与平面 $SCD$ 的交点为N，即N为面 $SBE$ 与面 $SCD$ 的公共点，
26. 所以N在 $SO$ 上，设 $\overrightarrow {{SN}}=t\overrightarrow {{SO}}$ ，
27. 由（2）可知： $\left ({1-\frac {2}{3}}\right )\frac {SB}{SB}+\frac {2}{3}\frac {SE}{SM}=\frac {1}{t}$ ， $\left ({1-\frac {1}{3}}\right )\frac {SD}{SQ}+\frac {1}{3}\frac {SC}{SP}=\frac {1}{t}$ ，
28. 设 $\overrightarrow {{SP}}=x\overrightarrow {{SC}},\overrightarrow {{SQ}}=y\overrightarrow {{SD}}$ ，
29. 则 $\frac {1}{3}+\frac {2}{3}\frac {1}{λ}=\frac {2}{3}\frac {1}{y}+\frac {1}{3}\frac {1}{x}$ ，即 $\frac {2}{y}+\frac {1}{x}=\frac {λ+2}{λ}$ ，
30. 因为 $λ=\frac {SM}{SE}$ ，所以 $\frac {S{{}_{\vartriangle BMS}}}{S{{}_{\vartriangle BES}}}=\frac {\frac {1}{2}SM\cdot SB\sin \angle BSM}{\frac {1}{2}SB\cdot SE\sin \angle BSE}=λ$ ，
31. 所以 $\frac {V{{}_{S-BPM}}}{V{{}_{S-BPE}}}=\frac {V{{}_{P-BMS}}}{V{{}_{P-BES}}}=λ$ ， $\frac {V{{}_{S-BQM}}}{V{{}_{S-BQE}}}=\frac {V{{}_{Q-BMS}}}{V{{}_{Q-BES}}}=λ$ ，
32. 因为 $\overrightarrow {{SP}}=x\overrightarrow {{SC}},\overrightarrow {{SQ}}=y\overrightarrow {{SD}}$ ，
33. 所以点 $P$ 到平面 $BES$ 的距离是点 $C$ 到平面 $BES$ 的距离的 $x$ 倍，
34. 点 $Q$ 到平面 $BES$ 的距离是点 $D$ 到平面 $BES$ 的距离的 $y$ 倍，
35. 所以 $V{{}_{S-BPE}}=V{{}_{P-BES}}=xV{{}_{C-BES}}=xV{{}_{S-BCE}}$ ， $V{{}_{S-BQE}}=V{{}_{Q-BES}}=yV{{}_{D-BES}}=yV{{}_{S-BDE}}$
36. 所以 $V{{}_{1}}=V{{}_{S-BPM}}+V{{}_{S-BQM}}=λV{{}_{S-BPE}}+λV{{}_{S-BQE}}=λxV{{}_{S-BCE}}+λyV{{}_{S-BDE}}$
37. $=λx\frac {1}{3}\cdot \frac {1}{2}\cdot 2\cdot 1\cdot \sin θ+λy\frac {1}{3}\cdot \frac {1}{2}\cdot 1\cdot 1\cdot \sin θ=\frac {1}{6}λ\cdot \sin θ\cdot (2x+y)$
38. $V=\frac {1}{3}\cdot \frac {1}{2}\cdot (1+2)\cdot 1\cdot \sin θ=\frac {1}{2}\sin θ$ ，
39. 又 $(2x+y)\left ({\frac {2}{y}+\frac {1}{x}}\right )=\frac {4x}{y}+2+2+\frac {y}{x}\geqslant 4+2\sqrt {\frac {4x}{y}\cdot \frac {y}{x}}=8$ ，当且仅当 $y=2x$ 时等号成立，
40. 所以 $\frac {V{{}_{1}}}{V}=\frac {1}{3}λ(2x+y)=\frac {1}{3}λ\frac {λ}{λ+2}(2x+y)\left ({\frac {2}{y}+\frac {1}{x}}\right )\geqslant \frac {8}{3}\frac {λ{^{2}}}{λ+2}=\frac {8}{3}\frac {1}{\frac {1}{λ}+\frac {2}{λ{^{2}}}}$
41. 因为 $θ\in \left [\frac {{\rm{π}}}{3},\frac {2{\rm{π}}}{3}\right ]$ ，所以 $\sqrt {6-2{\cos}θ}\in [\sqrt {5},\sqrt {7}]$ ，
42. 所以 $1+\frac {\sqrt {35}}{7}\leqslant \frac {1}{λ}=\frac {\sqrt {6-2{\cos}θ}+\sqrt {5}}{\sqrt {6-2{\cos}θ}}=1+\frac {\sqrt {5}}{\sqrt {6-2{\cos}θ}}\leqslant 2$ ，即 $1+\frac {\sqrt {35}}{7}\leqslant \frac {1}{λ}\leqslant 2$ ，
43. 设 $t=\frac {1}{λ}$ ， $y=t+2t{^{2}}$ ， $1+\frac {\sqrt {35}}{7}\leqslant t\leqslant 2$ ，
44. 函数 $y=t+2t{^{2}}$ 在 $\left [1+\frac {\sqrt {35}}{7},2\right ]$ 单调递增，
45. 所以当 $t=2$ 时，函数 $y=t+2t{^{2}}$ ， $t\in \left [1+\frac {\sqrt {35}}{7},2\right ]$ 取最大值，最大值为 $10$ ，
46. 所以 $\frac {V{{}_{1}}}{V}=\frac {8}{3}\frac {1}{\frac {1}{λ}+\frac {2}{λ{^{2}}}}\geqslant \frac {4}{15}$ ，
47. 当且仅当 $θ=\frac {{\rm{π}}}{3},λ=\frac {1}{2},x=\frac {2}{5},y=\frac {4}{5}$ 时，等号成立
48. 

## 知识点

**中文**:
  - 二次函数的图象与性质
  - 线段的定比分点公式
  - 棱柱、棱锥、棱台的体积
  - 二面角

**English**:
  - Graph and Properties of Quadratic Functions
  - Section Formula (Ratio of Division)
  - Volume of Polyhedra
  - Dihedral Angle

---
