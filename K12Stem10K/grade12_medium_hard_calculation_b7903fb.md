# Mathematics - 题目 3086

**ID**: b7903fbb859e42ea849136be6cc7f05e
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )={\ln}x-\frac {a\left ({x-1}\right )}{x+1}$ .​​​​​​​‌（1）若函数 $f\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上为单调增函数，求 $a$ 的取值范围；（2）设 $m,n\in {\rm{R}}$ ，且 $m\ne n$ ，求证 $\frac {m-n}{{\ln}m-{\ln}n}<\frac {m+n}{2}$ .

## 解答

1. 解：（1） $f^{′}{\left ({x}\right )}=\frac {1}{x}-\frac {a\left ({x+1}\right )-a\left ({x-1}\right )}{{\left({x+1}\right)^{2}}}=\frac {{\left({x+1}\right)^{2}}-2ax}{x{\left({x+1}\right)^{2}}}=\frac {x{^{2}}+\left ({2-2a}\right )x+1}{x{\left({x+1}\right)^{2}}}$ ，
2. 因为 $f\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上为单调增函数，所以 $f^{′}{\left ({x}\right )}\geqslant 0$ 在 $\left ({0,+∞}\right )$ 上恒成立
3. 即 $x{^{2}}+\left ({2-2a}\right )x+1\geqslant 0$ 在 $\left ({0,+∞}\right )$ 上恒成立，
4. 当 $x\in \left ({0,+\infty }\right )$ 时，由 $x{^{2}}+\left ({2-2a}\right )x+1\geqslant 0$ ，
5. 得： $2a-2\leqslant x+\frac {1}{x}$ ，设 $g\left ({x}\right )=x+\frac {1}{x},x\in \left ({0,+\infty }\right )$ ，
6. 则 $g\left ({x}\right )=x+\frac {1}{x}\geqslant 2\sqrt {x\cdot \frac {1}{x}}=2$ ，当且仅当 $x=\frac {1}{x}$ 即 $x=1$ 时， $g\left ({x}\right )$ 有最小值2，
7. 所以 $2a-2\leqslant 2$ ，解得 $a\leqslant 2$ ，所以 $a$ 的取值范围是 $\left ({-\infty ,2}\right ]$ ；
8. （2）设 $m>n$ ，
9. 要证 $\frac {m-n}{{\ln}m-{\ln}n}<\frac {m+n}{2}$ ，只需证 $\frac {\frac {m}{n}-1}{{\ln}\frac {m}{n}}<\frac {\frac {m}{n}+1}{2}$ ，
10. 即 ${\ln}\frac {m}{n}>\frac {2\left ({\frac {m}{n}-1}\right )}{\frac {m}{n}+1}$ ，即 ${\ln}\frac {m}{n}-\frac {2\left ({\frac {m}{n}-1}\right )}{\frac {m}{n}+1}>0$ ，
11. 设 $h\left ({x}\right )={\ln}x-\frac {2\left ({x-1}\right )}{x+1}$ ，
12. 由（1）知 $h\left ({x}\right )$ 在 $\left ({1,+\infty }\right )$ 上是单调增函数，又 $\frac {m}{n}>1$ ，
13. 所以 $h\left ({\frac {m}{n}}\right )>h\left ({1}\right )=0$ ，即 ${\ln}\frac {m}{n}-\frac {2\left ({\frac {m}{n}-1}\right )}{\frac {m}{n}+1}>0$ 成立，
14. 得到 $\frac {m-n}{{\ln}m-{\ln}n}<\frac {m+n}{2}$ .

## 知识点

**中文**:
  - 利用导数求函数中的参数
  - 利用导数证明不等式

**English**:
  - Finding Parameters using Derivatives
  - Proving Inequalities using Derivatives

---
