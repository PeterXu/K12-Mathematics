# Mathematics - 题目 3722

**ID**: f400b25bee4d4f52b3d4f7013009fda0
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知函数 $f\left ({x}\right )=x-{\rm{l}}{\rm{n}}x-m$ ．（1）若 $f\left ({x}\right )$ 有两个零点 $x{{}_{1}},x{{}_{2}}$ ，且 $x{{}_{2}}>x{{}_{1}}$ ，求 $m$ 的取值范围；​​​​​​​‌（2）在（1）的条件下，求证： $x{{}_{1}}+x{{}_{2}}>\frac {2\left ({m-1}\right )}{{\rm{l}}{\rm{n}}m}$ ．

## 解答

1. （1） $f^{′}{\left ({x}\right )}=\frac {x-1}{x}$ ，
2. 当 $0<x<1$ 时， $f^{′}{\left ({x}\right )}<0$ ，当 $x>1$ 时， $f^{′}{\left ({x}\right )}>0$ ，
3. 故 $f\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上为单调递减，在 $\left ({1,+∞}\right )$ 上为单调递增，
4. 因为 $f\left ({x}\right )$ 有两个零点 $x{{}_{1}},x{{}_{2}}$ ，故 $f\left ({x}\right ){{}_{{\rm \min }}}=f\left ({1}\right )=1-m<0$ ，故 $m>1$ .
5. 当 $m>1$ 时， $f\left ({{\rm{e}}{^{-m}}}\right )={\rm{e}}{^{-m}}>0$ ，而 $f\left ({{\rm{e}}{^{m}}}\right )={\rm{e}}{^{m}}-2m$ ，
6. 设 $s\left ({x}\right )={\rm{e}}{^{x}}-2x,x>1$ ，则 $s^{′}{\left ({x}\right )}={\rm{e}}{^{x}}-2>0$ ，故 $s\left ({x}\right )$ 在 $\left ({1,+∞}\right )$ 上为增函数，
7. 故 $s\left ({x}\right )>s\left ({1}\right )={\rm{e}}-2>0$ ，故 $f\left ({{\rm{e}}{^{m}}}\right )>0$ ，
8. 而 ${\rm{e}}{^{-m}}<1<{\rm{e}}{^{m}}$ ，故当 $m>1$ 时， $f\left ({x}\right )$ 确有两个实数根，
9. 综上， $m>1$ .
10. （2）由（1）可得 $0<x{{}_{1}}<1<x{{}_{2}}$ ，
11. 先证明： $x{{}_{1}}+x{{}_{2}}>m+1$ ，即证 $x{{}_{2}}>m+1-x{{}_{1}}$ ，
12. 而 $x{{}_{2}}>m+1-x{{}_{1}}>1$ ，故即证 $f\left ({x{{}_{2}}}\right )>f\left ({m+1-x{{}_{1}}}\right )$ ，
13. 而 $f\left ({x{{}_{1}}}\right )=f\left ({x{{}_{2}}}\right )=0$ ，故即证 $m+1-x{{}_{1}}-{\ln}\left ({m+1-x{{}_{1}}}\right )-m<0$ ，
14. 即证 $1-x{{}_{1}}-{\ln}\left ({m+1-x{{}_{1}}}\right )<0$ ，而 $x{{}_{1}}-{\ln}x{{}_{1}}=m$ ，
15. 故即证： $1-x{{}_{1}}-{\ln}\left ({1-{\ln}x{{}_{1}}}\right )<0$ ，
16. 设 $s\left ({x}\right )=1-x-{\ln}(1-{\ln}x),0<x<1$ ，则 $s^{′}{\left ({x}\right )}=\frac {\frac {1}{x}+{\ln}x-1}{1-{\ln}x}$ ，
17. 设 $t\left ({x}\right )=\frac {1}{x}+{\ln}x-1,0<x<1$ ，则 $t^{′}{\left ({x}\right )}=\frac {x-1}{x{^{2}}}<0$ ，
18. 故 $t\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上为减函数，故 $t\left ({x}\right )>t\left ({1}\right )=0$ ，
19. 故 $s\left ({x}\right )$ 在 $\left ({0,1}\right )$ 上为增函数，故 $s\left ({x}\right )<s\left ({1}\right )=0$ 即 $1-x{{}_{1}}-{\ln}\left ({1-{\ln}x{{}_{1}}}\right )<0$ 成立，
20. 故 $x{{}_{1}}+x{{}_{2}}>m+1$ .
21. 设 $v\left ({m}\right )={\ln}m-\frac {2\left ({m-1}\right )}{m+1},m>1$ ，则 $v^{′}{\left ({m}\right )}=\frac {{\left({m-1}\right)^{2}}}{m{\left({m+1}\right)^{2}}}>0$ ，
22. 故 $v\left ({m}\right )$ 在 $\left ({1,+∞}\right )$ 上为增函数，故 $v\left ({m}\right )>v\left ({1}\right )=0$ ，
23. 故 ${\ln}m>\frac {2\left ({m-1}\right )}{m+1}\left ({m>1}\right )$ ，故 $m+1>\frac {2\left ({m-1}\right )}{{\ln}m}\left ({m>1}\right )$ ，
24. 故 $x{{}_{1}}+x{{}_{2}}>\frac {2\left ({m-1}\right )}{{\rm{l}}{\rm{n}}m}$  .

## 知识点

**中文**:
  - 利用导数解决函数零点问题
  - 利用导数证明不等式

**English**:
  - Solving Zero Point Problems
  - Proving Inequalities using Derivatives

---
