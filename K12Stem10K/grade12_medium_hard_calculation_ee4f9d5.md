# Mathematics - 题目 1057

**ID**: ee4f9d5f7cfb4ffbbcb4520c1012ebf6
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
集合论在离散数学中有着非常重要的地位.​​​​​​​‌对于非空集合 $A$ 和 $B$ ，定义和集 $A+B=\left \{\left .{a+b}\right |a\in A,b\in B\right \}$ ，用符号 $d(A+B)$ 表示和集 $A+B$ 内的元素个数.（1）已知集合 $A=\left \{1,3,5\right \}$ ， $B=\left \{1,2,6\right \}$ ， $C=\left \{1,2,6,x\right \}$ ，若 $A+B=A+C$ ，求 $x$ 的值；（2）记集合 $A{{}_{n}}=\left \{1,2,\cdots ,n\right \}$ ， $B{{}_{n}}=\left \{\sqrt {2},2\sqrt {2},\cdots ,n\sqrt {2}\right \}$ ， $C{{}_{n}}=A{{}_{n}}+B{{}_{n}}$ ， $a{{}_{n}}$ 为 $C{{}_{n}}$ 中所有元素之和， $n\in {\mathbf{N}}{^{*}}$ ，求证： $\frac {1}{a{{}_{1}}}+\frac {2}{a{{}_{2}}}+\cdots +\frac {n}{a{{}_{n}}}<2(\sqrt {2}-1)$ ；（3）若 $A$ 与 $B$ 都是由 $m\left ({m\geqslant 3,m\in {\mathbf{N}}{^{*}}}\right )$ 个整数构成的集合，且 $d(A+B)=2m-1$ ，证明：若按一定顺序排列，集合 $A$ 与 $B$ 中的元素是两个公差相等的等差数列.

## 解答

1. （1）由题意知 $A+B=\{2,3,4,5,6,7,9,11\}$ ，
2. $\therefore 1+x$ ， $3+x$ ， $5+x\in A+B$ 且 $x\ne 1,2,6$ ，
3. 从而 $1+x=5$ ， $3+x=7$ ， $5+x=9$ ，故 $x=4$ .
4. （2）若 $\exists i{{}_{1}}$ , $i{{}_{2}}\in A{{}_{n}}$ ， $\sqrt {2}j{{}_{1}}$ , $\sqrt {2}j{{}_{2}}\in B{{}_{n}}$ ，使 $i{{}_{1}}+\sqrt {2}j{{}_{1}}=i{{}_{2}}+\sqrt {2}j{{}_{2}}$ ，其中 $i{{}_{1}}$ ， $i{{}_{2}}$ ， $j{{}_{1}}$ ， $j{{}_{2}}\in \{1,2,\cdots ,n\}$ ，
5. 则 $\sqrt {2}\left ({j{{}_{1}}-j{{}_{2}}}\right )=i{{}_{2}}-i{{}_{1}}$ ，故 $j{{}_{1}}=j{{}_{2}}$ ， $i{{}_{1}}=i{{}_{2}}$ .
6. $\therefore C{{}_{n}}=\left \{\left .{i+j\sqrt {2}}\right |i,j\in {\mathbf{N}}{^{*}},1\leqslant i,j\leqslant n\right \}$ ，
7. $\therefore a{{}_{n}}=(1+1\sqrt {2})+(1+2\sqrt {2})+\cdots +(1+n\sqrt {2})+(2+\sqrt {2})+(2+2\sqrt {2})+\cdots +(2+n\sqrt {2})+\cdots +(n+\sqrt {2})+$
8. $(n+2\sqrt {2})+\cdots +(n+n\sqrt {2})=n\cdot \frac {(1+n)\cdot n}{2}+n\cdot \frac {n(1+n)}{2}\sqrt {2}=\frac {1+\sqrt {2}}{2}\left ({n{^{2}}+n{^{3}}}\right )$ ，
9. $\therefore \frac {1}{a{{}_{1}}}+\frac {2}{a{{}_{2}}}+\cdots +\frac {n}{a{{}_{n}}}=\frac {2}{\sqrt {2}+1}\left ({\frac {1}{1\times 2}+\frac {1}{2\times 3}+\cdots +\frac {1}{n(n+1)}}\right )=2(\sqrt {2}-1)\left ({1-\frac {1}{n+1}}\right )<2(\sqrt {2}-1)$ .
10. （3）设集合 $A=\left \{a{{}_{1}},a{{}_{2}},\cdots ,a{{}_{m}}\right \}$ ， $B=\left \{b{{}_{1}},b{{}_{2}},\cdots ,b{{}_{m}}\right \}$ ，其中 $a{{}_{1}}<a{{}_{2}}<\cdots <a{{}_{m}}$ ， $b{{}_{1}}<b{{}_{2}}<\cdots <b{{}_{m}}$ .
11. 则 $a{{}_{1}}+b{{}_{1}}<a{{}_{2}}+b{{}_{1}}<\cdots <a{{}_{m}}+b{{}_{1}}<a{{}_{m}}+b{{}_{2}}<\cdots <a{{}_{m}}+b{{}_{m}}$ ，
12. 这里共 $2m-1$ 个不同元素，又 $d(A+B)=2m-1$ ，所以上面为和集 $A+B$ 中的所有元素.
13. 又 $a{{}_{1}}+b{{}_{1}}<a{{}_{1}}+b{{}_{2}}<a{{}_{2}}+b{{}_{2}}<\cdots <a{{}_{m}}+b{{}_{2}}<a{{}_{m}}+b{{}_{3}}<\cdots <a{{}_{m}}+b{{}_{m}}$ ，
14. 这里共 $2m-1$ 个不同元素，也为合集 $A+B$ 中的所有元素，
15. 所以有 $a{{}_{2}}+b{{}_{1}}=a{{}_{1}}+b{{}_{2}}$ ，即 $a{{}_{2}}-a{{}_{1}}=b{{}_{2}}-b{{}_{1}}$ .
16. 一般地，由 $a{{}_{1}}+b{{}_{1}}<a{{}_{1}}+b{{}_{2}}<\cdots <a{{}_{1}}+b{{}_{k}}<a{{}_{2}}+b{{}_{k}}<\cdots <a{{}_{m}}+b{{}_{k}}<a{{}_{m}}+b{{}_{k+1}}<\cdots <a{{}_{m}}+b{{}_{m}}$ ，
17. $a{{}_{1}}+b{{}_{1}}<\cdots <a{{}_{1}}+b{{}_{k}}<a{{}_{1}}+b{{}_{k+1}}<a{{}_{2}}+b{{}_{k+1}}<\cdots <a{{}_{m}}+b{{}_{k+1}}<\cdots <a{{}_{m}}+b{{}_{m}}$ ，
18. 可得 $a{{}_{2}}+b{{}_{k}}=a{{}_{1}}+b{{}_{k+1}}$ ，即 $a{{}_{2}}-a{{}_{1}}=b{{}_{k+1}}-b{{}_{k}}\left ({1\leqslant k\leqslant m-1}\right )$ .
19. 同理可得 $b{{}_{2}}-b{{}_{1}}=a{{}_{k+1}}-a{{}_{k}}\left ({1\leqslant k\leqslant m-1}\right )$ ，得证.

## 知识点

**中文**:
  - 等差数列的判定与证明
  - 集合的新定义问题

**English**:
  - Determination and Proof
  - New Definition Problems in Sets

---
