# Mathematics - 题目 3244

**ID**: 6196306fc5b246e3a829f57e61e664b8
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知 $a\in {\mathbf{R}}$ ，函数 $f(x)={\ln}x-ax+1$ ，曲线 $y=f(x)$ 在点 $A(1,f(1))$ 处的切线为 $l$ .​​​​​​​‌（1）证明： $l$ 过定点；（2）证明：除点 $A$ 外，曲线 $y=f(x)$ 都在 $l$ 的下方；（3）若 $a=1$ ，当 $x>1$ 时， $f(x)\geqslant \frac {m{\rm{e}}{^{x}}}{x}$ ，求实数 $m$ 的取值范围.

## 解答

1. （1）由题意得 $f^{′}(x)=\frac {1}{x}-a,x>0$ ，
2. 则 $f^{′}(1)=1-a$ ，且 $f(1)=1-a$ ，
3. 所以 $l$ 的方程为 $y=(1-a)(x-1)+1-a$ ，即 $y=(1-a)x$ .
4. 故 $l$ 过定点 $(0,0)$ .
5. （2）原命题等价于 $f(x)\leqslant (1-a)x$ ，即 ${\ln}x-x+1\leqslant 0$ ；
6. 设 $g(x)={\ln}x-x+1$ ，则 $g{^{\prime }}(x)=\frac {1}{x}-1=\frac {1-x}{x},x>0$ .
7. 当 $x\in (0,1)$ 时， $g^{′}(x)>0,g(x)$ 单调递增，当 $x\in (1,+\infty )$ 时， $g^{′}(x)<0,g(x)$ 单调递减，
8. 所以 $g(x)\leqslant g(1)=0$ ，仅当 $x=1$ 时等号成立，即原命题成立.
9. （3）当 $x>1$ 时， $f(x)\geqslant \frac {m{\rm{e}}{^{x}}}{x}$ 可转化为 $m\leqslant \frac {({\ln}x-x+1)x}{{\rm{e}}{^{x}}}$ .
10. 设 $h(x)=\frac {({\ln}x-x+1)x}{{\rm{e}}{^{x}}}$ ，则 $h^{′}(x)=\frac {(1-x)({\ln}x-x+2)}{{\rm{e}}{^{x}}}$ .
11. 当 $x>1$ 时， $1-x<0$ ，由（2）可知 $φ(x)={\ln}x-x+2$ 在 $(1,+\infty )$ 上单调递减，
12. 又 $φ({\rm{e}})={\ln}{\rm{e}}-{\rm{e}}+2=3-{\rm{e}}>0,φ\left ({{\rm{e}}{^{2}}}\right )={\ln}{\rm{e}}{^{2}}-{\rm{e}}{^{2}}+2=4-{\rm{e}}{^{2}}<0$ ，
13. 所以 $φ(x)$ 在 $\left ({{\rm{e}},{\rm{e}}{^{2}}}\right )$ 内存在唯一的零点 $x{{}_{0}}$ ，
14. 当 $x\in \left ({1,x{{}_{0}}}\right )$ 时， $φ(x)>0,h^{′}(x)<0,h(x)$ 单调递减，
15. 当 $x\in \left ({x{{}_{0}},+\infty }\right )$ 时， $φ(x)<0,h{^{\prime }}(x)>0,h(x)$ 单调递增，
16. 所以 $h(x){{}_{{\rm{m}}{\rm{i}}{\rm{n}}{\rm{\;}}}}=h\left ({x{{}_{0}}}\right )=\frac {\left ({{\ln}x{{}_{0}}-x{{}_{0}}+1}\right )x{{}_{0}}}{{\rm{e}}{^{x{{}_{0}}}}}$ .
17. 又 $φ\left ({x{{}_{0}}}\right )={\ln}x{{}_{0}}-x{{}_{0}}+2=0$ ，所以 ${\ln}x{{}_{0}}-x{{}_{0}}+1=-1,x{{}_{0}}={\rm{e}}{^{x{{}_{0}}-2}}$ ，
18. 所以 $h(x){{}_{{\rm \min }}}=-\frac {{\rm{e}}{^{x{{}_{0}}-2}}}{{\rm{e}}{^{x{{}_{0}}}}}=-\frac {1}{{\rm{e}}{^{2}}}$ ，所以 $m\leqslant -\frac {1}{{\rm{e}}{^{2}}}$ ，
19. 即实数 $m$ 的取值范围是 $\left ({-\infty ,-\frac {1}{{\rm{e}}{^{2}}}}\right ]$ .

## 知识点

**中文**:
  - 利用导数研究函数的图象
  - 导数几何意义的应用
  - 利用导数解决不等式恒成立问题

**English**:
  - Studying Function Graphs
  - Applications of Geometric Meaning of Derivatives
  - Solving Universally True Inequalities

---
