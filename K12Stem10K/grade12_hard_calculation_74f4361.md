# Mathematics - 题目 3725

**ID**: 74f4361c331d45568f8d15242e41147b
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知正项数列 $\left \{a{{}_{n}}\right \}$ 满足 $a{{}_{n+1}^{2}}=2-\frac {2}{a{{}_{n}}+1}$ ．(1)若 $a{{}_{3}}=a{{}_{4}}$ ，求 $a{{}_{7}}$ ；​​​​​​​‌(2)若 $a{{}_{1}}=\sqrt {2}$ ，求 $\left \{a{{}_{n}}\right \}$ 的通项公式；(3)记 $S{{}_{n}}$ 为数列 $\left \{\frac {1}{a{{}_{n}}}\right \}$ 的前 $n$ 项和，若 $S{{}_{2}^{2}}=\frac {\sqrt {3}}{2}+1$ ，证明： $\frac {1}{2}\leqslant n-S{{}_{n}}<\frac {3}{4}$ ．

## 解答

1. （1）由题， $a{{}_{4}^{2}}=2-\frac {2}{a{{}_{3}}+1}$ ，且 $a{{}_{3}}=a{{}_{4}}$ ，又 $a{{}_{n}}>0$ ，代入，解得 $a{{}_{3}}=a{{}_{4}}=1$ ，
2. 所以 $a{{}_{5}^{2}}=2-\frac {2}{a{{}_{4}}+1}=1$ ， $a{{}_{6}^{2}}=2-\frac {2}{a{{}_{5}}+1}=1$ ， $a{{}_{7}^{2}}=2-\frac {2}{a{{}_{4}}+1}=1$ ，故 $a{{}_{7}}=1$ ．
3. （2）令 $b{{}_{n}}=\frac {1}{a{{}_{n}}}$ ，则有 $\frac {1}{b{{}_{n+1}^{2}}}=\frac {2}{1+b{{}_{n}}}$ ，即 $b{{}_{n}}=2b{{}_{n+1}^{2}}-1$ ，又 $a{{}_{1}}=\sqrt {2}$ ，则 $b{{}_{1}}=\frac {\sqrt {2}}{2}$ ，
4. 此时不妨令 $b{{}_{n}}={\rm{c}}{\rm{o}}{\rm{s}}\frac {\mathrm{π}θ{{}_{n}}}{4}$ ，则 $b{{}_{n+1}}={\rm{c}}{\rm{o}}{\rm{s}}\frac {\mathrm{π}θ{{}_{n+1}}}{4}$ ，则有 $θ{{}_{n}}=2θ{{}_{n+1}}$ ，即 $θ{{}_{n}}=\frac {θ{{}_{1}}}{2{^{n-1}}}$ ，
5. 讨论周期性对 $b{{}_{n}}$ 唯一性的影响：不妨令 $θ{{}_{1}}=\frac {\mathrm{π}}{4}$ ，则 ${\rm{c}}{\rm{o}}{\rm{s}}\left ({\frac {θ{{}_{1}}+2n\mathrm{π}}{2}}\right )={\rm{c}}{\rm{o}}{\rm{s}}\left ({\frac {\mathrm{π}}{8}+n\mathrm{π}}\right )$ ，
6. 当 $n=2k+1$ 时， ${\rm{c}}{\rm{o}}{\rm{s}}\left ({\frac {\mathrm{π}}{8}+n\mathrm{π}}\right )<0$ ，不合题意，舍去；
7. 当 $n=2k\left ({k\in {\mathbf{Z}}}\right )$ 时，符合题意；此时 ${\rm{c}}{\rm{o}}{\rm{s}}\left ({\frac {\mathrm{π}}{8}+n\mathrm{π}}\right )={\rm{c}}{\rm{o}}{\rm{s}}\frac {\mathrm{π}}{8}={\rm{c}}{\rm{o}}{\rm{s}}θ{{}_{2}}$ ，
8. 同理， ${\rm{c}}{\rm{o}}{\rm{s}}θ{{}_{n}}$ 唯一，即 $\left \{b{{}_{n}}\right \}$ 唯一．即 $b{{}_{n}}={\rm{c}}{\rm{o}}{\rm{s}}\frac {\mathrm{π}}{2{^{n+1}}}$ ，故 $a{{}_{n}}=\frac {1}{{\rm{c}}{\rm{o}}{\rm{s}}\frac {\mathrm{π}}{2{^{n+1}}}}$ ．
9. （3）由题意，若 $S{{}_{2}^{2}}=\frac {\sqrt {3}}{2}+1={\left({\frac {1+\sqrt {3}}{2}}\right)^{2}}$ ，且 $a{{}_{n}}>0$ ，则 $S{{}_{2}}=\frac {1+\sqrt {3}}{2}$ ，
10. 联立 $\begin{cases}\frac {1}{a{{}_{1}}}+\frac {1}{a{{}_{2}}}=\frac {1+\sqrt {3}}{2}\\a{{}_{2}^{2}}=2-\frac {2}{a{{}_{1}}+1}\end{cases}$ ，解得 $a{{}_{1}}=2$ ，
11. 原不等式可转化为 $n-\frac {3}{4}<S{{}_{n}}\leqslant n-\frac {1}{2}$ ，
12. 先证明 $S{{}_{n}}>n-\frac {3}{4}$ ：
13. 由 $a{{}_{1}}=2$ ， $θ{{}_{1}}=\frac {\mathrm{π}}{3}$ ，由（2）可推 $a{{}_{n}}=\frac {1}{{\rm{c}}{\rm{o}}{\rm{s}}\frac {\mathrm{π}}{3\cdot 2{^{n-1}}}}$ ，则 $\frac {1}{a{{}_{n}}}={\rm{c}}{\rm{o}}{\rm{s}}\frac {\mathrm{π}}{3\cdot 2{^{n-1}}}$ ，
14. 令函数 $g\left ({x}\right )={\rm{c}}{\rm{o}}{\rm{s}}x-1+\frac {1}{2}x{^{2}}\left ({x>0}\right )$ ，则 $g^{′}{\left ({x}\right )}=-{\rm{s}}{\rm{i}}{\rm{n}}x+x$ ，
15. 令 $h\left ({x}\right )=-{\rm{s}}{\rm{i}}{\rm{n}}x+x$ ，则 $h^{′}{\left ({x}\right )}=1-{\cos}x\geqslant 0$ 恒成立，所以 $h\left ({x}\right )$ 在 $\left ({0,+\mathrm{∞}}\right )$ 上单调递增，
16. 又 $h\left ({0}\right )=0$ ，所以在 $\left ({0,+\mathrm{∞}}\right )$ 上有 $h\left ({x}\right )>h\left ({0}\right )=0$ ，
17. 所以 $g\left ({x}\right )$ 在 $\left ({0,+\mathrm{∞}}\right )$ 上单调递增，又 $g\left ({0}\right )=0$ ，则 $g\left ({x}\right )>0$ ，
18. 所以 ${\rm{c}}{\rm{o}}{\rm{s}}x>1-\frac {1}{2}x{^{2}}$ ，则 $\frac {1}{a{{}_{n}}}={\rm{c}}{\rm{o}}{\rm{s}}\frac {\mathrm{π}}{3\cdot 2{^{n-1}}}>1-\frac {1}{2}\left [\frac {\mathrm{π}}{3}{\left({\frac {1}{2}}\right)^{n-1}}\right ]{^{2}}=1-\frac {2\mathrm{π}{^{2}}}{9}{\left({\frac {1}{4}}\right)^{n}}$ ，
19. 故 $S{{}_{n}}=\frac {1}{a{{}_{1}}}+\frac {1}{a{{}_{2}}}+\cdots +\frac {1}{a{{}_{n}}}>n-\frac {2\mathrm{π}{^{2}}}{9}\left [{\left({\frac {1}{4}}\right)^{1}}+{\left({\frac {1}{4}}\right)^{2}}+\cdots +{\left({\frac {1}{4}}\right)^{n}}\right ]$
20. $=n-\frac {2\mathrm{π}{^{2}}}{9}\left [\frac {\frac {1}{4}-{\left({\frac {1}{4}}\right)^{n+1}}}{\frac {3}{4}}\right ]=n-\frac {2\mathrm{π}{^{2}}}{27}\left [1-{\left({\frac {1}{4}}\right)^{n}}\right ]$ ，
21. 又因为 $\frac {3}{4}-\frac {2\mathrm{π}{^{2}}}{27}\left [1-{\left({\frac {1}{4}}\right)^{n}}\right ]=\frac {3}{4}-\frac {2\mathrm{π}{^{2}}}{27}+\frac {2\mathrm{π}{^{2}}}{27}{\left({\frac {1}{4}}\right)^{n}}>\frac {2\mathrm{π}{^{2}}}{27}{\left({\frac {1}{4}}\right)^{n}}>0$ ，所以 $S{{}_{n}}>n-\frac {3}{4}$ ，
22. 证明 $S{{}_{n}}\leqslant n-\frac {1}{2}$ ：
23. 由 $\frac {1}{a{{}_{n}}}={\rm{c}}{\rm{o}}{\rm{s}}\frac {\mathrm{π}}{3\cdot 2{^{n-1}}}<1$ ，则 $\frac {1}{a{{}_{1}}}+\frac {1}{a{{}_{2}}}+\cdots +\frac {1}{a{{}_{n}}}\leqslant \frac {1}{2}+n-1$ ，当且仅当 $n=1$ 时取等，
24. 所以 $S{{}_{n}}\leqslant n-\frac {1}{2}$ ，故 $n-\frac {3}{4}<S{{}_{n}}\leqslant n-\frac {1}{2}$ ，
25. 所以 $\frac {1}{2}\leqslant n-S{{}_{n}}<\frac {3}{4}$ ．

## 知识点

**中文**:
  - 利用导数研究函数的单调性与单调区间
  - 数列的递推公式
  - 等比数列前n项和公式
  - 数列与不等式的综合

**English**:
  - Monotonicity and Monotonic Intervals
  - Recurrence Formula
  - Sum Formula
  - Sequences with Inequalities

---
