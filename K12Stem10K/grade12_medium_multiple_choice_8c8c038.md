# Mathematics - 题目 2723

**ID**: 8c8c038572af43458c0a3034f911c079
**年级**: Grade 12
**难度**: Medium
**题型**: Multiple-choice

## 题目
已知数列 $\left\{\begin{array}{l}a_{n}\end{array}\right \}$ 满足 $a_{1}+\frac {a_{2}}{2}+\frac {a_{3}}{3}+\cdots +\frac {a_{n}}{n}=2^{n+1}$ ，若数列 $\left\{\begin{array}{l}\frac {n+2}{\left ({n+1}\right )a_{n}}\end{array}\right \}$ 的前 $n$ 项和 $S_{n}$ ，对任意 $n\in {\rm{N}}^{{\rm{*}}}$ 不等式 $S_{n}<λ$ 恒成立，则实数 $λ$ 的取值范围是（      ）​​​​​​​‌

## 解答

1. $a_{1}+\frac {a_{2}}{2}+\frac {a_{3}}{3}+\cdots +\frac {a_{n}}{n}=2^{n+1}$ ①,
2. $a_{1}+\frac {a_{2}}{2}+\frac {a_{3}}{3}+\cdots +\frac {a_{n-1}}{n-1}=2^{n}$ ②,
3. 由①-②可得，当  $n\geqslant 2$  时, $\frac {a_{n}}{n}=2^{n}$ ,当 $n=1,a_{1}=2^{2}$ ,
4. 当 $n\geqslant 2$ , $\frac {n+2}{\left ({n+1}\right )a_{n}}=\frac {n+2}{\left ({n+1}\right )n\times 2^{n}}=2\left ({\frac {1}{n\times 2^{n}}-\frac {1}{\left ({n+1}\right )\times 2^{n+1}}}\right )$ ,当 $n=1,$  $\frac {n+2}{\left ({n+1}\right )a_{n}}=\frac {3}{8}$ ，
5. 所以 $S_{n}=\frac {3}{8}+2\left [\left ({\frac {1}{2\times 2^{2}}-\frac {1}{3\times 2^{3}}}\right )+\cdots +\left ({\frac {1}{n\times 2^{n}}-\frac {1}{\left ({n+1}\right )\times 2^{n+1}}}\right )\right ]=\frac {3}{8}+2\left ({\frac {1}{2\times 2^{2}}-\frac {1}{\left ({n+1}\right )\times 2^{n+1}}}\right )$ ,
6. 对任意 $n\in {\rm{N}}^{{\rm{*}}}$ 不等式 $S_{n}<λ$ 恒成立,所以  $λ>\left ({S_{n}}\right )_{{\rm{m}}{\rm{a}}{\rm{x}}}$ ,
7. $S_{n}=\frac {3}{8}+2\left ({\frac {1}{2\times 2^{2}}-\frac {1}{\left ({n+1}\right )\times 2^{n+1}}}\right )<\frac {3}{8}+\frac {2}{8}=\frac {5}{8}$ .
8. 所以 $λ\geqslant \frac {5}{8}$ .
9. 故选:C.

## 知识点

**中文**:
  - 数列与不等式的综合
  - 数列求和方法之裂项相消法

**English**:
  - Sequences with Inequalities
  - Telescoping Series Method

---
