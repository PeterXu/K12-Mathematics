# Mathematics - 题目 2606

**ID**: b17a50975574470e9e7610b6c1386b68
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
若简单多面体可以被分割成 $s\left ({s\geqslant 3}\right )$ 个完全相同的小多面体，则称该简单多面体为“ $m-$ 等和多面体”，其中 $m=V+E+F,V,E,F$ 分别表示简单多面体的顶点数、棱数、面数.​​​​​​​‌记每个小多面体的顶点数、棱数、面数分别为 $v{{}_{i}},e{{}_{i}}$ ， $f{{}_{i}}\left ({i=1,2,\cdots ,s}\right )$ ， $\sum \limits_{i=1}^{s}\mathop{v{{}_{i}}=V+a}$ ， $\sum \limits_{i=1}^{s}\mathop{e{{}_{i}}=E+b}$ ， $\sum \limits_{i=1}^{s}\mathop{f{{}_{i}}=F+c}$ （ $a,b,c$ 为与分割方式有关的正整数）.（1）已知长方体是“ $26-$ 等和多面体”，按分割方式：过长方体共顶点的三条棱的中点，各作一个与该棱垂直的平面，将长方体分割成若干个完全相同的小长方体，求该分割方式下 $s,a,b,c$ 的值；（2）判断正四面体 $ABCD$ 是否为“ $m-$ 等和多面体”.若是，请先描述一种分割方式，再求出该分割方式下 $m,s,a,b,c$ 的值；若不是，请说明理由；（3）若简单多面体是“ $m-$ 等和多面体”，求分割后小多面体的个数 $s$ 与 $a,b,c$ 的等量关系.参考公式：多面体欧拉定理可表示为“顶点数 $-$ 棱数 $+$ 面数 $=2$ ”，即 $V-E+F=2$ .

## 解答

1. （1）解：已知过长方体共顶点的三条棱的中点，各作一个与该棱垂直的平面，将长方体分割.在长方体每个维度上都被分割成两份，所以小长方体的个数为
2. $s=2\times 2\times 2=8$ ；
3. 原长方体顶点数 $V=8$ ，每个小长方体顶点数 $v{{}_{i}}=8$ ，
4. $\sum \limits_{i=1}^{s}\mathop{v{{}_{i}}}=8s=8\times 8=64$ ，
5. 又 $\sum \limits_{i=1}^{s}\mathop{v{{}_{i}}=V+a}$ ，
6. 所以 $a=\sum \limits_{i=1}^{s}\mathop{v{{}_{i}}}-V=64-8=56$ ；
7. 原长方体棱数 $E=12$ ，每个小长方体棱数 $e{{}_{i}}=12$ ，
8. $\sum \limits_{i=1}^{s}\mathop{e{{}_{i}}}=12s=12\times 8=96$ ，
9. 又因为 $\sum \limits_{i=1}^{s}\mathop{e{{}_{i}}}=E+b$ ，
10. 所以 $b=\sum \limits_{i=1}^{s}\mathop{e{{}_{i}}}-E=96-12=84$ ；
11. 原长方体面数 $F=6$ ，每个小长方体面数 $f{{}_{i}}=6$ ，
12. $\sum \limits_{i=1}^{s}\mathop{f{{}_{i}}}=6s=6\times 8=48$ ，
13. 又因为 $\sum \limits_{i=1}^{s}\mathop{f{{}_{i}}}=F+c$ ，
14. 所以 $c=\sum \limits_{i=1}^{s}\mathop{f{{}_{i}}}-F=48-6=42$ .
15. （2）解：正四面体 $V=4$ ， $E=6$ ， $F=4$ ， $m=V+E+F=14$ ，
16. 正四面体是“ $14-$ 等和多面体”.
17. 分割方式：将正四面体的每条棱三等分，连接各分点，可将正四面体分割成 $4$ 个完全相同的小正四面体，所以 $s=4$ .
18. 每个小正四面体顶点数 $v{{}_{i}}=4$ ，
19. $\sum \limits_{i=1}^{s}\mathop{v{{}_{i}}}=4s=4\times 4=16$ ，
20. 又 $\sum \limits_{i=1}^{s}\mathop{v{{}_{i}}}=V+a$ ，
21. 所以 $a=\sum \limits_{i=1}^{s}\mathop{v{{}_{i}}}-V=16-4=12$ ；
22. 每个小正四面体棱数 $e{{}_{i}}=6$ ，
23. $\sum \limits_{i=1}^{s}\mathop{e{{}_{i}}}=6s=6\times 4=24$ ，
24. 又因为 $\sum \limits_{i=1}^{s}\mathop{e{{}_{i}}}=E+b$ ，
25. 所以 $b=\sum \limits_{i=1}^{s}\mathop{e{{}_{i}}}-E=24-6=18$ ；
26. 每个小正四面体面数 $f{{}_{i}}=4$ ，
27. $\sum \limits_{i=1}^{s}\mathop{f{{}_{i}}}=4s=4\times 4=16$ ，
28. 又因为 $\sum \limits_{i=1}^{s}\mathop{f{{}_{i}}}=F+c$ ，
29. 所以 $c=\sum \limits_{i=1}^{s}\mathop{f{{}_{i}}}-F=16-4=12$ .
30. （3）利用欧拉公式建立等式：
31. 根据欧拉公式，对于原多面体有 $V-E+F=2$ ，
32. 对于每个小多面体有 $v{{}_{i}}-c{{}_{i}}+f{{}_{i}}=2$ ，
33. 对每个小多面体的欧拉公式两边同时乘以 $s$ 有
34. $v{{}_{i}}s-e{{}_{i}}s+f{{}_{i}}s=2s=\sum \limits_{i=1}^{s}\mathop{v{{}_{i}}}-\sum \limits_{i=1}^{s}\mathop{e{{}_{i}}}+\sum \limits_{i=1}^{s}\mathop{f{{}_{i}}}$ ，
35. 两式相减得 $\left ({\sum\limits_{i=1}^{s}\mathop{}v{{}_{i}}-\sum\limits_{i=1}^{s}\mathop{}e{{}_{i}}+\sum\limits_{i=1}^{s}\mathop{}f{{}_{i}}}\right )-\left ({V-E+F}\right )=2s-2$ ，
36. 即 $\left ({\sum\limits_{i=1}^{s}\mathop{}v{{}_{i}}-V}\right )-\left ({\sum\limits_{i=1}^{s}\mathop{}e{{}_{i}}-E}\right )+\left ({\sum\limits_{i=1}^{s}\mathop{}f{{}_{i}}-F}\right )=a-b+c=2s-2$ .

## 知识点

**中文**:
  - 新定义问题

**English**:
  - New Definition Problems

---
