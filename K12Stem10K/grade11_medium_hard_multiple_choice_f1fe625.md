# Mathematics - 题目 1522

**ID**: f1fe6259585a4971b6af6ea88eb6389a
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Multiple-choice

## 题目
已知甲盒中有a个黑球和b个白球 $(a,b\geqslant 3)$ ，乙盒中有1个球且为黑球.​​​​​​​‌从甲盒中随机抽取n个球放入乙盒中（ $1\leqslant n\leqslant a+b$ ）.记此时乙盒中含有的黑球个数为 $X{{}_{n}}$ ，从乙盒中随机抽取1球为黑球的概率是 $p{{}_{n}}$ ，则（      ）

## 解答

1. 从甲盒中随机抽取n个球，这n个球中黑球的个数设为 $Y$ ，
2. $Y$ 服从超几何分布，且 $P\left ({Y=k}\right )=\frac {{\rm{C}}{{}_{a}^{k}}{\rm{C}}{{}_{b}^{n-k}}}{{\rm{C}}{{}_{a+b}^{n}}}\left ({k=0,1,2,\cdots }\right )$ ，
3. 乙盒中有1个球且为黑球，放入n个球后， $X{{}_{n}}=1+Y$ ，
4. 因为 $E\left ({Y}\right )=n\cdot \frac {a}{a+b}$ ，所以 $E\left [X{{}_{n}}\right ]=E\left ({1+Y}\right )=1+E\left ({Y}\right )=1+n\cdot \frac {a}{a+b}$ ，
5. 因为 $a>0,a+b>0$ ，所以当 $n$ 从 $1$ 增加到 $a+b$ 时，
6. $n\cdot \frac {a}{a+b}$ 随 $n$ 的增大而增大，所以数列 $\left \{E\left [X{{}_{n}}\right ]\right \}$ 严格增；
7. 从乙盒中随机抽取1球为黑球的概率是 $p{{}_{n}}$ ，乙盒中此时有 $n+1$ 个球，黑球有 $X{{}_{n}}$ 个，
8. 所以 $p{{}_{n}}=\frac {E\left [X{{}_{n}}\right ]}{n+1}=\frac {1+n\cdot \frac {a}{a+b}}{n+1}=\frac {\frac {a}{a+b}\left ({\frac {a+b}{a}+n}\right )}{n+1}$
9. $=\frac {a}{a+b}\frac {\left ({n+1+\frac {b}{a}}\right )}{n+1}=\frac {a}{a+b}\left ({1+\frac {\frac {b}{a}}{n+1}}\right )$ ，
10. 因为 $a>0,a+b>0$ ，所以当 $n$ 从 $1$ 增加到 $a+b$ 时，
11. $\frac {\frac {b}{a}}{n+1}$ 单调递减，所以 $\left \{p{{}_{n}}\right \}$ 严格减.
12. 故选B.

## 知识点

**中文**:
  - 超几何分布

**English**:
  - Hypergeometric Distribution

---
