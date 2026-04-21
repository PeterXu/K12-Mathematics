# Mathematics - 题目 1682

**ID**: 78c568bd1ea54858b2585b6ded272bfb
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
新冠肺炎疫情造成医用防护服短缺，某地政府决定为防护服生产企业A公司扩大生产提供 $x(x\in [0,10])$ (万元)的专项补贴，并以每套80元的价格收购其生产的全部防护服 ${\rm .​​​​​​​‌\mathit{A}}$ 公司在收到政府 $x$ (万元)补贴后，防护服产量将增加到 $t=k\cdot \left ({6-\frac {12}{x+4}}\right )$ (万件)，其中 $k$ 为工厂工人的复工率( $k\in [0.5,1]$ ).A公司生产 $t$ 万件防护服还需投入成本 $(20+9x+50t)$ (万元).（1）将A公司生产防护服的利润 $y$ (万元)表示为补贴 $x$ (万元)的函数；(政府补贴x万元计入公司收入)（2）在复工率为k时，政府补贴多少万元才能使A公司的防护服利润达到最大？（3）对任意的 $x\in [0,10]$ (万元)，当复工率 $k$ 达到多少时，A公司才能不产生亏损？（精确到0.01）.

## 解答

1. （1）根据已知条件列出关系式，即可得出答案；
2. （2）由 $y=180k-\frac {360k}{x+4}-8x-20=180k+12-8\left [\left ({x+4}\right )+\frac {45k}{x+4}\right ]$ ，进而结合基本不等式求出 $\left ({x+4}\right )+\frac {45k}{x+4}$ 的最小值，此时 $y$ 取得最大值，从而可求出答案；
3. （3）对任意的 $x\in \left [0,10\right ]$ （万元）， $A$ 公司都不产生亏损，可知 $180k-\frac {360k}{x+4}-8x-20\geqslant 0$ 在 $x\in \left [0,10\right ]$ 上恒成立，利用参变分离，可得 $180k\geqslant \frac {\left ({20+8x}\right )\left ({x+4}\right )}{x+2}$ ，求出 $\frac {\left ({20+8x}\right )\left ({x+4}\right )}{x+4}$ 的最大值，即可得出 $k$ 的值.
4. （1）由题意， $y=x+80t-\left ({20+9x+50t}\right )=30t-8x-20$
5. $=30k\cdot \left ({6-\frac {12}{x+4}}\right )-8x-20=180k-\frac {360k}{x+4}-8x-20$
6. 即 $y=180k-\frac {360k}{x+4}-8x-20,x\in \left [0,10\right ],k\in \left [0.5,1\right ]$ ；
7. （2） $y=180k-\frac {360k}{x+4}-8x-20=180k+12-8\left [\left ({x+4}\right )+\frac {45k}{x+4}\right ]$
8. 因为 $x\in \left [0,10\right ]$ ，所以 $4\leqslant x+4\leqslant 14$ ，所以 $\left ({x+4}\right )+\frac {45k}{x+4}\geqslant 2\sqrt {\left ({x+4}\right )\times \frac {45k}{x+4}}=6\sqrt {5k}$ 当且仅当 $x+4=\frac {45k}{x+4}$ ，即 $x=3\sqrt {5k}-4$ 时，等号成立，
9. 所以 $y=180k+12-8\left [\left ({x+4}\right )+\frac {45k}{x+4}\right ]\leqslant 180k+12-48\sqrt {5k}$
10. 故政府补贴为 $3\sqrt {5k}-4$ 万元才能使 $A$ 公司的防护服利润达到最大，最大为 $180k+12-48\sqrt {5k}$ 万元.
11. （3）对任意的 $x\in \left [0,10\right ]$ （万元）， $A$ 公司都不产生亏损，则 $180k-\frac {360k}{x+4}-8x-20\geqslant 0$ 在 $x\in \left [0,10\right ]$ 上恒成立
12. 不等式整理得， $180k\geqslant \frac {\left ({20+8x}\right )\left ({x+4}\right )}{x+2}$
13. 令 $m=x+2$ ，则 $m\in \left [2,12\right ]$ ，则 $\frac {\left ({20+8x}\right )\left ({x+4}\right )}{x+2}=\frac {\left ({8m+4}\right )\left ({m+2}\right )}{m}=8m+\frac {8}{m}+20$
14. 令 $y=m+\frac {1}{m},m\in \left [2,12\right ]$
15. 任取 $m{{}_{1}},m{{}_{2}}\in \left [2,12\right ]$ ，且 $m{{}_{1}}<m{{}_{2}}$
16. 则 $y{{}_{1}}-y{{}_{2}}=m{{}_{1}}-m{{}_{2}}+\frac {1}{m{{}_{1}}}-\frac {1}{m{{}_{2}}}=\frac {\left ({m{{}_{1}}-m{{}_{2}}}\right )\left ({m{{}_{1}}m{{}_{2}}-1}\right )}{m{{}_{1}}m{{}_{2}}}$
17. $\because 2\leqslant m{{}_{1}}<m{{}_{2}}\leqslant 12,\therefore m{{}_{1}}-m{{}_{2}}<0,m{{}_{1}}m{{}_{2}}-1>0$ ， $\therefore y{{}_{1}}<y{{}_{2}}$
18. 即函数 $h\left ({m}\right )=8m+\frac {8}{m}+20$ 在 $\left [2,12\right ]$ 上单调递增
19. 可得 $h\left ({m}\right ){{}_{{\rm \max }}}=h\left ({12}\right )=8\times 12+\frac {8}{12}+20=116+\frac {2}{3}$
20. 所以 $180k\geqslant 116+\frac {2}{3}$ ，即 $k\geqslant \frac {116+\frac {2}{3}}{180}\approx 0.65$
21. 所以当复工率 $k$ 达到0.65时，对任意的 $x\in \left [0,10\right ]$ （万元）， $A$ 公司都不产生亏损.

## 知识点

**中文**:
  - 基本不等式的实际应用
  - 建立拟合函数模型解决实际问题

**English**:
  - Real-world Applications
  - Fitting Function Models for Real Problems

---
