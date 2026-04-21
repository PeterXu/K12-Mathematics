# Mathematics - 题目 3574

**ID**: 427e8dd9617441a8abef6116e67acb04
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
给定正整数m，数列 $A:a{{}_{1}},a{{}_{2}},\mathrm{⋯},a{{}_{m}},a{{}_{i}}\in {\mathbf{R}},i=1,2,\mathrm{⋯},m$ ，且 $a{{}_{1}}+a{{}_{2}}+\cdots +a{{}_{m}}=0$ .​​​​​​​‌对数列A进行T操作，得到数列 $T(A):\left |{a{{}_{1}}-2a{{}_{2}}}\right |,\left |{a{{}_{2}}-2a{{}_{3}}}\right |,\mathrm{⋯}\left |{a{{}_{m-1}}-2a{{}_{m}}}\right |,\left |{a{{}_{m}}-2a{{}_{1}}}\right |$ .（1）若 $m=4$ ， $a{{}_{1}}=1$ ， $a{{}_{2}}=2$ ， $a{{}_{3}}=3$ ，求数列 $T(A)$ ；（2）若m为偶数， $a{{}_{i}}\in \left [-\frac {m}{2},\frac {m}{2}\right ]$ ，且 $a{{}_{i}}\in {\mathbf{Z}},\quad i=1,2,\mathrm{⋯},m$ ，求数列 $T(A)$ 各项和的最大值；（3）若m为奇数，探索“数列 $T(A)$ 为常数列”的充要条件，并给出证明.

## 解答

1. （1）由题意 $m=4$ 时， $a{{}_{1}}=1$ ， $a{{}_{2}}=2$ ， $a{{}_{3}}=3$ ，由 $a{{}_{1}}+a{{}_{2}}+a{{}_{3}}+a{{}_{4}}=0$ ，知 $a{{}_{4}}=-6$ ，所以 $\left |{a{{}_{1}}-2a{{}_{2}}}\right |=3$ ， $\left |{a{{}_{2}}-2a{{}_{3}}}\right |=4$ ， $\left |{a{{}_{3}}-2a{{}_{4}}}\right |=15$ ， $\left |{a{{}_{4}}-2a{{}_{1}}}\right |=8$ ，
2. 故 $T(A):3,4,15,8$ .
3. （2）记数列 $T(A)$ 的所有项和为S，
4. 因为 $a{{}_{i}}\in \left [-\frac {m}{2},\frac {m}{2}\right ]$ ，且 $a{{}_{i}}\in {\mathbf{Z}},i=1,2,\mathrm{⋯},m$ ，所以 $a{{}_{i}}-2a{{}_{i+1}}\in \left [-\frac {3m}{2},\frac {3m}{2}\right ]$ ，
5. 则 $\left |{a{{}_{i}}-2a{{}_{i+1}}}\right |\leqslant \frac {3m}{2}$ ，故 $S=\sum \limits_{i=1}^{m}\mathop{\left |{a{{}_{i}}-2a{{}_{i+1}}}\right |}\leqslant m\cdot \frac {3m}{2}=\frac {3m{^{2}}}{2}$ .
6. 当 $a{{}_{2j}}=\frac {m}{2}$ ， $a{{}_{2j-1}}=-\frac {m}{2}\left ({j=1,2,\mathrm{⋯},\frac {m}{2}}\right )$ 或 $a{{}_{2j}}=-\frac {m}{2}$ ， $a{{}_{2j-1}}=\frac {m}{2}\left ({j=1,2,\mathrm{⋯},\frac {m}{2}}\right )$ 时取到等号，
7. 所以当 $a{{}_{2j}}=\frac {m}{2}$ ， $a{{}_{2j-1}}=-\frac {m}{2}\left ({j=1,2,\mathrm{⋯},\frac {m}{2}}\right )$ 或 $a{{}_{2j}}=-\frac {m}{2}$ ， $a{{}_{2j-1}}=\frac {m}{2}\left ({j=1,2,\mathrm{⋯},\frac {m}{2}}\right )$ 时，S取到最大值，为 $\frac {3m{^{2}}}{2}$ .
8. （3）“数列 $T(A)$ 为常数列”的充要条件是 $a{{}_{i}}=0$ （ $i=1,2,\cdots ,m$ ）证明如下：
9. 先证充分性：
10. 当 $a{{}_{i}}=0$ （ $i=1,2,\cdots ,m$ ）时， $\left |{a{{}_{i}}-2a{{}_{i+1}}}\right |=0\left ({i=1,2,\cdots ,m,a{{}_{m+1}}=a{{}_{1}}}\right )$ ，所以 $T(A)$ 为常数列；
11. 再证必要性：
12. 当 $T(A)$ 为常数列时，记 $\left |{a{{}_{i}}-2a{{}_{i+1}}}\right |=λ\quad \left ({i=1,2,\cdots ,m,a{{}_{m+1}}=a{{}_{1}}}\right )$ ，
13. 设 $a{{}_{1}}-2a{{}_{2}},a{{}_{2}}-2a{{}_{3}},\cdots ,a{{}_{m-1}}-2a{{}_{m}},a{{}_{m}}-2a{{}_{1}}$ 中有x个 $-λ(x\in {\mathbf{N}})$ ，则必有 $(m-x)$ 个 $λ$ ，将数列 $T(A)$ 的所有项相加得： $-a{{}_{1}}-a{{}_{2}}-\cdots -a{{}_{m-1}}-a{{}_{m}}=(m-2x)λ$ ，由 $\sum \limits_{i=1}^{m}\mathop{a{{}_{i}}}=0$ ，且m为奇数，所以 $λ=0$ ，
14. 所以 $a{{}_{i}}-2a{{}_{i+1}}=0\left ({i=1,2,\cdots ,m,a{{}_{m+1}}=a{{}_{1}}}\right )$ ，由 $\sum \limits_{i=1}^{m}\mathop{a{{}_{i}}}=0$ 得： $a{{}_{m}}+2a{{}_{m}}+\cdots +2{^{m-1}}a{{}_{m}}=0$ ，所以 $a{{}_{m}}=0$ ，
15. 所以 $a{{}_{i}}=0(i=1,2,\cdots ,m)$ .

## 知识点

**中文**:
  - 数列新定义问题

**English**:
  - New Definition Problems

---
