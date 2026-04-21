# Mathematics - 题目 3699

**ID**: 188cf7292800415380580c987844ae02
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Fill-in-the-blank

## 题目
点 $M\left ({x{{}_{1}},m}\right )$ 在直线 $y=nx+n\left ({n\in {\mathbf{N}}{^{{\rm{*}}}}}\right )$ 上，点 $N\left ({x{{}_{2}},m}\right )$ 在抛物线 $y{^{2}}=4x$ 上，记 $M,N$ 两点间的最小距离为 $d{{}_{n}}\left ({M,N}\right )$ ，若 $\prod \limits_{i=1}^{n}\mathop{a{{}_{i}}}=a{{}_{1}}a{{}_{2}}a{{}_{3}}\cdots a{{}_{n}}$ ，则 $\prod \limits_{n=2}^{2025}\mathop{d{{}_{n}}}(M,N)=$.​​​​​​​‌

## 解答

1. 已知点 $M(x{{}_{1}},m)$ 在直线 $y=nx+n(n\in {\rm{N}}{^{{\rm{*}}}})$ 上，
2. 则将点 $M$ 代入直线方程可得 $m=nx{{}_{1}}+n$   ①.
3. 点 $N(x{{}_{2}},m)$ 在抛物线 $y{^{2}}=4x$ 上，则将点 $N$ 代入抛物线方程可得 $m{^{2}}=4x{{}_{2}}$   ②.
4. 因为 $M$ ， $N$ 两点纵坐标相同，所以 $|MN|=|x{{}_{2}}-x{{}_{1}}|$ .
5. 由①可得 $x{{}_{1}}=\frac {m-n}{n}$ ，由②可得 $x{{}_{2}}=\frac {m{^{2}}}{4}$ ，则 $|MN|=|\frac {m{^{2}}}{4}-\frac {m-n}{n}|=|\frac {m{^{2}}}{4}-\frac {m}{n}+1|$ .
6. 令 $t=\frac {m}{2}$ ，则 $|MN|=|t{^{2}}-\frac {2t}{n}+1|$ ，将其转化为顶点式：
7. $|MN|=|t{^{2}}-\frac {2t}{n}+1|=|t{^{2}}-\frac {2t}{n}+{\left({\frac {1}{n}}\right)^{2}}-{\left({\frac {1}{n}}\right)^{2}}+1|=|{\left({t-\frac {1}{n}}\right)^{2}}+1-\frac {1}{n{^{2}}}|$ ，
8. 因为 $(t-\frac {1}{n}){^{2}}\geqslant 0$ ，所以当 $t=\frac {1}{n}$ 时， $|MN|$ 取得最小值， $|MN|{{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=|1-\frac {1}{n{^{2}}}|$ .
9. 因为 $n\in \mathbf{N}{^{{\rm{*}}}}$ ，所以 $1-\frac {1}{n{^{2}}}>0$ ，则 $d{{}_{n}}(M,N)=|MN|{{}_{{\rm{m}}{\rm{i}}{\rm{n}}}}=1-\frac {1}{n{^{2}}}=\frac {n{^{2}}-1}{n{^{2}}}=\frac {(n-1)(n+1)}{n{^{2}}}$ .
10. $\prod \limits_{n=2}^{2025}\mathop{d{{}_{n}}}(M,N)=\frac {1\times 3}{2{^{2}}}\times \frac {2\times 4}{3{^{2}}}\times \frac {3\times 5}{4{^{2}}}\times \cdots \times \frac {2024\times 2026}{2025{^{2}}}$ ，
11. 可以发现上式中相邻两项的分子分母可以约分，约分后可得：
12. $\prod \limits_{n=2}^{2025}\mathop{d{{}_{n}}}(M,N)=\frac {1}{2}\times \frac {2026}{2025}=\frac {1013}{2025}$ .

## 知识点

**中文**:
  - 与抛物线有关的距离问题、轨迹问题

**English**:
  - Distance and Locus Problems

---
