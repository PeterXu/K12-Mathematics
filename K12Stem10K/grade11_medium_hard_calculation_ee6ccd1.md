# Mathematics - 题目 759

**ID**: ee6ccd16d909405aa285ef6ab6be5a3d
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
无穷数列 $a{{}_{1}}$ ， $a{{}_{2}}$ ，…， $a{{}_{n}}$ ，…的定义如下：如果n是偶数，就对n尽可能多次地除以2，直到得出一个奇数，这个奇数就是 $a{{}_{n}}$ ﹔如果n是奇数，就对 $3n+1$ 尽可能多次地除以2，直到得出一个奇数，这个奇数就是 $a{{}_{n}}$ ．(1)写出这个数列的前7项；​​​​​​​‌(2)如果 $a{{}_{n}}=m$ 且 $a{{}_{m}}=n$ ，求m，n的值；(3)记 $a{{}_{n}}=f\left ({n}\right )$ ， $n\in {\mathbf{N}}{^{{\rm{*}}}}$ ，求一个正整数n，满足 $n<f\left ({n}\right )<f\left ({f\left ({n}\right )}\right )<\cdots <\underbrace{f\left ({f\left ({\cdots f\left ({n}\right )\cdots }\right )}\right )}_{2024个f}$ ．

## 解答

1. （1）根据题意， $a{{}_{1}}=\left ({3\times 1+1}\right )\div 2\div 2=1$ ， $a{{}_{2}}=2\div 2=1$ ，
2. $a{{}_{3}}=\left ({3\times 3+1}\right )\div 2=5$ ， $a{{}_{4}}=4\div 2\div 2=1$ ， $a{{}_{5}}=\left ({3\times 5+1}\right )\div 2{^{4}}=1$ ，
3. $a{{}_{6}}=6\div 2=3$ ， $a{{}_{7}}=\left ({3\times 7+1}\right )\div 2=11$ ．
4. （2）由已知，m，n均为奇数，不妨设 $n\leqslant m$ ．
5. 当 $n=1$ 时，因为 $a{{}_{1}}=1$ ，所以 $m=1$ ，故 $m=n=1$ ；
6. 当 $n>1$ 时，因为 $\frac {3n+1}{4}<n\mathrm{\leqslant }m$ ，而n为奇数， $a{{}_{n}}=m$ ，所以 $m=\frac {3n+1}{2}$ ．
7. 又m为奇数， $a{{}_{m}}=n$ ，所以存在 $k\in {\mathbf{N}}{^{{\rm{*}}}}$ ，使得 $n=\frac {3m+1}{2{^{k}}}$ 为奇数．
8. 所以 $2{^{k}}n=3m+1=\frac {3\left ({3n+1}\right )}{2}+1=\frac {9n+5}{2}$ ．
9. 而 $4n<\frac {9n+5}{2}<6n$ ，所以 $4n<2{^{k}}n<6n$ ，即 $4<2{^{k}}<6$ ， $k\in {\mathbf{N}}{^{{\rm{*}}}}$ ，无解．
10. 所以 $m=n=1$ ．
11. （3）显然，n不能为偶数，否则 $f\left ({n}\right )\leqslant \frac {n}{2}<n$ ，不满足 $n<f\left ({n}\right )$ ．
12. 所以n为正奇数．又 $f\left ({1}\right )=a{{}_{1}}=1$ ，所以 $n\geqslant 3$ ．
13. 设 $n=4k+1$ 或 $n=4k-1$ ， $k\in {\mathbf{N}}{^{{\rm{*}}}}$ ．
14. 当 $n=4k+1$ 时， $f\left ({n}\right )=\frac {3\left ({4k+1}\right )+1}{4}=3k+1<4k+1=n$ ，不满足 $n<f\left ({n}\right )$ ；
15. 当 $n=4k-1$ 时， $f\left ({n}\right )=\frac {3\left ({4k-1}\right )+1}{2}=6k-1>4k-1=n$ ，即 $n<f\left ({n}\right )$ ．
16. 所以取 $n=2{^{2025}}k-1$ ， $k\in {\mathbf{N}}{^{{\rm{*}}}}$ 时，
17. $\frac {3\left ({2{^{2025}}k-1}\right )+1}{2}=3\times 2{^{2024}}k-1<f\left ({f\left ({n}\right )}\right )=\frac {3\left ({3\times 2{^{2024}}k-1}\right )+1}{2}=3{^{2}}\times 2{^{2024}}k-1$
18. $<\cdots <{\mathop {{\mathop {f\left ({f\left ({\cdots f\left ({n}\right )\cdots }\right )}\right )}\limits_{�}^{}}}\limits_{2023}^{}}=\frac {3\left ({3{^{2022}}\times 2{^{3}}k-1}\right )+1}{2}=3{^{2023}}\times 2{^{2}}k-1$
19. $<{\mathop {{\mathop {f\left ({f\left ({\cdots f\left ({n}\right )\cdots }\right )}\right )}\limits_{�}^{}}}\limits_{2024}^{}}=\frac {3\left ({3{^{2023}}\times 2{^{2}}k-1}\right )+1}{2}=3{^{2024}}\times 2k-1$ ，
20. 即 $n<f\left ({n}\right )<f\left ({f\left ({n}\right )}\right )<\cdots <{\mathop {{\mathop {f\left ({f\left ({\cdots f\left ({n}\right )\cdots }\right )}\right )}\limits_{�}^{}}}\limits_{2024个f}^{}}$ ．

## 知识点

**中文**:
  - 数列新定义问题

**English**:
  - New Definition Problems

---
