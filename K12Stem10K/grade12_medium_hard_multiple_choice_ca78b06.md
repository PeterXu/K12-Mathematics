# Mathematics - 题目 3387

**ID**: ca78b063fcab43a0902b66f1d8973a44
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: 选择题(本大题共10小题，每小题4分，共40分．在每小题给出的四个选项中，只有一项是符合题目要求

## 题目
已知数列{a_{n}}满足a_{1}＝1，a_{n}_{＋}_{1}＝a_{n}－ $\frac{1}{3}$ a_{n}^{2}(n∈N^{*})，则（      ）​​​​​​​‌

## 解答

1. 本题考查数列的递推关系．由a_{n}_{＋}_{1}＝a_{n}－ $\frac{1}{3}$a_{n}^{2}＝－ $\frac{1}{3}{\begin{pmatrix}{a}_{n}-\frac{3}{2}\end{pmatrix}}^{2}$ ＋ $\frac{3}{4}$ ⩽ $\frac{3}{4}$ 及a_{n}≠0，得 $\frac{{a}_{n+1}}{{a}_{n}}$ ＝1－ $\frac{1}{3}$a_{n}⩾ $\frac{3}{4}$ >0(n⩾2)．又a_{1}＝1，所以a_{2}＝a_{1}－ $\frac{1}{3}$a_{1}^{2}＝ $\frac{2}{3}$ ＞0，所以a_{n}>0.由于a_{n}_{＋}_{1}＝a_{n}$\begin{pmatrix}1-\frac{1}{3}{a}_{n}\end{pmatrix}$ ，则 $\frac{1}{{a}_{n+1}}$ － $\frac{1}{{a}_{n}}$ ＝ $\frac{1}{3-{a}_{n}}$ > $\frac{1}{3}$ ，所以 $\frac{1}{{a}_{2}}$ － $\frac{1}{{a}_{1}}$ > $\frac{1}{3}$ ， $\frac{1}{{a}_{3}}$ － $\frac{1}{{a}_{2}}$ > $\frac{1}{3}$ ，…， $\frac{1}{{a}_{n+1}}$ － $\frac{1}{{a}_{n}}$ > $\frac{1}{3}$ ，累加得 $\frac{1}{{a}_{n+1}}$ － $\frac{1}{{a}_{1}}$ > $\frac{1}{3}$n，所以 $\frac{1}{{a}_{n+1}}$ > $\frac{1}{3}$n＋1，则 $\frac{1}{{a}_{100}}$ > $\frac{99}{3}$ ＋1＝34，所以a_{100}< $\frac{1}{34}$ ，100a_{100}< $\frac{50}{17}$ <3.由 $\frac{1}{{a}_{n+1}}$ ＞ $\frac{1}{3}$n＋1，可得 $\frac{1}{{a}_{n}}$ ＞ $\frac{1}{3}$ (n－1)＋1，即a_{n}＜ $\frac{3}{n+2}$ (n⩾2)，又a_{1}＝1，所以a_{n}⩽ $\frac{3}{n+2}$ ，则 $\frac{1}{{a}_{n+1}}$ － $\frac{1}{{a}_{n}}$ ＝ $\frac{1}{3-{a}_{n}}$ ⩽ $\frac{1}{3-\frac{3}{n+2}}$ ＝ $\frac{1}{3}\begin{pmatrix}1+\frac{1}{n+1}\end{pmatrix}$ ，所以 $\frac{1}{{a}_{2}}$ － $\frac{1}{{a}_{1}}$ ⩽ $\frac{1}{3}$ × $\begin{pmatrix}1+\frac{1}{2}\end{pmatrix}$ ， $\frac{1}{{a}_{3}}$ － $\frac{1}{{a}_{2}}$ ⩽ $\frac{1}{3}$ × $\begin{pmatrix}1+\frac{1}{3}\end{pmatrix}$ ，…， $\frac{1}{{a}_{n+1}}$ － $\frac{1}{{a}_{n}}$ ⩽ $\frac{1}{3}\begin{pmatrix}1+\frac{1}{n+1}\end{pmatrix}$ ，累加得 $\frac{1}{{a}_{n+1}}$ － $\frac{1}{{a}_{1}}$ ⩽ $\frac{1}{3}$n＋ $\frac{1}{3}$ ( $\frac{1}{2}$ ＋ $\frac{1}{3}$ ＋…＋ $\frac{1}{n+1}$ )，故 $\frac{1}{{a}_{n+1}}$ ⩽ $\frac{1}{3}$n＋ $\frac{1}{3}\begin{pmatrix}\frac{1}{2}+\frac{1}{3}+\dots +\frac{1}{n+1}\end{pmatrix}$ ＋1，所以 $\frac{1}{{a}_{100}}$ ⩽34＋ $\frac{1}{3}$ × $\begin{pmatrix}\frac{1}{2}+\frac{1}{3}+\dots +\frac{1}{100}\end{pmatrix}$ <34＋ $\frac{1}{3}$ ( $\frac{1}{2}$ ×6＋ $\frac{1}{8}$ ×93)<40，a_{100}> $\frac{1}{40}$ ，100a_{100}> $\frac{5}{2}$ .综上可知 $\frac{5}{2}$ <100a_{100}<3，故选B.

## 知识点

**中文**:
  - 数列的递推公式
  - 数列通项求法之累加法

**English**:
  - Recurrence Formula
  - Accumulation Method (Telescoping Sums)

---
