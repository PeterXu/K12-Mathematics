# Mathematics - 题目 1212

**ID**: 6c05b7cc3e4c4fceb710482168d952ab
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
记 $A=\left \{l\left ({x}\right )\left |{l\left ({x}\right )=kx+m,k,m\in {\rm{R}}}\right .​​​​​​​‌\right \}$ ，若 $l{{}_{0}}\left ({x}\right )\in A$ ，满足：对任意 $l\left ({x}\right )\in A$ ，均有 ${\mathop {{\rm \max }}\limits_{x\in [a,b]}^{}}|f(x)-l(x)|\geqslant {\mathop {{\rm \max }}\limits_{x\in [a,b]}^{}}|f(x)-l{{}_{0}}(x)|$ ，则称 $l{{}_{0}}\left ({x}\right )$ 为函数 $f\left ({x}\right )$ 在 $x\in \left [a,b\right ]$ 上“最接近”直线．已知函数 $g\left ({x}\right )=2{\rm{l}}{\rm{n}}x-x{^{2}}+3，x\in \left [r,s\right ]$ ．(1)若 $g\left ({r}\right )=g\left ({s}\right )=0$ ，证明：对任意 $l\left ({x}\right )\in A，{\rm{m}}{\rm{a}}{\rm{x}}\left |{g\left ({x}\right )-l\left ({x}\right )}\right |\geqslant 1$ ；(2)若 $r=1，s=2$ ，证明： $g\left ({x}\right )$ 在 $x\in \left [1,2\right ]$ 上的“最接近”直线为： $l{{}_{0}}\left ({x}\right )=\left ({2{\rm{l}}{\rm{n}}2-3}\right )\left ({x-\frac {1+x{{}_{0}}}{2}}\right )+\frac {2+g\left ({x{{}_{0}}}\right )}{2}$ ，其中 $x{{}_{0}}\in \left ({1,2}\right )$ 且为二次方程 $2x{^{2}}+\left ({2{\rm{l}}{\rm{n}}2-3}\right )x-2=0$ 的根．

## 解答

