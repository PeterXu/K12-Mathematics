# Mathematics - 题目 1571

**ID**: 21db62ac16f440b784b862eb7868461b
**年级**: Grade 12
**难度**: Medium
**题型**: Fill-in-the-blank

## 题目
十七世纪法国数学家、被誉为业余数学家之王的皮埃尔・德・费马提出的一个著名的几何问题：“已知一个三角形，求作一点，使其与这个三角形的三个顶点的距离之和最小”，意大利数学家托里拆利给出了解答，当 ${\huge \vartriangle }ABC$ 的三个内角均小于 $120{}\degree $ 时，使得 $\angle AOB=\angle BOC=\angle COA=120{}\degree $ 的点 $O$ 即为费马点；当 ${\huge \vartriangle }ABC$ 有一个内角大于或等于 $120{}\degree $ 时，最大内角的顶点为费马点.​​​​​​​‌已知 $a$ ， $b$ ， $c$ 分别是 ${\huge \vartriangle }ABC$ 三个内角 $A$ ， $B$ ， $C$ 的对边，且 ${\rm{c}}{\rm{o}}{\rm{s}}{^{2}}\frac {A}{2}=\frac {b+c}{2c}$ ，若点 $P$ 为 ${\huge \vartriangle }ABC$ 的费马点， $\left |{PB}\right |+\left |{PA}\right |=t\left |{PC}\right |$ ，则实数 $t$ 的取值范围为.

## 解答

1. 因为 ${\rm{c}}{\rm{o}}{\rm{s}}{^{2}}\frac {A}{2}=\frac {b+c}{2c}$ ，则 $\frac {1+{\cos}A}{2}=\frac {b+c}{2c}$ ，整理得 $c{\cos}A=b$ ，
2. 由正弦定理可得 $\sin C{\cos}A=\sin B=\sin \left ({A+C}\right )=\sin A{\cos}C+{\cos}A\sin C$ ，
3. 则 $\sin A{\cos}C=0$ ，且 $A,C\in \left ({0,{\rm{π}}}\right )$ ，则 $\sin A\ne 0$
4. 可得 ${\cos}C=0$ ，可知 $C=\frac {{\rm{π}}}{2}$ ，
5. 故由点 $P$ 为 ${\huge \vartriangle }ABC$ 的费马点得 $\angle APB=\angle BPC=\angle CPA=\frac {2{\rm{π}}}{3}$ ，
6. 
7. 设 $|PB|=m|PC|{\rm{,}}|PA|=n|PC|,|PC|=x,m>0,n>0,x>0$ ，
8. 由 $\left |{PB}\right |+\left |{PA}\right |=t\left |{PC}\right |$ 得 $m+n=t$ ；
9. 由余弦定理得 $\left |{BC}\right |{^{2}}=x{^{2}}+m{^{2}}x{^{2}}-2mx{^{2}}{\cos}\frac {2{\rm{π}}}{3}=\left ({m{^{2}}+m+1}\right )x{^{2}}$ ，
10. $|AC|{^{2}}=x{^{2}}+n{^{2}}x{^{2}}-2nx{^{2}}{\cos}\frac {2{\rm{π}}}{3}=\left ({n{^{2}}+n+1}\right )x{^{2}}$ ，
11. $|AB|{^{2}}=m{^{2}}x{^{2}}+n{^{2}}x{^{2}}-2mnx{^{2}}{\cos}\frac {2{\rm{π}}}{3}=\left ({m{^{2}}+n{^{2}}+mn}\right )x{^{2}}$ ，
12. 因为 $\left |{BC}\right |{^{2}}+\left |{AC}\right |{^{2}}=\left |{AB}\right |{^{2}}$ ，
13. 即 $\left ({n{^{2}}+n+1}\right )x{^{2}}+\left ({m{^{2}}+m+1}\right )x{^{2}}=\left ({m{^{2}}+n{^{2}}+mn}\right )x{^{2}}$ ，可得 $m+n+2=mn$ ，
14. 且 $m>0,n>0$ ，则 $m+n+2=mn\leqslant {\left({\frac {m+n}{2}}\right)^{2}}$ ，
15. 当且仅当 $\begin{cases}m=n\\m+n+2=mn\end{cases}$ ，即 $m=n=1+\sqrt {3}$ 时，等号成立，
16. 又因为 $m+n=t$ ，则 $t{^{2}}-4t-8\geqslant 0$ ，解得 $t\geqslant 2+2\sqrt {3}$ 或 $t\leqslant 2-2\sqrt {3}$ （舍去），
17. 所以实数 $t$ 的取值范围为 $\left [{2+2\sqrt {3},+\infty }\right )$ .
18. 故答案为： $\left [{2+2\sqrt {3},+\infty }\right )$ .

## 知识点

**中文**:
  - 复杂图形（多个三角形拼接、四边形）求解

**English**:
  - Solving Complex Shapes (Combined Triangles, Quadrilaterals)

---
