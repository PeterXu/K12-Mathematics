# Mathematics - 题目 405

**ID**: 661737eb1d014f2ca5c166a425734182
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设O为坐标原点，点 $P\left ({2,4}\right ){\rm ，\mathit{A}，\mathit{B}}$ 为椭圆 $\frac {x{^{2}}}{4}+\frac {y{^{2}}}{2}=1$ 上的两个动点， $\overrightarrow {{OP}}=λ\left ({\overrightarrow {{OA}}+\overrightarrow {{OB}}}\right )$ （ $λ\in {\mathbf{R}}$ ）.​​​​​​​‌（1）证明：向量 $\overrightarrow m=\left ({1,-\frac {1}{4}}\right )$ 是直线AB的一个方向向量；（2）若线段OP与椭圆交于点Q，求 $\vartriangle ABQ$ 面积的最大值.

## 解答

1. （1）点 $P(2,4)$ 在椭圆外， $\mathrm{A}$ 、 $B$ 为椭圆上的两个动点，
2. 设 $A(x{{}_{1}},y{{}_{1}})$ 、 $B(x{{}_{2}},y{{}_{2}})$ ，
3. 此时 $\overrightarrow {{OP}}=λ(\overrightarrow {{OA}}+\overrightarrow {{OB}})=λ(x{{}_{1}}+x{{}_{2}},y{{}_{1}}+y{{}_{2}})(λ\in {\mathbf{R}})$ ，
4. 则 $\begin{cases}x{{}_{1}^{2}}+2y{{}_{1}^{2}}=4①\\x{{}_{2}^{2}}+2y{{}_{2}^{2}}=4②\end{cases}$ ，
5. $①-②$ 得 $(x{{}_{1}}+x{{}_{2}})(x{{}_{1}}-x{{}_{2}})+2(y{{}_{1}}+y{{}_{2}})(y{{}_{1}}-y{{}_{2}})=0$ ，
6. 即 $\frac {y{{}_{1}}-y{{}_{2}}}{x{{}_{1}}-x{{}_{2}}}=-\frac {x{{}_{1}}+x{{}_{2}}}{2(y{{}_{1}}+y{{}_{2}})}$ ，
7. 因为直线OP的斜率为 $\frac {y{{}_{1}}+y{{}_{2}}}{x{{}_{1}}+x{{}_{2}}}=\frac {4-0}{2-0}=2$ ，
8. 所以直线AB的斜率为 $\frac {y{{}_{1}}-y{{}_{2}}}{x{{}_{1}}-x{{}_{2}}}=-\frac {1}{4}$ ，
9. 所以直线AB的一个方向向量为 $(1,-\frac {1}{4})$ ，
10. （2）
11. 
12. 线段OP的方程为 $y=2x\left ({0\leqslant x\leqslant 2}\right )$ ，
13. 由 $\begin{cases}\frac {x{^{2}}}{4}+\frac {y{^{2}}}{2}=1\\y=2x\left ({0\leqslant x\leqslant 2}\right )\end{cases}\Rightarrow \begin{cases}x=\frac {2}{3}\\y=\frac {4}{3}\end{cases}$ ，即 $Q(\frac {2}{3},\frac {4}{3})$ ，
14. 由（1）知，直线AB的斜率为 $-\frac {1}{4}$ ，
15. 设直线AB方程为 $y=-\frac {1}{4}x+m$ ，
16. 若 $m=0$ ，此时直线AB过原点，
17. 所以 $\overrightarrow {{OA}}+\overrightarrow {{OB}}=0$ ，其与 $\overrightarrow {{OP}}=λ(\overrightarrow {{OA}}+\overrightarrow {{OB}})(λ\in {\mathbf{R}})$ 矛盾，
18. 所以 $m\ne 0$ ，联立 $\begin{cases}x{^{2}}+2y{^{2}}=4\\y=-\frac {1}{4}x+m\end{cases}$ ，消去 $y$ 并整理得
19. $9x{^{2}}-8mx+16m{^{2}}-32=0$ ，
20. $Δ=64m{^{2}}-4\times 9\times 16(m{^{2}}-2)=128(9-4m{^{2}})>0$ ，
21. 解得 $-\frac {3}{2}{\rm{<}}m{\rm{<}}0$ 或 $0{\rm{<}}m{\rm{<}}\frac {3}{2}$ ，
22. 由韦达定理得 $x{{}_{1}}+x{{}_{2}}=\frac {8}{9}m$ ， $x{{}_{1}}x{{}_{2}}=\frac {16}{9}(m{^{2}}-2)$ ，
23. 所以 $|AB|=\sqrt {1+(-\frac {1}{4}){^{2}}}\sqrt {(x{{}_{1}}+x{{}_{2}}){^{2}}-4x{{}_{1}}x{{}_{2}}}=\sqrt {\frac {17}{16}[\frac {64}{81}m{^{2}}-\frac {64}{9}(m{^{2}}-2)]}=\frac {2\sqrt {34}}{9}\sqrt {9-4m{^{2}}}$
24. $=\frac {2\sqrt {34}}{9}\sqrt {(3-2m)(3+2m)}$ ，
25. 又 $Q$ 到直线AB的距离 $d=\frac {|\frac {2}{3}+4\times \frac {4}{3}-4m|}{\sqrt {17}}=\frac {2}{\sqrt {17}}\sqrt {(3-2m){^{2}}}$ ，
26. 所以 $S{{}_{\vartriangle ABQ}}=\frac {1}{2}|AB|\cdot d=\frac {2\sqrt {2}}{9}\sqrt {(3-2m){^{3}}(3+2m)}$ ，
27. 令 $t=3-2m\in (0,3)\cup (3,6)$ ，
28. 可得 $3+2m=6-t$ ，设 $f(t)=t{^{3}}(6-t)=-t{^{4}}+6t{^{3}}$ ，
29. 可得 $f{^{\prime }}(t)=-4t{^{3}}+18t{^{2}}=-2t{^{2}}(2t-9)$ ，
30. 当 $t\in (0,3)\cup (3,\frac {9}{2})$ 时， $f^{′}(t)>0$ ， $f(t)$ 在 $\left ({0,3}\right ),\left ({3,\frac {9}{2}}\right )$ 单调递增；
31. 当 $\frac {9}{2}<t<6$ 时， $f^{′}(t)<0$ ， $f(t)$ 在 $\left ({\frac {9}{2},6}\right )$ 单调递减,
32. 则当 $t=\frac {9}{2}$ 时，即 $m=-\frac {3}{4}$ 时， $S{{}_{\mathrm{△}ABQ}}$ 取得最大值，最大值为 $\frac {3\sqrt {6}}{2}$ .

## 知识点

**中文**:
  - 平面向量的坐标运算
  - 直线与椭圆的位置关系
  - 弦长面积问题
  - 范围最值问题

**English**:
  - Coordinate Operations
  - Line-Ellipse Relationship
  - Chord Length and Area Problems
  - Range and Extrema Problems

---
