# Mathematics - 题目 2423

**ID**: 43cb537021db43b78ef8bf8e7058227b
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
在某一次联考中，高三（9）班前10名同学的数学成绩 $x{{}_{i}}\left ({i=1,2,\ldots ,10}\right )$ 和物理成绩 $y{{}_{i}}\left ({i=1,2,\ldots ,10}\right )$ 如下表：学生编号12345678910数学成绩11613112412612111010699118117数学名次71324891056物理成绩80787981746563707384物理名次35426910871(1)从这10名同学任取一名，已知该同学数学优秀（成绩在120分（含）以上），则该同学物理也优秀（物理成绩在78分（含）以上）的概率；(2)已知该校高中生的数学成绩 $x$ ，物理成绩 $y$ ，化学成绩 $z$ 两两成正相关关系，经计算这10名同学的数学成绩 $x$ 和物理成绩 $y$ 的样本相关系数约为0.​​​​​​​‌8，已知这10名同学物理成绩 $y$ 与化学成绩 $z$ 的样本相关系数约为 $\frac {12}{13}$ ，分析相关系数的向量意义，求 $x,z$ 的样本相关系数的最大值.(3)设 $N$ 为正整数，变量 $x$ 和变量 $y$ 的一组样本数据为 $\left \{\left ({x{{}_{i}},y{{}_{i}}}\right )∣i=1,2,\ldots ,N\right \}$ ，其中 $x{{}_{i}}\left ({i=1,2,\ldots ,N}\right )$ 两两不相同， $y{{}_{i}}\left ({i=1,2,\ldots ,N}\right )$ 两两不相同，按照由大到小的顺序，记 $x{{}_{i}}$ 在 $\left \{x{{}_{n}}∣n=1,2,\ldots ,N\right \}$ 中排名是 $s{{}_{i}}$ 位 $\left ({i=1,2,\ldots ,N}\right ),y{{}_{i}}$ 在 $\left \{y{{}_{n}}∣n=1,2,\ldots ,N\right \}$ 中的排名是 $w{{}_{i}}$ 位 $\left ({i=1,2,\ldots ,N}\right )$ .定义变量 $x$ 和变量 $y$ 的斯皮尔曼相关系数（记为 $ρ$ ）为变量 $x{{}_{i}}$ 的排名 $s{{}_{i}}$ 和变量 $y{{}_{i}}$ 的排名 $w{{}_{i}}$ 的样本相关系数.记 $d{{}_{i}}=s{{}_{i}}-w{{}_{i}}$ ，其中 $i=1,2,\ldots N$ ，证明： $ρ=1-\frac {6}{N\left ({N{^{2}}-1}\right )}\sum\limits_{i=1}^{N}\mathop{}d{{}_{i}^{2}}$ ，并用上述公式求这组学生的数学成频和物理成绩的斯皮尔曼相关系数（精确到0.01）（参考公式：相关系数 $r=\frac {\sum\limits_{l=1}^{n}\mathop{}\left ({x{{}_{{\rm i}}}-\bar x}\right )\left ({y{{}_{{\rm i}}}-\bar y}\right )}{\sqrt {\sum\limits_{{\rm i}=1}^{n}\mathop{}\left ({x{{}_{{\rm i}}}-\bar x}\right )}\sqrt {\sum\limits_{l=1}^{n}\mathop{}{\left({y{{}_{{\rm i}}}-\bar y}\right)^{2}}}},\sum\limits_{{\rm i}=1}^{n}\mathop{}{\rm i}{^{2}}=\frac {n(n+1)(2n+1)}{6}$ ）

## 解答

