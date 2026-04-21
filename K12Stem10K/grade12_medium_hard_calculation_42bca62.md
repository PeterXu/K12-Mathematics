# Mathematics - 题目 1049

**ID**: 42bca624e08f4cf9b1aa6ebd20bedd91
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
定义:设三角形ABC的内角 $A，B，C$ 的对边分别为 $a，b，c$ ，若其所在平面内一点O满足 $\sin A\cdot \overrightarrow {{OA}}+\sin B\cdot \overrightarrow {{OB}}+\sin C\cdot \overrightarrow {{OC}}=$  $\overrightarrow 0$ ，则称点O为三角形ABC的正弦分点.​​​​​​​‌（1）证明:点O为三角形ABC的内心；（2）已知O为坐标原点，动点P到x轴的距离为d，且 $\left |{OP}\right |{^{2}}=λ+μd{^{2}}$ ，其中 $λ,μ$ 均为常数，动点P的轨迹称为 $(λ,μ)$ 曲线.${\rm （i）}$ 已知曲线 $Γ{{}_{1}}$ 为 $(1,\frac {4}{3})$ 曲线，其左顶点为A，右焦点为F，若点 $P{{}_{1}}$ 是曲线 $Γ{{}_{1}}$ 右支上的一点，三角形 $P{{}_{1}}AF$ 的正弦分点为Q，证明:点Q在曲线 $Γ{{}_{1}}$ 上；${\rm （ii）}$ 已知曲线 $Γ{{}_{2}}$ 为 $(3,\frac {2}{3})$ 曲线，其焦点分别为 $F{{}_{1}}$ ， $F{{}_{2}}$ ，若点 $P{{}_{2}}$ 是曲线 $Γ{{}_{2}}$ 上的一点，三角形 $P{{}_{2}}F{{}_{1}}F{{}_{2}}$ 的正弦分点为 ${\rm I}$ ，则是否存在两定点 $R,T$ ，使得 $\left |{IR}\right |+\left |{IT}\right |$ 恒为定值，若存在，求出此定值，若不存在，则说明理由.

## 解答

