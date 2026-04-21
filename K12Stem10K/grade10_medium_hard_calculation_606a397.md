# Mathematics - 题目 1118

**ID**: 606a397a3e704073b9276e19ae8abd89
**年级**: Grade 10
**难度**: Medium-Hard
**题型**: Calculation

## 题目
人脸识别技术在社会各行各业中的应用深刻改变着人们的生活．所谓人脸识别，就是利用计算机分析人脸视频或者图象、并从中提取出有效的识别信息，最终判别对象的身份．在人脸识别中为了检测样本之间的相似度主要运用距离进行测试，经常使用的测量距离有曼哈顿距离和余弦距离．若二维空间有两个点 $A\left ({x{{}_{1}},y{{}_{1}}}\right ),B\left ({x{{}_{2}},y{{}_{2}}}\right )$ ，则A，B之间的曼哈顿距离为： $d(A,B)=\left |{x{{}_{1}}-x{{}_{2}}}\right |+\left |{y{{}_{1}}-y{{}_{2}}}\right |{\rm ．\mathit{A}，\mathit{B}}$ 之间的余弦距离为 $1-{\cos}(A,B)$ ，其中 ${\cos}(A,B)=\frac {x{{}_{1}}}{\sqrt {x{{}_{1}}{^{2}}+y{{}_{1}}{^{2}}}}\times \frac {x{{}_{2}}}{\sqrt {x{{}_{2}}{^{2}}+y{{}_{2}}{^{2}}}}+\frac {y{{}_{1}}}{\sqrt {x{{}_{1}^{2}}+y{{}_{1}^{2}}}}\times \frac {y{{}_{2}}}{\sqrt {x{{}_{2}}{^{2}}+y{{}_{2}}{^{2}}}}$ 为A，B之间的余弦相似度．（1）若 $A(2,1),B(1,2)$ ，求A，B之间的曼哈顿距离和余弦距离；​​​​​​​‌（2）已知 $0<α<β<\frac {{\rm{π}}}{2},M({\cos}α,\sin α),N({\cos}β,\sin β),P({\cos}(α+β),\sin (α+β))$ ，且 ${\cos}(M,N)=\frac {12}{13},{\cos}(M,P)=\frac {3}{5}$ ．①求N，P之间的余弦距离；②求N，P之间的曼哈顿距离．

## 解答

