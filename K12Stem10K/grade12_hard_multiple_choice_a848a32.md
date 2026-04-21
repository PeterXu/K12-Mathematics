# Mathematics - 题目 541

**ID**: a848a32dc54f4cba813fd5a4436a85f9
**年级**: Grade 12
**难度**: Hard
**题型**: Multiple-choice

## 题目
如果 $y=f\left ({x}\right )\left ({x\in \left [0,1\right ]}\right )$ 同时满足以下三个条件：① $f\left ({1}\right )=1$ ；②对任意 $x\in \left [0,1\right ]$ ， $f\left ({x}\right )\geqslant 0$ 成立；③当 $x{{}_{1}}\geqslant 0$ ， $x{{}_{2}}\geqslant 0$ ， $x{{}_{1}}+x{{}_{2}}\leqslant 1$ 时，总有 $f\left ({x{{}_{1}}}\right )+f\left ({x{{}_{2}}}\right )\leqslant f\left ({x{{}_{1}}+x{{}_{2}}}\right )$ 成立，则称 $y=f\left ({x}\right )$ 为“理想函数”.​​​​​​​‌有下列两个命题：命题 $α$ ：若 $y=f\left ({x}\right )$ 为“理想函数”，则存在 $x{{}_{1}},x{{}_{2}}\in \left [0,1\right ]$ 且 $x{{}_{1}}<x{{}_{2}}$ ，使 $f\left ({x{{}_{1}}}\right )>f\left ({x{{}_{2}}}\right )$ 成立；命题 $β$ ：若 $y=f\left ({x}\right )$ 为“理想函数”，则对任意 $x\in \left [0,1\right ]$ ，都有 $f\left ({x}\right )\leqslant 2x$ 成立.则下列说法正确的是（      ）

## 解答

1. 令 $1\geqslant X{{}_{2}}=x{{}_{1}}+x{{}_{2}}>$  $X{{}_{1}}=x{{}_{1}}\geqslant 0$ ，则 $x{{}_{2}}=X{{}_{2}}-X{{}_{1}}\in (0,1]$ ，
2. 所以 $f\left ({X{{}_{1}}}\right )+f\left ({X{{}_{2}}-X{{}_{1}}}\right )\leqslant f\left ({X{{}_{2}}}\right )\Rightarrow f\left ({X{{}_{2}}}\right )-f\left ({X{{}_{1}}}\right )\geqslant f\left ({X{{}_{2}}-X{{}_{1}}}\right )$ ，
3. 又对任意 $x\in \left [0,1\right ],f\left ({x}\right )\geqslant 0$ 成立，则 $f(x{{}_{2}})=f\left ({X{{}_{2}}-X{{}_{1}}}\right )\geqslant 0$ ，即 $f\left ({X{{}_{2}}}\right )-f\left ({X{{}_{1}}}\right )\geqslant 0$ ，
4. 所以 $f\left ({X{{}_{2}}}\right )\geqslant f\left ({X{{}_{1}}}\right )$ ，即对任意 $0\leqslant x{{}_{1}}<x{{}_{2}}\leqslant 1$ ，都有 $f\left ({x{{}_{1}}}\right )\leqslant f\left ({x{{}_{2}}}\right )$ ，命题 $α$ 为假命题；
5. 由命题 $α$ 为假，即 $f\left ({x}\right )$ 在 $x\in \left [0,1\right ]$ 上非单调递减，有单调递增趋势的函数(不一定严格单调递增)，令 $x{{}_{1}}=x{{}_{2}}=0$ ，则 $2f\left ({0}\right )\leqslant f\left ({0}\right )\Rightarrow f(0)\leqslant 0$ ，而任意 $x\in \left [0,1\right ],f\left ({x}\right )\geqslant 0$ 成立；
6. 所以 $f(0)=0$ ，又 $f\left ({1}\right )=1$ ，故 $f\left ({x}\right )\in [0,1]$ ，
7. 反证法：若 $f\left ({x}\right )$ 为“理想函数”，存在 $x{{}_{0}}\in \left [0,1\right ]$ ，使 $f\left ({x{{}_{0}}}\right )>2x{{}_{0}}$ 成立，
8. 对于 $x\in \left [\frac {1}{2},1\right ]$ ， $f\left ({x}\right )\mathrm{\leqslant }1$ ，而 $2x\geqslant 1$ ，此时不存在 $x{{}_{0}}\in \left [\frac {1}{2},1\right ]$ 使 $f\left ({x{{}_{0}}}\right )>2x{{}_{0}}$ 成立；
9. 对于 $x\in [0,\frac {1}{2})$ ，若存在 $x{{}_{0}}\in [0,\frac {1}{2})$ 使 $f\left ({x{{}_{0}}}\right )>2x{{}_{0}}$ 成立，则 $f(f\left ({x{{}_{0}}}\right ))>f(2x{{}_{0}})$ ，
10. 而 $2x{{}_{0}}\in [0,1)$ ，则 $f(2x{{}_{0}})\geqslant f(x{{}_{0}})+f(x{{}_{0}})=2f(x{{}_{0}})$ ，即 $f(f\left ({x{{}_{0}}}\right ))>2f(x{{}_{0}})>4x{{}_{0}}$ ，
11. 由 $f(x{{}_{0}})$  $\in [0,1)$ ，依次类推，必有 $t\in [0,1)$ ， $f(t)>2{^{n}}x{{}_{0}}$ 且 $n\in \mathbf{N}{^{*}}$ 趋向于无穷大，
12. 此时 $f\left ({t}\right )\in [0,1)$ ，而 $2{^{n}}x{{}_{0}}$ 必然会出现大于1的情况，与 $f(t)>2{^{n}}x{{}_{0}}$ 矛盾，
13. 所以，在 $x\in [0,\frac {1}{2})$ 上也不存在 $x{{}_{0}}\in [0,\frac {1}{2})$ 使 $f\left ({x{{}_{0}}}\right )>2x{{}_{0}}$ 成立，
14. 综上，若 $f\left ({x}\right )$ 为“理想函数”，则对任意 $x\in \left [0,1\right ]$ ，都有 $f\left ({x}\right )\leqslant 2x$ 成立，命题 $β$ 为真命题；
15. 故选A.

## 知识点

**中文**:
  - 与函数有关的恒成立问题
  - 函数新定义问题

**English**:
  - Universally True Problems Related to Functions
  - New Definition Problems in Functions

---
