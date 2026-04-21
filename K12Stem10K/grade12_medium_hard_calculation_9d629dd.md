# Mathematics - 题目 1687

**ID**: 9d629ddb2dca44259b51385b8f629315
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设 $a,b\in {\mathbf{R}}$ ，函数 $f\left ({x}\right )=\left |{x{\rm{e}}{^{x}}-2x+a}\right |+\left |{x{\rm{e}}{^{x}}-x{^{2}}+b}\right |$ ， $g\left ({x}\right )=2x{\rm{e}}{^{x}}-x{^{2}}-2x+a+b,h\left ({x}\right )=x{^{2}}-2x+a-b,f\left ({x}\right ),g\left ({x}\right ),h\left ({x}\right )$ 的定义域都为 $\left [-\frac {1}{2},1\right ]$ .​​​​​​​‌(1)求 $g\left ({x}\right )$ 和 $h\left ({x}\right )$ 的值域；(2)用 ${\rm{m}}{\rm{a}}{\rm{x}}\left \{m,n\right \}$ 表示 $m,n$ 中的最大者，证明： $f\left ({x}\right )={\rm{m}}{\rm{a}}{\rm{x}}\left \{\left |{g\left ({x}\right )}\right |,\left |{h\left ({x}\right )}\right |\right \}$ ；(3)记 $f\left ({x}\right )$ 的最大值为 $F\left ({a,b}\right )$ ，求 $F\left ({a,b}\right )$ 的最小值.

## 解答

