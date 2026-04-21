# Mathematics - 题目 390

**ID**: 114f2f7532b14e508ff18024b418d4c5
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
新高考数学多选题6分制的模式改变了传统的多选题赋分模式，每题具有多个正确答案，答对所有正确选项得满分，答对部分选项也可得分，强调了对知识点理解和全面把握的要求．在某次数学测评中，第11题（6分制多选题）得分的学生有100人，其中 $\frac {3}{4}$ 的学生得部分分， $\frac {1}{4}$ 的学生得满分，若给每位得部分分的学生赠送1个书签，得满分的学生赠送2个书签．假设每个学生在第11题得分情况相互独立．（1）从第11题得分的100名学生中随机抽取4人，记这4人得到书签的总数为 $X$ 个，求 $X$ 的分布列和数学期望；​​​​​​​‌（2）从第11题得分的100名学生中随机抽取 $n$ 人 $\left ({0<n\leqslant 100,n\in {\rm{N}}{^{{\rm{*}}}}}\right )$ ，记这 $n$ 人得到书签的总数为 $\left ({n+1}\right )$ 个的概率为 $P{{}_{n}}$ ，求 $P{{}_{1}}+P{{}_{2}}+P{{}_{3}}+\cdot \cdot \cdot +P{{}_{n}}$ 的值；（3）已知王老师班有20名学生在第11题有得分，若以需要赠送书签总个数概率最大为依据，请问王老师应该提前准备多少个书签比较合理？

## 解答

