# Mathematics - 题目 1825

**ID**: 955a2230d6764f23a7e6d7567273712a
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
1799年，哥廷根大学的高斯在其博士论文中证明了如下定理：任何复系数一元 $n$ 次多项式方程在复数域上至少有一根（ $n\geqslant 1$ ）.​​​​​​​‌此定理被称为代数基本定理，在代数乃至整个数学中起着基础作用.由此定理还可以推出以下重要结论： $n$ 次复系数多项式方程在复数域内有且只有 $n$ 个根（重根按重数计算）.对于 $n$ 次复系数多项式 $f\left ({x}\right )=x{^{n}}+a{{}_{n-1}}x{^{n-1}}+\cdot \cdot \cdot +a{{}_{1}}x+a{{}_{0}}$ ，其中 $a{{}_{n-1}}$ ， $a{{}_{n-2}}$ ， $\cdot \cdot \cdot ,a{{}_{0}}\in {\mathbf{C}}$ ，若方程 $f\left ({x}\right )=0$ 有 $n$ 个复根 $x{{}_{1}},x{{}_{2}},\cdot \cdot \cdot ,x{{}_{n}}$ ，则有如下的高阶韦达定理： $\begin{cases}\sum\limits_{i=1}^{n}\mathop{}x{{}_{i}}=-a{{}_{n-1}}\\\sum\limits_{1\leqslant i<j\leqslant n}^{n}\mathop{}x{{}_{i}}x{{}_{j}}=a{{}_{n-2}}\\\sum\limits_{1\leqslant i<j<k\leqslant n}^{n}\mathop{}x{{}_{i}}x{{}_{j}}x{{}_{k}}=-a{{}_{n-3}}\\\vdots \\x{{}_{1}}x{{}_{2}}\cdot \cdot \cdot x{{}_{n}}={\left({-1}\right)^{n}}a{{}_{0}}\end{cases}$(1)在复数域内解方程 $x{^{2}}+4=0$ ；(2)若三次方程 $x{^{3}}+ax{^{2}}+bx+c=0$ 的三个根分别是 $x{{}_{1}}=1-{\rm{i}}$ ， $x{{}_{2}}=1+{\rm{i}}$ ， $x{{}_{3}}=2$ （ ${\rm{i}}$ 为虚数单位），求 $a$ ， $b$ ， $c$ 的值；(3)在 $n\geqslant 4$ 的多项式 $f\left ({x}\right )=x{^{n}}+a{{}_{n-1}}x{^{n-1}}+\cdot \cdot \cdot +a{{}_{1}}x+a{{}_{0}}$ 中，已知 $a{{}_{n-1}}=-1$ ， $a{{}_{1}}=-n{^{2}}a$ ， $a{{}_{0}}=a$ ， $a$ 为非零实数，且方程 $f\left ({x}\right )=0$ 的根恰好全是正实数，求出该方程的所有根（用含 $n$ 的式子表示）.

## 解答

