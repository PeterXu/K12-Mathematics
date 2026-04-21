# Mathematics - 题目 47

**ID**: 9b202ecb3f8242748c1d6cec05f3e783
**年级**: Grade 10
**难度**: Hard
**题型**: Calculation

## 题目
将所有平面向量组成的集合记作 ${\mathbf{R}}{^{2}}$ .​​​​​​​‌如果对于向量.  $\overrightarrow {{x}}=\left ({x{{}_{1}},x{{}_{2}}}\right )\in {\mathbf{R}}{^{2}}$ ，存在唯一的向量  $\overrightarrow {{y}}=\left ({y{{}_{1}}{\rm{,}}y{{}_{2}}}\right )\in {\mathbf{R}}{^{2}}$ 与之对应，其中坐标 $y{{}_{1}}$ 、 $y{{}_{2}}$ 由 $x{{}_{1}}$ 、 $x{{}_{2}}$ 确定，则把这种对应关系记为.  $\overrightarrow {{y}}=f\left ({\overrightarrow {{x}}}\right )$ 或者  $\left ({y{{}_{1}},y{{}_{2}}}\right )=f\left ({x{{}_{1}},x{{}_{2}}}\right )$ 简记为 $f$ .例如 $\left ({y{{}_{1}},y{{}_{2}}}\right )=f\left ({x{{}_{1}},x{{}_{2}}}\right )=\left ({2x{{}_{1}}+x{{}_{2}},x{{}_{1}^{2}}}\right )$ 就是一种对应关系.若在 $\left |{\overrightarrow {{x}}}\right |=1$ 的条件下 $\left |{\overrightarrow {{y}}}\right |$ 有最大值，则称此最大值为对应关系 $f$ 的模，并把 $f$ 的模记作 $\Vert {f}\Vert $ ；若存在非零向量 $\overrightarrow {{x}}\in {\mathbf{R}}{^{2}}$ 及实数 $λ$ 使得 $f\left ({\overrightarrow {{x}}}\right )=λ\overrightarrow {{x}}$ ，则称 $λ$ 为 $f$ 的一个特征值，（1）如果 $f\left ({x{{}_{1}}{\rm{,}}x{{}_{2}}}\right )=\left ({3x{{}_{1}}{\rm{,}}3x{{}_{2}}}\right )$ ，求 $\Vert {f}\Vert $ ；（2）如果 $f\left ({x{{}_{1}},x{{}_{2}}}\right )=\left ({2x{{}_{1}}+4x{{}_{2}},x{{}_{1}}-x{{}_{2}}}\right )$ ，计算 $f$ 的特征值，并求相应的 $\overrightarrow {{x}}$ ；（若符合条件的向量 $\overrightarrow {{x}}$ 有多个，写出其中一个即可）（3）若 $f\left ({x{{}_{1}},x{{}_{2}}}\right )=\left ({a{{}_{1}}x{{}_{1}}+a{{}_{2}}x{{}_{2}},b{{}_{1}}x{{}_{1}}+b{{}_{2}}x{{}_{2}}}\right )$ ，要使 $f$ 有唯一的特征值，实数 $a{{}_{1}}$ 、 $a{{}_{2}}$ 、 $b{{}_{1}}$ 、 $b{{}_{2}}$ 应满足什么条件?试找出一个对应关系 $f$ ，同时满足以下两个条件：①有唯一的特征值 $λ$ ，② $\Vert {f}\Vert =\left |{λ}\right |$ ，并验证 $f$ 满足这两个条件.

## 解答

