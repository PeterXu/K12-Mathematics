# Mathematics - 题目 1497

**ID**: 7df8fcfd60774a9499343f9eee1bfbdd
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\frac {1}{ax}+{\ln}x$ ， $g(x)=\frac {x}{{\rm{e}}{{}^{ax}}}+\frac {1}{2}-{\ln}a$ （ ${\rm{e}}$ 为自然对数的底数）(1)当 $a=1$ 时，求 $f\left ({x}\right )$ 的单调区间；(2) $a>0$ 时，若函数 $y=f(x)$ 与 $y=g(x)$ 的图象有且仅有一个公共点.​​​​​​​‌（i）求实数 $a$ 的集合；（ii）设经过点 $\left ({b,c}\right )$ 有且仅有3条直线与函数 $y=f\left ({x}\right )$ 的图象相切，求证：当 $b>{\rm{e}}$ 时， $\frac {1}{2}\left ({1-\frac {b}{{\rm{e}}}}\right )+c<f(b)<c$ .

## 解答

1. （1）当 $a=1$ 时， $f\left ({x}\right )=\frac {1}{x}+{\ln}x$ ， $x>0$ ，
2. $f^{′}{\left ({x}\right )}=-\frac {1}{x{{}^{2}}}+\frac {1}{x}=\frac {x-1}{x{{}^{2}}}$ ，
3. 当 $0<x<1$ 时， $f^{′}{\left ({x}\right )}<0$ ，所以 $f\left ({x}\right )$ 在区间 $\left ({0,1}\right )$ 上单调递减，
4. 当 $x>1$ 时， $f^{′}{\left ({x}\right )}>0$ ，所以 $f\left ({x}\right )$ 在区间 $\left ({1,+\infty }\right )$ 上单调递增，
5. 所以当 $a=1$ 时， $f\left ({x}\right )$ 的单调递增区间为 $\left ({1,+\infty }\right )$ ，单调递减区间为 $\left ({0,1}\right )$ .
6. （2）（i） $f^{′}{\left ({x}\right )}=-\frac {1}{ax{{}^{2}}}+\frac {1}{x}=\frac {ax-1}{x{{}^{2}}}$ ，
7. 因 $a>0$ ，当 $0<x<\frac {1}{a}$ 时， $f^{′}{\left ({x}\right )}<0$ ，所以 $f\left ({x}\right )$ 在区间 $\left ({0,\frac {1}{a}}\right )$ 上单调递减，
8. 当 $x>\frac {1}{a}$ 时， $f^{′}{\left ({x}\right )}>0$ ，所以 $f\left ({x}\right )$ 在区间 $\left ({\frac {1}{a},+\infty }\right )$ 上单调递增，
9. $f\left ({x}\right )$ 在 $x=\frac {1}{a}$ 处取得最小值；
10. $g^{′}(x)=\frac {{\rm{e}}{{}^{ax}}-ax{\rm{e}}{{}^{ax}}}{{\rm{e}}{{}^{2ax}}}=\frac {1-ax}{{\rm{e}}{{}^{ax}}}$ ，
11. 当 $0<x<\frac {1}{a}$ 时， $g^{′}{\left ({x}\right )}>0$ ，所以 $g\left ({x}\right )$ 在区间 $\left ({0,\frac {1}{a}}\right )$ 上单调递增，
12. 当 $x>\frac {1}{a}$ 时， $g^{′}{\left ({x}\right )}<0$ ，所以 $g\left ({x}\right )$ 在区间 $\left ({\frac {1}{a},+\infty }\right )$ 上单调递减，
13. $g\left ({x}\right )$ 在 $x=\frac {1}{a}$ 处取得最大值，
14. 故若函数 $y=f(x)$ 与 $y=g(x)$ 的图象有且仅有一个公共点，当且仅当 $f\left ({\frac {1}{a}}\right )=g\left ({\frac {1}{a}}\right )$ ，
15. 得 $1+{\ln}\frac {1}{a}=\frac {1}{a{\rm{e}}}+\frac {1}{2}-{\ln}a$ ，得 $a=\frac {2}{{\rm{e}}}$ ，
16. 故实数 $a$ 的集合为 $\left \{\frac {2}{{\rm{e}}}\right \}$ .
17. （ii）因 $a=\frac {2}{{\rm{e}}}$ ，所以 $f\left ({x}\right )=\frac {{\rm{e}}}{2x}+{\ln}x$ ， $f^{′}{\left ({x}\right )}=\frac {2x-{\rm{e}}}{2x{{}^{2}}}$
18. 设点 $\left ({x{{}_{0}},f\left ({x{{}_{0}}}\right )}\right )$ 为经过点 $\left ({b,c}\right )$ 的直线与函数 $y=f\left ({x}\right )$ 的图象相切的切点，
19. 则 $f\left ({x{{}_{0}}}\right )=\frac {{\rm{e}}}{2x{{}_{0}}}+{\ln}x{{}_{0}}$ ， $f^{′}{\left ({x}\right )}=\frac {2x{{}_{0}}-{\rm{e}}}{{\rm{2}}x{{}_{0}^{2}}}$ ，
20. 故切线方程为 $y-\left ({\frac {{\rm{e}}}{2x{{}_{0}}}+{\ln}x{{}_{0}}}\right )=\frac {2x{{}_{0}}-{\rm{e}}}{{\rm{2}}x{{}_{0}^{2}}}\left ({x-x{{}_{0}}}\right )$ ，
21. 因 $\left ({b,c}\right )$ 在切线上，故 $c-\left ({\frac {{\rm{e}}}{{\rm{2}}x{{}_{0}}}+{\ln}x{{}_{0}}}\right )=\frac {2x{{}_{0}}-{\rm{e}}}{{\rm{2}}x{{}_{0}^{2}}}\left ({b-x{{}_{0}}}\right )$ ，
22. 整理得 ${\ln}x{{}_{0}}-\frac {{\rm{e}}b}{{\rm{2}}x{{}_{0}^{2}}}+\frac {b+{\rm{e}}}{x{{}_{0}}}-1-c{\rm{=}}{\rm{0}}$ ，
23. 因经过点 $\left ({b,{\rm{e}}}\right )$ 有且仅有3条直线与函数 $y=f\left ({x}\right )$ 的图象相切
24. 则设 $u\left ({x}\right )={\ln}x-\frac {{\rm{e}}b}{{\rm{2}}x{{}^{2}}}+\frac {b+{\rm{e}}}{x}-1-c$ ， $u\left ({x}\right )$ 有且仅有3个零点.
25. $u^{′}{\left ({x}\right )}=\frac {1}{x}+\frac {{\rm{e}}b}{x{{}^{3}}}-\frac {b+{\rm{e}}}{x{{}^{2}}}=\frac {x{{}^{2}}-\left ({b+{\rm{e}}}\right )x{\rm{+}}{\rm{e}}b}{x{{}^{3}}}{\rm{=}}\frac {\left ({x-b}\right )\left ({x-{\rm{e}}}\right )}{x{{}^{3}}}$ ，
26. 因 $b>{\rm{e}}$ ，
27. 故当 $0<x<{\rm{e}}$ ， $u^{′}{\left ({x}\right )}>0$ ， $u\left ({x}\right )$ 在区间 $\left ({0,{\rm{e}}}\right )$ 上单调增，
28. 当 ${\rm{e}}<x<b$ ， $u^{′}{\left ({x}\right )}<0$ ， $u\left ({x}\right )$ 在区间 $\left ({{\rm{e}}{\rm{,}}b}\right )$ 上单调减，
29. 当 $x>b$ ， $u^{′}{\left ({x}\right )}>0$ ， $u\left ({x}\right )$ 在区间 $\left ({b,{\rm{+}}\infty }\right )$ 上单调增，
30. 故 $u\left ({x}\right )$ 有且仅有3个零点时， $u\left ({{\rm{e}}}\right )>0$ ， $u\left ({b}\right )<0$ ，
31. 由 $u\left ({{\rm{e}}}\right )={\ln}{\rm{e}}-\frac {{\rm{e}}b}{{\rm{2}}{\rm{e}}{{}^{2}}}+\frac {b+{\rm{e}}}{{\rm{e}}}-1-c>0$ 得 $1+\frac {b}{{\rm{2}}{\rm{e}}}-c>0$
32. 由 $u\left ({b}\right )={\ln}b-\frac {{\rm{e}}b}{{\rm{2}}b{{}^{2}}}+\frac {b+{\rm{e}}}{b}-1-c<0$ 得 ${\ln}b+\frac {{\rm{e}}}{2b}-c<0$ ，
33. 要证 $\frac {1}{2}\left ({1-\frac {b}{{\rm{e}}}}\right )+c<f(b)<c$ 成立，
34. 只需证 $\frac {1}{2}\left ({1-\frac {b}{{\rm{e}}}}\right )+c<\frac {{\rm{e}}}{2b}+{\ln}b<c$ 成立，
35. 即证 $\frac {1}{2}\left ({1-\frac {b}{{\rm{e}}}}\right )<\frac {{\rm{e}}}{2b}+{\ln}b-c<0$ ，
36. 因 ${\ln}b+\frac {{\rm{e}}}{2b}-c<0$ ，故只需证 $\frac {1}{2}\left ({1-\frac {b}{{\rm{e}}}}\right )<\frac {{\rm{e}}}{2b}+{\ln}b-c$ ，
37. 因 $1+\frac {b}{{\rm{2}}{\rm{e}}}-c>0$ ，所以 $\frac {b}{{\rm{e}}}>2c-2$ ，
38. 故只需证 $\frac {{\rm{e}}}{2b}+{\ln}b>\frac {3}{2}$ ，
39. 因 $f^{′}{\left ({x}\right )}=\frac {2x-{\rm{e}}}{2x{{}^{2}}}$ ，故当 $x>\frac {{\rm{e}}}{2}$ 时， $f\left ({x}\right )=\frac {{\rm{e}}}{2x}+{\ln}x$ 在 $\left ({\frac {{\rm{e}}}{2},+\infty }\right )$ 单调递增，
40. 因 $b>{\rm{e}}{\rm{>}}\frac {{\rm{e}}}{2}$ ，
41. 所以 $f\left ({b}\right )=\frac {{\rm{e}}}{2b}+{\ln}b>f\left ({{\rm{e}}}\right )=\frac {{\rm{e}}}{2{\rm{e}}}+{\ln}{\rm{e}}{\rm{=}}\frac {3}{2}$ ，即证.
42. 故当 $b>{\rm{e}}$ 时， $\frac {1}{2}\left ({1-\frac {b}{{\rm{e}}}}\right )+c<f(b)<c$ .
43. 【点睛】关键点点睛：不等式 $\frac {1}{2}\left ({1-\frac {b}{{\rm{e}}}}\right )+c<f(b)<c$ 中，考虑到 $u\left ({x}\right )={\ln}x-\frac {{\rm{e}}b}{{\rm{2}}x{{}^{2}}}+\frac {b+{\rm{e}}}{x}-1-c$ 为切线方程得到，故在 $x=b$ 时， $u\left ({b}\right )$ 和 $f(b)$ 有量上的关系，通过代入发现 $u\left ({b}\right )=f(b)-c$ ，结合不等式特点，右边不等式即证 $u\left ({b}\right )<0$ .

## 知识点

**中文**:
  - 利用导数研究函数的单调性与单调区间
  - 利用导数证明不等式
  - 利用导数研究函数的图象

**English**:
  - Monotonicity and Monotonic Intervals
  - Proving Inequalities using Derivatives
  - Studying Function Graphs

---
