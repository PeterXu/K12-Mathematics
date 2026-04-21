# Mathematics - 题目 1241

**ID**: 8dc40f3669e74f1d84822bdd9865fb05
**年级**: Grade 11
**难度**: Medium
**题型**: Fill-in-the-blank

## 题目
对任意 $x\in (1,+\infty )$ ，函数 $f(x)=a{^{x}}{\ln}a-a{\ln}(x-1)\mathrm{\geqslant }0(a>1)$ 恒成立，则a的取值范围为．​​​​​​​‌

## 解答

1. 由题意得 $a{^{x-1}}{\ln}a\mathrm{\geqslant }{\ln}(x-1)$ ，
2. 因为 $x\in (1,+\infty )$ ，所以 $\left ({x-1}\right )a{^{x-1}}{\ln}a\mathrm{\geqslant }\left ({x-1}\right ){\ln}\left ({x-1}\right )$ ，
3. 即 $a{^{x-1}}{\ln}a{^{x-1}}\mathrm{\geqslant }\left ({x-1}\right ){\ln}\left ({x-1}\right )$ ，
4. 令 $F\left ({t}\right )=t{\ln}t,t>0$ ，则 $F\left ({a{^{x-1}}}\right )\mathrm{\geqslant }F\left ({x-1}\right )$ 恒成立，
5. 因为 $F^{′}{\left ({t}\right )}=1+{\ln}t$ ，
6. 令 $F^{′}{\left ({t}\right )}>0$ 得， $t>{\rm{e}}{^{-1}}$ ， $F\left ({t}\right )=t{\ln}t$ 单调递增，
7. 令 $F^{′}{\left ({t}\right )}<0$ 得， $0<t<{\rm{e}}{^{-1}}$ ， $F\left ({t}\right )=t{\ln}t$ 单调递减，
8. 且当 $0<t\mathrm{\leqslant }1$ 时， $F\left ({t}\right )\mathrm{\leqslant }0$ 恒成立，当 $t>1$ 时， $F\left ({t}\right )>0$ 恒成立，
9. 因为 $a>1,x>1$ ，所以 $a{^{x-1}}>1$ 恒成立，故 $F\left ({a{^{x-1}}}\right )>0$ ，
10. 当 $x-1\in \left ({0,1}\right ]$ 时， $F\left ({x-1}\right )\mathrm{\leqslant }0$ ，此时满足 $F\left ({a{^{x-1}}}\right )\mathrm{\geqslant }F\left ({x-1}\right )$ 恒成立，
11. 当 $x-1>1$ ，即 $x>2$ 时，由于 $F\left ({t}\right )=t{\ln}t$ 在 $t\in \left ({{\rm{e}}{^{-1}},+\mathrm{∞}}\right )$ 上单调递增，
12. 由 $F\left ({a{^{x-1}}}\right )\mathrm{\geqslant }F\left ({x-1}\right )$ 得 $a{^{x-1}}\mathrm{\geqslant }x-1\Rightarrow {\ln}a\mathrm{\geqslant }\frac {{\ln}\left ({x-1}\right )}{x-1}$ ，
13. 令 $u=x-1>1$ ， $g\left ({u}\right )=\frac {{\ln}u}{u}$ ，
14. 则 $g^{′}{\left ({u}\right )}=\frac {1-{\ln}u}{u{^{2}}}$ ，当 $u\in \left ({1,{\rm{e}}}\right )$ 时， $g^{′}{\left ({u}\right )}>0$ ， $g\left ({u}\right )=\frac {{\ln}u}{u}$ 单调递增，
15. 当 $u\in \left ({{\rm{e}}{\rm{,}}{{+}}\mathrm{∞}}\right )$ 时， $g^{′}{\left ({u}\right )}<0$ ， $g\left ({u}\right )=\frac {{\ln}u}{u}$ 单调递减，
16. 故 $g\left ({u}\right )=\frac {{\ln}u}{u}$ 在 $u={\rm{e}}$ 处取得极大值，也是最大值， $g\left ({{\rm{e}}}\right )=\frac {{\ln}{\rm{e}}}{{\rm{e}}}=\frac {1}{{\rm{e}}}$ ，
17. 故 ${\ln}a\mathrm{\geqslant }\frac {1}{{\rm{e}}}$ ，即 $a\mathrm{\geqslant }{\rm{e}}{^{\frac {1}{{\rm{e}}}}}$ ，所以，a的取值范围是 $\left [{{\rm{e}}{^{\frac {1}{{\rm{e}}}}},+\mathrm{∞}}\right )$ .
18. 故答案为： $\left [{{\rm{e}}{^{\frac {1}{{\rm{e}}}}},+\mathrm{∞}}\right )$ .

## 知识点

**中文**:
  - 利用导数解决不等式恒成立问题

**English**:
  - Solving Universally True Inequalities

---
