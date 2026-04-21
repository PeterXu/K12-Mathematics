# Mathematics - 题目 2894

**ID**: 524e2bb0efd54c03a9107ad216b3240f
**年级**: Grade 10
**难度**: Medium
**题型**: Calculation

## 题目
某游戏厂商对新出品的一款游戏设定了“防沉迷系统”，设游玩时间为 $t$ ，规则如下：①当 $0<t\leqslant 3$ 的时间为健康时间，玩家在这段时间内获得的累计经验值 $E$ （单位：EXP）与游玩时间 $t$ （单位：小时）满足关系式： $E=t{^{2}}+20t+20a$ ；②当 $3<t\leqslant 5$ 的时间为疲劳时间，玩家在这段时间内获得的经验值为0（即累计经验值不变）：③当 $t>5$ 的时间为不健康时间，累计经验值开始损失，损失的经验值与不健康时间成正比例关系，正比例系数为50.​​​​​​​‌（1）写出 $E$ 与 $t$ 的函数关系式 $E=f\left ({t}\right )$ ，并求出当 $a=2$ ， $t=6$ 时的 $E$ 值；（2）该游戏厂商把 $E$ 与 $t$ 的比值称为“玩家愉悦指数”，记为 $H\left ({t}\right )$ .若 $a=\frac {5}{16}$ ，当 $t\leqslant 5$ 时，求 $H\left ({t}\right )$ 的最小值.

## 解答

1. （1）由题意可得，当 $0<t\leqslant 3$ 时，则 $f\left ({t}\right )=t{^{2}}+20t+20a$ ，
2. 且 $f\left ({3}\right )=3{^{2}}+20\times 3+20a=69+20a$ ；
3. 当 $3<t\leqslant 5$ 时，则 $f\left ({t}\right )=69+20a$ ；
4. 当 $t>5$ 时，则 $f\left ({t}\right )=69+20a-50\left ({t-5}\right )=-50t+20a+319$ ；
5. 综上所述：则 $f\left ({t}\right )=\begin{cases}t{^{2}}+20t+20a,0<t\leqslant 3\\20a+69,3<t\leqslant 5\\-50t+20a+319,t>5\end{cases}$ ，
6. 所以当 $a=2$ 时， $f\left ({6}\right )=-50\times 6+20\times 2+319=59\left ({{\rm{E}}{\rm{X}}{\rm{P}}}\right )$ ；
7. （2）由题可得 $a=\frac {5}{16}$ ，
8. 当 $0<t\leqslant 3$ 时， $H\left ({t}\right )=t+\frac {20a}{t}+20=t+\frac {25}{4t}+20\geqslant 2\sqrt {\frac {25}{4}}+20=25$ ，
9. 当且仅当 $t=\frac {25}{4t}$ ，即 $t=\frac {5}{2}$ 时，等号成立，
10. 当 $3<t\leqslant 5$ 时， $H\left ({t}\right )=\frac {20\times \frac {5}{16}+69}{t}=\frac {301}{4t}$ ，随着 $t$ 的增大， $H\left ({t}\right )$ 减小，
11. 所以当 $t=5$ 时， $H\left ({t}\right ){{}_{{\rm \min }}}=H\left ({5}\right )=\frac {301}{20}$ ，
12. 因为 $\frac {301}{20}<25$ ，所以当游玩时间为5小时， $H\left ({t}\right )$ 取到最小值为 $\frac {301}{20}$ .

## 知识点

**中文**:
  - 分段函数模型及应用

**English**:
  - Piecewise Function Model

---
