# Mathematics - 题目 2262

**ID**: fa944149548f483e9adf4b1929d7dd6a
**年级**: Grade 11
**难度**: Hard
**题型**: Calculation

## 题目
若对 $\forall x{{}_{1}},x{{}_{2}}\in D$ 且 $x{{}_{1}}<x{{}_{2}}$ ，函数 $f\left ({x}\right )$ ， $g\left ({x}\right )$ 满足： $\left |{f\left ({x{{}_{1}}}\right )-f\left ({x{{}_{2}}}\right )}\right |\geqslant m\left |{g\left ({x{{}_{1}}}\right )-g\left ({x{{}_{2}}}\right )}\right |\left ({m>0}\right )$ ，则称函数 $f\left ({x}\right )$ 是函数 $g\left ({x}\right )$ 在区间 $D$ 上的 $m$ 级控制函数．(1)判断函数 $f\left ({x}\right )=2x$ 是否是函数 $g\left ({x}\right )=x{^{2}}$ 在区间 $\left [-1,1\right ]$ 上的1级控制函数，并说明理由；​​​​​​​‌(2)若函数 $f\left ({x}\right )={\rm{e}}{^{x}}$ 是函数 $g\left ({x}\right )=x$ 在区间 $\left [0,3\right ]$ 上的 $m$ 级控制函数，求实数 $m$ 的取值范围；(3)若函数 $f\left ({x}\right )$ 是函数 $g\left ({x}\right )={\ln}x-x$ 在区间 $\left ({0,+\infty }\right )$ 上的 $m$ 级控制函数，且函数 $f\left ({x}\right )$ 在区间 $\left ({0,+\infty }\right )$ 上存在两个零点 $a,\,b$ ，求证 $a+b>2$ ．

## 解答

