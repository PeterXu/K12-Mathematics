# Mathematics - 题目 2792

**ID**: 0996383c5f854cb0be8a69fb160d21be
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
我们知道，函数 $y=f\left ({x}\right )$ 图象关于坐标原点成中心对称的图形的充要条件是函数 $y=f\left ({x}\right )$ 为奇函数，有同学发现可以将其推广为函数 $y=f\left ({x}\right )$ 的图象关于点 $P\left ({a,b}\right )$ 成中心对称图形的充要条件是函数 $y=f\left ({x+a}\right )-b$ 为奇函数．给定函数 $f(x)=x-\frac {6}{x+1}$ ．（1）求函数 $f\left ({x}\right )$ 图象的对称中心；​​​​​​​‌（2）用定义证明 $f\left ({x}\right )$ 在区间 $(-1,+\infty )$ 上的单调性，并求 $f\left ({x}\right )$ 在 $\left [{{1}}{\rm{,}}{{5}}\right ]$ 上的值域；（3）已知函数 $g\left ({x}\right )$ 的图象关于点 $\left ({1,1}\right )$ 对称，且当 $x\in [0,1]$ 时， $g\left ({x}\right )=x{^{2}}$ ．若对任意 $x{{}_{1}}\in [0,2]$ ，总存在 $x{{}_{2}}\in [1,5]$ ，使得 $g(x{{}_{1}})=f(x{{}_{2}})+m$ ，求实数 $m$ 的取值范围．

## 解答

1. （1）设函数 $f\left ({x}\right )$ 图象的对称中心为 $\left ({a,b}\right )$ ，则 $f\left ({a+x}\right )+f\left ({a-x}\right )-2b=0$ ，
2. 即 $\left ({x+a}\right )-\frac {6}{x+a+1}+\left ({-x+a}\right )-\frac {6}{-x+a+1}-2b=0$ ，
3. 整理得 $\left ({a-b}\right )x{^{2}}=\left ({a-b}\right ){\left({a+1}\right)^{2}}-6\left ({a+1}\right )$ ，
4. 于是 $\left ({a-b}\right )=\left ({a-b}\right ){\left({a+1}\right)^{2}}-6\left ({a+1}\right )=0$ ，解得 $a=b=-1$ ，
5. 所以 $f\left ({x}\right )$ 的对称中心为 $\left ({-1,-1}\right )$ .
6. （2）任取 $x{{}_{1}},x{{}_{2}}\in \left ({-1,+∞}\right )$ ，且 $x{{}_{1}}<x{{}_{2}}$ ，则
7. $f\left ({x{{}_{1}}}\right )-f\left ({x{{}_{2}}}\right )=x{{}_{1}}-\frac {6}{x{{}_{1}}+1}-\left ({x{{}_{2}}-\frac {6}{x{{}_{2}}+1}}\right )=\left ({x{{}_{1}}-x{{}_{2}}}\right )\left [1+\frac {6}{\left ({x{{}_{1}}+1}\right )\left ({x{{}_{2}}+1}\right )}\right ]$ ，
8. 所以 $x{{}_{1}}-x{{}_{2}}<0$ 且 $1+\frac {6}{\left ({x{{}_{1}}+1}\right )\left ({x{{}_{2}}+1}\right )}>0$ ，
9. 所以 $f\left ({x{{}_{1}}}\right )-f\left ({x{{}_{2}}}\right )<0$ ，即 $f\left ({x{{}_{1}}}\right )<f\left ({x{{}_{2}}}\right )$ ，
10. 所以 $f\left ({x}\right )=x-\frac {6}{x+1}$ 在 $\left ({-1,+∞}\right )$ 上单调递增.
11. 所以 $f\left ({x}\right )$ 在 $\left [1,5\right ]$ 上单调递增，故 $f\left ({x}\right )$ 的值域为 $\left [-2,4\right ]$ .
12. （3）由于对任意 $x{{}_{1}}\in \left [0,2\right ]$ ，总存在 $x{{}_{2}}\in [1,5]$ ，使得 $g(x{{}_{1}})=f(x{{}_{2}})+m$ ，
13. 于是问题转化为 $g\left ({x}\right )$ 在 $\left [0,2\right ]$ 上的值域是 $f\left ({x}\right )+m$ 值域的子集，
14. $g\left ({x}\right )$ 在 $\left [0,1\right ]$ 单调递增，图象又关于点 $\left ({1,1}\right )$ 对称且经过点 $\left ({1,1}\right )$ ，
15. 可知 $g\left ({x}\right )$ 在 $\left ({1,2}\right ]$ 上也单调递增，故 $g\left ({x}\right )$ 在 $\left [0,2\right ]$ 上单调递增，又 $g\left ({0}\right )=0$ ； $g\left ({2}\right )=2$ ，
16. 所以 $g\left ({x}\right )$ 在 $\left [0,2\right ]$ 的值域为 $\left [0,2\right ]$ ， $f\left ({x}\right )+m$ 在 $\left [1,5\right ]$ 的值域为 $\left [-2+m,4+m\right ]$ ，
17. $\therefore \left [0,2\right ]\subseteq \left [-2+m,4+m\right ]$ ， $\therefore \begin{cases}0\geqslant -2+m\\2\leqslant 4+m\end{cases}$ ，解得 $-2\leqslant m\leqslant 2$ ，则 $m$ 的取值范围是 $\left [-2,2\right ]$ .

## 知识点

**中文**:
  - 与函数有关的参数问题
  - 函数单调性的判断与证明
  - 函数对称性

**English**:
  - Parameter Problems Related to Functions
  - Judgment and Proof of Monotonicity
  - Symmetry of Functions

---
