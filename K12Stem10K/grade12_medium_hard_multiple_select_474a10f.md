# Mathematics - 题目 2302

**ID**: 474a10f4d60f470db3c2d45864dbd0cf
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Multiple-select

## 题目
设 $S{{}_{n}}$ 为数列 $\left \{a{{}_{n}}\right \}$ 的前 $n$ 项和，若 $(n+1)S{{}_{n+1}}=(n+2)S{{}_{n}}+n(n+1)(n+2)$ ， $n\in {\mathbf{N}^{*}}$ ，若 $S{{}_{1}}=-50$ ，则下列结论正确的有（      ）​​​​​​​‌

## 解答

1. 由条件可知 $nS{{}_{n}}=(n+1)S{{}_{n-1}}+(n-1)n\cdot (n+1)\left ({n\geqslant 2,n\in {\rm{N}}{^{*}}}\right )$ 得 $\frac {S{{}_{n}}}{n+1}-\frac {S{{}_{n-1}}}{n}=n-1\left ({n\geqslant 2,n\in {\rm{N}}{^{*}}}\right )$ ，
2. $\therefore \frac {S{{}_{2}}}{3}-\frac {S{{}_{1}}}{2}=1$ ， $\frac {S{{}_{3}}}{4}-\frac {S{{}_{2}}}{3}=2$ ，…， $\frac {S{{}_{n}}}{n+1}-\frac {S{{}_{n-1}}}{n}=n-1$ ，
3. 累加得， $\frac {S{{}_{n}}}{n+1}-\frac {S{{}_{1}}}{2}=1+2+\cdots +(n-1)=\frac {n(n-1)}{2}$ ，
4. 故 $2S{{}_{n}}=n{^{3}}-51n-50\left ({n\geqslant 2,n\in {\rm{N}}{^{*}}}\right )$ ，当 $n=1$ 时， $S{{}_{1}}=-50$ 满足上式，
5. $\therefore $  $S{{}_{n}}=\frac {n{^{3}}-51n-50}{2}$ .
6. 当 $n\mathrm{\geqslant }2$ 时， $a{{}_{n}}=S{{}_{n}}-S{{}_{n-1}}=\frac {3n{^{2}}-3n-50}{2}$ .
7. 对于 ${\rm A，}a{{}_{4}}=-7<0$ ，故A正确；
8. 对于B，由于函数 $y=3x{^{2}}-2x-50$ ，其图象对称轴为 $x=\frac {1}{3}$ ，当 $x\geqslant \frac {1}{3}$ 时函数递增，
9. 故当 $n\mathrm{\geqslant }2$ 时， $a{{}_{n}}=\frac {3n{^{2}}-3n-50}{2}$ 单调递增，又 $a{{}_{1}}=S{{}_{1}}=-50$ ， $a{{}_{2}}=S{{}_{2}}-S{{}_{1}}=-22$ ，
10. $\therefore $  $\left \{a{{}_{n}}\right \}$ 单调递增，且 $a{{}_{1}}<a{{}_{2}}<a{{}_{3}}<a{{}_{4}}<0<a{{}_{5}}<a{{}_{6}}<\cdots \cdots $ ，故B错误；
11. 对于C，由B可知 $a{{}_{1}}<a{{}_{2}}<a{{}_{3}}<a{{}_{4}}<0<a{{}_{5}}<a{{}_{6}}<\cdots \cdots $ ，
12. 当 $n\leqslant 4$ 时， $\left \{S{{}_{n}}\right \}$ 单调递减，当 $n\geqslant 5$ 时， $\left \{S{{}_{n}}\right \}$ 单调递增，且 $S{{}_{4}}<S{{}_{5}}$ ，
13. $\therefore $ 当 $n=4$ 时， $S{{}_{n}}$ 取得最小值，故C正确；
14. 对于D，当 $n\geqslant 5$ 时， $\left \{S{{}_{n}}\right \}$ 单调递增，又 $S{{}_{7}}=\frac {7{^{3}}-51\times 7-50}{2}=-32<0$ ， $S{{}_{8}}=\frac {8{^{3}}-51\times 8-50}{2}=27>0$ ，
15. $\therefore $ 当 $S{{}_{n}}>0$ 时， $n$ 的最小值为8，故D正确；
16. 故选ACD.

## 知识点

**中文**:
  - 数列通项求法之累加法

**English**:
  - Accumulation Method (Telescoping Sums)

---
