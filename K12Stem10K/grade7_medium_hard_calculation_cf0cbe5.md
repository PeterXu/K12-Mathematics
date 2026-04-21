# Mathematics - 题目 968

**ID**: cf0cbe56278b45a48a464b04bbccdb82
**年级**: Grade 7
**难度**: Medium-Hard
**题型**: Calculation

## 题目
【初步感知】（1）如图 1，已知 $\vartriangle ABC$为等边三角形，点D为边$BC$  上一动点（点D不与点B，点C重合）．以  $AD$ 为边向右侧作等边 $\vartriangle ADE$ ，连接$CE$ ．求证： $\mathrm{△}ABD≌\mathrm{△}ACE$ ；​​​​​​​‌【类比探究】（2）如图 2，若点D在边  $BC$的延长线上，随着动点D的运动位置不同，猜想并证明：①  $AB$与  $CE$的位置关系为：_；②线段  $EC$、  $AC$、  $CD$之间的数量关系为：_ ．【拓展应用】（3）如图 3，在等边  $\vartriangle ABC$中， $AB=5$ ，点P是边  $AC$上一定点且$AP=2$ ，若点D为射线  $BC$上动点，以 $DP$  为边向右侧作等边 $\vartriangle DPE$  ，连接  $CE$、 $BE$  ．请问：$PE$   $+BE$  是否有最小值？若有，请直接写出其最小值；若没有，请说明理由．

![images/968_73b2a68ff192e1a2.png](images/968_73b2a68ff192e1a2.png)

## 解答

1. （1）证明：∵ $\vartriangle ABC$ 和 $\vartriangle ADE$ 是等边三角形，
2. ∴ $AB=AC$ ， $AD=AE$ ， $\angle BAC=\angle DAE=60{}^\circ $ ，
3. ∵ $\angle BAC=\angle DAE$ ，
4. ∴ $\angle BAC-\angle DAC=\angle DAE-\angle DAC$
5. 即 $\angle BAD=\angle CAE$
6. 在 $\mathrm{△}ABD$ 和 $△ACE$ 中，
7. $\begin{cases}AB=AC\\\angle BAD=\angle CAE\\AD=AE\end{cases}$  ，
8. ∴ $\vartriangle ABD{\rm{≌}}\vartriangle ACE{\rm{（}}{\rm{S}}{\rm{A}}{\rm{S}}{\rm{）}}$ ；
9. （2）平行， $EC=AC+CD$ ，理由如下：
10. 由（1）得 $\vartriangle ABD{\rm{≌}}\vartriangle ACE{\rm{（}}{\rm{S}}{\rm{A}}{\rm{S}}{\rm{）}}$ ，
11. ∴ $\angle B=\angle ACE=60{}^\circ $ ， $CE{\rm{=}}BD$ ，
12. ∴ $\angle BAC=\angle ACE=60{}^\circ $ ，
13. ∴ $AB{\rm{/\mskip-4mu/}}CE$ ，
14. ∵ $CE=BD$ ， $AC=BC$ ，
15. ∴ $CE=BD=BC+CD=AC+CD$ ；
16. （3）有最小值，理由如下：
17. 如图，在射线 $BC$ 上取一点 $M$ ，使得 $DM=PC$ ，连接 $EM$ ，
18. 
19. ∵ $\vartriangle ABC$ 和 $\vartriangle DPE$ 是等边三角形，
20. ∴ $PE=ED$ ， $\angle DEP=\angle ACB=60{}^\circ $ ，
21. ∴ $\angle ACD=180{}^\circ -\angle ACB=180{}^\circ -60{}^\circ =120{}^\circ $ ，
22. ∴ $\angle ACD+\angle DEP=120{}^\circ +60{}^\circ =180{}^\circ $ ，
23. 由三角形内角和为 $180{}^\circ $ ，可知： $\angle PCE+\angle CEP+\angle EPC=180{}^\circ $ ， $\angle ECD+\angle CDE+\angle CED=180{}^\circ $ ，
24. ∴ $\angle PCE+\angle CEP+\angle EPC+\angle ECD+\angle CDE+\angle CED=360{}^\circ $ ，
25. 又∵ $\angle PCE+\angle ECD+\angle CEP+\angle CED=\angle ACD+\angle DEP=180{}^\circ $ ，
26. ∴ $\angle EPC+\angle CDE=360{}^\circ -180{}^\circ =180{}^\circ $ ，
27. ∵ $\angle EDM+\angle CDE=180{}^\circ $ ，
28. ∴ $∠EPC=∠EDM$ ，
29. 在 $ΔEPC$ 和 $ΔEDM$ 中，
30. $\begin{cases}PE=ED\\\angle EPC=\angle EDM\\PC=DM\end{cases}$  ，
31. $△EPC{\rm{≌}}△EDM{\rm{（}}{\rm{S}}{\rm{A}}{\rm{S}}{\rm{）}}$ ，
32. ∴ $EC{\rm{=}}EM$ ， $\angle PEC{\rm{=}}\angle DEM$ ，
33. ∵ $\angle PEC+\angle CED{\rm{=}}\angle DEP=60{}^\circ $ ，
34. ∴ $\angle CEM=\angle DEM+\angle CED=60{}^\circ $ ，
35. ∴ $ΔCEM$ 是等边三角形，
36. ∴ $\angle ECD=60{}^\circ $ ， $\angle ACE=180{}^\circ -\angle ECD-\angle ACB={{1}}{{8}}{{0}}{}^\circ -60{}^\circ -60{}^\circ =60{}^\circ $ ，
37. 即点E在 $∠ACD$ 的角平分线上运动，
38. 在射线 $CD$ 上截取 $CP^{′}=CP$ ，连接 $EP^{′}$ ，
39. 在 $ΔCEP$ 和 $ΔCEP^{′}$ 中，
40. $\begin{cases}PC=P^{′}C\\\angle PCE=\angle P^{′}CE=60{}^\circ \\CE=CE\end{cases}$  ，
41. $△CEP{\rm{≌}}△CEP^{′}{{\rm{（}}}{\rm{S}}{\rm{A}}{\rm{S}}{\rm{）}}$ ，
42. ∴ $PE=P^{′}E$ ，
43. 则 $BE+PE=BE+P^{′}E$ ，
44. 由三角形三边关系可知， $BE+P^{′}E\geqslant BP^{′}$ ，
45. 即当点E与点C重合， $BE+P^{′}E=BP^{′}$ 时， $PE+BE$ 有最小值 $BP^{′}$ ，
46. ∵ $BP^{′}=BE+CP^{′}=BC+CP=3+2=5$ ，
47. ∴ $BE+PE=BE+P^{′}E\geqslant BP^{′}=5$ ，
48. ∴ $BE+PE$ 最小值为5．
49. 

## 知识点

**中文**:
  - 三角形三边关系
  - 等边三角形的判定与性质
  - 全等三角形的判定与性质

**English**:
  - Relationship Between Sides
  - Determination and Properties
  - Determination and Properties

---
