# Mathematics - 题目 2271

**ID**: 058b2479a5e14e5a8a7a9093a817a12b
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Multiple-select

## 题目
数列 $\left \{a{{}_{n}}\right \}$ 中， $a{{}_{1}}>0$ 且 $a{{}_{1}}\ne 1$ ， $a{{}_{n+1}}=a{{}_{n}^{2}}$ ， $n\in {\rm{N}}{^{{\rm{*}}}}$ ．（      ）​​​​​​​‌

## 解答

1. 由题意可知： $a{{}_{n}}>0$ ,
2. $\because a{{}_{n+1}}=a{{}_{n}^{2}}$ ，两边取对数得， ${\ln}a{{}_{n+1}}=2{\ln}a{{}_{n}}$ ，
3. 令 $b{{}_{n}}={\ln}a{{}_{n}}$ ，则 $b{{}_{n+1}}=2b{{}_{n}}$ ，且 $b{{}_{1}}={\ln}a{{}_{1}}$ ，
4. $\therefore \left \{b{{}_{n}}\right \}$ 是首项为 ${\ln}a{{}_{1}}$ ，公比为 $2$ 的等比数列， $\therefore b{{}_{n}}=\left ({{\ln}a{{}_{1}}}\right )\times 2{^{n-1}}$ ，
5. $\therefore b{{}_{n}}={\ln}a{{}_{n}}=\left ({{\ln}a{{}_{1}}}\right )\times 2{^{n-1}}={\ln}a{{}_{1}^{2{^{n-1}}}}$ ， $\therefore a{{}_{n}}=a{{}_{1}^{2{^{n-1}}}}$ ，
6. 对于A选项，若 $a{{}_{1}}=2$ ，则 $a{{}_{n}}=2{^{2{^{n-1}}}}$ ，
7. $\therefore a{{}_{1}}\cdot a{{}_{2}}\cdot a{{}_{3}}\cdot \cdots \cdot a{{}_{10}}=2{^{2{^{0}}}}\times 2{^{2{^{1}}}}\times 2{^{2{^{2}}}}\times \cdots \times 2{^{2{^{9}}}}=2{^{1+2+4+\cdots +2{^{9}}}}=2{^{\frac {1-2{^{10}}}{1-2}}}=2{^{1023}}$ ，故A正确；
8. 对于B选项，若 $a{{}_{1}}\mathrm{=}\frac {1}{2}$ ，则 $a{{}_{n}}=\left ({\frac {1}{2}}\right ){^{2{^{n-1}}}}$ ， $\therefore a{{}_{n+1}}=\left ({\frac {1}{2}}\right ){^{2{^{n}}}}$ ， $a{{}_{n+2}}=\left ({\frac {1}{2}}\right ){^{2{^{n+1}}}}$ ，
9. $\therefore \frac {a{{}_{n}}+a{{}_{n+2}}}{a{{}_{n+1}}}=\frac {\left ({\frac {1}{2}}\right ){^{2{^{n-1}}}}+\left ({\frac {1}{2}}\right ){^{2{^{n+1}}}}}{\left ({\frac {1}{2}}\right ){^{2{^{n}}}}}=2{^{2{^{n-1}}}}+2{^{-2{^{n}}}}$ ，
10. 令 $t=2{^{n-1}}$ ， $y=2{^{2{^{n-1}}}}+2{^{-2{^{n}}}}$ ， $\because n\in {\rm{N}}{^{{\rm{*}}}}$ ， $\therefore t\geqslant 1$ 且 $t\in {\rm{N}}{^{{\rm{*}}}}$ ，
11. 则 $y=2{^{t}}+2{^{-2t}}$ ， $\therefore y^{′}=2{^{t}}\cdot {\ln}2-2\times 2{^{-2t}}\cdot {\ln}2={\ln}2\left ({2{^{t}}-2{^{1-2t}}}\right )$ ，
12. 当 $t\geqslant 1$ 时， $2{^{t}}-2{^{1-2t}}>0$ ，即 $y^{′}>0$ ， $\therefore y=2{^{t}}+2{^{-2t}}$ 在 $\left [{1,+\infty }\right )$ 上单调递增，
13. $\therefore $ 当 $t=1$ 时， $y{{}_{{\rm \min }}}=2+\frac {1}{4}=\frac {9}{4}$ ， $\therefore \frac {a{{}_{n}}+a{{}_{n+2}}}{a{{}_{n+1}}}\geqslant \frac {9}{4}$ ，故B正确；
14. 对于C选项，若 $\left \{a{{}_{n}}\right \}$ 中存在连续3项依次成等差数列，设为 $a{{}_{k}},a{{}_{k+1}},a{{}_{k+2}}$ ，
15. $\therefore 2a{{}_{k+1}}=a{{}_{k}}+a{{}_{k+2}}$ ，代入递推关系得， $2a{{}_{k}^{2}}=a{{}_{k}}+a{{}_{k+1}^{2}}=a{{}_{k}}+a{{}_{k}^{4}}$ ，
16. $\therefore a{{}_{k}^{4}}-2a{{}_{k}^{2}}+a{{}_{k}}=0$ ，即 $a{{}_{k}}\left ({a{{}_{k}^{3}}-2a{{}_{k}}+1}\right )=0$ ，
17. 当 $a{{}_{k}}=0$ 时，不符合题意舍去，
18. $\therefore a{{}_{k}^{3}}-2a{{}_{k}}+1=0$ ，即 $\left ({a{{}_{k}}-1}\right )\left ({a{{}_{k}^{2}}+a{{}_{k}}-1}\right )=0$ ， $\therefore a{{}_{k}}=1$ 或 $a{{}_{k}}=\frac {-1\pm \sqrt {5}}{2}$ ，
19. $\because a{{}_{1}}>0$ 且 $a{{}_{1}}\ne 1$ ， $\therefore a{{}_{n}}>0$ 且 $a{{}_{n}}\ne 1$ ， $\therefore a{{}_{k}}=\frac {-1+\sqrt {5}}{2}$ ，
20. 若 $a{{}_{k}}=\frac {-1+\sqrt {5}}{2}<1$ ，则 $a{{}_{1}}<1$ ，与 $a{{}_{1}}>1$ 矛盾，故C错误；
21. 对于D选项， $\left ({a{{}_{1}}-a{{}_{2}}}\right )a{{}_{3}}+\left ({a{{}_{2}}-a{{}_{3}}}\right )a{{}_{4}}+\cdots +\left ({a{{}_{n}}-a{{}_{n+1}}}\right )a{{}_{n+2}}=\sum\limits_{n=1}^{n}\mathop{}\left ({a{{}_{n}}-a{{}_{n+1}}}\right )a{{}_{n+2}}=\sum\limits_{n=1}^{n}\mathop{}\left ({a{{}_{n}}-a{{}_{n}^{2}}}\right )a{{}_{n}^{4}}=\sum\limits_{n=1}^{n}\mathop{}a{{}_{n}^{5}}\left ({1-a{{}_{n}}}\right )$ ，
22. $\because a{{}_{1}}=\frac {1}{3}$ ， $\left \{a{{}_{n}}\right \}$ ，
23. $\because \frac {a{{}_{n+1}^{5}}\left ({1-a{{}_{n+1}}}\right )}{a{{}_{n}^{5}}\left ({1-a{{}_{n}}}\right )}=\frac {a{{}_{n}^{10}}\left ({1-a{{}_{n}^{2}}}\right )}{a{{}_{n}^{5}}\left ({1-a{{}_{n}}}\right )}=a{{}_{n}^{5}}\left ({1+a{{}_{n}}}\right )=\left ({\frac {1}{3}}\right ){^{5\times 2{^{n-1}}}}\left [1+\left ({\frac {1}{3}}\right ){^{2{^{n-1}}}}\right ]=\left ({\frac {1}{3}}\right ){^{5\times 2{^{n-1}}}}+\left ({\frac {1}{3}}\right ){^{6\times 2{^{n-1}}}}<1$ ，
24. $\therefore \left \{a{{}_{n}^{5}}\left ({1-a{{}_{n}}}\right )\right \}$ 是递减正项数列，逐渐趋近于 $0$ ，总和远小于 $a{{}_{1}^{5}}=\frac {1}{243}$ ，
25. $\therefore \left ({a{{}_{1}}-a{{}_{2}}}\right )a{{}_{3}}+\left ({a{{}_{2}}-a{{}_{3}}}\right )a{{}_{4}}+\cdots +\left ({a{{}_{n}}-a{{}_{n+1}}}\right )a{{}_{n+2}}<\frac {1}{243}$ ，故D正确.
26. 故选ABD.

## 知识点

**中文**:
  - 单调性
  - 数列的递推公式
  - 数列的通项

**English**:
  - Monotonicity
  - Recurrence Formula
  - General Term

---
