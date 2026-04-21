# Mathematics - 题目 1496

**ID**: 4dbfccbe7a784aba8b3bb608a271b4e4
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
某大学有甲､乙两个运动场.​​​​​​​‌假设同学们可以任意选择其中一个运动场锻炼，也可选择不锻炼，一天最多锻炼一次，一次只能选择一个运动场.若同学们每次锻炼选择去甲或乙运动场的概率均为 $\frac {1}{2}$ ，每次选择相互独立.设王同学在某个假期的三天内去运动场锻炼的次数为 $X$ ，已知 $X$ 的分布列如下：（其中 $a>0,0<p<1$ ）$X$0123$P$$a(1-p){^{2}}$$\frac {a}{p}$$a$$a\left ({1-p}\right )$(1)记事件 $A{{}_{i}}$ 表示王同学假期三天内去运动场锻炼 $i$ 次 $\left ({i=0,1,2,3}\right )$ ，事件 $B$ 表示王同学在这三天内去甲运动场锻炼的次数大于去乙运动场锻炼的次数.当 $p=\frac {1}{2}$ 时，试根据全概率公式求 $P\left ({B}\right )$ 的值；(2)是否存在实数 $p$ ，使得 $E\left ({X}\right )=\frac {5}{3}$ ？若存在，求 $p$ 的值；若不存在，请说明理由；(3)记 $M$ 表示事件“甲运动场举办锻炼有奖的抽奖活动”， $N$ 表示事件“王同学去甲运动场锻炼”， $0<P\left ({M}\right )<1$ .已知王同学在甲运动场举办锻炼有奖的抽奖活动的情况下去甲运动场锻炼的概率，比不举办抽奖活动的情况下去甲运动场锻炼的概率大，证明： $P\left ({M∣N}\right )>P\left ({M∣\bar N}\right )$ .

## 解答

1. （1）当 $p=\frac {1}{2}$ 时， $P\left ({A{{}_{0}}}\right )=\frac {a}{4},P\left ({A{{}_{1}}}\right )=2a,P\left ({A{{}_{2}}}\right )=a,P\left ({A{{}_{3}}}\right )=\frac {a}{2}$ ，
2. 则 $\frac {a}{4}+2a+a+\frac {a}{2}=1$ ，解得 $a=\frac {4}{15}$ .
3. 由题意，得 $P\left ({B∣A{{}_{1}}}\right )={\rm{C}}{{}_{1}^{1}}\times \frac {1}{2},P\left ({B∣A{{}_{2}}}\right )={\rm{C}}{{}_{2}^{2}}{\left({\frac {1}{2}}\right)^{2}},P\left ({B∣A{{}_{3}}}\right )={\rm{C}}{{}_{3}^{2}}{\left({\frac {1}{2}}\right)^{3}}+{\rm{C}}{{}_{3}^{3}}{\left({\frac {1}{2}}\right)^{3}}$ .
4. 由全概率公式，得 $P(B)=\sum \limits_{i=1}^{3}\mathop{P}\left ({B∣A{{}_{i}}}\right )P\left ({A{{}_{i}}}\right )=a+{\rm{C}}{{}_{2}^{2}}{\left({\frac {1}{2}}\right)^{2}}a+\left [{\rm{C}}{{}_{3}^{2}}{\left({\frac {1}{2}}\right)^{3}}+{\rm{C}}{{}_{3}^{3}}{\left({\frac {1}{2}}\right)^{3}}\right ]\times \frac {a}{2}$
5. $=a+\frac {a}{4}+\frac {a}{4}=\frac {3}{2}a=\frac {3}{2}\times \frac {4}{15}=\frac {2}{5}.$
6. （2）由 $\frac {a}{p}+a+a\left ({1-p}\right )+a(1-p){^{2}}=1$ ，得 $\frac {1}{a}=p{^{2}}-3p+\frac {1}{p}+3$ .
7. 假设存在 $p$ ，使 $E\left ({X}\right )=\frac {a}{p}+2a+3a\left ({1-p}\right )=\frac {5}{3}$ .
8. 将上述两式左右分别相乘，得 $\frac {1}{p}+5-3p=\frac {5p{^{2}}}{3}-5p+\frac {5}{3p}+5$ ，化简得： $5p{^{3}}-6p{^{2}}+2=0$ .
9. 设 $h\left ({p}\right )=5p{^{3}}-6p{^{2}}+2$ ，则 $h^{′}{\left ({p}\right )}=15p{^{2}}-12p=3p\left ({5p-4}\right )$ .
10. 由 $h^{′}{\left ({p}\right )}<0$ ，得 $0<p<\frac {4}{5}$ ，由 $h^{′}{\left ({p}\right )}>0$ ，得 $\frac {4}{5}<p<1$ ，
11. 则 $h\left ({p}\right )$ 在 $\left ({0,\frac {4}{5}}\right )$ 上单调递减，在 $\left ({\frac {4}{5},1}\right )$ 上单调递增，所以 $h\left ({p}\right )$ 的最小值为 $h(p){{}_{{\rm \min }}}=h\left ({\frac {4}{5}}\right )=\frac {18}{25}>0$ ，
12. 所以不存在 $p{{}_{0}}$ 使得 $h\left ({p{{}_{0}}}\right )=0$ .即不存在 $p$ 值，使得 $E\left ({X}\right )=\frac {5}{3}$ .
13. （3）由题知 $P(N∣M)>P(N∣\bar M)$ ，所以 $\frac {P(NM)}{P(M)}>\frac {P(N\bar M)}{P(\bar M)}=\frac {P(N)-P(NM)}{1-P(M)}$ ，因 $0<P(M)<1$ ，
14. 故 $P\left ({NM}\right )>P\left ({N}\right )P\left ({M}\right )$ ，
15. 所以 $P\left ({NM}\right )-P\left ({N}\right )P\left ({NM}\right )>P\left ({N}\right )P\left ({M}\right )-P\left ({N}\right )P\left ({NM}\right )$ ，
16. 即 $P\left ({NM}\right )\cdot P\left ({\bar N}\right )>P\left ({N}\right )\cdot P\left ({\bar NM}\right )$ ，
17. 所以 $\frac {P(NM)}{P(N)}>\frac {P(\bar NM)}{P({\overline{N}})}$ ，即 $P(M∣N)>P(M∣\bar N)$ .

## 知识点

**中文**:
  - 全概率公式
  - 条件概率

**English**:
  - Law of Total Probability
  - Conditional Probability

---
