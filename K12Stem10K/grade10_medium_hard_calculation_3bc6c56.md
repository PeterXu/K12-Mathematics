# Mathematics - 题目 618

**ID**: 3bc6c567bf964a169590abb0093593df
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
对于函数 $y=f\left ({x}\right )$ ，记所有满足 $\forall s>t>0$ ，都有 $f\left ({s}\right ){\small \geqslant }f\left ({t}\right )$ 的函数构成集合 $A$ ；所有满足 $\forall s,t\in \left ({0,+\infty }\right )$ ，都有 $f\left ({s+t}\right )\geqslant f\left ({s}\right )+f\left ({t}\right )$ 的函数构成集合 $B$ .​​​​​​​‌(1)分别判断下列函数是否为集合 $B$ 中的元素，并说明理由，① $f\left ({x}\right )=2x+1$ ；② $f\left ({x}\right )=x{^{2}}$ ；(2)若 $f\left ({x}\right )={\log}{{}_{\frac {1}{2}}}\left ({x+a}\right )$ （ $a\geqslant 0$ ）是集合 $B$ 中的元素，求 $a$ 的最小值；(3)若 $g\left ({x}\right )=xf\left ({x}\right )$ ，求证： $f\left ({x}\right )\in A$ 是 $g\left ({x}\right )\in B$ 的充分不必要条件.

## 解答

1. （1）①不是.
2. 当 $s=t=1$ 时， $f\left ({s+t}\right )=f\left ({2}\right )=2\times 2+1=5$ ，
3. $f\left ({s}\right )+f\left ({t}\right )=3+3=6>f\left ({s+t}\right )$ ，
4. 所以 $f\left ({x}\right )=2x+1$ 不是集合 $B$ 中的元素；
5. ②是.
6. $\forall s,t\in \left ({0,+\infty }\right )$ ， $f\left ({s+t}\right )-f\left ({s}\right )-f\left ({t}\right )={\left({s+t}\right)^{2}}-s{^{2}}-t{^{2}}=2st>0$ ，
7. 所以 $f\left ({x}\right )=x{^{2}}$ 是集合 $B$ 中的元素.
8. （2）当 $a=1$ 时， $\forall s,t\in \left ({0,+\infty }\right )$ ， $f\left ({s+t}\right )={\log}{{}_{\frac {1}{2}}}\left ({s+t+1}\right )$ ，
9. $f\left ({s}\right )+f\left ({t}\right )={\log}{{}_{\frac {1}{2}}}\left ({s+1}\right )+{\log}{{}_{\frac {1}{2}}}\left ({t+1}\right )={\log}{{}_{\frac {1}{2}}}\left ({s+1}\right )\left ({t+1}\right )$ ，
10. 因为 $\left ({s+1}\right )\left ({t+1}\right )-\left ({s+t+1}\right )=st>0$ ， $y={\log}{{}_{\frac {1}{2}}}x$ 在 $\left ({0,+\infty }\right )$ 上单调递减，
11. 故 $f\left ({s+t}\right )\geqslant f\left ({s}\right )+f\left ({t}\right )$ 成立，即 $f\left ({x}\right )={\log}{{}_{\frac {1}{2}}}\left ({x+1}\right )\in B$ ；
12. 若 $0\leqslant a<1$ ，令 $s=t=\frac {1-a}{2}>0$ ， $f\left ({s+t}\right )={\log}{{}_{\frac {1}{2}}}\left ({s+t+a}\right )$ ，
13. $f\left ({s}\right )+f\left ({t}\right )={\log}{{}_{\frac {1}{2}}}\left ({s+a}\right )+{\log}{{}_{\frac {1}{2}}}\left ({t+a}\right )={\log}{{}_{\frac {1}{2}}}\left ({s+a}\right )\left ({t+a}\right )$ ，
14. 因为 $\left ({s+t+a}\right )-\left ({s+a}\right )\left ({t+a}\right )=1-{\left({\frac {1+a}{2}}\right)^{2}}>0$ ， $y={\log}{{}_{\frac {1}{2}}}x$ 在 $\left ({0,+\infty }\right )$ 上单调递减，
15. 所以 $f\left ({s+t}\right )<f\left ({s}\right )+f\left ({t}\right )$ ，因此 $f\left ({x}\right )={\log}{{}_{\frac {1}{2}}}\left ({x+a}\right )\notin B$ ，
16. 综上所述， $a$ 的最小值为1.
17. （3）充分性：因为 $f\left ({x}\right )\in A$ ，所以 $\forall s,t\in \left ({0,+\infty }\right )$ ， $s+t>s$ ， $f\left ({s+t}\right )\geqslant f\left ({s}\right )$ ，进而 $sf\left ({s+t}\right )\geqslant sf\left ({s}\right )$ ，
18. 同理 $tf\left ({s+t}\right )\geqslant tf\left ({t}\right )$ ，相加得 $\left ({s+t}\right )f\left ({s+t}\right ){\small \geqslant }sf\left ({s}\right )+tf\left ({t}\right )$ ，即 $xf(x)\in B$ ，所以充分性满足；
19. 必要性：设 $g\left ({x}\right )=\left [x\right ]$ ， $\forall s,t\in \left ({0,+\infty }\right )$ ， $\left [s\right ]+\left [t\right ]\leqslant \left [s+t\right ]$ ，
20. 所以 $g\left ({x}\right )=\left [x\right ]\in B$ ，此时 $f\left ({x}\right )=\frac {\left [x\right ]}{x}$ ，当 $1<x<2$ 时， $f\left ({x}\right )=\frac {1}{x}$ ，
21. 所以 $f\left ({x}\right )$ 在 $\left ({1,2}\right )$ 上单调递减，因此 $f\left ({x}\right )=\frac {\left [x\right ]}{x}\notin A$ ，所以必要性不满足；
22. 综上所述， $f\left ({x}\right )\in A$ 是 $g\left ({x}\right )\in B$ 的充分不必要条件.

## 知识点

**中文**:
  - 函数与不等式的综合问题

**English**:
  - Functions and Inequalities Combined

---
