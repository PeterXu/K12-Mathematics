# Mathematics - 题目 123

**ID**: ffbfd5992b4f44989d39ca92ca2b164d
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\frac {x}{1-x}-{\rm{l}}{\rm{n}}\frac {x{^{2}}-1}{x{^{2}}+x-1}$ .​​​​​​​‌（1）求 $f\left ({x}\right )$ 的定义域；（2）求 $f\left ({x}\right )$ 在区间 $\left ({0,\frac {1}{2}}\right )$ 上的零点个数；（3）设 $k\in \left ({0,\frac {1}{2}}\right )$ ，证明： $\left ({k{^{2}}+1}\right )\left ({k{^{3}}+1}\right )\left ({k{^{4}}+1}\right )\cdot \cdot \cdot \left ({k{^{n}}+1}\right )<\frac {k-1}{k{^{2}}+k-1}$

## 解答

1. （1）由题意 $\begin{cases}1-x\ne 0\\\frac {x{^{2}}-1}{x{^{2}}+x-1}>0\\x{^{2}}+x-1\ne 0\end{cases}$ ，所以 $\begin{cases}x\ne 1\\x{^{2}}-1>0\\x{^{2}}+x-1>0\end{cases}$ 或 $\begin{cases}x\ne 1\\x{^{2}}-1<0\\x{^{2}}+x-1<0\end{cases}$ ，
2. 解得 $x<\frac {-1-\sqrt {5}}{2}$ 或 $x>1$ 或 $-1<x<\frac {-1+\sqrt {5}}{2}$ ，
3. 所以 $f\left ({x}\right )$ 的定义域为 $\left ({-∞,\frac {-1-\sqrt {5}}{2}}\right )\cup \left ({-1,\frac {-1+\sqrt {5}}{2}}\right )\cup \left ({1,+∞}\right )$ .
4. （2）由题意得 $f\left ({x}\right )=\frac {x}{1-x}-{\rm{l}}{\rm{n}}\frac {x{^{2}}-1}{x{^{2}}+x-1}$ ，
5. 所以 $f^{′}(x)=\frac {1-x-(-1)\cdot x}{{\left({1-x}\right)^{2}}}-\frac {x{^{2}}+x-1}{x{^{2}}-1}\cdot \left ({\frac {x{^{2}}-1}{x{^{2}}+x-1}}\right ){^{\prime }}$
6. ${\rm =}\frac {1}{{\left({1-x}\right)^{2}}}-\frac {x{^{2}}+x-1}{x{^{2}}-1}\cdot \frac {2x\cdot \left ({x{^{2}}+x-1}\right )-\left ({2x+1}\right )\left ({x{^{2}}-1}\right )}{{\left({x{^{2}}+x-1}\right)^{2}}}$
7. ${\rm =}\frac {1}{{\left({1-x}\right)^{2}}}-\frac {x{^{2}}+1}{\left ({x{^{2}}-1}\right )\left ({x{^{2}}+x-1}\right )}=\frac {x(x-1)(3x-1)}{{\left({1-x}\right)^{2}}\left ({x{^{2}}-1}\right )\left ({x{^{2}}+x-1}\right )}$
8. $=\frac {x(3x-1)}{{\left({1-x}\right)^{2}}\left ({x+1}\right )\left ({x{^{2}}+x-1}\right )}$ ，
9. 因为当 $x\in \left ({0,\frac {1}{2}}\right )$ 时， $x{^{2}}+x-1={\left({x+\frac {1}{2}}\right)^{2}}-\frac {5}{4}<0$ ，
10. 所以当 $x\in \left ({0,\frac {1}{3}}\right )$ 时， $f^{′}(x)>0$ ， $f(x)$ 单调递增，
11. 当 $x\in \left ({\frac {1}{3},\frac {1}{2}}\right )$ 时， $f^{′}(x)<0$ ， $f(x)$ 单调递减，
12. 所以当 $x\in \left ({0,\frac {1}{3}}\right ]$ 时， $f(x)>f(0)=0$ ，则 $f\left ({\frac {1}{3}}\right )>0$ ，
13. 又 $f\left ({\frac {1}{2}}\right )=\frac {\frac {1}{2}}{1-\frac {1}{2}}-{\ln}\frac {\frac {1}{4}-1}{\frac {1}{4}+\frac {1}{2}-1}=1-{\ln}3<0$ ，则 $f\left ({\frac {1}{3}}\right )\cdot f\left ({\frac {1}{2}}\right )<0$
14. 所以 $f(x)$ 在区间 $\left ({0,\frac {1}{3}}\right ]$ 上没有零点，在区间 $\left ({\frac {1}{3},\frac {1}{2}}\right )$ 有且仅有1个零点，
15. 所以 $f\left ({x}\right )$ 在区间 $\left ({0,\frac {1}{2}}\right )$ 上有且仅有1个零点.
16. （3）当 $k\in \left ({0,\frac {1}{2}}\right )$ 时，要证 $\left ({k{^{2}}+1}\right )\left ({k{^{3}}+1}\right )\left ({k{^{4}}+1}\right )\cdot \cdot \cdot \left ({k{^{n}}+1}\right )<\frac {k-1}{k{^{2}}+k-1}$ ，
17. 对两边同取对数得 ${\ln}\left ({k{^{2}}+1}\right )+{\ln}\left ({k{^{3}}+1}\right )+\cdot \cdot \cdot +{\ln}\left ({k{^{n}}+1}\right )<{\ln}\frac {k-1}{k{^{2}}+k-1}$ ，
18. 令 $h(x)={\ln}x-x+1$ ， $(x>0)$ ，则 $h^{′}(x)=\frac {1}{x}-1=\frac {1-x}{x}$ ，
19. 所以当 $x>1$ 时， $h^{′}(x)<0$ ， $h(x)$ 单调递减，
20. 所以 $h(x)<h(1)=0$ ，
21. 所以当 $x>1$ 时， ${\ln}x<x-1$ ，所以 ${\ln}\left ({k{^{n}}+1}\right )<k{^{n}}$ ，
22. 所以 ${\ln}\left ({k{^{2}}+1}\right )+{\ln}\left ({k{^{3}}+1}\right )+\cdot \cdot \cdot +{\ln}\left ({k{^{n}}+1}\right )<k{^{2}}+k{^{3}}+\cdot \cdot \cdot +k{^{n}}=\frac {k{^{2}}(1-k{^{n-1}})}{1-k}<\frac {k{^{2}}}{1-k}$ ，
23. 要证原不等式成立，只需证 $\frac {k{^{2}}}{1-k}<{\ln}\frac {k-1}{k{^{2}}+k-1}$ ，
24. 令 $g(x)=\frac {x{^{2}}}{1-x}-{\rm{l}}{\rm{n}}\frac {x-1}{x{^{2}}+x-1}$ ，
25. 则 $g^{′}(x)=\frac {2x\cdot (1-x)-(-1)\cdot x{^{2}}}{{\left({1-x}\right)^{2}}}-\frac {x{^{2}}+x-1}{x-1}\cdot \frac {x{^{2}}+x-1-(2x+1)(x-1)}{{\left({x{^{2}}+x-1}\right)^{2}}}$
26. $=\frac {2x-x{^{2}}}{{\left({1-x}\right)^{2}}}-\frac {2x-x{^{2}}}{\left ({x-1}\right )\left ({x{^{2}}+x-1}\right )}$
27. ${\rm =}\left ({2x-x{^{2}}}\right )\left [\frac {1}{{\left({1-x}\right)^{2}}}-\frac {1}{\left ({x-1}\right )\left ({x{^{2}}+x-1}\right )}\right ]$  $=\frac {x{^{3}}(2-x)}{{\left({1-x}\right)^{2}}\left ({x{^{2}}+x-1}\right )}$ ，
28. 由（1）得，当 $x\in \left ({0,\frac {1}{2}}\right )$ 时， $x{^{2}}+x-1={\left({x+\frac {1}{2}}\right)^{2}}-\frac {5}{4}<0$ ，
29. 所以 $g^{′}(x)<0$ ， $g(x)$ 单调递减，
30. 所以 $g(x)<g(0)=0$ ，
31. 所以当 $k\in \left ({0,\frac {1}{2}}\right )$ 时， $g(k)<0$ ，即 $\frac {k{^{2}}}{1-k}<{\ln}\frac {k-1}{k{^{2}}+k-1}$ ，
32. 从而原命题得证.

## 知识点

**中文**:
  - 函数的定义域
  - 利用导数解决函数零点问题
  - 构造放缩函数问题

**English**:
  - Domain of Functions
  - Solving Zero Point Problems
  - Constructing Scaling Functions

---
