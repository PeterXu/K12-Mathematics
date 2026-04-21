# Mathematics - 题目 415

**ID**: 69165d2524374f3fbbbf94574fc7e51b
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
“ $q-$ 数”在量子代数研究中发挥了重要作用.​​​​​​​‌设 $q$ 是非零实数，对任意 $n\in {\mathbf{N}}{^{{\rm{*}}}}$ ，定义“ $q-$ 数” $(n){{}_{q}}=1+q+\cdots +q{^{n-1}}$ 利用“ $q-$ 数”可定义“ $q-$ 阶乘” $\left ({n}\right )!{{}_{q}}=(1){{}_{q}}(2){{}_{q}}\cdots (n){{}_{q}}{\rm{,}}且\left ({0}\right )!{{}_{q}}=1.$ 和“ $q-$ 组合数”，即对任意 $k\in {\mathbf{N}},n\in {\mathbf{N}}{^{{\rm{*}}}},k\leqslant n$ ， $\begin{pmatrix}n\\k\end{pmatrix}{{}_{q}}=\frac {\left ({n}\right )!{{}_{q}}}{\left ({k}\right )!{{}_{q}}\left ({n-k}\right )!{{}_{q}}}$(1)计算： $\begin{pmatrix}5\\3\end{pmatrix}{{}_{2}}$ ；(2)证明：对于任意 $k,n\in {\mathbf{N}}{^{{\rm{*}}}},k+1\leqslant n$ ， $\begin{pmatrix}n\\k\end{pmatrix}{{}_{q}}=\begin{pmatrix}n-1\\k-1\end{pmatrix}{{}_{q}}+q{^{k}}\begin{pmatrix}n-1\\k\end{pmatrix}{{}_{q}}$(3)证明：对于任意 $k,m\in {\mathbf{N}},n\in {\mathbf{N}}{^{{\rm{*}}}},k+1\leqslant n$ ， $\begin{pmatrix}n+m+1\\k+1\end{pmatrix}{{}_{q}}-\begin{pmatrix}n\\k+1\end{pmatrix}{{}_{q}}=\sum\limits_{i=0}^{m}\mathop{}q{^{n-k+i}}\begin{pmatrix}n+i\\k\end{pmatrix}{{}_{q}}.$

## 解答