1. （1）函数 $f\left ({x}\right )=2x$ 是函数 $g\left ({x}\right )=x{^{2}}$ 在区间 $\left [-1,1\right ]$ 上的1级控制数．
2. 理由如下：因为 $x{{}_{1}}<x{{}_{2}}$ ，且 $x{{}_{1}},x{{}_{2}}\in \left [-1,1\right ]$ ，所以 $\left |{x{{}_{1}}+x{{}_{2}}}\right |<2,\,\left |{x{{}_{1}}-x{{}_{2}}}\right |\ne 0$ ，
3. 所以 $2\left |{x{{}_{1}}-x{{}_{2}}}\right |\geqslant \left |{x{{}_{1}}-x{{}_{2}}}\right |\cdot \left |{x{{}_{1}}+x{{}_{2}}}\right |=\left |{x{{}_{1}^{2}}-x{{}_{2}^{2}}}\right |$ ，即 $\left |{f\left ({x{{}_{1}}}\right )-f\left ({x{{}_{2}}}\right )}\right |\geqslant \left |{g\left ({x{{}_{1}}}\right )-g\left ({x{{}_{2}}}\right )}\right |$ 成立，
4. 所以函数 $f\left ({x}\right )=2x$ 是函数 $g\left ({x}\right )=x{^{2}}$ 在区间 $\left [-1,1\right ]$ 上的1级控制函数．
5. （2）由函数 $f\left ({x}\right )={\rm{e}}{^{x}}$ 是函数 $g\left ({x}\right )=x$ 在区间 $\left [0,3\right ]$ 上的 $m$ 级控制函数，
6. 得 $\left |{{\rm{e}}{^{x{{}_{1}}}}-{\rm{e}}{^{x{{}_{2}}}}}\right |\geqslant m\left |{x{{}_{1}}-x{{}_{2}}}\right |$ ，又 $x{{}_{1}}<x{{}_{2}}$ ，由指数函数性质得 $f\left ({x}\right )$ 在 $\left [0,\,3\right ]$ 上单调递增，
7. 所以 ${\rm{e}}{^{x{{}_{2}}}}-{\rm{e}}{^{x{{}_{1}}}}\geqslant mx{{}_{2}}-mx{{}_{1}}$ ，即 ${\rm{e}}{^{x{{}_{2}}}}-mx{{}_{2}}\geqslant {\rm{e}}{^{x{{}_{1}}}}-mx{{}_{1}}$ 恒成立．
8. 令 $h\left ({x}\right )={\rm{e}}{^{x}}-mx$ ，所以当 $x{{}_{1}}<x{{}_{2}}$ ，且 $x{{}_{1}},x{{}_{2}}\in \left [0,3\right ]$ 时， $h\left ({x{{}_{2}}}\right )\geqslant h\left ({x{{}_{1}}}\right )$ 恒成立，
9. 故 $h^{′}{\left ({x}\right )}\geqslant 0$ 在 $\left [0,3\right ]$ 上恒成立．因为 $h^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-m$ ，所以 ${\rm{e}}{^{x}}-m\mathrm{\geqslant }0$ 在 $\left [0,3\right ]$ 上恒成立，
10. 则 $m\leqslant {\rm{e}}{^{x}}$ 恒成立，即 $m\leqslant f\left ({x}\right ){{}_{\min }}$ ，由指数函数性质 $f\left ({x}\right )$ 在 $\left [0,3\right ]$ 上单调递增，
11. 故 $f\left ({x}\right ){{}_{\min }}=f\left ({0}\right )=1$ ，则 $m\mathrm{\leqslant }1$ ，由题意得 $m>0$ ，所以 $0<m\leqslant 1$ ，
12. 综上，可以得到实数 $m$ 的取值范围是 $\left ({0,1}\right ]$ ．
13. （3）证明：因为函数 $f\left ({x}\right )$ 在区间 $\left ({0,+\infty }\right )$ 上存在两个零点 $a,b$ ，
14. 所以我们不妨设 $a<b$ ，且 $f\left ({a}\right )=f\left ({b}\right )=0$ ，
15. 因为函数 $f\left ({x}\right )$ 是函数 $g\left ({x}\right )={\ln}x-x$ 在区间 $\left ({0,+\infty }\right )$ 上的 $m$ 级控制函数，
16. 所以 $\left |{f\left ({a}\right )-f\left ({b}\right )}\right |\geqslant m\left |{g\left ({a}\right )-g\left ({b}\right )}\right |\left ({m>0}\right )$ ，即 $0\geqslant m\left |{g\left ({a}\right )-g\left ({b}\right )}\right |\left ({m>0}\right ),\,g\left ({a}\right )=g\left ({b}\right )$ ，
17. 可以得到 ${\ln}a-a={\ln}b-b,{\ln}b-{\ln}a=b-a,\frac {{\ln}b-{\ln}a}{b-a}=1$ ．
18. 要证 $a+b>2$ ，即证 $\left ({a+b}\right )\cdot \frac {{\ln}b-{\ln}a}{b-a}>2$ ，即证 $\frac {\frac {b}{a}+1}{\frac {b}{a}-1}\cdot {\ln}\frac {b}{a}>2$ ，即证 ${\ln}\frac {b}{a}-2\cdot \frac {\frac {b}{a}-1}{\frac {b}{a}+1}>0$ ，
19. 令 $x=\frac {b}{a}>1$ ，构造 $φ\left ({x}\right )={\ln}x-2\cdot \frac {x-1}{x+1}$ ，所以 $φ^{′}{\left ({x}\right )}=\frac {1}{x}-\frac {4}{{\left({x+1}\right)^{2}}}=\frac {{\left({x-1}\right)^{2}}}{x{\left({x+1}\right)^{2}}}>0$ ，
20. 所以 $φ\left ({x}\right )$ 在 $\left ({1,+\infty }\right )$ 上单调递增，所以 $φ\left ({x}\right )>φ\left ({1}\right )=0$ ，即 $x=\frac {b}{a}>1$ 时， ${\ln}x-2\cdot \frac {x-1}{x+1}>0$ ，
21. 即 ${\ln}\frac {b}{a}-2\cdot \frac {\frac {b}{a}-1}{\frac {b}{a}+1}>0$ 成立，所以 $a+b>2$ 得证．

## 知识点

**中文**:
  - 利用导数解决函数零点问题
  - 利用导数解决新定义问题

**English**:
  - Solving Zero Point Problems
  - Solving New Definition Problems

---
