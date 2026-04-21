# Mathematics - 题目 3584

**ID**: 95bbd6b9db5b42cf8f8f5e7eb3740e64
**年级**: Grade 10
**难度**: Medium
**题型**: Fill-in-the-blank

## 题目
已知函数 $f(x)=\left \{\hspace{-0.​​​​​​​‌5em}\begin{array}{l}\left |{x+4}\right |-2,x<-2\\2f(x-4),x\geqslant -2\end{array}\hspace{-0.5em}\right.$ .记 $\sum \limits_{i=1}^{n}\mathop{a{{}_{i}}}=a{{}_{1}}+a{{}_{2}}+\cdots +a{{}_{n}}$ ，则（1） $f(2025)=$；（2）若函数 $y=f(x)-t$ （t为常数）在 $(-\infty ,10)$ 上有8个零点 $x{{}_{i}}(i=1,2,3,\cdots ,8)$ ，则 $\sum \limits_{i=1}^{8}\mathop{x{{}_{i}}}f\left ({x{{}_{i}}}\right )$ 的取值范围为.

## 解答

1. 当 $n=1$ 时， $f\left ({x}\right )=2{^{1}}f\left ({x-4\times 1}\right )$ ；假设当 $n=k$ 时， $f\left ({x}\right )=2{^{k}}f\left ({x-4k}\right )$ ；
2. 当 $n=k+1$ 时， $2{^{k+1}}f\left [x-4\left ({k+1}\right )\right ]=2\times \left [2{^{k}}f\left ({x-4-4k}\right )\right ]=2f\left ({x-4}\right )=f\left ({x}\right )$ .
3. 根据数学归纳法，可得 $n\in {\rm{N}}{^{*}}$ ， $f\left ({x}\right )=2{^{n}}f\left ({x-4n}\right )$ 在 $\left [{-2,+\infty }\right )$ 上恒成立.
4. $f\left ({2025}\right )=f\left ({-3+4\times 507}\right )=2{^{507}}f\left ({2025-4\times 507}\right )=2{^{507}}f\left ({-3}\right )$
5. $=2{^{507}}\left ({\left |{-3+4}\right |-2}\right )=-2{^{507}}$ ，
6. 由题意可得 $f\left ({x{{}_{i}}}\right )=t$ （ $i=1,2,3,\cdots ,8$ ），
7. 则可得 $x{{}_{i}}$ （ $i=1,2,3,\cdots ,8$ ）为函数 $f\left ({x}\right )$ 的图象与直线 $y=t$ 在 $x\in \left ({0,10}\right )$ 上交点的横坐标，如下图：
8. 
9. 由图可得 $t\in \left ({-2,0}\right )$ ，
10. 当 $x\in \left ({-6,-2}\right )$ 时，显然当 $-4-m\in \left ({-6,-2}\right )$ 时，可得 $-4-m\in \left ({-6,-2}\right )$ ，
11. $f\left ({-4-m}\right )=\left |{-4-m+4}\right |-2=\left |{-4+m+4}\right |-2=f\left ({-4+m}\right )$ ，
12. 结合图象，函数 $f\left ({x}\right )$ 的图象在 $x\in \left ({-6,-2}\right )$ 上关于直线 $x=-4$ 对称，
13. 由题意同理可得，函数 $f\left ({x}\right )$ 的图象在 $x\in \left ({-2,2}\right )$ 上关于直线 $x=0$ 对称，
14. 函数 $f\left ({x}\right )$ 的图象在 $x\in \left ({2,6}\right )$ 上关于直线 $x=4$ 对称，
15. 函数 $f\left ({x}\right )$ 的图象在 $x\in \left ({6,10}\right )$ 上关于直线 $x=8$ 对称，
16. 不妨设 $x{{}_{1}}<x{{}_{2}}<x{{}_{3}}<x{{}_{4}}<x{{}_{5}}<x{{}_{6}}<x{{}_{7}}<x{{}_{8}}$ ，
17. 则 $x{{}_{1}}+x{{}_{2}}=-8$ ， $x{{}_{3}}+x{{}_{4}}=0$ ， $x{{}_{5}}+x{{}_{6}}=8$ ， $x{{}_{7}}+x{{}_{8}}=16$ ，
18. 所以 $\sum\limits_{i=1}^{8}\mathop{}x{{}_{i}}f\left ({x{{}_{i}}}\right )=t\cdot \left ({\sum\limits_{i=1}^{8}\mathop{}x{{}_{i}}}\right )=16t\in \left ({-32,0}\right )$ .
19. 故答案为： $-2{^{507}}$ ； $\left ({-32,0}\right )$ .

## 知识点

**中文**:
  - 函数图象的应用
  - 函数零点与其对应方程根的关系

**English**:
  - Applications of Function Graphs
  - Relationship between Zero Points and Equation Roots

---
