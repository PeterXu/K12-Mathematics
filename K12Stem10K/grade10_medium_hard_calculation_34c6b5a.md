# Mathematics - 题目 617

**ID**: 34c6b5a34185480a9b0576bceaedb3bd
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f(x)=\sqrt {3}\sin (ωx+φ)+2\sin {^{2}}\left ({\frac {ωx+φ}{2}}\right )-1,(ω>0,0<φ<π)$ 为奇函数，且 $f(x)$ 图象相邻的对称轴之间的距离为 $\frac {π}{2}$（1）求函数 $f(x)$ 的解析式及其减区间；​​​​​​​‌（2）在 $\vartriangle ABC$ 中，角A、B、C对应的边为a、b、c，且 $a=\sqrt {3}$ ， $f\left ({\frac {A}{2}+\frac {π}{6}}\right )=\sqrt {3}$ ，求 $\vartriangle ABC$ 的周长的取值范围．

## 解答

1. （1） $f(x)=\sqrt {3}\sin (ωx+φ)+2\sin {^{2}}\left ({\frac {ωx+φ}{2}}\right )-1$  $=\sqrt {3}\sin (ωx+φ)-{\cos}(ωx+φ)=2\sin \left ({ωx+φ-\frac {π}{6}}\right )$ ，
2. 由函数 $f(x)$ 相邻的对称轴之间的距离为 $\frac {π}{2}$ ，得 $ω=\frac {2π}{T}=\frac {2π}{π}=2$ ，
3. ∴ $f(x)=2\sin \left ({2x+φ-\frac {π}{6}}\right )$ ，
4. 又∵ $f(x)$ 为奇函数，∴ $f(0)=0$ ，即 $2\sin \left ({φ-\frac {π}{6}}\right )=0$ ，
5. 得 $φ-\frac {π}{6}=kπ$ ，即 $φ=\frac {π}{6}+kπ$ ，而 $0<φ<π,φ=\frac {π}{6}$ ，故 $f(x)=2\sin 2x$ ，
6. 令 $\frac {π}{2}+2kπ\leqslant 2x\leqslant \frac {3}{2}π+2kπ,k\in \mathbf{Z}$ ，得 $\frac {π}{4}+kπ\leqslant x\leqslant \frac {3}{4}π+kπ,k\in \mathbf{Z}$ ，
7. ∴ $f(x)$ 的减区间为 $\left [\frac {π}{4}+kπ,\frac {3}{4}π+kπ\right ],k\in \mathbf{Z}$ ；
8. （2）由（1）可知 $f(x)=2\sin 2x,f\left ({\frac {A}{2}+\frac {π}{6}}\right )=\sqrt {3}$ ，得 $2\sin \left ({A+\frac {π}{3}}\right )=\sqrt {3}$ ，即 $\sin \left ({A+\frac {π}{3}}\right )=\frac {\sqrt {3}}{2}$ ，
9. ∵ $A\in (0,π)$ ，∴ $\left ({A+\frac {π}{3}}\right )\in \left ({\frac {π}{3},\frac {4π}{3}}\right )$ ，∴ $A+\frac {π}{3}=\frac {2π}{3}$ ，即 $A=\frac {π}{3}$ ，
10. ∵ $a=\sqrt {3},A=\frac {π}{3},A+B+C=π$ ，∴ $2R=\frac {a}{\sin A}=2,C=\frac {2}{3}π-B,B\in \left ({0,\frac {2}{3}π}\right )$
11. ∴ $b+c=2R(\sin B+\sin C)=2\left [\sin B+\sin \left ({\frac {2}{3}π-B}\right )\right ]=2\left ({\frac {3}{2}\sin B+\frac {\sqrt {3}}{2}{\cos}B}\right )$
12. $=2\sqrt {3}\sin \left ({B+\frac {π}{6}}\right )$ ，
13. 而 $B\in \left ({0,\frac {2}{3}π}\right )$ ，故 $\left ({B+\frac {π}{6}}\right )\in \left ({\frac {π}{6},\frac {5π}{6}}\right )$ ；∵ $\sin \left ({B+\frac {π}{6}}\right )\in \left ({\frac {1}{2},1}\right ]$ ，故 $(b+c)\in (\sqrt {3},2\sqrt {3}]$ ；
14. ∴ $l=(a+b+c)\in (2\sqrt {3},3\sqrt {3}]$ ，即 $\vartriangle ABC$ 的周长的取值范围为 $(2\sqrt {3},3\sqrt {3}]$ .

## 知识点

**中文**:
  - 三角恒等变换的综合应用
  - 函数y=Asin（ωx＋φ）的图象和性质

**English**:
  - Comprehensive Application of Identities
  - Graph and Properties of y=Asin(ωx+φ)

---
