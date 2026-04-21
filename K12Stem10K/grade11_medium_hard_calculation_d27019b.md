# Mathematics - 题目 1843

**ID**: d27019b058c64f12ab56e859bdf6acac
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设 $n$ 为正整数， $C{{}_{1}}$ ， $C{{}_{2}}$ ，… $C{{}_{n}}$ 为 $n$ 枚质地不均匀的硬币.​​​​​​​‌投掷硬币 $C{{}_{k}}\left ({k=1,2,\cdots ,n}\right )$ ，设正面朝上的概率为 $p{{}_{k}}$ ，反面朝上的概率为 $1-p{{}_{k}}$ .同时投出 $n$ 枚硬币，当正面朝上的硬币数为奇数时，即为游戏成功.（1）当 $n=3$ ， $p{{}_{k}}=\frac {1}{3}\left ({k=1,2,3}\right )$ 时，求游戏成功的概率；（2）当 $p{{}_{k}}=\frac {1}{3}\left ({k=1,2,\cdots ,n}\right )$ 时，设游戏成功的概率为 $Q{{}_{n}}\left ({n\in {\mathbf{N}}{^{*}}}\right )$ ，求当 $n\mathrm{\geqslant }2$ 时， $Q{{}_{n-1}}$ 与 $Q{{}_{n}}$ 的递推关系，并证明 $\left \{Q{{}_{n}}-\frac {1}{2}\right \}$ 是等比数列；（3）设 $n=3m\left ({m\in {\mathbf{N}}{^{*}}}\right )$ ，对于 $k=1,2,\cdots ,3m$ ， $p{{}_{k}}$ 的取值如下： $p{{}_{k}}=\begin{cases}\frac {1}{3m}\left ({k=1,2,\cdots ,m}\right )\\\frac {2}{3m}\left ({k=m+1,m+2,\cdots ,2m}\right )\\\frac {1}{m}\left ({k=2m+1,2m+2,\cdots ,3m}\right )\end{cases}$ ，设此时游戏成功的概率为 $Q{{}_{3m}}$ ，求证： $Q{{}_{3m}}\mathrm{\leqslant }\frac {1}{2}$ .

## 解答

