# Mathematics - 题目 740

**ID**: 7d5ef5dcd7f34416b769ad3b9f30e431
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知 $a>0$ ，函数 $f\left ({x}\right )=ax\sin x+{\cos}ax-1$ ， $0<x<\frac {{\rm{π}}}{4}$ ．(1)若 $a=2$ ，证明： $f\left ({x}\right )>0$ ；​​​​​​​‌(2)若 $f\left ({x}\right )>0$ ，求a的取值范围；(3)设集合 $P=\{a{{}_{n}}|a{{}_{n}}=\sum \limits_{k=1}^{n}\mathop{{\cos}\frac {{\rm{π}}}{2k\left ({k+1}\right )}}{\rm{,}}n\in \mathbf{N}{^{∗}}\}$ ，对于正整数m，集合 $Q{{}_{m}}=\left \{x|m<x<2m\right \}$ ，记 $P\cap Q{{}_{m}}$ 中元素的个数为 $b{{}_{m}}$ ，求数列 $\left \{b{{}_{m}}\right \}$ 的通项公式．

## 解答

1. （1）因为 $a=2$ ，所以 $f\left ({x}\right )=2x\sin x+{\cos}2x-1=2\left ({x-\sin x}\right )\sin x$ ，
2. $0<x<\frac {{\rm{π}}}{4}$ ， $2\sin x>0$ ．
3. 设 $g\left ({x}\right )=x-{\rm{s}}{\rm{i}}{\rm{n}}x$ ， $0<x<\frac {{\rm{π}}}{4}$ ，
4. 则 $g^{′}{\left ({x}\right )}=1-{\rm{c}}{\rm{o}}{\rm{s}}x>0$ ，所以 $g\left ({x}\right )$ 在 $\left ({0,\frac {{\rm{π}}}{4}}\right )$ 上单调递增，
5. 所以 $g\left ({x}\right )>g\left ({0}\right )=0$ ，
6. 因此 $f\left ({x}\right )>0$ ．
7. （2）函数 $f\left ({x}\right )=ax\sin x+{\cos}ax-1$ ， $0<x<\frac {{\rm{π}}}{4}$ ，
8. $f^{′}{\left ({x}\right )}=a\left ({{\rm{s}}{\rm{i}}{\rm{n}}x+x{\rm{c}}{\rm{o}}{\rm{s}}x-{\rm{s}}{\rm{i}}{\rm{n}}ax}\right )$ ，
9. 当 $0\mathrm{<}a\leqslant 2$ 时，
10. 注意到 $0<ax\leqslant 2x<\frac {{\rm{π}}}{2}$ ，故 ${\rm{s}}{\rm{i}}{\rm{n}}ax\leqslant {\rm{s}}{\rm{i}}{\rm{n}}2x$ ，
11. 因此 $f^{′}{\left ({x}\right )}\geqslant a\left ({{\rm{s}}{\rm{i}}{\rm{n}}x+x{\rm{c}}{\rm{o}}{\rm{s}}x-{\rm{s}}{\rm{i}}{\rm{n}}2x}\right )=a\left [{\rm{s}}{\rm{i}}{\rm{n}}x\left ({1-{\rm{c}}{\rm{o}}{\rm{s}}x}\right )+\left ({x-{\rm{s}}{\rm{i}}{\rm{n}}x}\right ){\rm{c}}{\rm{o}}{\rm{s}}x\right ]$ ，
12. 由（1）得 $x-{\rm{s}}{\rm{i}}{\rm{n}}x>0$ ，因此 $f^{′}{\left ({x}\right )}>0$ ，
13. 所以 $f\left ({x}\right )$ 在 $\left ({0,\frac {{\rm{π}}}{4}}\right )$ 上单调递增，从而 $f\left ({x}\right )>f\left ({0}\right )=0$ ，满足题意；
14. 当 $a>2$ 时，令 $h\left ({x}\right )=f^{′}{\left ({x}\right )}=a\left ({{\rm{s}}{\rm{i}}{\rm{n}}x+x{\rm{c}}{\rm{o}}{\rm{s}}x-{\rm{s}}{\rm{i}}{\rm{n}}ax}\right )$ ，
15. $h^{′}{\left ({x}\right )}=a\left ({2{\cos}x-x\sin x-a{\cos}ax}\right )<a\left ({2-a{\cos}ax}\right )=a{^{2}}\left ({\frac {2}{a}-{\cos}ax}\right )$ ，
16. 因为 $0<\frac {2}{a}<1$ ，所以存在 $aθ\in \left ({0{\rm{,}}\frac {\mathrm{π}}{2}}\right )$ ，使得 ${\cos}aθ=\frac {2}{a}$ ，
17. 则当 $x\in (0,θ)$ 时， $ax\in (0,aθ)$ ， $h^{′}{\left ({x}\right )}<a{^{2}}\left ({\frac {2}{a}-\frac {2}{a}}\right )=0$ ，所以 $f^{′}{\left ({x}\right )}$ 在 $\left ({0,θ}\right )$ 上单调递减，
18. 从而 $f^{′}{\left ({x}\right )}<f^{′}{\left ({0}\right )}=0$ ，所以 $f\left ({x}\right )$ 在 $\left ({0,θ}\right )$ 上单调递减，因此 $f\left ({θ}\right )<f\left ({0}\right )=0$ ，不合题意；
19. 综上， $0\mathrm{<}a\leqslant 2$ ．
20. （3）由（1）可知 $a=2$ 时， ${\rm{c}}{\rm{o}}{\rm{s}}2x>1-2x{\rm{s}}{\rm{i}}{\rm{n}}x>1-2x$ ，
21. 所以 ${\cos}\frac {{\rm{π}}}{2k\left ({k+1}\right )}>1-\frac {{\rm{π}}}{2k\left ({k+1}\right )}=1-\frac {{\rm{π}}}{2}\left ({\frac {1}{k}-\frac {1}{k+1}}\right )$ ，
22. $n=1$ 时， $\sum \limits_{k=1}^{n}\mathop{{\cos}}\frac {{\rm{π}}}{2k\left ({k+1}\right )}=\frac {\sqrt {2}}{2}$ ，
23. $n=2$ 时， $\sum \limits_{k=1}^{n}\mathop{{\cos}}\frac {{\rm{π}}}{2k\left ({k+1}\right )}=\frac {\sqrt {2}}{2}+\frac {\sqrt {6}+\sqrt {2}}{4}=\frac {3\sqrt {2}+\sqrt {6}}{4}$ ，
24. $n\geqslant 3$ 时，
25. $\sum \limits_{k=1}^{n}\mathop{{\cos}}\frac {{\rm{π}}}{2k\left ({k+1}\right )}\geqslant \frac {\sqrt {2}}{2}+\frac {\sqrt {6}+\sqrt {2}}{4}+n-2-\frac {{\rm{π}}}{2}\left ({\frac {1}{3}-\frac {1}{n+1}}\right )>n-2+\frac {3\sqrt {2}+\sqrt {6}}{4}-\frac {{\rm{π}}}{6}$ ，
26. ${\left({9\sqrt {2}+3\sqrt {6}}\right)^{2}}-20{^{2}}=54\sqrt {12}-184>0$ ，则 ${\left({9\sqrt {2}+3\sqrt {6}}\right)^{2}}>20{^{2}}$ ，即 $9\sqrt {2}+3\sqrt {6}-20>0$ ，
27. $\frac {3\sqrt {2}+\sqrt {6}}{4}-\frac {{\rm{π}}}{6}-1>\frac {3\sqrt {2}+\sqrt {6}}{4}-\frac {{{4}}}{6}-1=\frac {9\sqrt {2}+3\sqrt {6}-20}{12}>0$ ，则 $\frac {3\sqrt {2}+\sqrt {6}}{4}-\frac {{\rm{π}}}{6}>1$ ，
28. 得 $\sum \limits_{k=1}^{n}\mathop{{\cos}}\frac {{\rm{π}}}{2k\left ({k+1}\right )}>n-2+\frac {3\sqrt {2}+\sqrt {6}}{4}-\frac {{\rm{π}}}{6}>n-1$ ，
29. 又因为 $\sum \limits_{k=1}^{n}\mathop{{\cos}}\frac {{\rm{π}}}{2k\left ({k+1}\right )}<n$ ，
30. $n=1$ 时， $0<\frac {\sqrt {2}}{2}<1$ ， $n=2$ 时， $1<\frac {3\sqrt {2}+\sqrt {6}}{4}<2$ ，
31. 所以 $n∈\mathbf{N}{^{*}}$ 时，都有 $n-1<\sum \limits_{k=1}^{n}\mathop{{\cos}}\frac {{\rm{π}}}{2k\left ({k+1}\right )}<n$ ，
32. $P=\{a{{}_{n}}|a{{}_{n}}=\sum \limits_{k=1}^{n}\mathop{{\cos}\frac {{\rm{π}}}{2k\left ({k+1}\right )}}{\rm{,}}n\in \mathbf{N}{^{∗}}\}$ ，则 $n\in \mathbf{N}{^{*}}$ 时，集合 $P$ 在每个区间 $\left ({n-1,n}\right )$ 都有且只有一个元素，
33. 对于正整数m，集合 $Q{{}_{m}}=\left \{x|m<x<2m\right \}$ ，记 $P\cap Q{{}_{m}}$ 中元素的个数为 $b{{}_{m}}$ ，
34. 由 $2m-m=m$ ，所以 $b{{}_{m}}=m$ .

## 知识点

**中文**:
  - 利用导数研究函数的最值
  - 利用导数证明不等式
  - 数列求和方法之裂项相消法

**English**:
  - Global Extrema (Max/Min) using Derivatives
  - Proving Inequalities using Derivatives
  - Telescoping Series Method

---
