# Mathematics - 题目 3496

**ID**: 5509442602224485ab708026d45d9dc0
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
已知集合 $S{{}_{n}}=\left \{X\left |{X=\left ({x{{}_{1}},\,x{{}_{2}},\,\cdots ,\,x{{}_{n}}}\right ),\,x{{}_{i}}\in \left \{0,\,1\right \},\,i=1,\,2,\,\cdots ,\,n}\right .​​​​​​​‌\right \}\left ({n\geqslant 3}\right )$ ， $T$ 是 $S{{}_{n}}$ 的非空子集．对于任意元素 $X=\left ({x{{}_{1}},x{{}_{2}},\cdots ,x{{}_{n}}}\right ),Y=\left ({y{{}_{1}},y{{}_{2}},\cdots ,y{{}_{n}}}\right )\in S{{}_{n}}$ ，定义 $X$ 与 $Y$ 之间的距离 $d=\left ({X,Y}\right )$  $=\sum \limits_{i=1}^{n}\mathop{\left |{x{{}_{i}}-y{{}_{i}}}\right |}$ ，记 $λ\left ({T}\right )={\rm{m}}{\rm{i}}{\rm{n}}\left \{d\left ({X,\,Y}\right )\left |{X,\,Y\in T,\,X\ne Y}\right .\right \}$ 为子集 $T$ 的特征值，其中 ${\rm \min }A$ 表示有限集 $A$ 中的最小数．（1）当 $n=3$ 时，直接写出集合 $T{{}_{1}}=\left \{(1,0,0),(0,1,0),(1,0,1)\right \}$ 和 $T{{}_{2}}=\{(1,1,1),(1,0,0),(0,1,0),(0,0,1)\}$ 的特征值；（2）令 $T=\left \{X|X=\left ({x{{}_{1}},x{{}_{2}},\cdots ,x{{}_{n}}}\right )\in S{{}_{n}}\right.$ ，且 $x{{}_{1}}+x{{}_{2}}+\cdots +x{{}_{n}}$ 为奇数 $\}$ ，分别求出集合 $T$ 中元素个数和 $T$ 的特征值，并说明理由．

## 解答

1. （1）对集合 $T{{}_{1}}$ ， $d\left ({\left ({1,0,0}\right ),\left ({0,1,0}\right )}\right )=\left |{1-0}\right |+\left |{0-1}\right |+\left |{0-0}\right |=2$ ，
2. $d\left ({\left ({1,0,0}\right ),\left ({1,0,1}\right )}\right )=\left |{1-1}\right |+\left |{0-0}\right |+\left |{0-1}\right |=1$ ， $d\left ({\left ({0,1,0}\right ),\left ({1,0,1}\right )}\right )=\left |{0-1}\right |+\left |{1-0}\right |+\left |{0-1}\right |=3$ ，
3. 故 $λ\left ({T{{}_{1}}}\right )=1$ ；
4. 对集合 $T{{}_{2}}$ ， $d\left ({\left ({1,1,1}\right ),\left ({1,0,0}\right )}\right )=\left |{1-1}\right |+\left |{1-0}\right |+\left |{1-0}\right |=2$ ，
5. $d\left ({\left ({1,1,1}\right ),\left ({0,1,0}\right )}\right )=\left |{1-0}\right |+\left |{1-1}\right |+\left |{1-0}\right |=2$ ， $d\left ({\left ({1,1,1}\right ),\left ({0,0,1}\right )}\right )=\left |{1-0}\right |+\left |{1-0}\right |+\left |{1-1}\right |=2$ ，
6. $d\left ({\left ({1,0,0}\right ),\left ({0,1,0}\right )}\right )=\left |{1-0}\right |+\left |{0-1}\right |+\left |{0-0}\right |=2$ ， $d\left ({\left ({1,0,0}\right ),\left ({0,0,1}\right )}\right )=\left |{1-0}\right |+\left |{0-0}\right |+\left |{0-1}\right |=2$ ，
7. $d\left ({\left ({0,1,0}\right ),\left ({0,0,1}\right )}\right )=\left |{0-0}\right |+\left |{1-0}\right |+\left |{0-1}\right |=2$ ，
8. 故 $λ\left ({T{{}_{2}}}\right )=2$ ；
9. （2）由于集合 $S{{}_{n}}$ 中元素的每个分量取值有两种可能，所以集合 $S{{}_{n}}$ 中共有 $2{^{n}}$ 个元素，
10. 对于任意 $X=\left ({x{{}_{1}},x{{}_{2}},\cdots ,x{{}_{n}}}\right )$ ，其分量和 $x{{}_{1}}+x{{}_{2}}+\cdots +x{{}_{n}}$ 可能是奇数也可能是偶数，
11. 由于每个分量都独立取值，所以分量和为奇数和偶数的个数相同，
12. 因为 $T$ 中元素的分量和为奇数，所以 $T$ 中元素的个数为 $\frac {2{^{n}}}{2}=2{^{n-1}}$ ；
13. 因为 $T$ 中元素的分量和为奇数，所以其两元素间的距离必为偶数，
14. 因为 $X\ne Y$ ，所以 $d\left ({X,Y}\right )\ne 0$ ，
15. 取 $X=\left ({1,0,0,\cdots ,0}\right )$ （分量和为1）， $Y=\left ({0,1,0,0,\cdots ,0}\right )$ （分量和为1），
16. 此时 $d\left ({X,Y}\right )=2$ ，所以 $λ\left ({T}\right )=2$ ；

## 知识点

**中文**:
  - 集合的新定义问题

**English**:
  - New Definition Problems in Sets

---