1. （1）由正弦定理可知 $a\cdot \overrightarrow {{OA}}+b\cdot \overrightarrow {{OB}}+c\cdot \overrightarrow {{OC}}=\overrightarrow 0$
2. 则 $\frac {a}{a+b}\cdot \overrightarrow {{OA}}+\frac {b}{a+b}\cdot \overrightarrow {{OB}}=-\frac {c}{a+b}\cdot \overrightarrow {{OC}}$ .
3. 记 $\overrightarrow {{OD}}=\frac {a}{a+b}\cdot \overrightarrow {{OA}}+\frac {b}{a+b}\cdot \overrightarrow {{OB}}$ ，
4. 由于 $\frac {a}{a+b}+\frac {b}{a+b}=1$ ，
5. 所以 $D$ 在直线 $AB$ 上，
6. 且 $\frac {\left |{\overrightarrow {{AD}}}\right |}{\left |{\overrightarrow {{DB}}}\right |}=\frac {\left |{\overrightarrow {{OD}}-\overrightarrow {{OA}}}\right |}{\left |{\overrightarrow {{OB}}-\overrightarrow {{OD}}}\right |}=\frac {\frac {b}{a+b}\left |{\overrightarrow {{OB}}-\overrightarrow {{OA}}}\right |}{\frac {a}{a+b}\left |{\overrightarrow {{OB}}-\overrightarrow {{OA}}}\right |}=\frac {b}{a}=\frac {CA}{CB}$ ，
7. 所以 $D$ 在角 $C$ 的角平分线上，
8. 又因为 $\overrightarrow {{OD}}=-\frac {c}{a+b}\cdot \overrightarrow {{OC}}$ ，
9. 所以 $O,C,D$ 三点共线，
10. 即 $O$ 在角 $C$ 的角平分线上，
11. 同理可得 $O$ 在角 $\mathrm{A}$ ，角 $B$ 的角平分线上，
12. 即 $O$ 为 $\vartriangle ABC$ 的内心.
13. （2） ${\rm （i）}\left |{OP}\right |{^{2}}=x{^{2}}+y{^{2}}$ ， $d{^{2}}=y{^{2}}$ ，则 $x{^{2}}+y{^{2}}=1+\frac {4}{3}y{^{2}}$ ，
14. 即 $Γ{{}_{1}}:x{^{2}}-\frac {y{^{2}}}{3}=1$ ， $A\left ({-1,0}\right )$ ， $F\left ({2,0}\right )$ ，
15. 设 $Q\left ({m,n}\right )$ ，则 $k{{}_{AQ}}=\frac {n}{m+1}$ ， $k{{}_{FQ}}=\frac {n}{m-2}$
16. 设直线 $AP{{}_{1}}$ ： $y=k{{}_{1}}\left ({x+1}\right )$ ，直线 $FP{{}_{1}}$ ： $y=k{{}_{2}}\left ({x-2}\right )$ ，
17. $\begin{cases}y=k{{}_{1}}\left ({x+1}\right )\\y=k{{}_{2}}\left ({x-2}\right )\end{cases}\Rightarrow $  $x{{}_{P{{}_{1}}}}=\frac {-k{{}_{1}}-2k{{}_{2}}}{k{{}_{1}}-k{{}_{2}}}$ ， $y{{}_{P{{}_{1}}}}=\frac {-3k{{}_{1}}k{{}_{2}}}{k{{}_{1}}-k{{}_{2}}}$ .
18. 代入 $Γ{{}_{1}}$ 可得 $2k{{}_{1}}k{{}_{2}}+k{{}_{2}^{2}}-k{{}_{1}^{2}}k{{}_{2}^{2}}=0$ .
19. 显然 $k{{}_{1}},k{{}_{2}}\ne 0$ ,否则 $A,F,P{{}_{1}}$ 三点共线构成不了三角形.
20. 故 $2k{{}_{1}}+k{{}_{2}}-k{{}_{1}^{2}}k{{}_{2}}=0$ ，即 $\frac {2}{k{{}_{2}}}=k{{}_{1}}-\frac {1}{k{{}_{1}}}$ ①
21. 由（1）可知 $Q$ 为 $△AFP{{}_{1}}$ 的内心.，不妨设 $P{{}_{1}}$ 在第一象限，
22. 故 $k{{}_{2}}=\frac {2k{{}_{FQ}}}{1-k{{}_{FQ}^{2}}}$ ， $k{{}_{1}}=\frac {2k{{}_{AQ}}}{1-k{{}_{AQ}^{2}}}$ 代入①可得 $\frac {1}{k{{}_{FQ}}}-k{{}_{FQ}}=k{{}_{1}}-\frac {1}{k{{}_{1}}}$ ，
23. 则 $\frac {1}{k{{}_{FQ}}}=k{{}_{1}}$ （舍去，注： $k{{}_{FQ}}<0,k{{}_{1}}>0$ ）或者 $-k{{}_{FQ}}=k{{}_{1}}$ ，
24. 即 $-\frac {n}{m-2}=\frac {2n\left ({m+1}\right )}{{\left({m+1}\right)^{2}}-n{^{2}}}\Rightarrow m{^{2}}-\frac {n{^{2}}}{3}=1$ .
25. 
26. ${\rm （ii）}x{^{2}}+y{^{2}}=3+\frac {2}{3}y{^{2}}$ ，
27. 即 $Γ{{}_{2}}:\frac {x{^{2}}}{3}+\frac {y{^{2}}}{9}=1$ ， $F{{}_{1}}\left ({0,\sqrt {6}}\right )$ ， $F{{}_{2}}\left ({0,-\sqrt {6}}\right )$ ，设 $P{{}_{2}}\left ({x{{}_{0}},y{{}_{0}}}\right )$ ， $I\left ({x,y}\right )$ ，
28. $\left |{P{{}_{2}}F{{}_{1}}}\right |=3-\frac {\sqrt {6}}{3}y{{}_{0}}$ ， $\left |{P{{}_{2}}F{{}_{2}}}\right |=3+\frac {\sqrt {6}}{3}y{{}_{0}}$
29. $\overrightarrow {{IF{{}_{1}}}}=\left ({-x,\sqrt {6}-y}\right )$ ， $\overrightarrow {{IF{{}_{2}}}}=\left ({-x,-\sqrt {6}-y}\right )$ ， $\overrightarrow {{IP{{}_{2}}}}=\left ({x{{}_{0}}-x,y{{}_{0}}-y}\right )$ ，
30. 则 $2\sqrt {6}\overrightarrow {{IP{{}_{2}}}}+\left ({3+\frac {\sqrt {6}}{3}y{{}_{0}}}\right )\overrightarrow {{IF{{}_{1}}}}+\left ({3-\frac {\sqrt {6}}{3}y{{}_{0}}}\right )\overrightarrow {{IF{{}_{2}}}}=0$ ，
31. 即 $2\sqrt {6}\left ({x{{}_{0}}-x,y{{}_{0}}-y}\right )+\left ({3+\frac {\sqrt {6}}{3}y{{}_{0}}}\right )\left ({-x,\sqrt {6}-y}\right )+\left ({3-\frac {\sqrt {6}}{3}y{{}_{0}}}\right )\left ({-x,-\sqrt {6}-y}\right )=0$ ，
32. 解得 $x{{}_{0}}=\left ({1+\frac {\sqrt {6}}{2}}\right )x$ ， $y{{}_{0}}=\left ({\frac {3+\sqrt {6}}{2+\sqrt {6}}}\right )y$ ，
33. 则 $\frac {x{^{2}}}{\frac {6}{5+2\sqrt {6}}}+\frac {y{^{2}}}{6}=1$ ，
34. 即 $I$ 的轨迹为椭圆，则 $\left |{IR}\right |+\left |{IT}\right |=2\sqrt {6}$ .
35. 

## 知识点

**中文**:
  - 定点定值定直线问题
  - 曲线与方程

**English**:
  - Fixed Point, Value, Line Problems
  - Curves and Equations

---
