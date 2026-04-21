# Mathematics - 题目 1449

**ID**: b5e3191e91ab4ba781d089f691bc295b
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
对于给定的正项数列 $\left \{a{{}_{n}}\right \}$ ，定义： $\prod \limits_{i=1}^{n}\mathop{a{{}_{i}}}=a{{}_{1}}\cdot a{{}_{2}}\cdot a{{}_{3}}\cdot \cdots \cdot a{{}_{n}}$ ，其中， $a{{}_{i}}$ 为数列 $\left \{a{{}_{n}}\right \}$ 中的第 $i$ 项（ $1\leqslant i\leqslant n,i,n\in {\mathbf{N}}{^{{\rm{*}}}}$ ）.​​​​​​​‌若存在非零常数 $T$ ，使得数列 $\left \{a{{}_{n}}\right \}$ 满足 $\prod \limits_{i=1}^{n}\mathop{a{{}_{i}^{2}}}=a{{}_{n+1}^{2}}+T$ ，则称数列 $\left \{a{{}_{n}}\right \}$ 为“ $T$ 数列”.(1)写出首项为2的“2数列”的前4项；(2)若数列 $\left \{a{{}_{n}}\right \}$ 是首项为1的“ $T$ 数列”，数列 $\left \{b{{}_{n}}\right \}$ 为等比数列，且 $\sum \limits_{i=1}^{n}\mathop{a{{}_{i}^{4}}}=\prod \limits_{i=1}^{n}\mathop{a{{}_{i}^{2}}}+{\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}b{{}_{n}}$ .求数列 $\left \{\frac {\left ({n-1}\right )b{{}_{n}}}{n\left ({n+1}\right )}\right \}$ 的前 $n$ 项和 $B{{}_{n}}$ ；(3)设数列 $\left \{a{{}_{n}}\right \}$ 为“ $T$ 数列”， $a{{}_{1}}>1$ ， $T<0$ ，记 $S{{}_{n}}$ 为 $\left \{a{{}_{n}}\right \}$ 的前 $n$ 项和， $T{{}_{n}}$ 为数列 $\left \{\frac {1}{a{{}_{n}}}\right \}$ 的前 $n$ 项和；证明： $a{{}_{n+1}^{2}}+T<{\rm{e}}{^{S{{}_{n}}-T{{}_{n}}}}$ （ ${\rm{e}}$ 为自然对数的底数）.

## 解答

