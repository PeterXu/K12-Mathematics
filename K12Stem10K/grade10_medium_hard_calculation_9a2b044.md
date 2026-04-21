# Mathematics - 题目 1255

**ID**: 9a2b04449bcb4308bc9c68ddfa90988d
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
欧拉公式 ${\rm{e}}{^{{\rm{i}}x}}={\cos}x+{\rm{i}}\sin x(x\in \mathbf{R}){\rm ，e}$ 是自然对数的底，i是虚数单位.​​​​​​​‌它的一个简单而重要的结论是：余弦函数和正弦函数可以用定义在复数集上的指数函数构造出来，即 ${\cos}x=$  $\frac {{\rm{e}}{^{{\rm{i}}x}}+{\rm{e}}{^{{\rm{i}}x}}}{2},\sin x=$  $\frac {{\rm{e}}{^{{\rm{i}}x}}-{\rm{e}}{^{-{\rm{i}}x}}}{2{\rm{i}}}$  $(x\in \mathbf{R})$ .欧拉公式将指数函数的定义域扩大到复数集，建立了三角函数和指数函数的关系，被誉为“数学中的天桥”.当 $x={\rm{π}}$ 时，得到等式 ${\rm{e}}{^{{\rm{i}}{\rm{π}}}}+1=0$ ，数学里最重要的五个常数 ${\rm{e}},{\rm{π}},{\rm{i}},1,0$ 被联系在一起，仿佛一句诗，道尽了数学之美.（1）证明：若 $x\in \mathbf{R}$ ，则 ${\rm{e}}{^{{\rm{i}}x}}$ 与 ${\rm{e}}{^{-{\rm{i}}x}}$ 互为共轭复数；（2）已知 ${\rm{e}}{^{z{{}_{1}}}}{\rm{e}}{^{z{{}_{2}}}}={\rm{e}}{^{z{{}_{1}}+z{{}_{2}}}}\left ({z{{}_{1}},z{{}_{2}}\in \mathbf{C}}\right )$ ，欧拉公式在复数集内可推广为 ${\rm{e}}{^{{\rm{i}}z}}={\cos}z+{\rm{i}}\sin z,{\rm{e}}{^{-{\rm{i}}z}}=$  ${\cos}z-{\rm{i}}\sin z(z\in \mathbf{C})$ ，需要指出的是， ${\cos}z$ 和 $\sin z$ 是复数，它们不是 ${\rm{e}}{^{{\rm{i}}z}}$ 的实部和虚部，且 ${\cos}z=\frac {{\rm{e}}{^{{\rm{i}}z}}+{\rm{e}}{^{-{\rm{i}}z}}}{2},\sin z=\frac {{\rm{e}}{^{{\rm{i}}z}}-{\rm{e}}{^{-{\rm{i}}z}}}{2{\rm{i}}}(z\in \mathbf{C})$ .容易证明，两角和的余弦公式在复数范围内仍然成立，即 ${\cos}\left ({z{{}_{1}}+z{{}_{2}}}\right )={\cos}z{{}_{1}}{\cos}z{{}_{2}}-\sin z{{}_{1}}\sin z{{}_{2}}\left ({z{{}_{1}},z{{}_{2}}\in \mathbf{C}}\right )$ .定义函数 ${\rm \cos h}z={\cos}({\rm{i}}z)$ ， ${\sinh}z=-{\rm{i}}\sin ({\rm{i}}z)$  $(z\in \mathbf{C})$ .证明： ${\rm \cos h}\left ({z{{}_{1}}+z{{}_{2}}}\right )={\rm \cos h}z{{}_{1}}{\rm \cos h}z{{}_{2}}+{\sinh}z{{}_{1}}{\sinh}z{{}_{2}}\left ({z{{}_{1}},z{{}_{2}}\in \mathbf{C}}\right )$ ；（3）若 $a,x,y\in \mathbf{R}$ ，令 $z=a+{\rm{i}}{\ln}2,{\cos}z=x+y{\rm{i}}$ ，证明： $\frac {16x{^{2}}}{25}+\frac {16y{^{2}}}{9}=1$ .

## 解答