1. （1）当 $n=3$ 时，要使游戏成功，需满足正面朝上的数量为1或3，
2. 此时，游戏成功的概率为： ${\rm{C}}{{}_{3}^{1}}\cdot \frac {1}{3}\cdot {\left({\frac {2}{3}}\right)^{2}}+{\left({\frac {1}{3}}\right)^{3}}=\frac {13}{27}$ ；
3. （2）设游戏成功的概率为 $Q{{}_{n}}$ ，当 $n=1$ 时， $Q{{}_{1}}=p{{}_{1}}=\frac {1}{3}$ ，接下来用 $Q{{}_{n-1}}$ 表示 $Q{{}_{n}}$ ，
4. 当 $n\mathrm{\geqslant }2$ 时，投掷 $n$ 枚硬币 $C{{}_{1}}$ ， $C{{}_{2}}$ ，…， $C{{}_{n}}$ 正面朝上的硬币为奇数有两种情况：
5. 第一：硬币 $C{{}_{1}}$ ， $C{{}_{2}}$ ，…， $C{{}_{n-1}}$ 中正面朝上的硬币数为奇数时， $C{{}_{n}}$ 反面朝上；
6. 第二：硬币 $C{{}_{1}}$ ， $C{{}_{2}}$ ，…， $C{{}_{n-1}}$ 中正面朝上的硬币数为偶数时， $C{{}_{n}}$ 正面朝上.
7. 此时， $Q{{}_{n}}=Q{{}_{n-1}}\cdot \left ({1-\frac {1}{3}}\right )+\left ({1-Q{{}_{n-1}}}\right )\cdot \frac {1}{3}$ ，所以 $Q{{}_{n}}=\frac {1}{3}Q{{}_{n-1}}+\frac {1}{3}$ （ $n\mathrm{\geqslant }2$ 且 $n\in {\mathbf{N}}{^{*}}$ ），
8. 则 $Q{{}_{n}}-\frac {1}{2}=\frac {1}{3}\left ({Q{{}_{n-1}}-\frac {1}{2}}\right )$ ，且 $Q{{}_{1}}=p{{}_{1}}=\frac {1}{3}$ ，则 $\left \{Q{{}_{n}}-\frac {1}{2}\right \}$ 是以 $Q{{}_{1}}-\frac {1}{2}=-\frac {1}{6}$ 为首项， $\frac {1}{3}$ 为公比的等比数列.
9. （3）方法一：当 $1\leqslant k\leqslant m$ 时，此时游戏成功的概率记为 $Q{{}_{k}}$ ， $Q{{}_{1}}=\frac {1}{3m}$ .
10. 由（2）知： $Q{{}_{k}}=Q{{}_{k-1}}\left ({1-\frac {1}{3m}}\right )+\left ({1-Q{{}_{k-1}}}\right )\frac {1}{3m}$ ，则 $Q{{}_{k}}-\frac {1}{2}=\left ({1-\frac {2}{3m}}\right )\left ({Q{{}_{k-1}}-\frac {1}{2}}\right )$ ，（ $k\geqslant 2$ ）
11. 所以 $Q{{}_{m}}-\frac {1}{2}={\left({1-\frac {2}{3m}}\right)^{m-1}}\left ({Q{{}_{1}}-\frac {1}{2}}\right )=-\frac {1}{2}\cdot {\left({1-\frac {2}{3m}}\right)^{m}}$ ，（ $m\in {\mathbf{N}}{^{*}}$ ）①
12. 当 $m+1\leqslant k\leqslant 2m$ 时， $Q{{}_{k}}=Q{{}_{k-1}}\left ({1-\frac {2}{3m}}\right )+\left ({1-Q{{}_{k-1}}}\right )\frac {2}{3m}$ ，
13. 则 $Q{{}_{2m}}-\frac {1}{2}={\left({1-\frac {4}{3m}}\right)^{m-1}}\left ({Q{{}_{m+1}}-\frac {1}{2}}\right )$ ，
14. 注意到： $Q{{}_{m+1}}=Q{{}_{m}}\left ({1-\frac {2}{3m}}\right )+\left ({1-Q{{}_{m}}}\right )\cdot \frac {2}{3m}$ ，则 $Q{{}_{m+1}}-\frac {1}{2}=\left ({1-\frac {4}{3m}}\right )\left ({Q{{}_{m}}-\frac {1}{2}}\right )$ ，
15. 故： $Q{{}_{2m}}-\frac {1}{2}={\left({1-\frac {4}{3m}}\right)^{m}}\left ({Q{{}_{m}}-\frac {1}{2}}\right )$ ②
16. 当 $2m+1\mathrm{\leqslant }k\mathrm{\leqslant }3m$ 时， $Q{{}_{k}}=Q{{}_{k-1}}\left ({1-\frac {1}{m}}\right )+\left ({1-Q{{}_{k-1}}}\right )\frac {1}{m}$ ，
17. 则： $Q{{}_{3m}}-\frac {1}{2}={\left({1-\frac {6}{3m}}\right)^{m}}\left ({Q{{}_{2m}}-\frac {1}{2}}\right )$ ③.
18. 结合①②③： $Q{{}_{3m}}-\frac {1}{2}={\left({1-\frac {2}{m}}\right)^{m}}\left ({Q{{}_{2m}}-\frac {1}{2}}\right )={\left({1-\frac {2}{m}}\right)^{m}}{\left({1-\frac {4}{3m}}\right)^{m}}\left ({Q{{}_{m}}-\frac {1}{2}}\right )=-\frac {1}{2}\cdot {\left({1-\frac {2}{3m}}\right)^{m}}{\left({1-\frac {2}{m}}\right)^{m}}{\left({1-\frac {4}{3m}}\right)^{m}}$
19. 由于 $m\in {\mathbf{N}}{^{*}}$ ，当 $m=1$ 时， ${\left({1-\frac {2}{3m}}\right)^{m}}>0$ ， ${\left({1-\frac {2}{m}}\right)^{m}}<0$ ， ${\left({1-\frac {4}{3m}}\right)^{m}}<0$ ，则 $Q{{}_{3m}}<\frac {1}{2}$ ；
20. 当 $m=2$ 时， ${\left({1-\frac {2}{m}}\right)^{m}}=0$ ，则 $Q{{}_{3m}}=\frac {1}{2}$ ；
21. 当 $m\geqslant 3$ 时， ${\left({1-\frac {2}{3m}}\right)^{m}}>0$ ， ${\left({1-\frac {2}{m}}\right)^{m}}>0$ ， ${\left({1-\frac {4}{3m}}\right)^{m}}>0$ ，则 $Q{{}_{3m}}<\frac {1}{2}$ .
22. 综上：对任意的 $m\in {\mathbf{N}}{^{*}}$ ， $Q{{}_{3m}}\mathrm{\leqslant }\frac {1}{2}$ 成立.
23. 方法二：对于 $m$ 个硬币出现奇数的概率为 $p\left ({m}\right )$ ，
24. ∴ $p\left ({m}\right )=p\left ({m-1}\right )\cdot \left ({1-p{{}_{k}}}\right )+\left [1-p\left ({m-1}\right )\right ]\cdot p{{}_{k}}$
25. ∴ $p\left ({m}\right )=\left ({1-2p{{}_{k}}}\right )\cdot p{{}_{m-1}}+p{{}_{k}}$
26. ∴ $p\left ({m}\right )-\frac {1}{2}=\left ({1-2p{{}_{k}}}\right )\cdot \left ({p\left ({m-1}\right )-\frac {1}{2}}\right )$
27. ∴ $\left \{p\left ({m}\right )-\frac {1}{2}\right \}$ 等比，∴ $p\left ({m}\right )-\frac {1}{2}=\left ({p{{}_{k}}-\frac {1}{2}}\right )\cdot {\left({1-2p{{}_{k}}}\right)^{m-1}}$
28. ∴前 $m$ 个硬币出现奇数的概率 $p{{}_{1}}=\left ({\frac {1}{3m}-\frac {1}{2}}\right )\cdot {\left({1-\frac {2}{3m}}\right)^{m-1}}+\frac {1}{2}=-\frac {1}{2}{\left({1-\frac {2}{3m}}\right)^{m}}+\frac {1}{2}$
29. 中间 $m$ 个： $p{{}_{2}}=-\frac {1}{2}{\left({1-\frac {4}{3m}}\right)^{m}}+\frac {1}{2}$
30. 后面 $m$ 个： $p{{}_{3}}=-\frac {1}{2}{\left({1-\frac {2}{m}}\right)^{m}}+\frac {1}{2}$
31. $Q{{}_{3m}}=p{{}_{1}}\cdot p{{}_{2}}\cdot p{{}_{3}}+p{{}_{1}}\cdot {\overline{p{{}_{2}}}}\cdot {\overline{p{{}_{3}}}}+{\overline{p{{}_{1}}}}\cdot p{{}_{2}}\cdot {\overline{p{{}_{3}}}}+{\overline{p{{}_{1}}}}\cdot {\overline{p{{}_{2}}}}\cdot p{{}_{3}}$
32. $=\left ({x{{}_{1}}+\frac {1}{2}}\right )\left ({x{{}_{2}}+\frac {1}{2}}\right )\left ({x{{}_{3}}+\frac {1}{2}}\right )+\left ({x{{}_{1}}+\frac {1}{2}}\right )\left ({\frac {1}{2}-x{{}_{2}}}\right )\left ({\frac {1}{2}-x{{}_{3}}}\right )+\left ({\frac {1}{2}-x{{}_{1}}}\right )\left ({x{{}_{2}}+\frac {1}{2}}\right )\left ({\frac {1}{2}-x{{}_{3}}}\right )$  $+\left ({\frac {1}{2}-x{{}_{1}}}\right )\left ({\frac {1}{2}-x{{}_{2}}}\right )\left ({x{{}_{3}}+\frac {1}{2}}\right )$  $=4x{{}_{1}}x{{}_{2}}x{{}_{3}}+\frac {1}{2}$
33. $=-\frac {1}{2}\left [\left ({1-\frac {2}{3m}}\right )\cdot \left ({1-\frac {4}{3m}}\right )\cdot \left ({1-\frac {2}{m}}\right )\right ]{^{m}}+\frac {1}{2}$
34. 当 $m=1$ 时， $Q{{}_{3}}<\frac {1}{2}$ .
35. 当 $m=2$ 时， $Q{{}_{6}}=\frac {1}{2}$ .
36. 当 $m\geqslant 3$ 时， $Q{{}_{3m}}<\frac {1}{2}$ .
37. ∴ $Q{{}_{3m}}\mathrm{\leqslant }\frac {1}{2}$ 成立.

## 知识点

**中文**:
  - 数列通项求法之构造法
  - 独立重复试验

**English**:
  - Construction Method
  - Independent Repeated Trials (Bernoulli Trials)

---
