# Mathematics - 题目 3566

**ID**: 459a356cae1748b4a4848729f5f8941d
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f(x)={\ln}{^{2}}x-x+m{\ln}x$ 有两个极值点x_{1}，x_{2}．（1）求实数m的取值范围；​​​​​​​‌（2）证明：x_{1}x_{2}＜4．

## 解答

1. （1） $f(x)={\ln}{^{2}}x-x+m{\ln}x$ 有两个极值点x_{1}，x_{2}，
2. $f^{′}(x)=\frac {2}{x}{\ln}x-1+\frac {m}{x}=0$ 在 $x\in \left ({0,+\infty }\right )$ 有两不等实根 $x{{}_{1}},x{{}_{2}}$ ，
3. $m=x-2{\ln}x$ ，记 $m\left ({x}\right )=x-2{\ln}x,x\to 0{^{+}},m\left ({x}\right )\to +\infty $ ， $x\to +\infty ,m\left ({x}\right )\to +\infty $
4. $m^{′}{\left ({x}\right )}=1-\frac {2}{x}$ ，
5. $x\in \left ({0,2}\right ),m^{′}{\left ({x}\right )}<0,m\left ({x}\right )$ 单调递减，
6. $x\in \left ({2,+\infty }\right ),m^{′}{\left ({x}\right )}>0,m\left ({x}\right )$ 单调递增，
7. $m\left ({x}\right )$ 最小值 $m\left ({2}\right )=2-2{\ln}2$
8. 因为 $f^{′}(x)=\frac {2}{x}{\ln}x-1+\frac {m}{x}=0$ 在 $x\in \left ({0,+\infty }\right )$ 有两根 $x{{}_{1}},x{{}_{2}}$ ，
9. 所以 $m>2-2{\ln}2$ ；
10. （2）由（1） $x{{}_{2}}-2{\ln}x{{}_{2}}=x{{}_{1}}-2{\ln}x{{}_{1}}$ ，
11. $x{{}_{2}}-x{{}_{1}}=2\left ({{\ln}x{{}_{2}}-{\ln}x{{}_{1}}}\right )$ ， $\frac {x{{}_{2}}-x{{}_{1}}}{{\ln}x{{}_{2}}-{\ln}x{{}_{1}}}=2$ ，
12. 要证x_{1}x_{2}＜4，只需证明： $\sqrt {x{{}_{1}}x{{}_{2}}}<\frac {x{{}_{2}}-x{{}_{1}}}{{\ln}x{{}_{2}}-{\ln}x{{}_{1}}}$ 即可，不妨设 $x{{}_{1}}<x{{}_{2}}$ ，则 $\frac {x{{}_{2}}}{x{{}_{1}}}>1$
13. 即证 ${\ln}x{{}_{2}}-{\ln}x{{}_{1}}<\frac {x{{}_{2}}-x{{}_{1}}}{\sqrt {x{{}_{1}}x{{}_{2}}}}$ ，
14. 即证 ${\ln}\frac {x{{}_{2}}}{x{{}_{1}}}<\sqrt {\frac {x{{}_{2}}}{x{{}_{1}}}}-\sqrt {\frac {x{{}_{1}}}{x{{}_{2}}}}$ ，只需证明 ${\ln}\frac {x{{}_{2}}}{x{{}_{1}}}-\sqrt {\frac {x{{}_{2}}}{x{{}_{1}}}}+\sqrt {\frac {x{{}_{1}}}{x{{}_{2}}}}<0$ ，令 $t=\frac {x{{}_{2}}}{x{{}_{1}}},t>1$ ，
15. 记函数 $h\left ({t}\right )=2{\ln}t-t+\frac {1}{t},t>1$
16. $h^{′}{\left ({t}\right )}=\frac {2}{t}-1-\frac {1}{t{^{2}}}=\frac {2t-t{^{2}}-1}{t{^{2}}}=\frac {-{\left({t-1}\right)^{2}}}{t{^{2}}}<0$ ，
17. 所以 $h\left ({t}\right )=2{\ln}t-t+\frac {1}{t},t>1$ 单调递减，
18. $h\left ({t}\right )<h\left ({1}\right )=0$ ，所以 ${\ln}\frac {x{{}_{2}}}{x{{}_{1}}}-\sqrt {\frac {x{{}_{2}}}{x{{}_{1}}}}+\sqrt {\frac {x{{}_{1}}}{x{{}_{2}}}}<0$ 成立，
19. 同理可证当 $x{{}_{1}}>x{{}_{2}}$ 时结论成立，
20. 所以原命题x_{1}x_{2}＜4得证.

## 知识点

**中文**:
  - 利用导数求函数中的参数
  - 利用导数证明不等式

**English**:
  - Finding Parameters using Derivatives
  - Proving Inequalities using Derivatives

---
