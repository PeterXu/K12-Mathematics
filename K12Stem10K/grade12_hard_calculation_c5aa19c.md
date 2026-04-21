# Mathematics - 题目 3563

**ID**: c5aa19c3437540578ffea626f6fae2d4
**年级**: Grade 12
**难度**: Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=\frac {{\ln}2x}{x-2}-ax{^{2}}\left ({a\in \mathbf{R}}\right )$ .​​​​​​​‌（1）当 $a=0$ 时，求 $f\left ({x}\right )$ 的单调区间；（2）讨论 $f\left ({x}\right )$ 的零点的个数，并确定每个零点的取值范围（不要求范围“最小”）.

## 解答

1. （1）当 $a=0$ 时， $f\left ({x}\right )=\frac {{\ln}2x}{x-2}$ ，则 $f\left ({x}\right )$ 定义域为 $\left ({0,2}\right )\cup \left ({2,+\infty }\right )$ ，
2. $\therefore $  $f^{′}{\left ({x}\right )}=\frac {\frac {x-2}{x}-{\ln}2x}{{\left({x-2}\right)^{2}}}=\frac {1-\frac {2}{x}-{\ln}2x}{{\left({x-2}\right)^{2}}}$ ，
3. 令 $g\left ({x}\right )=1-\frac {2}{x}-{\ln}2x\left ({x>0}\right )$ ，则 $g^{′}{\left ({x}\right )}=\frac {2}{x{^{2}}}-\frac {1}{x}=\frac {2-x}{x{^{2}}}$ ，
4. $\therefore $ 当 $x\in \left ({0,2}\right )$ 时， $g^{′}{\left ({x}\right )}>0$ ；当 $x\in \left ({2,+\infty }\right )$ 时， $g^{′}{\left ({x}\right )}<0$ ；
5. $\therefore $  $g\left ({x}\right )$ 在 $\left ({0,2}\right )$ 上单调递增，在 $\left ({2,+\infty }\right )$ 上单调递减，
6. $\therefore g\left ({x}\right )\leqslant g\left ({2}\right )=1-1-{\ln}4=-{\ln}4<0$ ， $\therefore f^{′}{\left ({x}\right )}<0$ ，
7. $\therefore f\left ({x}\right )$ 的单调递减区间为 $\left ({0,2}\right )$ ， $\left ({2,+\infty }\right )$ ，无单调递增区间；
8. （2）令 $h\left ({x}\right )=\frac {{\ln}2x}{x-2}$ ， $m\left ({x}\right )=ax{^{2}}$ ，且 $h\left ({x}\right ),m\left ({x}\right )$ 定义域均为 $\left ({0,2}\right )\cup \left ({2,+\infty }\right )$ ，
9. 则 $f\left ({x}\right )$ 零点个数即为 $h\left ({x}\right )$ 与 $m\left ({x}\right )$ 交点个数；
10. 由（1）知： $h\left ({x}\right )$ 在 $\left ({0,2}\right )$ ， $\left ({2,+\infty }\right )$ 上单调递减；
11. 当 $x\to 0$ 时， $h\left ({x}\right )\to +\infty $ ；当 $x$ 从负方向无限趋近 $2$ 时， $h\left ({x}\right )\to -\infty $ ；
12. 当 $x$ 从正方向无限趋近 $2$ 时， $h\left ({x}\right )\to +\infty $ ；当 $x\to +\infty $ 时， $h\left ({x}\right )→0$ 且 $h\left ({x}\right )>0$ ，
13. 由此可得 $h\left ({x}\right )$ 图象如下图所示：
14. 
15. ①当 $a=0$ 时， $m\left ({x}\right )=0$ ，由 $\frac {{\ln}2x}{x-2}=0$ 得： $x=\frac {1}{2}$ ， $\therefore f\left ({x}\right )$ 有且仅有一个零点 $x=\frac {1}{2}$ ；
16. ②当 $a>0$ 时， $m\left ({x}\right )$ 为以原点为顶点，开口方向向上的二次函数，
17. 
18. 由图象可知： $m\left ({x}\right )$ 与 $h\left ({x}\right )$ 在 $\left ({0,\frac {1}{2}}\right )$ 和 $\left ({2,+\infty }\right )$ 各有一个交点，
19. $\therefore f\left ({x}\right )$ 有两个零点，分别位于 $\left ({0,\frac {1}{2}}\right )$ 和 $\left ({2,+\infty }\right )$ 内；
20. ③当 $a<0$ 时， $m\left ({x}\right )$ 为以原点为顶点，开口方向向下的二次函数，
21. $\because h\left ({\frac {1}{2}}\right )-m\left ({\frac {1}{2}}\right )=0-\frac {1}{4}a>0$ ，当 $x$ 从负方向无限趋近 $2$ 时， $h\left ({x}\right )-m\left ({x}\right )<0$ ，
22. 则 $h\left ({x}\right )$ 与 $m\left ({x}\right )$ 在 $\left ({\frac {1}{2},2}\right )$ 上必有交点，设从左至右第一个交点横坐标为 $t$ ，
23. 则 $h\left ({t}\right )=m\left ({t}\right )$ ，即 $\frac {{\ln}2t}{t-2}=at{^{2}}$ ， $\therefore {\ln}2t=at{^{3}}-2at{^{2}}$ ，即 ${\ln}2t-at{^{3}}+2at{^{2}}=0$ ，
24. 设 $φ\left ({x}\right )={\ln}2x-ax{^{3}}+2x{^{2}}$ ，则 $φ^{′}{\left ({x}\right )}=\frac {1}{2x}-3ax{^{2}}+4x>0$ ，
25. $\therefore φ\left ({x}\right )$ 在 $\left ({0,+∞}\right )$ 上单调递增，又 $φ\left ({t}\right )=0$ ， $\therefore x=t$ 为 $φ\left ({x}\right )$ 的唯一零点，
26. 即 $h\left ({x}\right )$ 与 $m\left ({x}\right )$ 有且仅有唯一一个交点；
27. 
28. $\therefore f\left ({x}\right )$ 有唯一零点，位于 $\left ({\frac {1}{2},2}\right )$ 内；
29. 综上所述：当 $a=0$ 时， $f\left ({x}\right )$ 有唯一零点 $x=\frac {1}{2}$ ；
30. 当 $a>0$ 时， $f\left ({x}\right )$ 有两个零点，分别位于 $\left ({0,\frac {1}{2}}\right )$ 和 $\left ({2,+\infty }\right )$ 内；
31. 当 $a<0$ 时， $f\left ({x}\right )$ 有唯一零点，位于 $\left ({\frac {1}{2},2}\right )$ 内.

## 知识点

**中文**:
  - 利用导数研究函数的单调性与单调区间
  - 利用导数解决函数零点问题

**English**:
  - Monotonicity and Monotonic Intervals
  - Solving Zero Point Problems

---
