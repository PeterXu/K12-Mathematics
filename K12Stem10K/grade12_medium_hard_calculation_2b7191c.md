# Mathematics - 题目 2665

**ID**: 2b7191c67fce41bcbf6fb7ab3014aee0
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\frac {1}{3}x{^{3}}+\frac {1}{2}ax{^{2}}+\left ({\frac {1}{4}a{^{2}}-1}\right )x，a\in {\rm{R}}$ .​​​​​​​‌（1）求证：存在 $m，n$ ，使得函数 $y=f\left ({x+m}\right )-n$ 是奇函数，并由此求 $f\left ({x}\right )$ 的图象的对称中心的坐标（用 $a$ 表示）；（2）若 $f\left ({x}\right )$ 的极大值点是 $f\left ({x}\right )$ 的一个零点，求 $a$ 的值及函数 $f\left ({x}\right )$ 的所有零点的和.

## 解答

1. （1）（法一）因为 $y=f\left ({x+m}\right )-n=\frac {1}{3}{\left({x+m}\right)^{3}}+\frac {1}{2}a{\left({x+m}\right)^{2}}+\left ({\frac {1}{4}a{^{2}}-1}\right )\left ({x+m}\right )-n$
2. $=\frac {1}{3}x{^{3}}+\left ({m+\frac {1}{2}a}\right )x{^{2}}+\left ({m{^{2}}+am+\frac {1}{4}a{^{2}}-1}\right )x+\frac {1}{3}m{^{3}}+\frac {1}{2}am{^{2}}+\left ({\frac {1}{4}a{^{2}}-1}\right )m-n$ ，
3. 所以要使函数 $y=f\left ({x+m}\right )-n$ 是奇函数，
4. 则有 $m+\frac {1}{2}a=\frac {1}{3}m{^{3}}+\frac {1}{2}am{^{2}}+\left ({\frac {1}{4}a{^{2}}-1}\right )m-n=0$ ，
5. 所以 $m=-\frac {1}{2}a,n=\frac {12a-a{^{3}}}{24},y=f\left ({x+m}\right )-n=\frac {1}{3}x{^{3}}-x$ 是奇函数，
6. 所以存在 $m=-\frac {1}{2}a,n=\frac {12a-a{^{3}}}{24}$ ，使得 $y=f\left ({x+m}\right )-n$ 是奇函数，
7. 又奇函数的图象关于原点对称，所以 $f\left ({x}\right )$ 的图象关于点 $\left ({-\frac {1}{2}a,\frac {12a-a{^{3}}}{24}}\right )$ 对称，
8. 即 $f\left ({x}\right )$ 的图象的对称中心的坐标为 $\left ({-\frac {1}{2}a,\frac {12a-a{^{3}}}{24}}\right )$ .
9. （法二）设 $\frac {1}{3}x{^{3}}+\frac {1}{2}ax{^{2}}+\left ({\frac {1}{4}a{^{2}}-1}\right )x=\frac {1}{3}{\left({x+s}\right)^{3}}+t\left ({x+s}\right )+h$ ，
10. 因为 $\frac {1}{3}{\left({x+s}\right)^{3}}+t\left ({x+s}\right )+h=\frac {1}{3}\left ({x{^{3}}+3sx{^{2}}+3s{^{2}}x+s{^{3}}}\right )+tx+ts+h=\frac {1}{3}x{^{3}}+sx{^{2}}+\left ({t+s{^{2}}}\right )x+ts+h+\frac {1}{3}s{^{3}}$ ，
11. 所以 $s=\frac {1}{2}a,t+s{^{2}}=\frac {1}{4}a{^{2}}-1,ts+h+\frac {1}{3}s{^{3}}=0$ ，
12. 所以 $s=\frac {1}{2}a,t=-1,h=\frac {12a-a{^{3}}}{24}$ ，
13. 令 $g\left ({x}\right )=f\left ({x-\frac {1}{2}a}\right )-\frac {12a-a{^{3}}}{24}=\frac {1}{3}x{^{3}}-x$ ，
14. 则 $g\left ({x}\right )$ 是奇函数，所以存在 $m=-\frac {1}{2}a,n=\frac {12a-a{^{3}}}{24}$ ，使得 $y=$  $f\left ({x+m}\right )-n$ 是奇函数，
15. 又奇函数的图象关于原点对称，所以 $f\left ({x}\right )$ 的图象关于点 $\left ({-\frac {1}{2}a,\frac {12a-a{^{3}}}{24}}\right )$ 对称，
16. 即 $f\left ({x}\right )$ 的图象的对称中心的坐标为 $\left ({-\frac {1}{2}a,\frac {12a-a{^{3}}}{24}}\right )$ .
17. （2） $f^{′}{\left ({x}\right )}=x{^{2}}+ax+\frac {1}{4}a{^{2}}-1=\left ({x+\frac {1}{2}a+1}\right )\left ({x+\frac {1}{2}a-1}\right )$ ，
18. 当 $f^{′}{\left ({x}\right )}=0$ 时， $x=-1-\frac {1}{2}a$ ，或 $x=1-\frac {1}{2}a$ ，
19. 当 $x<-1-\frac {1}{2}a$ ，或 $x>1-\frac {1}{2}a$ 时， $f^{′}{\left ({x}\right )}>0$ ，当 $-1-\frac {1}{2}a<x<1-\frac {1}{2}a$ 时， $f^{′}{\left ({x}\right )}<0$ ，
20. 所以 $f\left ({x}\right )$ 的单调增区间为 $\left ({-∞，-1-\frac {1}{2}a}\right )$ 与 $\left ({1-\frac {1}{2}a，+∞}\right )$ ，单调减区间为 $\left ({-1-\frac {1}{2}a，1-\frac {1}{2}a}\right )$ ，
21. 所以 $x=-1-\frac {1}{2}a$ 是 $f\left ({x}\right )$ 的极大值点，
22. 因为 $f\left ({x}\right )$ 的极大值点是 $f\left ({x}\right )$ 的一个零点，所以 $f\left ({-1-\frac {1}{2}a}\right )=0$ ，
23. 所以 $-1-\frac {1}{2}a=0$ ，或 $\frac {1}{3}{\left({-1-\frac {1}{2}a}\right)^{2}}+\frac {1}{2}a\left ({-1-\frac {1}{2}a}\right )+\frac {1}{4}a{^{2}}-1=0$ ，
24. 所以 $a=-2$ ，或 $a=4$ .
25. 当 $a=-2$ 时， $f\left ({x}\right )=\frac {1}{3}x{^{3}}-x{^{2}},f^{′}{\left ({x}\right )}=x\left ({x-2}\right ),f\left ({x}\right )$ 的极大值点为 ${\rm 0，}f\left ({x}\right )$ 有两个零点0与3，
26. 当 $a=4$ 时， $f\left ({x}\right )=\frac {1}{3}x{^{3}}+2x{^{2}}+3x,f^{′}{\left ({x}\right )}=x{^{2}}+4x+3=\left ({x+3}\right )\left ({x+1}\right ),f\left ({x}\right )$ 的极大值点为 $-3,f\left ({x}\right )$ 有两个零点−3与0，
27. 所以 $a$ 的值为 $-2$ 或4，当 $a=-2$ 时， $f\left ({x}\right )$ 所有零点的和为3，当 $a=4$ 时， $f\left ({x}\right )$ 所有零点的和为 $-3$ .

## 知识点

**中文**:
  - 函数奇偶性的应用
  - 函数对称性
  - 利用导数解决函数零点问题

**English**:
  - Applications of Parity
  - Symmetry of Functions
  - Solving Zero Point Problems

---