1. （1）由定义可知，
2. $\begin{pmatrix}5\\3\end{pmatrix}{{}_{2}}=\frac {\left ({5}\right )!{{}_{2}}}{\left ({3}\right )!{{}_{2}}\left ({2}\right )!{{}_{2}}}=\frac {(1){{}_{2}}(2){{}_{2}}(3){{}_{2}}(4){{}_{2}}(5){{}_{2}}}{\left [(1){{}_{2}}(2){{}_{2}}(3){{}_{2}}\right ]\left [(1){{}_{2}}(2){{}_{2}}\right ]}$
3. $=\frac {(4){{}_{2}}(5){{}_{2}}}{(1){{}_{2}}(2){{}_{2}}}=\frac {\left ({1+2+2{^{2}}+2{^{3}}}\right )\left ({1+2+2{^{2}}+2{^{3}}+2{^{4}}}\right )}{1\times \left ({1+2}\right )}=155$ .
4. （2）因为 $\begin{pmatrix}n\\k\end{pmatrix}{{}_{q}}=\frac {\left ({n}\right )!{{}_{q}}}{\left ({k}\right )!{{}_{q}}\left ({n-k}\right )!{{}_{q}}}=\frac {(n){{}_{q}}\cdot \left ({n-1}\right )!{{}_{q}}}{\left ({k}\right )!{{}_{q}}\left ({n-k}\right )!{{}_{q}}}$ ，
5. $\begin{pmatrix}n-1\\k-1\end{pmatrix}{{}_{q}}+q{^{k}}\begin{pmatrix}n-1\\k\end{pmatrix}{{}_{q}}=\frac {\left ({n-1}\right )!{{}_{q}}}{\left ({k-1}\right )!{{}_{q}}\left ({n-k}\right )!{{}_{q}}}+\frac {q{^{k}}\cdot \left ({n-1}\right )!{{}_{q}}}{\left ({k}\right )!{{}_{q}}\left ({n-k-1}\right )!{{}_{q}}}$
6. $=\frac {\left ({n-1}\right )!{{}_{q}}}{\left ({k}\right )!{{}_{q}}\left ({n-k}\right )!{{}_{q}}}\left [(k){{}_{q}}+q{^{k}}\cdot (n-k){{}_{q}}\right ]$ .
7. 又 $(k){{}_{q}}+q{^{k}}\cdot (n-k){{}_{q}}=1+q+\cdots +q{^{k-1}}+q{^{k}}\left ({1+q+\cdots +q{^{n-k-1}}}\right )$
8. $=1+q+\cdots +q{^{n-1}}=(n){{}_{q}}$ ,
9. 所以 $\begin{pmatrix}n\\k\end{pmatrix}{{}_{q}}=\begin{pmatrix}n-1\\k-1\end{pmatrix}{{}_{q}}+q{^{k}}\begin{pmatrix}n-1\\k\end{pmatrix}{{}_{q}}$
10. （3）由定义得：
11. 对任意 $k\in {\rm{N}},n\in {\rm{N}}{^{{\rm{*}}}},k\leqslant n,\begin{pmatrix}n\\k\end{pmatrix}{{}_{q}}=\begin{pmatrix}n\\n-k\end{pmatrix}{{}_{q}}$ .
12. 结合（2）可知
13. $\begin{pmatrix}n\\k\end{pmatrix}{{}_{q}}=\begin{pmatrix}n\\n-k\end{pmatrix}{{}_{q}}=\begin{pmatrix}n-1\\n-k-1\end{pmatrix}{{}_{q}}+q{^{n-k}}\begin{pmatrix}n-1\\n-k\end{pmatrix}{{}_{q}}$
14. $=\begin{pmatrix}n-1\\k\end{pmatrix}{{}_{q}}+q{^{n-k}}\begin{pmatrix}n-1\\k-1\end{pmatrix}{{}_{q}}$
15. 即 $\begin{pmatrix}n\\k\end{pmatrix}{{}_{q}}=\begin{pmatrix}n-1\\k\end{pmatrix}{{}_{q}}+q{^{n-k}}\begin{pmatrix}n-1\\k-1\end{pmatrix}{{}_{q}}$ ，
16. 也即 $\begin{pmatrix}n\\k\end{pmatrix}{{}_{q}}-\begin{pmatrix}n-1\\k\end{pmatrix}{{}_{q}}=q{^{n-k}}\begin{pmatrix}n-1\\k-1\end{pmatrix}{{}_{q}}$ .
17. 所以 $\begin{pmatrix}n+m+1\\k+1\end{pmatrix}{{}_{q}}-\begin{pmatrix}n+m\\k+1\end{pmatrix}{{}_{q}}=q{^{n+m-k}}\begin{pmatrix}n+m\\k\end{pmatrix}{{}_{q}}$ ，
18. $\begin{pmatrix}n+m\\k+1\end{pmatrix}{{}_{q}}-\begin{pmatrix}n+m-1\\k+1\end{pmatrix}{{}_{q}}=q{^{n+m-1-k}}\begin{pmatrix}n+m-1\\k\end{pmatrix}{{}_{q}}$ ，
19. ……
20. $\begin{pmatrix}n+1\\k+1\end{pmatrix}{{}_{q}}-\begin{pmatrix}n\\k+1\end{pmatrix}{{}_{q}}=q{^{n-k}}\begin{pmatrix}n\\k\end{pmatrix}{{}_{q}}$ .
21. 上述 $m+1$ 个等式两边分别相加得：
22. $\begin{pmatrix}n+m+1\\k+1\end{pmatrix}{{}_{q}}-\begin{pmatrix}n\\k+1\end{pmatrix}{{}_{q}}=\sum\limits_{i=0}^{m}\mathop{}q{^{n-k+i}}\begin{pmatrix}n+i\\k\end{pmatrix}{{}_{q}}$ .

## 知识点

**中文**:
  - 排列数公式

**English**:
  - Formula

---
