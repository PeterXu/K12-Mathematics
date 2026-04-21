# Mathematics - 题目 3410

**ID**: 39cded5e16c147bc8f5830f86a88d35a
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\left |{x-a}\right |-\frac {4}{x}+a$ ， $x\in \left [1,4\right ]$ ， $a\in {\mathbf{R}}$（1）若 $a=4$ ，写出函数 $f\left ({x}\right )$ 的单调区间，并证明其单调性；（2）若函数 $f\left ({x}\right )$ 在 $\left [1,a\right ]$ 上单调，且存在 $x{{}_{0}}\in \left [1,a\right ]$ ，使 $f\left ({x{{}_{0}}}\right )>-2$ 成立，求实数a的取值范围：（3）当 $a\in \left ({1,4}\right )$ 时，函数 $f\left ({x}\right )$ 的最大值为 $M\left ({a}\right )$ ，求 $M\left ({a}\right )$ 的解析式.​​​​​​​‌

## 解答

1. （1）当 $a=4$ 时， $f\left ({x}\right )=\left |{x-4}\right |-\frac {4}{x}+4=-x-\frac {4}{x}+8$ ，
2. $f\left ({x}\right )$ 的单调递增区间为 $\left [1,2\right ]$ ，单调递减区间为 $\left ({2,4}\right ]$ ．
3. 证明： $\forall x{{}_{1}}$ ， $x{{}_{2}}\in \left [1,4\right ]$ ，且 $x{{}_{1}}<x{{}_{2}}$ ，
4. 则 $f\left ({x{{}_{1}}}\right )-f\left ({x{{}_{2}}}\right )=-x{{}_{1}}-\frac {4}{x{{}_{1}}}+8+x{{}_{2}}+\frac {4}{x{{}_{2}}}-8$
5. $=x{{}_{2}}-x{{}_{1}}-\frac {4\left ({x{{}_{2}}-x{{}_{1}}}\right )}{x{{}_{1}}x{{}_{2}}}=\frac {\left ({x{{}_{2}}-x{{}_{1}}}\right )\left ({x{{}_{1}}x{{}_{2}}-4}\right )}{x{{}_{1}}x{{}_{2}}}$ ，
6. 因为 $x{{}_{1}}$ ， $x{{}_{2}}\in \left [1,4\right ]$ ，且 $x{{}_{1}}<x{{}_{2}}$ ，
7. 所以 $x{{}_{2}}-x{{}_{1}}>0$ ， $x{{}_{1}}x{{}_{2}}>0$ ，
8. 当 $x{{}_{1}}$ ， $x{{}_{2}}\in \left [1,2\right ]$ 时， $x{{}_{1}}x{{}_{2}}<4$ ，得 $f\left ({x{{}_{1}}}\right )-f\left ({x{{}_{2}}}\right )<0$ ，即 $f\left ({x{{}_{1}}}\right )<f\left ({x{{}_{2}}}\right )$ ；
9. 当 $x{{}_{1}}$ ， $x{{}_{2}}\in \left ({2,4}\right ]$ 时， $x{{}_{1}}x{{}_{2}}>4$ ，得 $f\left ({x{{}_{1}}}\right )-f\left ({x{{}_{2}}}\right )>0$ ，即 $f\left ({x{{}_{1}}}\right )>f\left ({x{{}_{2}}}\right )$ ；
10. 所以 $f\left ({x}\right )$ 在 $\left [1,2\right ]$ 上单调递增，在 $\left ({2,4}\right ]$ 上单调递减．
11. （2）当 $x\in \left [1,a\right ]$ ，时， $f\left ({x}\right )=-x-\frac {4}{x}+2a$ ，
12. 易知 $f\left ({x}\right )=-x-\frac {4}{x}+2a$ 的单调区间与 $y=-x-\frac {4}{x}+8$ 的单调区间一致，
13. 故由（1）知 $f\left ({x}\right )=-x-\frac {4}{x}+2a$ 在 $\left [1,2\right ]$ 上单调递增，在 $\left ({2,4}\right ]$ 上单调递减，
14. 因为函数 $f\left ({x}\right )$ 在 $\left [1,a\right ]$ 上单调，
15. 所以 $a\in \left ({1,2}\right ]$ ， $f\left ({x}\right )$ 在 $\left [1,a\right ]$ 上单调递增，
16. 又存在 $x{{}_{0}}\in \left [1,a\right ]$ ，使 $f\left ({x{{}_{0}}}\right )>-2$ 成立，
17. 所以 $f\left ({x}\right ){{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}=f\left ({a}\right )=a-\frac {4}{a}>-2$ ，
18. 即 $a{^{2}}+2a-4>0$ ，
19. 解得 $a>\sqrt {5}-1$ ，或 $a<-\sqrt {5}-1$ ，
20. 所以实数a的取值范围为 $\left ({\sqrt {5}-1,2}\right ]$ ．
21. （3）由题意，得 $f\left ({x}\right )=\begin{cases}-x-\frac {4}{x}+2a,1\leqslant x<a\\x-\frac {4}{x},a\leqslant x\leqslant 4\end{cases}$ ，
22. 易知 $f\left ({x}\right )=x-\frac {4}{x}$ 在区间 $\left [a,4\right ]$ 上单调递增，
23. ①当 $a\in \left ({1,2}\right ]$ 时， $f\left ({x}\right )$ 在 $\left [{1,a}\right )$ 上单调递增，在 $\left [a,4\right ]$ 上单调递增，则 $M\left ({a}\right )=f\left ({x}\right ){{}_{{\rm \max }}}=f\left ({4}\right )=3$ ；
24. ②当 $a\in \left ({2,4}\right )$ 时， $f\left ({x}\right )$ 在 $\left [1,2\right ]$ 上单调递增，在 $\left [2,a\right ]$ 上单调递减，在 $\left [a,4\right ]$ 上单调递增， $f\left ({2}\right )=2a-4$ ， $f\left ({4}\right )=3$ ，
25. 当 $2a-4>3$ ，即 $\frac {7}{2}<a<4$ 时， $M\left ({a}\right )=f\left ({x}\right ){{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}=f\left ({2}\right )=2a-4$ ；
26. 当 $2a-4\mathrm{\leqslant }3$ ，即 $2<a\leqslant \frac {7}{2}$ 时， $M\left ({a}\right )=f\left ({x}\right ){{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}=f\left ({4}\right )=3$ ；
27. 综上所述， $M\left ({a}\right )=\begin{cases}3,1<a\leqslant \frac {7}{2}\\2a-4,\frac {7}{2}<a<4\end{cases}$ ．

## 知识点

**中文**:
  - 与函数有关的参数问题
  - 函数单调性（单调区间）与最大（小）值的求法
  - 函数单调性的判断与证明

**English**:
  - Parameter Problems Related to Functions
  - Monotonicity and Extrema
  - Judgment and Proof of Monotonicity

---
