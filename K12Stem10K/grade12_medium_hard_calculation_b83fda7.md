# Mathematics - 题目 410

**ID**: b83fda7ef12840c58c4784c8a436df18
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
若 $\vartriangle ABC$ 内一点 $P$ 满足 $\angle PAB=\angle PBC=\angle PCA=θ$ ，则称点 $P$ 为 $\vartriangle ABC$ 的布洛卡点， $θ$ 为 $\vartriangle ABC$ 的布洛卡角．如图，已知 $\vartriangle ABC$ 中， $BC=a$ ， $AC=b$ ， $AB=c$ ，点 $P$ 为的布洛卡点， $θ$ 为 $\vartriangle ABC$ 的布洛卡角．(1)若 $b=c$ ，且满足 $\frac {PB}{PA}=\sqrt {3}$ ，求 $∠ABC$ 的大小．(2)若 $\vartriangle ABC$ 为锐角三角形．（ⅰ）证明： $\frac {1}{{\tan}θ}=\frac {1}{{\tan}\angle BAC}+\frac {1}{{\tan}\angle ABC}+\frac {1}{{\tan}\angle ACB}$ ．（ⅱ）若 $PB$ 平分 $∠ABC$ ，证明： $b{^{2}}=ac$ ．​​​​​​​‌

![images/410_4ad35c44f7704fef.png](images/410_4ad35c44f7704fef.png)

## 解答

