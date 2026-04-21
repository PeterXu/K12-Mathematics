# Mathematics - 题目 2452

**ID**: 46d9ae2e9fcf447cb384dd5daaf638a1
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Multiple-select

## 题目
设函数 $f(x)=\frac {x}{{\ln}x}-ax$ ，若函数 $f(x)$ 有两个极值点，则实数a的值可以是（      ）​​​​​​​‌

## 解答

1. 函数 $f(x)=\frac {x}{{\ln}x}-ax$ 的定义域为 $(0,1)\cup (1,+\infty )$ ，求导得 $f^{′}(x)=\frac {{\ln}x-1}{({\ln}x)^{2}}-a$ ，
2. 因为函数 $f(x)$ 有两个极值点，则方程 $f^{′}(x)=0$ ，即 $a=\frac {{\ln}x-1}{({\ln}x)^{2}}$ 在 $(0,1)\cup (1,+\infty )$ 内有两个变号零点，
3. 令 $t={\ln}x$ ， $x\in (0,1)\cup (1,+\infty )$ ，则 $t\in (-\infty ,0)\cup (0,+\infty )$ ，令 $g(t)=\frac {t-1}{t^{2}}=-(\frac {1}{t}-\frac {1}{2})^{2}+\frac {1}{4}$ ，
4. 当 $t<0$ 时， $\frac {1}{t}<0$ ， $g(t)$ 的取值集合是 $(-\infty ,0)$ ，当 $t>0$ 时， $\frac {1}{t}>0$ ，
5. 若 $0<\frac {1}{t}\leqslant \frac {1}{2}$ ，即 $t\geqslant 2$ ，函数 $y=-(\frac {1}{t}-\frac {1}{2})^{2}+\frac {1}{4}$ 对 $\frac {1}{t}\in (0,\frac {1}{2}]$ 单调递增， $g(t)$ 的取值集合是 $(0,\frac {1}{4}]$ ，
6. 若 $\frac {1}{t}\geqslant \frac {1}{2}$ ，即 $0<t\leqslant 2$ ，函数 $y=-(\frac {1}{t}-\frac {1}{2})^{2}+\frac {1}{4}$ 对 $\frac {1}{t}\in [\frac {1}{2},+\infty )$ 单调递减， $g(t)$ 的取值集合是 $(-\infty ,\frac {1}{4}]$ ，
7. 依题意，方程 $a=g(t)$ 在 $t\in (-\infty ,0)\cup (0,+\infty )$ 内有两个不等实根，即直线 $y=a$ 与函数 $y=g(t),t\ne 0$ 的图象有两个公共点，
8. 在同一坐标系内作出直线 $y=a$ 与函数 $y=g(t),t\ne 0$ 的部分图象，如图，
9. 
10. 观察图象知，当 $a{\rm{<}}{\rm{0}}$ 或 $0<{\rm{a}}<\frac {1}{4}$ 时，直线 $y=a$ 与函数 $y=g(t),t\ne 0$ 的图象有两个公共点，
11. 于是当 $a{\rm{<}}{\rm{0}}$ 或 $0<{\rm{a}}<\frac {1}{4}$ 时， $a=\frac {{\ln}x-1}{({\ln}x)^{2}}$ 在 $(0,1)\cup (1,+\infty )$ 内有两个变号零点，
12. 所以实数a的取值范围是 $a{\rm{<}}{\rm{0}}$ 或 $0<{\rm{a}}<\frac {1}{4}$ ，即a的值可以是 $\frac {1}{8}$ ， $-\frac {1}{4}$ ，选项AC不满足，BD正确.
13. 故选：BD

## 知识点

**中文**:
  - 利用导数求函数中的参数
  - 利用导数研究函数的极值

**English**:
  - Finding Parameters using Derivatives
  - Extrema of Functions using Derivatives

---