1. （1）由题意 $d(A,B)=\left |{x{{}_{1}}-x{{}_{2}}}\right |+\left |{y{{}_{1}}-y{{}_{2}}}\right |=\left |{2-1}\right |+\left |{1-2}\right |=2$ ；
2. 因为 ${\cos}\left ({A,B}\right )=\frac {x{{}_{1}}}{\sqrt {x{{}_{1}}{^{2}}+y{{}_{1}}{^{2}}}}\times \frac {x{{}_{2}}}{\sqrt {x{{}_{2}}{^{2}}+y{{}_{2}}{^{2}}}}+\frac {y{{}_{1}}}{\sqrt {x{{}_{1}^{2}}+y{{}_{1}^{2}}}}\times \frac {y{{}_{2}}}{\sqrt {x{{}_{2}}{^{2}}+y{{}_{2}}{^{2}}}}=\frac {2}{\sqrt {5}}\times \frac {1}{\sqrt {5}}+\frac {1}{\sqrt {5}}\times \frac {2}{\sqrt {5}}=\frac {4}{5}$ ，
3. 所以余弦距离为 $1-{\cos}(A,B)=\frac {1}{5}$ .
4. （2）①由题意 ${\rm{c}}{\rm{o}}{\rm{s}}(M,N)={\rm{c}}{\rm{o}}{\rm{s}}α{\rm{c}}{\rm{o}}{\rm{s}}β+{\rm{s}}{\rm{i}}{\rm{n}}α{\rm{s}}{\rm{i}}{\rm{n}}β={\rm{c}}{\rm{o}}{\rm{s}}(α-β)=\frac {12}{13}$ ，
5. 由 $0<α<β<\frac {{\rm{π}}}{2}$ ，可得 $-\frac {π}{2}<α-β<0$ ，故 $\sin \left ({α-β}\right )=-\sqrt {1-{\cos}{^{2}}\left ({α-β}\right )}=-\frac {5}{13}$ ；
6. 因 ${\rm{c}}{\rm{o}}{\rm{s}}\left ({M,P}\right )={\rm{c}}{\rm{o}}{\rm{s}}α{\rm{c}}{\rm{o}}{\rm{s}}\left ({α+β}\right )+{\rm{s}}{\rm{i}}{\rm{n}}α{\rm{s}}{\rm{i}}{\rm{n}}\left ({α+β}\right ){\rm{=}}{\rm{c}}{\rm{o}}{\rm{s}}{\rm{[}}{\rm{α}}{{-}}{\rm{(}}{\rm{α}}{{+}}{\rm{β}}{\rm{)}}{\rm{]}}={\rm{c}}{\rm{o}}{\rm{s}}β=\frac {3}{5}$ ，故 $\sin β=\frac {4}{5}$ ，
7. 则 ${\rm{c}}{\rm{o}}{\rm{s}}\left ({N,P}\right )={\rm{c}}{\rm{o}}{\rm{s}}β{\rm{c}}{\rm{o}}{\rm{s}}\left ({α+β}\right )+{\rm{s}}{\rm{i}}{\rm{n}}β{\rm{s}}{\rm{i}}{\rm{n}}\left ({α+β}\right )={\cos}\left [β-\left ({α+β}\right )\right ]={\rm{c}}{\rm{o}}{\rm{s}}α$ ，
8. 又 ${\cos}α={\cos}\left ({α-β+β}\right )={\cos}\left ({α-β}\right ){\cos}β-\sin \left ({α-β}\right )\sin β=\frac {12}{13}\times \frac {3}{5}-\left ({-\frac {5}{13}}\right )\times \frac {4}{5}=\frac {56}{65}$ ，
9. 所以N，P之间的余弦距离为 ${{1}}-{\rm{c}}{\rm{o}}{\rm{s}}(N,P)={{1}}-{\cos}α=\frac {9}{65}$ .
10. ②由①可知 $\sin 2β=2\sin β{\cos}β=\frac {24}{25}$ ， ${\cos}2β=2{\cos}{^{2}}β-1=-\frac {7}{25}$ ，
11. ${\rm{c}}{\rm{o}}{\rm{s}}(α+β)={\rm{c}}{\rm{o}}{\rm{s}}[(α-β)+2β]={\rm{c}}{\rm{o}}{\rm{s}}(α-β){\rm{c}}{\rm{o}}{\rm{s}}2β-{\rm{s}}{\rm{i}}{\rm{n}}(α-β){\rm{s}}{\rm{i}}{\rm{n}}2β$
12. $=\frac {12}{13}\times \left ({-\frac {7}{25}}\right )-\left ({-\frac {5}{13}}\right )\times \frac {24}{25}=\frac {36}{325}$ ，
13. 因 $0<α+β<π$ ，则 $\sin \left ({α+β}\right )=\sqrt {1-{\cos}{\left({α+β}\right)^{2}}}=\frac {323}{325}$ ，
14. 所以N，P之间的曼哈顿距离为：
15. $d(N,P)=\left |{{\rm{c}}{\rm{o}}{\rm{s}}β-{\rm{c}}{\rm{o}}{\rm{s}}(α+β)}\right |+\left |{\sin β-\sin (α+β)}\right |$  $=\left |{\frac {3}{5}-\frac {36}{325}}\right |+\left |{\frac {4}{5}-\frac {323}{325}}\right |=\frac {222}{325}$ .

## 知识点

**中文**:
  - 三角函数中的新定义问题
  - 三角恒等变换的综合应用

**English**:
  - New Definition Problems
  - Comprehensive Application of Identities

---
