# 数学知识点滴
## 协方差 协方差矩阵
[协方差](https://www.zhihu.com/question/20852004/answer/134902061)
> 协方差是变量间的相关关系  Conv(X,Y)=SUM(Xi - EX)(Yi - EY)  两个变量所有时刻点对之间的相关关系之和，同一时刻你比均值大，我也比均值大，就是正相关；同一时刻你比均值小，我也比均值小，也是正相关；同一时刻一个比均值大，一个比均值小，就是父相关；所有时刻的相关性加和就是两个变量之间的协方差；如果两个变量独立，那么他们之间的协方差为0，同一个变量和自身的协方差，就是方差，就是标准差平方。

[协方差矩阵](https://zhuanlan.zhihu.com/p/24650651)
> 就是多个变量，两两之间的协方差，排列成的矩阵。

> 例如两个变量之间的协方差矩阵，维度就是 2*2 

> n个变量之间的协方差矩阵，维度就是 n*n

> 例如 独立随机变量 X 和 Y 的均值为0，标准差为1 和 2，则他们的协方差矩阵 为 |1 0; 0 4|

> 再如变量 X1 X2 X3 X4 X5 C=|Conv(X1,X1) Conv(X1,X2) Conv(X1,X3) Conv(X1,X4) Conv(X1,X5);...|

## 逆矩阵 伪逆矩阵  矩阵转置
[现代视频](http://www.bilibili.com/video/av6731067/index_5.html#page=1)
> 转置  列与行互换    (AB)转置 = B转置 * A转置

> 逆矩阵，非奇异方矩阵，有逆矩阵，  A的伴随矩阵 除以 A的行列式   AB=I,B成为A的逆

> 伪逆矩阵，是逆矩阵的广义形式，由于奇异矩阵或非方阵的矩阵不存在逆矩阵，但是有伪逆矩阵

> 一个与A的 转置矩阵A' 同型的矩阵X，并且满足:AXA=A, XAX=X. 此时，称矩阵X为矩阵A的伪逆，也称为广义逆矩阵。