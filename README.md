# Tropical-Convolutional-Neural-Networks
TCNN-An Alternative Practice of Tropical Convolution to Traditional Convolutional Neural Networks

Paper：https://ui.adsabs.harvard.edu/abs/2021arXiv210302096F/abstract

## 运行环境

python 3.6.5
pytorch 1.7.0


## 运行参数设置

运行参数参考options_func，并注意在load_data中需要添加你需要的数据集及其存放的位置。

## 运行示例

python .\Tropical_Convolutional_Neural_Networks.py --net net0

## 代码中包括

- 6种tropical convolution layers

 MinPlus-Sum_Conv Layer (MinP-S)

 MaxPlus-Sum-Conv Layer (MaxP-S)

 MinPlus-Max-Conv Layer (MinP-Max)

 MaxPlus-Min-Conv Layer (MaxP-Min)

 MinPlus-Min-Conv Layer (MinP-Min)

 MaxPlus-Max-Conv Layer (MaxP-Max)

- 6种网络结构

 详见论文。


