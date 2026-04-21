# Mathematics - 题目 3512

**ID**: a30715569c6f4766b519726c655036ad
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Multiple-choice

## 题目
设 $a{{}_{i}}\left ({i=0,1,2,\cdots ,2020}\right )$ 是常数，对于 $\forall x\in R$ ，都有 $x{^{2020}}=a{{}_{0}}+a{{}_{1}}\left ({x-1}\right )+a{{}_{2}}\left ({x-1}\right )\left ({x-2}\right )+\cdots +a{{}_{2020}}\left ({x-1}\right )\left ({x-2}\right )\cdots \left ({x-2020}\right )$ ，则 $-a{{}_{0}}+a{{}_{1}}-a{{}_{2}}+2!a{{}_{3}}-3!a{{}_{4}}+4!a{{}_{5}}-\cdots +2018!a{{}_{2019}}-2019!a{{}_{2020}}=$ （      ）​​​​​​​‌

## 解答

1. 因为 $x{^{2020}}=a{{}_{0}}+a{{}_{1}}\left ({x-1}\right )+a{{}_{2}}\left ({x-1}\right )\left ({x-2}\right )+\cdots +a{{}_{2020}}\left ({x-1}\right )\left ({x-2}\right )\cdots \left ({x-2020}\right )$ ，
2. 则令 $x=1$ 可得 $a{{}_{0}}=1$ .
3. 又对 $x{^{2020}}=a{{}_{0}}+a{{}_{1}}\left ({x-1}\right )+a{{}_{2}}\left ({x-1}\right )\left ({x-2}\right )+\cdots +a{{}_{2020}}\left ({x-1}\right )\left ({x-2}\right )\cdots \left ({x-2020}\right )$ 两边求导可得：
4. $2020x{^{2019}}=a{{}_{1}}+a{{}_{2}}\left [\left ({x-1}\right )\left ({x-2}\right )\right ]{^{\prime }}+\cdots +a{{}_{2020}}\left [\left ({x-1}\right )\left ({x-2}\right )\cdots \left ({x-2020}\right )\right ]{^{\prime }}$ ，
5. 令 $f{{}_{n}}\left ({x}\right )=\left ({x-1}\right )\left ({x-2}\right )\times \cdots \times \left ({x-n}\right )$ ，
6. 则 $f{{}_{n}}{^{\prime }}\left ({x}\right )=\left ({x-1}\right )\left [\left ({x-2}\right )\times \cdots \times \left ({x-n}\right )\right ]{^{\prime }}{\rm{+}}\left ({x-2}\right )\times \cdots \times \left ({x-n}\right )$ ，
7. 所以 $f{{}_{n}}{^{\prime }}\left ({1}\right )=\left ({1-2}\right )\times \cdots \times \left ({1-n}\right )={\left({-1}\right)^{n-1}}\left ({n-1}\right )!$ ，
8. 所以 $2020\times 1{^{2019}}=a{{}_{1}}+a{{}_{2}}\times {\left({-1}\right)^{1}}\times 1+a{{}_{3}}\times {\left({-1}\right)^{2}}\times 2!+\cdots +a{{}_{2020}}\times {\left({-1}\right)^{2019}}2019!$
9. 故 $2020=a{{}_{1}}-a{{}_{2}}+2!a{{}_{3}}-\cdots -2019!a{{}_{2020}}$ ，
10. 所以 $-a{{}_{0}}+a{{}_{1}}-a{{}_{2}}+2!a{{}_{3}}-3!a{{}_{4}}+4!a{{}_{5}}-\cdots +2018!a{{}_{2019}}-2019!a{{}_{2020}}=2020-1=2019$ .
11. 故选：A.

## 知识点

**中文**:
  - 利用导数解决函数中的其他问题

**English**:
  - Other Function Problems using Derivatives

---
