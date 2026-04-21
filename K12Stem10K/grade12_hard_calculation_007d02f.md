# Mathematics - 题目 214

**ID**: 007d02fe7ee34638a71760af02f7e4b4
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
定义：若存在 $x{{}_{0}}$ 使得 $af^{′}{\left ({x{{}_{0}}}\right )}=g^{′}{\left ({x{{}_{0}}}\right )}$ 成立，则称 $x{{}_{0}}$ 为函数 $f\left ({x}\right )$ 和 $g\left ({x}\right )$ 的 $a{\rm -}$ 平衡点，其中 $f^{′}{\left ({x}\right )},g^{′}{\left ({x}\right )}$ 分别为 $f\left ({x}\right ),g\left ({x}\right )$ 的导函数．已知函数 $f\left ({x}\right )=x{\rm{l}}{\rm{n}}x-x,g\left ({x}\right )=x-2{\rm{l}}{\rm{n}}\left ({x+1}\right )$ ．（1）若函数 $f^{′}{\left ({x}\right )}$ 和 $g^{′}{\left ({x}\right )}$ 存在 $a{\rm -}$ 平衡点，求实数 $a$ 的最大值；​​​​​​​‌（2）若函数 $f\left ({x}\right )$ 和 $g\left ({x}\right )$ 存在3个不同的 $a{\rm -}$ 平衡点 $x{{}_{1}},x{{}_{2}},x{{}_{3}}$ ，且 $x{{}_{1}}<x{{}_{2}}<x{{}_{3}}$ ．（1）求实数 $a$ 的取值范围；（2）求证： $\left ({3a-1}\right )\left ({x{{}_{1}}+x{{}_{3}}+2}\right )<2$ ．

## 解答