1. （1）由题意可得数学优秀的学生有4名，这4名中物理优秀的有3名同学，
2. 由条件根概率公式可得 $P=\frac {3}{4}$ ；
3. （2）分析r的向量意义，设 $\overrightarrow a=\left ({x{{}_{1}}-\bar x,x{{}_{2}}-\bar x,\ldots ,x{{}_{n}}-\bar x}\right ),\overrightarrow b=\left ({y{{}_{1}}-\bar y,y{{}_{2}}-\bar y,\ldots ,y{{}_{n}}-\bar y}\right )$ ，则 $r=\frac {\overrightarrow a\cdot \overrightarrow b}{\left |{\overrightarrow a}\right |\cdot \left |{\overrightarrow b}\right |}={\rm{c}}{\rm{o}}{\rm{s}}\left \langle {\overrightarrow a,\overrightarrow b}\right \rangle $ ，
4. 分别令 $x,y$ 的样本相关系数 $r{{}_{1}}={\rm{c}}{\rm{o}}{\rm{s}}α$ ， $y,z$ 的样本相关系数 $r{{}_{2}}={\rm{c}}{\rm{o}}{\rm{s}}β$ ， $x$ 与 $z$ 的样本相关系数为 $r{{}_{3}}={\rm{c}}{\rm{o}}{\rm{s}}r$ ，
5. 则 ${\rm{c}}{\rm{o}}{\rm{s}}α=\frac {4}{5},{\rm{c}}{\rm{o}}{\rm{s}}β=\frac {12}{13}$ ，
6. $\because α,β\in \left [0,{\rm{π}}\right ]$ ， $\sin α=\sqrt {1-{\cos}{^{2}}α}=\frac {3}{5},\sin β=\sqrt {{{1}}-{\rm{c}}{\rm{o}}{\rm{s}}{^{2}}β}=\frac {5}{13}$ ，
7. $\therefore ({\rm{c}}{\rm{o}}{\rm{s}}r){{}_{{\rm{m}}{\rm{a}}{\rm{x}}}}={\rm{c}}{\rm{o}}{\rm{s}}\left ({α-β}\right )={\cos}α{\cos}β+\sin α\sin β=\frac {4}{5}\times \frac {12}{13}+\frac {3}{5}\times \frac {5}{13}=\frac {63}{65}$ ，
8. $\therefore x,z$ 夹角余弦值最大值为 $\frac {63}{65}$ ；
9. （3） $\because \left \{s{{}_{i}}\right \}\left \{ω{{}_{i}}\right \}$ 都是 $1,2,\ldots ,N$ 的一个排列，
10. $\therefore \sum \limits_{i=1}^{N}\mathop{s{{}_{i}}}=\sum \limits_{i=1}^{N}\mathop{ω{{}_{i}}}=\frac {N(N+1)}{2}$
11. $\sum \limits_{i=1}^{N}\mathop{s{{}_{i}^{2}}}=\sum \limits_{i=1}^{N}\mathop{ω{{}_{i}^{2}}}=\frac {N(N+1)(2N+1)}{6},{\overline{s}}={\overline{ω}}=\frac {N+1}{2},$
12. $\sum \limits_{i=1}^{N}\mathop{{\left({s{{}_{i}}-{\overline{s}}}\right)^{2}}}=\sum \limits_{i=1}^{N}\mathop{s{{}_{i}^{2}}}-2\bar s\sum \limits_{i=1}^{N}\mathop{s{{}_{i}}}+N\cdot \bar s{^{2}}$
13. $=\sum \limits_{i=1}^{N}\mathop{s{{}_{i}^{2}}}-N{\overline{s}}{^{2}}=\frac {N(N+1)(2N+1)}{6}-\frac {N(N+1){^{2}}}{4}$
14. $=\frac {N(N+1)(N-1)}{12}$
15. 同理 $\sum \limits_{i=1}^{N}\mathop{{\left({ω{{}_{i}}-{\overline{ω}}}\right)^{2}}}=\frac {N(N+1)(N-1)}{12},\sum \limits_{i=1}^{N}\mathop{d{{}_{i}^{2}}}=\sum \limits_{i=1}^{N}\mathop{{\left({s{{}_{i}}-ω{{}_{i}}}\right)^{2}}}=\sum \limits_{i=1}^{N}\mathop{\left [\left ({s{{}_{i}}-\bar s}\right )-\left ({ω{{}_{i}}-\bar ω}\right )\right ]{^{2}}}$
16. $=\sum \limits_{i=1}^{N}\mathop{{\left({s{{}_{i}}-\bar s}\right)^{2}}}+\sum \limits_{i=1}^{N}\mathop{{\left({ω{{}_{i}}-\bar ω}\right)^{2}}}-2\sum \limits_{i=1}^{N}\mathop{\left ({s{{}_{i}}-\bar s}\right )\left ({ω{{}_{i}}-\bar ω}\right )}$
17. $=2\frac {N(N+1)(N-1)}{12}-2\sum \limits_{i=1}^{N}\mathop{\left ({s{{}_{i}}-\bar s}\right )\left ({ω{{}_{i}}-\bar ω}\right )}$
18. $\therefore ρ=\frac {\sum \limits_{i=1}^{N}\mathop{\left ({s{{}_{i}}-\bar s}\right )\left ({ω{{}_{i}}-\bar ω}\right )}}{\sqrt {\sum \limits_{i=1}^{N}\mathop{{\left({s{{}_{i}}-{\overline{s}}}\right)^{2}}}\sum \limits_{i=1}^{N}\mathop{{\left({ω{{}_{i}}-{\overline{ω{{}_{i}}}}}\right)^{2}}}}}=\frac {\frac {N(N+1)(N-1)}{12}-\frac {1}{2}\sum \limits_{i=1}^{N}\mathop{d{{}_{i}^{2}}}}{\frac {N(N+1)(N-1)}{12}}$
19. $=1-\frac {6}{N\left ({N{^{2}}-1}\right )}\sum \limits_{i=1}^{N}\mathop{d{{}_{i}^{2}}}$ .
20. 结合图表 $ρ=1-\frac {6}{10\times 99}\left ({4{^{2}}+4{^{2}}+1{^{2}}+0{^{2}}+2{^{2}}+1{^{2}}+1{^{2}}+2{^{2}}+2{^{2}}+5{^{2}}}\right )\approx 0.56$

## 知识点

**中文**:
  - 变量间的相关关系
  - 相关系数r

**English**:
  - Correlation Relationship
  - Correlation Coefficient r

---
