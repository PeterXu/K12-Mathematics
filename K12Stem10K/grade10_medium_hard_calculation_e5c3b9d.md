# Mathematics - 题目 78

**ID**: e5c3b9da49b146d4981729fcd061ea6d
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设P为多面体M的一个顶点，定义多面体M在点P处的离散曲率为 $1-\frac {1}{2{\rm{π}}}\left ({\angle Q{{}_{1}}PQ{{}_{2}}+\angle Q{{}_{2}}PQ{{}_{3}}+\cdots +\angle Q{{}_{k-1}}PQ{{}_{k}}+\angle Q{{}_{k}}PQ{{}_{1}}}\right )$ ，其中 $Q{{}_{i}}$ （ $i=1{\rm ，2}$ ，…， ${\rm \mathit{k}，}k\geqslant 3$ ）为多面体M的所有与点P相邻的顶点，且平面 $Q{{}_{1}}PO{{}_{2}}$ ，平面 $Q{{}_{2}}PO{{}_{3}}$ ，…，平面 $Q{{}_{k-1}}PQ{{}_{k}}$ 和平面 $Q{{}_{k}}PQ{{}_{1}}$ 为多面体M的所有以P为公共点的面．已知在直四棱柱 $ABCD-A{{}_{1}}B{{}_{1}}C{{}_{1}}D{{}_{1}}$ 中，底面ABCD为菱形，且 $AA{{}_{1}}=AB=1$ ．(1)求直四棱柱 $ABCD-A{{}_{1}}B{{}_{1}}C{{}_{1}}D{{}_{1}}$ 在各个顶点的离散曲率之和；​​​​​​​‌(2)若直四棱柱 $ABCD-A{{}_{1}}B{{}_{1}}C{{}_{1}}D{{}_{1}}$ 在点A处的离散曲率为x，直四棱柱 $ABCD-AB{{}_{1}}C{{}_{1}}D{{}_{1}}$ 体积为 $f\left ({x}\right )$ ，求函数 $y=f\left ({x}\right )$ 的解析式及单调区间．

## 解答

1. （1）在直四棱柱 $ABCD-A{{}_{1}}B{{}_{1}}C{{}_{1}}D{{}_{1}}$ 中, $\angle A{{}_{1}}AD=\angle A{{}_{1}}AB=\frac {{\rm{π}}}{{{2}}}$ ，底面ABCD为菱形，
2. 由离散曲率的定义知： $A,A{{}_{1}},C,C{{}_{1}}$ 的离散曲率相等， $B,B{{}_{1}},D,D{{}_{1}}$ 的离散曲率相等，
3. 所以 $A$ 处的曲率为 $1-\frac {1}{2{\rm{π}}}\times (\frac {{\rm{π}}}{2}+\frac {{\rm{π}}}{2}+\angle BAD)=\frac {1}{2}-\frac {\angle BAD}{2{\rm{π}}}$ ，而 $D$ 处的曲率为 $1-\frac {1}{2{\rm{π}}}\times (\frac {{\rm{π}}}{2}+\frac {{\rm{π}}}{2}+\angle ADC)=\frac {1}{2}-\frac {\angle ADC}{2{\rm{π}}}$ ，又 $\angle BAD+\angle ADC={\rm{π}}$ ，
4. 所以 $A$ 、 $D$ 两处的曲率和为 $\frac {1}{2}-\frac {\angle BAD}{2{\rm{π}}}+\frac {1}{2}-\frac {\angle ADC}{2{\rm{π}}}=1-\frac {\angle BAD+\angle ADC}{2{\rm{π}}}=\frac {1}{2}$ ，
5. 故直四棱柱 $ABCD-AB{{}_{1}}C{{}_{1}}D{{}_{1}}$ 在各个顶点的离散曲率之和 $4\times \frac {1}{2}=2$ .
6. 
7. （2）由题设， $A$ 处的曲率 $1-\frac {1}{2{\rm{π}}}\times (\frac {{\rm{π}}}{2}+\frac {{\rm{π}}}{2}+\angle BAD)=\frac {1}{2}-\frac {\angle BAD}{2{\rm{π}}}=x$ ，故 $\angle BAD={\rm{π}}(1-2x)$ ，
8. 所以直四棱柱底面面积为 $2S{{}_{\vartriangle ABD}}=2\times \frac {1}{2}\times 1{^{2}}\times \sin {\rm{π}}(1-2x)=\sin {\rm{π}}(1-2x)=\sin 2{\rm{π}}x$ ，
9. 故直四棱柱 $ABCD-AB{{}_{1}}C{{}_{1}}D{{}_{1}}$ 高为1，故体积为 $f(x)=\sin 2{\rm{π}}x$ ，
10. 令 $2k{\rm{π}}-\frac {{\rm{π}}}{2}\leqslant 2{\rm{π}}x\leqslant 2k{\rm{π}}+\frac {{\rm{π}}}{2}$ ， $k\in \mathbf{Z}$ ，可得 $k-\frac {1}{4}\leqslant x\leqslant k+\frac {1}{4}$ ， $k\in \mathbf{Z}$ ，即 $[k-\frac {1}{4},k+\frac {1}{4}]$ ， $k\in \mathbf{Z}$ 上 $f(x)$ 递增；
11. 令 $2k{\rm{π}}+\frac {{\rm{π}}}{2}\leqslant 2{\rm{π}}x\leqslant 2k{\rm{π}}+\frac {{{3}}{\rm{π}}}{2}$ ， $k\in \mathbf{Z}$ ，可得 $k+\frac {1}{4}\leqslant x\leqslant k+\frac {3}{4}$ ， $k\in \mathbf{Z}$ ，即 $[k+\frac {1}{4},k+\frac {3}{4}]$ ， $k\in \mathbf{Z}$ 上 $f(x)$ 递减；
12. 所以 $f(x)$ 增区间为 $[k-\frac {1}{4},k+\frac {1}{4}]$ ，减区间为 $[k+\frac {1}{4},k+\frac {3}{4}]$ ， $k\in \mathbf{Z}$ .

## 知识点

**中文**:
  - 新定义问题

**English**:
  - New Definition Problems

---
