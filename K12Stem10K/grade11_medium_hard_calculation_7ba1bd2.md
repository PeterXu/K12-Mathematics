# Mathematics - 题目 3145

**ID**: 7ba1bd2b945748d08c9e940b66f9f53c
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
在平面直角坐标系xOy中，定义向量 $\overrightarrow {{OA}}=\left ({m,n}\right )$ 为函数 $f\left ({x}\right )=m\sin x+n{\cos}x$ 的有序相伴向量.​​​​​​​‌（1）设 $h\left ({x}\right )=2\sin \left ({x+\frac {{\rm{π}}}{6}}\right )$ （ $x\in {\mathbf{R}}$ ），写出函数 $h\left ({x}\right )$ 的有序相伴向量 $\overrightarrow {{OM}}$ ；（2）若 $f\left ({x}\right )$ 的有序相伴向量为 $\overrightarrow {{OB}}=\left ({0,2}\right )$ ，若函数 $h\left ({x}\right )=f\left ({x}\right )+\left |{\sin x}\right |$ ， $x\in \left [0,2{\rm{π}}\right ]$ ，与直线 $y=k$ 有且仅有二个不同的交点，求实数k的取值范围；（3）若 $f\left ({x}\right )$ 的有序相伴向量为 $\overrightarrow {{OB}}=\left ({m,0}\right )$ ，当函数 $f\left ({x}\right )$ 在区间 $\left [a,b\right ]$ 上时值域为 $\left [a,b\right ]$ ，则称区间 $\left [a,b\right ]$ 为函数的“和谐区间”.当 $m=\mathrm{-}2$ 时， $f\left ({x}\right )$ 是否存在“和谐区间”？若存在，求出 $f\left ({x}\right )$ 的所有“和谐区间”，若不存在，请说明理由.

## 解答

