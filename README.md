## XLSTM 网络搭建

[paper](https://arxiv.org/abs/1709.08073)

说明：

原文是建立三个模型，对三个模型的中间一个LSTM层进行特征交叉，每个模型的输入是不同的（体重，步数，睡眠）。本文为了简便，三个模型输入的是相同的数据。即都是 手写字体数据。

网络结构图：

![](https://github.com/dylan2wang/xlstm/blob/master/001.png)

