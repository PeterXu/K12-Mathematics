# Mathematics - 题目 3380

**ID**: e29db54444bb4005b3287792883dfca5
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数： $f\left ({x}\right )=-x{^{2}}+ax+2a{^{2}},a>0$（1） $g\left ({x}\right )=f\left ({\left |{x}\right |}\right )-b$ 有4个零点且从小到大记作 $x{{}_{1}},x{{}_{2}},x{{}_{3}},x{{}_{4}}$ .​​​​​​​‌求 $x{{}_{1}}+x{{}_{2}}+x{{}_{3}}+x{{}_{4}}$ ；（2）已知 $a=1,A,B,C$ 为 $\vartriangle ABC$ 的三个内角， $f\left ({{\rm{s}}{\rm{i}}{\rm{n}}A}\right )=f\left ({{\rm{s}}{\rm{i}}{\rm{n}}B}\right )$ ，若 $A\ne B$ 且 $A､B$ 均为锐角.证明： $∠C$ 为钝角；（3）若函数 $h\left ({x}\right )=\left |{f\left ({x}\right )}\right |$ 在区间 $\left [0,2\right ]$ 上的最大值为 $M$ ，最小值为 $m$ ，且 $M-m\leqslant 4$ ，求 $a$ 的取值范围.

## 解答

1. （1）由题可得： $g\left ({x}\right )=-x{^{2}}+a\left |{x}\right |+2a{^{2}}-b$ ,其定义域为 ${\rm R}$ ,
2. 由于 $g\left ({-x}\right )=-{\left({-x}\right)^{2}}+a\left |{-x}\right |+2a{^{2}}-b=-x{^{2}}+a\left |{x}\right |+2a{^{2}}-b=g\left ({x}\right )$ ,
3. 所以 $g\left ({x}\right )$ 为偶函数，
4. 即当 $x>0$ ， $g\left ({x}\right )=-x{^{2}}+ax+2a{^{2}}-b$ 有两个零点，记作 $x{{}_{3}},x{{}_{4}}$ ，由韦达定理则有 $x{{}_{3}}+x{{}_{4}}=a$ ,
5. 由对称性 $x{{}_{1}}+x{{}_{2}}=-a$ ，故 $x{{}_{1}}+x{{}_{2}}+x{{}_{3}}+x{{}_{4}}=0$ .
6. （2）当 $a=1$ 时， $f\left ({x}\right )=-x{^{2}}+x+2$ ，其对称轴为： $x=\frac {1}{2}$ ，
7. 因为 $A\ne B$ ，则 $\sin A\ne \sin B$ ，
8. 由于 $f\left ({{\rm{s}}{\rm{i}}{\rm{n}}A}\right )=f\left ({{\rm{s}}{\rm{i}}{\rm{n}}B}\right )$ ，则 $\frac {\sin A+\sin B}{2}=\frac {1}{2}$ ，
9. 故 ${\rm{s}}{\rm{i}}{\rm{n}}A+{\rm{s}}{\rm{i}}{\rm{n}}B=1$
10. 若 $C$ 为钝角，即证： $A+B<\frac {{\rm{\mathrm{π}}}}{2}$
11. 即证： $A<\frac {{\rm{\mathrm{π}}}}{2}-B$ ，因为 $A､B$ 均为锐角， $y=\sin x$ 在 $\left ({0,\frac {{\rm{\mathrm{π}}}}{2}}\right )$ 上单调递增，
12. 即证： ${\rm{s}}{\rm{i}}{\rm{n}}A<{\rm{s}}{\rm{i}}{\rm{n}}\left ({\frac {{\rm{\mathrm{π}}}}{2}-B}\right )={\rm{c}}{\rm{o}}{\rm{s}}B$
13. 即证： $1-{\rm{s}}{\rm{i}}{\rm{n}}B<{\rm{c}}{\rm{o}}{\rm{s}}B$
14. 即证： ${\rm{c}}{\rm{o}}{\rm{s}}B+{\rm{s}}{\rm{i}}{\rm{n}}B>1$
15. 设 $p\left ({B}\right )={\rm{c}}{\rm{o}}{\rm{s}}B+{\rm{s}}{\rm{i}}{\rm{n}}B=\sqrt {2}{\rm{s}}{\rm{i}}{\rm{n}}\left ({B+\frac {{\rm{\mathrm{π}}}}{4}}\right ),B\in \left ({0,\frac {{\rm{\mathrm{π}}}}{2}}\right )$
16. $B+\frac {{\rm{\mathrm{π}}}}{4}\in \left ({\frac {{\rm{\mathrm{π}}}}{4},\frac {3{\rm{\mathrm{π}}}}{4}}\right ),p\left ({B}\right )>\sqrt {2}\cdot \frac {\sqrt {2}}{2}=1$
17. 即 $A+B<\frac {{\rm{\mathrm{π}}}}{2}$ ，证毕.
18. （3） $f\left ({x}\right )=-x{^{2}}+ax+2a{^{2}}$ 对称轴为 $x=\frac {a}{2}$ ,
19. $f\left ({0}\right )=2a{^{2}},f\left ({\frac {a}{2}}\right )=\frac {9}{4}a{^{2}},f\left ({2}\right )=2a{^{2}}+2a-4$ ,
20. $h\left ({x}\right )=\left |{f\left ({x}\right )}\right |=\begin{cases}-x{^{2}}+ax+2a{^{2}},x\leqslant 2a\\x{^{2}}-ax-2a{^{2}},x>2a\end{cases}$
21. ①当 $2\leqslant \frac {a}{2}\Rightarrow a\geqslant 4$ ，
22. $M=f\left ({2}\right ),m=f\left ({0}\right ),M-m=2a-4\leqslant 4\Rightarrow a\leqslant 4$ ,
23. 综上所述 $a=4$
24. ②当 $\frac {a}{2}<2\leqslant 2a\Rightarrow 1\leqslant a<4$ ，
25. 则 $M=f\left ({\frac {a}{2}}\right )=\frac {9}{4}a{^{2}}$ ， $m=\left \{f\left ({0}\right ),f\left ({2}\right )\right \}{{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=\left \{2a{^{2}},2a{^{2}}+2a-4\right \}{{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}$ ,且 $M-m\leqslant 4$ .
26. 故只需 $\left \{\hspace{-0.5em}\begin{array}{}\frac {9}{4}a{^{2}}-2a{^{2}}\leqslant 4\\\frac {1}{4}a{^{2}}-2a+4\leqslant 4\end{array}\hspace{-0.5em}\Rightarrow \left \{\hspace{-0.5em}\begin{array}{l}0\leqslant a\leqslant 4\\0\leqslant a\leqslant 8\end{array}\hspace{-0.5em}\right.\right.$ ，因为 $1\leqslant a<4$ ，
27. 故此时解为 $1\leqslant a<4$ ;
28. ③当 $2>2a\Rightarrow 0<a<1$ ，
29. $m=f\left ({2a}\right )=0$  $M=\left \{f\left ({\frac {a}{2}}\right ),h\left ({2}\right )\right \}{{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}=\left \{\frac {9}{4}a{^{2}},4-2a{^{2}}-2a\right \}{{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}$ .
30. 故只需 $\begin{cases}\frac {9}{4}a{^{2}}\leqslant 4\\4-2a{^{2}}-2a\leqslant 4\end{cases}$ ,
31. 当 $0<a<1$ 上式恒成立，
32. 综上 $a\in \left ({0,4}\right ]$ .

## 知识点

**中文**:
  - 函数性质的综合运用
  - 函数零点的概念

**English**:
  - Comprehensive Application of Function Properties
  - Concept of Zero Points

---
