基于MNIST数据库进行手写数字识别训练，手写数字图片7万张
训练集6万张（调整神经网络参数）+测试集1万张（评估网络性能）
所选图片大小为28×28像素，每个像素灰度值在0~255之间
神经网络输出节点10个，利用softmax归一化转化为像概率的数值
激活函数选的是整流函数（非线性）
