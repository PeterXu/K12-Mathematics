# Mathematics - 题目 2416

**ID**: 713975117af94ddfad422ce450d251ba
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )={\rm{e}}{^{x}}$ .​​​​​​​‌（1）证明不等式： $f\left ({x}\right )\geqslant f^{′}{\left ({m}\right )}\left ({x-m}\right )+f\left ({m}\right )$ ；（2）记 $a{{}_{n}}=f\left ({n}\right )$ ，证明： $\sum \limits_{i=1}^{n}\mathop{a{{}_{i}}}\geqslant n\cdot {\rm{e}}{^{\frac {n+1}{2}}}$ ；（3）已知 $k{{}_{1}},k{{}_{2}},\cdot \cdot \cdot ,k{{}_{n}}>0$ ，证明： $\frac {k{{}_{1}}+k{{}_{2}}+\cdot \cdot \cdot +k{{}_{n}}}{n}\geqslant \sqrt[n]{k{{}_{1}}\cdot k{{}_{1}}\cdot \cdots \cdot k{{}_{n}}}$ .

## 解答

1. （1）令 $g\left ({x}\right )=f\left ({x}\right )-f^{′}{\left ({m}\right )}\left ({x-m}\right )-f\left ({m}\right )$ ，
2. 则 $g^{′}{\left ({x}\right )}=f^{′}{\left ({x}\right )}-f^{′}{\left ({m}\right )}={\rm{e}}{^{x}}-{\rm{e}}{^{m}}$ ，
3. 在 $x\in \left ({-\infty ,m}\right ),g^{′}{\left ({x}\right )}<0,$ ，在 $x\in \left ({m,+\infty }\right ),g^{′}{\left ({x}\right )}>0$ ，
4. 故 $g\left ({x}\right )$ 在 $\left ({-\infty ,m}\right )$ 上单调递减，在 $\left ({m,+\infty }\right )$ 上单调递增，
5. 所以 $g\left ({x}\right )\geqslant g\left ({m}\right )=0$ 即 $f\left ({x}\right )\geqslant f^{′}{\left ({m}\right )}\left ({x-m}\right )+f\left ({m}\right )$ ；
6. （2）由（1）知 $a{{}_{i}}=f\left ({i}\right )\geqslant f^{′}{\left ({m}\right )}\left ({i-m}\right )+f\left ({m}\right )$ ，
7. 所以 $\sum\limits_{{\rm i}=1}^{n}\mathop{}a{{}_{{\rm i}}}\geqslant \sum\limits_{{\rm i}=1}^{n}\mathop{}\left ({f^{′}{\left ({m}\right )}\left ({{\rm i}-m}\right )+f\left ({m}\right )}\right )=f^{′}{\left ({m}\right )}\left ({\sum\limits_{{\rm i}=1}^{n}\mathop{}{\rm i}-nm}\right )+nf\left ({m}\right )$ ，
8. 令 $m=\frac {\sum\limits_{{\rm i}=1}^{n}\mathop{}{\rm i}}{n}=\frac {1}{2}\left ({n+1}\right )$ 得 $\sum\limits_{i=1}^{n}\mathop{}a{{}_{i}}\geqslant nf\left ({\frac {1}{2}\left ({n+1}\right )}\right )=n\cdot {\rm{e}}{^{\frac {n+1}{2}}}$ ；
9. （3）要证 $\frac {k{{}_{1}}+k{{}_{2}}+\cdot \cdot \cdot +k{{}_{n}}}{n}\geqslant \sqrt[n]{k{{}_{1}}\cdot k{{}_{1}}\cdot \cdots \cdot k{{}_{n}}}$ ，
10. 只要证 $\frac {{\rm{l}}{\rm{n}}k{{}_{1}}+{\rm{l}}{\rm{n}}k{{}_{2}}+\cdot \cdot \cdot +{\rm{l}}{\rm{n}}k{{}_{n}}}{n}\leqslant {\rm{l}}{\rm{n}}\left ({\frac {k{{}_{1}}+k{{}_{2}}+\cdot \cdot \cdot +k{{}_{n}}}{n}}\right )$ ，
11. 令 $h\left ({x}\right )={\rm{l}}{\rm{n}}x-\frac {1}{t}\left ({x-t}\right )-{\rm{l}}{\rm{n}}t$ ，则 $h^{′}{\left ({x}\right )}=\frac {1}{x}-\frac {1}{t}$ ，
12. 在 $x\in \left ({0,t}\right ),h^{′}{\left ({x}\right )}>0,$ ，在 $x\in \left ({t,+\infty }\right ),h^{′}{\left ({x}\right )}<0,$
13. 故 $h\left ({x}\right )$ 在 $\left ({0,t}\right )$ 上单调递增，在 $\left ({t,+\infty }\right )$ 上单调递减，
14. 所以 $h\left ({x}\right )\leqslant h\left ({t}\right )=0$ ，故 ${\rm{l}}{\rm{n}}x\leqslant \frac {1}{t}\left ({x-t}\right )+{\rm{l}}{\rm{n}}t$ ，
15. 所以 ${\rm{l}}{\rm{n}}k{{}_{i}}\leqslant \frac {1}{t}\left ({k{{}_{i}}-t}\right )+{\rm{l}}{\rm{n}}t\left ({i=1,2,\cdot \cdot \cdot ,n}\right )\Rightarrow {\mathop {∑}\limits_{n}^{i=1}}{\rm{l}}{\rm{n}}k{{}_{i}}\leqslant \frac {1}{t}\left ({{\mathop {∑}\limits_{n}^{i=1}}k{{}_{i}}-nt}\right )+n{\rm{l}}{\rm{n}}t$ ，
16. 令 $t=\frac {\sum\limits_{i=1}^{n}\mathop{}k{{}_{i}}}{n}$ 则 ${\mathop {∑}\limits_{n}^{i=1}}{\rm{l}}{\rm{n}}k{{}_{i}}\leqslant n{\rm{l}}{\rm{n}}t$ ，
17. 即 $\frac {{\rm{l}}{\rm{n}}k{{}_{1}}+{\rm{l}}{\rm{n}}k{{}_{2}}+\cdot \cdot \cdot +{\rm{l}}{\rm{n}}k{{}_{n}}}{n}\leqslant {\rm{l}}{\rm{n}}\left ({\frac {k{{}_{1}}+k{{}_{2}}+\cdot \cdot \cdot +k{{}_{n}}}{n}}\right )$ .

## 知识点

**中文**:
  - 利用导数证明不等式

**English**:
  - Proving Inequalities using Derivatives

---
