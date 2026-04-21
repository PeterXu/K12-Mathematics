# Mathematics - 题目 1752

**ID**: c4b1f912e750466798a6e4fab0f19cde
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=t\left ({x-1}\right )-{\ln}x\left ({t\in {\rm{R}}}\right )$ .​​​​​​​‌(1)若 $f\left ({x}\right )\geqslant 0$ 恒成立，求实数 $t$ 的值；(2)当 $t=0$ 时，方程 $f\left ({x}\right )+x{^{2}}-x=m$ 有两个不同的根，分别为 $x{{}_{1}},x{{}_{2}}\left ({x{{}_{1}}<x{{}_{2}}}\right )$ .①求实数 $m$ 的取值范围；②求证： ${\ln}x{{}_{1}}+x{{}_{2}}>1-m$ .

## 解答

1. （1） $f^{′}{\left ({x}\right )}=t-\frac {1}{x}$ ， $\because f\left ({1}\right )=0\therefore f\left ({x}\right )\geqslant 0\Leftrightarrow f\left ({x}\right )\geqslant f\left ({1}\right )$ ．
2. 由于 $x=1$ 不是定义域区间的端点，且 $f\left ({x}\right )$ 在定义域上连续，
3. 故： $f\left ({1}\right )$ 不仅是函数 $f\left ({x}\right )$ 的最小值，同时也是极小值．
4. $f^{′}{\left ({1}\right )}=0\Rightarrow t-1=0\Rightarrow t=1$ ．
5. 检验：当 $t=1$ 时，
6. $f\left ({x}\right )=x-1-{\ln}x$ ， $f^{′}{\left ({x}\right )}=1-\frac {1}{x}=\frac {x-1}{x}$
7. 当 $0<x<1$ 时， $f^{′}{\left ({x}\right )}<0$ ， $f\left ({x}\right )$ 单调递减，当 $x>1$ 时， $f^{′}{\left ({x}\right )}>0$ ， $f\left ({x}\right )$ 单调递增．
8. 所以：  $f\left ({x}\right )\geqslant f\left ({1}\right )=0$ 成立，
9. 故： $t=1$
10. （2）①当 $t=0$ 时， $g\left ({x}\right )=f\left ({x}\right )+x{^{2}}-x=x{^{2}}-x-{\ln}x$ ， $g^{′}{\left ({x}\right )}=2x-1-\frac {1}{x}=\frac {\left ({2x+1}\right )\left ({x-1}\right )}{x}$
11. 令： $g^{′}{\left ({x}\right )}>0\Rightarrow x>1$ ；同理： $g^{′}{\left ({x}\right )}<0\Rightarrow 0<x<1$
12. 所以 $g\left ({x}\right )$  在 $\left ({0，1}\right )$ 上单调递减，在 $\left ({1，+∞}\right )$ 上单调递增.
13. 当 $x\to 0$ 时， $g\left ({x}\right )\to +∞$ ；当 $x\to +\infty $ 时， $g\left ({x}\right )\to +∞$ ；
14. 且 $g\left ({1}\right )=0$ ；所以方程 $f\left ({x}\right )+x{^{2}}-x=m$ 有两个不同的根时， $m\in \left ({0,+∞}\right )$ ．
15. 
16. ②由题可知： $g\left ({x{{}_{1}}}\right )=g\left ({x{{}_{2}}}\right )=m$ ，
17. 即 $x{{}_{1}^{2}}-x{{}_{1}}-{\ln}x{{}_{1}}=x{{}_{2}^{2}}-x{{}_{2}}-{\ln}x{{}_{2}}=m$ 且 $0<x{{}_{1}}<1<x{{}_{2}}$
18. 构造函数 $h\left ({x}\right )=g\left ({x}\right )-g\left ({2-x}\right )\left ({0<x<1}\right )$
19. $h^{′}{\left ({x}\right )}=g^{′}{\left ({x}\right )}+g^{′}{\left ({2-x}\right )}=2x-1-\frac {1}{x}+2\left ({2-x}\right )-1-\frac {1}{2-x}=\frac {-2{\left({x-1}\right)^{2}}}{x\left ({2-x}\right )}<0$
20. 所以 $h\left ({x}\right )$ 在 $\left ({0，1}\right )$ 上单调递减，故 $h\left ({x}\right )>h\left ({1}\right )=g\left ({1}\right )-g\left ({2-1}\right )=0$ ．
21. 所以 $g\left ({x}\right )>g\left ({2-x}\right )$ ，
22. 又因为 $0<x{{}_{1}}<1$ 所以： $g\left ({x{{}_{1}}}\right )>g\left ({2-x{{}_{1}}}\right )$ ，
23. 又因为 $g\left ({x{{}_{1}}}\right )=g\left ({x{{}_{2}}}\right )$ ，所以： $g\left ({x{{}_{2}}}\right )>g\left ({2-x{{}_{1}}}\right )$
24. 因为 $g\left ({x}\right )$  在 $\left ({1，+∞}\right )$ 单调递增， $2-x{{}_{1}}>1,x{{}_{2}}>1$
25. 所以 $x{{}_{2}}>2-x{{}_{1}}\Leftrightarrow x{{}_{1}}+x{{}_{2}}>2$ ．
26. 要证： ${\ln}x{{}_{1}}+x{{}_{2}}>1-m$ ，
27. 即证： ${\ln}x{{}_{1}}+x{{}_{2}}>1-\left ({x{{}_{1}}{^{2}}-x{{}_{1}}-{\ln}x{{}_{1}}}\right )$ ，
28. 即 $x{{}_{2}}>1-x{{}_{1}}{^{2}}+x{{}_{1}}$
29. 只须证明： $x{{}_{2}}+x{{}_{1}}>1-x{{}_{1}}{^{2}}+x{{}_{1}}+x{{}_{1}}$ ，
30. 即证： $x{{}_{2}}+x{{}_{1}}>1-x{{}_{1}}{^{2}}+2x{{}_{1}}$
31. 因为： $x{{}_{1}}+x{{}_{2}}>2$ ，故只须证明： $1-x{{}_{1}}{^{2}}+2x{{}_{1}}\leqslant 2$
32. 因为 $1-x{{}_{1}}{^{2}}+2x{{}_{1}}=2-x{{}_{1}}{^{2}}+2x{{}_{1}}-1=2-{\left({x{{}_{1}}-1}\right)^{2}}<2$ 成立．
33. 所以原不等式 ${\ln}x{{}_{1}}+x{{}_{2}}>1-m$ 成立，证毕.

## 知识点

**中文**:
  - 利用导数研究方程的根
  - 利用导数证明不等式
  - 利用导数解决不等式恒成立问题

**English**:
  - Studying Equation Roots
  - Proving Inequalities using Derivatives
  - Solving Universally True Inequalities

---
