# Mathematics - 题目 3909

**ID**: 500001c7a23644a4a713e6251611a023
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
将平面直角坐标系中的一列点 $A{{}_{1}}\left ({1,a{{}_{1}}}\right )$ 、 $A{{}_{2}}\left ({2,a{{}_{2}}}\right )$ 、 $\cdots $ 、 $A{{}_{n}}\left ({n,a{{}_{n}}}\right )$ 、 $\cdots $ ，记为 $\left \{A{{}_{n}}\right \}$ ，设 $f\left ({n}\right )=\overrightarrow {{A{{}_{n}}A{{}_{n+1}}}}\cdot \overrightarrow {{j}}$ ，其中 $\overrightarrow {{j}}$ 为与 $y$ 轴方向相同的单位向量.​​​​​​​‌若对任意的正整数 $n$ ，都有 $f\left ({n+1}\right )>f\left ({n}\right )$ ，则称 $\left \{A{{}_{n}}\right \}$ 为 $T$ 点列.（1）判断 $A{{}_{1}}\left ({1,1}\right )$ 、 $A{{}_{2}}\left ({2,\frac {1}{2}}\right )$ 、 $A{{}_{3}}\left ({3,\frac {1}{3}}\right )$ 、 $\cdots $ 、 $A{{}_{n}}\left ({n,\frac {1}{n}}\right )$ 、 $\cdots $ 是否为 $T$ 点列，并说明理由；（2）若 $\left \{A{{}_{n}}\right \}$ 为 $T$ 点列，且 $a{{}_{1}}>a{{}_{2}}$ .任取其中连续三点 $A{{}_{k}}$ 、 $A{{}_{k+1}}$ 、 $A{{}_{k+2}}$ ，证明 $\vartriangle A{{}_{k}}A{{}_{k+1}}A{{}_{k+2}}$ 为钝角三角形；（3）若 $\left \{A{{}_{n}}\right \}$ 为 $T$ 点列，对于正整数 $k$ 、 $l$ 、 $m\left ({k<l<m}\right )$ ，比较 $\overrightarrow {{A{{}_{l}}A{{}_{m+k}}}}·\overrightarrow {{j}}$ 与 $\overrightarrow {{A{{}_{l-k}}A{{}_{m}}}}·\overrightarrow {{j}}$ 的大小，并说明理由.

## 解答