1. （1） $\because {\rm{e}}{^{-{\rm{i}}x}}={\cos}(-x)+{\rm{i}}\sin (-x)={\cos}x-{\rm{i}}\sin x$ ，
2. $\therefore {\rm{e}}{^{-{\rm{i}}x}}$ 的实部为 ${\cos}x$ ，虚部为 $-\sin x$ ，
3. 又 ${\rm{e}}{^{{\rm{i}}x}}$ 的实部为 ${\cos}x$ ，虚部为 $\sin x$
4. $\therefore {\rm{e}}{^{{\rm{i}}x}}$ 与 ${\rm{e}}{^{-{\rm{i}}x}}$ 实部相同，虚部相反，互为共轭复数.
5. （2）代入双曲函数定义，应用三角函数加法公式：
6. ${\rm \cos h}z{{}_{1}}\cdot {\rm \cos h}z{{}_{2}}+{\sinh}z{{}_{1}}\cdot {\sinh}z{{}_{2}}$
7. $={\cos}\left ({{\rm{i}}z{{}_{1}}}\right ){\cos}\left ({{\rm{i}}z{{}_{2}}}\right )+(-{\rm{i}})\sin \left ({{\rm{i}}z{{}_{1}}}\right )(-{\rm{i}})\sin \left ({{\rm{i}}z{{}_{2}}}\right )$
8. $={\cos}\left ({{\rm{i}}z{{}_{1}}}\right ){\cos}\left ({{\rm{i}}z{{}_{2}}}\right )-\sin \left ({{\rm{i}}z{{}_{1}}}\right )\sin \left ({{\rm{i}}z{{}_{2}}}\right )$
9. $={\cos}\left [{\rm{i}}\left ({z{{}_{1}}+z{{}_{2}}}\right )\right ]$
10. $={\rm \cos h}\left ({z{{}_{1}}+z{{}_{2}}}\right )$ .
11. （3）代入已知复数表达式 $z=a+{\rm{i}}{\ln}2$ 并分离实部与虚部：
12. ${\cos}(a+{\rm{i}}{\ln}2)={\cos}a{\cos}({\rm{i}}{\ln}2)-\sin a\sin ({\rm{i}}{\ln}2)$
13. $={\cos}a{\rm \cos h}\left ({{\ln}2}\right )-{\rm{i}}{\rm{s}}{\rm{i}}{\rm{n}}a{\sinh}\left ({{\ln}2}\right ),$
14. 由 ${\rm }{\rm \cos h}z={\cos}({\rm{i}}z)=\frac {{\rm{e}}{^{{\rm{i}}({\rm{i}}z)}}+{\rm{e}}{^{-{\rm{i}}({\rm{i}}z)}}}{2}=\frac {{\rm{e}}{^{-z}}+{\rm{e}}{^{z}}}{2}{\rm }$ ，
15. ${\sinh}z=-{\rm{i}}\sin ({\rm{i}}z)=-{\rm{i}}\cdot \frac {{\rm{e}}{^{{\rm{i}}({\rm{i}}z)}}-{\rm{e}}{^{-{\rm{i}}({\rm{i}}z)}}}{2{\rm{i}}}=\frac {{\rm{e}}{^{z}}-{\rm{e}}{^{-z}}}{2}$ ，
16. 得 $x={\cos}a{\rm \cos h}({\ln}2)={\cos}a\cdot \frac {{\rm{e}}{^{{\ln}2}}+{\rm{e}}{^{-{\ln}2}}}{2}=\frac {5}{4}{\cos}a$ ，
17. $y=-\sin a{\sinh}({\ln}2)=-\sin a\cdot \frac {{\rm{e}}{^{{\ln}2}}-{\rm{e}}{^{-{\ln}2}}}{2}=-\frac {3}{4}\sin a,$
18. 由 ${\cos}{^{2}}a+\sin {^{2}}a=1$ ，整理得 $\frac {16x{^{2}}}{25}+\frac {16y{^{2}}}{9}=1$ .

## 知识点

**中文**:
  - 共轭复数
  - 复数的三角表示*
  - 复数新定义问题

**English**:
  - Conjugate Complex Numbers
  - Trigonometric Form
  - New Definition Problems in Complex Numbers

---
