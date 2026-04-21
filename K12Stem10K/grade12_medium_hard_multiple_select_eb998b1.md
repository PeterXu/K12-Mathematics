# Mathematics - 题目 3890

**ID**: eb998b1b38fe4a5fbc9d5c29c284d600
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Multiple-select

## 题目
已知函数 $f\left ({x}\right )$ 的定义域为 ${\mathbf{R}}$ ， $f\left ({2x}\right )>2f\left ({x}\right )-1$ ，且当 $x<2$ 时， $f\left ({x}\right )=x$ ，则下列结论一定正确的是（      ）​​​​​​​‌

## 解答

1. 当 $x\in \left [{2{^{n}},2{^{n+1}}}\right )$ 时， $\frac {x}{2{^{n}}}\in \left [{1,2}\right )$ ，由题意知 $f\left ({x}\right )>2f\left ({\frac {x}{2}}\right )-1$ ，
2. 整理得 $f\left ({x}\right )-1>2\left [f\left ({\frac {x}{2}}\right )-1\right ]$ ，
3. 所以 $f\left ({x}\right )-1>2\left [f\left ({\frac {x}{2}}\right )-1\right ]>2{^{2}}\left [f\left ({\frac {x}{4}}\right )-1\right ]>\cdots >2{^{n}}\left [f\left ({\frac {x}{2{^{n}}}}\right )-1\right ]$ ，
4. 因此 $f\left ({x}\right )>x-2{^{n}}+1$ .
5. 对于 ${\rm A，}1024\in \left [{2{^{10}},2{^{11}}}\right )$ ，对应 $n=10$ ，
6. 所以 $f\left ({1024}\right )=f\left ({2{^{10}}}\right )>2{^{10}}-2{^{10}}+1=1$ ，故A正确；
7. 对于B，因为 $2025\in \left [{2{^{10}},2{^{11}}}\right )$ ，对应 $n=10$ ，
8. 所以 $f\left ({2025}\right )>2025-2{^{10}}+1=1002$ ，推不出 $f\left ({2025}\right )>1005$ ，故B错误；
9. 对于C，因为 $2{^{n}}+1\in \left [{2{^{n}},2{^{n+1}}}\right )$ ，所以 $f\left ({2{^{n}}+1}\right )>2{^{n}}+1-2{^{n}}+1=2$ ，
10. 所以 $f\left ({3}\right )+f\left ({5}\right )+f\left ({9}\right )+\cdots +f\left ({2{^{n}}+1}\right )>2n$ ，故C正确；
11. 对于D，因为 $f\left ({2{^{n}}+1}\right )>2$ ， $f\left ({2{^{n}}+2}\right )>3$ ， $f\left ({2{^{n}}+3}\right )>4$ ， $\cdots $ ， $f\left ({2{^{n}}+2{^{n}}-1}\right )>2{^{n}}$ ， $f\left ({2{^{n}}+2{^{n}}}\right )>1$ ，
12. 所以 $f\left ({2{^{n}}+1}\right )+f\left ({2{^{n}}+2}\right )+f\left ({2{^{n}}+3}\right )+\cdots +f\left ({2{^{n+1}}}\right )>1+2+3+4+\cdots +2{^{n}}$
13. $=\frac {2{^{n}}\left ({2{^{n}}+1}\right )}{2}=\frac {2{^{2n}}+2{^{n}}}{2}>\frac {2\sqrt {2{^{2n}}·2{^{n}}}}{2}=2{^{\frac {3n}{2}}}$ ，故D正确.
14. 故选ACD

## 知识点

**中文**:
  - 函数与不等式的综合问题

**English**:
  - Functions and Inequalities Combined

---