1. （1）若 $b=c$ ，即 $AB=AC$ ，得 $∠ABC=\angle ACB$ ，
2. 点 $P$ 满足 $\angle PAB=\angle PBC=\angle PCA=θ$ ，则 $\angle PCB=\angle PBA$ ，
3. 在 $\vartriangle PCB$ 和 $\vartriangle PBA$ 中， $\angle PCB=\angle PBA$ ， $\angle PAB=\angle PBC=θ$ ，
4. 所以 $\vartriangle PCB$ 与 $\vartriangle PBA$ 相似，且 $\frac {PB}{PA}=\sqrt {3}$ ，
5. 所以 $\frac {BC}{AB}=\frac {a}{c}=\sqrt {3}$ ，即 $a=\sqrt {3}c$ ，
6. 由余弦定理得： ${\cos}\angle ABC=\frac {a{^{2}}+c{^{2}}-b{^{2}}}{2ac}$ ，且 $a=\sqrt {3}c$ ， $b=c$ ，
7. 得 ${\cos}∠ABC=\frac {3b{^{2}}+b{^{2}}-b{^{2}}}{2\sqrt {3}b{^{2}}}=\frac {\sqrt {3}}{2}$ ，且 $0<B<{\rm{π}}$ ，
8. 所以 $\angle ABC=\frac {{\rm{π}}}{6}$ ；
9. （2）（ⅰ）在 $\vartriangle ABC$ 内，应用余弦定理以及三角形的面积公式得：
10. $\frac {1}{{\tan}\angle BAC}=\frac {{\cos}\angle BAC}{{\sin}\angle BAC}=\frac {b{^{2}}+c{^{2}}-a{^{2}}}{2bc{\sin}\angle BAC}=\frac {b{^{2}}+c{^{2}}-a{^{2}}}{4S{{}_{\vartriangle ABC}}}$ ，
11. $\frac {1}{{\tan}\angle ABC}=\frac {{\cos}\angle ABC}{{\sin}\angle ABC}=\frac {a{^{2}}+c{^{2}}-b{^{2}}}{2ac{\sin}\angle ABC}=\frac {a{^{2}}+c{^{2}}-b{^{2}}}{4S{{}_{\vartriangle ABC}}}$ ，
12. $\frac {1}{{\tan}\angle ACB}=\frac {{\cos}\angle ACB}{{\sin}\angle ACB}=\frac {a{^{2}}+b{^{2}}-c{^{2}}}{2ab{\sin}\angle ACB}=\frac {a{^{2}}+b{^{2}}-c{^{2}}}{4S{{}_{\vartriangle ABC}}}$ ，
13. 三式相加可得： $\frac {1}{{\tan}\angle BAC}+\frac {1}{{\tan}\angle ABC}+\frac {1}{{\tan}\angle ACB}=\frac {a{^{2}}+b{^{2}}+c{^{2}}}{4S{{}_{\vartriangle ABC}}}$ ①
14. 在 $\vartriangle PAB$ 内，应用余弦定理以及三角形的面积公式得：
15. $\frac {1}{{\tan}θ}=\frac {{\cos}θ}{{\sin}θ}=\frac {AP{^{2}}+c{^{2}}-BP{^{2}}}{2AP\cdot c{\sin}θ}=\frac {AP{^{2}}+c{^{2}}-BP{^{2}}}{4S{{}_{\vartriangle PAB}}}$ ，
16. 在 $\vartriangle PBC$ 和 $\vartriangle PCA$ 内，同理： $\frac {1}{{\tan}θ}=\frac {BP{^{2}}+a{^{2}}-CP{^{2}}}{4S{{}_{\vartriangle PBC}}}$ ， $\frac {1}{{\tan}θ}=\frac {CP{^{2}}+b{^{2}}-AP{^{2}}}{4S{{}_{\vartriangle PCA}}}$ ，
17. 三式相等： $\frac {1}{{\tan}θ}=\frac {AP{^{2}}+c{^{2}}-BP{^{2}}}{4S{{}_{\vartriangle PAB}}}=\frac {BP{^{2}}+a{^{2}}-CP{^{2}}}{4S{{}_{\vartriangle PBC}}}=\frac {CP{^{2}}+b{^{2}}-AP{^{2}}}{4S{{}_{\vartriangle PCA}}}$ ，
18. 因为 $S{{}_{\vartriangle ABC}}=S{{}_{\vartriangle PAB}}+S{{}_{\vartriangle PBC}}+S{{}_{\vartriangle PCA}}$ ，由等比性质得： $\frac {1}{{\tan}θ}=\frac {(AP{^{2}}+c{^{2}}-BP{^{2}})+(BP{^{2}}+a{^{2}}-CP{^{2}})+(CP{^{2}}+b{^{2}}-AP{^{2}})}{4S{{}_{\vartriangle PAB}}+4S{{}_{\vartriangle PBC}}+4S{{}_{\vartriangle PCA}}}=\frac {a{^{2}}+b{^{2}}+c{^{2}}}{4S{{}_{\vartriangle ABC}}}$ ②
19. 由①②式可证得： $\frac {1}{{\tan}θ}=\frac {1}{{\tan}\angle BAC}+\frac {1}{{\tan}\angle ABC}+\frac {1}{{\tan}\angle ACB}$ ；
20. （ⅱ）因为 $S{{}_{\vartriangle ABC}}=S{{}_{\vartriangle PAB}}+S{{}_{\vartriangle PBC}}+S{{}_{\vartriangle PAC}}=\frac {1}{2}c\cdot AP{\sin}θ+\frac {1}{2}a\cdot BP{\sin}θ+\frac {1}{2}b\cdot CP{\sin}θ$ ，
21. 即 $S{{}_{\vartriangle ABC}}=\frac {1}{2}{\sin}θ\left ({c\cdot AP+a\cdot BP+b\cdot CP}\right )$ ，
22. 所以 $c\cdot AP+a\cdot BP+b\cdot CP=\frac {2S{{}_{\vartriangle ABC}}}{{\sin}θ}$ ，
23. 在 $\vartriangle PAB,\vartriangle PBC,\vartriangle PAC$ 中，
24. 分别由余弦定理得： $BP{^{2}}=c{^{2}}+AP{^{2}}-2c\cdot AP{\cos}θ$ ， $CP{^{2}}=a{^{2}}+BP{^{2}}-2a\cdot BP{\cos}θ$ ， $AP{^{2}}=b{^{2}}+CP{^{2}}-2b\cdot CP{\cos}θ$ ，
25. 三式相加整理得 $2{\cos}θ\left ({c\cdot AP+a\cdot BP+b\cdot CP}\right )=a{^{2}}+b{^{2}}+c{^{2}}$ ，
26. $a{^{2}}+b{^{2}}+c{^{2}}=2{\cos}θ\left ({c\cdot AP+a\cdot BP+b\cdot CP}\right )$ ，
27. 将 $c\cdot AP+a\cdot BP+b\cdot CP=\frac {2S{{}_{\vartriangle ABC}}}{{\sin}θ}$ 代入得：
28. $a{^{2}}+b{^{2}}+c{^{2}}=2{\cos}θ\cdot \frac {2S{{}_{\vartriangle ABC}}}{{\sin}θ}$
29. 若 $PB$ 平分 $∠ABC$ ，则 $\angle ABC=2θ$ ， $S{{}_{\vartriangle ABC}}=\frac {1}{2}ac{\sin}2θ$ ，
30. 所以 $a{^{2}}+b{^{2}}+c{^{2}}=2{\cos}θ\cdot \frac {2S{{}_{\vartriangle ABC}}}{{\sin}θ}=2{\cos}θ\cdot \frac {ac{\sin}2θ}{{\sin}θ}=4ac{\cos}{^{2}}θ$ ③
31. 又由余弦定理可得： $a{^{2}}+c{^{2}}=b{^{2}}+2ac{\cos}2θ=b{^{2}}+2ac\left ({{\cos}{^{2}}θ-{\sin}{^{2}}θ}\right )$ ④
32. 由③-④得： $b{^{2}}=-b{^{2}}+2ac\left ({{\sin}{^{2}}θ+{\cos}{^{2}}θ}\right )$
33. 所以 $b{^{2}}=ac\left ({{\sin}{^{2}}θ+{\cos}{^{2}}θ}\right )$ ，
34. 所以 $b{^{2}}=ac$ .

## 知识点

**中文**:
  - 复杂图形（多个三角形拼接、四边形）求解

**English**:
  - Solving Complex Shapes (Combined Triangles, Quadrilaterals)

---
