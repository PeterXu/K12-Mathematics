# Mathematics - 题目 349

**ID**: 3b8eca8739014e68bbdc867dcbf20c24
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
法国数学家拉格朗日于1778年在其著作《解析函数论》中提出一个定理：如果函数 $y=f(x)$ 满足如下条件：① $f(x)$ 的图象在闭区间 $\left [a,b\right ]$ 上是连续不断的；② $f(x)$ 在区间 $(a,b)$ 上都有导数.​​​​​​​‌则在区间 $(a,b)$ 上至少存在一个数 $m$ ，使得 $f(b)-f(a)=f^{′}(m)(b-a)$ .这就是著名的“拉格朗日中值定理”，其中 $m$ 称为拉格朗日中值.请阅读以上内容，回答以下问题:（1）函数 $y=\frac {1}{x}$ 在区间 $\left [\frac {1}{2},2\right ]$ 上的拉格朗日中值 $m$ 为；（2）下列函数，是否存在以0为拉格朗日中值的区间 $(a,b)$ ?若存在，请将函数对应的序号全部填在横线上.① $y=x{^{2}}-1$ ；    ② $y=x{^{3}}$ ；    ③ $y={\rm{e}}{^{x}}-1$ ；    ④ $y=\sin x$ ；    ⑤ $y={\ln}(x+1)$ .

## 解答

1. （1）由题意知 $y=f(x)=\frac {1}{x}$ 在区间 $\left [\frac {1}{2},2\right ]$ 上的拉格朗日中值为 $m$ ，
2. 所以 $f{^{\mathrm{′}}}(x)=-\frac {1}{x{^{2}}}$ ， $f(2)=\frac {1}{2}$ ， $f(\frac {1}{2})=2$ ，
3. 根据“拉格朗日中值定理”可得 $f(2)-f(\frac {1}{2})=-\frac {1}{m{^{2}}}(2-\frac {1}{2})$ ，解得 $m=\pm 1$ ，又因为 $m\in \left [\frac {1}{2},2\right ]$ ，
4. 故 $m=1$ .
5. （2）根据题意知① $y=f\left ({x}\right )=x{^{2}}-1$ ，故 $f^{′}{\left ({x}\right )}=2x$ ，
6. 所以 $f(b)-f(a)=f^{′}(m)(b-a)$ ，代入可得 $b{^{2}}-a{^{2}}=2m(b-a)$ ，
7. 若 $m=0$ ，则 $b{^{2}}-a{^{2}}=0$ ，即 $a=-b$ ，存在区间 $(-b,b)$ ；
8. 根据题意知② $y=f\left ({x}\right )=x{^{3}}$ ，故 $f^{′}{\left ({x}\right )}=3x{^{2}}$ ，
9. 所以 $f(b)-f(a)=f^{′}(m)(b-a)$ ，代入 $b{^{3}}-a{^{3}}=3m{^{2}}(b-a)$ ，
10. 若 $m=0$ ，则 $b{^{3}}-a{^{3}}=0$ ，即 $a=b$ ，不存在以0为拉格朗日中值的区间；
11. 根据题意知③ $y=f\left ({x}\right )={\rm{e}}{^{x}}-1$ ，故 $f^{′}{\left ({x}\right )}={\rm{e}}{^{x}}$ ，
12. 所以 $f(b)-f(a)=f^{′}(m)(b-a)$ ，代入可得 ${\rm{e}}{^{b}}-{\rm{e}}{^{a}}=f^{′}{\left ({m}\right )}\left ({b-a}\right )$ ，
13. 若 $m=0$ ，则 ${\rm{e}}{^{b}}-{\rm{e}}{^{a}}=b-a$ ，变形可得 ${\rm{e}}{^{b}}-b={\rm{e}}{^{a}}-a$ ，
14. 可设 $g\left ({x}\right ){\rm{=}}{\rm{e}}{^{x}}-x$ ，即 $g\left ({b}\right ){\rm{=}}{\rm{e}}{^{b}}-b=g\left ({a}\right )={\rm{e}}{^{a}}-a$ ，则 $g^{′}{\left ({x}\right )}{\rm{=}}{\rm{e}}{^{x}}-1$ ，令 $g^{′}{\left ({x}\right )}{\rm{=}}{\rm{e}}{^{x}}-1=0$ 可得 $x=0$ ，
15. 当 $x<0$ 时， $g^{′}{\left ({x}\right )}<0$ ，所以 $g\left ({x}\right )$ 单调递减，
16. 当 $x>0$ 时， $g^{′}{\left ({x}\right )}>0$ ，所以 $g\left ({x}\right )$ 单调递增，
17. $g{{}_{{\rm \min }}}\left ({x}\right )=g\left ({0}\right )=1$ ， $g\left ({x}\right )$ 连续不间断函数，所以存在 $a<0<b$ 使得 $g\left ({b}\right ){\rm{=}}g\left ({a}\right )$ ，
18. 故存在 $(a,b)$ ；
19. 根据题意知④ $y=\sin x$ ， $f^{′}{\left ({x}\right )}={\cos}x$ ，
20. $f(b)-f(a)=f^{′}(m)(b-a)$ ，代入 $\sin b-\sin a={\cos}m(b-a)$ ，
21. 若 $m=0$ ，则 $\sin b-\sin a=b-a$ ，变形可得 $\sin b-b=\sin a-a$ ，
22. 可设 $F\left ({x}\right ){\rm{=}}\sin x-x$ ， $F^{′}{\left ({x}\right )}{\rm{=}}{\cos}x-1$ ，则 $F^{′}{\left ({x}\right )}{\rm{=}}{\cos}x-1\leqslant 0$ ，所以 $F\left ({x}\right ){\rm{=}}\sin x-x$ 单调递减，
23. 故不存在 $(a,b)$ ；
24. 根据题意知⑤ $y=f\left ({x}\right )={\ln}(x+1)$ ，故 $f^{′}{\left ({x}\right )}=\frac {1}{x+1}$ ，
25. 所以 $f(b)-f(a)=f^{′}(m)(b-a)$ ，代入 ${\ln}(b+1)-{\ln}(a+1)=b-a$ ，
26. 变形可得 ${\ln}(b+1)-b={\ln}(a+1)-a$ ，可设 $u\left ({x}\right )={\ln}(x+1)-x$ ， $u^{′}{\left ({x}\right )}=\frac {1}{x+1}-1$ ，
27. 令 $u^{′}{\left ({x}\right )}=\frac {1}{x+1}-1=0$ ，可得 $x=0$ ，
28. 当 $-1<x<0$ 时， $u^{′}{\left ({x}\right )}>0$ ，则 $u\left ({x}\right )$ 单调递增，
29. 当 $x>0$ 时， $u^{′}{\left ({x}\right )}<0$ ，则 $u\left ({x}\right )$ 单调递减，
30. $u{{}_{{\rm \min }}}\left ({x}\right )=u(0)=0$ ， $u\left ({x}\right )$ 连续不间断函数，所以存在 $-1<a<0<b$ 使得 $u\left ({b}\right ){\rm{=}}u\left ({a}\right )$ ，
31. 存在 $(a,b)$ .
32. 故选①③⑤.

## 知识点

**中文**:
  - 利用导数解决新定义问题

**English**:
  - Solving New Definition Problems

---
