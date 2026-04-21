# Mathematics - 题目 1751

**ID**: 88f5715a302d4673aa3f8091e6b30fe9
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\frac {1}{x}-\frac {1}{{\rm{e}}{^{x}}-1}\left ({x>0}\right )$ .​​​​​​​‌(1)证明： $0<f\left ({x}\right )<\frac {1}{2}$ ；(2)证明： $\sum \limits_{k=1}^{n}\mathop{\frac {2}{2k+1}}<{\ln}(n+1)<\sum \limits_{k=1}^{n}\mathop{\frac {1}{k}}$ ， $n\in {\mathbf{N}}{^{*}}$ .

## 解答

1. （1）（i）要证 $f\left ({x}\right )=\frac {1}{x}-\frac {1}{{\rm{e}}{^{x}}-1}>0\left ({x>0}\right )$ ，即证 $\mathrm{e}{^{x}}-1>x$ ，
2. 构造函数 $g\left ({x}\right )={\rm{e}}{^{x}}-x-1$ ，其中 $x>0$ ，则 $g^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-1>0$ ，
3. 所以，函数 $g\left ({x}\right )$ 在 $\left ({0,+\infty }\right )$ 上单调递增，
4. 所以， $g\left ({x}\right )={\rm{e}}{{}^{x}}-x-1>g\left ({0}\right )=0$ ，即当 $x>0$ 时，有 $\mathrm{e}{^{x}}-1>x$ ；
5. ${\rm （ii）}$ 要证 $f\left ({x}\right )=\frac {1}{x}-\frac {1}{{\rm{e}}{^{x}}-1}<\frac {1}{2}\left ({x>0}\right )$ ，即证 $\frac {1}{{\rm{e}}{^{x}}-1}>\frac {1}{x}-\frac {1}{2}=\frac {2-x}{2x}$ ，
6. 即证 $\left ({x-2}\right ){\rm{e}}{^{x}}+x+2>0$ ，
7. 令 $h\left ({x}\right )=\left ({x-2}\right ){\rm{e}}{^{x}}+x+2$ ，其中 $x>0$ ，则 $h^{′}{\left ({x}\right )}=\left ({x-1}\right ){\rm{e}}{^{x}}+1$ ，
8. 令 $p\left ({x}\right )=\left ({x-1}\right ){\rm{e}}{^{x}}+1$ ，其中 $x>0$ ，则 $p^{′}{\left ({x}\right )}=x{\rm{e}}{^{x}}>0$ ，
9. 所以，函数 $h^{′}{\left ({x}\right )}$ 在 $\left ({0,+\infty }\right )$ 上单调递增，则 $h^{′}{\left ({x}\right )}>h^{′}{\left ({0}\right )}=0$ ，
10. 所以，函数 $h\left ({x}\right )$ 在 $\left ({0,+\infty }\right )$ 上单调递增，则 $h\left ({x}\right )=\left ({x-2}\right ){\rm{e}}{^{x}}+x+2>h\left ({0}\right )=0$ ，即 $f\left ({x}\right )<\frac {1}{2}$ .
11. 综上所述，当 $x>0$ 时， $0<f\left ({x}\right )<\frac {1}{2}$ .
12. （2）由（1）可知，当 $x>0$ 时， $0<f\left ({x}\right )<\frac {1}{2}$ ，变形可得 $\frac {2\left ({{\rm{e}}{^{x}}-1}\right )}{{\rm{e}}{^{x}}+1}<x<{\rm{e}}{^{x}}-1$ ，
13. 令 $x={\ln}\left ({1+\frac {1}{k}}\right )$ ，得 $\frac {2}{2k+1}=\frac {\frac {2}{k}}{2+\frac {1}{k}}<{\ln}\left ({1+\frac {1}{k}}\right )<\frac {1}{k}$ ，
14. 分别取 $k=1$ ， $2$ ， $3$ ， $\cdots $ ， $n$ ，得
15. $\frac {2}{3}<{\ln}2<1$ ， $\frac {2}{5}<{\ln}\frac {3}{2}<\frac {1}{2}$ ， $\frac {2}{7}<{\ln}\frac {4}{3}<\frac {1}{3}$ ， $\cdots $ ， $\frac {2}{2n+1}<{\ln}\left ({1+\frac {1}{n}}\right )={\ln}\frac {n+1}{n}<\frac {1}{n}$ ，
16. 由不等式的基本性质可得 $\sum \limits_{k=1}^{n}\mathop{\frac {2}{2k+1}}<{\ln}(n+1)<\sum \limits_{k=1}^{n}\mathop{\frac {1}{k}}$ ， $n\in {\mathbf{N}}{^{∗}}$ .

## 知识点

**中文**:
  - 利用导数证明不等式

**English**:
  - Proving Inequalities using Derivatives

---
