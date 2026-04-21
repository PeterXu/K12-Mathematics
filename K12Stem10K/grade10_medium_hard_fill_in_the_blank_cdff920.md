# Mathematics - 题目 385

**ID**: cdff920b30424d9d9fb0f6e745173503
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Fill-in-the-blank

## 题目
已知集合 $A=\left \{x\left |{x{^{2}}+2024x+2025=0}\right .​​​​​​​‌\right \},B=\left \{x\left |{\left ({x{^{2}}+ax}\right )\left ({x{^{2}}+4ax+4}\right )=0}\right .\right \}$ ，记非空集合 $\mathrm{S}$ 的元素个数为 $n\left ({S}\right )$ ，已知 $\left |{n\left ({A}\right )-n\left ({B}\right )}\right |=1$ ，记实数 $a$ 的所有可能取值构成的集合 $M$ ，则 $M$ 的非空子集的个数是．

## 解答

1. 对于 $x{^{2}}+2024x+2025=0$ ，有 $\Delta =2024{^{2}}-4\times 2025>0$ ，
2. 所以集合 $A=\left \{x\left |{x{^{2}}+2024x+2025=0}\right .\right \}$ 中有两个元素，即 $n\left ({A}\right )=2$ ，
3. 因为 $\left |{n\left ({A}\right )-n\left ({B}\right )}\right |=1$ ，所以 $n\left ({B}\right )=1$ 或3，
4. 对于 $\left ({x{^{2}}+ax}\right )\left ({x{^{2}}+4ax+4}\right )=0$ ，易知 $x=0$ 必是方程中的唯一解，且 $x=0$ 不是方程 $x{^{2}}+4ax+4=0$ 的根；
5. 当 $n\left ({B}\right )=1$ 时， $B=\left \{0\right \}$ ，所以 $x{^{2}}+ax=0$ 有唯一解，且 $x{^{2}}+4ax+4=0$ 无解，
6. 则 $\begin{cases}{\rm{Δ}}{{}_{1}}=a{^{2}}-4\times 0=0\\{\rm{Δ}}{{}_{2}}={\left({4a}\right)^{2}}-4\times 4<0\end{cases}$ ，解得 $a=0$ ；
7. 当 $n\left ({B}\right )=3$ 时，若 $x{^{2}}+ax=0$ 有两个相等的实数解，由上述分析可知 $a=0$ ，
8. $x{^{2}}+4ax+4=0$ 无解，不满足题意；
9. 若 $x{^{2}}+ax=0$ 有两个不相等的实数解，此时 $a\ne 0$ ，则 $x{^{2}}+4ax+4=0$ 有两个相等的实数解或有两个不相等的实数解且一解为 $-a$ ，
10. 当 $x{^{2}}+4ax+4=0$ 有两个相等的实数解时，则 $\begin{cases}{\rm{Δ}}{{}_{1}}=a{^{2}}-4\times 0>0\\{\rm{Δ}}{{}_{2}}={\left({4a}\right)^{2}}-4\times 4=0\end{cases}$ ，
11. 解得 $a=-1$ 或1；
12. 当 $x{^{2}}+4ax+4=0$ 有两个不相等的实数解且一解为 $-a$ 时，
13. 则 $a{^{2}}-4a{^{2}}+4=0$ ，解得 $a=\pm \frac {2\sqrt {3}}{3}$ ，符合题意；
14. 综上，实数 $a$ 的所有可能取值为： $-1,0,1,\frac {2\sqrt {3}}{3},-\frac {2\sqrt {3}}{3}$ ，则 $M=\left \{-1,0,1,\frac {2\sqrt {3}}{3},-\frac {2\sqrt {3}}{3}\right \}$ .
15. 所以 $M$ 的非空子集的个数 $2{^{5}}-1=31$ .

## 知识点

**中文**:
  - 与子集、真子集相关的个数问题

**English**:
  - Counting Problems Related to Subsets

---
