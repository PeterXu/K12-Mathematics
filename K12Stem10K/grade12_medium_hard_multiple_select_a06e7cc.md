# Mathematics - 题目 1850

**ID**: a06e7cc81d3244bfbd423c0749a08d98
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Multiple-select

## 题目
已知正方体 $ABCD-{A}_{1}{B}_{1}{C}_{1}{D}_{1}$ 的棱长为1,点 $P$ 满足 $\overrightarrow {AP}=x\overrightarrow {AB}+y\overrightarrow {AD}+z\overrightarrow {A{A}_{1}}$ ,其中 $x$ , $y$ , $z\in [0,1]$ ,则（      ）​​​​​​​‌

## 解答

1. 以 $A$ 为坐标原点， $AB$ , $AD$ , $A{A}_{1}$ 所在直线分别为 $x$ , $y$ , $z$ 轴建立空间直角坐标系，如图所示，则 $A(0,0,0)$ , $B(1,0,0)$ , $C(1,1,0)$ , $D(0,1,0)$ ， ${A}_{1}(0,0,1)$ , ${B}_{1}(1,0,1)$ ， ${C}_{1}(1,1,1)$ , ${D}_{1}(0,1,1)$ ，因为 $\overrightarrow {AP}=x\overrightarrow {AB}+y\overrightarrow {AD}+z\overrightarrow {A{A}_{1}}$ ，所以 $P(x,y,z)$ .
2. 对于 $\mathrm{A}$ ， $\overrightarrow {AP}=(x,x,z)$ , $\overrightarrow {CP}=(x-1,x-1,z)$ ， $\overrightarrow {BD}=(-1,1,0)$ ，
3. 因为 $\begin{cases}\overrightarrow {AP}\cdot \overrightarrow {BD}=-x+x=0,\\\overrightarrow {CP}\cdot \overrightarrow {BD}=-x+1+x-1=0,\end{cases}$ 所以 $\overrightarrow {BD}$ 是平面 $ACP$ 的一个法向量.又因为 $\overrightarrow {B{B}_{1}}=(0,0,1)$ ,所以 $\overrightarrow {B{B}_{1}}\cdot \overrightarrow {BD}=0$ ，所以 $\overrightarrow {B{B}_{1}}\perp \overrightarrow {BD}$ ,又 $B{B}_{1}\not\subset $  平面 $ACP$ ,所以 $B{B}_{1}//$ 平面 $ACP$ ，故$\mathrm{A}$正确；
4. 
5. 对于 $\mathrm{B}$ ，设 $x=y=z=a\ne 0$ ，则 $\overrightarrow {AP}=(a,a,a)$ ， $\overrightarrow {BC}=(0,1,0)$ ，设异面直线 $AP$ 与 $BC$ 所成的角为 $\alpha $  ，则 $\cos \alpha =\frac{|\overrightarrow {AP}\cdot \overrightarrow {BC}|}{|\overrightarrow {AP}||\overrightarrow {BC}|}=\frac{a}{\sqrt{3}a}=\frac{\sqrt{3}}{3}\ne \frac{\sqrt{2}}{2}$ ，所以 $\alpha \ne {45}^{\circ }$  ，故$\mathrm{B}$错误；
6. 对于 $\mathrm{C}$ ，设 $x=a$ ，则 $P(a,1-a,0)$ ，所以 $\overrightarrow {{D}_{1}P}=(a,-a,-1)$ .又 $\overrightarrow {{A}_{1}{C}_{1}}=(1,1,0)$ ，则 $\overrightarrow {{D}_{1}P}\cdot \overrightarrow {{A}_{1}{C}_{1}}=a-a=0$ ，所以 ${D}_{1}P\perp {A}_{1}{C}_{1}$ ，故$\mathrm{C}$正确；
7. 对于 $\mathrm{D}$ ， $|\overrightarrow {AP}|=\sqrt{{x}^{2}+{y}^{2}+{z}^{2}}$ ，因为 $x+y+z=1$ ，所以 $1={x}^{2}+{y}^{2}+{z}^{2}+2xy+2xz+2yz\leqslant {x}^{2}+{y}^{2}+{z}^{2}+{x}^{2}+{y}^{2}+{x}^{2}+{z}^{2}+{y}^{2}+{z}^{2}=3({x}^{2}+{y}^{2}+{z}^{2})$ ，所以 ${x}^{2}+{y}^{2}+{z}^{2}\geqslant \frac{1}{3}$ ，当且仅当 $x=y=z$ 时取等号（提示:连续使用基本不等式时，一定要注意取等条件的一致性），所以 $|\overrightarrow {AP}|=\sqrt{{x}^{2}+{y}^{2}+{z}^{2}}\geqslant \sqrt{\frac{1}{3}}=\frac{\sqrt{3}}{3}$ ，故$\mathrm{D}$正确.故选$\mathrm{A}\mathrm{C}\mathrm{D}$ .

## 知识点

**中文**:
  - 向量法求异面直线所成角
  - 用向量证明平行问题
  - 用向量证明垂直问题

**English**:
  - Angle between Skew Lines
  - Proving Parallelism
  - Proving Perpendicularity

---
