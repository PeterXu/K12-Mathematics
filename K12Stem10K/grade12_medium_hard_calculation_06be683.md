# Mathematics - 题目 1369

**ID**: 06be683159c44cfb8349fa91cc7415c4
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=a\left ({{\rm{e}}{^{x}}-1}\right )-x{^{2}}+x$(1)当 $a=1$ 时，求 $f\left ({x}\right )$ 的图象在点 $\left ({0,f\left ({0}\right )}\right )$ 处的切线方程；(2)若 $a\geqslant 1$ ，证明：当 $x>0$ 时， $f\left ({x}\right )+{\cos}x>1$ .​​​​​​​‌

## 解答

1. （1）当 $a=1$ 时， $f\left ({x}\right )={\rm{e}}{^{x}}-1-x{^{2}}+x$ ， $\therefore f^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-2x+1$ ，
2. $\therefore f^{′}{\left ({0}\right )}=1-0+1=2$ ，又 $f\left ({0}\right )=1-1-0+0=0$ ，
3. $\therefore f\left ({x}\right )$ 在点 $\left ({0,f\left ({0}\right )}\right )$ 处的切线方程为： $y=2x$ .
4. （2）当 $a\geqslant 1$ ， $x>0$ 时， $f\left ({x}\right )+{\cos}x=a\left ({{\rm{e}}{^{x}}-1}\right )-x{^{2}}+x+{\cos}x\geqslant {\rm{e}}{^{x}}-1-x{^{2}}+x+{\cos}x$ ，
5. 方法一：要证 $f\left ({x}\right )+{\cos}x>1$ ，只需证 ${\rm{e}}{^{x}}-1-x{^{2}}+x+{\cos}x>1$ ，
6. 即证 $\left ({{\rm{e}}{^{x}}-\frac {3}{2}x{^{2}}+x}\right )+\left ({{\cos}x-1+\frac {1}{2}x{^{2}}}\right )>1$ ；
7. 令 $g\left ({x}\right )={\rm{e}}{^{x}}-\frac {3}{2}x{^{2}}+x\left ({x>0}\right )$ ，则 $g^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-3x+1$ ，
8. 令 $h\left ({x}\right )=g^{′}{\left ({x}\right )}$ ，则 $h^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-3$ ，
9. $\therefore $ 当 $x\in \left ({0,{\ln}3}\right )$ 时， $h^{′}{\left ({x}\right )}<0$ ；当 $x\in \left ({{\ln}3,+\infty }\right )$ 时， $h^{′}{\left ({x}\right )}>0$ ；
10. $\therefore h\left ({x}\right )$ 在 $\left ({0,{\ln}3}\right )$ 上单调递减，在 $\left ({{\ln}3,+\infty }\right )$ 上单调递增，
11. $\therefore h\left ({x}\right )\geqslant h\left ({{\ln}3}\right )=4-3{\ln}3={\ln}\frac {{\rm{e}}{^{4}}}{27}>0$ ，
12. $\therefore g\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上单调递增， $\therefore g\left ({x}\right )>g\left ({0}\right )=1$ ；
13. 令 $φ\left ({x}\right )={\cos}x-1+\frac {1}{2}x{^{2}}\left ({x>0}\right )$ ，则 $φ^{′}{\left ({x}\right )}=x-{\sin}x$ ，
14. 令 $m\left ({x}\right )=φ^{′}{\left ({x}\right )}$ ，则 $m^{′}{\left ({x}\right )}=1-{\cos}x\geqslant 0$ ， $\therefore m\left ({x}\right )$ 在 $\left ({0,+\mathrm{∞}}\right )$ 上单调递增，
15. $\therefore m\left ({x}\right )>m\left ({0}\right )=0$ ， $\therefore φ\left ({x}\right )$ 在 $\left ({0,+\mathrm{∞}}\right )$ 上单调递增， $\therefore φ\left ({x}\right )>φ\left ({0}\right )=0$ ；
16. $\therefore g\left ({x}\right )+φ\left ({x}\right )>1+0=1$ ，即 $\left ({{\rm{e}}{^{x}}-\frac {3}{2}x{^{2}}+x}\right )+\left ({{\cos}x-1+\frac {1}{2}x{^{2}}}\right )>1$ ，
17. $\therefore $ 当 $a\geqslant 1$ ， $x>0$ 时， $f\left ({x}\right )+{\cos}x>1$ .
18. 方法二：要证 $f\left ({x}\right )+{\cos}x>1$ ，只需证 ${\rm{e}}{^{x}}-1-x{^{2}}+x+{\cos}x>1$ ，
19. 令 $g\left ({x}\right )={\rm{e}}{^{x}}-1-x{^{2}}+x+{\cos}x\left ({x>0}\right )$ ，则 $g^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-2x+1-{\sin}x\geqslant {\rm{e}}{^{x}}-2x$ ，
20. 令 $h\left ({x}\right )={\rm{e}}{^{x}}-2x\left ({x>0}\right )$ ，则 $h^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-2$ ，
21. $\therefore $ 当 $x\in \left ({0,{\ln}2}\right )$ 时， $h^{′}{\left ({x}\right )}<0$ ；当 $x\in \left ({{\ln}2,+\infty }\right )$ 时， $h^{′}{\left ({x}\right )}>0$ ；
22. $\therefore h\left ({x}\right )$ 在 $\left ({0,{\ln}2}\right )$ 上单调递减，在 $\left ({{\ln}2,+\infty }\right )$ 上单调递增，
23. $\therefore h\left ({x}\right )\geqslant h\left ({{\ln}2}\right )=2-2{\ln}2=2\left ({1-{\ln}2}\right )>0$ ， $\therefore g^{′}{\left ({x}\right )}>0$ ，
24. $\therefore g\left ({x}\right )$ 在 $\left ({0,+\mathrm{∞}}\right )$ 上单调递增， $\therefore g\left ({x}\right )>g\left ({0}\right )=1$ ，即 ${\rm{e}}{^{x}}-1-x{^{2}}+x+{\cos}x>1$ ，
25. $\therefore $ 当 $a\geqslant 1$ ， $x>0$ 时， $f\left ({x}\right )+{\cos}x>1$ .

## 知识点

**中文**:
  - 利用导数证明不等式
  - 导数几何意义的应用

**English**:
  - Proving Inequalities using Derivatives
  - Applications of Geometric Meaning of Derivatives

---
