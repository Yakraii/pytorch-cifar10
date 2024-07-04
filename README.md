# ResNet on Cifar10

[kaggle-cifar10](http://www.kaggle.com/c/cifar-10)

## 环境

- python3.9
- PyTorch version: 2.2.0+cpu



## 运行

#### 1.数据集 

按照说明文档中的数据集结构（使用d2l的方法）处理好数据放置于'./data'中。

#### 2.训练模型

运行'cifar10-train.ipynb'中代码即可，其中包含resnet18(修改),  resnet56。

#### 3.测试模型

导入model中保存的模型，使用'cifar10-train.ipynb'最后部分的预测生成'submisson.csv'，上传kaggle评分。



## 效果

#### resnet56

测试准确率达到92.46%

#### resnet18(修改)

测试准确率达到89.94%