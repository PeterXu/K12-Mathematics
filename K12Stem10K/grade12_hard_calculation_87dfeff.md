# Mathematics - 题目 1924

**ID**: 87dfeff164d94d298cb3be0e44b8b3a1
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
定义：若对 $\forall n\in \mathbf{N}{^{*}}$ ， $n\mathrm{\geqslant }2$ ，都有 $\left |{b{{}_{n}}-b{{}_{n-1}}}\right |=j$ （j为常数，且 $j>0$ ），则称数列 $\left \{b{{}_{n}}\right \}$ 为“绝对等差数列”，常数j为数列 $\left \{b{{}_{n}}\right \}$ 的“绝对公差”．已知“绝对等差数列” $\left \{a{{}_{n}}\right \}$ 所有项的和为E．（1）若 $j=1$ ， $a{{}_{1}}=2$ ， $a{{}_{4}}=1$ ，请写出有序实数对 $\left ({a{{}_{2}},a{{}_{3}}}\right )$ 的所有取值；​​​​​​​‌（2）若数列 $\left \{a{{}_{n}}\right \}$ 共有259项，且 $j=3$ ， $a{{}_{1}}=211$ ， $a{{}_{259}}=985$ ，求数列 $\left \{a{{}_{n}}\right \}$ 的通项公式 $a{{}_{n}}$ ；（3）若j为奇数，数列 $\left \{a{{}_{n}}\right \}$ 共有2k（ $k\in \mathbf{N}{^{*}}$ ， $k\geqslant 2$ ）项，且 $a{{}_{1}}=0$ ， $E=0$ ．证明：k为偶数，并写出一个符合条件的数列 $\left \{a{{}_{n}}\right \}$ ．

## 解答

