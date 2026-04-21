# Mathematics - 题目 3604

**ID**: 3bee60d016384ac6aa77b5f33b983675
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: 填空题：本题共3小题，每小题5分，共15分．

## 题目
法国著名数学家傅里叶用一个纯粹的数学定理表述了周期性声音的规则特征：任何周期性声音的公式是形如 $A{\rm{s}}{\rm{i}}{\rm{n}}wt$ 的简单正弦函数之和．某种叠加音波的函数模型为 $f\left ({t}\right )={\rm{s}}{\rm{i}}{\rm{n}}t+\frac {1}{2}{\rm{s}}{\rm{i}}{\rm{n}}2t+\frac {1}{3}{\rm{s}}{\rm{i}}{\rm{n}}3t\left ({t\geqslant 0}\right )$ ，则函数 $f\left ({t}\right )$ 的最大值为．​​​​​​​‌

## 解答

1. $f\left ({t+2{\rm{\mathrm{π}}}}\right )={\rm{s}}{\rm{i}}{\rm{n}}\left ({t+2{\rm{\mathrm{π}}}}\right )+\frac {1}{2}{\rm{s}}{\rm{i}}{\rm{n}}\left ({2t+4{\rm{\mathrm{π}}}}\right )+\frac {1}{3}{\rm{s}}{\rm{i}}{\rm{n}}\left ({3t+6{\rm{\mathrm{π}}}}\right )$  $={\rm{s}}{\rm{i}}{\rm{n}}t+\frac {1}{2}{\rm{s}}{\rm{i}}{\rm{n}}2t+\frac {1}{3}{\rm{s}}{\rm{i}}{\rm{n}}3t=f\left ({t}\right )$ ，
2. 故 $f\left ({t}\right )={\rm{s}}{\rm{i}}{\rm{n}}t+\frac {1}{2}{\rm{s}}{\rm{i}}{\rm{n}}2t+\frac {1}{3}{\rm{s}}{\rm{i}}{\rm{n}}3t\left ({t\geqslant 0}\right )$ 的一个周期为 $2{\rm{\mathrm{π}}}$ ，
3. 考虑 $t\in \left [0,2{\rm{\mathrm{π}}}\right ]$ ， $f^{′}{\left ({t}\right )}={\cos}t+{\cos}2t+{\cos}3t$ ，
4. 其中 ${\cos}3t={\cos}\left ({2t+t}\right )={\cos}2t{\cos}t-\sin 2t\sin t=\left ({1-2\sin {^{2}}t}\right ){\cos}t-2\sin {^{2}}t{\cos}t$
5. $=\left ({1-4\sin {^{2}}t}\right ){\cos}t$ ，
6. $f^{′}{\left ({t}\right )}={\cos}t+{\cos}2t+\left ({1-4\sin {^{2}}t}\right ){\cos}t=\left ({2-4\sin {^{2}}t}\right ){\cos}t+{\cos}2t$
7. $=2{\cos}2t{\cos}t+{\cos}2t=\left ({2{\cos}t+1}\right ){\cos}2t=\left ({2{\cos}t+1}\right )\left ({2{\cos}{^{2}}t-1}\right )$
8. $=\left ({2{\cos}t+1}\right )\left ({\sqrt {2}{\cos}t+1}\right )\left ({\sqrt {2}{\cos}t-1}\right )$ ，
9. 令 $f^{′}{\left ({t}\right )}=0$ 得 $t=\frac {{\rm{\mathrm{π}}}}{4},\frac {{{2}}{\rm{\mathrm{π}}}}{3},\frac {{{3}}{\rm{\mathrm{π}}}}{4},\frac {{{5}}{\rm{\mathrm{π}}}}{4},\frac {{{4}}{\rm{\mathrm{π}}}}{3},\frac {{{7}}{\rm{\mathrm{π}}}}{4}$ ，
10. 当 $t\in \left ({0,\frac {{\rm{\mathrm{π}}}}{4}}\right )\cup \left ({\frac {{{2}}{\rm{\mathrm{π}}}}{3},\frac {{{3}}{\rm{\mathrm{π}}}}{4}}\right )\cup \left ({\frac {{{5}}{\rm{\mathrm{π}}}}{4},\frac {{{4}}{\rm{\mathrm{π}}}}{3}}\right )\cup \left ({\frac {{{7}}{\rm{\mathrm{π}}}}{4},2{\rm{\mathrm{π}}}}\right )$ 时， $f^{′}{\left ({t}\right )}>0$ ，
11. 当 $t\in \left ({\frac {{\rm{\mathrm{π}}}}{4},\frac {{{2}}{\rm{\mathrm{π}}}}{3}}\right )\cup \left ({\frac {{{3}}{\rm{\mathrm{π}}}}{4},\frac {{{5}}{\rm{\mathrm{π}}}}{4}}\right )\cup \left ({\frac {{{4}}{\rm{\mathrm{π}}}}{3},\frac {{{7}}{\rm{\mathrm{π}}}}{4}}\right )$ 时， $f^{′}{\left ({t}\right )}<0$ ，
12. 所以 $f\left ({t}\right )$ 在 $\left ({0,\frac {{\rm{\mathrm{π}}}}{4}}\right ),\left ({\frac {{{2}}{\rm{\mathrm{π}}}}{3},\frac {{{3}}{\rm{\mathrm{π}}}}{4}}\right ),\left ({\frac {{{5}}{\rm{\mathrm{π}}}}{4},\frac {{{4}}{\rm{\mathrm{π}}}}{3}}\right ),\left ({\frac {{{7}}{\rm{\mathrm{π}}}}{4},2{\rm{\mathrm{π}}}}\right )$ 上单调递增，
13. 在 $\left ({\frac {{\rm{\mathrm{π}}}}{4},\frac {{{2}}{\rm{\mathrm{π}}}}{3}}\right ),\left ({\frac {{{3}}{\rm{\mathrm{π}}}}{4},\frac {{{5}}{\rm{\mathrm{π}}}}{4}}\right ),\left ({\frac {{{4}}{\rm{\mathrm{π}}}}{3},\frac {{{7}}{\rm{\mathrm{π}}}}{4}}\right )$ 上单调递减，
14. 故 $f\left ({t}\right )$ 在 $t=\frac {{\rm{\mathrm{π}}}}{4},\frac {{{3}}{\rm{\mathrm{π}}}}{4},\frac {{{5}}{\rm{\mathrm{π}}}}{4}$ 处取得极大值，
15. 且 $f\left ({\frac {{\rm{\mathrm{π}}}}{4}}\right )={\rm{s}}{\rm{i}}{\rm{n}}\frac {{\rm{\mathrm{π}}}}{4}+\frac {1}{2}{\rm{s}}{\rm{i}}{\rm{n}}\frac {{\rm{\mathrm{π}}}}{2}+\frac {1}{3}{\rm{s}}{\rm{i}}{\rm{n}}\frac {{{3}}{\rm{\mathrm{π}}}}{4}=\frac {\sqrt {2}}{2}+\frac {1}{2}+\frac {1}{3}\times \frac {\sqrt {2}}{2}=\frac {1}{2}+\frac {2\sqrt {2}}{3}$ ，
16. $f\left ({\frac {{{3}}{\rm{\mathrm{π}}}}{4}}\right )={\rm{s}}{\rm{i}}{\rm{n}}\frac {{{3}}{\rm{\mathrm{π}}}}{4}+\frac {1}{2}{\rm{s}}{\rm{i}}{\rm{n}}\frac {{{3}}{\rm{\mathrm{π}}}}{2}+\frac {1}{3}{\rm{s}}{\rm{i}}{\rm{n}}\frac {{{9}}{\rm{\mathrm{π}}}}{4}=\frac {\sqrt {2}}{2}-\frac {1}{2}+\frac {1}{3}\times \frac {\sqrt {2}}{2}=-\frac {1}{2}+\frac {2\sqrt {2}}{3}$ ，
17. $f\left ({\frac {{{5}}{\rm{\mathrm{π}}}}{4}}\right )={\rm{s}}{\rm{i}}{\rm{n}}\frac {{{4}}{\rm{\mathrm{π}}}}{3}+\frac {1}{2}{\rm{s}}{\rm{i}}{\rm{n}}\frac {{{8}}{\rm{\mathrm{π}}}}{3}+\frac {1}{3}{\rm{s}}{\rm{i}}{\rm{n}}{{4}}\mathrm{π}=-\frac {\sqrt {3}}{2}+\frac {\sqrt {3}}{2}-\frac {1}{3}\times 0=0$ ，
18. 又 $f\left ({2{\rm{\mathrm{π}}}}\right )=f\left ({0}\right )=0$ ， $f\left ({\frac {{\rm{\mathrm{π}}}}{4}}\right )>f\left ({\frac {{{3}}{\rm{\mathrm{π}}}}{4}}\right )>f\left ({2{\rm{\mathrm{π}}}}\right )>f\left ({\frac {{{4}}{\rm{\mathrm{π}}}}{3}}\right )$ ，
19. 故 $f\left ({t}\right )$ 的最大值为 $\frac {1}{2}+\frac {2\sqrt {2}}{3}$ .

## 知识点

**中文**:
  - 在实际问题中建立三角函数模型

**English**:
  - Modeling Real-world Problems

---