1. （1）由题意 $\overrightarrow {{y}}=\left ({3x{{}_{1}},3x{{}_{2}}}\right )=3\left ({x{{}_{1}},x{{}_{2}}}\right )=3\overrightarrow {{x}}$ ，所以 $\left |{\overrightarrow {{y}}}\right |=3\left |{\overrightarrow {{x}}}\right |$ ，当 $\left |{\overrightarrow {{x}}}\right |=1$ 时， $\left |{\overrightarrow {{y}}}\right |=3$ ，最大值也为 $3$ ，所以 $\Vert {f}\Vert =3$ ．
2. （2）由 $f\left ({x{{}_{1}},x{{}_{2}}}\right )=\left ({2x{{}_{1}}+4x{{}_{2}},x{{}_{1}}-x{{}_{2}}}\right )=λ\left ({x{{}_{1}},x{{}_{2}}}\right )$ ，可得： $\begin{cases}2x{{}_{1}}+4x{{}_{2}}=λx{{}_{1}}\\x{{}_{1}}-x{{}_{2}}=λx{{}_{2}}\end{cases}$ ，
3. 上述两个 相加得 $3\left ({x{{}_{1}}+x{{}_{2}}}\right )=λ\left ({x{{}_{1}}+x{{}_{2}}}\right )$ ，解得 $λ=3$ ．
4. 当 $λ=3$ 时，解方程组 $\begin{cases}2x{{}_{1}}+4x{{}_{2}}=3x{{}_{1}}\\x{{}_{1}}-x{{}_{2}}=3x{{}_{2}}\end{cases}$ ，此时这两个方程是同一个方程 $x{{}_{1}}+x{{}_{2}}=0$ ，
5. 所以此时方程有无穷多个解，为 $\overrightarrow {{x}}=m\left ({1,-1}\right )$ （写出一个即可），其中 $m\in {\mathbf{R}}$ 且 $m\ne 0$ ．
6. （3）由 $\begin{cases}a{{}_{1}}x{{}_{1}}+a{{}_{2}}x{{}_{2}}=λx{{}_{1}}\\b{{}_{1}}x{{}_{1}}+b{{}_{2}}x{{}_{2}}=λx{{}_{2}}\end{cases}$ ，可得 $x{{}_{1}}\left ({a{{}_{1}}-λ,b{{}_{1}}}\right )+x{{}_{2}}\left ({a{{}_{2}},b{{}_{2}}-λ}\right )=0$ ．
7. 因为 $x{{}_{1}}$ 、 $x{{}_{2}}$ 都不为 $0$ ，从而向量 $\left ({a{{}_{1}}-λ,b{{}_{1}}}\right )$ 与 $\left ({a{{}_{2}},b{{}_{2}}-λ}\right )$ 平行，
8. 所以存在实数 $λ$ 满足 $\left ({a{{}_{1}}-λ}\right )\left ({b{{}_{2}}-λ}\right )=a{{}_{2}}b{{}_{1}}$ ，即 $λ{^{2}}-\left ({a{{}_{1}}+b{{}_{2}}}\right )λ+a{{}_{1}}b{{}_{2}}-a{{}_{2}}b{{}_{1}}=0$ ．
9. 要使 $λ$ 存在且唯一，则 $a{{}_{1}}$ 、 $a{{}_{2}}$ 、 $b{{}_{1}}$ 、 $b{{}_{2}}$ 应满足： ${\rm{Δ}}={\left({a{{}_{1}}-b{{}_{2}}}\right)^{2}}+4a{{}_{2}}b{{}_{1}}=0$ ．
10. 当 $f\left ({\overrightarrow {{x}}}\right )=λ\overrightarrow {{x}}$ 时， $f$ 有唯一的特征值，且 $\Vert {f}\Vert =\left |{λ}\right |$ ．具体证明为：
11. 由 $f$ 的定义可知： $f\left ({x{{}_{1}},x{{}_{2}}}\right )=λ\left ({x{{}_{1}},x{{}_{2}}}\right )$ ，所以 $λ$ 为特征值．
12. 此时 $a{{}_{1}}=λ$ ， $a{{}_{2}}=0$ ， $b{{}_{1}}=0$ ， $b{{}_{2}}=λ$ 满足： ${\left({a{{}_{1}}-b{{}_{2}}}\right)^{2}}+4a{{}_{2}}b{{}_{1}}=0$ ，所以有唯一的特征值．
13. 在 $x{{}_{1}^{2}}+x{{}_{2}^{2}}=1$ 的条件下 ${\left({λx{{}_{1}}}\right)^{2}}+{\left({λx{{}_{2}}}\right)^{2}}=λ{^{2}}$ ，从而有 $\Vert {f}\Vert =\left |{λ}\right |$ ．

## 知识点

**中文**:
  - 平面向量的新定义问题

**English**:
  - New Definition Problems

---
