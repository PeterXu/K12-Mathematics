# Mathematics - 题目 2576

**ID**: 15974ac46cd644e492a30dbd47d6bd8d
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知 ${\rm{i}}$ 为虚数单位，定义 $x{^{n}}=1$ 的解称为 $n$ 次单位根或单位根，这 $n$ 个单位根分别为 $ω{{}_{{\rm i}}}={\cos}\frac {2k{\rm{π}}}{n}+{\rm i}\cdot \sin \frac {2k{\rm{π}}}{n},\left ({k=0,1,2,\cdots ,n-1}\right )$ ．复数单位根在代数、分析、信号处理和几何学等领域都有广泛的应用．例如在平面几何中，记 $\overrightarrow {{OZ{{}_{1}}}}$ 对应的复数为 $z{{}_{1}}=r\left ({{\cos}α+i\sin α}\right )$ ，将 $\overrightarrow {{OZ{{}_{1}}}}$ 绕原点 $O$ 逆时针旋转 $\frac {2k{\rm{π}}}{n}$ 得到 $\overrightarrow {{OZ{{}_{2}}}}$ ，则 $\overrightarrow {{OZ{{}_{2}}}}$ 对应的复数为 $z{{}_{2}}=z{{}_{1}}ω{{}_{i}}=r\left [{\cos}\left ({α+\frac {2k{\rm{π}}}{n}}\right )+i\sin \left ({α+\frac {2k{\rm{π}}}{n}}\right )\right ]$ ．此外，在数字信号处理中，单位根用于设计滤波器，以选择或抑制特定频率的示性信号．（1）方程 $x{^{2}}+x+1=0$ 在复数域上的两根为 $z{{}_{1}},z{{}_{2}}$ ，将 $z{{}_{1}},z{{}_{2}}$ 对应的向量 $\overrightarrow {{OZ{{}_{1}}}},\overrightarrow {{OZ{{}_{2}}}}$ 逆时针旋转 $\frac {{\rm{π}}}{2}$ 后得到 $\overrightarrow {{OZ{{}_{3}}}},\overrightarrow {{OZ{{}_{4}}}}$ ，记 $\overrightarrow {{OZ{{}_{3}}}},\overrightarrow {{OZ{{}_{4}}}}$ 对应的复数为 $z{{}_{3}},z{{}_{4}}$ ，请求出 $z{{}_{1}},z{{}_{2}},z{{}_{3}},z{{}_{4}}$ （结果用代数形式表示）；​​​​​​​‌（2）已知定义在整数集上的示性函数 $f\left ({x}\right )=\begin{cases}1,x=3k\left ({k\in {\rm{Z}}}\right )\\ω,x=3k+1\left ({k\in {\rm{Z}}}\right )\\ω{^{2}},x=3k+2\left ({k\in {\rm{Z}}}\right )\end{cases}\left ({ω={\cos}\frac {2{\rm{π}}}{3}+{\rm{i}}\cdot \sin \frac {2{\rm{π}}}{3}}\right )$ ，在复平面上的正三角形 $\vartriangle ABC$ 顶点 $A,\,B,\,C$ 三点分别对应的复数为 $α,β,γ$ ，若存在 $x{{}_{1}},x{{}_{2}},x{{}_{3}}\in \left \{0,1,\cdots ,9\right \}$ 使得 $f\left ({x{{}_{1}}}\right )α+f\left ({x{{}_{2}}}\right )β+f\left ({x{{}_{3}}}\right )γ=0$ ，则称 $n=100x{{}_{1}}+10x{{}_{2}}+x{{}_{3}}$ 为正三角形数．若 $n$ 为正三角形数，求 $f\left ({n}\right )$ ；（3）一个圆环上系有 $n\left ({n\geqslant 6}\right )$ 个绳结，且圆环上每个绳结的位置都不相同，现有两种打结方式分别可以得到 $A,B$ 型绳结，每个绳结等可能地采用两种打结方式．记顺序相邻的5个绳结中恰有1，2，3，4个 $\mathrm{A}$ 型绳结的组数分别为 $a,b,c,d$ ，证明： $3a+b-c-3d$ 是5的倍数．

## 解答

