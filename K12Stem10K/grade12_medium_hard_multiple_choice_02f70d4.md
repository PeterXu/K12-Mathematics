# Mathematics - 题目 3876

**ID**: 02f70d4caf524304933ee2df64fdac3f
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Multiple-choice

## 题目
已知函数 $φ\left ({x}\right )=\frac {{\ln}x}{x}$ ．设s为正数，则在 $φ(s),φ\left ({s{{}^{2}}}\right ),φ(2s)$ 中（      ）​​​​​​​‌

## 解答

1. ∵ $φ^{′}{\left ({x}\right )}=\frac {1-{\ln}x}{x{{}^{2}}}$ ，则当 $0<x<{\rm{e}}$ 时， $φ^{′}{\left ({x}\right )}>0$ ，当 $x>{\rm{e}}$ 时， $φ^{′}{\left ({x}\right )}<0$ ，
2. 故 $φ\left ({x}\right )$ 在 $\left ({0,{\rm{e}}}\right )$ 上单调递增，在 $\left ({{\rm{e}},+\mathrm{∞}}\right )$ 上单调递减，则 $φ\left ({x}\right )\leqslant φ\left ({{\rm{e}}}\right )=\frac {1}{{\rm{e}}}$ ，且 $φ\left ({2}\right )=φ\left ({4}\right )=\frac {{\ln}2}{2}$ ，
3. 对A：若 $s{{}^{2}}={\rm{e}}$ ，则 $s=\sqrt {{\rm{e}}},2s=2\sqrt {{\rm{e}}}$ ，则 $φ(s)<φ\left ({s{{}^{2}}}\right ),φ(2s)<φ\left ({s{{}^{2}}}\right )$ ，A错误；
4. 对B、C：当 $0<s\leqslant 1$ 时，则 $0<s{{}^{2}}\leqslant s<2s\leqslant 2<{\rm{e}}$ ，故 $φ\left ({s{{}^{2}}}\right )\leqslant φ(s)<φ(2s)$ ；
5. 当 $1<s<2$ 时，则 $s<2<2s<4$ ，故 $φ(s)<φ\left ({2}\right )=φ\left ({4}\right )<φ(2s)$ ；
6. 当 $s=2$ 时，则 $2s=s{{}^{2}}=4$ ，故 $φ(s)=φ\left ({2}\right )=φ\left ({4}\right )=φ\left ({s{{}^{2}}}\right )=φ(2s)$ ；
7. 当 $s>2$ 时，则 $4<2s<s{{}^{2}}$ ，故 $φ\left ({2s}\right )>φ\left ({s{{}^{2}}}\right )$ ；
8. 综上所述： $φ(2s)$ 不可能同时小于 $φ\left ({s{{}^{2}}}\right ),φ\left ({s}\right )$ ，B、C错误；
9. 对D：构建 $f\left ({x}\right )={\ln}\left ({1+x}\right )-\frac {x{{}^{2}}+6x}{4x+6}$ ，则 $f^{′}{\left ({x}\right )}=-\frac {x{{}^{3}}}{\left ({x+1}\right )\left ({2x+3}\right ){{}^{2}}}<0$ 当 $x\in \left ({0,2}\right )$ 时恒成立，
10. 故 $f\left ({x}\right )$ 在 $\left ({0,2}\right )$ 上单调递减，则 $f\left ({x}\right )<f\left ({0}\right )=0$ ，
11. 令 $x=1$ ，可得 $f\left ({1}\right )={\ln}2-\frac {7}{10}<0$ ，则 ${\ln}2<\frac {7}{10}<\frac {\sqrt {2}}{2}$ ，
12. 故 $\frac {{\ln}2}{2}<\frac {\sqrt {2}}{4}<\frac {1}{{\rm{e}}}$ ，即 $\exists x{{}_{0}}\in \left ({2,4}\right )$ ，使得 $f\left ({x{{}_{0}}}\right )=\frac {\sqrt {2}}{4}$ ，
13. 反证：假设 $φ(s),φ\left ({s{{}^{2}}}\right ),φ(2s)$ 均不小于 $\frac {\sqrt {2}}{4}$ ，则 $s,s{{}^{2}},2s\in \left ({2,4}\right )$ ，
14. 显然不成立，假设不成立，D正确.
15. 故选：D.

## 知识点

**中文**:
  - 利用导数解决函数中的其他问题

**English**:
  - Other Function Problems using Derivatives

---