1. （1）由题意得书签的总数 $X$ 的所有可能取值为4，5，6，7，8，
2. 其中 $P\left ({X=4}\right )={\left({\frac {3}{4}}\right)^{4}}=\frac {81}{256}$ ， $P\left ({X=5}\right )={\rm{C}}{{}_{4}^{1}}\times \frac {1}{4}\times {\left({\frac {3}{4}}\right)^{3}}=\frac {27}{64}$ ，
3. $P\left ({X=6}\right )={\rm{C}}{{}_{4}^{2}}\times {\left({\frac {1}{4}}\right)^{2}}\times {\left({\frac {3}{4}}\right)^{2}}=\frac {27}{128}$ ， $P\left ({X=7}\right )={\rm{C}}{{}_{4}^{3}}\times {\left({\frac {1}{4}}\right)^{3}}\times \frac {3}{4}=\frac {3}{64}$ ，
4. $P\left ({X=8}\right )={\left({\frac {1}{4}}\right)^{4}}=\frac {1}{256}$ ，
5. 所以 $X$ 的分布列为
6. $X$
7. 4
8. 5
9. 6
10. 7
11. 8
12. $P$
13. $\frac {81}{256}$
14. $\frac {27}{64}$
15. $\frac {27}{128}$
16. $\frac {3}{64}$
17. $\frac {1}{256}$
18. $E\left ({X}\right )=4\times \frac {81}{256}+5\times \frac {27}{64}+6\times \frac {27}{128}+7\times \frac {3}{64}+8\times \frac {1}{256}=5$ .
19. （2）因为这 $n$ 人得到书签的总数为 $\left ({n+1}\right )$ 个（ $0<n\leqslant 100,n\in {\rm{N}}{^{{\rm{*}}}}$ ），
20. 所以其中只有1人得到2个书签，
21. 所以 $P{{}_{n}}={\rm{C}}{{}_{n}^{1}}\times \frac {1}{4}\times {\left({\frac {3}{4}}\right)^{n-1}}=\frac {n}{3}\cdot {\left({\frac {3}{4}}\right)^{n}}\left ({0<n\leqslant 100,n\in {\rm{N}}{^{{\rm{*}}}}}\right )$ ，
22. 则 $P{{}_{1}}+P{{}_{2}}+P{{}_{3}}+...+P{{}_{n}}=\frac {1}{3}\times \left [1\times \frac {3}{4}+2\times {\left({\frac {3}{4}}\right)^{2}}+3\times {\left({\frac {3}{4}}\right)^{3}}+...+n\times {\left({\frac {3}{4}}\right)^{n}}\right ]$
23. 所以 $\frac {3}{4}\left ({P{{}_{1}}+P{{}_{2}}+P{{}_{3}}+\cdot \cdot \cdot +P{{}_{n}}}\right )=\frac {1}{3}\times \left [1\times {\left({\frac {3}{4}}\right)^{2}}+2\times {\left({\frac {3}{4}}\right)^{3}}+3\times {\left({\frac {3}{4}}\right)^{4}}+...+\left ({n-1}\right )\times {\left({\frac {3}{4}}\right)^{n}}+n\times {\left({\frac {3}{4}}\right)^{n+1}}\right ]$
24. 两式相减得 $\frac {1}{4}\left ({P{{}_{1}}+P{{}_{2}}+P{{}_{3}}+\cdot \cdot \cdot +P{{}_{n}}}\right )=\frac {1}{3}\times \left [\frac {3}{4}+{\left({\frac {3}{4}}\right)^{2}}+{\left({\frac {3}{4}}\right)^{3}}+\cdot \cdot \cdot +{\left({\frac {3}{4}}\right)^{n}}-n\times {\left({\frac {3}{4}}\right)^{n+1}}\right ]$
25. $=\frac {1}{3}\times \left \{\frac {\frac {3}{4}\times \left [1-{\left({\frac {3}{4}}\right)^{n}}\right ]}{1-\frac {3}{4}}-n\times {\left({\frac {3}{4}}\right)^{n+1}}\right \}=1-\frac {n+4}{3}\times {\left({\frac {3}{4}}\right)^{n+1}}$ ，
26. 所以 $P{{}_{1}}+P{{}_{2}}+P{{}_{3}}+\cdot \cdot \cdot +P{{}_{n}}=4-\left ({n+4}\right )\times {\left({\frac {3}{4}}\right)^{n}}\left ({0<n\leqslant 100,n\in {\rm{N}}{^{{\rm{*}}}}}\right )$ ．
27. （3）在这20名学生中，设得到1个书签的人数为 $x$ ，则得到2个书签的人数为 $\left ({20-x}\right )$ ，
28. 所以得到书签的总个数 $n=x+2\left ({20-x}\right )=40-x$ ，
29. 此时得到书签的总个数为 $n$ 的概率为 ${\rm{C}}{{}_{20}^{x}}{\left({\frac {3}{4}}\right)^{x}}\cdot {\left({\frac {1}{4}}\right)^{20-x}}=\frac {3{^{x}}\cdot {\rm{C}}{{}_{20}^{x}}}{4{^{20}}}$ ，
30. 所以 $\begin{cases}\frac {3{^{x}}\cdot {\rm{C}}{{}_{20}^{x}}}{4{^{20}}}\geqslant \frac {3{^{x+1}}\cdot {\rm{C}}{{}_{20}^{x+1}}}{4{^{20}}}\\\frac {3{^{x}}\cdot {\rm{C}}{{}_{20}^{x}}}{4{^{20}}}\geqslant \frac {3{^{x-1}}\cdot {\rm{C}}{{}_{20}^{x-1}}}{4{^{20}}}\end{cases}$ ，整理得 $\begin{cases}x+1\geqslant 3\left ({20-x}\right )\\3\left ({21-x}\right )\geqslant x\end{cases}$ ，解得 $\frac {59}{4}\leqslant x\leqslant \frac {63}{4}$ ，
31. 而 $0\leqslant x\leqslant 20$ ， $x∈{\rm{N}}$ ，所以 $x=15$ ，所以 $n=40-15=25$ ，
32. 所以需要赠送书签总个数概率最大为依据，王老师应该提前准备25个书签比较合理．

## 知识点

**中文**:
  - 数列求和方法之错位相减法
  - 离散型随机变量的分布列

**English**:
  - Offset Subtraction Method
  - Probability Distribution Table

---
