# Mathematics - 题目 1797

**ID**: a4beefb06354411cad455626be257046
**年级**: Grade 10
**难度**: Hard
**题型**: Calculation

## 题目
（1）已知 $a,b,c\in {\mathbf{R}}$ ，求证： $\left |{a+b+c}\right |\mathrm{\leqslant }\left |{a}\right |+\left |{b}\right |+\left |{c}\right |$ ；（2）设函数 $φ{{}_{1}}\left ({x}\right ),φ{{}_{2}}\left ({x}\right )$ 的定义域均为 $I$ ，若 $\exists K>0,\forall x{{}_{1}},x{{}_{2}}\in I,\left |{φ{{}_{1}}\left ({x{{}_{1}}}\right )+φ{{}_{2}}\left ({x{{}_{2}}}\right )}\right |\mathrm{\leqslant }K$ ，则称 $φ{{}_{1}}\left ({x}\right ),φ{{}_{2}}\left ({x}\right )$ 是 $I$ 上的“和有界函数对”.​​​​​​​‌${\rm （i）}$ 若 $φ{{}_{1}}\left ({x}\right ),φ{{}_{2}}\left ({x}\right )$ 是 $I$ 上的“和有界函数对”，证明： $\exists K>0,\forall x\in I,\left |{φ{{}_{1}}\left ({x}\right )+φ{{}_{2}}\left ({x}\right )}\right |\mathrm{\leqslant }K$ ；${\rm （ii）}$ 当 $I{{}_{1}}\subseteq I,I{{}_{2}}\subseteq I$ ，且 $I{{}_{1}}\cap I{{}_{2}}\ne \varnothing $ 时，若 $φ{{}_{1}}\left ({x}\right ),φ{{}_{2}}\left ({x}\right )$ 是 $I{{}_{1}}$ 上的“和有界函数对”， $φ{{}_{1}}\left ({x}\right ),φ{{}_{2}}\left ({x}\right )$ 是 $I{{}_{2}}$ 上的“和有界函数对”，请判断 $φ{{}_{1}}\left ({x}\right ),φ{{}_{2}}\left ({x}\right )$ 是否是 $I{{}_{1}}\cup I{{}_{2}}$ 上的“和有界函数对”，若是，请给出证明；若不是，请给出反例.

## 解答

