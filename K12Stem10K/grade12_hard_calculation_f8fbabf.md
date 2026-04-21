# Mathematics - 题目 3784

**ID**: f8fbabfd95a94237a7008258193dedcf
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知常数 $p>1$ ，定义在 $\left ({0,+∞}\right )$ 的函数 $f\left ({x}\right )=x{^{p}}-x$ .​​​​​​​‌(1)求函数 $f\left ({x}\right )$ 的最小值：(2)若函数 $g\left ({x}\right )=ax-x{^{\frac {1}{p}}},x\in \left ({0,+∞}\right )$ 且 $g\left ({x}\right )$ 的最小值等于 $f\left ({x}\right )$ 的取小值.${\rm （i）}$ 求实数 $a$ 的值；${\rm （ii）}$ 证明：存在直线 $y=b$ ，其与两条曲线 $y=f\left ({x}\right )$ 和 $y=g\left ({x}\right )$ 共有三个不同的交点，并且从左到右的三个交点的横坐标成等差数列.

## 解答

1. （1）由题意可知： $f^{′}{\left ({x}\right )}=px{^{p-1}}-1$ ，
2. 由 $f^{′}{\left ({x}\right )}>0$ 得 $x>p{^{\frac {1}{1-p}}}$ ；由 $f^{′}{\left ({x}\right )}<0$ 得 $0<x<p{^{\frac {1}{1-p}}}$ ；
3. 可知 $f\left ({x}\right )$ 在区间 $\left ({0,p{^{\frac {1}{1-p}}}}\right )$ 内单调递减，在区间 $\left ({p{^{\frac {1}{1-p}}},+∞}\right )$ 内单调递增；
4. 所以函数 $f\left ({x}\right )$ 的最小值为 $f\left ({p{^{\frac {1}{1-p}}}}\right )=p{^{\frac {p}{1-p}}}-p{^{\frac {1}{1-p}}}$ .
5. （2）（i）由题意可知： $g^{′}{\left ({x}\right )}=a-\frac {1}{p}x{^{\frac {1}{p}-1}}=a-\frac {1}{p}x{^{\frac {1-p}{p}}}$ ，
6. ①当 $a\leqslant 0$ 时， $g^{′}{\left ({x}\right )}<0,g\left ({x}\right )$ 在区间 $\left ({0,+∞}\right )$ 内单调递减， $g\left ({x}\right )$ 无最小值，不符；
7. ②当 $a>0$ 时，由 $g^{′}{\left ({x}\right )}>0$ 得 $x>(pa){^{\frac {p}{1-p}}}$ ；由 $g^{′}{\left ({x}\right )}<0$ 得 $0<x<(pa){^{\frac {p}{1-p}}}$ ；
8. 可知 $g\left ({x}\right )$ 在区间 $\left ({0,(pa){^{\frac {p}{1-p}}}}\right )$ 内单调递减，在区间 $\left ({(pa){^{\frac {p}{1-p}}},+∞}\right )$ 内单调递增；
9. 故
10. 因为 $f\left ({x}\right )$ 和 $g\left ({x}\right )$ 有相同的最小值，则 $\left ({p{^{\frac {p}{1-p}}}-p{^{\frac {1}{1-p}}}}\right )\cdot a{^{\frac {1}{1-p}}}=p{^{\frac {p}{1-p}}}-p{^{\frac {1}{1-p}}}$ ，
11. 即 $\left ({p{^{\frac {p}{1-p}}}-p{^{\frac {1}{1-p}}}}\right )\cdot \left ({a{^{\frac {1}{1-p}}}-1}\right )=0$ ，所以 $a=1$ ；
12. ${\rm （ii）}$ 证明：因为 $f\left ({x}\right )$ 在 $\left ({0,p{^{\frac {1}{1-p}}}}\right )$ 内单调递减，在 $\left ({p{^{\frac {1}{1-p}}},+∞}\right )$ 内单调递增；
13. $g\left ({x}\right )$ 在 $\left ({0,p{^{\frac {p}{1-p}}}}\right )$ 内单调递减，在 $\left ({p{^{\frac {p}{1-p}}},+∞}\right )$ 内单调递增；且 $f\left ({x}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=g\left ({x}\right ){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=p{^{\frac {p}{1-p}}}-p{^{\frac {1}{1-p}}}<0$ .
14. ①当 $b<p{^{\frac {p}{1-p}}}-p{^{\frac {1}{1-p}}}$ 时， $y=b$ 与 $y=f\left ({x}\right ),y=g\left ({x}\right )$ 均无交点，不符；
15. ②当 $b=p{^{\frac {p}{1-p}}}-p{^{\frac {1}{1-p}}}$ 时， $y=b$ 与 $y=f\left ({x}\right ),y=g\left ({x}\right )$ 均只有1个点，共2个交点，不符；
16. ③当 $b\geqslant 0$ 时， $f\left ({x}\right )$ 在区间 $\left ({0,p{^{\frac {1}{1-p}}}}\right )$ 递减，所以 $x\in \left ({0,p{^{\frac {1}{1-p}}}}\right )$ 时， $f\left ({x}\right )<f\left ({0}\right )=0$ ，
17. 所以 $y=b$ 与 $y=f\left ({x}\right )$ 最多1个交点；同理 $y=b$ 与 $y=g\left ({x}\right )$ 最多1个交点；
18. 故 $y=b$ 与 $y=f\left ({x}\right ),y=g\left ({x}\right )$ 一共最多2个交点，不符；
19. ④当 $p{^{\frac {p}{1-p}}}-p{^{\frac {1}{1-p}}}<b<0$ 时， $y=b$ 与 $y=f\left ({x}\right ),y=g\left ({x}\right )$ 各有2个交点，
20. 设其横坐标分别为 $x{{}_{1}},x{{}_{2}},x{{}_{3}},x{{}_{4}}$ 且 $f\left ({x{{}_{1}}}\right )=f\left ({x{{}_{2}}}\right )=g\left ({x{{}_{3}}}\right )=g\left ({x{{}_{4}}}\right )=b$ ，
21. 因为 $y=b$ 与 $y=f\left ({x}\right ),y=g\left ({x}\right )$ 共有3个交点，
22. 所以 $x{{}_{1}},x{{}_{2}},x{{}_{3}},x{{}_{4}}$ 中必存在两个相等，不妨设 $x{{}_{2}}=x{{}_{3}}=x{{}_{0}}$ ，
23. 则 $f\left ({x{{}_{0}}}\right )=g\left ({x{{}_{0}}}\right )$ 即 $f\left ({x{{}_{0}}}\right )-g\left ({x{{}_{0}}}\right )=0$ ，
24. 所以 $\left ({x{{}_{0}}}\right ){^{\frac {1}{p}}}+{\left({x{{}_{0}}}\right)^{p}}-2x{{}_{0}}=0{^{即}}\left ({x{{}_{0}}}\right ){^{\frac {1}{p}}}+{\left({x{{}_{0}}}\right)^{p}}=2x{{}_{0}}$
25. 下面证明存在 $x{{}_{0}}\in \left ({p{^{\frac {p}{1-p}}},p{^{\frac {1}{1-p}}}}\right )$ 使得 $f\left ({x{{}_{0}}}\right )=g\left ({x{{}_{0}}}\right )$ .
26. 设 $h\left ({x}\right )=f\left ({x}\right )-g\left ({x}\right )$ ，
27. 因为 $h\left ({p{^{\frac {p}{1-p}}}}\right )=f\left ({p{^{\frac {p}{1-p}}}}\right )-g\left ({p{^{\frac {p}{1-p}}}}\right )=f\left ({p{^{\frac {p}{1-p}}}}\right )-g(x){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}>0$
28. 且 $h\left ({p{^{\frac {1}{1-p}}}}\right )=f\left ({p{^{\frac {1}{1-p}}}}\right )-g\left ({p{^{\frac {1}{1-p}}}}\right )=f(x){{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}-g\left ({p{^{\frac {1}{1-p}}}}\right )<0$ ，
29. 所以 $h\left ({x}\right )=f\left ({x}\right )-g\left ({x}\right )$ 在区间 $\left ({p{^{\frac {p}{1-p}}},p{^{\frac {1}{1-p}}}}\right )$ 至少有1个零点 $x{{}_{0}}$ .
30. 结合 $y=b$ 与 $y=f\left ({x}\right ),y=g\left ({x}\right )$ 各有2个交点及它们的单调性知 $x{{}_{1}}<x{{}_{2}}=x{{}_{3}}<x{{}_{4}}$ ，
31. 所以存在 $b=f\left ({x{{}_{0}}}\right )$ ，使得直线 $y=b$ 与 $y=f\left ({x}\right ),y=g\left ({x}\right )$ 共有3个交点 $x{{}_{1}},x{{}_{0}},x{{}_{4}}$ .
32. 因为 $g\left ({x}\right )=x-(x){^{\frac {1}{p}}}=\left ({(x){^{\frac {1}{p}}}}\right ){^{p}}-(x){^{\frac {1}{p}}}=f\left ({(x){^{\frac {1}{p}}}}\right )$ ，
33. 所以 $g\left ({x{{}_{3}}}\right )=g\left ({x{{}_{4}}}\right )=f\left ({\left ({x{{}_{3}}}\right ){^{\frac {1}{p}}}}\right )=f\left ({\left ({x{{}_{4}}}\right ){^{\frac {1}{p}}}}\right )=b$ ，所以 $\left \{x{{}_{1}},x{{}_{2}}\right \}=\left \{\left ({x{{}_{3}}}\right ){^{\frac {1}{p}}},\left ({x{{}_{4}}}\right ){^{\frac {1}{p}}}\right \}$ ，
34. 所以 $\begin{cases}x{{}_{1}}=\left ({x{{}_{3}}}\right ){^{\frac {1}{p}}}\\x{{}_{2}}=\left ({x{{}_{4}}}\right ){^{\frac {1}{p}}}\end{cases}$ 即 $\begin{cases}x{{}_{1}}=\left ({x{{}_{0}}}\right ){^{\frac {1}{p}}}\\x{{}_{0}}=\left ({x{{}_{4}}}\right ){^{\frac {1}{p}}}\end{cases}$ ，所以 $x{{}_{1}}+x{{}_{4}}=\left ({x{{}_{0}}}\right ){^{\frac {1}{p}}}+{\left({x{{}_{0}}}\right)^{p}}=2x{{}_{0}}$ .
35. 所以存在直线 $y=b$ ，其与两条曲线 $y=f\left ({x}\right )$ 和 $y=g\left ({x}\right )$ 共有三个不同的交点，并且从左到右的三个交点的横坐标成等差数列.
36. 1．构造函数，这是解决此类题的关键点和难点，并求其定义域；
37. 2．求导数，得单调区间和极值点；
38. 3．数形结合，挖掘隐含条件，确定函数图象与x轴的交点情况进而求解．

## 知识点

**中文**:
  - 利用导数研究函数的图象
  - 导数几何意义的应用
  - 利用导数研究函数的最值

**English**:
  - Studying Function Graphs
  - Applications of Geometric Meaning of Derivatives
  - Global Extrema (Max/Min) using Derivatives

---