1. （1）由 $a{{}_{1}}=2$ ， $a{{}_{n+1}^{2}}=\prod \limits_{i=1}^{n}\mathop{a{{}_{i}^{2}}}-2$ ，
2. 得 $a{{}_{2}^{2}}=2{^{2}}-2=2$ ，则 $a{{}_{2}}=\sqrt {2}$ ，
3. $a{{}_{3}^{2}}=2{^{2}}\times 2-2=6$ ，则 $a{{}_{3}}=\sqrt {6}$ ，
4. $a{{}_{4}^{2}}=2{^{2}}\times 2\times 6-2=46$ ，则 $a{{}_{4}}=\sqrt {46}$ .
5. （2）设等比数列 $\left \{b{{}_{n}}\right \}$ 的公比为 $q$ ， $q>0$ ，
6. 由 $\sum \limits_{i=1}^{n}\mathop{a{{}_{i}^{4}}}=\prod \limits_{i=1}^{n}\mathop{a{{}_{i}^{2}}}+{\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}b{{}_{n}}$ ，得 $\sum \limits_{i=1}^{n+1}\mathop{a{{}_{i}^{4}}}=\prod \limits_{i=1}^{n+1}\mathop{a{{}_{i}^{2}}}+{\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}b{{}_{n+1}}$ ，
7. 两式相减得 $a{{}_{n+1}^{4}}=\left ({a{{}_{n+1}^{2}}-1}\right )\prod \limits_{i=1}^{n}\mathop{a{{}_{i}^{2}}}+{\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}q$ ，
8. 由 $\prod \limits_{i=1}^{n}\mathop{a{{}_{i}^{2}}}=a{{}_{n+1}^{2}}+T$ ，得 $a{{}_{n+1}^{4}}=\left ({a{{}_{n+1}^{2}}-1}\right )\cdot \left ({a{{}_{n+1}^{2}}+T}\right )+{\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}q$ ，
9. 整理得 $\left ({T-1}\right )a{{}_{n+1}^{2}}=T-{\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}q\left ({n\geqslant 1}\right )$ 恒成立.
10. 又因为 $\left \{a{{}_{n}}\right \}$ 是首项为1的“ $T$ 数列”，所以 $a{{}_{1}^{2}}=1$ ， $a{{}_{2}^{2}}=1-T$ ， $a{{}_{3}^{2}}=1{^{2}}\times \left ({1-T}\right )-T=1-2T$ ，
11. 则 $\begin{cases}\left ({T-1}\right )\left ({1-T}\right )=T-{\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}q\\\left ({T-1}\right )\left ({1-2T}\right )=T-{\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}q\end{cases}$ ，解得 $T=1$ ， $q=2$ .
12. 又因为 $a{{}_{1}^{2}}=1$ ， $a{{}_{1}^{4}}=a{{}_{1}^{2}}+{\rm{l}}{\rm{o}}{\rm{g}}{{}_{2}}b{{}_{1}}$ ，所以 $b{{}_{1}}=1$ ，
13. 所以 $b{{}_{n}}=b{{}_{1}}q{^{n-1}}=2{^{n-1}}$ .
14. 又因为 $\frac {\left ({n-1}\right )b{{}_{n}}}{n\left ({n+1}\right )}=\frac {\left ({n-1}\right )2{^{n-1}}}{n\left ({n+1}\right )}=\frac {2{^{n}}}{n+1}-\frac {2{^{n-1}}}{n}$ ，
15. 所以 $B{{}_{n}}=\frac {2{^{1}}}{2}-\frac {2{^{0}}}{1}+\frac {2{^{2}}}{3}-\frac {2{^{1}}}{2}+\frac {2{^{2}}}{4}-\frac {2{^{2}}}{3}+\cdots +\frac {2{^{n}}}{n+1}-\frac {2{^{n-1}}}{n}=\frac {2{^{n}}}{n+1}-\frac {2{^{0}}}{1}=\frac {2{^{n}}}{n+1}-1$ .
16. （3）令 $f\left ({x}\right )=2{\rm{l}}{\rm{n}}x-x+\frac {1}{x}\left ({x>0}\right )$ ，则 $f^{′}{\left ({x}\right )}=\frac {2}{x}-1-\frac {1}{x{^{2}}}=-\frac {{\left({x-1}\right)^{2}}}{x{^{2}}}<0$ ，
17. 所以 $f\left ({x}\right )$ 在区间 $\left ({0,+\infty }\right )$ 内单调递减，且 $f\left ({1}\right )=0$ .
18. 当 $x>1$ 时， $f\left ({x}\right )<0$ ，即 $2{\rm{l}}{\rm{n}}x<x-\frac {1}{x}$ ，
19. 又因为 $a{{}_{1}}>1$ ， $T<0$ ，所以 $a{{}_{2}^{2}}=a{{}_{1}^{2}}-T>1$ ，
20. 则 $a{{}_{2}}>1$ ，依次迭代可知 $a{{}_{3}}>1,\cdots ,a{{}_{n}}>1$ ，
21. 所以 $2{\rm{l}}{\rm{n}}a{{}_{n}}<a{{}_{n}}-\frac {1}{a{{}_{n}}}$ ，即 ${\rm{l}}{\rm{n}}a{{}_{n}^{2}}<a{{}_{n}}-\frac {1}{a{{}_{n}}}$ ，
22. 所以 ${\rm{l}}{\rm{n}}a{{}_{1}^{2}}<a{{}_{1}}-\frac {1}{a{{}_{1}}}$ ， ${\rm{l}}{\rm{n}}a{{}_{2}^{2}}<a{{}_{2}}-\frac {1}{a{{}_{2}}}$ ，…， ${\rm{l}}{\rm{n}}a{{}_{n-1}^{2}}<a{{}_{n-1}}-\frac {1}{a{{}_{n-1}}}$ ，
23. 将这 $n$ 个式子相加得： ${\rm{l}}{\rm{n}}a{{}_{1}^{2}}+{\rm{l}}{\rm{n}}a{{}_{2}^{2}}+\cdots +{\rm{l}}{\rm{n}}a{{}_{n}^{2}}<\left ({a{{}_{1}}+a{{}_{2}}+\cdots +a{{}_{n}}}\right )-\left ({\frac {1}{a{{}_{1}}}+\frac {1}{a{{}_{2}}}+\cdots +\frac {1}{a{{}_{n}}}}\right )$ ，
24. 所以 ${\rm{l}}{\rm{n}}\left ({\prod \limits_{i=1}^{n}\mathop{a{{}_{i}^{2}}}}\right )<S{{}_{n}}-T{{}_{n}}$ ，即 ${\rm{l}}{\rm{n}}\left ({a{{}_{n+1}^{2}}+T}\right )<S{{}_{n}}-T{{}_{n}}$ ，
25. 故 $a{{}_{n+1}^{2}}+T<{\rm{e}}{^{S{{}_{n}}-T{{}_{n}}}}$ .

## 知识点

**中文**:
  - 利用导数证明不等式
  - 等比数列的概念与通项公式
  - 数列与不等式的综合
  - 数列新定义问题

**English**:
  - Proving Inequalities using Derivatives
  - Concept and Formula
  - Sequences with Inequalities
  - New Definition Problems

---
