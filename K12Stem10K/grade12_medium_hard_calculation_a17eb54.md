# Mathematics - 题目 109

**ID**: a17eb54a7b694f3eadae07d47f4dd064
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
$\vartriangle ABC$ 中，角A，B，C所对应的边分别为a，b，c，已知 $c{\sin}C{\cos}B+b{\sin}C{\cos}C=\sqrt {3}c{\cos}A$ .​​​​​​​‌(1)求∠A；(2)若 $∠ABC=\angle ACB$ ，满足 $BD=3$ ， $CD=2$ ，四边形 $ABDC$ 是凸四边形，求四边形 $ABDC$ 面积的最大值．

## 解答

1. （1）由正弦定理和 $c{\sin}C{\cos}B+b{\sin}C{\cos}C=\sqrt {3}c{\cos}A$ 得：
2. ${\sin}C{\sin}C{\cos}B+{\sin}B{\sin}C{\cos}C=\sqrt {3}{\sin}C{\cos}A$ ，
3. 即 ${\sin}C\left ({{\sin}C{\cos}B+{\sin}B{\cos}C}\right )$  $={\sin}C{\sin}\left ({B+C}\right )={\sin}C{\sin}A=\sqrt {3}{\sin}C{\cos}A$ ，
4. 又 $C\in \left ({0,{\rm{π}}}\right )$ ，故 ${\sin}C\ne 0$ ，
5. 所以 ${\sin}A=\sqrt {3}{\cos}A$ ，即 ${\tan}A=\sqrt {3}$ ，又 $A\in \left ({0,{\rm{π}}}\right )$ ，
6. 所以 $A=\frac {{\rm{π}}}{3}$ .
7. （2）法一：若 $∠ABC=\angle ACB$ ，
8. 则由（1）可知 $\vartriangle ABC$ 为正三角形，设其边长为 $2a$ ，
9. 则有 $3-2\mathrm{<}2a\mathrm{<}3+2$ ，即 $\frac {1}{2}<a<\frac {5}{2}$ ，
10. 且由正三角形面积公式得 $S{{}_{\vartriangle ABC}}=\frac {\sqrt {3}}{4}\times {\left({2a}\right)^{2}}=\sqrt {3}a{^{2}}$ ，
11. 对于 $\mathrm{△}BCD$ ，设 $\angle CBD=θ$ ，则由余弦定理有 ${\cos}θ=\frac {4a{^{2}}+9-4}{2\times 2a\times 3}=\frac {4a{^{2}}+5}{12a}$ ，
12. 
13. 故 $S{{}_{\vartriangle BCD}}=\frac {1}{2}\times 3\times 2a{\sin}θ=3a\sqrt {1-{\cos}{^{2}}θ}=3a\sqrt {1-{\left({\frac {4a{^{2}}+5}{12a}}\right)^{2}}}$
14. $=\frac {\sqrt {-16\left ({a{^{4}}-\frac {13}{2}a{^{2}}}\right )-25}}{4}=\frac {\sqrt {-16{\left({a{^{2}}-\frac {13}{4}}\right)^{2}}+144}}{4}=\sqrt {-{\left({a{^{2}}-\frac {13}{4}}\right)^{2}}+9}$ ，
15. 所以四边形 $ABDC$ 的面积为 $S=S{{}_{\vartriangle ABC}}+S{{}_{\vartriangle BCD}}=\sqrt {3}a{^{2}}+\sqrt {-{\left({a{^{2}}-\frac {13}{4}}\right)^{2}}+9}$ ，
16. 令 $t=a{^{2}}-\frac {13}{4}\in \left ({-3,3}\right )$ （ $\frac {1}{2}<a<\frac {5}{2}$ ），则 $a{^{2}}=t+\frac {13}{4}$ ，
17. 故 $S=\sqrt {3}\left ({t+\frac {13}{4}}\right )+\sqrt {-t{^{2}}+9}=\sqrt {3}t+\sqrt {-t{^{2}}+9}+\frac {13\sqrt {3}}{4}$ ，
18. 再令 $t=3{\sin}α,α\in \left ({-\frac {{\rm{π}}}{2},\frac {{\rm{π}}}{2}}\right )$ ，
19. 则 $S=3\sqrt {3}{\sin}α+\sqrt {-{\left({3{\sin}α}\right)^{2}}+9}+\frac {13\sqrt {3}}{4}=3\sqrt {3}{\sin}α+3{\cos}α+\frac {13\sqrt {3}}{4}$  $=6{\sin}\left ({α+\frac {{\rm{π}}}{6}}\right )+\frac {13\sqrt {3}}{4}$ ，
20. 又 $α\in \left ({-\frac {{\rm{π}}}{2},\frac {{\rm{π}}}{2}}\right )$ ，所以 $α+\frac {{\rm{π}}}{6}\in \left ({-\frac {{\rm{π}}}{3},\frac {{{2}}{\rm{π}}}{3}}\right )$ ，
21. 所以 ${\sin}\left ({α+\frac {{\rm{π}}}{6}}\right )\in \left ({-\frac {\sqrt {3}}{2},1}\right ]$ ，
22. 所以当 ${\sin}\left ({α+\frac {{\rm{π}}}{6}}\right )=1$ 时，四边形 $ABDC$ 的面积取得最大值为： $6+\frac {13\sqrt {3}}{4}$ .
23. 法二：若 $∠ABC=\angle ACB$ ，则由（1）可知 $\vartriangle ABC$ 为正三角形，
24. 设 $\angle BDC=β$ ，由题意 $β\in \left ({0,{\rm{π}}}\right )$ ，
25. 由余弦定理 $BC{^{2}}=BD{^{2}}+CD{^{2}}-2BD\centerdot CD{\cos}β=13-12{\cos}β$ ，
26. 所以 $S=S{{}_{\vartriangle ABC}}+S{{}_{\vartriangle BCD}}=\frac {\sqrt {3}}{4}\times BC{^{2}}+\frac {1}{2}CD·BD{\sin}β=\frac {\sqrt {3}}{4}\times \left ({13-12{\cos}β}\right )+\frac {1}{2}\times 2\times 3\times {\sin}β$
27. $=3{\sin}β-3\sqrt {3}{\cos}β+\frac {13\sqrt {3}}{4}=6{\sin}\left ({β-\frac {{\rm{π}}}{3}}\right )+\frac {13\sqrt {3}}{4}$ ，
28. 又 $β\in \left ({0,{\rm{π}}}\right )$ ，所以 $β-\frac {{\rm{π}}}{3}\in \left ({-\frac {{\rm{π}}}{3},\frac {{{2}}{\rm{π}}}{3}}\right )$ ，
29. 所以 ${\sin}\left ({β-\frac {{\rm{π}}}{3}}\right )\in \left ({-\frac {\sqrt {3}}{2},1}\right ]$ ，
30. 所以当 ${\sin}\left ({β-\frac {{\rm{π}}}{3}}\right )=1$ 时，四边形 $ABDC$ 的面积取得最大值为： $6+\frac {13\sqrt {3}}{4}$ .
31. 

## 知识点

**中文**:
  - 两角和与差的正弦公式
  - 正弦定理及其公式的变形
  - 复杂图形（多个三角形拼接、四边形）求解

**English**:
  - Sine of Sum and Difference
  - Law of Sines and Formula Transformations
  - Solving Complex Shapes (Combined Triangles, Quadrilaterals)

---
