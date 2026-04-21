# Mathematics - 题目 1209

**ID**: b076cdcf4da7470a8441415e4d7b57af
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Fill-in-the-blank

## 题目
已知 $A$ ， $B$ 分别为双曲线 $C:x{^{2}}-y{^{2}}=1$ 的左右顶点，点 $P$ 为 $C$ 上一动点， $O$ 为坐标原点，则 $\frac {\left |{PO}\right |}{\left |{PA}\right |+\left |{PB}\right |}$ 的最小值是．​​​​​​​‌

## 解答

1. 根据对称性，不妨设点 $P\left ({x,y}\right )$ 在 $x$ 轴上或第一象限内，则 $y\geqslant 0$ ， $x{^{2}}=y{^{2}}+1$ ，
2. 则 $\frac {\left |{PO}\right |{^{2}}}{{\left({\left |{PA}\right |+\left |{PB}\right |}\right)^{2}}}=\frac {x{^{2}}+y{^{2}}}{\left ({\sqrt {{\left({x+1}\right)^{2}}+y{^{2}}}+\sqrt {{\left({x-1}\right)^{2}}+y{^{2}}}}\right ){^{2}}}$
3. $=\frac {2y{^{2}}+1}{{\left({\sqrt {2y{^{2}}+2+2x}+\sqrt {2y{^{2}}+2-2x}}\right)^{2}}}=\frac {2y{^{2}}+1}{4y{^{2}}+4+4\sqrt {{\left({y{^{2}}+1}\right)^{2}}-4x{^{2}}}}$
4. $=\frac {2y{^{2}}+1}{4y{^{2}}+4+4\sqrt {y{^{2}}\left ({y{^{2}}+1}\right )}}$ .
5. 令 $y={\tan}θ,θ\in \left [{0,\frac {π}{2}}\right )$ ，
6. 则 $\frac {2y{^{2}}+1}{4y{^{2}}+4+4\sqrt {y{^{2}}\left ({y{^{2}}+1}\right )}}=\frac {2{\tan}{^{2}}θ+1}{4\left ({{\tan}{^{2}}θ+1}\right )+4\sqrt {{\tan}{^{2}}θ\left ({{\tan}{^{2}}θ+1}\right )}}$
7. $=\frac {\frac {2\sin {^{2}}θ}{{\cos}{^{2}}θ}+1}{4\left ({\frac {\sin {^{2}}θ}{{\cos}{^{2}}θ}+1}\right )+4\sqrt {\frac {\sin {^{2}}θ}{{\cos}{^{2}}θ}\left ({\frac {\sin {^{2}}θ}{{\cos}{^{2}}θ}+1}\right )}}=\frac {\frac {2\sin {^{2}}θ}{{\cos}{^{2}}θ}+1}{\frac {4}{{\cos}{^{2}}θ}+4\sqrt {\frac {\sin {^{2}}θ}{{\cos}{^{4}}θ}}}=\frac {\frac {2\sin {^{2}}θ}{{\cos}{^{2}}θ}+1}{\frac {4}{{\cos}{^{2}}θ}+\frac {4\sin θ}{{\cos}{^{2}}θ}}$
8. $=\frac {2\sin {^{2}}θ+{\cos}{^{2}}θ}{4+4\sin θ}=\frac {\sin {^{2}}θ+1}{4+4\sin θ}=\frac {1}{4}\cdot \frac {{\left({\sin θ+1}\right)^{2}}-2\left ({\sin θ+1}\right )+2}{\sin θ+1}$
9. $=\frac {1}{4}\left [\left ({\sin θ+1}\right )+\frac {2}{\sin θ+1}-2\right ]\geqslant \frac {1}{4}\left ({2\sqrt {2}-2}\right )=\frac {\sqrt {2}-1}{2}$ ，
10. 当且仅当 $\sin θ+1=\frac {2}{\sin θ+1}$ ，即 $\sin θ=\sqrt {2}-1$ 时等号成立，
11. 所以 $\frac {\left |{PO}\right |{^{2}}}{{\left({\left |{PA}\right |+\left |{PB}\right |}\right)^{2}}}\geqslant \frac {\sqrt {2}-1}{2}$ ，所以 $\frac {\left |{PO}\right |}{\left |{PA}\right |+\left |{PB}\right |}\geqslant \sqrt {\frac {\sqrt {2}-1}{2}}$ ，
12. 即 $\frac {\left |{PO}\right |}{\left |{PA}\right |+\left |{PB}\right |}$ 的最小值为 $\sqrt {\frac {\sqrt {2}-1}{2}}$ .
13. 

## 知识点

**中文**:
  - 范围最值问题

**English**:
  - Range and Extrema Problems

---
