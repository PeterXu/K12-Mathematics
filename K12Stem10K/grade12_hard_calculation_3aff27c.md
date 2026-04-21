# Mathematics - 题目 1253

**ID**: 3aff27c989d7436d876bf4a9c91cfb44
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=m\left ({1-x}\right ){\rm{e}}{{}^{x}}+{\ln}x$ ， $m\in \left ({0,{\rm{e}}{{}^{-1}}}\right )$ ， ${\rm{e}}$ 为自然对数的底数.​​​​​​​‌(1)证明：函数 $f\left ({x}\right )$ 存在唯一的极值点 $β$ ；(2)在（1）的条件下，若 $f\left ({α}\right )=0$ ，且 $α>β$ ，证明： $3β-α>2$ .

## 解答

1. （1）证明：函数 $f\left ({x}\right )=m\left ({1-x}\right ){\rm{e}}{{}^{x}}+{\ln}x$ 的定义域为 $\left ({0,+∞}\right )$ ，
2. 则 $f^{′}{\left ({x}\right )}=-m{\rm{e}}{{}^{x}}+m\left ({1-x}\right ){\rm{e}}{{}^{x}}+\frac {1}{x}=\frac {1}{x}-mx{\rm{e}}{{}^{x}}=\frac {1-mx{{}^{2}}{\rm{e}}{{}^{x}}}{x},x\in \left ({0,+\infty }\right )$ ，
3. 令 $g\left ({x}\right )=1-mx{{}^{2}}{\rm{e}}{{}^{x}}$ ，因为 $m\in \left ({0,{\rm{e}}{{}^{-1}}}\right )$ ，
4. 则 $g^{′}{\left ({x}\right )}=-2mx{\rm{e}}{{}^{x}}-mx{{}^{2}}{\rm{e}}{{}^{x}}=-m\left ({x{{}^{2}}+2x}\right ){\rm{e}}{{}^{x}}<0$ 在 $\left ({0,+∞}\right )$ 恒成立，
5. 所以函数 $g\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上单调递增，
6. 因为 $m\in \left ({0,{\rm{e}}{{}^{-1}}}\right )$ ，所以 $\frac {1}{m}>{\rm{e}}$ ，所以 $g\left ({1}\right )=1-m{\rm{e}}>0$ ， $g\left ({{\ln}\frac {1}{m}}\right )=1-\left ({{\ln}\frac {1}{m}}\right ){{}^{2}}<0$ ，
7. 所以函数 $g\left ({x}\right )=1-mx{{}^{2}}{\rm{e}}{{}^{x}}$ 在 $\left ({1,{\ln}\frac {1}{m}}\right )$ 上存在唯一零点 $β$ .
8. 又当 $x\in \left ({0,β}\right )$ 时， $g\left ({x}\right )>0$ ，即 $f^{′}{\left ({x}\right )}>0$ ，函数 $f\left ({x}\right )$ 单调递增，
9. 当 $x\in \left ({β,+\infty }\right )$ 时， $g\left ({x}\right )<0$ ，即 $f^{′}{\left ({x}\right )}<0$ ，函数 $f\left ({x}\right )$ 单调递减，
10. 所以函数 $f\left ({x}\right )$ 在 $x=β$ 处取得极大值，即函数 $f\left ({x}\right )$ 存在唯一的极值点 $β$ .
11. （2）证明：由（1）知， $α>β>1$ ， $f^{′}{\left ({β}\right )}=0$ ，则 $1-mβ{{}^{2}}{\rm{e}}{{}^{β}}=0$ ，即 $1=mβ{{}^{2}}{\rm{e}}{{}^{β}}$ ，
12. 则 $\frac {1}{β{{}^{2}}}=m{\rm{e}}{{}^{β}}$ .①
13. 又 $f\left ({α}\right )=0$ ，即 $f\left ({α}\right )=m\left ({1-α}\right ){\rm{e}}{{}^{α}}+{\ln}α=0$ ，则有 $\frac {{\ln}α}{α-1}=m{\rm{e}}{{}^{α}}$ .②
14. 联立①②可得 ${\rm{e}}{{}^{α-β}}=\frac {β{{}^{2}}{\ln}α}{α-1}$ ，
15. 令 $m\left ({x}\right )={\ln}x-x+1,x>1$ ，则 $m^{′}{\left ({x}\right )}=\frac {1}{x}-1$ ，
16. 当 $x>1$ 时， $\frac {1}{x}<1$ ，即 $\frac {1}{x}-1<0$ ， $m^{′}{\left ({x}\right )}<0$ ，
17. 所以 $m\left ({x}\right )$ 单调递减，则 $m\left ({x}\right )<m\left ({1}\right )=0$ ，
18. 即 ${\ln}x<x-1$ 在 $\left ({1,+\infty }\right )$ 恒成立，所以 $\frac {β{{}^{2}}{\ln}α}{α-1}<\frac {β{{}^{2}}\left ({α-1}\right )}{α-1}=β{{}^{2}}$ ，
19. 所以 ${\rm{e}}{{}^{α-β}}<β{{}^{2}}$ ，则 ${\ln}{\rm{e}}{{}^{α-β}}<{\ln}β{{}^{2}}$ ，即 $α-β<2{\ln}β<2\left ({β-1}\right )$ ，
20. 即 $α-β<2\left ({β-1}\right )$ ，即 $3β-α>2$ .
21. 【点睛】本题考查函数的单调性，函数的极值以及函数不等式的证明，解答本题的关键在于找到等量关系，从而去证明不等关系.

## 知识点

**中文**:
  - 利用导数研究函数的极值
  - 利用导数证明不等式

**English**:
  - Extrema of Functions using Derivatives
  - Proving Inequalities using Derivatives

---
