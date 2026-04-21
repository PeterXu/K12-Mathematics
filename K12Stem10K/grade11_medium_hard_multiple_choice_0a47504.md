# Mathematics - 题目 592

**ID**: 0a4750405be64181ae524eeed8d699ac
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Multiple-choice

## 题目
已知等差数列 $\{a{{}_{n}}\}$ 的公差 $d\in (0,1)$ ，且 $\frac {\sin {^{2}}a{{}_{3}}-\sin {^{2}}a{{}_{7}}}{\sin (a{{}_{3}}+a{{}_{7}})}=-1$ ，当 $n=10$ 时，数列 $\{a{{}_{n}}\}$ 的前 $n$ 项和 $S{{}_{n}}$ 取得最小值，则首项 $a{{}_{1}}$ 的取值范围是​​​​​​​‌

## 解答

1. 试题分析：利用三角函数的降幂公式将条件 $\frac {\sin {^{2}}a{{}_{3}}-\sin {^{2}}a{{}_{7}}}{\sin (a{{}_{3}}+a{{}_{7}})}=-1$ 转化为 $\frac {\cos 2a{{}_{7}}-\cos 2a{{}_{3}}}{2}=-\sin （a{{}_{3}}+a{{}_{7}}）$ 再利用和差化积公式转化，求得 $\sin （a{{}_{7}}-a{{}_{3}}）=1$ ，从而可求得等差数列 $\{a{{}_{n}}\}$ 的公差 $d=\frac {π}{8}$ ，根据 $\{\hspace{-0.5em}\begin{array}{}a{{}_{10}}\leqslant 0\\a{{}_{11}}\geqslant 0\end{array}\hspace{-0.5em}$ 即可求得首项 $a{{}_{1}}$ 的取值范围．
2. ∵ $\{a{{}_{n}}\}$ 为等差数列， $\frac {\sin {^{2}}a{{}_{3}}-\sin {^{2}}a{{}_{7}}}{\sin (a{{}_{3}}+a{{}_{7}})}=-1$ ，
3. $\therefore \frac {\frac {1-\cos 2a{{}_{3}}}{2}-\frac {1-\cos 2a{{}_{7}}}{2}}{\sin \left ({a{{}_{3}}+a{{}_{7}}}\right )}=-1，\therefore \frac {\cos 2a{{}_{7}}-\cos 2a{{}_{3}}}{2}=-\sin （a{{}_{3}}+a{{}_{7}}），$
4. $\therefore \frac {1}{2}\times （-2）\sin （a{{}_{7}}+a{{}_{3}}）\cdot \sin （a{{}_{7}}-a{{}_{3}}）=-\sin （a{{}_{3}}+a{{}_{7}}），\because \sin （a{{}_{3}}+a{{}_{7}}）\ne 0，\therefore \sin （a{{}_{7}}-a{{}_{3}}）=1，$
5. $\therefore 4d=2kπ+\frac {π}{2}\in （0，4）\therefore k=0，\therefore 4d=\frac {π}{2}，\therefore d=\frac {π}{8}$ ，
6. ∵ $n=10$ 时，数列 $\{a{{}_{n}}\}$ 的前 $n$ 项和 $S{{}_{n}}$ 取得最小值， $\{\hspace{-0.5em}\begin{array}{}a{{}_{10}}\leqslant 0\\a{{}_{11}}\geqslant 0\end{array}\hspace{-0.5em},\therefore \{\hspace{-0.5em}\begin{array}{}a{{}_{1}}+9\times \frac {π}{8}\leqslant 0\\a{{}_{1}}+10\times \frac {π}{8}\geqslant 0\end{array}\hspace{-0.5em}，\therefore -\frac {5π}{4}\leqslant a{{}_{1}}\leqslant -\frac {9π}{8}$ ，
7. 故选D
8. 考点：数列与三角函数的综合；等差数列的通项公式；等差数列的前n项和．
9. 【方法点睛】本题考查数列与三角函数的综合，利用三角函数的降幂公式与和差化积公式求得 $\sin （a{{}_{7}}-a{{}_{3}}）=1$ 是关键，也是难点，继而可求出 $d=\frac {π}{8}$ ，问题迎刃而解，突出化归思想与函数与方程思想的考查，属于难题．

## 知识点

**中文**:
  - 等差数列前n项和的函数特性
  - 等差数列的概念及通项公式

**English**:
  - Functional Properties of Sum
  - Concept and Formula

---
