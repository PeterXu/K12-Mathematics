# Mathematics - 题目 1628

**ID**: 27069a45ad504822bcde9f811c71f112
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: 解答题共6小题，共85分．解答应写出文字说明，演算步骤或证明过程．

## 题目
已知 $x\in \mathbf{R}$ ，用 $\left [x\right ]$ 表示不超过x的最大整数，例如 $\left [1.​​​​​​​‌2\right ]=1$ ， $\left [-1.2\right ]=-2$ ， $\left [1\right ]=1$ .对于函数 $f\left ({x}\right )$ ，若存在 $m\in \mathbf{R}$ ， $m\notin \mathbf{Z}$ ，使得 $f\left ({m}\right )=f\left ({\left [m\right ]}\right )$ ，则称函数 $f\left ({x}\right )$ 是“ $Ω$ 函数”.（1）判断函数 $f\left ({x}\right )=x{^{3}}-\frac {1}{4}x$ ， $g\left ({x}\right )=\left |{{\tan}{\rm{π}}x}\right |$ 是否是“ $Ω$ 函数”；（2）设函数 $f\left ({x}\right )$ 是定义在 $\mathbf{R}$ 上的周期函数，最小正周期是T，若 $f\left ({x}\right )$ 不是“ $Ω$ 函数”，求T的最小值；（3）若函数 $f\left ({x}\right )={\ln}x+\frac {a}{{\ln}x}$ 是“ $Ω$ 函数”，求a的取值范围.

## 解答

1. （1）对函数 $f\left ({x}\right )=x{^{3}}-\frac {1}{4}x$ ，
2. 取 $x=\frac {1}{2}$ ，则 $\left [x\right ]=0$ ，
3. $f\left ({\frac {1}{2}}\right )=\frac {1}{2}\left [{\left({\frac {1}{2}}\right)^{2}}-\frac {1}{4}\right ]=0$ ， $f\left ({\left [\frac {1}{2}\right ]}\right )=f\left ({0}\right )=0$ ，所以 $f\left ({\frac {1}{2}}\right )=f\left ({\left [\frac {1}{2}\right ]}\right )$ .
4. 所以 $f\left ({x}\right )=x{^{3}}-\frac {1}{4}x$ 是“ $Ω$ 函数”；
5. 对函数 $g\left ({x}\right )=\left |{{\tan}{\rm{π}}x}\right |$ ，
6. 因为 $g\left ({x}\right )=\left |{{\tan}{\rm{π}}x}\right |$ 是周期函数，且周期为： $T=1$ .
7. 由 $g\left ({x}\right )=\left |{{\tan}{\rm{π}}x}\right |=0$  $\Leftrightarrow $  $x\mathrm{∈}\mathbf{Z}$ .
8. 设 $m\in \mathbf{R}$ 且 $m\notin \mathbf{Z}$ ，则 $\left [m\right ]\in \mathbf{Z}$ .
9. 所以 $g\left ({m}\right )\ne 0$ ，但 $g\left ({\left [m\right ]}\right )=0$ ，
10. 所以不存在 $m\in \mathbf{R}$ 且 $m\notin \mathbf{Z}$ ，使得 $g\left ({m}\right )=g\left ({\left [m\right ]}\right )$ 成立.
11. 所以 $g\left ({x}\right )=\left |{{\tan}{\rm{π}}x}\right |$ 不是“ $Ω$ 函数”.
12. （2）因为 $f\left ({x}\right )$ 是以 $T$ 为最小正周期的周期函数，所以 $f\left ({T}\right )=f\left ({0}\right )$ .
13. 假设 $0<T<1$ ，则 $\left [T\right ]=0$ ，所以 $f\left ({\left [T\right ]}\right )=f\left ({0}\right )=f\left ({T}\right )$ ，
14. 所以 $f\left ({x}\right )$ 是“ $Ω$ 函数”.
15. 所以若 $f\left ({x}\right )$ 不是“ $Ω$ 函数”，必有 $T\geqslant 1$ .
16. 设函数 $f\left ({x}\right )=x-\left [x\right ]$ ，则函数 $f\left ({x}\right )$ 是周期函数，且周期为1.
17. 对任意 $x\in \mathbf{R}$ 且 $x\notin \mathbf{Z}$ ，  $f\left ({x}\right )=x-\left [x\right ]\in \left ({0,1}\right )$ ， $f\left ({\left [x\right ]}\right )=\left [x\right ]-\left [x\right ]=0$ ，所以 $f\left ({x}\right )\ne f\left ({\left [x\right ]}\right )$ .
18. 所以 $f\left ({x}\right )=x-\left [x\right ]$ 不是“ $Ω$ 函数”.
19. 故函数 $f\left ({x}\right )$ 是定义在 $\mathbf{R}$ 上的周期函数，最小正周期是T，
20. 若 $f\left ({x}\right )$ 不是“ $Ω$ 函数”，则 $T$ 的最小值为1.
21. （3）因为 $f(x)={\ln}x+\frac {a}{{\ln}x},x>0$ ，且 $x\ne 1$ ；
22. 当 $m\in (0,1)$ 时， $[m]=0$ ，显然不符合题意；
23. 当 $m\in (1,2)$ 时， $[m]=1$ ， ${\ln}1+\frac {a}{{\ln}1}$ 没有意义；
24. 当 $m\in (k,k+1)$ ，且 $k\in \mathbf{N}$ ， $k\geqslant 2$ ，有 $[m]=k$ ，由 $f(m)=f([m])$ ，
25. 得到 ${\ln}m+\frac {a}{{\ln}m}={\ln}k+\frac {a}{{\ln}k}$ ，即 ${\ln}m-{\ln}k+\frac {a}{{\ln}m}-\frac {a}{{\ln}k}=0$ ，
26. 化简并整理得 $({\ln}m-{\ln}k)(1-\frac {a}{{\ln}m\cdot {\ln}k})=0$
27. 又因为 $m\ne k$ ，故 $1-\frac {a}{{\ln}m\cdot {\ln}k}=0$ ，则 $a={\ln}m\cdot {\ln}k$ ;
28. 由 $2\leqslant k<m<k+1$ ，则 ${\ln}2\leqslant {\ln}k<{\ln}m<{\ln}(k+1)$ ，
29. 故 $({\ln}k){^{2}}<{\ln}m\cdot {\ln}k<{\ln}k\cdot {\ln}(k+1)$ ，即 $({\ln}k){^{2}}<a<{\ln}k\cdot {\ln}(k+1)$ ，
30. 所以 $a$ 的取值范围为 $\{a|({\ln}k){^{2}}<a<{\ln}k\cdot {\ln}(k+1),k\in \mathbf{N},k>1\}$ .

## 知识点

**中文**:
  - 函数新定义问题

**English**:
  - New Definition Problems in Functions

---
