# Mathematics - 题目 1967

**ID**: c39f8046ea3f47d09ec90d209888ba4e
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Multiple-choice

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ 满足 $a{{}_{1}}=2,a{{}_{n+1}}-1={\ln}\left ({a{{}_{n}}+b}\right )-b\left ({n\in {\mathbf{N}}{^{∗}}}\right )$ ．若 $\left \{a{{}_{n}}\right \}$ 有无穷多个项，则（      ）​​​​​​​‌

## 解答

1. ∵ $a{{}_{n+1}}-1={\ln}\left ({a{{}_{n}}+b}\right )-b\left ({n\in {\mathbf{N}}{^{*}}}\right )$ ，即 $a{{}_{n+1}}+b={\ln}\left ({a{{}_{n}}+b}\right )+1$ ；
2. 令 $c{{}_{n}}=a{{}_{n}}+b$ ，则 $c{{}_{n+1}}={\ln}c{{}_{n}}+1$ ，易证：当 $x>0$ 时， ${\ln}x+1\leqslant x$ ，
3. 所以当 $c{{}_{n}}\geqslant 1$ 时， $1\leqslant {\ln}c{{}_{n}}+1\leqslant c{{}_{n}}$ ，所以 $1\leqslant c{{}_{n+1}}\leqslant c{{}_{n}}$ ，
4. 当 $b\geqslant -1$ 时， $c{{}_{1}}=a{{}_{1}}+b\geqslant 1$ ，易得 $1\leqslant \cdots \leqslant c{{}_{n}}\leqslant \cdots \leqslant c{{}_{2}}\leqslant c{{}_{1}}$ ，
5. 即 $1-b\leqslant \cdots \leqslant a{{}_{n}}\leqslant \cdots \leqslant a{{}_{2}}\leqslant a{{}_{1}}=2$ ，此时 $\left \{a{{}_{n}}\right \}$ 有无穷多个项，故 $b\geqslant -1$ 合题；
6. 当 $b<-1$ 时，则 $a{{}_{2}}={\ln}\left ({2+b}\right )-b+1<b+1-b+1=2$ ，
7. 设 $a{{}_{k}}<2$ ，则 $a{{}_{k}}+b<2-1=1$ ，
8. 则 $a{{}_{k+1}}-a{{}_{k}}={\ln}\left ({a{{}_{k}}+b}\right )-\left ({a{{}_{k}}+b}\right )+1<a{{}_{k}}+b-1-\left ({a{{}_{k}}+b}\right )+1=0$ ，
9. 所以 $\left \{a{{}_{n}}\right \}$ 为单调递减数列，故 $1-b>2>a{{}_{2}}>a{{}_{3}}>\cdots $ ，
10. 即 $1>2+b>a{{}_{2}}+b>a{{}_{3}}+b>\cdots $ ，
11. 令 $f(x)={\ln}x-x+1$ ， $f^{′}{\left ({x}\right )}=\frac {1}{x}-1$ ，当 $0<x<1$ 时， $f^{′}{\left ({x}\right )}>0$ ，
12. 即 $f\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上单调递增，因为 $a{{}_{k}}+b<2+b<1$ ，
13. 所以 $a{{}_{k+1}}-a{{}_{k}}={\ln}\left ({a{{}_{k}}+b}\right )-\left ({a{{}_{k}}+b}\right )+1<{\ln}\left ({2+b}\right )-(2+b)+1$ ，
14. 不妨令 ${\ln}\left ({2+b}\right )-(2+b)+1=d$ ，显然 $d<{\ln}1-1+1=0$ ，即 $d<0$ ，
15. 即 $a{{}_{k+1}}-a{{}_{k}}<d$ ，累加可得 $a{{}_{n}}-a{{}_{1}}<(n-1)d$ ，即 $a{{}_{n}}<2+\left ({n-1}\right )d$ ，
16. 故当 $n>1-\frac {b+2}{d}$ 时， $a{{}_{n}}+b<0$ ，此时 $a{{}_{n+1}}$ 不存在，不是无穷多个项，故 $b<-1$ 不合题；
17. 综上： $b\geqslant -1$ ．
18. 故选：B．

## 知识点

**中文**:
  - 数列的递推公式

**English**:
  - Recurrence Formula

---
