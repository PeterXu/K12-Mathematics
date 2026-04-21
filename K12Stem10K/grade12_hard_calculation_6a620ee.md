# Mathematics - 题目 3296

**ID**: 6a620eee14d24cc1b1fbb14ed1618b7e
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
对于求解方程 $q:x{^{2}}-2y{^{2}}=1$ 的正整数解 $Q{{}_{n}}\left ({x{{}_{n}},y{{}_{n}}}\right )$ （ $x{{}_{n}}$ ， $y{{}_{n}}$ ， $n\in {\rm{N}}{^{*}}$ ）的问题，循环构造是一种常用且有效地构造方法．例如已知 $\begin{cases}x{{}_{1}}=3\\y{{}_{1}}=2\end{cases}$ 是方程 $q$ 的一组正整数解，则 $1=3{^{2}}-2\cdot 2{^{2}}=\left ({3+2\sqrt {2}}\right )\left ({3-2\sqrt {2}}\right )$ ，将 $1=\left ({3+2\sqrt {2}}\right )\left ({3-2\sqrt {2}}\right )$ 代入等式右边，得 $1=\left ({3+2\sqrt {2}}\right )\left ({3-2\sqrt {2}}\right )\cdot 1=\left ({3+2\sqrt {2}}\right )\left ({3-2\sqrt {2}}\right )\left ({3+2\sqrt {2}}\right )\left ({3-2\sqrt {2}}\right )$ ，变形得： $1={\left({3+2\sqrt {2}}\right)^{2}}{\left({3-2\sqrt {2}}\right)^{2}}=\left ({17+12\sqrt {2}}\right )\left ({17-12\sqrt {2}}\right )=17{^{2}}-2\cdot 12{^{2}}$ ，于是构造出方程 $q$ 的另一组解 $\begin{cases}x{{}_{2}}=17\\y{{}_{2}}=12\end{cases}$ ，重复上述过程，可以得到其他正整数解．进一步地，若取初始解时满足 $x{{}_{1}}$ 最小，则依次重复上述过程可以得到方程 $q$ 的所有正整数解．已知双曲线 $E:\frac {x{^{2}}}{a{^{2}}}-\frac {y{^{2}}}{b{^{2}}}=1$ （ $a>0$ ， $b>0$ ）的离心率为 $\frac {2\sqrt {3}}{3}$ ，实轴长为2．(1)求双曲线 $E$ 的标准方程；​​​​​​​‌(2)方程 $\frac {x{^{2}}}{a{^{2}}}-\frac {y{^{2}}}{b{^{2}}}=1$ 的所有正整数解为 $Q{{}_{n}}\left ({x{{}_{n}},y{{}_{n}}}\right )\left ({n\in {\rm{N}}{^{*}}}\right )$ ，且数列 $\left \{x{{}_{n}}\right \}$ 单调递增．①求证： $x{{}_{n+2}}+x{{}_{n}}$ 始终是4的整数倍；②将 $Q{{}_{n}}\left ({x{{}_{n}},y{{}_{n}}}\right )\left ({n\in {\rm{N}}{^{*}}}\right )$ 看作点，试问 $\mathrm{△}OQ{{}_{n}}Q{{}_{n+1}}$ 的面积是否为定值？若是，请求出该定值；若不是，请说明理由．

## 解答

