# Mathematics - 题目 2867

**ID**: 3169c7b63f51462f85c5712d6ed55483
**年级**: Grade 12
**难度**: Medium-Hard
**题型**: Calculation

## 题目
人脸识别技术在各行各业的应用改变着人类的生活，所谓人脸识别，就是利用计算机分析人脸视频或者图像，并从中提取出有效的识别信息，最终判别对象的身份，在人脸识别中为了检测样本之间的相似度主要应用距离的测试，常用测量距离的方式有曼哈顿距离和余弦距离.​​​​​​​‌若二维空间有两个点 $A\left ({x{{}_{1}},y{{}_{1}}}\right )$ ， $B\left ({x{{}_{2}},y{{}_{2}}}\right )$ ，则曼哈顿距离为： $d\left ({A,B}\right )=\left |{x{{}_{1}}-x{{}_{2}}}\right |+\left |{y{{}_{1}}-y{{}_{2}}}\right |$ ，余弦相似度为： ${\cos}\left ({A,B}\right )=\frac {x{{}_{1}}}{\sqrt {x{{}_{1}^{2}}+y{{}_{1}^{2}}}}\times \frac {x{{}_{2}}}{\sqrt {x{{}_{2}^{2}}+y{{}_{2}^{2}}}}+\frac {y{{}_{1}}}{\sqrt {x{{}_{1}^{2}}+y{{}_{1}^{2}}}}\times \frac {y{{}_{2}}}{\sqrt {x{{}_{2}^{2}}+y{{}_{2}^{2}}}}$ ，余弦距离为 $1-{\cos}\left ({A,B}\right )$(1)若 $A\left ({-1,2}\right )$ ， $B\left ({\frac {3}{5},\frac {4}{5}}\right )$ ，求A，B之间的曼哈顿距离 $d\left ({A,B}\right )$ 和余弦距离；(2)已知 $0<α<β<\frac {{\rm{π}}}{2}$ ， $M\left ({5{\cos}α,5\sin α}\right )$ 、 $N\left ({13{\cos}β,13\sin β}\right )$ ， $P\left ({5{\cos}\left ({α+β}\right ),5\sin \left ({α+β}\right )}\right )$ ，若 ${\cos}\left ({M,P}\right )=\frac {5}{13}$ ， ${\cos}\left ({M,N}\right )=\frac {63}{65}$ ，求M、P之间的曼哈顿距离.

## 解答

1. （1）由题设定义知： $d\left ({A,B}\right )=|-1-\frac {3}{5}|+|2-\frac {4}{5}|=\frac {14}{5}$ ，
2. ${\cos}\left ({A,B}\right )=\frac {-1}{\sqrt {5}}\times \frac {3}{5}+\frac {2}{\sqrt {5}}\times \frac {4}{5}=\frac {\sqrt {5}}{5}$ ，则余弦距离为 $1-\frac {\sqrt {5}}{5}$ ；
3. （2） ${\cos}\left ({M,P}\right )={\cos}α\times {\cos}(α+β)+\sin α\times \sin (α+β)={\cos}β=\frac {5}{13}$ ，又 $0<β<\frac {{\rm{π}}}{2}$ ，则 $\sin β=\frac {12}{13}$ ，
4. ${\cos}\left ({M,N}\right )={\cos}α\times {\cos}β+\sin α\times \sin β=\frac {63}{65}$ ，则 $\frac {5}{13}{\cos}α+\frac {12}{13}\sin α=\frac {63}{65}$ ，
5. 所以 $5{\cos}α+12\sin α=\frac {63}{5}$ ，结合 $\sin {^{2}}α+{\cos}{^{2}}α=1$ ， $0<α<\frac {{\rm{π}}}{2}$ ，
6. 所以 $169\times 25\sin {^{2}}α-2\times 63\times 60\sin α+3344=0$ ，可得 $\sin α=\frac {4}{5}$ 或 $\sin α=\frac {836}{845}$ ，
7. 由 $0<α<β<\frac {{\rm{π}}}{2}$ ，即 $\sin β=\frac {12}{13}>\sin α$ ，故 $\sin α=\frac {4}{5}$ ，则 ${\cos}α=\frac {3}{5}$ ，
8. ${\cos}\left ({α+β}\right )={\cos}α{\cos}β-\sin α\sin β=\frac {3}{5}\times \frac {5}{13}-\frac {4}{5}\times \frac {12}{13}=-\frac {33}{65}$ ，
9. $\sin \left ({α+β}\right )=\sin α{\cos}β+{\cos}α\sin β=\frac {4}{5}\times \frac {5}{13}+\frac {3}{5}\times \frac {12}{13}=\frac {56}{65}$ ，
10. 所以 $M\left ({3,4}\right )$ ， $P\left ({-\frac {33}{13},\frac {56}{13}}\right )$ ，则 $d\left ({M,P}\right )=\left |{3+\frac {33}{13}}\right |+\left |{4-\frac {56}{13}}\right |=\frac {72}{13}+\frac {4}{13}=\frac {76}{13}$ .

## 知识点

**中文**:
  - 三角函数中的新定义问题
  - 两角和与差的余弦公式
  - 两角和与差的正弦公式

**English**:
  - New Definition Problems
  - Cosine of Sum and Difference
  - Sine of Sum and Difference

---
