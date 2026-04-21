# Mathematics - 题目 3237

**ID**: 76dd3cae33ff4b2da28e5671dbd0abae
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知数列 $a{{}_{n}}=3{^{n-1}}$ ，其前 $n$ 项的和为 $S{{}_{n}}$ ．设数列 $b{{}_{n}}=\begin{cases}2k,n=a{{}_{k}}\\b{{}_{n-1}}+4k,a{{}_{k}}<n<a{{}_{k+1}}\end{cases}$ ，其中 $k\in {\rm{N}}{^{+}}$ ．（1）求 $b{{}_{27}},b{{}_{85}}$ ；​​​​​​​‌（2）设 $T{{}_{n}}=\sum \limits_{i=1}^{2S{{}_{n}}}\mathop{b{{}_{i}}}$ ，求 $T{{}_{n}}$ 的值；（3）设 $c{{}_{n}}=\frac {n{^{2}}}{n+1}\left ({\sqrt {\frac {8n-1}{8T{{}_{n}}-1}}+1}\right )$ ，求使得 $\sum\limits_{i=1}^{n}\mathop{}\left [c{{}_{i}}\right ]\leqslant 2026$ 成立的最大正整数 $n$ 的值．（其中符号 $\left [x\right ]$ 表示不超过 $x$ 的最大整数）

## 解答

1. （1） $\because 27=3{^{3}}=a{{}_{4}}$ ， $\therefore b{{}_{27}}=2\times 4=8$ ，
2. $\because 3{^{4}}<85<3{^{5}}$ ，即 $a{{}_{5}}<85<a{{}_{6}}$ ，
3. $\therefore b{{}_{85}}=b{{}_{84}}+4\times 5$ ，
4. $\because 3{^{4}}<84<3{^{5}}$ ，即 $a{{}_{5}}<84<a{{}_{6}}$ ，
5. $\therefore b{{}_{85}}=b{{}_{84}}+4\times 5=b{{}_{83}}+4\times 5\times 2$ ，
6. 同理， $a{{}_{5}}<83<a{{}_{6}},a{{}_{5}}<82<a{{}_{6}}$ ，
7. 则 $b{{}_{85}}=b{{}_{83}}+4\times 5\times 2=b{{}_{82}}+4\times 5\times 3=b{{}_{81}}+4\times 5\times 4$ ，
8. 而 $81=3{^{4}}=a{{}_{5}}$ ，所以 $b{{}_{85}}=b{{}_{81}}+4\times 5\times 4=2\times 5+4\times 5\times 4=90$ .
9. （2）由 $S{{}_{n}}=\frac {1-3{^{n}}}{1-3}=\frac {3{^{n}}-1}{2}$ ，则 $T{{}_{n}}=\sum \limits_{i=1}^{3{^{n}}-1}\mathop{b{{}_{i}}}$ ，
10. 当 $3{^{k-1}}\leqslant i\leqslant 3{^{k}}-1\left ({k\in {\rm{N}}{^{+}}}\right )$ 时， $b{{}_{i}}-b{{}_{i-1}}=4k,b{{}_{3{^{k-1}}}}=2k$ ，
11. 可知数列 $\left \{b{{}_{i}}\right \}$ 是以 $2k$ 为首项，以 $4k$ 为公差，项数为 $2\cdot 3{^{k-1}}$ 的等差数列，
12. $\therefore \sum \limits_{i=3{^{k-1}}}^{3{^{k}}-1}\mathop{b{{}_{i}}}=\frac {2\cdot 3{^{k-1}}\left [2k+2k+4k\left ({2\cdot 3{^{k-1}}-1}\right )\right ]}{2}=8k\cdot 9{^{k-1}}$ ，
13. $\because 8k\cdot 9{^{k-1}}=\frac {1}{8}\left [\left ({8k-1}\right )9{^{k}}-\left ({8k-9}\right )9{^{k-1}}\right ]$ ，
14. $\therefore T{{}_{n}}=\sum \limits_{k=1}^{n}\mathop{\frac {1}{8}}\left [(8k-1)9{^{k}}-(8k-9)9{^{k-1}}\right ]=\frac {1}{8}\cdot \left ({7\cdot 9{^{1}}+1\cdot 9{^{0}}+15\cdot 9{^{2}}-7\cdot 9{^{1}}+23\cdot 9{^{3}}-15\cdot 9{^{2}}+\cdots +\left ({8n-1}\right )9{^{n}}-\left ({8n-9}\right )9{^{n-1}}}\right )$  $=\frac {1+(8n-1)9{^{n}}}{8}$ .
15. （3） $c{{}_{n}}=\frac {n{^{2}}}{n+1}\left ({\sqrt {\frac {8n-1}{8T{{}_{n}}-1}}+1}\right )=\frac {n{^{2}}}{n+1}\left ({\frac {1}{3{^{n}}}+1}\right )=\frac {n{^{2}}}{\left ({n+1}\right )3{^{n}}}+\frac {n{^{2}}}{n+1}=\frac {n{^{2}}}{\left ({n+1}\right )3{^{n}}}+\frac {1}{n+1}+n-1$  $=\frac {n{^{2}}+3{^{n}}}{\left ({n+1}\right )3{^{n}}}+n-1$ ，
16. 下证当 $n\geqslant 1$ 时， $0<\frac {n{^{2}}+3{^{n}}}{\left ({n+1}\right )3{^{n}}}<1$ ：
17. ①显然 $\frac {n{^{2}}+3{^{n}}}{\left ({n+1}\right )3{^{n}}}>0$ 恒成立
18. ② $n{^{2}}+3{^{n}}-\left ({n+1}\right )3{^{n}}=n\left ({n-3{^{n}}}\right )$ ，
19. $\because 3{^{n}}=(2+1){^{n}}={\rm{C}}{{}_{n}^{0}}\cdot 1{^{n}}\cdot 2{^{0}}+{\rm{C}}{{}_{n}^{1}}\cdot 1{^{n-1}}\cdot 2{^{1}}+{\rm{C}}{{}_{n}^{2}}\cdot 1{^{n-2}}\cdot 2{^{2}}+\ldots +{\rm{C}}{{}_{n}^{n}}\cdot 1{^{0}}\cdot 2{^{n}}\geqslant 1+2n>n$
20. $\therefore n{^{2}}+3{^{n}}-\left ({n+1}\right )3{^{n}}=n\left ({n-3{^{n}}}\right )<0$ ，
21. $\therefore 0<\frac {n{^{2}}+3{^{n}}}{\left ({n+1}\right )3{^{n}}}<1$ ，故 $\left [c{{}_{n}}\right ]=n-1$ ，
22. $\therefore \sum \limits_{i=1}^{n}\mathop{\left [c{{}_{i}}\right ]}=1+2+3+\ldots +(n-1)=\frac {1}{2}n(n-1)$ ，
23. $\therefore \frac {1}{2}n\left ({n-1}\right )\leqslant 2026$ ，即 $n\left ({n-1}\right )\leqslant 4052$ ，
24. 又 $64\times 63=4032$ ， $65\times 64=4160$ ，
25. 因此满足不等式的最大正整数 $n=64$ .

## 知识点

**中文**:
  - 数列与不等式的综合
  - 数列的递推公式
  - 等差数列求和公式基本应用

**English**:
  - Sequences with Inequalities
  - Recurrence Formula
  - Basic Applications of Sum Formula

---
