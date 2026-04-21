# Mathematics - 题目 1199

**ID**: 01977d81e4a74e1c8ca0ee79f4dc988b
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
某工厂为扩大生产规模,今年年初新购置了一条高性能的生产线,该生产线在使用过程中的维护费用会逐年增加,第一年的维护费用是4万元,从第二年到第七年,每年的维护费用均比上年增加2万元,从第八年开始,每年的维护费用比上年增加25%（1）设第 $n$ 年该生产线的维护费用为 $a{{}_{n}}$ ,求 $a{{}_{n}}$ 的表达式;（2）若该生产线前 $n$ 年每年的平均维护费用大于12万元时,需要更新生产线,求该生产线前 $n$ 年每年的平均维护费用,并判断第几年年初需要更新该生产线?​​​​​​​‌

## 解答

1. （1）当 $n\leqslant 7$ 时，数列 $\left \{an\right \}$ 是首项为4，公差为2的等差数列， $an=4+2(n-1)=2n+2$ ，
2. 当 $n\geqslant 8$ 时，数列 $\left \{an\right \}$ 是首项为 $a7$ ，公比为 $\frac {5}{4}$ 的等比数列，又 $a7=16,\therefore an=16\times (\frac {5}{4}){^{n-7}}$
3. $\therefore an$ 的表达式为 $an=\begin{cases}2n+2,n\leqslant 7\\16\times {\left({\frac {5}{4}}\right)^{n-7}},n\geqslant 8\end{cases}$ ，
4. 设 $Sn$ 表示数列 $\left \{an\right \}$ 的前 $n$ 项和，由等差及等比数列的求和公式得
5. 当 $1\leqslant n\leqslant 7$ 时， $Sn=4n+n(n-1)=n{^{2}}+3n$
6. 当 $n\geqslant 8$ 时，由 $S{{}_7}=70$ ， $Sn=S{{}_7}+16\times \frac {5}{4}\times \frac {1-{\left({\frac {5}{4}}\right)^{n-7}}}{1-\frac {5}{4}}=80\times {\left({\frac {5}{4}}\right)^{n-7}}-10$
7. 该生产线前 $n$ 年每年平均的维护费用 $\frac {Sn}{n}=\begin{cases}n+3,1\leqslant n\leqslant 7\\\frac {80\times {\left({\frac {5}{4}}\right)^{n-7}}-10}{n},n\geqslant 8\end{cases}$
8. 当 $1\leqslant n\leqslant 7$ 时， $\left \{\frac {Sn}{an}\right \}$ 为递增数列，
9. 当 $n\geqslant 8$ 时， $\because \frac {Sn+1}{n+1}-\frac {Sn}{n}=\frac {80\times {\left({\frac {5}{4}}\right)^{n-7}}\times \left ({\frac {n}{4}-1}\right )+10}{n(n+1)}>0$ ， $\left \{\frac {Sn}{n}\right \}$ 也为递增数列，
10. 又 $\frac {Sn}{7}=10<12,\frac {Sn}{8}=11.25<12,\frac {Sn}{9}\approx 12.78>12$ ，
11. 则第9年初需要更新该生产线.

## 知识点

**中文**:
  - 递推数列模型

**English**:
  - Recurrence Sequence Models

---
