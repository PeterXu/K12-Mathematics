# Mathematics - 题目 3247

**ID**: 28d54c0f23884614b440f8ed3b183d7f
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
定义：若数列 $\{a{{}_{n}}\}$ 满足所有的项均由 $-1$ ，1构成且其中 $-1$ 有 $m$ 个，1有 $p$ 个 $(m+p\mathrm{\geqslant }3)$ ，则称 $\{a{{}_{n}}\}$ 为“ $(m,p)-$ 数列”.​​​​​​​‌（1） $a{{}_{i}}$ ， $a{{}_{j}}$ ， $a{{}_{k}}(i<j<k)$ 为“ $(3,4)-$ 数列” $\{a{{}_{n}}\}$ 中的任意三项，则使得 $a{{}_{i}}a{{}_{j}}a{{}_{k}}=1$ 的取法有多少种？（2） $a{{}_{i}}$ ， $a{{}_{j}}$ ， $a{{}_{k}}(i<j<k)$ 为“ $(m,p)-$ 数列” $\{a{{}_{n}}\}$ 中的任意三项，则存在多少正整数对 $(m,p)$ 使得 $1\leqslant m\leqslant p\leqslant 10$ ，且 $a{{}_{i}}a{{}_{j}}a{{}_{k}}=1$ 的概率为 $\frac {1}{2}$ .

## 解答

1. （1）三个数乘积为1有两种情况：“ $-1$ ， $-1$ ，1”，“1，1，1”，
2. 其中“ $-1$ ， $-1$ ，1”共有： ${\rm C}{_{3}^{2}}{\rm C}{_{4}^{1}}=12$ 种，“1，1，1”共有： ${\rm C}{_{4}^{3}}=4$ 种，
3. 利用分类计数原理得：
4. $a{{}_{i}}$ ， $a{{}_{j}}$ ， $a{{}_{k}}(i<j<k)$ 为“ $(3,4)-$ 数列” $\{a{{}_{n}}\}$ 中的任意三项，
5. 则使得 $a{{}_{i}}a{{}_{j}}a{{}_{k}}=1$ 的取法有： $12+4=16$ 种.
6. （2）与（1）基本同理，“ $-1$ ， $-1$ ，1”共有 ${\rm C}{_{m}^{2}}{\rm C}{_{p}^{1}}$ 种，“1，1，1”共有 ${\rm C}{_{p}^{3}}$ 种，
7. 而在“ $(m,p)-$ 数列”中任取三项共有 ${\rm C}{_{m+p}^{3}}$ 种，
8. 根据古典概型有： $\frac {{\rm C}{_{m}^{2}}{\rm C}{_{p}^{1}}+{\rm C}{_{p}^{3}}}{{\rm C}{_{m+p}^{3}}}=\frac {1}{2}$ ，
9. 再根据组合数的计算公式能得到：
10. $(p-m)(p{^{2}}-3p-2mp+m{^{2}}-3m-2)=0$ ，
11. ① $p=m$ 时，应满足 $\begin{cases}1\mathrm{\leqslant }m\mathrm{\leqslant }p\mathrm{\leqslant }100\\m+p\mathrm{\geqslant }3\\p=m\end{cases}$ ，
12. $\therefore (m$ , $p)=(k$ , $k)$ ， $k\in \{2$ ,3,4, $\ldots $ , $100\}$ ，共99个，
13. ② $p{^{2}}-3p-2mp+m{^{2}}-3m-2=0$ 时，
14. 应满足 $\begin{cases}1\mathrm{\leqslant }m\mathrm{\leqslant }p\mathrm{\leqslant }100\\m+p\mathrm{\geqslant }3\\p{^{2}}-3p-2mp+m{^{2}}-3m-2=0\end{cases}$ ，
15. 视 $m$ 为常数，可解得 $p=\frac {(2m+3)\pm \sqrt {24m+1}}{2}$ ，
16. $\because m\mathrm{\geqslant }1$ ， $\therefore $  $\sqrt {24m+1}\mathrm{\geqslant }5$ ，
17. 根据 $p\mathrm{\geqslant }m$ 可知， $p=\frac {(2m+3)+\sqrt {24m+1}}{2}$ ，（否则 $p\mathrm{\leqslant }m-1)$ ，
18. 下设 $k=\sqrt {24m+1}$ ，则由于 $p$ 为正整数知 $k$ 必为正整数，
19. $\because 1\mathrm{\leqslant }m\mathrm{\leqslant }100$ ， $\therefore 5\mathrm{\leqslant }k\mathrm{\leqslant }49$ ，
20. 化简上式关系式可以知道： $m=\frac {k{^{2}}-1}{24}=\frac {(k-1)(k+1)}{24}$ ，
21. $\therefore k-1$ ， $k+1$ 均为偶数， $\therefore $ 设 $k=2t+1$ ， $(t\in {\mathbf{N}^{*}})$ ，则 $2\mathrm{\leqslant }t\mathrm{\leqslant }24$ ，
22. $\therefore m=\frac {k{^{2}}-1}{24}=\frac {t(t+1)}{6}$ ，由于 $t$ ， $t+1$ 中必存在偶数，
23. $\therefore $ 只需 $t$ ， $t+1$ 中存在数为3的倍数即可，
24. $\therefore t=2$ ，3，5，6，8，9，11， $\ldots $ ，23，24，
25. $\therefore k=5$ ，11，13， $\ldots $ ，47，49.
26. 检验： $p=\frac {(2m+3)+\sqrt {24m+1}}{2}=\frac {(k-1)(k+1)}{24}\mathrm{\leqslant }\frac {48+50}{24}=100$ ，符合题意，
27. $\therefore $ 共有16个，
28. 综上所述：共有115个数对 $(m,p)$ 符合题意.

## 知识点

**中文**:
  - 数列新定义问题

**English**:
  - New Definition Problems

---
