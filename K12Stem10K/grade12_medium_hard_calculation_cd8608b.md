# Mathematics - 题目 2510

**ID**: cd8608b2ca6c4a198de1f8dcf848ca46
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知项数为 $m\left ({m\in N{^{{\rm{*}}}}，m\geqslant 2}\right )$ 的数列 $\left \{a{{}_{n}}\right \}$ 满足如下条件：① $a{{}_{n}}\in N{^{{\rm{*}}}}\left ({n=1,2,\cdots ,m}\right )$ ；② $a{{}_{1}}<a{{}_{2}}<···<a{{}_{m}}.​​​​​​​‌$ 若数列 $\left \{b{{}_{n}}\right \}$ 满足 $b{{}_{n}}=\frac {\left ({a{{}_{1}}+a{{}_{2}}+···+a{{}_{m}}}\right )-a{{}_{n}}}{m-1}\in N{^{{\rm{*}}}}，$ 其中 $n=1,2,\cdots ,m$ 则称 $\left \{b{{}_{n}}\right \}$ 为 $\left \{a{{}_{n}}\right \}$ 的“伴随数列”.（I）数列 $1，3，5，7，9$ 是否存在“伴随数列”，若存在，写出其“伴随数列”；若不存在，请说明理由；（II）若 $\left \{b{{}_{n}}\right \}$ 为 $\left \{a{{}_{n}}\right \}$ 的“伴随数列”，证明： $b{{}_{1}}>b{{}_{2}}>···>b{{}_{m}}$ ；（III）已知数列 $\left \{a{{}_{n}}\right \}$ 存在“伴随数列” $\left \{b{{}_{n}}\right \}，$ 且 $a{{}_{1}}=1，a{{}_{m}}=2049，$ 求 $m$ 的最大值.

## 解答

1. （I）不存在.理由如下：因为 $b{{}_{4}}=\frac {1+3+5+7+9-7}{5-1}\in {\mathbf{N}^{*}}$ ，所以数列 $1,3,5,7,9$ 不存在“伴随数列”.
2. （II）因为 $b{{}_{n+1}}-b{{}_{n}}=\frac {a{{}_{n}}-a{{}_{n+1}}}{m-1},1\leqslant n\leqslant m-1,n\in {\mathbf{N}^{*}}$ ，
3. 又因为 $a{{}_{1}}<a{{}_{2}}<\cdots <a{{}_{m}}$ ，所以 $a{{}_{n}}-a{{}_{n+1}}<0$ ，所以 $b{{}_{n+1}}-b{{}_{n}}=\frac {a{{}_{n}}-a{{}_{n+1}}}{m-1}<0$ ，即 $b{{}_{n+1}}<b{{}_{n}}$ ，所以 $b{{}_{1}}>b{{}_{2}}>···>b{{}_{m}}$ 成立.
4. （III） $\forall 1\leqslant i<j\leqslant m$ ，都有 $b{{}_{i}}-b{{}_{j}}=\frac {a{{}_{j}}-a{{}_{j}}}{m-1}$ ，因为 $b{{}_{i}}\in {\mathbf{N}^{*}}$ ， $b{{}_{1}}>b{{}_{2}}>\cdots >b{{}_{m}}$ ，
5. 所以 $b{{}_{i}}-b{{}_{j}}\in {\mathbf{N}^{*}}$ ，所以 $b{{}_{1}}-b{{}_{m}}=\frac {a{{}_{m}}-a{{}_{1}}}{m-1}=\frac {2048}{m-1}\in {\mathbf{N}^{*}}$ .
6. 因为 $b{{}_{n-1}}-b{{}_{n}}=\frac {a{{}_{n}}-a{{}_{n-1}}}{m-1}\in {\mathbf{N}^{*}}$ ，
7. 所以 $a{{}_{n}}-a{{}_{n-1}}\geqslant m-1$ .
8. 而 $a{{}_{m}}-a{{}_{1}}=\left ({a{{}_{m}}-a{{}_{m-1}}}\right )+\left ({a{{}_{m-1}}-a{{}_{m-2}}}\right )+\cdots +\left ({a{{}_{2}}-a{{}_{1}}}\right )\geqslant \left ({m-1}\right )+\left ({m-1}\right )+\cdots +\left ({m-1}\right )$  $={\left({m-1}\right)^{2}}$ ，即 $2049-1\geqslant {\left({m-1}\right)^{2}}$ ，
9. 所以 ${\left({m-1}\right)^{2}}\leqslant 2048$ ，故 $m\leqslant 46$ .
10. 由于 $\frac {2048}{m-1}\in {\mathbf{N}^{*}}$ ，经验证可知 $m\leqslant 33$ .所以 $m$ 的最大值为 $33$ .

## 知识点

**中文**:
  - 数列新定义问题

**English**:
  - New Definition Problems

---