1. （1）由题意知 $\begin{cases}\frac {c}{a}=\frac {2\sqrt {3}}{3}\\2a=2\end{cases}$ 解得 $\begin{cases}a=1\\c=\frac {2\sqrt {3}}{3}\end{cases}$ ，则 $b{^{2}}=c{^{2}}-a{^{2}}=\frac {1}{3}$ ，
2. 故双曲线E的标准方程为 $x{^{2}}-\frac {y{^{2}}}{\frac {1}{3}}=1$ ．
3. （2）①方法一：由 $x{^{2}}-\frac {y{^{2}}}{\frac {1}{3}}=1$ 得 $x{^{2}}-3y{^{2}}=1$ ，其中 $\begin{cases}x{{}_{1}}=2\\y{{}_{1}}=1\end{cases}$ 是方程的一组正整数解，则 $1=2{^{2}}-3\cdot 1{^{2}}=\left ({2+\sqrt {3}}\right )\left ({2-\sqrt {3}}\right )$ ，
4. 在循环构造中，对任意正整数 $k$ ，由 $x{{}_{k}}$ ， $y{{}_{k}}$ 是正整数，第k组解 $Q{{}_{k}}\left ({x{{}_{k}},y{{}_{k}}}\right )$ 中的 $x{{}_{k}}$ 为二项式 ${\left({2+\sqrt {3}}\right)^{k}}$ 的展开式中不含 $\sqrt {3}$ 的部分， $\sqrt {3}y{{}_{k}}$ 为二项式的展开式 ${\left({2+\sqrt {3}}\right)^{k}}$ 中含 $\sqrt {3}$ 的部分，
5. 注意到二项式 ${\left({2+\sqrt {3}}\right)^{k}}$ 的展开式中不含 $\sqrt {3}$ 的部分与二项式 ${\left({2-\sqrt {3}}\right)^{k}}$ 的展开式中不含 $\sqrt {3}$ 的部分相同，
6. 二项式 ${\left({2+\sqrt {3}}\right)^{k}}$ 的展开式中含 $\sqrt {3}$ 的部分与二项式 ${\left({2-\sqrt {3}}\right)^{k}}$ 的展开式中含 $\sqrt {3}$ 的部分互为相反数，于是由二项式定理有
7. $x{{}_{k}}+\sqrt {3}y{{}_{k}}={\left({2+\sqrt {3}}\right)^{k}}$ ， $x{{}_{k}}-\sqrt {3}y{{}_{k}}={\left({2-\sqrt {3}}\right)^{k}}$ ，从而 $x{{}_{k}}=\frac {1}{2}\left [{\left({2+\sqrt {3}}\right)^{k}}+{\left({2-\sqrt {3}}\right)^{k}}\right ]$ ，
8. 于是对任意的正整数 $n$ ，
9. $x{{}_{n+2}}+x{{}_{n}}=\frac {1}{2}\left [{\left({2+\sqrt {3}}\right)^{n+2}}+{\left({2-\sqrt {3}}\right)^{n+2}}\right ]+\frac {1}{2}\left [{\left({2+\sqrt {3}}\right)^{n}}+{\left({2-\sqrt {3}}\right)^{n}}\right ]$
10. $=\frac {1}{2}\left [{\left({2+\sqrt {3}}\right)^{n+2}}+{\left({2+\sqrt {3}}\right)^{n}}\right ]+\frac {1}{2}\left [{\left({2-\sqrt {3}}\right)^{n+2}}+{\left({2-\sqrt {3}}\right)^{n}}\right ]$
11. $=\frac {1}{2}\left [{\left({2+\sqrt {3}}\right)^{n+1}}\cdot 4\right ]+\frac {1}{2}\left [{\left({2-\sqrt {3}}\right)^{n+1}}\cdot 4\right ]=4x{{}_{n+1}}$ ，
12. 因为 $x{{}_{n+1}}$ 是正整数，所以 $x{{}_{n+2}}+x{{}_{n}}$ 是4的整数倍．
13. 方法二：
14. 在循环构造中，对任意正整数 $k$ ，由 $x{{}_{k}}$ ， $y{{}_{k}}$ 是正整数，第 $k$ 组解 $Q{{}_{k}}\left ({x{{}_{k}},y{{}_{k}}}\right )$ 中的 $x{{}_{k}}$ 为二项式 ${\left({2+\sqrt {3}}\right)^{k}}$ 的展开式中不含 $\sqrt {3}$ 的部分， $\sqrt {3}y{{}_{k}}$ 为二项式 ${\left({2+\sqrt {3}}\right)^{k}}$ 的展开式中含 $\sqrt {3}$ 的部分；
15. 第 $k+1$ 组解 $Q{{}_{k+1}}\left ({x{{}_{k+1}},y{{}_{k+1}}}\right )$ 中的 $x{{}_{k+1}}$ 为二项式 ${\left({2+\sqrt {3}}\right)^{k+1}}$ 的展开式中不含 $\sqrt {3}$ 的部分， $\sqrt {3}y{{}_{k+1}}$ 为二项式 ${\left({2+\sqrt {3}}\right)^{k+1}}$ 的展开式中含 $\sqrt {3}$ 的部分，
16. 故 $x{{}_{k}}+\sqrt {3}y{{}_{k}}={\left({2+\sqrt {3}}\right)^{k}}$ ， $x{{}_{k+1}}+\sqrt {3}y{{}_{k+1}}={\left({2+\sqrt {3}}\right)^{k+1}}$
17. 于是 $x{{}_{k+1}}+\sqrt {3}y{{}_{k+1}}={\left({2+\sqrt {3}}\right)^{k}}\left ({2+\sqrt {3}}\right )=\left ({x{{}_{k}}+\sqrt {3}y{{}_{k}}}\right )\left ({2+\sqrt {3}}\right )$ ，
18. $x{{}_{k+1}}+\sqrt {3}y{{}_{k+1}}={\left({2+\sqrt {3}}\right)^{k}}\left ({2+\sqrt {3}}\right )=\left ({2x{{}_{k}}+3y{{}_{k}}}\right )+\sqrt {3}\left ({x{{}_{k}}+2y{{}_{k}}}\right )$ ，
19. 即 $\begin{cases}x{{}_{k+1}}=2x{{}_{k}}+3y{{}_{k}}\\y{{}_{k+1}}=x{{}_{k}}+2y{{}_{k}}\end{cases}$ ，
20. 由 $x{{}_{k+1}}=2x{{}_{k}}+3y{{}_{k}}$ 得 $y{{}_{k}}=\frac {1}{3}\left ({x{{}_{k+1}}-2x{{}_{k}}}\right )$ ， $y{{}_{k+1}}=\frac {1}{3}\left ({x{{}_{k+2}}-2x{{}_{k+1}}}\right )$ ，
21. 代入 $y{{}_{k+1}}=x{{}_{k}}+2y{{}_{k}}$ 得 $\frac {1}{3}\left ({x{{}_{k+2}}-2x{{}_{k+1}}}\right )=x{{}_{k}}+\frac {2}{3}\left ({x{{}_{k+1}}-2x{{}_{k}}}\right )$ ，
22. 整理得 $x{{}_{k+2}}+x{{}_{k}}=4x{{}_{k+1}}$ ，即 $x{{}_{n+2}}+x{{}_{n}}=4x{{}_{n+1}}$ ．
23. 因为 $x{{}_{n+1}}$ 是正整数，所以 $x{{}_{n+2}}+x{{}_{n}}$ 是4的整数倍．
24. ② $\overrightarrow {{OQ{{}_{n}}}}=\left ({x{{}_{n}},y{{}_{n}}}\right )$ ， $\overrightarrow {{OQ{{}_{n+1}}}}=\left ({x{{}_{n+1}},y{{}_{n+1}}}\right )$ ，设 $\overrightarrow {{OQ{{}_{n}}}}$ ， $\overrightarrow {{OQ{{}_{n+1}}}}$ 的夹角为 $α$ ，
25. 则 $\mathrm{△}OQ{{}_{n}}Q{{}_{n+1}}$ 的面积
26. $S{{}_{\vartriangle OQ{{}_{n}}Q{{}_{n+1}}}}=\frac {1}{2}\left |{\overrightarrow {{OQ{{}_{n}}}}}\right |\cdot \left |{\overrightarrow {{OQ{{}_{n+1}}}}}\right |\sin α=\frac {1}{2}\sqrt {\left |{\overrightarrow {{OQ{{}_{n}}}}}\right |{^{2}}\cdot \left |{\overrightarrow {{OQ{{}_{n+1}}}}}\right |{^{2}}\sin {^{2}}α}$
27. $=\frac {1}{2}\sqrt {\left |{\overrightarrow {{OQ{{}_{n}}}}}\right |{^{2}}\cdot \left |{\overrightarrow {{OQ{{}_{n+1}}}}}\right |{^{2}}-\left |{\overrightarrow {{OQ{{}_{n}}}}}\right |{^{2}}\cdot \left |{\overrightarrow {{OQ{{}_{n+1}}}}}\right |{^{2}}{\cos}{^{2}}α}$
28. $=\frac {1}{2}\sqrt {\left |{\overrightarrow {{OQ{{}_{n}}}}}\right |{^{2}}\cdot \left |{\overrightarrow {{OQ{{}_{n+1}}}}}\right |{^{2}}-{\left({\overrightarrow {{OQ{{}_{n}}}}\cdot \overrightarrow {{OQ{{}_{n+1}}}}}\right)^{2}}}$
29. $=\frac {1}{2}\sqrt {\left ({x{{}_{n}^{2}}+y{{}_{n}^{2}}}\right )\left ({x{{}_{n+1}^{2}}+y{{}_{n+1}^{2}}}\right )-{\left({x{{}_{n}}x{{}_{n+1}}+y{{}_{n}}y{{}_{n+1}}}\right)^{2}}}$
30. $=\frac {1}{2}\left |{x{{}_{n}}y{{}_{n+1}}-x{{}_{n+1}}y{{}_{n}}}\right |$ ，
31. 由 $x{{}_{n+1}}=2x{{}_{n}}+3y{{}_{n}}$ 得 $y{{}_{n}}=\frac {1}{3}x{{}_{n+1}}-\frac {2}{3}x{{}_{n}}$ ， $y{{}_{n+1}}=\frac {1}{3}x{{}_{n+2}}-\frac {2}{3}x{{}_{n+1}}$ ，
32. 代入 $S{{}_{\vartriangle OQ{{}_{n}}Q{{}_{n+1}}}}=\frac {1}{2}\left |{x{{}_{n}}y{{}_{n+1}}-x{{}_{n+1}}y{{}_{n}}}\right |$ 得 $S{{}_{\vartriangle OQ{{}_{n}}Q{{}_{n+1}}}}=\frac {1}{2}\left |{x{{}_{n}}\left ({\frac {1}{3}x{{}_{n+2}}-\frac {2}{3}x{{}_{n+1}}}\right )-x{{}_{n+1}}\left ({\frac {1}{3}x{{}_{n+1}}-\frac {2}{3}x{{}_{n}}}\right )}\right |$ ， $S{{}_{\vartriangle OQ{{}_{n}}Q{{}_{n+1}}}}=\frac {1}{6}\left |{x{{}_{n}}x{{}_{n+2}}-x{{}_{n+1}^{2}}}\right |$ ，
33. 由 $x{{}_{n+2}}+x{{}_{n}}=4x{{}_{n+1}}$ 得 $\frac {x{{}_{n+2}}+x{{}_{n}}}{x{{}_{n+1}}}=4$ ，从而 $\frac {x{{}_{n+1}}+x{{}_{n-1}}}{x{{}_{n}}}=4$ ，
34. 故 $\frac {x{{}_{n+2}}+x{{}_{n}}}{x{{}_{n+1}}}=\frac {x{{}_{n+1}}+x{{}_{n-1}}}{x{{}_{n}}}$ ， $\therefore x{{}_{n}}x{{}_{n+2}}+x{{}_{n}^{2}}=x{{}_{n+1}^{2}}+x{{}_{n-1}}x{{}_{n+1}}$ ，
35. $\therefore x{{}_{n}}x{{}_{n+2}}-x{{}_{n+1}^{2}}=x{{}_{n-1}}x{{}_{n+1}}-x{{}_{n}^{2}}=\cdots \cdots =x{{}_{1}}x{{}_{3}}-x{{}_{2}^{2}}$ ．
36. $\because x{{}_{1}}=2$ ， $x{{}_{2}}=7$ ， $x{{}_{3}}=26$ ， $\therefore x{{}_{1}}x{{}_{3}}-x{{}_{2}^{2}}=3$ ，即 $x{{}_{n}}x{{}_{n+2}}-x{{}_{n+1}^{2}}=3$ ，
37. 代入 $S{{}_{\vartriangle OQ{{}_{n}}Q{{}_{n+1}}}}=\frac {1}{6}\left |{x{{}_{n}}x{{}_{n+2}}-x{{}_{n+1}^{2}}}\right |$ 得 $S{{}_{\mathrm{△}OQ{{}_{n}}Q{{}_{n+1}}}}=\frac {1}{2}$ ，
38. 于是 $\mathrm{△}OQ{{}_{n}}Q{{}_{n+1}}$ 的面积为定值 $\frac {1}{2}$ ．

## 知识点

**中文**:
  - 二项展开式中各项的系数
  - 双曲线标准方程及其应用
  - 弦长面积问题
  - 定点定值定直线问题

**English**:
  - Coefficients in Binomial Expansion
  - Standard Equation and Applications
  - Chord Length and Area Problems
  - Fixed Point, Value, Line Problems

---