1. （1） $\left \{A{{}_{n}}\right \}$ 为 $T$ 点列，理由如下：
2. 由题意可知， $\overrightarrow {{A{{}_{n+1}}A{{}_{n}}}}=\left ({1,\frac {1}{n+1}-\frac {1}{n}}\right )$ ， $\overrightarrow {{j}}=\left ({0,1}\right )$ ，所以 $f\left ({n}\right )=\overrightarrow {{A{{}_{n}}A{{}_{n+1}}}}\cdot \overrightarrow {{j}}=\frac {1}{n+1}-\frac {1}{n}$ ，
3. $f\left ({n+1}\right )-f\left ({n}\right )=\frac {1}{n+2}-\frac {1}{n+1}-\left ({\frac {1}{n+1}-\frac {1}{n}}\right )=\frac {2}{n\left ({n+1}\right )\left ({n+2}\right )}>0$ ，即 $f\left ({n+1}\right )>f\left ({n}\right )$ ， $n\in {\mathbf{N}^{*}}$ ，
4. 所以 $A{{}_{1}}\left ({1,1}\right )$ 、 $A{{}_{2}}\left ({2,\frac {1}{2}}\right )$ 、 $A{{}_{3}}\left ({3,\frac {1}{3}}\right )$ 、 $\cdots $ 、 $A{{}_{n}}\left ({n,\frac {1}{n}}\right )$ 、 $\cdots $ 为 $T$ 点列；
5. （2）由题意可知， $\overrightarrow {{A{{}_{n}}A{{}_{n+1}}}}=\left ({1,a{{}_{n+1}}-a{{}_{n}}}\right )$ ， $\overrightarrow {{j}}=\left ({0,1}\right )$ ，所以 $f\left ({n}\right )=\overrightarrow {{A{{}_{n}}A{{}_{n+1}}}}\cdot \overrightarrow {{j}}=a{{}_{n+1}}-a{{}_{n}}$ ，
6. 因为 $\left \{A{{}_{n}}\right \}$ 为 $T$ 点列，所以 $f\left ({n+1}\right )-f\left ({n}\right )=a{{}_{n+2}}-a{{}_{n+1}}-\left ({a{{}_{n+1}}-a{{}_{n}}}\right )>0$ ， $n\in {\mathbf{N}^{*}}$ ，
7. 又因为 $a{{}_{2}}>a{{}_{1}}$ ，所以 $a{{}_{2}}-a{{}_{1}}>0$ .
8. 所以对 $\left \{A{{}_{n}}\right \}$ 中连续三点 $A{{}_{k}}$ 、 $A{{}_{k+1}}$ 、 $A{{}_{k+2}}$ ，都有 $a{{}_{k+2}}-a{{}_{k+1}}>a{{}_{k+1}}-a{{}_{k}}$ ， $a{{}_{k+2}}>a{{}_{k+1}}>a{{}_{k}}$ .
9. 因为 $\overrightarrow {{A{{}_{k}}A{{}_{k+1}}}}=\left ({1,a{{}_{k+1}}-a{{}_{k}}}\right )$ ， $\overrightarrow {{A{{}_{k+1}}A{{}_{k+2}}}}=\left ({1,a{{}_{k+2}}-a{{}_{k+1}}}\right )$ ，
10. 因为 $a{{}_{k+2}}-a{{}_{k+1}}>a{{}_{k+1}}-a{{}_{k}}$ ，故 $\overrightarrow {{A{{}_{k}}A{{}_{k+1}}}}$ 与 $\overrightarrow {{A{{}_{k+1}}A{{}_{k+2}}}}$ 不共线，即 $A{{}_{k}}$ 、 $A{{}_{k+1}}$ 、 $A{{}_{k+2}}$ 不共线，
11. 因为 $\overrightarrow {{A{{}_{k+1}}A{{}_{k}}}}\cdot \overrightarrow {{A{{}_{k+1}}A{{}_{k+2}}}}=-1+\left ({a{{}_{k}}-a{{}_{k+1}}}\right )\left ({a{{}_{k+2}}-a{{}_{k+1}}}\right )<0$ ，
12. 所以， ${\cos}\angle A{{}_{k}}A{{}_{k+1}}A{{}_{k+2}}=\frac {\overrightarrow {{A{{}_{k+1}}A{{}_{k}}}}\cdot \overrightarrow {{A{{}_{k+1}}A{{}_{k+2}}}}}{\left |{\overrightarrow {{A{{}_{k+1}}A{{}_{k}}}}}\right |\cdot \left |{\overrightarrow {{A{{}_{k+1}}A{{}_{k+2}}}}}\right |}<0$ ，则 $\angle A{{}_{k}}A{{}_{k+1}}A{{}_{k+2}}$ 为钝角，
13. 所以 $\vartriangle A{{}_{k}}A{{}_{k+1}}A{{}_{k+2}}$ 为钝角三角形；
14. （3）由 $k<l<m$ ， $m\geqslant 3$ .
15. 因为 $\left \{A{{}_{n}}\right \}$ 为 $T$ 点列，由（2）知 $a{{}_{n+2}}-a{{}_{n+1}}>a{{}_{n+1}}-a{{}_{n}}$ ， $n\in {\mathbf{N}^{*}}$ ，
16. 所以 $a{{}_{m+k}}-a{{}_{m+k-1}}>a{{}_{m+k-1}}-a{{}_{m+k-2}}$ ， $a{{}_{m+k-1}}-a{{}_{m+k-2}}>a{{}_{m+k-2}}-a{{}_{m+k-3}}$ ， $\cdots $ ，
17. $a{{}_{m+1}}-a{{}_{m}}>a{{}_{m}}-a{{}_{m-1}}$ ，
18. 两边分别相加可得 $a{{}_{m+k}}-a{{}_{m}}>a{{}_{m+k-1}}-a{{}_{m-1}}$ ，
19. 所以 $a{{}_{m+k-1}}-a{{}_{m-1}}>a{{}_{m+k-2}}-a{{}_{m-2}}>a{{}_{l}}-a{{}_{l-k}}$ ，所以 $a{{}_{m+k}}-a{{}_{m}}>a{{}_{l}}-a{{}_{l-k}}$ ，所以 $a{{}_{m+k}}-a{{}_{l}}>a{{}_{m}}-a{{}_{l-k}}$ ，
20. 又 $\overrightarrow {{A{{}_{l}}A{{}_{m+k}}}}=\left ({m+k-l,a{{}_{m+k}}-a{{}_{l}}}\right )$ ， $\overrightarrow {{A{{}_{l-k}}A{{}_{m}}}}=\left ({m-l+k,a{{}_{m}}-a{{}_{l-k}}}\right )$ ，
21. 所以 $\overrightarrow {{A{{}_{l}}A{{}_{m+k}}}}\cdot \overrightarrow {{j}}=a{{}_{m+k}}-a{{}_{l}}$ ， $\overrightarrow {{A{{}_{l-k}}A{{}_{m}}}}\cdot \overrightarrow {{j}}=a{{}_{m}}-a{{}_{l-k}}$ ，所以 $\overrightarrow {{A{{}_{l}}A{{}_{m+k}}}}\cdot \overrightarrow {{j}}>\overrightarrow {{A{{}_{l-k}}A{{}_{m}}}}\cdot \overrightarrow {{j}}$ .

## 知识点

**中文**:
  - 平面向量的新定义问题

**English**:
  - New Definition Problems

---
