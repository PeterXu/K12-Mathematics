# Mathematics - 题目 2703

**ID**: c3d8cf45351c46ecb22753fe2dc14719
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
若实数 $x,y\in \left [0,2{\rm{\mathrm{π}}}\right ]$ ，且满足 ${\rm{c}}{\rm{o}}{\rm{s}}\left ({x+y}\right )={\rm{c}}{\rm{o}}{\rm{s}}x+{\rm{c}}{\rm{o}}{\rm{s}}y$ ，则称 $x,y$ 是“余弦相关”的．（1）若 $x=\frac {{\rm{\mathrm{π}}}}{2}$ ，求出所有与之“余弦相关”的实数 $y$ ；​​​​​​​‌（2）若实数 $x,y$ 是“余弦相关”的，求 ${\rm{c}}{\rm{o}}{\rm{s}}x$ 的取值范围；（3）若不相等的两个实数 $x,y$ 是“余弦相关”的，求证：存在实数 $z$ ，使得 $x,z$ 为“余弦相关”的， $y,z$ 也为“余弦相关”的．

## 解答

1. （1） $x=\frac {{\rm{\mathrm{π}}}}{2}$ 代入得， ${\rm{c}}{\rm{o}}{\rm{s}}\left ({\frac {{\rm{\mathrm{π}}}}{2}+y}\right )={\rm{c}}{\rm{o}}{\rm{s}}\frac {{\rm{\mathrm{π}}}}{2}+{\rm{c}}{\rm{o}}{\rm{s}}y$ ，
2. 即 ${\rm{c}}{\rm{o}}{\rm{s}}\frac {{\rm{\mathrm{π}}}}{2}{\cos}y-\sin \frac {{\rm{\mathrm{π}}}}{2}\sin y={\rm{c}}{\rm{o}}{\rm{s}}\frac {{\rm{\mathrm{π}}}}{2}+{\rm{c}}{\rm{o}}{\rm{s}}y$ ， $-\sin y={\rm{c}}{\rm{o}}{\rm{s}}y$ ，
3. 因此 ${\tan}y=\frac {\sin y}{{\cos}y}=\frac {\sin y}{-\sin y}=-1$ ，
4. 又因为 $y\in \left [0,2{\rm{\mathrm{π}}}\right ]$ ，
5. 所以 $y=\frac {3{\rm{\mathrm{π}}}}{4}$ 或 $y=\frac {{{7}}{\rm{\mathrm{π}}}}{4}$ .
6. （2）由 ${\rm{c}}{\rm{o}}{\rm{s}}\left ({x+y}\right )={\rm{c}}{\rm{o}}{\rm{s}}x+{\rm{c}}{\rm{o}}{\rm{s}}y$ 得 ${\cos}x{\cos}y-\sin x\sin y={\rm{c}}{\rm{o}}{\rm{s}}x+{\rm{c}}{\rm{o}}{\rm{s}}y$ ，进行化简得：
7. $\sin x\sin y-{\cos}x{\cos}y=-{\rm{c}}{\rm{o}}{\rm{s}}x-{\rm{c}}{\rm{o}}{\rm{s}}y$ ， $\sin x\sin y+(1-{\cos}x){\cos}y=-{\rm{c}}{\rm{o}}{\rm{s}}x$ ，
8. $\sqrt {\sin {^{2}}x+(1-{\cos}x){^{2}}}\sin (y{{+}}φ)=-{\rm{c}}{\rm{o}}{\rm{s}}x$ ， $\left |{\sqrt {\sin {^{2}}x+(1-{\cos}x){^{2}}}\sin (y{{+}}φ)}\right |=\left |{-{\rm{c}}{\rm{o}}{\rm{s}}x}\right |$ ，
9. 因为 $-1\leqslant \sin (y{{+}}φ)\leqslant {{1}}$ ，所以 $\left |{\sin (y{{+}}φ)}\right |\leqslant 1$ ，
10. 因此 $\left |{-{\rm{c}}{\rm{o}}{\rm{s}}x}\right |\leqslant \left |{\sqrt {\sin {^{2}}x+(1-{\cos}x){^{2}}}}\right |$ ，解不等式：
11. ${\cos}{^{2}}x\leqslant (\sqrt {\sin {^{2}}x+(1-{\cos}x){^{2}}}){^{2}}$ ， ${\cos}{^{2}}x\leqslant \sin {^{2}}x+1-2{\cos}x+{\cos}{^{2}}x$ ， ${\cos}{^{2}}x\leqslant 2-2{\cos}x$ ，
12. 解得 $-1\leqslant {\cos}x\leqslant \sqrt {3}-1$ .
13. （3）假设 $0\leqslant x+y<{\rm{\mathrm{π}}}$ ，
14. 则由余弦函数的单调性可知 ${\cos}(x+y)\leqslant {\cos}x$ ，
15. 所以 ${\cos}y={\cos}(x+y)-{\cos}x\leqslant 0$ ， $y\geqslant \frac {{\rm{\mathrm{π}}}}{2}$ ，
16. 同理可得 $x\geqslant \frac {{\rm{\mathrm{π}}}}{2}$ ，相加得 $x+y\geqslant {\rm{\mathrm{π}}}$ ，与假设矛盾，故 $x+y\geqslant {\rm{\mathrm{π}}}$ ，
17. $2{\rm{\mathrm{π}}}-x\in \left [0,2{\rm{\mathrm{π}}}\right ]$ ， $2{\rm{\mathrm{π}}}-y\in \left [0,2{\rm{\mathrm{π}}}\right ]$ ，
18. ${\cos}[(2{\rm{\mathrm{π}}}-x)+(2{\rm{\mathrm{π}}}-y)]={\cos}(-x-y)={\cos}(x+y)={\cos}x+{\cos}y={\cos}(2{\rm{\mathrm{π}}}-x)+{\cos}(2{\rm{\mathrm{π}}}-y)$ ，
19. 故 $2{\rm{\mathrm{π}}}-x$ ， $2{\rm{\mathrm{π}}}-y$ 也是余弦相关的，
20. 所以 $(2{\rm{\mathrm{π}}}-x)+(2{\rm{\mathrm{π}}}-y)\geqslant {\rm{\mathrm{π}}}$ ，解得 $-x-y\geqslant -3{\rm{\mathrm{π}}}$ ， $x+y\leqslant 3{\rm{\mathrm{π}}}$ ，
21. 综上， ${\rm{\mathrm{π}}}\leqslant x+y\leqslant 3{\rm{\mathrm{π}}}$ ，
22. 此时可设 $z=3{\rm{\mathrm{π}}}-(x+y)$ ， $z\in [0,2{\rm{\mathrm{π}}}]$ ，
23. ${\cos}(x+z)={\cos}[x+3{\rm{\mathrm{π}}}-(x+y)]={\cos}(3{\rm{\mathrm{π}}}-y)={\cos}3{\rm{\mathrm{π}}}{\cos}y+\sin 3{\rm{\mathrm{π}}}\sin y=-{\cos}y$ ，
24. ${\cos}x+{\cos}z={\cos}x+{\cos}[3{\rm{\mathrm{π}}}-(x+y)]={\cos}x-{\cos}(x+y)={\cos}x-({\cos}x+{\cos}y)=-{\cos}y$ ，
25. 故 ${\cos}(x+z)={\cos}x+{\cos}z$ ， $x,z$ 为“余弦相关”的，
26. 同理， $y,z$ 也为“余弦相关”的.

## 知识点

**中文**:
  - 三角函数中的新定义问题

**English**:
  - New Definition Problems

---
