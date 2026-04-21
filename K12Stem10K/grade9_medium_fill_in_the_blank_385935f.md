# Mathematics - 题目 3183

**ID**: 385935f710d64cedbaf269b026ad6bea
**年级**: Grade 9
**难度**: Medium
**题型**: Fill-in-the-blank

## 题目
我们规定：如果一个自然数A的个位数字不为0，且能分解成 $m\times n$ ，其中m与n都是两位数，m与n的十位数字相同，个位数字之和为10，则称数A为“十合数”，并把数A分解成 $A=m\times n$ 的过程，称为“十合分解”．例如：因为 $616=22\times 28{\rm ，22}$ 和28的十位数字相同，个位数字之和为10，所以616是“十合数”，616分解成 $616=22\times 28$ 的过程就是“十合分解”．按照这个规定，最小的“十合数”是；​​​​​​​‌把一个“十合数”A进行“十合分解”，即 $A=m\times n$ ，若 $F(A)=m+n$ ， $G(A)=\left |{m-n}\right |$ ，令 $H(A)=\frac {F(A)}{G(A)}$ ，若 $H(A)$ 能被3整除，则满足条件的A的最小值为．

## 解答

1. 解：设m和n的十位数字为 $y\left ({1\leqslant y\leqslant 9}\right ){\rm ，\mathit{m}}$ 的个位数字为 $x\left ({1\leqslant x\leqslant 9}\right )$ ，则n的个位数字为 $10-x$ ，其中x，y均为整数．
2. ∵最小“十合数”，
3. ∴取 $y=1,x=1$ 或9，
4. 此时 $A=\left ({10\times 1+1}\right )\times \left ({10\times 1+9}\right )=11\times 19=209$ ．
5. 根据题意得： $F\left ({A}\right )=m+n=10y+x+10y+\left ({10-x}\right )=20y+10$ ，
6. $G\left ({A}\right )=\left |{m-n}\right |=\left |{10y+x-10y-\left ({10-x}\right )}\right |=2\left |{x-5}\right |$ ，
7. ∴ $H\left ({A}\right )=\frac {F\left ({A}\right )}{G\left ({A}\right )}=\frac {20y+10}{2\left |{x-5}\right |}=\frac {5\left ({2y+1}\right )}{\left |{x-5}\right |}$ ，
8. ∵ $H\left ({A}\right )$ 能被3整除，
9. ∴ $\frac {5\left ({2y+1}\right )}{3\left |{x-5}\right |}$ 为整数，
10. ∵“十合数”最小，
11. ∴y优先取最小数，
12. 当 $y=1$ 时， $\frac {5\left ({2y+1}\right )}{3\left |{x-5}\right |}=\frac {5}{\left |{x-5}\right |}$ ，
13. 此时 $x=4$ 或6，
14. ∴当 $y=1$ ， $x=4$ 时，“十合数”最小，
15. 此时 $m=14,n=16$ ，
16. $A=m\times n=14\times 16=224$ ．

## 知识点

**中文**:
  - 代数推理

**English**:
  - Algebraic Reasoning

---
