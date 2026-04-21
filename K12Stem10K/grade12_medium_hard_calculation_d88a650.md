# Mathematics - 题目 2934

**ID**: d88a650fdafc4c82bd2e8dc9e7f6b3f1
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=x+a{\rm{s}}{\rm{i}}{\rm{n}}x,g\left ({x}\right )=b{\rm{l}}{\rm{n}}x\left ({a,b\in {\mathbf{R}}}\right )$ ，且曲线 $y=g\left ({x}\right )$ 在点 $\left ({1,0}\right )$ 处的切线方程为 $y=-x+1$ .​​​​​​​‌（1）求实数 $b$ 的值.（2）当 $a=-1$ 时，证明：当 $x>0$ 时， $f\left ({x}\right )>0$ .（3）当 $a=\frac {1}{3}$ 时，若存在 $0<x{{}_{1}}<x{{}_{2}}$ ，使得 $f\left ({x{{}_{1}}}\right )+g\left ({x{{}_{1}}}\right )=f\left ({x{{}_{2}}}\right )+g\left ({x{{}_{2}}}\right )$ 成立，证明： $\sqrt {x{{}_{1}}}+\sqrt {x{{}_{2}}}>\sqrt {3}$ .

## 解答

1. （1） $\because g\left ({x}\right )=b{\rm{l}}{\rm{n}}x,\therefore g^{′}{\left ({x}\right )}=\frac {b}{x}$ .
2. $\because $ 曲线 $y=g\left ({x}\right )$ 在点 $\left ({1,0}\right )$ 处的切线方程为 $y=-x+1,\therefore g^{′}{\left ({1}\right )}=b=-1$ .
3. （2） $\because $ 当 $a=-1$ 时， $f\left ({x}\right )=x-{\rm{s}}{\rm{i}}{\rm{n}}x$ ，
4. $\therefore f^{′}{\left ({x}\right )}=1-{\rm{c}}{\rm{o}}{\rm{s}}x\geqslant 0$ 在 $\left ({0,+∞}\right )$ 上恒成立，
5. $\therefore f\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上单调递增，
6. $\therefore $ 当 $x>0$ 时， $f\left ({x}\right )>f\left ({0}\right )=0$ .
7. （3） $\because $ 当 $a=\frac {1}{3}$ 时， $f\left ({x}\right )=x+\frac {1}{3}{\rm{s}}{\rm{i}}{\rm{n}}x,g\left ({x}\right )=-{\rm{l}}{\rm{n}}x$ ，
8. 当 $0<x{{}_{1}}<x{{}_{2}}$ 时，存在 $f\left ({x{{}_{1}}}\right )+g\left ({x{{}_{1}}}\right )=f\left ({x{{}_{2}}}\right )+g\left ({x{{}_{2}}}\right )$ 成立，
9. $\therefore x{{}_{1}}+\frac {1}{3}{\rm{s}}{\rm{i}}{\rm{n}}x{{}_{1}}-{\rm{l}}{\rm{n}}x{{}_{1}}=x{{}_{2}}+\frac {1}{3}{\rm{s}}{\rm{i}}{\rm{n}}x{{}_{2}}-{\rm{l}}{\rm{n}}x{{}_{2}}$ ，
10. 得 $x{{}_{2}}-x{{}_{1}}+\frac {1}{3}\left ({{\rm{s}}{\rm{i}}{\rm{n}}x{{}_{2}}-{\rm{s}}{\rm{i}}{\rm{n}}x{{}_{1}}}\right )={\rm{l}}{\rm{n}}x{{}_{2}}-{\rm{l}}{\rm{n}}x{{}_{1}}$ .
11. 由（2）可知，当 $x>0$ 时， $f\left ({x}\right )=x-{\rm{s}}{\rm{i}}{\rm{n}}x$ 单调递增，
12. $\therefore x{{}_{2}}-{\rm{s}}{\rm{i}}{\rm{n}}x{{}_{2}}>x{{}_{1}}-{\rm{s}}{\rm{i}}{\rm{n}}x{{}_{1}}$ ，即 $x{{}_{2}}-x{{}_{1}}>{\rm{s}}{\rm{i}}{\rm{n}}x{{}_{2}}-{\rm{s}}{\rm{i}}{\rm{n}}x{{}_{1}}$ ，
13. $\therefore {\rm{l}}{\rm{n}}\frac {x{{}_{2}}}{x{{}_{1}}}<\frac {4}{3}\left ({x{{}_{2}}-x{{}_{1}}}\right )$ ，
14. 设 $M\left ({x}\right )={\rm{l}}{\rm{n}}x-2\cdot \frac {x-1}{x+1}$ ，
15. 则 $M^{′}{\left ({x}\right )}=\frac {1}{x}-\frac {4}{(x+1){^{2}}}=\frac {(x-1){^{2}}}{x(x+1){^{2}}}\geqslant 0$ ，
16. $\therefore $ 当 $x>1$ 时， $M\left ({x}\right )>M\left ({1}\right )=0$ ，则 ${\rm{l}}{\rm{n}}x>2\cdot \frac {x-1}{x+1}$ ，
17. $\therefore {\rm{l}}{\rm{n}}\sqrt {\frac {x{{}_{2}}}{x{{}_{1}}}}>2\cdot \frac {\sqrt {\frac {x{{}_{2}}}{x{{}_{1}}}}-1}{\sqrt {\frac {x{{}_{2}}}{x{{}_{1}}}}+1}=2\cdot \frac {\sqrt {x{{}_{2}}}-\sqrt {x{{}_{1}}}}{\sqrt {x{{}_{2}}}+\sqrt {x{{}_{1}}}},\therefore {\rm{l}}{\rm{n}}\frac {x{{}_{2}}}{x{{}_{1}}}>4\cdot \frac {\sqrt {x{{}_{2}}}-\sqrt {x{{}_{1}}}}{\sqrt {x{{}_{2}}}+\sqrt {x{{}_{1}}}}$ ，
18. $\therefore 4\cdot \frac {\sqrt {x{{}_{2}}}-\sqrt {x{{}_{1}}}}{\sqrt {x{{}_{2}}}+\sqrt {x{{}_{1}}}}<\frac {4}{3}\left ({\sqrt {x{{}_{2}}}-\sqrt {x{{}_{1}}}}\right )\left ({\sqrt {x{{}_{2}}}+\sqrt {x{{}_{1}}}}\right ),\therefore 3<{\left({\sqrt {x{{}_{2}}}+\sqrt {x{{}_{1}}}}\right)^{2}}$ ，
19. $\therefore \sqrt {x{{}_{1}}}+\sqrt {x{{}_{2}}}>\sqrt {3}$ .

## 知识点

**中文**:
  - 利用导数解决不等式能成立问题
  - 导数几何意义的应用
  - 利用导数证明不等式

**English**:
  - Solving Solvable Inequality Problems
  - Applications of Geometric Meaning of Derivatives
  - Proving Inequalities using Derivatives

---