1. （1）证明：因为 $a,b,c\in {\mathbf{R}}$ ，所以 $-\left |{a}\right |\leqslant a\leqslant \left |{a}\right |,-\left |{b}\right |\leqslant b\leqslant \left |{b}\right |,-\left |{c}\right |\leqslant c\leqslant \left |{c}\right |$ ，
2. 所以 $-\left |{a}\right |-\left |{b}\right |-\left |{c}\right |\leqslant a+b+c\leqslant \left |{a}\right |+\left |{b}\right |+\left |{c}\right |$ ，所以 $\left |{a+b+c}\right |\leqslant \left |{a}\right |+\left |{b}\right |+\left |{c}\right |$ .
3. （2）（i）证明：因为 $φ{{}_{1}}\left ({x}\right ),φ{{}_{2}}\left ({x}\right )$ 是 $I$ 上的“和有界函数对”，
4. 所以 $\exists K>0,\forall x{{}_{1}},x{{}_{2}}\in I,\left |{φ{{}_{1}}\left ({x{{}_{1}}}\right )+φ{{}_{2}}\left ({x{{}_{2}}}\right )}\right |\leqslant K$ ，
5. 令 $x{{}_{1}}=x{{}_{2}}$ ，则 $\left |{φ{{}_{1}}\left ({x{{}_{1}}}\right )+φ{{}_{2}}\left ({x{{}_{1}}}\right )}\right |\leqslant K$ ，
6. 由 $x{{}_{1}}$ 的任意性，得 $\forall x\in I,\left |{φ{{}_{1}}\left ({x}\right )+φ{{}_{2}}\left ({x}\right )}\right |\leqslant K$ .
7. ${\rm （ii）}$ 解： $φ{{}_{1}}\left ({x}\right ),φ{{}_{2}}\left ({x}\right )$ 是 $I{{}_{1}}\cup I{{}_{2}}$ 上的“和有界函数对”，证明如下：
8. 因为 $φ{{}_{1}}\left ({x}\right ),φ{{}_{2}}\left ({x}\right )$ 是 $I{{}_{1}}$ 上的“和有界函数对”， $φ{{}_{1}}\left ({x}\right ),φ{{}_{2}}\left ({x}\right )$ 是 $I{{}_{2}}$ 上的“和有界函数对”，
9. 所以 $\exists K{{}_{1}},K{{}_{2}}>0,\forall x{{}_{1}},x{{}_{2}}\in I{{}_{1}},\left |{φ{{}_{1}}\left ({x{{}_{1}}}\right )+φ{{}_{2}}\left ({x{{}_{2}}}\right )}\right |\leqslant K{{}_{1}},\forall x{{}_{3}},x{{}_{4}}\in I{{}_{2}},\left |{φ{{}_{1}}\left ({x{{}_{3}}}\right )+φ{{}_{2}}\left ({x{{}_{4}}}\right )}\right |\leqslant K{{}_{2}}$ .
10. ①若任取 $x{{}_{1}}\in I{{}_{1}},x{{}_{4}}\in I{{}_{2}}$ ，由 $I{{}_{1}}\cap I{{}_{2}}\ne \varnothing $ ，易知存在 $x{{}_{0}}\in I{{}_{1}}\cap I{{}_{2}}$ ，不妨令 $x{{}_{2}}=x{{}_{3}}=x{{}_{0}}$ ，
11. 所以 $\left |{φ{{}_{1}}\left ({x{{}_{1}}}\right )+φ{{}_{2}}\left ({x{{}_{4}}}\right )}\right |=\left |{φ{{}_{1}}\left ({x{{}_{1}}}\right )+φ{{}_{2}}\left ({x{{}_{0}}}\right )-φ{{}_{2}}\left ({x{{}_{0}}}\right )-φ{{}_{1}}\left ({x{{}_{0}}}\right )+φ{{}_{1}}\left ({x{{}_{0}}}\right )+φ{{}_{2}}\left ({x{{}_{4}}}\right )}\right |{\rm （*）}$ ，
12. 由（1）的结论得， $\left ({{\rm{*}}}\right )$ 式 $\leqslant \left |{φ{{}_{1}}\left ({x{{}_{1}}}\right )+φ{{}_{2}}\left ({x{{}_{0}}}\right )}\right |+\left |{-φ{{}_{2}}\left ({x{{}_{0}}}\right )-φ{{}_{1}}\left ({x{{}_{0}}}\right )}\right |+\left |{φ{{}_{1}}\left ({x{{}_{0}}}\right )+φ{{}_{2}}\left ({x{{}_{4}}}\right )}\right |$
13. $=\left |{φ{{}_{1}}\left ({x{{}_{1}}}\right )+φ{{}_{2}}\left ({x{{}_{0}}}\right )}\right |+\left |{φ{{}_{2}}\left ({x{{}_{0}}}\right )+φ{{}_{1}}\left ({x{{}_{0}}}\right )}\right |+\left |{φ{{}_{1}}\left ({x{{}_{0}}}\right )+φ{{}_{2}}\left ({x{{}_{4}}}\right )}\right |$ ，
14. 由 ${\rm （i）}$ 得， $\left |{φ{{}_{2}}\left ({x{{}_{0}}}\right )+φ{{}_{1}}\left ({x{{}_{0}}}\right )}\right |\leqslant K{{}_{1}}$ ，又 $\left |{φ{{}_{1}}\left ({x{{}_{1}}}\right )+φ{{}_{2}}\left ({x{{}_{0}}}\right )}\right |\leqslant K{{}_{1}},\left |{φ{{}_{1}}\left ({x{{}_{0}}}\right )+φ{{}_{2}}\left ({x{{}_{4}}}\right )}\right |\leqslant K{{}_{2}}$ ，
15. 所以 $\left |{φ{{}_{1}}\left ({x{{}_{1}}}\right )+φ{{}_{2}}\left ({x{{}_{0}}}\right )}\right |+\left |{φ{{}_{2}}\left ({x{{}_{0}}}\right )+φ{{}_{1}}\left ({x{{}_{0}}}\right )}\right |+\left |{φ{{}_{1}}\left ({x{{}_{0}}}\right )+φ{{}_{2}}\left ({x{{}_{4}}}\right )}\right |\leqslant 2K{{}_{1}}+K{{}_{2}}$ ，
16. 即 $\left |{φ{{}_{1}}\left ({x{{}_{1}}}\right )+φ{{}_{2}}\left ({x{{}_{4}}}\right )}\right |\leqslant 2K{{}_{1}}+K{{}_{2}}$ ，
17. 同理可得，当 $x{{}_{1}}\in I{{}_{2}},x{{}_{4}}\in I{{}_{1}}$ 时， $\left |{φ{{}_{1}}\left ({x{{}_{1}}}\right )+φ{{}_{2}}\left ({x{{}_{4}}}\right )}\right |\leqslant 2K{{}_{2}}+K{{}_{1}}$ ，
18. 令 $K={\rm \max }\{2K{{}_{1}}+K{{}_{2}},2K{{}_{2}}+K{{}_{1}}\}$ ，即 $\left |{φ{{}_{1}}\left ({x{{}_{1}}}\right )+φ{{}_{2}}\left ({x{{}_{4}}}\right )}\right |\leqslant K$ ，
19. 所以 $\exists K>0,\forall x{{}_{1}}\in I{{}_{1}},x{{}_{4}}\in I{{}_{2}},\left |{φ{{}_{1}}\left ({x{{}_{1}}}\right )+φ{{}_{2}}\left ({x{{}_{4}}}\right )}\right |\leqslant K$ .
20. ②若任取 $x{{}_{1}},x{{}_{2}}\in I{{}_{1}}$ ，则 $\left |{φ{{}_{1}}\left ({x{{}_{1}}}\right )+φ{{}_{2}}\left ({x{{}_{2}}}\right )}\right |\leqslant K{{}_{1}}<K$ ；
21. 若任取 $x{{}_{3}},x{{}_{4}}\in I{{}_{2}}$ ，则 $\left |{φ{{}_{1}}\left ({x{{}_{3}}}\right )+φ{{}_{2}}\left ({x{{}_{4}}}\right )}\right |\leqslant K{{}_{2}}<K$ .
22. 综上， $\exists K>0,\forall x{{}_{5}},x{{}_{6}}\in I{{}_{1}}\cup I{{}_{2}},\left |{φ{{}_{1}}\left ({x{{}_{5}}}\right )+φ{{}_{2}}\left ({x{{}_{6}}}\right )}\right |\leqslant K$ ，即 $φ{{}_{1}}\left ({x}\right ),φ{{}_{2}}\left ({x}\right )$ 是 $I{{}_{1}}\cup I{{}_{2}}$ 上的“和有界函数对”.

## 知识点

**中文**:
  - 函数新定义问题

**English**:
  - New Definition Problems in Functions

---
