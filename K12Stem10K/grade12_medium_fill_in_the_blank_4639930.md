# Mathematics - 题目 1617

**ID**: 46399309b40f47549e8f08b78e9b102b
**年级**: Grade 12
**难度**: Medium
**题型**: Fill-in-the-blank

## 题目
已知 $\vartriangle ABC$ 是锐角三角形，内角A，B，C所对应的边分别为a，b，c．若 $a{^{2}}-b{^{2}}=bc$ ，则 $\frac {b}{a+c}$ 的取值范围是.​​​​​​​‌

## 解答

1. 因为 $a{^{2}}-b{^{2}}=bc$ ，得 $a{^{2}}=b{^{2}}+bc$ ．
2. 由余弦定理得 $a{^{2}}=b{^{2}}+c{^{2}}-2bc{\cos}A$ ，
3. 所以 $b{^{2}}+bc=b{^{2}}+c{^{2}}-2bc{\cos}A$ ，即 $b=c-2b{\cos}A$ ．
4. 由正弦定理得 $\sin B=\sin C-2\sin B{\cos}A$ ，
5. 因为 $C={\rm{π}}-\left ({A+B}\right )$ ，则 $\sin C=\sin (A+B)=\sin A{\cos}B+{\cos}A\sin B$ ，
6. 所以 $\sin B=\sin A{\cos}B-{\cos}A\sin B$ ，即 $\sin B=\sin \left ({A-B}\right )$ ．
7. 因为 $\vartriangle ABC$ 是锐角三角形，所以 $0<A<\frac {{\rm{π}}}{2}$ ， $0<B<\frac {{\rm{π}}}{2}$ ，所以 $-\frac {{\rm{π}}}{2}<A-B<\frac {{\rm{π}}}{2}$ ．
8. 又 $y=\sin x$ 在 $\left ({-\frac {{\rm{π}}}{2},\frac {{\rm{π}}}{2}}\right )$ 上单调递增，所以 $B=A-B$ ，则 $A=2B$ ．
9. 因为 $\vartriangle ABC$ 是锐角三角形，所以 $0<B<\frac {{\rm{π}}}{2}$ ， $0<A=2B<\frac {{\rm{π}}}{2}$ ， $0<C={\rm{π}}-3B<\frac {{\rm{π}}}{2}$ ，
10. 所以 $\frac {{\rm{π}}}{6}<B<\frac {{\rm{π}}}{4}$ ，
11. 由正弦定理得 $\frac {b}{a+c}=\frac {\sin B}{\sin A+\sin C}=\frac {\sin B}{\sin 2B+\sin \left ({{\rm{π}}-3B}\right )}=\frac {\sin B}{\sin 2B+\sin 3B}$
12. $=\frac {\sin B}{\sin 2B+\sin 2B{\cos}B+{\cos}2B\sin B}=\frac {1}{2{\cos}B+2{\cos}{^{2}}B+2{\cos}{^{2}}B-1}$
13. $=\frac {1}{4{\cos}{^{2}}B+2{\cos}B-1}$ ，
14. 令 ${\cos}B=t$ ，因为 $\frac {{\rm{π}}}{6}<B<\frac {{\rm{π}}}{4}$ ，所以 $t\in \left ({\frac {\sqrt {2}}{2},\frac {\sqrt {3}}{2}}\right )$ ．
15. $y=4t{^{2}}+2t-1=4{\left({t+\frac {1}{4}}\right)^{2}}-\frac {5}{4}$ 在 $t\in \left ({\frac {\sqrt {2}}{2},\frac {\sqrt {3}}{2}}\right )$ 上单调递增，
16. 当 $t=\frac {\sqrt {2}}{2}$ 时， $y=1+\sqrt {2}$ ，当 $t=\frac {\sqrt {3}}{2}$ 时， $y=2+\sqrt {3}$ ，
17. 故 $\frac {b}{a+c}=\frac {1}{4t{^{2}}+2t-1}\in \left ({\frac {1}{2+\sqrt {3}},\frac {1}{1+\sqrt {2}}}\right )=\left ({2-\sqrt {3},\sqrt {2}-1}\right )$ .

## 知识点

**中文**:
  - 二次函数的图象与性质
  - 正弦定理及其公式的变形
  - 余弦定理及其公式的变形

**English**:
  - Graph and Properties of Quadratic Functions
  - Law of Sines and Formula Transformations
  - Law of Cosines and Formula Transformations

---
