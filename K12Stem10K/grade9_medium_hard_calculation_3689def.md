# Mathematics - 题目 809

**ID**: 3689def758e8486b8d6850a16589d15e
**年级**: Grade 9
**难度**: Medium-Hard
**题型**: Calculation

## 题目
任意一个个位数字不为0的四位数x，都可以看作由前面三位数和最后一位数组成，交换这个数的前面三位数和最后一位数的位置，将得到一个新的四位数y，记f（x）＝ $\frac {x-y}{9}$ ，例如：x＝2356，则y＝6235，f（2356）＝ $\frac {2356-6235}{9}$ ＝﹣431．（1）计算：f（5234）＝，f（3215）＝．（2）若x的前三位所表示的数与最后一位数之差能被11整除，求证：f（x）能被11整除．（3）若s＝1100+20a+b，t＝1000b+100a+23（1⩽a⩽4，1⩽b⩽5，a、b均为整数），若f（s）+f（t）被7除余2，求满足条件的f（t）的最小值．​​​​​​​‌

## 解答

1. 解：（1） $f\left ({5234}\right )=\frac {5234-4523}{9}=79$ ， $f\left ({3215}\right )=\frac {3215-5321}{9}=-234,$
2. 故答案为：79，-234；
3. （2）设x的最后一位为a，前三位为b，则b-a=11k，∴b=11k+a，
4. 由题意得x=10b+a，y=1000a+b，
5. ∴ $f\left ({x}\right )=\frac {x-y}{9}$
6. $=\frac {\left ({10b+a}\right )-\left ({1000a+b}\right )}{9}$
7. $=\frac {9b-999a}{9}$
8. $=\frac {9\left ({11k+a}\right )-999a}{9}$
9. $=\frac {99k-990a}{9}$
10. $=11\left ({k-10a}\right )$ ，
11. ∵k、a都是整数，
12. ∴f（x）能被11整除；
13. （3）由s＝1100+20a+b，t＝1000b+100a+23（1⩽a⩽4，1⩽b⩽5，a、b均为整数），得s的个位数字为b，t的个位数字为3，
14. ∴ $f\left ({s}\right )=\frac {\left ({1100+20a+b}\right )-\left ({1000b+\frac {1100+20a}{10}}\right )}{9}=110+2a-111b$ ，
15. $f\left ({t}\right )=\frac {\left ({1000b+100a+23}\right )-\left ({3000+\frac {1000b+100a+20}{10}}\right )}{9}=100b+10a-331$ ，
16. ∴ $f\left ({s}\right )+f\left ({t}\right )=\left ({110+2a-11b}\right )+\left ({100b+10a-331}\right )=12a-11b-221$ ，
17. ∵ $f\left ({s}\right )+f\left ({t}\right )$ 被7除余2，
18. ∴ $f\left ({s}\right )+f\left ({t}\right )=12a-11b-221=7k+2$ （k为整数），
19. ∵1⩽a⩽4，1⩽b⩽5，a、b均为整数，
20. ∴在a、b的几组值中试算，当a=2，b=1时，k为整数，且f（t）最小，
21. 此时 $f\left ({t}\right )=100b+10a-331=-211$ ．

## 知识点

**中文**:
  - 实数的运算

**English**:
  - Operations with Real Numbers

---
