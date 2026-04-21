# Mathematics - 题目 1915

**ID**: 9cb905b0c891435a94d66276d8247327
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Multiple-choice

## 题目
已知函数 $f\left ({x}\right )=1-2{\sin}\left ({x+\frac {{\rm{π}}}{2}}\right ){\cos}\left ({x-\frac {{\rm{π}}}{2}}\right )$ 的图象与直线 $kx-y+1=0\left ({k>0}\right )$ ，恰有三个公共点，这三个点的横坐标分别为 $x{{}_{{{1}}}},x{{}_{2}},x{{}_{3}}\left ({x{{}_{{{1}}}}<x{{}_{2}}<x{{}_{3}}}\right )$ ，则 $\frac {{\tan}\left ({x{{}_{1}}+x{{}_{2}}-x{{}_{3}}}\right )}{x{{}_{1}}+x{{}_{2}}-x{{}_{3}}}=$ （      ）​​​​​​​‌

## 解答

1. $f\left ({x}\right )=1-2{\sin}\left ({x+\frac {{\rm{π}}}{2}}\right ){\cos}\left ({x-\frac {{\rm{π}}}{2}}\right )=1-2{\cos}x{\sin}x=1-{\sin}2x$ ，
2. 联立 $\begin{cases}y=1-{\sin}2x\\y=kx+1\end{cases}$ 可得 $kx+{\sin}2x=0$ ，从而函数 $g\left ({x}\right )=kx+{\sin}2x$ 恰有三个零点 $x{{}_{{{1}}}},x{{}_{2}},x{{}_{3}}\left ({x{{}_{{{1}}}}<x{{}_{2}}<x{{}_{3}}}\right )$ .
3. 由于 $g\left ({x}\right )$ 是奇函数，故 $x{{}_{1}}+x{{}_{3}}=x{{}_{2}}=0$ ，从而 $\frac {{\tan}\left ({x{{}_{1}}+x{{}_{2}}-x{{}_{3}}}\right )}{x{{}_{1}}+x{{}_{2}}-x{{}_{3}}}=\frac {{\tan}\left ({x{{}_{1}}-x{{}_{3}}}\right )}{x{{}_{1}}-x{{}_{3}}}=\frac {{\tan}\left ({-2x{{}_{3}}}\right )}{-2x{{}_{3}}}=\frac {{\tan}2x{{}_{3}}}{2x{{}_{3}}}$ .
4. 根据题意，可知 $g\left ({x}\right )=kx+{\sin}2x$ 在 $\left ({0,+\infty }\right )$ 上有唯一零点 $x{{}_{3}}$ .
5. 假设存在 $a>0$ ，使得 $g\left ({a}\right )<0$ ，则 ${\sin}2a=g\left ({a}\right )-ka<g\left ({a}\right )<0$ ，所以 $a>\frac {{\rm{π}}}{2}$ .
6. 而 $g\left ({\frac {{\rm{π}}}{2}}\right )=\frac {k{\rm{π}}}{2}>0$ ， $g\left ({a}\right )<0$ ， $g\left ({a+\frac {1}{k}}\right )=k\left ({a+\frac {1}{k}}\right )+{\sin}2\left ({a+\frac {1}{k}}\right )\geqslant k\left ({a+\frac {1}{k}}\right )-1=ka>0$ ，
7. 从而 $g\left ({x}\right )$ 在 $\left ({\frac {{\rm{π}}}{2},a}\right )$ 和 $\left ({a,a+\frac {1}{k}}\right )$ 上各有一个零点，故在 $\left ({0,+\infty }\right )$ 上有两个零点，矛盾.
8. 所以 $a>0$ 时必有 $g\left ({a}\right )\geqslant 0$ ，这表明 $g\left ({x}\right )$ 在 $x{{}_{3}}$ 处取得最小值 $0$ ，故 $g^{′}{\left ({x{{}_{3}}}\right )}=0$ .
9. 而 $g^{′}{\left ({x}\right )}=k+2{\cos}2x$ ，故 $k+2{\cos}2x{{}_{3}}=0$ ，即 ${\cos}2x{{}_{3}}=-\frac {k}{2}$ .
10. 所以 $\frac {{\tan}\left ({x{{}_{1}}+x{{}_{2}}-x{{}_{3}}}\right )}{x{{}_{1}}+x{{}_{2}}-x{{}_{3}}}=\frac {{\tan}2x{{}_{3}}}{2x{{}_{3}}}=\frac {{\sin}2x{{}_{3}}}{2x{{}_{3}}{\cos}2x{{}_{3}}}=\frac {-kx{{}_{3}}}{2x{{}_{3}}\cdot \left ({-\frac {k}{2}}\right )}=1$ .
11. 故选D.

## 知识点

**中文**:
  - 二倍角的正弦
  - 函数零点的存在性定理及应用
  - 正弦函数的图象及应用

**English**:
  - Double Angle Sine
  - Existence Theorem of Zero Points and Applications
  - Graph and Applications of Sine Function

---