1. （1）因为 $h\left ({x}\right )=2\sin \left ({x+\frac {{\rm{π}}}{6}}\right )=2\left ({\frac {\sqrt {3}}{2}\sin x+\frac {1}{2}{\cos}x}\right )=\sqrt {3}\sin x+{\cos}x$ ，
2. 所以函数 $h\left ({x}\right )$ 的有序相伴向量 $\overrightarrow {{OM}}=\left ({\sqrt {3},1}\right )$ ；
3. （2）若 $f\left ({x}\right )$ 的有序相伴向量为 $\overrightarrow {{OB}}=\left ({0,2}\right )$ ，则 $f\left ({x}\right )=2{\cos}x$ ，
4. 所以 $h\left ({x}\right )=f\left ({x}\right )+\left |{\sin x}\right |=2{\cos}x+\left |{\sin x}\right |=\begin{cases}2{\cos}x+\sin x,x\in \left [0,{\rm{π}}\right ]\\2{\cos}x-\sin x,x\in \left ({{\rm{π}},2{\rm{π}}}\right ]\end{cases}$
5. $=\begin{cases}\sqrt {5}\sin \left ({x+φ}\right ),x\in \left [0,{\rm{π}}\right ]\\-\sqrt {5}\sin \left ({x-φ}\right ),x\in \left ({{\rm{π}},2{\rm{π}}}\right ]\end{cases}$ ，其中 $φ\in \left [0,\frac {{\rm{π}}}{2}\right ]$ ， ${\tan}φ=2$ ，
6. 如图所示为 $h\left ({x}\right )$ 的草图：
7. $h\left ({0}\right )=2$ ， $h\left ({x}\right ){{}_{{\rm \max }}}=\sqrt {5}$ ， $h\left ({{\rm{π}}}\right )=-2$ ，
8. 由图象可知，若函数 $h\left ({x}\right )$ 与直线 $y=k$ 有且仅有2个不同的交点，
9. 则 $k=\sqrt {5}$ 或 $-{{2}}{\rm{<}}k{\rm{<}}{{2}}$ ，所以 $k\in \left ({-2,2}\right )\cup \left \{\sqrt {5}\right \}$ ；
10. （3） $f\left ({x}\right )$ 有唯一“和谐区间” $\left [-2,2\right ]$ ，理由如下：
11. $f\left ({x}\right )=-2\sin x$ ，假设 $f\left ({x}\right )$ 存在“和谐区间”，
12. 则由 $-2\leqslant f\left ({x}\right )\leqslant 2$ ，得 $-2\mathrm{\leqslant }a\mathrm{\leqslant }b\mathrm{\leqslant }2$ ，
13. ①若 ${\rm \mathit{a}，}b\geqslant 0$ ，则由 $\left [a,b\right ]\subseteq \left [{0,{\rm{π}}}\right )$ ，知 $f\left ({x}\right )\leqslant 0$ ，与值域 $\left [a,b\right ]\subseteq \left [{0,{\rm{π}}}\right )$ 矛盾，
14. 故不存在“和谐区间”；
15. ②同理 ${\rm \mathit{a}，}b<0$ 时，由 $\left [a,b\right ]\subseteq \left ({-{\rm{π}},0}\right ]$ ，知 $f\left ({x}\right )\geqslant 0$ ，与值域 $\left [a,b\right ]\subseteq \left ({-{\rm{π}},0}\right ]$ 矛盾，
16. 故不存在“和谐区间”；
17. 下面讨论 $a\mathrm{\leqslant }0\mathrm{\leqslant }b$ ，
18. ③若 $b\geqslant \frac {{\rm{π}}}{2}$ ，则 $\left [0,\frac {{\rm{π}}}{2}\right ]\subseteq \left [a,b\right ]$ ，故 $f\left ({x}\right )$ 的最小值为 $-2$ ，于是 $a=-2$ ，
19. 所以 $\left [-\frac {{\rm{π}}}{2},\frac {{\rm{π}}}{2}\right ]\subseteq \left [a,b\right ]$ ，所以 $f\left ({x}\right )$ 的最大值为2，故 $b=2$ ，
20. 此时 $f\left ({x}\right )$ 的定义域为 $\left [-2,2\right ]$ ，值域为 $\left [-2,2\right ]$ ，符合题意；
21. ④若 $0\leqslant b<\frac {{\rm{π}}}{2}$ ，当 $a\leqslant -\frac {{\rm{π}}}{2}$ 时，同理可得 $b=2$ ， $a=-2$ ，但此时 $b>\frac {{\rm{π}}}{2}$ ，舍去；
22. 当 $a>-\frac {{\rm{π}}}{2}$ 时， $f\left ({x}\right )$ 在 $\left [a,b\right ]$ 上单调递减，所以 $a=-2\sin b$ ， $b=-2\sin a$ ，
23. 于是 $a+2\sin a=-\left ({b+2\sin b}\right )$ ，
24. 令 $g\left ({x}\right )=x+2\sin x$ ，则有 $g\left ({a}\right )=-g\left ({b}\right )$ ，
25. 又 $g\left ({x}\right )=x+2\sin x$ 为奇函数，且在 $\left [-\frac {{\rm{π}}}{2},\frac {{\rm{π}}}{2}\right ]$ 单调递增，
26. 所以 $a=-b$ ，所以 $a=-2\sin b=-2\sin \left ({-a}\right )=2\sin a$
27. 即 $\frac {a}{2}=\sin a$ ，同一坐标系内，画出图象 $y=\sin x$ 与 $y=\frac {x}{2}$ ，如下：
28. 
29. 可知，当 $x\in \left ({0,\frac {{\rm{π}}}{2}}\right )$ 时， $\sin x>\frac {x}{2}$ ，
30. 所以 $a=0$ ，从而 $b=0$ ，矛盾．
31. 综上所述， $f\left ({x}\right )$ 有唯一“和谐区间” $\left [-2,2\right ]$ ．

## 知识点

**中文**:
  - 平面向量的新定义问题

**English**:
  - New Definition Problems

---
