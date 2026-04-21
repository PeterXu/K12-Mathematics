# Mathematics - 题目 431

**ID**: 3ee79ee3323b45abae36ad32f93868f6
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Multiple-choice

## 题目
已知 $a>\frac {1}{2}$ 且 $2a={\rm{e}}{^{a-\frac {1}{2}}}$ ， $b>\frac {1}{3}$ 且 $3b={\rm{e}}{^{b-\frac {1}{3}}}$ ， $c>\frac {1}{4}$ 且 $4c={\rm{e}}{^{c-\frac {1}{4}}}$ ，则（      ）​​​​​​​‌

## 解答

1. 由已知条件，对于 $2a={\rm{e}}{^{a-\frac {1}{2}}}$ ，两边同取对数，
2. 则有 ${\ln}2+{\ln}a=a-\frac {1}{2}$ ，即 $a-{\ln}a=\frac {1}{2}+{\ln}2=\frac {1}{2}-{\ln}\frac {1}{2}$ ，
3. 同理： $b-{\ln}b=\frac {1}{3}-{\ln}\frac {1}{3}$ ； $c-{\ln}c=\frac {1}{4}-{\ln}\frac {1}{4}$
4. 构造函数 $f\left ({x}\right )=x-{\ln}x$ ，
5. 则 $f\left ({a}\right )=f\left ({\frac {1}{2}}\right )$ ， $f\left ({b}\right )=f\left ({\frac {1}{3}}\right )$ ， $f\left ({c}\right )=f\left ({\frac {1}{4}}\right )$
6. 对其求导得： $f^{′}{\left ({x}\right )}=\frac {x-1}{x}\left ({x>0}\right )$
7. $\therefore $ 当 $0<x<1$ 时， $f^{′}{\left ({x}\right )}<0$ ， $f\left ({x}\right )$ 单调递减；
8. 当 $x>1$ 时， $f^{′}{\left ({x}\right )}>0$ ， $f\left ({x}\right )$ 单调递增；
9. 又 $\because $  $a>\frac {1}{2}$ ， $b>\frac {1}{3}$ ， $c>\frac {1}{4}$
10. $\therefore 1<a<b<c$
11. 再构造函数 $g\left ({x}\right )=x{\ln}x$ ，对其求导得：
12. $g^{′}{\left ({x}\right )}={\ln}x+1\left ({x>0}\right )$
13. $\therefore $ 当 $0<x<\frac {1}{e}$ 时， $g^{′}{\left ({x}\right )}<0$ ， $g\left ({x}\right )$ 单调递减；
14. 当 $x>\frac {1}{e}$ 时， $g^{′}{\left ({x}\right )}>0$ ， $g\left ({x}\right )$ 单调递增；
15. $\therefore g\left ({a}\right )<g\left ({b}\right )<g\left ({c}\right )$
16. 即： $a{\ln}a<b{\ln}b<c{\ln}c$
17. 又 $\because abc>0$
18. $\therefore \frac {{\ln}a}{bc}<\frac {{\ln}b}{ac}<\frac {{\ln}c}{ab}$
19. 故选：A.

## 知识点

**中文**:
  - 利用导数证明不等式

**English**:
  - Proving Inequalities using Derivatives

---
