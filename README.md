# Simple-ResNet
# Residual Neural Network

------

这是一个简单的ResNet实现。使用数据是mnist，堆叠了50个resNet block，每个block由2个全连接层组成。共103层全连接神经网络。
### 1. 直接训练后的效果
[没有](https://www.zybuluo.com/static/img/logo.png)
### 2. 去掉h(x) = f(x) + x
[没有](https://www.zybuluo.com/static/img/logo.png)
### 3. 如何使用
代码结构
----model  
-------SimpleResNet.py  
----util  
-------datasets.py  
----data  

SimpleResNet.py是模型的实现以及主函数  
datasets.py加载数据的一个工具类  
直接运行simpleResNet.py即可，里面可以修改模型的参数。  
更详细的解释请直接参考simpleResNet.py中的注释。  



