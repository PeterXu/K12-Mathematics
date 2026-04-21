# Mathematics - 题目 2012

**ID**: a2e33d77cd9b40f19594ca1dd710e7dd
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\left ({x+k}\right ){\ln}x$ ， $g\left ({x}\right )=x+a\sin x+b{\ln}x$ .​​​​​​​‌（1）若 $k=1$ ，求曲线 $y=f\left ({x}\right )$ 过点 $\left ({0,-2}\right )$ 处的切线方程；（2）当 $x>1$ 时， $f\left ({x}\right )>2\left ({x-1}\right )$ 恒成立，求实数 $k$ 的取值范围；（3）设 $0<a<1$ ， $b<0$ ，若存在 $x{{}_{1}},x{{}_{2}}\in \left ({0,+\infty }\right )$ ，使得 $g\left ({x{{}_{1}}}\right )=g\left ({x{{}_{2}}}\right )\left ({x{{}_{1}}\ne x{{}_{2}}}\right )$ .证明： $\sqrt {x{{}_{1}}}+\sqrt {x{{}_{2}}}>\frac {2\sqrt {-b}}{\sqrt {a}+1}$ .

## 解答

1. （1）当 $k=1$ 时， $f\left ({x}\right )=\left ({x+1}\right ){\rm{l}}{\rm{n}}x$ ，则 $f^{′}{\left ({x}\right )}={\rm{l}}{\rm{n}}x+\frac {\left ({x+1}\right )}{x}$ ，
2. 设切点坐标为 $\left ({x{{}_{0}},\left ({x{{}_{0}}+1}\right ){\rm{l}}{\rm{n}}x{{}_{0}}}\right )$ ，
3. 则切线方程为 $y-\left ({x{{}_{0}}+1}\right ){\rm{l}}{\rm{n}}x{{}_{0}}=\left [{\rm{l}}{\rm{n}}x{{}_{0}}+\frac {\left ({x{{}_{0}}+1}\right )}{x{{}_{0}}}\right ]\left ({x-x{{}_{0}}}\right )$ ，
4. 代入点 $(0,-2)$ ，可得 $-2-\left ({x{{}_{0}}+1}\right ){\rm{l}}{\rm{n}}x{{}_{0}}=\left [{\rm{l}}{\rm{n}}x{{}_{0}}+\frac {\left ({x{{}_{0}}+1}\right )}{x{{}_{0}}}\right ]\left ({-x{{}_{0}}}\right )$ ，整理得 $x{{}_{0}}-{\ln}x{{}_{0}}=1$ ，
5. 设函数 $F\left ({x}\right )=x-{\ln}x$ ，则 $F^{′}{\left ({x}\right )}=1-\frac {1}{x}=\frac {x-1}{x}$ ，
6. 当 $x\in \left ({0,1}\right )$ 时， $F^{′}{\left ({x}\right )}<0$ ， $F\left ({x}\right )$ 单调递减；当 $x\in \left ({1,+\infty }\right )$ 时， $F^{′}{\left ({x}\right )}>0$ ， $F\left ({x}\right )$ 单调递增，
7. 又 $F\left ({1}\right )=1-{\ln}1=1$ ，故当且仅当 $x=1$ 时， $F\left ({x}\right )=1$ .
8. 所以解得 $x{{}_{0}}=1$ ，则切线方程为 $y=2x-2$ .
9. （2）设 $m\left ({x}\right )=f\left ({x}\right )-2\left ({x-1}\right )=\left ({x+k}\right ){\rm{l}}{\rm{n}}x-2x+2$ ，只需 $m\left ({x}\right )>0$ 在 $x>1$ 时恒成立即可，
10. 又 $m^{′}{\left ({x}\right )}={\rm{l}}{\rm{n}}x+\frac {k}{x}-1$ ，且 $m\left ({1}\right )=0$ ，
11. 所以要使当 $x>1$ 时， $m\left ({x}\right )>0$ ，必须满足 $m^{′}{\left ({1}\right )}=k-1\geqslant 0$ ，即 $k\geqslant 1$ .
12. 下面证明 $k\geqslant 1$ 时满足题意：
13. 当 $k\geqslant 1$ 时，由 $x>1$ ， $m\left ({x}\right )=\left ({x+k}\right ){\rm{l}}{\rm{n}}x-2x+2\geqslant \left ({x+1}\right ){\rm{l}}{\rm{n}}x-2\left ({x-1}\right )$ ，
14. 令 $φ\left ({x}\right )=\left ({x+1}\right ){\rm{l}}{\rm{n}}x-2\left ({x-1}\right ),x>1$ ，
15. 则 $φ^{′}{\left ({x}\right )}={\ln}x+\frac {x+1}{x}-2={\ln}x+\frac {1}{x}-1$ ，
16. 设 $G\left ({x}\right )=φ^{′}{\left ({x}\right )}={\ln}x+\frac {1}{x}-1,x>1$ ，则 $G^{′}{\left ({x}\right )}=\frac {1}{x}-\frac {1}{x{^{2}}}=\frac {x-1}{x{^{2}}}>0$ ，
17. 故 $φ^{′}{\left ({x}\right )}$ 在 $\left ({1,+\infty }\right )$ 上单调递增，即 $φ^{′}{\left ({x}\right )}>φ^{′}{\left ({1}\right )}=0$ ，
18. 所以 $φ\left ({x}\right )$ 在 $\left ({1,+\infty }\right )$ 上单调递增，即 $φ\left ({x}\right )>φ\left ({1}\right )=0$ ，
19. 所以当 $x>1$ 时， $m\left ({x}\right )\geqslant φ\left ({x}\right )>0$ ，即 $m\left ({x}\right )>0$ 恒成立；
20. 当 $k<1$ 时， $m^{′}{\left ({x}\right )}={\rm{l}}{\rm{n}}x+\frac {k}{x}-1$ ，
21. 令 $t\left ({x}\right )=m^{′}{\left ({x}\right )}$ ， $\left ({x>1}\right )$ ，则 $t^{′}{\left ({x}\right )}=\frac {x-k}{x{^{2}}}>0$ ，
22. 所以 $m^{′}{\left ({x}\right )}$ 在 $\left ({1,+\infty }\right )$ 上单调递增，又 $m^{′}{\left ({1}\right )}=k-1<0$ ，当 $x\to +\infty $ 时， $m^{′}{\left ({x}\right )}\to +\infty $ ，
23. 所以存在 $x{{}_{0}}\in \left ({1,+\infty }\right )$ ，使得 $m^{′}{\left ({x{{}_{0}}}\right )}=0$ ，
24. 当 $x\in \left ({1,x{{}_{0}}}\right )$ 时， $m^{′}{\left ({x}\right )}<0$ ， $m\left ({x}\right )$ 在 $\left ({1,x{{}_{0}}}\right )$ 上单调递减，则 $m\left ({x}\right )<m\left ({1}\right )=0$ ，
25. 所以当 $k<1$ 时， $m\left ({x}\right )>0$ 不恒成立.
26. 综上所述，实数 $k$ 的取值范围是 $\left [{1,+\infty }\right )$ .
27. （3）由函数 $g\left ({x}\right )=x+a{\rm{s}}{\rm{i}}{\rm{n}}x+b{\rm{l}}{\rm{n}}x$ ，可得 $g^{′}{\left ({x}\right )}=1+a{\rm{c}}{\rm{o}}{\rm{s}}x+\frac {b}{x}$ ，
28. 设 $x{{}_{1}}<x{{}_{2}}$ ，则 $\frac {x{{}_{2}}}{x{{}_{1}}}>1$ ，
29. 由 $g\left ({x{{}_{1}}}\right )=g\left ({x{{}_{2}}}\right )$ ，可得 $x{{}_{1}}+a{\rm{s}}{\rm{i}}{\rm{n}}x{{}_{1}}+b{\rm{l}}{\rm{n}}x{{}_{1}}=x{{}_{2}}+a{\rm{s}}{\rm{i}}{\rm{n}}x{{}_{2}}+b{\rm{l}}{\rm{n}}x{{}_{2}}$ ，
30. 则 $\left ({x{{}_{2}}-x{{}_{1}}}\right )+a\left ({{\rm{s}}{\rm{i}}{\rm{n}}x{{}_{2}}-{\rm{s}}{\rm{i}}{\rm{n}}x{{}_{1}}}\right )=-b\left ({{\rm{l}}{\rm{n}}x{{}_{2}}-{\rm{l}}{\rm{n}}x{{}_{1}}}\right )=-b{\ln}\frac {x{{}_{2}}}{x{{}_{1}}}$ ，
31. 又由 $y=x-{\rm{s}}{\rm{i}}{\rm{n}}x$ ，可得 $y^{′}=1-{\rm{c}}{\rm{o}}{\rm{s}}x\geqslant 0$ ，所以函数 $y=x-{\rm{s}}{\rm{i}}{\rm{n}}x$ 为单调递增函数，
32. 则 $x{{}_{2}}-{\rm{s}}{\rm{i}}{\rm{n}}x{{}_{2}}>x{{}_{1}}-{\rm{s}}{\rm{i}}{\rm{n}}x{{}_{1}}$ ，即 ${\rm{s}}{\rm{i}}{\rm{n}}x{{}_{2}}-{\rm{s}}{\rm{i}}{\rm{n}}x{{}_{1}}<x{{}_{2}}-x{{}_{1}}$ ， $-b{\ln}\frac {x{{}_{2}}}{x{{}_{1}}}<\left ({a+1}\right )\left ({x{{}_{2}}-x{{}_{1}}}\right )$ ，
33. 由（2）知，当 $x>1$ 时， $φ\left ({x}\right )=\left ({x+1}\right ){\rm{l}}{\rm{n}}x-2\left ({x-1}\right )>0$ ，即 ${\rm{l}}{\rm{n}}x>2\times \frac {x-1}{x+1}$ ，则 ${\rm{l}}{\rm{n}}\sqrt {x}>2\times \frac {\sqrt {x}-1}{\sqrt {x}+1}$ ，
34. 即 ${\ln}x=2{\ln}\sqrt {x}>4\times \frac {\sqrt {x}-1}{\sqrt {x}+1}$ ， ${\rm{l}}{\rm{n}}\frac {x{{}_{2}}}{x{{}_{1}}}>4\times \frac {\sqrt {\frac {x{{}_{2}}}{x{{}_{1}}}}-1}{\sqrt {\frac {x{{}_{2}}}{x{{}_{1}}}}+1}=4\times \frac {\sqrt {x{{}_{2}}}-\sqrt {x{{}_{1}}}}{\sqrt {x{{}_{2}}}+\sqrt {x{{}_{1}}}}$ ，
35. 代入可得： $4\times \left ({-b}\right )\times \frac {\sqrt {x{{}_{2}}}-\sqrt {x{{}_{1}}}}{\sqrt {x{{}_{2}}}+\sqrt {x{{}_{1}}}}<-b{\ln}\frac {x{{}_{2}}}{x{{}_{1}}}<\left ({a+1}\right )\left ({x{{}_{2}}-x{{}_{1}}}\right )=\left ({a+1}\right )\left ({\sqrt {x{{}_{2}}}-\sqrt {x{{}_{1}}}}\right )\left ({\sqrt {x{{}_{2}}}+\sqrt {x{{}_{1}}}}\right )$ ，
36. 则 $4\times \frac {\left ({-b}\right )}{a+1}<{\left({\sqrt {x{{}_{2}}}+\sqrt {x{{}_{1}}}}\right)^{2}}$ ， $\sqrt {x{{}_{2}}}+\sqrt {x{{}_{1}}}>2\sqrt {\frac {-b}{a+1}}$ ，
37. 又因为 $0<a<1$ 时， ${\left({\sqrt {a}+1}\right)^{2}}=a+2\sqrt {a}+1>a+1={\left({\sqrt {a+1}}\right)^{2}}$ ，
38. 所以 $\sqrt {a}+1>\sqrt {a+1}$ ，所以 $\sqrt {x{{}_{1}}}+\sqrt {x{{}_{2}}}>\frac {2\sqrt {-b}}{\sqrt {a}+1}$ 得证.

## 知识点

**中文**:
  - 利用导数解决不等式恒成立问题
  - 导数几何意义的应用
  - 利用导数证明不等式

**English**:
  - Solving Universally True Inequalities
  - Applications of Geometric Meaning of Derivatives
  - Proving Inequalities using Derivatives

---
