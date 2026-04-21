# Mathematics - 题目 239

**ID**: 7f3dcfa6aac942faaa6029f1513252bf
**年级**: Grade 12
**难度**: Medium
**题型**: Calculation

## 题目
已知数列 $\left \{a{{}_{n}}\right \}$ 中， $a{{}_{1}}=4$ ，且 $a{{}_{n}}-a{{}_{n+1}}=\frac {1}{2}\left ({a{{}_{n+1}}-3}\right )\left ({a{{}_{n}}-3}\right )$ .​​​​​​​‌(1)求证：数列 $\left \{\frac {2}{a{{}_{n}}-3}\right \}$ 是等差数列；(2)记数列 $b{{}_{n}}=\left ({a{{}_{n}}-3}\right )\left ({a{{}_{n+1}}-3}\right )$ ，求数列 $\left \{b{{}_{n}}\right \}$ 的前 $n$ 项和 $T{{}_{n}}$ .

## 解答

1. （1）∵ $a{{}_{n}}-a{{}_{n+1}}=\frac {1}{2}\left ({a{{}_{n+1}}-3}\right )\left ({a{{}_{n}}-3}\right )$ ，
2. ∴ $2a{{}_{n}}-2a{{}_{n+1}}=\left ({a{{}_{n+1}}-3}\right )\left ({a{{}_{n}}-3}\right )$ ，即 $2\left ({a{{}_{n}}-3}\right )-2\left ({a{{}_{n+1}}-3}\right )=\left ({a{{}_{n+1}}-3}\right )\left ({a{{}_{n}}-3}\right )$ ，
3. ∴ $\frac {2}{a{{}_{n+1}}-3}-\frac {2}{a{{}_{n}}-3}=1\left ({a{{}_{n}}\ne 3}\right )$ ， $\frac {2}{a{{}_{1}}-3}=2$ .
4. ∴ $\left \{\frac {2}{a{{}_{n}}-3}\right \}$ 是首项为2，公差为1的等差数列.
5. （2）由（1）知， $\left \{\frac {2}{a{{}_{n}}-3}\right \}$ 是首项为2，公差为1的等差数列，
6. 所以 $\frac {2}{a{{}_{n}}-3}=2+n-1=n+1$ ，
7. 所以 $a{{}_{n}}-3=\frac {2}{n+1}$ ， $a{{}_{n+1}}-3=\frac {2}{n+2}$ ，
8. 所以 $b{{}_{n}}=\left ({a{{}_{n}}-3}\right )\left ({a{{}_{n+1}}-3}\right )=\frac {2}{n+1}\cdot \frac {2}{n+2}=4\left ({\frac {1}{n+1}-\frac {1}{n+2}}\right )$ ，
9. $T{{}_{n}}=b{{}_{1}}+b{{}_{2}}+\cdot \cdot \cdot +b{{}_{n}}=4\times \left ({\frac {1}{2}-\frac {1}{3}}\right )+4\times \left ({\frac {1}{3}-\frac {1}{4}}\right )+\cdot \cdot \cdot +4\left ({\frac {1}{n+1}-\frac {1}{n+2}}\right )$  $=4\times \left ({\frac {1}{2}-\frac {1}{n+2}}\right )=\frac {2n}{n+2}$ .

## 知识点

**中文**:
  - 数列求和方法之裂项相消法
  - 等差数列的概念及通项公式
  - 等差数列的判定与证明

**English**:
  - Telescoping Series Method
  - Concept and Formula
  - Determination and Proof

---
