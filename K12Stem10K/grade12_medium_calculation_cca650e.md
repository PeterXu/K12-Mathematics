# Mathematics - 题目 3945

**ID**: cca650ea64104ae591038bd22096bd62
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
已知焦点在 $x$ 轴上的椭圆 $C:\frac {x{^{2}}}{4}+\frac {y{^{2}}}{b{^{2}}}=1\left ({b>0}\right )$ ，点 $P$ ， $Q$ 是椭圆 $C$ 上的两点，且位于 $x$ 轴上方， $T\left ({t,0}\right )$ 为 $x$ 轴上一点， $O$ 为坐标原点．（1）当点 $Q$ 在 $y$ 轴上， $t=1$ ，且 $\vartriangle QOT$ 的面积为 $\frac {\sqrt {3}}{2}$ 时，求椭圆 $C$ 的离心率；​​​​​​​‌（2）若点 $P$ 在第一象限， $\mathrm{A}$ ， $B$ 分别为椭圆的上顶点和右顶点，直线 $PA$ ， $PB$ 分别与 $x$ 轴和 $y$ 轴交于点 $M$ ， $N$ ．记 $\vartriangle PMN$ ， $\vartriangle PAB$ 的面积分别为 $S{{}_{1}}$ 、 $S{{}_{2}}$ ，若 $S{{}_{1}}-S{{}_{2}}$ 为定值2，求椭圆 $C$ 的标准方程；（3）对于（2）所求的椭圆 $C$ ，是否存在实数 $t$ ，使得 $\vartriangle TPQ$ 是以 $T$ 为直角顶点的等腰直角三角形？若存在，求 $t$ 的取值范围；若不存在，请说明理由．

## 解答

