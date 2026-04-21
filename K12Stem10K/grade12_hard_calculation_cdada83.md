# Mathematics - 题目 1365

**ID**: cdada83b874e42fd96278db9ab8ef512
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )={\rm{e}}^{x}-mx^{2}\left ({m\in {\rm{R}}}\right )$ ，其中e为自然对数的底数．(1)若函数 $f\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 有2个极值点，求m的取值范围；​​​​​​​‌(2)若函数 $h\left ({x}\right )=f^{′}\left ({x}\right )-2n{\sin}x$ 在 $\left ({0,+∞}\right )$ 有零点，求证： $m^{2}+n^{2}>\frac {{\rm{e}}}{4}$ ．

## 解答

1. （1）由题设 $f^{′}(x)={\rm{e}}^{x}-2mx$ 在 $\left ({0,+∞}\right )$ 有2个变号零点，
2. 当 $m\leqslant 0$ 时 $f^{′}(x)>0$ ，即 $f(x)$ 在 $\left ({0,+∞}\right )$ 上递增，不可能有2个零点；
3. 当 $m>0$ 时，令 $f^{′}(x_{0})=0$ ，则 $x_{0}={\ln}2m+{\ln}x_{0}$ ，且在 $\left ({0,+∞}\right )$ 上有2个对应的 $x_{0}$ ，
4. 所以，问题化为 $y=x_{0}-{\ln}x_{0}$ 与 $y={\ln}2m$ 在 $\left ({0,+∞}\right )$ 上有两个交点，
5. 对于 $g(x)=x-{\ln}x$ ，有 $g^{′}(x)=1-\frac {1}{x}$ ，则 $(0,1)$ 上 $g^{′}(x)<0$ ， $g(x)$ 递减， $(1,+\infty )$ 上 $g^{′}(x)>0$ ， $g(x)$ 递增，
6. 又 $x$ 趋向于0时 $g(x)$ 趋向正无穷， $x$ 趋向于正无穷时 $g(x)$ 趋向正无穷，且 $g(x)_{min}=g(1)=1$ ，
7. 所以 ${\ln}2m>1$ ，故 $m>\frac {{\rm{e}}}{2}$ .
8. 综上， $m>\frac {{\rm{e}}}{2}$ .
9. （2）由 $h(x)={\rm{e}}^{x}-2mx-2n{\sin}x$ ，则 $mx+n{\sin}x=\frac {{\rm{e}}^{x}}{2}$ 在 $\left ({0,+∞}\right )$ 有解，
10. 若 $\overrightarrow a=(m,n),\overrightarrow b=(x,{\sin}x)$ ，由 $\left |{\overrightarrow a}\right |\left |{\overrightarrow b}\right |\geqslant \overrightarrow a\cdot \overrightarrow b$ 知： $\sqrt {m^{2}+n^{2}}\cdot \sqrt {x^{2}+{\sin}^{2}x}\geqslant mx+n{\sin}x$ ，
11. 所以 $\sqrt {m^{2}+n^{2}}\cdot \sqrt {x^{2}+{\sin}^{2}x}\geqslant \frac {{\rm{e}}^{x}}{2}$ ，即 $\sqrt {m^{2}+n^{2}}\geqslant \frac {{\rm{e}}^{x}}{2\sqrt {x^{2}+{\sin}^{2}x}}$ ，
12. 下证 $x^{2}-{\sin}^{2}x=(x-{\sin}x)(x+{\sin}x)>0$ 在 $\left ({0,+∞}\right )$ 上恒成立，
13. 令 $h=x-{\sin}x$ ，则 $h^{′}=1-{\cos}x\geqslant 0$ ，故 $h$ 在 $\left ({0,+∞}\right )$ 上递增，所以 $h>h|_{x=0}=0$ ，即 $x-{\sin}x>0$ ；
14. 令 $k=x+{\sin}x$ ，则 $k^{′}=1+{\cos}x\geqslant 0$ ，故 $k$ 在 $\left ({0,+∞}\right )$ 上递增，所以 $k>k|_{x=0}=0$ ，即 $x+{\sin}x>0$ ；
15. 综上， $x^{2}-{\sin}^{2}x>0$ ，即 $x^{2}>{\sin}^{2}x$ ，故 $\sqrt {m^{2}+n^{2}}>\frac {{\rm{e}}^{x}}{2\sqrt {2x^{2}}}$ ，即 $m^{2}+n^{2}>\frac {{\rm{e}}^{2x}}{8x^{2}}$ ，
16. 下证 $\frac {{\rm{e}}^{x}}{x}\geqslant {\rm{e}}$ ，即 ${\rm{e}}^{x}\geqslant {\rm{e}}x$ 在 $\left ({0,+∞}\right )$ 上恒成立，
17. 令 $l={\rm{e}}^{x}-{\rm{e}}x$ ，则 $l^{′}={\rm{e}}^{x}-{\rm{e}}$ ，在 $(0,1)$ 上 $l^{′}<0$ ， $l$ 递减，在 $(1,+\infty )$ 上 $l^{′}>0$ ， $l$ 递增，
18. 所以 $l\geqslant l|_{x=1}=0$ ，即 ${\rm{e}}^{x}\geqslant {\rm{e}}x$ ，故 $m^{2}+n^{2}>\frac {{\rm{e}}^{2}}{8}>\frac {2{\rm{e}}}{8}=\frac {{\rm{e}}}{4}$ ，得证.
19. 【点睛】关键点点睛：第二问注意引用向量数量积的不等关系 $\left |{\overrightarrow a}\right |\left |{\overrightarrow b}\right |\geqslant \overrightarrow a\cdot \overrightarrow b$ ，得 $\sqrt {m^{2}+n^{2}}\geqslant \frac {{\rm{e}}^{x}}{2\sqrt {x^{2}+{\sin}^{2}x}}$ ，再构造函数作放缩处理证明结论.

## 知识点

**中文**:
  - 利用导数研究函数的极值
  - 利用导数解决函数零点问题

**English**:
  - Extrema of Functions using Derivatives
  - Solving Zero Point Problems

---
