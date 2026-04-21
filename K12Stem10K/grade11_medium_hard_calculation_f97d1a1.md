# Mathematics - 题目 2274

**ID**: f97d1a1c31f64a02bc35674056956655
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
在平面直角坐标系中，对于 $\vartriangle ABC$ 及直线l，记 $d{{}_{1}}\left ({A}\right )$ 、 $d{{}_{1}}\left ({B}\right )$ 、 $d{{}_{l}}\left ({C}\right )$ 分别表示A、B、C到l的距离，且 $S{{}_{l}}=\left [d{{}_{l}}\left ({A}\right )\right ]{^{2}}+\left [d{{}_{l}}\left ({B}\right )\right ]{^{2}}+\left [d{{}_{l}}\left ({C}\right )\right ]{^{2}}$ ．对于给定的 $\vartriangle ABC$ ，记 $S{{}_{1}}$ 的最小值为 $m{{}_{\mathrm{△}ABC}}$ ．（1）已知定点 $A\left ({0,0}\right )$ ， $B\left ({3,0}\right )$ ， $C\left ({2,2}\right )$ ，直线l的方程为 $x+7y+9=0$ ，求 $S{{}_{l}}$ 的值；​​​​​​​‌（2）已知 $A\left ({x{{}_{A}}{\rm{,}}y{{}_{A}}}\right )$ ， $B\left ({x{{}_{B}},y{{}_{B}}}\right )$ ， $C\left ({x{{}_{C}}{\rm{,}}y{{}_{C}}}\right )$ 为给定的不共线的三点，若直线 $l{{}_{0}}$ 使得 $S{{}_{l{{}_{0}}}}=m{{}_{\mathrm{△}ABC}}$ ，求证：直线 $l{{}_{0}}$ 过 $\vartriangle ABC$ 的重心；（3）若对于 $\vartriangle ABC$ ，满足 $S{{}_{l}}=m{{}_{\mathrm{△}ABC}}$ 的不同直线l至少有两条，试判断 $\vartriangle ABC$ 的形状，并予以证明．

## 解答