1. （1）由 $x{^{2}}+4=0$ 可得 $x{^{2}}=-4$ ，解得 $x=\pm 2{\rm{i}}$ .
2. （2）由题意可知： $\begin{cases}x{{}_{1}}+x{{}_{2}}+x{{}_{3}}=-a\\x{{}_{1}}x{{}_{2}}+x{{}_{2}}x{{}_{3}}+x{{}_{1}}x{{}_{3}}=b\\x{{}_{1}}x{{}_{2}}x{{}_{3}}=-c\end{cases}$ ，
3. 将 $x{{}_{1}}=1-{\rm{i}}$ ， $x{{}_{2}}=1+{\rm{i}}$ ， $x{{}_{3}}=2$ 代入可得 $\begin{cases}4=-a\\6=b\\4=-c\end{cases}$ ，
4. 所以 $a=4,b=6,c=-4$ .
5. （3）设 $\overrightarrow {{a}}=\left ({a{{}_{1}},a{{}_{2}},\cdot \cdot \cdot ,a{{}_{n}}}\right ),\overrightarrow {{b}}=\left ({b{{}_{1}},b{{}_{2}},\cdot \cdot \cdot ,b{{}_{n}}}\right )$ ， $a{{}_{1}},a{{}_{2}},\cdot \cdot \cdot ,a{{}_{n}},b{{}_{1}},b{{}_{2}},\cdot \cdot \cdot ,b{{}_{n}}>0$ ，
6. 因为 $\left |{\overrightarrow {{a}}\cdot \overrightarrow {{b}}}\right |\leqslant \left |{\overrightarrow {{a}}}\right |\left |{\overrightarrow {{b}}}\right |$ ，当且仅当 $\overrightarrow {{a}}$∥$\overrightarrow {{b}}$ 时，等号成立，
7. 可得 $\left |{a{{}_{1}}b{{}_{1}}+a{{}_{2}}b{{}_{2}}+\cdot \cdot \cdot +a{{}_{n}}b{{}_{n}}}\right |\leqslant \sqrt {a{{}_{1}^{2}}+a{{}_{2}^{2}}+\cdot \cdot \cdot +a{{}_{n}^{2}}}\cdot \sqrt {b{{}_{1}^{2}}+b{{}_{2}^{2}}+\cdot \cdot \cdot +b{{}_{n}^{2}}}$ ，
8. 即 $a{{}_{1}}b{{}_{1}}+a{{}_{2}}b{{}_{2}}+\cdot \cdot \cdot +a{{}_{n}}b{{}_{n}}\leqslant \sqrt {a{{}_{1}^{2}}+a{{}_{2}^{2}}+\cdot \cdot \cdot +a{{}_{n}^{2}}}\cdot \sqrt {b{{}_{1}^{2}}+b{{}_{2}^{2}}+\cdot \cdot \cdot +b{{}_{n}^{2}}}$ ，
9. 当且仅当 $\frac {a{{}_{1}}}{b{{}_{1}}}=\frac {a{{}_{2}}}{b{{}_{2}}}=\cdot \cdot \cdot =\frac {a{{}_{n}}}{b{{}_{n}}}$ 时，等号成立，
10. 因为方程 $f\left ({x}\right )=x{^{n}}+a{{}_{n-1}}x{^{n-1}}+\cdot \cdot \cdot +a{{}_{1}}x+a{{}_{0}}=0$ 的根恰好全是正实数，
11. 设这n个正根分别为 $x{{}_{1}},x{{}_{2}},\cdot \cdot \cdot ,x{{}_{n}}$ ，
12. 且 $a{{}_{n-1}}=-1$ ， $a{{}_{1}}=-n{^{2}}a$ ， $a{{}_{0}}=a$ ，
13. 由题意可知： $\begin{cases}x{{}_{1}}+x{{}_{2}}+\cdot \cdot \cdot +x{{}_{n}}=1\\x{{}_{1}}x{{}_{2}}\cdot \cdot \cdot x{{}_{n-1}}+x{{}_{1}}\cdot \cdot \cdot x{{}_{n-2}}x{{}_{n}}+\cdot \cdot \cdot +x{{}_{2}}x{{}_{3}}\cdot \cdot \cdot x{{}_{n}}={\left({-1}\right)^{n-1}}\left ({-n{^{2}}a}\right )\\x{{}_{1}}x{{}_{2}}\cdot \cdot \cdot x{{}_{n}}={\left({-1}\right)^{n}}a\end{cases}$ ，
14. 因为 $x{{}_{1}}+x{{}_{2}}+\cdot \cdot \cdot +x{{}_{n}}=1$ ，且 $x{{}_{1}},x{{}_{2}},\cdot \cdot \cdot ,x{{}_{n}}$ 均为正数，
15. 则 $\frac {1}{x{{}_{1}}}+\frac {1}{x{{}_{2}}}+\cdot \cdot \cdot +\frac {1}{x{{}_{n}}}=\left ({x{{}_{1}}+x{{}_{2}}+\cdot \cdot \cdot +x{{}_{n}}}\right )\left ({\frac {1}{x{{}_{1}}}+\frac {1}{x{{}_{2}}}+\cdot \cdot \cdot +\frac {1}{x{{}_{n}}}}\right )$
16. $\geqslant {\left({\sqrt {x{{}_{1}}}\cdot \frac {1}{\sqrt {x{{}_{1}}}}+\sqrt {x{{}_{2}}}\cdot \frac {1}{\sqrt {x{{}_{2}}}}+\cdot \cdot \cdot +\sqrt {x{{}_{n}}}\cdot \frac {1}{\sqrt {x{{}_{n}}}}}\right)^{2}}=n{^{2}}$ ，
17. 当且仅当 $\frac {1}{x{{}_{1}}}=\frac {1}{x{{}_{2}}}=\cdot \cdot \cdot =\frac {1}{x{{}_{n}}}=\frac {1}{n}$ 时，等号成立，
18. 又因为 $\frac {x{{}_{1}}x{{}_{2}}\cdot \cdot \cdot x{{}_{n-1}}+x{{}_{1}}\cdot \cdot \cdot x{{}_{n-2}}x{{}_{n}}+\cdot \cdot \cdot +x{{}_{2}}x{{}_{3}}\cdot \cdot \cdot x{{}_{n}}}{x{{}_{1}}x{{}_{2}}\cdot \cdot \cdot x{{}_{n}}}=\frac {1}{x{{}_{1}}}+\frac {1}{x{{}_{2}}}+\cdot \cdot \cdot +\frac {1}{x{{}_{n}}}=\frac {{\left({-1}\right)^{n-1}}\left ({-n{^{2}}a}\right )}{{\left({-1}\right)^{n}}a}=n{^{2}}$ ，
19. 即 $\frac {1}{x{{}_{1}}}+\frac {1}{x{{}_{2}}}+\cdot \cdot \cdot +\frac {1}{x{{}_{n}}}=n{^{2}}$ ，
20. 所以 $\frac {1}{x{{}_{1}}}=\frac {1}{x{{}_{2}}}=\cdot \cdot \cdot =\frac {1}{x{{}_{n}}}=\frac {1}{n}$ .

## 知识点

**中文**:
  - 复数新定义问题

**English**:
  - New Definition Problems in Complex Numbers

---