1. （1）对于 $x{^{2}}+x+1=0$ ，它的两个根为 $\frac {-1\pm \sqrt {3}{\rm{i}}}{2}$ ，
2. 不妨设 $z{{}_{1}}=\frac {-1+\sqrt {3}{\rm{i}}}{2}={\cos}\frac {2{\rm{π}}}{3}+{\rm{i}}\sin \frac {2{\rm{π}}}{3},z{{}_{2}}=\frac {-1-\sqrt {3}{\rm{i}}}{2}={\cos}\frac {{{4}}{\rm{π}}}{3}+{\rm{i}}\sin \frac {{{4}}{\rm{π}}}{3}$ ，
3. 从而 $z{{}_{3}}={\cos}\left ({\frac {2{\rm{π}}}{3}+\frac {{\rm{π}}}{2}}\right )+{\rm{i}}\sin \left ({\frac {2{\rm{π}}}{3}+\frac {{\rm{π}}}{2}}\right )=-\frac {\sqrt {3}+{\rm{i}}}{2},z{{}_{4}}={\cos}\left ({\frac {{{4}}{\rm{π}}}{3}+\frac {{\rm{π}}}{2}}\right )+{\rm{i}}\sin \left ({\frac {{{4}}{\rm{π}}}{3}+\frac {{\rm{π}}}{2}}\right )=\frac {\sqrt {3}-{\rm{i}}}{2}$ ；
4. （2）由题意不妨设正 $\vartriangle ABC$ 的边长为 $\sqrt {3}$ ，它的三个顶点分别为 $A\left ({1,0}\right ),B\left ({-\frac {1}{2},\frac {\sqrt {3}}{2}}\right ),C\left ({-\frac {1}{2},-\frac {\sqrt {3}}{2}}\right )$ ，
5. 则 $α=1,β=ω,γ=ω{^{2}}$ ，
6. 若存在 $x{{}_{1}},x{{}_{2}},x{{}_{3}}\in \left \{0,1,\cdots ,9\right \}$ 使得 $f\left ({x{{}_{1}}}\right )α+f\left ({x{{}_{2}}}\right )β+f\left ({x{{}_{3}}}\right )γ=0$ ，
7. 即若存在 $x{{}_{1}},x{{}_{2}},x{{}_{3}}\in \left \{0,1,\cdots ,9\right \}$ 使得 $f\left ({x{{}_{1}}}\right )\cdot 1+f\left ({x{{}_{2}}}\right )ω+f\left ({x{{}_{3}}}\right )ω{^{2}}=0$ ，
8. 注意到 $ω{^{2}}+ω+1=0$ ，从而有 $ω{^{3}}=ω\left ({-ω-1}\right )=-ω{^{2}}-ω=1,ω{^{4}}=ω$ ，
9. 对 $f\left ({x{{}_{1}}}\right )\cdot 1+f\left ({x{{}_{2}}}\right )ω+f\left ({x{{}_{3}}}\right )ω{^{2}}=0$ 两边同时乘以 $ω$ ，可得 $f\left ({x{{}_{1}}}\right )\cdot ω+f\left ({x{{}_{2}}}\right )ω{^{2}}+f\left ({x{{}_{3}}}\right )\cdot 1=0$ ；
10. 对 $f\left ({x{{}_{1}}}\right )\cdot 1+f\left ({x{{}_{2}}}\right )ω+f\left ({x{{}_{3}}}\right )ω{^{2}}=0$ 两边同时乘以 $ω{^{2}}$ ，可得 $f\left ({x{{}_{1}}}\right )\cdot ω{^{2}}+f\left ({x{{}_{2}}}\right )\cdot 1+f\left ({x{{}_{3}}}\right )ω=0$ ，
11. 观察发现 $f\left ({x{{}_{1}}}\right ),f\left ({x{{}_{2}}}\right ),f\left ({x{{}_{3}}}\right )$ 具有轮换对称性，从而地位一样，
12. 故 $f\left ({x{{}_{1}}}\right )=f\left ({x{{}_{2}}}\right )=f\left ({x{{}_{3}}}\right )$ ，
13. 又因为 $f\left ({x{{}_{1}}}\right ),f\left ({x{{}_{2}}}\right ),f\left ({x{{}_{3}}}\right )\in \left \{1,ω,ω{^{2}}\right \}$ ，
14. 所以 $f\left ({x{{}_{1}}}\right )=f\left ({x{{}_{2}}}\right )=f\left ({x{{}_{3}}}\right )=1,ω,ω{^{2}}$ ，
15. 当 $f\left ({x{{}_{1}}}\right )=f\left ({x{{}_{2}}}\right )=f\left ({x{{}_{3}}}\right )=1$ 时，
16. 设 $x{{}_{1}}=3k{{}_{1}},x{{}_{2}}=3k{{}_{2}},x{{}_{3}}=3k{{}_{3}},x{{}_{1}},x{{}_{2}},x{{}_{3}}\in \left \{0,1,\cdots ,9\right \},k{{}_{1}},k{{}_{2}},k{{}_{3}}\in {\rm{Z}}$ ，
17. 此时 $f\left ({n}\right )=f\left ({100x{{}_{1}}+10x{{}_{2}}+x{{}_{3}}}\right )=f\left ({x{{}_{1}}+x{{}_{2}}+x{{}_{3}}}\right )=f\left ({3\left ({k{{}_{1}}+k{{}_{2}}+k{{}_{3}}}\right )}\right )=1$ ；
18. 当 $f\left ({x{{}_{1}}}\right )=f\left ({x{{}_{2}}}\right )=f\left ({x{{}_{3}}}\right )=ω$ 时，
19. 设 $x{{}_{1}}=3k{{}_{1}}+1,x{{}_{2}}=3k{{}_{2}}+1,x{{}_{3}}=3k{{}_{3}}+1,x{{}_{1}},x{{}_{2}},x{{}_{3}}\in \left \{0,1,\cdots ,9\right \},k{{}_{1}},k{{}_{2}},k{{}_{3}}\in {\rm{Z}}$ ，
20. 此时 $f\left ({n}\right )=f\left ({100x{{}_{1}}+10x{{}_{2}}+x{{}_{3}}}\right )=f\left ({x{{}_{1}}+x{{}_{2}}+x{{}_{3}}}\right )=f\left ({3\left ({k{{}_{1}}+k{{}_{2}}+k{{}_{3}}+1}\right )}\right )=1$ ；
21. 当 $f\left ({x{{}_{1}}}\right )=f\left ({x{{}_{2}}}\right )=f\left ({x{{}_{3}}}\right )=ω{^{2}}$ 时，
22. 设 $x{{}_{1}}=3k{{}_{1}}+2,x{{}_{2}}=3k{{}_{2}}+2,x{{}_{3}}=3k{{}_{3}}+2,x{{}_{1}},x{{}_{2}},x{{}_{3}}\in \left \{0,1,\cdots ,9\right \},k{{}_{1}},k{{}_{2}},k{{}_{3}}\in {\rm{Z}}$ ，
23. 此时 $f\left ({n}\right )=f\left ({100x{{}_{1}}+10x{{}_{2}}+x{{}_{3}}}\right )=f\left ({x{{}_{1}}+x{{}_{2}}+x{{}_{3}}}\right )=f\left ({3\left ({k{{}_{1}}+k{{}_{2}}+k{{}_{3}}+2}\right )}\right )=1$ ；
24. 综上所述， $f\left ({n}\right )=1$ ；
25. （3）为了方便起见，记顺序相邻的5个绳结中恰有1，2，3，4个 $\mathrm{A}$ 型绳结的组数分别为 $a{{}_{1}},a{{}_{2}},a{{}_{3}},a{{}_{4}}$ ，
26. 故只需证明 $3a{{}_{1}}+a{{}_{2}}-a{{}_{3}}-3a{{}_{4}}$ 是五的倍数，
27. 所以 $3a{{}_{1}}+a{{}_{2}}-a{{}_{3}}-3a{{}_{4}}=\sum \limits_{k=1}^{4}\mathop{\left ({5-2k}\right )a{{}_{k}}}=5\sum \limits_{k=1}^{4}\mathop{a{{}_{k}}}-2\sum \limits_{k=1}^{4}\mathop{ka{{}_{k}}}$ ，
28. 设圆环上总共有 $m$ 个 $\mathrm{A}$ 型绳结，由于每个 $\mathrm{A}$ 型绳结属于5个不同的顺序相邻的5个绳结组，
29. 故所有顺序相邻的5个绳结组中绳结 $\mathrm{A}$ 的总数为 $\sum \limits_{k=1}^{5}\mathop{ka{{}_{k}}}=5m$ ，其中 $a{{}_{5}}$ 表示顺序相邻的5个绳结中全是绳结 $\mathrm{A}$ 的绳结组的组数，
30. 所以 $\sum \limits_{k=1}^{4}\mathop{ka{{}_{k}}}=5\left ({m-a{{}_{5}}}\right )$ ，也就是说 $\sum \limits_{k=1}^{4}\mathop{ka{{}_{k}}}$ 是5的倍数，
31. 又因为 $5\sum \limits_{k=1}^{4}\mathop{a{{}_{k}}}$ 也是5的倍数，
32. 从而 $3a{{}_{1}}+a{{}_{2}}-a{{}_{3}}-3a{{}_{4}}=\sum \limits_{k=1}^{4}\mathop{\left ({5-2k}\right )a{{}_{k}}}=5\sum \limits_{k=1}^{4}\mathop{a{{}_{k}}}-2\sum \limits_{k=1}^{4}\mathop{ka{{}_{k}}}$ 是5的倍数，命题得证.

## 知识点

**中文**:
  - 复数新定义问题

**English**:
  - New Definition Problems in Complex Numbers

---