1. （1）由题意 $g^{′}{\left ({x}\right )}=\frac {2}{x}-2x=\frac {2\left ({1+x}\right )\left ({1-x}\right )}{x}$ ，
2. 则当 $x\in \left ({0,1}\right )$ 时， $g^{′}{\left ({x}\right )}>0$ ， $g\left ({x}\right )$ 在区间 $\left ({0,1}\right )$ 上单调递增，
3. 当 $x\in \left ({1,+∞}\right )$ 时， $g^{′}{\left ({x}\right )}<0$ ， $g\left ({x}\right )$ 在区间 $\left ({1,+∞}\right )$ 上单调递减，
4. 又 $g\left ({r}\right )=g\left ({s}\right )=0$ ， $\therefore 0<r<1<s$ ，
5. $\therefore g\left ({x}\right )$ 在区间 $\left [r,s\right ]$ 上的最大值为 $g{{}_{{\rm \max }}}\left ({x}\right )=g\left ({1}\right )=2$ ，
6. 根据函数 $g\left ({x}\right )$ 的图象特点，可知对任意 $l\left ({x}\right )\in A$ ，均有
7. ${\mathop {{\rm \max }}\limits_{x\in [r,s]}^{}}\left |{g(x)-l(x)}\right |\geqslant {\mathop {{\rm \max }}\limits_{x\in [r,s]}^{}}\left \{\left |{g(r)-l(r)}\right |,\left |{g(s)-l(s)}\right |,\left |{g(1)-l(1)}\right |\right \}$ ，
8. $={\mathop {{\rm \max }}\limits_{x\in \left [r,s\right ]}^{}}\left \{\left |{l\left ({r}\right )}\right |,\left |{l\left ({s}\right )}\right |,\left |{2-l\left ({1}\right )}\right |\right \}$ ，
9. 下面讨论 $\left |{l\left ({r}\right )}\right |,\left |{l\left ({s}\right )}\right |$ 的大小：
10. ①若 $\left |{l\left ({r}\right )}\right |,\left |{l\left ({s}\right )}\right |$ 至少有一个大于等于1，则 ${\mathop {{\rm \max }}\limits_{x\in [r,s]}^{}}|g(x)-l(x)|\geqslant 1$ ，
11. ②若 $\left |{l\left ({r}\right )}\right |,\left |{l\left ({s}\right )}\right |$ 两个都小于1，则 $l\left ({r}\right )<1,l\left ({s}\right )<1$ ，
12. 因为 $l\left ({x}\right )$ 是直线，故对任意 $x\in \left [r,s\right ]$ ，均有 $l\left ({x}\right )<1$ ， $\therefore l\left ({1}\right )<1$ ，从而 $\left |{2-l\left ({1}\right )}\right |>1$ ，
13. 即 ${\mathop {{\rm \max }}\limits_{x\in [r,s]}^{}}\left |{g(x)-l(x)}\right |\geqslant {\mathop {{\rm \max }}\limits_{x\in [r,s]}^{}}\left \{\left |{l(r)}\right |,\left |{l\left ({s}\right )}\right |,\left |{2-l\left ({1}\right )}\right |\right \}>1$
14. 由①②可知， ${\mathop {{\rm \max }}\limits_{x\in [r,s]}^{}}\left \{\left |{g(r)-l(r)}\right |,\left |{g(s)-l(s)}\right |,\left |{g(1)-l(1)}\right |\right \}\geqslant 1$ ，
15. 当 $l\left ({x}\right )=\frac {g\left ({1}\right )}{2}=1$ 时，
16. ${\mathop {{\rm \max }}\limits_{x\in [r,s]}^{}}|g(x)-l(x)|=1$ ， ${\mathop {{\rm \max }}\limits_{x\in \left [r,s\right ]}^{}}\left \{\left |{g\left ({r}\right )-1}\right |,\left |{g\left ({s}\right )-1}\right |,\left |{g\left ({1}\right )-1}\right |\right \}=1$ ，此时等号成立，
17. 结论证毕.
18. （2）设 $h\left ({x}\right )=\left ({2{\ln}2-3}\right )\left ({x-1}\right )+2$ ，再令 $f\left ({x}\right )=g\left ({x}\right )-h\left ({x}\right )$ ，
19. $\therefore f^{′}{\left ({x}\right )}=g^{′}{\left ({x}\right )}-h^{′}{\left ({x}\right )}=\frac {2}{x}-2x-\left ({2{\ln}2-3}\right )$ ，
20. 令 $m\left ({x}\right )=\frac {2}{x}-2x-\left ({2{\ln}2-3}\right )$ ， $m^{′}{\left ({x}\right )}=-\frac {2}{x{^{2}}}-2<0$ ，
21. $\therefore f^{′}{\left ({x}\right )}$ 在区间 $\left [1,2\right ]$ 上单调递减，
22. 而 $f^{′}{\left ({1}\right )}>0$ ， $f^{′}{\left ({2}\right )}<0$ ， $\therefore $ 存在 $x{{}_{0}}\in \left ({1,2}\right )$ ，使得 $f^{′}{\left ({x{{}_{0}}}\right )}=0$ ，
23. 即 $\frac {2}{x{{}_{0}}}-2x{{}_{0}}-\left ({2{\ln}2-3}\right )=0\Rightarrow 2x{{}_{0}^{2}}+\left ({2{\ln}2-3}\right )x{{}_{0}}-2=0$ ，
24. 且 $x\in \left [1,x{{}_{0}}\right ]$ 时， $f^{′}{\left ({x}\right )}>0$ ， $f\left ({x}\right )$ 单调递增， $x\in \left [x{{}_{0}},2\right ]$ 时， $f^{′}{\left ({x}\right )}<0$ ， $f\left ({x}\right )$ 单调递减，
25. $\therefore f\left ({x}\right )$ 在区间 $\left [1,2\right ]$ 上的最大值为 $f\left ({x{{}_{0}}}\right )$ ，
26. 而 $f\left ({1}\right )=g\left ({1}\right )-h\left ({1}\right )=0$ ， $f\left ({2}\right )=g\left ({2}\right )-h\left ({2}\right )=0$ ，
27. 则 $f\left ({x}\right )$ 在区间 $\left [1,2\right ]$ 上大于等于0，
28. 由（1）问分析知，对定义在 $\left [a,b\right ]$ 上的函数 $f\left ({x}\right )\geqslant 0$ ，
29. 若 $f\left ({x}\right )$ 满足 $f\left ({a}\right )=f\left ({b}\right )=0$ ，且 $x{{}_{0}}\in \left [a,b\right ]$ 为 $f\left ({x}\right )$ 唯一的最大值点，
30. 则对任意的 $l\left ({x}\right )\in A$ ， ${\mathop {{\rm \max }}\limits_{x\in \left [a,b\right ]}^{}}\left |{f\left ({x}\right )-l\left ({x}\right )}\right |\geqslant \frac {f\left ({x{{}_{0}}}\right )}{2}$ ， $l\left ({x}\right )=\frac {f\left ({x{{}_{0}}}\right )}{2}$ 时取等号，
31. 
32. 又 ${\mathop {{\rm \max }}\limits_{x\in \left [1,2\right ]}^{}}\left |{f\left ({x}\right )-l\left ({x}\right )}\right |={\mathop {{\rm \max }}\limits_{x\in \left [1,2\right ]}^{}}\left |{g\left ({x}\right )-h\left ({x}\right )-l\left ({x}\right )}\right |$ ，
33. 故当 $l\left ({x}\right )=\frac {f\left ({x{{}_{0}}}\right )}{2}$ 时， ${\mathop {{\rm \max }}\limits_{x\in \left [1,2\right ]}^{}}\left |{f\left ({x}\right )-l\left ({x}\right )}\right |={\mathop {{\rm \max }}\limits_{x\in \left [1,2\right ]}^{}}\left |{g\left ({x}\right )-h\left ({x}\right )-l\left ({x}\right )}\right |$ 取得最小值 $\frac {f\left ({x{{}_{0}}}\right )}{2}$ ，
34. $\therefore g\left ({x}\right )$ 在 $x\in \left [1,2\right ]$ 上的“最接近”直线为 $l{{}_{\circ }}\left ({x}\right )=h\left ({x}\right )+\frac {f\left ({x{{}_{0}}}\right )}{2}$ ，
35. 即 $l{{}_{\circ }}\left ({x}\right )=\left ({2{\ln}2-3}\right )\left ({x-1}\right )+2+\frac {g\left ({x{{}_{\circ }}}\right )-\left ({2{\ln}2-3}\right )\left ({x{{}_{\circ }}-1}\right )-2}{2}$ ，
36. 化简可得 $l{{}_{\circ }}\left ({x}\right )=\left ({2{\ln}2-3}\right )\left ({x-\frac {x{{}_{\circ }}+1}{2}}\right )+\frac {2+g\left ({x{{}_{\circ }}}\right )}{2}$ ，其中 $x{{}_{\circ }}\in \left ({1,2}\right )$ ，
37. 且 $x{{}_{\circ }}$ 是二次方程 $2x{^{2}}+\left ({2{\ln}2-3}\right )x-2=0$ 的根，证毕.

## 知识点

**中文**:
  - 利用导数解决新定义问题

**English**:
  - Solving New Definition Problems

---
