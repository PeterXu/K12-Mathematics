# Mathematics - 题目 2347

**ID**: f9aae30a8a2c475b86972ba990c93891
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Multiple-select

## 题目
过点 $P\left ({-1,0}\right )$ 向曲线 $C{{}_{n}}$ ： $x{^{2}}-2nx+y{^{2}}=0\left ({n\in {\mathbf{N}}{^{{\rm{*}}}}}\right )$ 引斜率为 $k{{}_{n}}\left ({k{{}_{n}}>0}\right )$ 的切线 $l{{}_{n}}$ ，切点为 $P{{}_{n}}\left ({x{{}_{n}},y{{}_{n}}}\right )$ ，则下列结论正确的是（      ）​​​​​​​‌

## 解答

1. 由题意，设直线 $l{{}_{n}}:y=k{{}_{n}}\left ({x+1}\right )$ ，
2. 联立方程 $\begin{cases}y=k{{}_{n}}\left ({x+1}\right )\\x{^{2}}-2nx+y{^{2}}=0\end{cases}$ 可得 $\left ({1+k{{}_{n}^{2}}}\right )x{^{2}}+\left ({2k{{}_{n}^{2}}-2n}\right )x+k{{}_{n}^{2}}=0$ ，
3. 则 $\Delta ={\left({2k{{}_{n}^{2}}-2n}\right)^{2}}-4k{{}_{n}^{2}}\left ({1+k{{}_{n}^{2}}}\right )=0$ ，解得 $k{{}_{n}}=\frac {n}{\sqrt {2n+1}}$ （负值舍去），
4. 所以 $x{{}_{n}}=\frac {n-k{{}_{n}^{2}}}{1+k{{}_{n}^{2}}}=\frac {n}{n+1},y{{}_{n}}=k{{}_{n}}\left ({x{{}_{n}}+1}\right )=\frac {n\sqrt {2n+1}}{n+1}$ ，故B错误；
5. 所以 $\sum \limits_{i=1}^{2025}\mathop{{\ln}x{{}_{i}}=}\sum \limits_{i=1}^{2025}\mathop{{\ln}\frac {i}{i+1}}={\ln}\frac {1}{2}+{\ln}\frac {2}{3}+\cdots +{\ln}\frac {2025}{2026}={\ln}\frac {1}{2026}=-{\ln}2026$ ，故A正确；
6. 因为 $\sqrt {\frac {1-x{{}_{n}}}{1+x{{}_{n}}}}=\sqrt {\frac {1-\frac {n}{n+1}}{1+\frac {n}{n+1}}}=\sqrt {\frac {1}{2n+1}}$ ，
7. 又因为 $4n{^{2}}>4n{^{2}}-1$ ，则 $\frac {2n-1}{4n{^{2}}}<\frac {2n-1}{4n{^{2}}-1}=\frac {1}{2n+1}$ ，即 $\frac {{\left({2n-1}\right)^{2}}}{4n{^{2}}}<\frac {2n-1}{2n+1}$ ，所以 $\frac {2n-1}{2n}<\sqrt {\frac {2n-1}{2n+1}}$ ，
8. 则 $x{{}_{1}}\cdot x{{}_{3}}\cdot x{{}_{5}}\cdot \cdot \cdot x{{}_{2n-1}}=\frac {1}{2}\times \frac {3}{4}\times \cdots \times \frac {2n-1}{2n}<\sqrt {\frac {1}{3}\times \frac {3}{5}\times \cdots \times \frac {2n-1}{2n+1}}=\sqrt {\frac {1}{2n+1}}=\sqrt {\frac {1-x{{}_{n}}}{1+x{{}_{n}}}}$ ，故C正确；
9. 因为 $\frac {x{{}_{n}}}{y{{}_{n}}}=\frac {n}{n+1}\times \frac {n+1}{n\sqrt {2n+1}}=\sqrt {\frac {1}{2n+1}}$ ，所以 $\frac {x{{}_{n}}}{y{{}_{n}}}=\sqrt {\frac {1-x{{}_{n}}}{1+x{{}_{n}}}}$ ，且 $0<\sqrt {\frac {1}{2n+1}}<1$ ，
10. 设函数 $f\left ({x}\right )=x-\sin x,x\in \left ({0,1}\right )$ ，则 $f^{′}{\left ({x}\right )}=1-{\cos}x>0$ ，所以函数 $f\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上单调递增，
11. 则 $f\left ({x}\right )>f\left ({0}\right )=0$ ，即 $x>\sin x$ ，所以 $\frac {x{{}_{n}}}{y{{}_{n}}}>{\rm{s}}{\rm{i}}{\rm{n}}\sqrt {\frac {1-x{{}_{n}}}{1+x{{}_{n}}}}$ ，故D正确.
12. 故选ACD.

## 知识点

**中文**:
  - 直线与圆相切及圆的切线方程

**English**:
  - Tangency and Tangent Equations

---
