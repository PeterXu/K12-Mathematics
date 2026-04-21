# Mathematics - 题目 3069

**ID**: 59e134d81b8d4a4a953ac023876acf56
**年级**: Grade 11
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=x-{\ln}\left ({1+x}\right )$ .​​​​​​​‌（1）求函数 $f\left ({x}\right )$ 在原点处的切线方程；（2）讨论函数 $z\left ({x}\right )=f\left ({x}\right )-\frac {1}{2}mx{^{2}}\left ({m\in {\mathbf{R}}}\right )$ 的单调区间；（3）证明： $\left [1+{\left({\frac {1}{2}}\right)^{0}}\right ]\times \left [1+2\times {\left({\frac {1}{2}}\right)^{1}}\right ]\times \cdot \cdot \cdot \times \left [1+n\times {\left({\frac {1}{2}}\right)^{n-1}}\right ]<{\rm{e}}{^{4}}$ .

## 解答

1. （1） $f^{′}\left ({x}\right )=1-\frac {1}{1+x}=\frac {x}{1+x}$ ， $f^{′}\left ({0}\right )=0$ ，
2. 所以函数 $f\left ({x}\right )$ 在原点处的切线方程为 $y=0$ .
3. （2） $z\left ({x}\right )=f\left ({x}\right )-\frac {1}{2}mx{^{2}}=x-{\ln}\left ({1+x}\right )-\frac {1}{2}mx{^{2}}\left ({x>-1}\right )$ ， $z^{′}\left ({x}\right )=1-\frac {1}{1+x}-mx=\frac {-x\left ({mx+m-1}\right )}{x+1}$
4. 当 $m=0$ 时， $z^{′}\left ({x}\right )=1-\frac {1}{1+x}-mx=\frac {x}{1+x}$ ，
5. 若 $x\in \left ({-1,0}\right )$ ， $z^{′}\left ({x}\right )<0$ ；若 $x\in \left ({0,+∞}\right )$ ， $z^{′}\left ({x}\right )>0$
6. 所以函数 $z\left ({x}\right )$ 的单调递减区间为 $\left ({-1,0}\right )$ ，单调递增区间为 $\left ({0,+∞}\right )$ .
7. 当 $m\ne 0$ 时，令 $z^{′}\left ({x}\right )=0$ ，则 $x{{}_{1}}=0,x{{}_{2}}=\frac {1-m}{m}$
8. ① $-1<x{{}_{2}}<x{{}_{1}}$ ，即 $m<0$ 或 $m>1$ ，
9. 若 $x\in \left ({-1,x{{}_{2}}}\right )\cup \left ({x{{}_{1}},+∞}\right )$ ，则 $z^{′}\left ({x}\right )<0$ ；若 $x\in \left ({x{{}_{2}},x{{}_{1}}}\right )$ ，则 $z^{′}\left ({x}\right )>0$ ，
10. 所以函数 $z\left ({x}\right )$ 的单调递减区间为 $\left ({-1,x{{}_{2}}}\right ),\left ({x{{}_{1}},+∞}\right )$ ，单调递增区间为 $\left ({x{{}_{2}},x{{}_{1}}}\right )$ .
11. ② $x{{}_{2}}=x{{}_{1}}$ ，即 $m=1$ ， $z^{′}\left ({x}\right )\leqslant 0$ 在 $\left ({-1,∞}\right )$ 恒成立，
12. 所以函数 $z\left ({x}\right )$ 的单调递减区间为 $\left ({-1,+∞}\right )$ ，没有单调递增区间.
13. ③ $x{{}_{2}}=x{{}_{1}}$ ，即 $0<m<1$ ，
14. 若 $x\in \left ({-1,x{{}_{1}}}\right )\cup \left ({x{{}_{2}},+∞}\right )$ ，则 $z^{′}\left ({x}\right )<0$ ；若 $x\in \left ({x{{}_{1}},x{{}_{2}}}\right )$ ，则 $z^{′}\left ({x}\right )>0$ ，
15. 所以函数 $z\left ({x}\right )$ 的单调递减区间为 $\left ({-1,x{{}_{1}}}\right ),\left ({x{{}_{2}},+∞}\right )$ ，单调递增区间为 $\left ({x{{}_{1}},x{{}_{2}}}\right )$
16. （3）要证明： $\left [1+{\left({\frac {1}{2}}\right)^{0}}\right ]\times \left [1+2\times {\left({\frac {1}{2}}\right)^{1}}\right ]\times \cdot \cdot \cdot \times \left [1+n\times {\left({\frac {1}{2}}\right)^{n-1}}\right ]<{\rm{e}}{^{4}}$ ，
17. 即证明： ${\ln}\left \{\left [1+{\left({\frac {1}{2}}\right)^{0}}\right ]\times \left [1+2\times {\left({\frac {1}{2}}\right)^{1}}\right ]\times \cdot \cdot \cdot \times \left [1+n\times {\left({\frac {1}{2}}\right)^{n-1}}\right ]\right \}<{\ln}{\rm{e}}{^{4}}$
18. 即证明： ${\ln}\left [1+{\left({\frac {1}{2}}\right)^{0}}\right ]+{\ln}\left [1+2\times {\left({\frac {1}{2}}\right)^{1}}\right ]+\cdot \cdot \cdot +{\ln}\left [1+n\times {\left({\frac {1}{2}}\right)^{n-1}}\right ]<4$
19. 由（2）可知：当 $m=0$ 时， $z\left ({x}\right )=x-{\ln}\left ({1+x}\right )$ ，函数 $z\left ({x}\right )$ 的单调递减区间为 $\left ({-1,0}\right )$ ，单调递增区间为 $\left ({0,+∞}\right )$ ，
20. 所以 $z\left ({x}\right )\geqslant z\left ({0}\right )=0\Rightarrow x\geqslant {\ln}\left ({1+x}\right )$ （当 $x=0$ 时取等号）.
21. ${\ln}\left [1+{\left({\frac {1}{2}}\right)^{0}}\right ]+{\ln}\left [1+2\times {\left({\frac {1}{2}}\right)^{1}}\right ]+\cdot \cdot \cdot +{\ln}\left [1+n\times {\left({\frac {1}{2}}\right)^{n-1}}\right ]<{\left({\frac {1}{2}}\right)^{0}}+2\times {\left({\frac {1}{2}}\right)^{1}}+...+n\times {\left({\frac {1}{2}}\right)^{n-1}}$ ,
22. 令 $S{{}_{n}}={\left({\frac {1}{2}}\right)^{0}}+2\times {\left({\frac {1}{2}}\right)^{1}}+...+n\times {\left({\frac {1}{2}}\right)^{n-1}}$ ①，
23. $\frac {1}{2}S{{}_{n}}=\frac {1}{2}+2\times {\left({\frac {1}{2}}\right)^{2}}+...+\left ({n-1}\right )\times {\left({\frac {1}{2}}\right)^{n-1}}+n\times {\left({\frac {1}{2}}\right)^{n}}$ ②，
24. 由①-②： $\frac {1}{2}S{{}_{n}}=1+\frac {1}{2}+{\left({\frac {1}{2}}\right)^{2}}+...+\left ({n-1}\right ){\left({\frac {1}{2}}\right)^{n-1}}-n\times {\left({\frac {1}{2}}\right)^{n}}$ ，
25. 所以 $\frac {1}{2}S{{}_{n}}=1+\frac {\frac {1}{2}\left [1-{\left({\frac {1}{2}}\right)^{n-1}}\right ]}{1-\frac {1}{2}}--n\times {\left({\frac {1}{2}}\right)^{n}}$ ，则 $S{{}_{n}}=4-{\left({\frac {1}{2}}\right)^{n-2}}-n\times {\left({\frac {1}{2}}\right)^{n-1}}$ ，
26. 所以 $S{{}_{n}}=4-{\left({\frac {1}{2}}\right)^{n-2}}-n\times {\left({\frac {1}{2}}\right)^{n-1}}<4$ ，
27. 所以 ${\ln}\left [1+{\left({\frac {1}{2}}\right)^{0}}\right ]+{\ln}\left [1+2\times {\left({\frac {1}{2}}\right)^{1}}\right ]+\cdot \cdot \cdot +{\ln}\left [1+n\times {\left({\frac {1}{2}}\right)^{n-1}}\right ]<4$ ，证毕.

## 知识点

**中文**:
  - 利用导数研究函数的单调性与单调区间
  - 导数几何意义的应用
  - 利用导数证明不等式

**English**:
  - Monotonicity and Monotonic Intervals
  - Applications of Geometric Meaning of Derivatives
  - Proving Inequalities using Derivatives

---
