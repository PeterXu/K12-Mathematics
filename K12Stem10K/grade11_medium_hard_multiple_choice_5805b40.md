# Mathematics - 题目 794

**ID**: 5805b40a9099494aaee39cdf136cb561
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Multiple-choice

## 题目
定义：在数列的每相邻两项之间插入此两项的积，形成新数列，这样的操作叫作该数列的一次“美好成长”.​​​​​​​‌将数列 $1,4$ 进行“美好成长”，第一次得到数列 $1,4,4$ ；第二次得到数列 $1,4,4,16,4$ ； $\cdots $ ，设第 $n$ 次“美好成长”后得到的数列为 $1,x{{}_{1}},x{{}_{2}},\cdot \cdots ,x{{}_{k}},4$ ，记 $a{{}_{n}}={\log}{{}_{4}}\left ({1\cdot x{{}_{1}}\cdot x{{}_{2}}\cdot \cdots \cdot x{{}_{k}}\cdot 4}\right )$ ，则下列说法错误的是（      ）

## 解答

1. 对A选项，根据题意可得： $a{{}_{2}}={\log}{{}_{4}}\left ({1\times 4\times 4\times 16\times 4}\right )={\log}{{}_{4}}4{^{5}}=5$ ， $\therefore {\rm A}$ 选项正确；
2. 对B选项，设每次插入项的个数构成数列 $\left \{b{{}_{n}}\right \}$ ，则 $b{{}_{1}}=1,b{{}_{2}}=2,b{{}_{3}}=2{^{2}},\cdots $ ，
3. $\therefore $ 数列 $\left \{b{{}_{n}}\right \}$ 是以首项为1，公比为2的等比数列，
4. $\therefore $ 数列 $\left \{b{{}_{n}}\right \}$ 的前 $n$ 项和即为 $k$ ， $k=\frac {1-2{^{n}}}{1-2}=2{^{n}}-1$ ， $\therefore {\rm B}$ 选项正确；
5. 对C选项， $a{{}_{n+1}}={\log}{{}_{4}}\left [\left ({1\cdot x{{}_{1}}\cdot x{{}_{2}}\cdot \cdots x{{}_{k}}\cdot 4}\right )\cdot \left ({1\cdot x{{}_{1}}}\right )\cdot \left ({x{{}_{1}}\cdot x{{}_{2}}}\right )\left ({x{{}_{2}}\cdot x{{}_{3}}}\right )\cdot \cdots \cdot \left ({x{{}_{k-1}}\cdot x{{}_{k}}}\right )\cdot \left ({x{{}_{k}}\cdot 4}\right )\right ]$
6. $={\log}{{}_{4}}\left [{\left({1\cdot x{{}_{1}}\cdot x{{}_{2}}\cdot \cdots x{{}_{k}}\cdot 4}\right)^{3}}\cdot \frac {1}{4}\right ]=3{\log}{{}_{4}}\left ({1\cdot x{{}_{1}}\cdot x{{}_{2}}\cdot \cdots x{{}_{k}}\cdot 4}\right )-1=3a{{}_{n}}-1$ ， $\therefore {\rm C}$ 选项错误；
7. 对D选项，由B选项分析可得 $a{{}_{n+1}}=3a{{}_{n}}-1$ ，又 $a{{}_{1}}={\log}{{}_{4}}\left ({1\times 4\times 4}\right )=2$ ，
8. $a{{}_{n+1}}-\frac {1}{2}=3\left ({a{{}_{n}}-\frac {1}{2}}\right )$ ，又 $a{{}_{1}}-\frac {1}{2}=2-\frac {1}{2}=\frac {3}{2}$ ，
9. $\therefore \left \{a{{}_{n}}-\frac {1}{2}\right \}$ 是以首项为 $\frac {3}{2}$ ，公比为3的等比数列，
10. $\therefore a{{}_{n}}-\frac {1}{2}=\frac {3}{2}\times 3{^{n-1}}=\frac {1}{2}\times 3{^{n}},$  $a{{}_{n}}=\frac {1+3{^{n}}}{2}$ ， $\therefore {\rm D}$ 选项正确．
11. 故选C．

## 知识点

**中文**:
  - 数列通项求法之构造法
  - 等比数列的概念与通项公式
  - 等比数列的性质

**English**:
  - Construction Method
  - Concept and Formula
  - Properties

---