1. （1）由题， $\left |{a{{}_{2}}-a{{}_{1}}}\right |=\left |{a{{}_{2}}-2}\right |=1$ ，所以 $a{{}_{2}}=3$ 或 $a{{}_{2}}=1$ ，
2. 当 $a{{}_{2}}=3$ 时， $\left |{a{{}_{3}}-a{{}_{2}}}\right |=\left |{a{{}_{3}}-3}\right |=1$ ，得 $a{{}_{3}}=2$ 或 $a{{}_{3}}=4$ ，
3. 因为 $\left |{a{{}_{4}}-a{{}_{3}}}\right |=\left |{1-a{{}_{3}}}\right |=1$ ，所以 $a{{}_{3}}=2$ ，
4. 此时 $\left ({a{{}_{2}},a{{}_{3}}}\right )=\left ({3,2}\right )$ ；
5. 当 $a{{}_{2}}=1$ 时， $\left |{a{{}_{3}}-a{{}_{2}}}\right |=\left |{a{{}_{3}}-1}\right |=1$ ，得 $a{{}_{3}}=0$ 或 $a{{}_{3}}=2$ ，符合 $\left |{a{{}_{4}}-a{{}_{3}}}\right |=\left |{1-a{{}_{3}}}\right |=1$ ，
6. 此时 $\left ({a{{}_{2}},a{{}_{3}}}\right )=\left ({1,2}\right )$ 或 $\left ({a{{}_{2}},a{{}_{3}}}\right )=\left ({1,0}\right )$ ，
7. 所以 $\left ({a{{}_{2}},a{{}_{3}}}\right )$ 的取值情况为 $\left ({3,2}\right )$ ， $\left ({1,2}\right )$ ， $\left ({1,0}\right )$ ．
8. （2）由题， $\left |{a{{}_{k+1}}-a{{}_{k}}}\right |=3$ ， $k=1,2,\cdots ,258$ ，
9. 所以 $a{{}_{259}}-a{{}_{258}}\leqslant 3,a{{}_{258}}-a{{}_{257}}\leqslant 3,\cdots \cdots ,a{{}_{2}}-a{{}_{1}}\leqslant 3$ ，
10. 累加得 $a{{}_{259}}-a{{}_{1}}\leqslant 774$ ，即 $a{{}_{259}}\leqslant a{{}_{1}}+774=985$ ，
11. 因为 $a{{}_{259}}=985$ ，所以上述不等式中的等号同时成立，
12. 所以 $a{{}_{k+1}}-a{{}_{k}}=3$ ， $k=1,2,\cdots ,258$ ，
13. 故数列 $\left \{a{{}_{n}}\right \}$ 是以 $a{{}_{1}}=211$ 为首项，3为公差的等差数列，
14. 故 $a{{}_{n}}=211+\left ({n-1}\right )\times 3=3n+208$ （ $n\in \mathbf{N}{^{*}}$ ， $n\leqslant 259$ ）．
15. 所以数列 $\left \{a{{}_{n}}\right \}$ 的通项公式 $a{{}_{n}}=3n+208$ （ $n\in \mathbf{N}{^{*}}$ ， $n\leqslant 259$ ）．
16. （3）证明：令 $c{{}_{h}}=a{{}_{h+1}}-a{{}_{h}}$ ， $h=1,2,\cdots ,2k-1$ ，则 $c{{}_{h}}=\pm j$ ，
17. 因为 $a{{}_{2}}=a{{}_{1}}+c{{}_{1}},a{{}_{3}}=a{{}_{1}}+c{{}_{1}}+c{{}_{2}},\cdots \cdots ,a{{}_{2k}}=a{{}_{1}}+c{{}_{1}}+c{{}_{2}}+\cdots +c{{}_{2k-1}}$ ，
18. 所以 $E=a{{}_{1}}+a{{}_{2}}+\cdots +a{{}_{2k}}=2ka{{}_{1}}+\left ({2k-1}\right )c{{}_{1}}+\left ({2k-2}\right )c{{}_{2}}+\cdots +c{{}_{2k-1}}$ ，
19. 又 $a{{}_{1}}=0$ ，所以 $E=\left ({2k-1}\right )c{{}_{1}}+\left ({2k-2}\right )c{{}_{2}}+\cdots +c{{}_{2k-1}}$
20. $=\left ({2k-1}\right )+\left ({2k-2}\right )+\cdots +1-\left [\left ({2k-1}\right )\left ({1-c{{}_{1}}}\right )+\left ({2k-2}\right )\left ({1-c{{}_{2}}}\right )+\left ({2k-3}\right )\left ({1-c{{}_{3}}}\right )+\cdots +\left ({1-c{{}_{2k-1}}}\right )\right ]$
21. $=\frac {\left ({2k-1}\right )\times \left ({2k-1+1}\right )}{2}-\left [\left ({2k-1}\right )\left ({1-c{{}_{1}}}\right )+\left ({2k-2}\right )\left ({1-c{{}_{2}}}\right )+\left ({2k-3}\right )\left ({1-c{{}_{3}}}\right )+\cdots +\left ({1-c{{}_{2k-1}}}\right )\right ]$
22. $=\left ({2k-1}\right )k-\left [\left ({2k-1}\right )\left ({1-c{{}_{1}}}\right )+\left ({2k-2}\right )\left ({1-c{{}_{2}}}\right )+\left ({2k-3}\right )\left ({1-c{{}_{3}}}\right )+\cdots +\left ({1-c{{}_{2k-1}}}\right )\right ]$ ，
23. 因为 $c{{}_{h}}=\pm j$ ，且j为奇数，所以 $1-c{{}_{h}}\left ({h=1,2,\cdots ,2k-1}\right )$ 为偶数，
24. 所以 $\left ({2k-1}\right )\left ({1-c{{}_{1}}}\right )+\left ({2k-2}\right )\left ({1-c{{}_{2}}}\right )+\left ({2k-3}\right )\left ({1-c{{}_{3}}}\right )+\cdots +\left ({1-c{{}_{2k-1}}}\right )$ 为偶数，
25. 因为 $E=0$ ，所以 $\left ({2k-1}\right )\times k$ 为偶数，
26. 又因为 $2k-1$ 为奇数，所以k为偶数．得证．
27. 当 $k\left ({k\geqslant 2}\right )$ 为偶数时， $a{{}_{n}}=\begin{cases}0,n为奇数\\j\cdot \left ({-1}\right ){^{\frac {n}{2}}},n为偶数\end{cases}$ ．符合条件.

## 知识点

**中文**:
  - 数列新定义问题

**English**:
  - New Definition Problems

---
