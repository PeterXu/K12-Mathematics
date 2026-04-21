# Mathematics - 题目 1362

**ID**: 105d08436d4c408eaf0a59e6599d814f
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Fill-in-the-blank

## 题目
已知函数 $f\left ({x}\right )=\frac {3a{^{x}}-1}{a{^{x}}+1}$ （ $a>0$ 且 $a\ne 1$ ），若 $\exists x\in \left ({0,3}\right )$ ， $f\left ({x{^{2}}+3}\right )+f\left ({-ax-a}\right )-2\geqslant 0$ 是假命题，则实数a的取值范围是．​​​​​​​‌

## 解答

1. 因为 $f\left ({x}\right )=\frac {3a{^{x}}-1}{a{^{x}}+1}=\frac {3\left ({a{^{x}}+1}\right )-4}{a{^{x}}+1}=3-\frac {4}{a{^{x}}+1}$ ，
2. 若 $a>1$ ，由于 $y=\frac {4}{a{^{x}}+1}$ 单调递减，则 $f\left ({x}\right )$ 在R上单调递增；
3. 若 $0<a<1$ ，由于 $y=\frac {4}{a{^{x}}+1}$ 单调递增，则 $f\left ({x}\right )$ 在R上单调递减，
4. 又 $f\left ({x}\right )+f\left ({-x}\right )=6-\frac {4}{a{^{x}}+1}-\frac {4}{a{^{-x}}+1}=2$ ，故 $2-f\left ({-x}\right )=f\left ({x}\right )$ ，
5. 因为 $\exists x\in \left ({0,3}\right )$ ， $f\left ({x{^{2}}+3}\right )+f\left ({-ax-a}\right )-2\geqslant 0$ 是假命题，
6. 故 $\forall x\in \left ({0,3}\right )$ ， $f\left ({x{^{2}}+3}\right )+f\left ({-ax-a}\right )-2<0$ 恒成立为真命题，
7. 即不等式 $f\left ({x{^{2}}+3}\right )<2-f\left ({-ax-a}\right )=f\left ({ax+a}\right )$ 对 $\forall x\in \left ({0,3}\right )$ 恒成立，
8. 当 $a>1$ 时， $x{^{2}}+3<a\left ({x+1}\right )\Rightarrow \frac {x{^{2}}+3}{x+1}<a$ ，即 $\left ({x+1}\right )+\frac {4}{x+1}-2<a$ 在 $\forall x\in \left ({0,3}\right )$ 恒成立，
9. 设 $t=x+1\left ({1<t<4}\right )$ ，即 $a>t+\frac {4}{t}-2$ 在 $t\in \left ({1,4}\right )$ 恒成立．
10. 由于对勾函数 $h\left ({t}\right )=t+\frac {4}{t}-2$ 在 $\left ({1,2}\right )$ 单调递减，在 $\left ({2,4}\right )$ 单调递增，
11. 因为 $h\left ({t}\right )<h\left ({1}\right )=h\left ({4}\right )=3$ ，因此 $a\geqslant 3$ ；
12. 当 $0<a<1$ 时， $x{^{2}}+3>a\left ({x+1}\right )\Rightarrow a<\frac {x{^{2}}+3}{x+1}$ ，
13. 即 $a<\left ({x+1}\right )+\frac {4}{x+1}-2$ 在 $\forall x\in \left ({0,3}\right )$ 恒成立，
14. 当 $t=2$ 时，函数 $h\left ({t}\right )=t+\frac {4}{t}-2$ 有最小值 $f\left ({2}\right )=2$ ，
15. 即 $a<2$ ，又因为 $0<a<1$ ，故 $0<a<1$ ．综上可知： $\left \{\left .{a}\right |0<a<1\right.$ 或 $\left.a\geqslant 3\right \}$ ．
16. 故答案为： $\left \{\left .{a}\right |0<a<1\right.$ 或 $\left.a\geqslant 3\right \}$
17. 【点睛】方法点睛：存在量词命题是假命题，则其否定是真命题.当命题正面求解困难时，可利用命题的否定来进行求解.含参数的不等式恒成立问题，可以利用分离常数法进行求解，分离参数时，要注意不等式的符号.

## 知识点

**中文**:
  - 利用导数解决不等式能成立问题

**English**:
  - Solving Solvable Inequality Problems

---
