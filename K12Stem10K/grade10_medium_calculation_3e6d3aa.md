# Mathematics - 题目 2173

**ID**: 3e6d3aae4b4c4f328f7158b3b1616062
**年级**: Grade 10
**难度**: Medium
**题型**: Calculation

## 题目
已知定义域为R的函数 $f\left ({x}\right )=\frac {2{^{x}}+n}{2{^{x+1}}+m}$ 是奇函数.​​​​​​​‌(1)求实数 $m，n$ 的值；(2)判断 $f\left ({x}\right )$ 的单调性，并用单调性的定义证明；(3)当 $x\in \left [\frac {1}{3},3\right ]$ 时， $f\left ({kx{^{2}}}\right )+f\left ({2x-1}\right )>0$ 恒成立，求实数 $k{~}$ 的取值范围.

## 解答

1. （1）因为 $f\left ({x}\right )$ 是定义在R上的奇函数，
2. 所以 $f\left ({0}\right )=0$ ，所以 $n=-1$ ，
3. 又由 $f\left ({-1}\right )=-f\left ({1}\right )$ ，得 $m=2$ .
4. 此时， $f\left ({x}\right )=\frac {2{^{x}}-1}{2{^{x+1}}+2}$ ，
5. 又 $f\left ({-x}\right )=\frac {2{^{-x}}-1}{2{^{1-x}}+2}=\frac {1-2{^{x}}}{2+2{^{x+1}}}=-f\left ({x}\right )$ ，符合奇函数的定义，
6. 所以 $m=2$ ， $n=-1$ .
7. （2）函数 $f\left ({x}\right )$ 在R上单调递增.
8. 证明：由（1）知 $f\left ({x}\right )=\frac {2{^{x}}-1}{2{^{x+1}}+2}=\frac {1}{2}-\frac {1}{2{^{x}}+1}$ ，
9. 任取 $x{{}_{1}},x{{}_{2}}\in {\mathbf{R}}$ ，设 $x{{}_{1}}<x{{}_{2}}$ ，则 $f\left ({x{{}_{2}}}\right )-f\left ({x{{}_{1}}}\right )=\frac {1}{2{^{x{{}_{1}}}}+1}-\frac {1}{2{^{x{{}_{2}}}}+1}=\frac {2{^{x{{}_{2}}}}-2{^{x{{}_{1}}}}}{\left ({2{^{x{{}_{1}}}}+1}\right )\left ({2{^{x{{}_{2}}}}+1}\right )}$ ，
10. 因为函数 $y=2{^{x}}$ 在R上是增函数，
11. 所以 $2{^{x{{}_{2}}}}-2{^{x{{}_{1}}}}>0$ ， $\left ({2{^{x{{}_{1}}}}+1}\right )\left ({2{^{x{{}_{2}}}}+1}\right )>0$ ，
12. 所以 $f\left ({x{{}_{2}}}\right )-f\left ({x{{}_{1}}}\right )>0$ ，即 $f\left ({x{{}_{2}}}\right )>f\left ({x{{}_{1}}}\right )$ ，
13. 所以函数 $f\left ({x}\right )$ 在R上是增函数.
14. （3）因为 $f\left ({x}\right )$ 是奇函数，
15. 所以不等式 $f\left ({kx{^{2}}}\right )+f\left ({2x-1}\right )>0$ 等价于 $f\left ({kx{^{2}}}\right )>-f\left ({2x-1}\right )=f\left ({1-2x}\right )$ .
16. 又 $f\left ({x}\right )$ 在R上是增函数，故 $kx{^{2}}>1-2x$ ，
17. 即对任意 $x\in \left [\frac {1}{3},3\right ]$ 有 $k>\frac {1-2x}{x{^{2}}}={\left({\frac {1}{x}}\right)^{2}}-2\cdot \frac {1}{x}$ 恒成立.
18. 令 $t=\frac {1}{x}$ ， $t\in \left [\frac {1}{3},3\right ]$ ，则有 $g\left ({t}\right )=t{^{2}}-2t$ ， $t\in \left [\frac {1}{3},3\right ]$ ，
19. 所以 $g\left ({t}\right ){{}_{\max }}=g\left ({3}\right )=3$ ，
20. 所以 $k>3$ ，即k的取值范围为 $\left ({3,+\infty }\right )$ .

## 知识点

**中文**:
  - 与函数有关的恒成立问题
  - 函数单调性的判断与证明
  - 函数奇偶性的应用

**English**:
  - Universally True Problems Related to Functions
  - Judgment and Proof of Monotonicity
  - Applications of Parity

---
