# Mathematics - 题目 940

**ID**: b198129079374d77827366a77b144268
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Fill-in-the-blank

## 题目
已知平面向量 $\overrightarrow a$ ，  $\overrightarrow b$ 和单位向量 $\overrightarrow {{e{{}_{1}}}}$ ，  $\overrightarrow {{e{{}_{2}}}}$ 满足 $\overrightarrow {{e{{}_{1}}}}=-\overrightarrow {{e{{}_{2}}}}$ ，  $\left |{\overrightarrow a-\overrightarrow {{e{{}_{1}}}}+\overrightarrow {{e{{}_{2}}}}}\right |=3\left |{\overrightarrow a+\overrightarrow {{e{{}_{1}}}}-\overrightarrow {{e{{}_{2}}}}}\right |，\overrightarrow b=λ\overrightarrow a+μ\overrightarrow {{e{{}_{1}}}}$ ， $2λ+μ=2$  ， 当 $\overrightarrow a$ 变化时，  $\left |{\overrightarrow b}\right |$ 的最小值为 $m$ ， 则 $m$ 的最大值为.​​​​​​​‌

## 解答

1. 不妨设 $\overrightarrow {{e{{}_{1}}}}=\left ({1,0}\right )$  ， $\overrightarrow a=\left ({x,y}\right )$  ，则由题知 $\overrightarrow {{e{{}_{2}}}}=\left ({-1,0}\right )$
2. $\overrightarrow a-\overrightarrow {{e{{}_{1}}}}+\overrightarrow {{e{{}_{2}}}}=\left ({x-2,y}\right )，\overrightarrow a+\overrightarrow {{e{{}_{1}}}}-\overrightarrow {{e{{}_{2}}}}=\left ({x+2,y}\right )$
3. 又 $\left |{\overrightarrow a-\overrightarrow {{e{{}_{1}}}}+\overrightarrow {{e{{}_{2}}}}}\right |=3\left |{\overrightarrow a+\overrightarrow {{e{{}_{1}}}}-\overrightarrow {{e{{}_{2}}}}}\right |$  ，所以 $\sqrt {{\left({x-2}\right)^{2}}+y{^{2}}}=3\sqrt {{\left({x+2}\right)^{2}}+y{^{2}}}$
4. 整理得 ${\left({x+\frac {5}{2}}\right)^{2}}+y{^{2}}=\frac {9}{4}$ ① ，所以 $-4\mathrm{\leqslant }x\mathrm{\leqslant }-1$
5. 又 $\overrightarrow b=λ\overrightarrow a+μ\overrightarrow {{e{{}_{1}}}}$  ， $2λ+μ=2$
6. 所以 $\overrightarrow b=λ\overrightarrow a+\left ({2-2λ}\right )\overrightarrow {{e{{}_{1}}}}=\left ({λx+2-2λ,λy}\right )$
7. 而 $\left |{\overrightarrow b}\right |=\sqrt {{\left({λx+2-2λ}\right)^{2}}+{\left({λy}\right)^{2}}}$
8. $=\sqrt {λ{^{2}}\left ({x{^{2}}+y{^{2}}}\right )+2λ\left ({2-2λ}\right )x+{\left({2-2λ}\right)^{2}}}$
9. 将①代入整理得：
10. $\left |{\overrightarrow b}\right |=\sqrt {-9xλ{^{2}}+\left ({4x-8}\right )λ+4}$
11. 令 $f\left ({λ}\right )=-9xλ{^{2}}+\left ({4x-8}\right )λ+4,x\in \left [-4,-1\right ]$  ，
12. $\because \-9x>0$  ， $\therefore \f\left ({λ}\right )$ 有最小值，
13. $f\left ({λ}\right ){{}_{\min }}=\frac {16\times \left ({-9x}\right )-{\left({4x-8}\right)^{2}}}{-36x}=\frac {4x}{9}+\frac {16}{9x}+\frac {20}{9}$
14. $m=\left |{\overrightarrow b}\right |{{}_{\min }}=\sqrt {\frac {4x}{9}+\frac {16}{9x}+\frac {20}{9}}\，x\in \left [-4,-1\right ]$
15. 又 $\frac {-4x}{9}+\frac {16}{-9x}\geqslant 2\sqrt {\frac {-4x}{9}\times \frac {16}{-9x}}=\frac {16}{9}$  ，当且仅当 $x=-2$ 时等号成立
16. 所以 $0\leqslant m\leqslant \sqrt {\frac {4}{9}}=\frac {2}{3}$  ，当 $x=-2$ 时 $m$ 有最大值 $\frac {2}{3}$  .
17. 故答案为： $\frac {2}{3}$  .

## 知识点

**中文**:
  - 向量的模的坐标计算
  - 基本不等式在最值问题中的应用
  - 平面向量的坐标运算

**English**:
  - Coordinate Calculation of Modulus
  - Application in Extremum Problems
  - Coordinate Operations

---
