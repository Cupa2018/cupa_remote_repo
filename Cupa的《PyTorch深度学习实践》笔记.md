

开头遇见校友

![image-20241013015742500](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241013015742500.png)



![image-20241013121401201](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241013121401201.png)

![image-20241013122020792](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241013122020792.png)

![image-20241013122902250](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241013122902250.png)

![image-20241013161124653](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241013161124653.png)



![image-20241013163229904](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241013163229904.png)

![image-20241014002257794](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241014002257794.png)

![image-20241014002316649](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241014002316649.png)

![image-20241014002335071](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241014002335071.png)

![image-20241014140157360](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241014140157360.png)

![image-20241014140600352](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241014140600352.png)

MSE(均方误差)：均方误差（MSE）是衡量回归模型预测精度的常用指标之一。它计算了预测值与实际值之间差异的平方和的平均值。在回归分析中，MSE 提供了一个简单的衡量模型预测性能的方法。MSE 越小，表明模型的预测值与实际值之间的差异越小，模型的预测精度越高。

![image-20241014140846868](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241014140846868.png)

![image-20241014142305850](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241014142305850.png)

![image-20241014142706659](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241014142706659.png)

使用visdom进行可视化训练

![image-20241014142932864](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241014142932864.png)

meshgrid()绘制3d图形

![image-20241015191751433](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241015191751433.png)

![image-20241016121038766](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241016121038766.png)

![image-20241016123025819](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241016123025819.png)

![image-20241016123330938](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241016123330938.png)

![image-20241016124811640](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241016124811640.png)

![image-20241016125909832](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241016125909832.png)

指数加权均值

![image-20241016130013489](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241016130013489.png)

随机梯度下降（防止陷入鞍点），但是无法并行，时间复杂度高

（Stochastic Gradient Descent, SGD）

![image-20241016132528677](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241016132528677.png)

解决方法：batch，分成小批量随机梯度

![image-20241016143249523](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241016143249523.png)

![image-20241016144027523](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241016144027523.png)

![image-20241016145256977](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241016145256977.png)

![image-20241016145602947](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241016145602947.png)

![image-20241016152007412](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241016152007412.png)

![image-20241016183416578](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241016183416578.png)

![image-20241016190732799](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241016190732799.png)

![image-20241016191335558](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241016191335558.png)

==loss最终一定要是一个标量，不然无法对其进行backward!==

![image-20241020203936545](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241020203936545.png)

![image-20241016200038201](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241016200038201.png)

![image-20241016210226708](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241016210226708.png)

![image-20241017190606809](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241017190606809.png)

逻辑斯蒂回归（处理分类问题）：不再预测输出值是多少，转而输出属于某个类的概率是多少

![image-20241017191620469](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241017191620469.png)

![image-20241017191921333](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241017191921333.png)

![image-20241017193933600](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241017193933600.png)

![image-20241017194617567](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241017194617567.png)

逻辑斯蒂函数：将线性结果映射到[0,1]上

![image-20241017195301707](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241017195301707.png)

饱和函数：取值在[0,1]之间，单增，导函数符合正态分布；其中最出名的是逻辑斯蒂函数

![image-20241017195954193](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241017195954193.png)

![image-20241017201056083](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241017201056083.png)

交叉熵，KL散度可以用于表示分布之间的差异

![image-20241020222132441](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241020222132441.png)

![image-20241020233202553](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241020233202553.png)

loss函数由MSE变为交叉熵函数（BCE)

![image-20241020233411653](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241020233411653.png)

![image-20241020233538552](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241020233612795.png)

![image-20241020233725948](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241020233725948.png)

![image-20241020234027691](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241020234027691.png)

说明：

1.逻辑斯蒂回归和线性模型的明显区别是在线性模型的后面，添加了激活函数(非线性变换)

2.分布的差异：KL散度，cross-entropy交叉熵

3.BCELoss 是CrossEntropyLoss的一个特例，只用于二分类问题，而CrossEntropyLoss可以用于二分类，也可以用于多分类。

   如果是二分类问题，建议BCELoss



![image-20241021132208072](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021132208072.png)

![image-20241021132557715](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021132557715.png)

torch中继承自model的函数均是向量化函数，支持向量输入，故mini-batch可以写成矩阵形式,写成向量化形式后可以使用gpu大大提升运算速度

![image-20241021133158160](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021133158160.png)

==矩阵乘法本质上是对矩阵进行空间的运算，神经网络本质上是使用多层的线性变换来模拟复杂的非线性变换==

==而线性变换的叠加还是线性变换，故需要引入sigmoid这样的激活函数，引入非线性因子，来达到可以调整线性元素来拟合非线性变换的效果==

![image-20241021142216846](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021142216846.png)

![image-20241021142612233](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021142612233.png)

老师觉得的计算机的最重要的能力（类比深度学习的学习率不可以太高，拥有泛化能力最好）

![image-20241021142940480](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021142940480.png)

直接8维降1维中间的神经元少，学习效果可能不佳，所以要多几层，但是也不能太多，否则会造成过拟合

![image-20241021143834348](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021143834348.png)

![image-20241021143910983](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021143910983.png)

![image-20241021143951168](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021143951168.png)

![image-20241021144100183](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021144100183.png)

常见的激活函数们

![image-20241021144134658](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021144134658.png)

![image-20241021144205967](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021144205967.png)

Relu函数的取值在0到1之间，但是只要输入小于0，输出就为0

但是Relu函数存在梯度爆死的问题，梯度会等于零而无法进行反向传播，所以一般将Relu函数和Sigmoid函数一起使用

![image-20241021150611580](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021150611580.png)

调试代码时遇到问题，numpy与pytorch使用的OpenMP版本不同

解决方法：

```
import os
os.environ["KMP_DUPLICATE_LIB_OK"] = "TRUE"
```

使程序可以继续运行



![image-20241021150808916](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021150808916.png)







![image-20241021155248873](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021155248873.png)

![image-20241021155427345](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021155427345.png)

shuffle:是否打乱

![image-20241021161142492](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021161142492.png)

![image-20241021161401217](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021161401217.png)

![image-20241021161604404](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021161604404.png)

![image-20241021161915885](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021161915885.png)

![image-20241021161957097](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021161957097.png)

![image-20241021163219597](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021163219597.png)

内置数据集，都是dataset的子类

![image-20241021163416368](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021163416368.png)

![image-20241021164836322](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021164836322.png)







![image-20241021165305735](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021165305735.png)

![image-20241021175315600](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021175315600.png)

softmax层将线性层的结果转换为正数，且使各个分类的概率之和相加为1

实现方法：

![image-20241021175727827](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021175727827.png)

![image-20241021181010397](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021181010397.png)

![image-20241021181120772](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021181120772.png)

![image-20241021182132091](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021182132091.png)

将MNIST0-255映射到0-1上

![image-20241021182249944](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021182249944.png)

transforms，用于对图像进行处理的类

![image-20241021182406469](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021182406469.png)

![image-20241021182807508](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021182807508.png)

![image-20241021182926273](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021182926273.png)

![image-20241021183041477](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021183041477.png)

normalize中一个代表均值，一个代表标准差，来源是数据集中的所有像素，将数据点转化为01分部

![image-20241021183612681](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021183612681.png)

![image-20241021185629910](C:\Users\31675\AppData\Roaming\Typora\typora-user-images\image-20241021185629910.png)







