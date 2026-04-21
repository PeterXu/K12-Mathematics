# Mathematics - 题目 2728

**ID**: ef08894914f6481f9c5d5b4273c307a7
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
设 $T>0$ ，对定义在 ${\mathbf{R}}$ 上的函数 $f\left ({x}\right )$ ，若存在常数 $\mathrm{S}$ ，使得 $f\left ({x+T}\right )=f\left ({x}\right )+S$ 对任意 $x\in {\mathbf{R}}$ 恒成立，则称函数 $f\left ({x}\right )$ 满足性质 $P\left ({T}\right )$ ．（1）判断下列函数是否具有性质 $P\left ({2}\right )$ ？① $f{{}_{1}}\left ({x}\right )={\rm{s}}{\rm{i}}{\rm{n}}{\rm{π}}x$ ，② $f{{}_{2}}\left ({x}\right )=x{^{2}}$ ，③ $f{{}_{3}}\left ({x}\right )=2x+1$ ．（2）若函数 $f\left ({x}\right )$ 具有性质 $P\left ({T{{}_{1}}}\right ),P\left ({T{{}_{2}}}\right )$ ，其中 $T{{}_{2}}>T{{}_{1}}>0$ ，求证：函数 $f\left ({x}\right )$ 具有性质 $P\left ({T{{}_{2}}-T{{}_{1}}}\right )$ ；​​​​​​​‌（3）设函数 $F\left ({x}\right )=f\left ({x}\right )+g\left ({x}\right )$ 具有性质 $P\left ({T}\right )$ ，其中 $f\left ({x}\right )$ 是奇函数， $g\left ({x}\right )$ 是偶函数．若 $f\left ({\frac {T}{2}}\right )=1$ ，求 $f\left ({\frac {2023T}{2}}\right )$ 的值．

## 解答

1. （1）①因为 $f{{}_{1}}\left ({x+2}\right )={\rm{s}}{\rm{i}}{\rm{n}}\left [{\rm{π}}\left ({x+2}\right )\right ]={\rm{s}}{\rm{i}}{\rm{n}}{\rm{π}}x=f{{}_{1}}\left ({x}\right )$ ，所以 $f{{}_{1}}\left ({x}\right )$ 具有性质 $P\left ({2}\right )$ ；
2. ②因为 $f{{}_{2}}\left ({x+2}\right )={\left({x+2}\right)^{2}}=x{^{2}}+4x+4\ne f{{}_{2}}\left ({x}\right )+s$ ，所以  $f{{}_{2}}\left ({x}\right )$ 不具有性质 $P\left ({2}\right )$ ；
3. ③ $f{{}_{3}}\left ({x+2}\right )=2\left ({x+2}\right )+1=f{{}_{3}}\left ({x}\right )+4$ ，所以具有性质 $P\left ({2}\right )$ ．
4. （2）因为函数 $f\left ({x}\right )$ 具有性质 $P\left ({T{{}_{2}}}\right )$ ，则存在常数 $S{{}_{2}}$ ，使得
5. $f\left ({x+T{{}_{2}}}\right )=f\left ({x}\right )+S{{}_{2}}$ 对任意 $x\in {\mathbf{R}}$ 恒成立．
6. 因为函数 $f\left ({x}\right )$ 具有性质 $P\left ({T{{}_{1}}}\right )$ ，则存在常数 $S{{}_{1}}$ ，使得
7. $f\left ({x+T{{}_{1}}}\right )=f\left ({x}\right )+S{{}_{1}}$ ，对任意 $x\in {\mathbf{R}}$ 恒成立，
8. 故 $f\left ({x-T{{}_{1}}+T{{}_{1}}}\right )=f\left ({x-T{{}_{1}}}\right )+S{{}_{1}}$ ，即 $f\left ({x-T{{}_{1}}}\right )=f\left ({x}\right )-S{{}_{1}}$ 也对任意 $x\in {\mathbf{R}}$ 恒成立，
9. 因此 $f\left ({x+T{{}_{2}}-T{{}_{1}}}\right )=f\left ({x+T{{}_{2}}}\right )-S{{}_{1}}=f\left ({x}\right )+S{{}_{2}}-S{{}_{1}}$ 对任意 $x\in {\mathbf{R}}$ 恒成立．
10. 又因为 $T{{}_{2}}>T{{}_{1}}>0$
11. 所以函数 $f\left ({x}\right )$ 具有性质 $P\left ({T{{}_{2}}-T{{}_{1}}}\right )$ ．
12. （3）由已知存在 $\mathrm{S}$ 满足 $F\left ({x+T}\right )=F\left ({x}\right )+S$ ，即 $f\left ({x+T}\right )+g\left ({x+T}\right )=f\left ({x}\right )+g\left ({x}\right )+S$ ，
13. 令 $x=a$ ，则 $f\left ({a+T}\right )+g\left ({a+T}\right )=f\left ({a}\right )+g\left ({a}\right )+S$ ①，
14. 令 $x+T=-a$ ，则 $f\left ({-a}\right )+g\left ({-a}\right )=f\left ({-a-T}\right )+g\left ({-a-T}\right )+S$ ②，
15. 因为 $f\left ({x}\right )$ 是奇函数， $g\left ({x}\right )$ 是偶函数，
16. 所以 $f\left ({-a}\right )=-f\left ({a}\right ),g\left ({-a}\right )=g\left ({a}\right ),f\left ({-a-T}\right )=-f\left ({a+T}\right ),g\left ({-a-T}\right )=g\left ({a+T}\right )$ ，
17. ①+②，整理得 $f\left ({a+T}\right )=f\left ({a}\right )+S$ ，
18. 令 $a=-\frac {T}{2}$ ，则 $f\left ({\frac {T}{2}}\right )=f\left ({-\frac {T}{2}}\right )+S$ ，即 $f\left ({\frac {T}{2}}\right )=\frac {S}{2}$ ，
19. 又因为 $f\left ({\frac {T}{2}}\right )=1$ ，所以 $S=2$ ，
20. 所以 $f\left ({\frac {2023T}{2}}\right )=f\left ({1011T+\frac {T}{2}}\right )=f\left ({1010T+\frac {T}{2}}\right )+2=\cdots =1011\times 2+f\left ({\frac {T}{2}}\right )=2023.$

## 知识点

**中文**:
  - 函数奇偶性的应用
  - 函数新定义问题

**English**:
  - Applications of Parity
  - New Definition Problems in Functions

---
