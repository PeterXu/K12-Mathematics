# Mathematics - 题目 920

**ID**: 94073562f3cd46f3a868eeeae523b33f
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
若两个集合M，N满足： $\forall x\in M$ ， $-x\in \mathbf{N}$ ，且 $\forall x\in {\rm{N}}$ ， $-x\in M$ ，则称M，N互为对偶集．已知函数 $f\left ({x}\right )=\frac {1}{1+{\rm{e}}{^{-x}}}+a\left ({x+1}\right )+bx{^{3}}$ ，定义 $A{{}_{t}}=$  $\left \{x|f\left ({x}\right )>t\right \}$ ， $B{{}_{t}}=\left \{x|f\left ({x}\right )<t\right \}$ ．（1）若 $b=0$ ， $a=-\frac {1}{4}$ ， $p<q$ ，证明： $A{{}_{f(p)}}\subseteq A{{}_{f(q)}}$ ；​​​​​​​‌（2）证明：存在 $s\in {\mathbf{R}}$ ，使得无论t取何值， $A{{}_{t}}$ 与 $B{{}_{s-t}}$ 均互为对偶集；（3）若 $A{{}_{\frac {1}{2}}}=(0,+\infty )$ ，求b的取值范围．

## 解答

1. （1）由题意知， $f\left ({x}\right )=\frac {1}{1+{\rm{e}}{^{-x}}}-\frac {1}{4}\left ({x+1}\right )$ ，
2. 则 $f^{′}(x)=\frac {{\rm{e}}{^{-x}}}{{\left({1+{\rm{e}}{^{-x}}}\right)^{2}}}-\frac {1}{4}=\frac {1}{{\rm{e}}{^{x}}+{\rm{e}}{^{-x}}+2}-\frac {1}{4}\leqslant \frac {1}{2\sqrt {{\rm{e}}{^{x}}\cdot {\rm{e}}{^{-x}}}+2}-\frac {1}{4}=0$ ，
3. 因此 $f\left ({x}\right )$ 在 ${\mathbf{R}}$ 上单调递减．
4. $A{{}_{f(p)}}=\left \{x|f\left ({x}\right )>f\left ({p}\right )\right \}=\left \{x|x<p\right \}$ ，
5. $A{{}_{f(q)}}=\left \{x|f\left ({x}\right )>f\left ({q}\right )\right \}=\left \{x|x<q\right \}$ ，
6. 又 $p<q$ ，故 $A{{}_{f(p)}}\subseteq A{{}_{f(q)}}$ ．
7. （2）观察发现， $f\left ({x}\right )+f\left ({-x}\right )=\frac {{\rm{e}}{^{x}}}{1+{\rm{e}}{^{x}}}+a\left ({x+1}\right )+bx{^{3}}+\frac {1}{1+{\rm{e}}{^{x}}}+a\left ({-x+1}\right )-bx{^{3}}=2a+1$ ，
8. 取 $s=2a+1$ ，下证 $A{{}_{t}}$ 与 $B{{}_{2a+1-t}}$ 互为对偶集，
9. $\forall x\in A{{}_{t}}$ ， $f\left ({x}\right )>t$ ，则 $2a+1-f\left ({-x}\right )>t$ ，
10. 即 $f\left ({-x}\right )<2a+1-t$ ，
11. 由定义知 $-x\in B{{}_{2a+1-t}}$ ．
12. 同理可知， $\forall x\in B{{}_{2a+1-t}}$ ， $-x\in A{{}_{t}}$ ．
13. 故当 $s=2a+1$ 时， $A{{}_{t}}$ 与 $B{{}_{s-t}}$ 互为对偶集．
14. （3）构造函数 $g\left ({x}\right )=f\left ({x}\right )-\frac {1}{2}$ ，
15. 则 $A{{}_{\frac {1}{2}}}=\left ({0,+\infty }\right )$ ，即 $g\left ({x}\right )>0$ 的充分必要条件为 $x\in \left ({0,+\infty }\right )$ ，
16. 若 $g\left ({0}\right )<0$ ，又 $g\left ({1}\right )>0$ ，由于 $g\left ({x}\right )$ 的图象在 $\left [0,1\right ]$ 上连续不断，
17. 故 $\exists x{{}_{0}}\in \left ({0,1}\right )$ ，使得 $g\left ({x{{}_{0}}}\right )=0$ ，
18. 则与 $A{{}_{\frac {1}{2}}}=\left ({0,+\infty }\right )$ 矛盾，
19. 因此 $g\left ({0}\right )=0$ ，代入解得 $a=0$ ．
20. 若 $b<0$ ，则 $f\left ({\sqrt[3]{-\frac {1}{b}}}\right )=\frac {1}{1+{\rm{e}}-\sqrt[3]{\frac {-1}{b}}}+b{\left({\sqrt[3]{-\frac {1}{b}}}\right)^{3}}=\frac {1}{1+{\rm{e}}\sqrt[3]{\frac {1}{b}}}-1<0$ ，不符合题意，舍去．
21. 若 $b\geqslant 0$ ，此时 $f\prime \left ({x}\right )=\frac {{\rm{e}}{^{x}}}{{\left({1+{\rm{e}}{^{x}}}\right)^{2}}}+3bx{^{2}}>0$ 在 ${\mathbf{R}}$ 上恒成立，
22. 此时 $f\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上单调递增，则 $g\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上单调递增，
23. 又 $g\left ({0}\right )=0$ ，所以 $g\left ({x}\right )>0$ 在 $\left ({0,+∞}\right )$ 上恒成立，符合题意．
24. 综上，b的取值范围为 $\left [{0,+\infty }\right )$ ．

## 知识点

**中文**:
  - 利用导数解决不等式恒成立问题
  - 集合的新定义问题

**English**:
  - Solving Universally True Inequalities
  - New Definition Problems in Sets

---
