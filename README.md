# SYSU 2022 Digital Image Processing Final Project

代码参考：https://github.com/qxdn/cs231n-assignment

实验报告见`report.ipynb`或者`实验报告.md`

## 实验1 全连接神经网络(必做)
依照 `FullConnectedNetwork.ipynb` 中的要求:
- [x] 实现affine layer的前向传播和反向传播
- [x] 实现ReLU激活函数的前向传播和反向传播，并在jupyter notebook上回答问题1
- [x] 利用你实现的affine layer和ReLU激活函数构建一个两层的全连接神经网络
- [x] 训练你实现的两层全连接神经网络，使测试结果的准确率达到50%以上
- [x] 构建多层的全连接网络，满足FullConnectedNetwork.ipynb中的测试要求

## 实验2 归一化(必做)

依照 `BatchNormalization.ipynb` 中的要求:

- [x] 实现batch normalization的前向传播和反向传播
- [x] 修改你之前实现的全连接神经网络，添加batch normalization，回答问题1
- [x] 探究batch normalization和batch size的关系，回答问题2
- [x] 实现layer normalization的前向传播和反向传播，并将layer normalization添加到你之前实现的全连接神经网络中
- [x] 探究layer normalization和batch size的关系，回答问题3

## 实验三 CNN(选做)
依照 `ConvolutionalNetwork.ipynb` 中的要求:
- [x] 实现CNN的前向传播和反向传播
- [x] 实现maxpooling的前向传播和反向传播
- [x]  实现一个三层卷积神经网络
- [x]  实现spatialbatchnormalization

## 实验四 实现ConvNet(选做)
- [x] 根据 `ConvolutionalNetwork.ipynb` 中 Train your best model 的要求:
利用annp文件夹中的模块实现用于分类cifar-10数据集的卷积神经网络。需要注意的是，只能用annp文件夹中的模 块实现你的模型，不允许使用额外的深度学习框架，请在`annp/classifiers/cnn.py`中实现你的模型，在jupyter notebook对应位置实现你的训练过程，实验结果以及可视化分析。请各位同学仔细阅读annp文件夹中每个模块的用法。