1. （1） $d{{}_{l}}\left ({A}\right )=\frac {\left |{1\cdot 0+7\cdot 0+9}\right |}{\sqrt {1{^{2}}+7{^{2}}}}=\frac {9}{\sqrt {50}}$ ， $d{{}_{l}}\left ({B}\right )=\frac {\left |{1\cdot 3+7\cdot 0+9}\right |}{\sqrt {1{^{2}}+7{^{2}}}}=\frac {12}{\sqrt {50}}$ ， $d{{}_{l}}\left ({C}\right )=\frac {\left |{1\cdot 2+7\cdot 2+9}\right |}{\sqrt {1{^{2}}+7{^{2}}}}=\frac {25}{\sqrt {50}}$ ，
2. 故 $S{{}_{l}}={\left({\frac {9}{\sqrt {50}}}\right)^{2}}+{\left({\frac {12}{\sqrt {50}}}\right)^{2}}+{\left({\frac {25}{\sqrt {50}}}\right)^{2}}=17$ ．
3. （2）设 $A\left ({x{{}_{A}}{\rm{,}}y{{}_{A}}}\right )$ ， $B\left ({x{{}_{B}},y{{}_{B}}}\right )$ ， $C\left ({x{{}_{C}}{\rm{,}}y{{}_{C}}}\right )$ ，直线 $l{{}_{0}}:ax+by+c=0$ ，
4. 对任意固定的a、b，要使得 $S{{}_{l{{}_{0}}}}=\frac {1}{a{^{2}}+b{^{2}}}\left [{\left({ax{{}_{A}}+by{{}_{A}}+c}\right)^{2}}+{\left({ax{{}_{B}}+by{{}_{B}}+c}\right)^{2}}+{\left({ax{{}_{C}}+by{{}_{C}}+c}\right)^{2}}\right ]$
5. $=\frac {1}{a{^{2}}+b{^{2}}}\left [3c{^{2}}+2\left ({ax{{}_{A}}+ax{{}_{B}}+ax{{}_{C}}+by{{}_{A}}+by{{}_{B}}+by{{}_{C}}}\right )c+{\left({ax{{}_{A}}+by{{}_{A}}}\right)^{2}}+{\left({ax{{}_{B}}+by{{}_{B}}}\right)^{2}}+{\left({ax{{}_{C}}+by{{}_{C}}}\right)^{2}}\right ]$ ，最小，
6. 那么由二次函数的性质可得， $c=-\frac {a\left ({x{{}_{A}}+x{{}_{B}}+x{{}_{C}}}\right )}{3}-\frac {b\left ({y{{}_{A}}+y{{}_{B}}+y{{}_{C}}}\right )}{3}$ ，
7. 此时直线方程为 $l:ax+by+c=a\left ({x-\frac {x{{}_{A}}+x{{}_{B}}+x{{}_{c}}}{3}}\right )+b\left ({y-\frac {y{{}_{A}}+y{{}_{B}}+y{{}_{c}}}{3}}\right )=0$ ，
8. 过 $\vartriangle ABC$ 的重心 $\left ({\frac {x{{}_{A}}+x{{}_{B}}+x{{}_{c}}}{3},\frac {y{{}_{A}}+y{{}_{B}}+y{{}_{c}}}{3}}\right )$ ，因此 $l{{}_{0}}$ 过 $\vartriangle ABC$ 的重心．
9. （3）由（2）知， $S{{}_{l}}$ 取最小值时，l过 $\vartriangle ABC$ 的重心，不失一般性，
10. 不妨设 $A\left ({x{{}_{A}}{\rm{,}}-h}\right )$ ， $B\left ({x{{}_{B}}{\rm{,}}-h}\right )$ ， $C\left ({-\left ({x{{}_{A}}+x{{}_{B}}}\right ){\rm{,}}2h}\right )$ ，其中 $h\ne 0$ ，
11. 此时l的方程为 $\sin θ\cdot x-{\cos}θ\cdot y=0$ ，这里 ${\rm \mathit{θ}}$ 表示直线l的倾斜角 $0\leqslant θ<{\rm{π}}$ ，
12. 此时 $S{{}_{l}}\left ({θ}\right )={\left({x{{}_{A}}\sin θ+h{\cos}θ}\right)^{2}}+{\left({x{{}_{B}}\sin θ+h{\cos}θ}\right)^{2}}+\left [\left ({x{{}_{A}}+x{{}_{B}}}\right )\sin θ+2h{\cos}θ\right ]{^{2}}$
13. $=3h{^{2}}+x{{}_{A}^{2}}+x{{}_{B}^{2}}+x{{}_{A}}x{{}_{B}}+3h\left ({x{{}_{A}}+x{{}_{B}}}\right )\sin 2θ+\left [3h{^{2}}-\left ({x{{}_{A}^{2}}+x{{}_{B}^{2}}+x{{}_{A}}x{{}_{B}}}\right )\right ]{\cos}2θ$ ，
14. 此时 $S{{}_{l}}\left ({θ}\right )$ 为关于 ${\rm \mathit{θ}}$ 的函数、定义域为 $\left [{0,{\rm{π}}}\right )$ 的函数，
15. 令 $λ=3h\left ({x{{}_{A}}+x{{}_{B}}}\right )$ ， $μ=3h{^{2}}-\left ({x{{}_{A}^{2}}+x{{}_{B}^{2}}+x{{}_{A}}x{{}_{B}}}\right )$ ， $ν=3h{^{2}}+x{{}_{A}^{2}}+x{{}_{B}^{2}}+x{{}_{A}}x{{}_{B}}$ ，
16. 则 $S{{}_{l}}\left ({θ}\right )=\sqrt {λ{^{2}}+μ{^{2}}}\sin \left ({2θ+φ}\right )+ν$ ，
17. 若 $λ\ne 0$ 或 $μ\ne 0$ ，那么函数 $S{{}_{l}}\left ({θ}\right )$ 在 $θ\in \left [{0,{\rm{π}}}\right )$ 上有且仅有一个最小值，这与已知条件取最小值至少有两条直线满足条件矛盾．
18. 因此必须有 $λ=0$ 且 $μ=0$ ，即 $\begin{cases}3h\left ({x{{}_{A}}+x{{}_{B}}}\right )=0\\3h{^{2}}-\left ({x{{}_{A}^{2}}+x{{}_{B}^{2}}+x{{}_{A}}x{{}_{B}}}\right )=0\end{cases}$ ，
19. 由 $h\ne 0$ 得 $x{{}_{A}}=-x{{}_{B}}=\pm \sqrt {3}h$ ，
20. 不妨取 $x{{}_{A}}=-x{{}_{B}}=\sqrt {3}h$ ，
21. 所以 $A\left ({\sqrt {3}h{\rm{,}}-h}\right )$ ， $B\left ({-\sqrt {3}h{\rm{,}}-h}\right )$ ， $C\left ({0{\rm{,}}2h}\right )$ ，
22. 所以 $\left |{AB}\right |{^{2}}=12h{^{2}},\left |{AC}\right |{^{2}}=12h{^{2}},\left |{BC}\right |{^{2}}=12h{^{2}}$ ，即 $\left |{AB}\right |=\left |{BC}\right |=\left |{AC}\right |$ ，
23. 所以 $\vartriangle ABC$ 为等边三角形．

## 知识点

**中文**:
  - 与直线有关的新定义问题

**English**:
  - New Definition Problems

---
