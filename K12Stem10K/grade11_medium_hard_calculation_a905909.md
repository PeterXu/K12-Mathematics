# Mathematics - 题目 795

**ID**: a90590926be148788a344f392994ac27
**年级**: Grade 11
**难度**: Medium-Hard
**题型**: Calculation

## 题目
已知正整数 $n\left ({n\geqslant 2}\right )$ ， ${\rm{Ω}}{{}_{n}}=\left \{\left ({i,j}\right )\left |{0\leqslant i<n,0\leqslant j<n,i\in {\rm{Z}},j\in {\rm{Z}}}\right .​​​​​​​‌\right \}$ ， $Γ$ 为 $Ω{{}_{n}}$ 的k元子集 $\left ({k\geqslant 2}\right )$ ，记 $Γ^{′}=\left \{\overrightarrow {{PQ}}\left |{P\in {\rm{Γ}},Q\in {\rm{Γ}},\overrightarrow {{PQ}}}\right .\right.$ 为非零向量 $\left..\right \}$ ，若 $Γ^{′}$ 的元素个数为 $k{^{2}}-k$ ，则称 $Γ$ 为 $Ω{{}_{n}}$ 的不重子集．(1)已知集合 $A=\left \{\left ({0,0}\right ),\left ({{{1}},0}\right ),\left ({{{2}},0}\right )\right \}$ ， $B=\left \{\left ({0,0}\right ),\left ({{{1}},0}\right ),\left ({{{2}},1}\right )\right \}$ ， $C=\left \{\left ({0,0}\right ),\left ({{{1}},1}\right ),\left ({{{2}},2}\right )\right \}$ ，这三个集合中，集合是 $Ω{{}_{3}}$ 的不重子集；若该集合新增m个元素后，仍为 $Ω{{}_{3}}$ 的不重子集，则m的最大值为，此时新增的这m个元素为；(2)若 $Γ$ 为 $Ω{{}_{5}}$ 的不重子集，且 $\forall \overrightarrow a,\overrightarrow b\in Γ^{′}$ ， $\overrightarrow a\cdot \overrightarrow b\ne 0$ ，求k的最大值；(3)若 $Γ$ 为 $Ω{{}_{5}}$ 的不重子集，则k的最大值为，直接在平面直角坐标系中给出一个使得k最大的 $Γ$ 的例子．

## 解答

1. （1）由题意得 $k=3$ ，根据题干得：若A为不重子集，则 $A^{′}=\left \{\left ({1,0}\right ),\left ({2,0}\right ),\left ({-1,0}\right ),\left ({-2,0}\right )\right \}$ ,
2. 其所含的元素个数为4，不是 $3{^{2}}-3=6$ ，故A不是 $Ω{{}_{3}}$ 的不重子集.
3. 若B为不重子集，则 $B^{′}=\left \{\left ({1,0}\right ),\left ({2,1}\right ),\left ({-1,0}\right ),\left ({-2,-1}\right ),\left ({-1,-1}\right ),\left ({1,1}\right )\right \}$ ,故B是 $Ω{{}_{3}}$ 的不重子集；
4. 若C为不重子集，则 $C^{′}=\left \{\left ({1,1}\right ),\left ({2,2}\right ),\left ({-1,-1}\right ),\left ({-2,-2}\right )\right \}$ ,元素个数为4，不等于6，故C不是 $Ω{{}_{3}}$ 的不重子集；
5. $m$ 的最大值为2，证明如下：
6. 
7. 如图，由题意已知点A,点B,点E已经在不重子集里，在从剩余的6个点里最多选择几个，
8. 显然点C是不能选的，这样 $\overrightarrow {{AB}}=\overrightarrow {{BC}}$ ,若选择点Q，则剩余的点一定都不选，
9. 会出现相等元素，此时 $m=1$ ；若选择点D，则点F，点H，点Q，点G不选
10. (若选G则有 $\overrightarrow {{GD}}=\overrightarrow {{EB}}$ )，此时 $m=1$ ;若选点F,则点D，点G，点Q不选，
11. 点H可选，此时 $m=2$ ；若选G点，剩余点都不选；若选H，同上，此时 $m=2$ ，
12. 故m最大值为2，增加的两个元素为 $\left ({0,2}\right )$ ， $\left ({2,2}\right )$ .
13. （2）k的最大值5，证明如下：
14. 由题意知， $Ω{{}_{5}}$ 中点的横、纵坐标均只有5种取值．
15. 一方面，若 $k\geqslant 6$ ，由抽屉原理知， $Γ$ 中必存在两个横坐标相同的点A，B，两个纵坐标相同的点C，D，
16. 则 $\overrightarrow {{AB}},\overrightarrow {{CD}}\in Γ^{′}$ ，且 $\overrightarrow {{AB}}\cdot \overrightarrow {{CD}}=0$ ，矛盾.另一方面，可以构造 $k=5$ 的满足题意的不重子集.
17. 
18. （3）k的最大值为8，可以构造 $k=8$ 的不重子集．
19. 根据向量不相等可排除性的选点，得到如下图所示，最大值为8.
20. 

## 知识点

**中文**:
  - 集合的新定义问题

**English**:
  - New Definition Problems in Sets

---