1. （1）函数 $f\left ({x}\right )=x{\rm{l}}{\rm{n}}x-x$ 的定义域为 $\left ({0,+\infty }\right )$ ， $f^{′}{\left ({x}\right )}={\ln}x,x>0$ ．
2. 函数 $g\left ({x}\right )=x-2{\rm{l}}{\rm{n}}\left ({x+1}\right )$ 的定义域为 $\left ({-1,+\infty }\right )$ ， $g^{′}{\left ({x}\right )}=1-\frac {2}{x+1},x>-1$
3. 令 $s\left ({x}\right )=f^{′}{\left ({x}\right )},t\left ({x}\right )=g^{′}{\left ({x}\right )}$ ，则 $s^{′}{\left ({x}\right )}=\frac {1}{x},x>0$ ； $t^{′}{\left ({x}\right )}=\frac {2}{{\left({x+1}\right)^{2}}},x>-1$ .所以 $s^{′}{\left ({x}\right )}>0,t^{′}{\left ({x}\right )}>0$ .
4. 由函数 $f^{′}{\left ({x}\right )}$ 和 $g^{′}{\left ({x}\right )}$ 存在 $a{\rm -}$ 平衡点，知 $s\left ({x}\right )$ 和 $t\left ({x}\right )$ 存在 $a{\rm -}$ 平衡点，所以存在实数 $x{{}_{0}}$ 使得 $as^{′}{\left ({x{{}_{0}}}\right )}=t^{′}{\left ({x{{}_{0}}}\right )}$ 成立，即存在实数 $x{{}_{0}}$ 使得 $a=\frac {t^{′}{\left ({x{{}_{0}}}\right )}}{s^{′}{\left ({x{{}_{0}}}\right )}}$ 成立.
5. 令 $h\left ({x}\right )=\frac {t^{′}{\left ({x}\right )}}{s^{′}{\left ({x}\right )}}=\frac {2x}{x{^{2}}+2x+1}=\frac {1}{\frac {x}{2}+\frac {1}{2x}+1}\leqslant \frac {1}{2}$ ，当且仅当 $\frac {x}{2}=\frac {1}{2x}=\frac {1}{2}$ ，即 $x=1$ 时，等号成立.
6. 所以当 $x=1$ 时， $h\left ({x}\right )$ 取得最大值，最大值为 $\frac {1}{2}$ .
7. 实数 $a$ 的最大值为 $\frac {1}{2}$ .
8. （2）若函数 $f\left ({x}\right )$ 和 $g\left ({x}\right )$ 存在3个不同的 $a{\rm -}$ 平衡点 $x{{}_{1}},x{{}_{2}},x{{}_{3}}$ ，且 $x{{}_{1}}<x{{}_{2}}<x{{}_{3}}$ ，则 $af^{′}{\left ({x}\right )}=g^{′}{\left ({x}\right )}$ 有3个不同的解.
9. 当 $f^{′}{\left ({x}\right )}=0,$ 即 ${\ln}x=0,x=1$ 时， $g^{′}{\left ({x}\right )}=g^{′}{\left ({1}\right )}=0$ ，所以 $x=1$ 是 $af^{′}{\left ({x}\right )}=g^{′}{\left ({x}\right )}$ 的一个解，此时 $a\in {\mathbf{R}}$ .
10. 所以当 $x\ne 1$ 时， $af^{′}{\left ({x}\right )}=g^{′}{\left ({x}\right )}$ ，即 $a=\frac {g^{′}{\left ({x}\right )}}{f^{′}{\left ({x}\right )}}$ 有2个不同的解.
11. 令 $F\left ({x}\right )=\frac {g^{′}{\left ({x}\right )}}{f^{′}{\left ({x}\right )}}$ ，则由（1）得： $F\left ({x}\right )=\frac {1-\frac {2}{x+1}}{{\ln}x}=\frac {x-1}{\left ({x+1}\right ){\ln}x},x>0,$ 且 $x\ne 1$ .
12. $F^{′}{\left ({x}\right )}=\frac {\left ({x+1}\right ){\ln}x-\left ({x-1}\right )\left ({{\ln}x+\frac {x+1}{x}}\right )}{{\left({x+1}\right)^{2}}·{\ln}{^{2}}x}=\frac {2{\ln}x-x+\frac {1}{x}}{{\left({x+1}\right)^{2}}·{\ln}{^{2}}x},x>0$ ，且 $x\ne 1$ .
13. 令 $G\left ({x}\right )=2{\ln}x-x+\frac {1}{x},x>0$ ，则 $G^{′}{\left ({x}\right )}=\frac {2}{x}-1-\frac {1}{x{^{2}}}=\frac {-{\left({x-1}\right)^{2}}}{x{^{2}}}\leqslant 0$ ，所以 $G\left ({x}\right )=2{\ln}x-x+\frac {1}{x},x>0$ 单调递减.
14. 因为 $G\left ({1}\right )=0$  ，所以当 $0<x<1$ 时， $G\left ({x}\right )>0$ ， $F^{′}{\left ({x}\right )}>0$ ， $F\left ({x}\right )$ 单调递增；
15. 当 $x>1$ 时， $G\left ({x}\right )<0$ ， $F^{′}{\left ({x}\right )}<0$ ， $F\left ({x}\right )$ 单调递减.
16. 当 $x\to 0$ 时， $F\left ({x}\right )\to 0$ ；当 $x<1,$ 且 $x\to 1$ 时， $x-1<0,{\ln}x<0$ ， $x-1\to {\ln}x$ ，所以 $\frac {x-1}{\left ({x+1}\right ){\ln}x}\to \frac {1}{2}$ ；
17. 当 $x>1,$ 且 $x\to 1$ 时， $x-1>0,{\ln}x>0,$  $x-1\to {\ln}x$ ，所以 $\frac {x-1}{\left ({x+1}\right ){\ln}x}\to \frac {1}{2}$ ；
18. 当 $x\to +\infty $ 时， $x-1\to +\infty ,x+1\to +\infty ,{\ln}x\to +\infty $ ，所以 $\frac {x-1}{\left ({x+1}\right ){\ln}x}>0,\frac {x-1}{\left ({x+1}\right ){\ln}x}\to 0$ ；
19. 因此， $F\left ({x}\right )$ 的简图如下：
20. 
21. 所以当 $0<a<\frac {1}{2}$ 时， $a=F\left ({x}\right )$ 有两个不同的解.
22. ①所以实数 $a$ 的取值范围是 $\left ({0,\frac {1}{2}}\right )$ .
23. ②若 $F\left ({x}\right )=\frac {x-1}{\left ({x+1}\right ){\ln}x},x>0,$ 且 $x\ne 1$ ，则 $F\left ({\frac {1}{x}}\right )=\frac {\frac {1}{x}-1}{\left ({\frac {1}{x}+1}\right ){\ln}\frac {1}{x}}\frac {x-1}{\left ({x+1}\right ){\ln}x}=F\left ({x}\right )$
24. 如图可知： $0<x{{}_{1}}<x{{}_{2}}=1<x{{}_{3}}$ ，且 $a=F\left ({x{{}_{1}}}\right )=F\left ({x{{}_{3}}}\right )$ ，所以 $x{{}_{1}}=\frac {1}{x{{}_{3}}}$ .
25. 要证 $\left ({3a-1}\right )\left ({x{{}_{1}}+x{{}_{3}}+2}\right )<2$ ，只需证 $3a\left ({x{{}_{1}}+x{{}_{3}}+2}\right )<2+\left ({x{{}_{1}}+x{{}_{3}}+2}\right )$ ，
26. 即证 $3a\left ({\frac {1}{x{{}_{3}}}+x{{}_{3}}+2}\right )<\frac {1}{x{{}_{3}}}+x{{}_{3}}+4$ ，即证 $3a{\left({x{{}_{3}}+1}\right)^{2}}-\left ({x{{}_{3}^{2}}+4x{{}_{3}}+1}\right )<0$ ，
27. 即证 $\frac {3\left ({x{{}_{3}}-1}\right )}{\left ({x{{}_{3}}+1}\right ){\ln}x{{}_{3}}}\times {\left({x{{}_{3}}+1}\right)^{2}}-\left ({x{{}_{3}^{2}}+4x{{}_{3}}+1}\right )=\frac {3\left ({x{{}_{3}^{2}}-1}\right )}{{\ln}x{{}_{3}}}-\left ({x{{}_{3}^{2}}+4x{{}_{3}}+1}\right )<0$ ，
28. 即证 $3\left ({x{{}_{3}^{2}}-1}\right )-\left ({x{{}_{3}^{2}}+4x{{}_{3}}+1}\right ){\ln}x{{}_{3}}<0$ .
29. 令 $H\left ({x}\right )=3\left ({x{^{2}}-1}\right )-\left ({x{^{2}}+4x+1}\right ){\ln}x,x>1$ ，则 $H^{′}{\left ({x}\right )}=6x-\left ({2x+4}\right ){\ln}x-\frac {x{^{2}}+4x+1}{x}=5x-\frac {1}{x}-\left ({2x+4}\right ){\ln}x-4,x>1$ ，
30. 令 $M\left ({x}\right )=5x-\frac {1}{x}-\left ({2x+4}\right ){\ln}x-4,x>1$ ，则 $M^{′}{\left ({x}\right )}=5+\frac {1}{x{^{2}}}-2{\ln}x-\frac {2x+4}{x}=3+\frac {1}{x{^{2}}}-\frac {4}{x}-2{\ln}x,x>1$
31. 令 $N\left ({x}\right )=3+\frac {1}{x{^{2}}}-\frac {4}{x}-2{\ln}x,x>1$ ，则 $N^{′}{\left ({x}\right )}=-\frac {2}{x{^{3}}}+\frac {4}{x{^{2}}}-\frac {2}{x}=-\frac {2{\left({x-1}\right)^{2}}}{x{^{3}}},x>1$ .
32. 所以当 $x>1$ 时， $N^{′}{\left ({x}\right )}<0$ ， $\mathbf{N}\left ({x}\right )$ 单调递减，所以 $\mathbf{N}\left ({x}\right )<0$ ，即 $M^{′}{\left ({x}\right )}<0$ .
33. 所以 $M\left ({x}\right )$ 单调递减，且 $M\left ({x}\right )<0$ ，即 $H^{′}{\left ({x}\right )}<0$ .所以 $H\left ({x}\right )$ 单调递减，所以 $H\left ({x}\right )<0$ .
34. 即当 $x>1$ 时， $3\left ({x{^{2}}-1}\right )-\left ({x{^{2}}+4x+1}\right ){\ln}x<0$ .
35. 因此， $3\left ({x{{}_{3}^{2}}-1}\right )-\left ({x{{}_{3}^{2}}+4x{{}_{3}}+1}\right ){\ln}x{{}_{3}}<0$ .
36. 故 $\left ({3a-1}\right )\left ({x{{}_{1}}+x{{}_{3}}+2}\right )<2$ 得证.

## 知识点

**中文**:
  - 利用导数解决新定义问题

**English**:
  - Solving New Definition Problems

---