1. （1） $g^{′}{\left ({x}\right )}=2\left ({x+1}\right ){\rm{e}}{^{x}}-2x-2=2\left ({x+1}\right )\left ({{\rm{e}}{^{x}}-1}\right )$ ，
2. 因为当 $x\in \left ({-\frac {1}{2},0}\right )$ 时， $g^{′}{\left ({x}\right )}<0$ ；当 $x\in \left ({0,1}\right )$ 时， $g^{′}{\left ({x}\right )}>0$ ，
3. 所以 $g\left ({x}\right )$ 在 $\left ({-\frac {1}{2},0}\right )$ 上单调递减，在 $\left ({0,1}\right )$ 上单调递增，
4. 又 $g\left ({-\frac {1}{2}}\right )=-{\rm{e}}{^{-\frac {1}{2}}}+\frac {3}{4}+a+b,g\left ({1}\right )=2{\rm{e}}-3+a+b,g\left ({-\frac {1}{2}}\right )<g\left ({1}\right )$ ，
5. 所以 $g\left ({x}\right )$ 的值域为 $\left [g\left ({0}\right ),g\left ({1}\right )\right ]$ ，即 $\left [a+b,2{\rm{e}}-3+a+b\right ]$ .
6. 因为 $h\left ({x}\right )=x{^{2}}-2x+a-b=(x-1){^{2}}+a-b-1,x\in \left [-\frac {1}{2},1\right ]$ 是减函数，
7. 所以 $h\left ({x}\right )$ 的值域为 $\left [h\left ({1}\right ),h\left ({-\frac {1}{2}}\right )\right ]$ ，即 $\left [a-b-1,a-b+\frac {5}{4}\right ]$ .
8. （2）当 $\left |{m+n}\right |\geqslant \left |{m-n}\right |$ 时， $\left |{m+n|{^{2}}\geqslant }\right |m-n|{^{2}}$ ，即 $mn\geqslant 0$ ，
9. 从而 $\left |{m}\right |+\left |{n}\right |=\left |{m+n}\right |;$
10. 当 $\left |{m+n}\right |<\left |{m-n}\right |$ 时， $|m+n|{^{2}}<|m-n|{^{2}}$ ，即 $mn<0$ ，
11. 从而 $\left |{m}\right |+\left |{n}\right |=\left |{m-n}\right |$ ，
12. 所以 $\left |{m}\right |+\left |{n}\right |={\rm{m}}{\rm{a}}{\rm{x}}\left \{\left |{m+n}\right |,\left |{m-n}\right |\right \}$ ，
13. 所以 $f(x)={\rm \max }\left \{\left |{\left ({x{\rm{e}}{^{x}}-2x+a}\right )+\left ({x{\rm{e}}{^{x}}-x{^{2}}+b}\right )}\right |,\left |{\left ({x{\rm{e}}{^{x}}-2x+a}\right )-\left ({x{\rm{e}}{^{x}}-x{^{2}}+b}\right )}\right |\right \}$ . $={\rm{m}}{\rm{a}}{\rm{x}}\left \{\left |{2x{\rm{e}}{^{x}}-x{^{2}}-2x+a+b}\right |,\left |{x{^{2}}-2x+a-b}\right |\right \}$
14. $={\rm{m}}{\rm{a}}{\rm{x}}\left \{\left |{g\left ({x}\right )}\right |,\left |{h\left ({x}\right )}\right |\right \}$ .
15. （3）由（1），得 $|g\left ({x}\right )|{{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}={\rm{m}}{\rm{a}}{\rm{x}}\left \{\left |{g\left ({0}\right )}\right |,\left |{g\left ({1}\right )}\right |\right \}$ ，
16. $|h\left ({x}\right )|{{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}={\rm{m}}{\rm{a}}{\rm{x}}\left \{\left |{h\left ({1}\right )}\right |,\left |{h\left ({-\frac {1}{2}}\right )}\right |\right \}$ ，
17. 再结合（2），得 $F\left ({a,b}\right )=[f\left ({x}\right )]{{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}={\rm{m}}{\rm{a}}{\rm{x}}\left \{\left |{g\left ({x}\right )|{{}_{{\rm{m}}{\rm{a}}{\rm{x}}}},}\right |h\left ({x}\right )|{{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}\right \}$
18. $={\rm{m}}{\rm{a}}{\rm{x}}\left \{\left |{g\left ({0}\right )}\right |,\left |{g\left ({1}\right )}\right |,\left |{h\left ({1}\right )}\right |,\left |{h\left ({-\frac {1}{2}}\right )}\right |\right \}$ ，
19. 所以 $F\left ({a,b}\right )\geqslant \left |{g\left ({0}\right )}\right |,F\left ({a,b}\right )\geqslant \left |{g\left ({1}\right )}\right |$ ，
20. 所以 $F\left ({a,b}\right )\geqslant \frac {\left |{g\left ({0}\right )}\right |+\left |{g\left ({1}\right )}\right |}{2}\geqslant \frac {\left |{g\left ({0}\right )-g\left ({1}\right )}\right |}{2}$
21. $=\frac {\left |{\left ({a+b}\right )-\left ({2{\rm{e}}-3+a+b}\right )}\right |}{2}=\frac {2{\rm{e}}-3}{2}$ ，
22. 又当 $g\left ({0}\right )=a+b=-\frac {2{\rm{e}}-3}{2},g\left ({1}\right )=2{\rm{e}}-3+a+b=\frac {2{\rm{e}}-3}{2}$ ，
23. $\left |{h\left ({1}\right )}\right |=\left |{a-b-1}\right |\leqslant \frac {2{\rm{e}}-3}{2},\left |{h\left ({-\frac {1}{2}}\right )}\right |=\left |{a-b+\frac {5}{4}}\right |\leqslant \frac {2{\rm{e}}-3}{2}$ ，
24. （可取 $a=2-{\rm{e}},b=-\frac {1}{2}$ ）时， $F\left ({a,b}\right )=\frac {2{\rm{e}}-3}{2}$ ，
25. 所以 $F\left ({a,b}\right )$ 的最小值为 $\frac {2{\rm{e}}-3}{2}$ .

## 知识点

**中文**:
  - 函数新定义问题
  - 利用导数研究函数的最值

**English**:
  - New Definition Problems in Functions
  - Global Extrema (Max/Min) using Derivatives

---
