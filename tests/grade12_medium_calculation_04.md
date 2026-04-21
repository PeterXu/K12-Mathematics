# Mathematics - 题目 15

**ID**: 14d7a784cf0f45e4a95cc7678e4d08f4
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ 的前项和为 $S{{}_{n}}$ ， $a{{}_{1}}=1$ ，且 $na{{}_{n+1}}=S{{}_{n}}+n{^{2}}+n$ .​​​​​​ 
（1）证明：数列 $\left \{\frac {S{{}_{n}}}{n}\right \}$ 为等差数列；  
（2）设 $b{{}_{n}}=\sum \limits_{i=1}^{n}\mathop{{\rm{C}}{{}_{n}^{i}}}a{{}_{i}}$ ，  
${\rm （i）}$ 求数列 $\left \{b{{}_{n}}\right \}$ 的前 $n$ 项和；
${\rm （ii）}$ 当 $n\geqslant 1$ 时，设集合 $M{{}_{n}}=\left \{b{{}_{i}}+b{{}_{j}}\left |{3n\cdot 2{^{n-1}}+2<b{{}_{i}}+b{{}_{j}}<n\cdot 2{^{n+2}}+2}\right .,1\leqslant i<j,i,j\in {\rm{N}}{^{*}}\right \}$ ，集合 $M{{}_{n}}$ 中所有元素的和记为 $K{{}_{n}}$ ，求数列 $\left \{K{{}_{n}}\right \}$ 的通项公式.
## 解答

1。

(1)由 $\frac {S{{}_{1}}}{1}=\frac {a{{}_{1}}}{1}=1$ ， $na{{}_{n+1}}=n(S{{}_{n+1}}-S{{}_{n}})=S{{}_{n}}+n{^{2}}+n$ ，则 $nS{{}_{n+1}}=(n+1)S{{}_{n}}+n(n+1)$ ，
2. 所以 $\frac {S{{}_{n+1}}}{n+1}-\frac {S{{}_{n}}}{n}=1$ ，故 $\left \{\frac {S{{}_{n}}}{n}\right \}$ 是首项、公差均为1的等差数列；
3。

(2)(i)由(1)得 $\frac {S{{}_{n}}}{n}=n\Rightarrow S{{}_{n}}=n{^{2}}$ ，
4. 当 $n\mathrm{\geqslant }2$ 时， $a{{}_{n}}=S{{}_{n}}-S{{}_{n-1}}=n{^{2}}-(n-1){^{2}}=2n-1$ ，
5. 显然 $a{{}_{1}}=1$ 满足，所以 $a{{}_{n}}=2n-1$ ，
6. 所以 $b{{}_{n}}={\rm{C}}{{}_{n}^{1}}\cdot 1+{\rm{C}}{{}_{n}^{2}}\cdot 3+\cdots +{\rm{C}}{{}_{n}^{n-1}}\cdot (2n-3)+{\rm{C}}{{}_{n}^{n}}\cdot (2n-1)$ ，
7. 又 ${\rm{C}}{{}_{n}^{i}}{\rm{=}}{\rm{C}}{{}_{n}^{n-i}}$ ， $i\in {\rm{N}},n\in {\rm{N}}{^{*}},i\leqslant n$ ，
8. 所以 $2b{{}_{n}}={\rm{C}}{{}_{n}^{1}}(2n-2)+{\rm{C}}{{}_{n}^{2}}(2n-2)+\cdots +{\rm{C}}{{}_{n}^{n-1}}(2n-2)+2(2n-1)$  $=(2n-2)({\rm{C}}{{}_{n}^{1}}+{\rm{C}}{{}_{n}^{2}}+\cdots +{\rm{C}}{{}_{n}^{n-1}})+2(2n-1)$  $=(2n-2)\cdot 2{^{n}}+2$ ，
9. 所以 $b{{}_{n}}=(n-1)\cdot 2{^{n}}+1$ ，
10. 若数列 $\left \{b{{}_{n}}\right \}$ 的前 $n$ 项和为 $T{{}_{n}}$ ，
11. 则 $T{{}_{n}}=0\cdot 2{^{1}}+1\cdot 2{^{2}}+\cdots +(n-1)\cdot 2{^{n}}+n$ ， $2T{{}_{n}}=0\cdot 2{^{2}}+1\cdot 2{^{3}}+\cdots +(n-1)\cdot 2{^{n+1}}+2n$ ，
12. 所以 $-T{{}_{n}}=2{^{2}}+2{^{3}}+\cdots +2{^{n}}-(n-1)\cdot 2{^{n+1}}-n=\frac {4(1-2{^{n-1}})}{1-2}-(n-1)\cdot 2{^{n+1}}-n$  $=(2-n)\cdot 2{^{n+1}}-4-n$ ，
13. 所以 $T{{}_{n}}=(n-2)\cdot 2{^{n+1}}+n+4$ ；
14. ${\rm (ii)}$ 当 $j\geqslant n+2$ 时， $b{{}_{i}}+b{{}_{j}}=\left ({i-1}\right )\cdot 2{^{i}}+\left ({j-1}\right )\cdot 2{^{j}}+2\geqslant $  $(n+1)\cdot 2{^{n+2}}+2>n\cdot 2{^{n+2}}+2$ ，与 $b{{}_{i}}+b{{}_{j}}<n\cdot 2{^{n+2}}+2$ 矛盾，所以 $j\leqslant n+1$ ，
15. 当 $j\leqslant n$ 时， $b{{}_{i}}+b{{}_{j}}\leqslant b{{}_{n-1}}+b{{}_{n}}=(n-2)\cdot 2{^{n-1}}+(n-1)\cdot 2{^{n}}+2<3n\cdot 2{^{n-1}}+2$ ，与 $b{{}_{i}}+b{{}_{j}}>3n\cdot 2{^{n-1}}+2$ 矛盾，所以 $j\geqslant n+1$ ，
16. 综上 $j=n+1$ ，此时 $3n\cdot 2{^{n-1}}+2<b{{}_{i}}+b{{}_{j}}=(i-1)\cdot 2{^{i}}+n\cdot 2{^{n+1}}+2<n\cdot 2{^{n+2}}+2$ ，
17. 所以 $-n\cdot 2{^{n-1}}<(i-1)\cdot 2{^{i}}<n\cdot 2{^{n+1}}$ ，可得 $1\leqslant i\leqslant n$ ，即 $i=1,2,\cdots ,n$ ，
18. 所以 $M{{}_{n}}=\{b{{}_{1}}+b{{}_{n+1}},b{{}_{2}}+b{{}_{n+1}},\cdots ,b{{}_{n}}+b{{}_{n+1}}\}$ ，则 $K{{}_{n}}=b{{}_{1}}+b{{}_{n+1}}+b{{}_{2}}+b{{}_{n+1}}+\cdots +b{{}_{n}}+b{{}_{n+1}}$
19. $=T{{}_{n}}+nb{{}_{n+1}}=(n-2)\cdot 2{^{n+1}}+n+4+n{^{2}}\cdot 2{^{n+1}}+n$  $=(n{^{2}}+n-2)2{^{n+1}}+2n+4$ .

## 知识点

**中文**:
  - 数列求和方法之错位相减法
  - 数列的递推公式
  - 等差数列的判定与证明

**English**:
  - Offset Subtraction Method
  - Recurrence Formula
  - Determination and Proof

---
