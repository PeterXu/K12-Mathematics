# Mathematics - 题目 3440

**ID**: 6e268792dda94439aeb154ece74f90db
**年级**: Grade 10
**难度**: Medium
**题型**: Calculation

## 题目
已知函数 $y=a{^{x}}$ （ $a>0$ 且 $a\ne 1$ ）在 $\left [2,4\right ]$ 上的最大值和最小值之和为20，函数 $f\left ({x}\right )=\frac {a{^{x}}}{a{^{x}}+1}+b$ 是奇函数．(1)求a和b的值；​​​​​​​‌(2)用函数单调性的定义证明：函数 $f\left ({x}\right )$ 在R上单调递增；(3)若函数 $g\left ({x}\right )=m\left [f\left ({x}\right )+f\left ({1-x}\right )\right ]-1$ 恰有两个不同的零点，求m的取值范围．

## 解答

1. （1）当 $a>1$ 时，函数 $y=a{^{x}}$ 在 $\left [2,4\right ]$ 上单调递增；
2. 当 $0<a<1$ 时，函数 $y=a{^{x}}$ 在 $\left [2,4\right ]$ 上单调递减，
3. 所以函数 $y=a{^{x}}$ 在 $\left [2,4\right ]$ 上的最大值与最小值之和为 $a{^{2}}+a{^{4}}=20$ ，解得 $a=2$ ．
4. 所以 $f\left ({x}\right )=\frac {2{^{x}}}{2{^{x}}+1}+b$ ， $f\left ({x}\right )$ 的定义域为R，又函数 $f\left ({x}\right )$ 是奇函数，
5. 所以 $f\left ({0}\right )=\frac {2{^{0}}}{2{^{0}}+1}+b=\frac {1}{2}+b=0$ ，解得 $b=-\frac {1}{2}$ ，
6. 当 $b=-\frac {1}{2}$ 时， $f\left ({x}\right )=\frac {2{^{x}}}{2{^{x}}+1}-\frac {1}{2}$ ，
7. 所以 $f\left ({-x}\right )=\frac {2{^{-x}}}{2{^{-x}}+1}-\frac {1}{2}=\frac {1}{2{^{x}}+1}-\frac {1}{2}=\frac {1}{2{^{x}}+1}-1+\frac {1}{2}=-\frac {2{^{x}}}{2{^{x}}+1}+\frac {1}{2}=-f\left ({x}\right )$ ，
8. 所以函数 $f\left ({x}\right )$ 是奇函数，满足题意．
9. （2）证明：任取 $x{{}_{1}},x{{}_{2}}\in {\rm{R}}$ ，且 $x{{}_{1}}<x{{}_{2}}$ ，
10. 所以 $f\left ({x{{}_{1}}}\right )-f\left ({x{{}_{2}}}\right )=\frac {2{^{x{{}_{1}}}}}{2{^{x{{}_{1}}}}+1}-\frac {1}{2}-\left ({\frac {2{^{x{{}_{2}}}}}{2{^{x{{}_{2}}}}+1}-\frac {1}{2}}\right )=\frac {2{^{x{{}_{1}}}}}{2{^{x{{}_{1}}}}+1}-\frac {2{^{x{{}_{2}}}}}{2{^{x{{}_{2}}}}+1}$
11. $=\frac {2{^{x{{}_{1}}}}\left ({2{^{x{{}_{2}}}}+1}\right )-2{^{x{{}_{2}}}}\left ({2{^{x{{}_{1}}}}+1}\right )}{\left ({2{^{x{{}_{1}}}}+1}\right )\left ({2{^{x{{}_{2}}}}+1}\right )}=\frac {2{^{x{{}_{1}}}}-2{^{x{{}_{2}}}}}{\left ({2{^{x{{}_{1}}}}+1}\right )\left ({2{^{x{{}_{2}}}}+1}\right )}$ ，
12. 又 $x{{}_{1}}<x{{}_{2}}$ ，所以 $2{^{x{{}_{1}}}}<2{^{x{{}_{2}}}}$ ， $2{^{x{{}_{1}}}}+1>0$ ， $2{^{x{{}_{2}}}}+1>0$ ，所以 $f\left ({x{{}_{1}}}\right )-f\left ({x{{}_{2}}}\right )<0$ ，
13. 即 $f\left ({x{{}_{1}}}\right )<f\left ({x{{}_{2}}}\right )$ ，
14. 所以函数 $f\left ({x}\right )$ 在R上单调递增．
15. （3）因为 $f\left ({x}\right )+f\left ({1-x}\right )=\frac {2{^{x}}}{2{^{x}}+1}+\frac {2{^{1-x}}}{2{^{1-x}}+1}-1=\frac {2{^{x}}}{2{^{x}}+1}+\frac {2}{2+2{^{x}}}-1=\frac {2{^{2x}}+4\cdot 2{^{x}}+2}{2{^{2x}}+3\cdot 2{^{x}}+2}-1=$  $\frac {2{^{x}}}{2{^{2x}}+3\cdot 2{^{x}}+2}$ ，
16. 所以 $g\left ({x}\right )=m\left [f\left ({x}\right )+f\left ({1-x}\right )\right ]-1=\frac {m\cdot 2{^{x}}}{2{^{2x}}+3\cdot 2{^{x}}+2}-1=0$ 有两个不同的实数解，
17. 即 $2{^{2x}}-\left ({m-3}\right )\cdot 2{^{x}}+2=0$ 有两个不同的实数解，
18. 令 $t=2{^{x}}\left ({t>0}\right )$ ，则 $t{^{2}}-\left ({m-3}\right )t+2=0$ 在 $\left ({0,+∞}\right )$ 上有两个不同的实数解，
19. 令 $h\left ({t}\right )=t{^{2}}-\left ({m-3}\right )t+2$ ，又 $h\left ({0}\right )=2>0$ ，所以 $\begin{cases}-\frac {-\left ({m-3}\right )}{2}>0,\\{\rm{Δ}}=\left [-\left ({m-3}\right )\right ]{^{2}}-8>0,\end{cases}$
20. 解得 $m>3+2\sqrt {2}$ ，即m的取值范围是 $\left ({3+2\sqrt {2},+∞}\right )$ ．

## 知识点

**中文**:
  - 函数单调性的判断与证明
  - 函数奇偶性的应用
  - 函数零点的存在性定理及应用

**English**:
  - Judgment and Proof of Monotonicity
  - Applications of Parity
  - Existence Theorem of Zero Points and Applications

---