1. （1）由题意知 $Q\left ({0,b}\right ),T\left ({t,0}\right )$ ，
2. 由 $\vartriangle QOT$ 的面积为 $\frac {\sqrt {3}}{2}$ ，得 $\frac {1}{2}\times b\times 1=\frac {\sqrt {3}}{2}$ ，则 $b=\sqrt {3}$ ，
3. 而 $a=2$ ，故 $c=\sqrt {a{^{2}}-b{^{2}}}=\sqrt {4-3}=1$ ，
4. 所以椭圆 $C$ 的离心率为 $e=\frac {c}{a}=\frac {1}{2}$ ；
5. （2）设 $P\left ({x{{}_{0}},y{{}_{0}}}\right )$ ，由题意知 $A\left ({0,b}\right ),B\left ({2,0}\right )$ ，
6. 则直线 $PA$ 的方程为： $y=\frac {y{{}_{0}}-b}{x{{}_{0}}}\times x+b$ ，令 $y=0$ ，则 $x=\frac {bx{{}_{0}}}{b-y{{}_{0}}}$ ，
7. 即得 $M\left ({\frac {bx{{}_{0}}}{b-y{{}_{0}}},0}\right )$ ，
8. 直线 $PB$ 的方程为： $y=\frac {y{{}_{0}}}{x{{}_{0}}-2}\times \left ({x-2}\right )$ ，令 $x=0$ ，则 $y=\frac {2y{{}_{0}}}{2-x{{}_{0}}}$ ，
9. 即得 $N\left ({0,\frac {2y{{}_{0}}}{2-x{{}_{0}}}}\right )$ ，
10. 故 $S{{}_{1}}-S{{}_{2}}=S{{}_{\vartriangle PMN}}-S{{}_{\vartriangle PAB}}=S{{}_{\vartriangle MBN}}-S{{}_{\vartriangle MBA}}=\frac {1}{2}\left |{BM}\right |\left ({\left |{ON}\right |-\left |{OA}\right |}\right )=\frac {1}{2}\left |{BM}\right |\left |{AN}\right |=2$ ，
11. 即 $\frac {1}{2}\left ({\frac {bx{{}_{0}}}{b-y{{}_{0}}}-2}\right )\left ({\frac {2y{{}_{0}}}{2-x{{}_{0}}}-b}\right )=2$ ，即得 $\frac {{\left({bx{{}_{0}}+2y{{}_{0}}-2b}\right)^{2}}}{\left ({b-y{{}_{0}}}\right )\left ({2-x{{}_{0}}}\right )}=4$ ，
12. 则 $\frac {b{^{2}}x{{}_{0}^{2}}+4y{{}_{0}^{2}}+4b{^{2}}+4bx{{}_{0}}y{{}_{0}}-4b{^{2}}x{{}_{0}}-8by{{}_{0}}}{x{{}_{0}}y{{}_{0}}-bx{{}_{0}}-2y{{}_{0}}+2b}=4$ ，
13. 又 $b{^{2}}x{{}_{0}^{2}}+4y{{}_{0}^{2}}=4b{^{2}}$ ，故 $\frac {4bx{{}_{0}}y{{}_{0}}-4b{^{2}}x{{}_{0}}-8by{{}_{0}}+8b{^{2}}}{x{{}_{0}}y{{}_{0}}-bx{{}_{0}}-2y{{}_{0}}+2b}=4$ ，
14. 即 $4b=4,\therefore b=1$ ，
15. 故椭圆 $C$ 的标准方程为 $\frac {x{^{2}}}{4}+y{^{2}}=1$ ；
16. 
17. （3）假设存在实数 $t$ ，使得 $\vartriangle TPQ$ 是以 $T$ 为直角顶点的等腰直角三角形，
18. 由题意知，直线 $PQ$ 的斜率存在，设其方程为 $y=kx+m$ ，设 $P\left ({x{{}_{1}},y{{}_{1}}}\right ),Q\left ({x{{}_{2}},y{{}_{2}}}\right ),y{{}_{1}}>0,y{{}_{2}}>0$ ，
19. 联立 $\begin{cases}y=kx+m\\\frac {x{^{2}}}{4}+y{^{2}}=1\end{cases}$ ，得 $\left ({1+4k{^{2}}}\right )x{^{2}}+8kmx+4m{^{2}}-4=0$ ，
20. 由 ${\rm{Δ}}=64k{^{2}}m{^{2}}-16\left ({m{^{2}}-1}\right )\left ({1+4k{^{2}}}\right )=64k{^{2}}-16m{^{2}}+16>0$ ，得 $4k{^{2}}>m{^{2}}-1$ ，
21. 则 $x{{}_{1}}+x{{}_{2}}=-\frac {8km}{1+4k{^{2}}},x{{}_{1}}x{{}_{2}}=\frac {4\left ({m{^{2}}-1}\right )}{1+4k{^{2}}},\therefore y{{}_{1}}+y{{}_{2}}=k\left ({x{{}_{1}}+x{{}_{2}}}\right )+2m=\frac {2m}{1+4k{^{2}}}>0$ ，
22. $y{{}_{1}}y{{}_{2}}=k{^{2}}x{{}_{1}}x{{}_{2}}+km\left ({x{{}_{1}}+x{{}_{2}}}\right )+m{^{2}}=\frac {4k{^{2}}m{^{2}}-4k{^{2}}}{1+4k{^{2}}}-\frac {8k{^{2}}m{^{2}}}{1+4k{^{2}}}+m{^{2}}=\frac {m{^{2}}-4k{^{2}}}{1+4k{^{2}}}>0$ ，
23. 故 $m{^{2}}>4k{^{2}}$ 且 $m>0$ ，故 $\sqrt {4k{^{2}}+1}>m>2|k|\geqslant 0$ ，
24. 当 $k=0$ 时， $y{{}_{1}}=y{{}_{2}}=m$ 且 $|x{{}_{1}}|=|x{{}_{2}}|=m$ ，则 $m=\frac {2\sqrt {5}}{5}\in \left ({0,1}\right )$ ，
25. 此时 $T\left ({0,0}\right )$ ，满足题意；
26. 当 $k\ne 0$ 时， $PQ$ 的中点为 $A\left ({-\frac {4km}{1+4k{^{2}}},\frac {m}{1+4k{^{2}}}}\right )$ ，又 $T\left ({t,0}\right )$ ，
27. 故 $k{{}_{TA}}=\frac {\frac {m}{1+4k{^{2}}}-0}{-\frac {4km}{1+4k{^{2}}}-t}=-\frac {1}{k}$ ，则 $t=-\frac {3km}{1+4k{^{2}}}$ ，
28. $\overrightarrow {{TP}}\cdot \overrightarrow {{TQ}}=\left ({x{{}_{1}}-t}\right )\left ({x{{}_{2}}-t}\right )+y{{}_{1}}y{{}_{2}}=x{{}_{1}}x{{}_{2}}-t\left ({x{{}_{1}}+x{{}_{2}}}\right )+t{^{2}}+y{{}_{1}}y{{}_{2}}=0$
29. 则 $\frac {4\left ({m{^{2}}-1}\right )}{1+4k{^{2}}}+\frac {8kmt}{1+4k{^{2}}}+t{^{2}}+\frac {m{^{2}}-4k{^{2}}}{1+4k{^{2}}}=\frac {5m{^{2}}-4k{^{2}}-4}{1+4k{^{2}}}+\frac {8kmt}{1+4k{^{2}}}+t{^{2}}=0$ ，
30. 则 $5m{^{2}}-4k{^{2}}-4+8kmt+\left ({1+4k{^{2}}}\right )t{^{2}}=0$ ，
31. 即 $5m{^{2}}\left ({1+k{^{2}}}\right )=4\left ({4k{^{4}}+1}\right )\left ({1+k{^{2}}}\right ),\therefore m{^{2}}=\frac {4}{5}\left ({4k{^{2}}+1}\right )$ ，
32. 结合 $m{^{2}}>4k{^{2}}$ ，则 $\frac {4}{5}\left ({4k{^{2}}+1}\right )>4k{^{2}},\therefore 0<k{^{2}}<1$ ，
33. 则 $t{^{2}}=\frac {9k{^{2}}m{^{2}}}{{\left({1+4k{^{2}}}\right)^{2}}}=\frac {36}{\frac {5}{k{^{2}}}+20}$ ，故 $t{^{2}}\in \left ({0,\frac {36}{25}}\right )$ ，
34. 故 $t\in \left ({-\frac {6}{5},0}\right )\cup \left ({0,\frac {6}{5}}\right )$ ;
35. 综合上述可知存在实数 $t$ ，使得 $\vartriangle TPQ$ 是以 $T$ 为直角顶点的等腰直角三角形， $t\in \left ({-\frac {6}{5},\frac {6}{5}}\right )$ .

## 知识点

**中文**:
  - 存在性或者探究性问题
  - 椭圆的离心率
  - 直线与椭圆的位置关系

**English**:
  - Existence and Inquiry Problems
  - Eccentricity
  - Line-Ellipse Relationship

---
