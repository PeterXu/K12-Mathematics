# Mathematics - 题目 2267

**ID**: 99fa03344b0f4c13a931fded8118e888
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Fill-in-the-blank

## 题目
在平面直角坐标系 $xOy$ 中，射线 $OT$ 与直线 $l:x=9$ ，圆 $O:x{{}^{2}}+y{{}^{2}}=9$ 分别相交于 $A,B$ 两点，若线段 $OB$ 上存在点 $M(m,n)$ （不含端点），使得对于圆 $O$ 上任意一点 $P$ 都满足 $\frac {|PM|}{|PA|}=\frac {|BM|}{|BA|}$ ，则 $mn$ 的最大值为．​​​​​​​‌

## 解答

1. 设 $M(m,km),B(x,kx),A(9,9k)$ ，则 $B^{′}(-x,-kx)$ ，
2. 因为 $\frac {|PM|}{|PA|}=\frac {|BM|}{|BA|}$ ，根据阿氏圆的性质和相似，可得 $\frac {\left |{BA}\right |}{\left |{BM}\right |}=\frac {\left |{B^{′}A}\right |}{\left |{B^{′}M}\right |}$ ,
3. 则 $\frac {9-x}{x-m}=\frac {9+x}{m+x}$ ，整理得 $-x{{}^{2}}+(9-m)x+9m=x{{}^{2}}+(9-m)x-9m$ ，
4. 可得 $x{{}^{2}}=9m$ ，即 $x=3\sqrt {m}$ ，
5. 所以 $B(3\sqrt {m},3k\sqrt {m})$ ，代入圆的方程 $x{{}^{2}}+y{{}^{2}}=9$ ，可得 $m(k{{}^{2}}+1)=1$ ，
6. 所以 $mn=km{{}^{2}}=k\times \frac {1}{(k{{}^{2}}+1){{}^{2}}}=\frac {k}{(k{{}^{2}}+1){{}^{2}}}$ ，设 $f\left ({k}\right )=\frac {k}{(k{{}^{2}}+1){{}^{2}}},k>0$ ，
7. 可得 $f^{′}{\left ({k}\right )}=\frac {\left ({k{{}^{2}}+1}\right ){{}^{2}}-k\cdot 4k\left ({k{{}^{2}}+1}\right )}{\left ({k{{}^{2}}+1}\right ){{}^{4}}}=\frac {\left ({k{{}^{2}}+1}\right )-k\cdot 4k}{\left ({k{{}^{2}}+1}\right ){{}^{3}}}=\frac {1-3k{{}^{2}}}{\left ({k{{}^{2}}+1}\right ){{}^{3}}}$ ，
8. 当 $x\in (0,\frac {\sqrt {3}}{3})$ 时， $f^{′}{\left ({k}\right )}>0$ ， $f\left ({k}\right )$ 单调递增；
9. 当 $x\in (\frac {\sqrt {3}}{3},+\infty )$ 时， $f^{′}{\left ({k}\right )}<0$ ， $f\left ({k}\right )$ 单调递减，
10. 所以 $(mn){{}_{\max }}=f(k){{}_{\max }}=f(\frac {\sqrt {3}}{3})=\frac {\frac {\sqrt {3}}{3}}{\frac {16}{9}}=\frac {3\sqrt {3}}{16}$ .
11. 故答案为： $\frac {3\sqrt {3}}{16}$ .
12. 
13. 【点睛】关键点点睛：利用阿氏圆模型得到 $\frac {\left |{BA}\right |}{\left |{BM}\right |}=\frac {\left |{B^{′}A}\right |}{\left |{B^{′}M}\right |}$ ，转化为相关点坐标值的数量关系，进而得到 $mn$ 关于参数的函数.

## 知识点

**中文**:
  - 直线与圆的综合问题与实际应用

**English**:
  - Comprehensive Problems and Applications

---
