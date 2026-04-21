# Mathematics - 题目 3606

**ID**: 749d40b631c14019a23fe7fe4cd07e83
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设函数 $f(x)=x\sin x(x\in {\rm{R}})$ ．(1)判断函数 $y=f\left ({x}\right )$ 的奇偶性，并说明理由；​​​​​​​‌(2)设 $x{{}_{0}}$ 为 $f\left ({x}\right )$ 的一个极值点，证明 $\left [f\left ({x{{}_{0}}}\right )\right ]{^{2}}=\frac {x{{}_{0}^{4}}}{1+x{{}_{0}^{2}}}$ ；(3)设 $f\left ({x}\right )$ 在 $\left ({0{\rm{,}}+\infty }\right )$ 内的全部极值点按从小到大的顺序排列 $a{{}_{1}},a{{}_{2}},\cdots ,a{{}_{n}},\cdots $ ，证明 $\frac {π}{2}<a{{}_{n+1}}-a{{}_{n}}<π\left ({n=1,2,\ldots }\right )$

## 解答

1. （1）函数 $f\left ({x}\right )=x{\rm{s}}{\rm{i}}{\rm{n}}x$ 定义域为 ${\rm{R}}$ ，对任意 $x\in {\rm{R}}$ ，有 $-x\in {\rm{R}}$ ，
2. 且 $f\left ({-x}\right )=-x{\rm{s}}{\rm{i}}{\rm{n}}\left ({-x}\right )=x{\rm{s}}{\rm{i}}{\rm{n}}x=f\left ({x}\right )$ 恒成立，故函数 $y=f\left ({x}\right )$ 为偶函数.
3. （2）因为函数 $f(x)=x\sin x(x\in {\rm{R}})$ ，
4. 所以 $f^{′}(x)=\sin x+x{\cos}x$ ，
5. 令 $f^{′}(x)=0$ ，则 $\sin x+x{\cos}x=0$ ，对满足方程的 $x$ 有 ${\cos}x\ne 0$ ，
6. 所以 $x=-{\tan}x$ ，
7. 由函数 $y=x$ 与函数 $y=-{\tan}x$ 的图象可知此方程一定有解，
8. 
9. 故 $f(x)$ 的一个极值点 $x{{}_{0}}$ 满足 ${\tan}x{{}_{0}}=-x{{}_{0}}$ ，
10. 所以 $\left [f\left ({x{{}_{0}}}\right )\right ]{^{2}}={\left({x{{}_{0}}\sin x{{}_{0}}}\right)^{2}}=x{{}_{0}^{2}}\sin {^{2}}x{{}_{0}}=\frac {x{{}_{0}^{2}}\sin {^{2}}x{{}_{0}}}{\sin {^{2}}x{{}_{0}}+{\cos}{^{2}}x{{}_{0}}}=\frac {x{{}_{0}^{2}}{\tan}{^{2}}x{{}_{0}}}{{\tan}{^{2}}x{{}_{0}}+1}=\frac {x{{}_{0}^{4}}}{1+x{{}_{0}^{2}}}$ ；
11. （3）设 $x{{}_{0}}$ 是 $f^{′}(x)=0$ 的任意正实根，则 $x{{}_{0}}=-{\tan}x{{}_{0}}$ ，
12. 则存在一个非负整数 $k$ ，使 $x{{}_{0}}\in \left ({\frac {{\rm{π}}}{2}+k{\rm{π}},{\rm{π}}+k{\rm{π}}}\right )$ ，即 $x{{}_{0}}$ 为第二或第四象限角，
13. 因为 $f^{′}(x)=\sin x+x{\cos}x={\cos}x\left ({{\tan}x+x}\right )$ ，
14. 所以在第二或第四象限 $x$ 变化时， $f^{′}(x)$ 变化如下，
15. $x$
16. $\left ({\frac {{\rm{π}}}{2}+k{\rm{π}},x{{}_{0}}}\right )$
17. $x{{}_{0}}$
18. $\left ({x{{}_{0}},{\rm{π}}+k{\rm{π}}}\right )$
19. $f^{′}(x)$ ( $k$ 为奇数)
20. $-$
21. 0
22. +
23. $f^{′}(x)$ ( $k$ 为偶数)
24. +
25. 0
26. $-$
27. 所以满足 $f^{′}(x)=0$ 的正根 $x{{}_{0}}$ 都为函数 $f(x)$ 的极值点，
28. 由题可知 $a{{}_{1}},a{{}_{2}},\cdot \cdot \cdot ,a{{}_{n}},\cdot \cdot \cdot $ 为方程 $x=-{\tan}x$ 的全部正实根且满足 $a{{}_{1}}<a{{}_{2}}<\cdot \cdot \cdot <a{{}_{n}}<\cdot \cdot \cdot $ ， $(n=1,2,\cdot \cdot \cdot )$
29. 所以 $a{{}_{n+1}}-a{{}_{n}}=-\left ({{\tan}a{{}_{n+1}}-{\tan}a{{}_{n}}}\right )=-\left ({1+{\tan}a{{}_{n+1}}{\tan}a{{}_{n}}}\right ){\tan}\left ({a{{}_{n+1}}-a{{}_{n}}}\right )$ ，
30. 因为 $\frac {{\rm{π}}}{2}+\left ({n-1}\right ){\rm{π}}<a{{}_{n}}<{\rm{π}}+\left ({n-1}\right ){\rm{π}}$ ， $\frac {{\rm{π}}}{2}+n{\rm{π}}<a{{}_{n+1}}<{\rm{π}}+n{\rm{π}}$ ，  $(n=1,2,\cdot \cdot \cdot )$
31. 则 $\frac {{\rm{π}}}{2}<a{{}_{n+1}}-a{{}_{n}}<\frac {{{3}}{\rm{π}}}{2}$ ，
32. 由 ${\tan}a{{}_{n+1}}{\tan}a{{}_{n}}>0$ ，可得 ${\tan}\left ({a{{}_{n+1}}-a{{}_{n}}}\right )<0$ ，
33. 所以 $\frac {{\rm{π}}}{2}<a{{}_{n+1}}-a{{}_{n}}<{\rm{π}}$ .

## 知识点

**中文**:
  - 函数奇偶性的判断与证明
  - 利用导数研究函数的单调性与单调区间
  - 利用导数研究函数的极值

**English**:
  - Judgment and Proof of Parity (Odd/Even)
  - Monotonicity and Monotonic Intervals
  - Extrema of Functions using Derivatives

---
