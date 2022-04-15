### 脉冲神经网络

[**脉冲神经网络研究进展综述**](http://kzyjc.cnjournals.com/html/2021/1/20210101.htm#b115)





#### 训练算法

* SNN trained with BP
* SNN trained with Biological Plasticity Rules
* Conversion Based Methods

| 已读 | 年份 |                             论文                             |                             简介                             |                             代码                             |
| :--: | :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|      | 2010 | [Learning to recognize objects using waves of spikes and Spike Timing-Dependent Plasticity](https://ieeexplore.ieee.org/document/5596934) |                         STDP训练算法                         |                                                              |
|  ✅   | 2015 | [Unsupervised learning of digit recognition using spike-timing-dependent plasticity](https://www.frontiersin.org/articles/10.3389/fncom.2015.00099/full) |     无监督学习算法 STDP 作用于 MNIST(使用 brian 模拟器)      |     [源码](https://github.com/peter-u-diehl/stdp-mnist)      |
|  ✅   | 2018 | [Spatio-temporal backpropagation for training high-performance spiking neural networks](https://www.frontiersin.org/articles/10.3389/fnins.2018.00331/full) | 有监督学习算法 STBP(Spatio-Temporal BP), 同时考虑到时域和空间域的信息。另外，提出了解决在 spiking time处不可导的方法，用一个小矩形包住去趋近。 | [源码](https://github.com/yjwu17/STBP-for-training-SpikingNN/tree/yjwu17-pytorch-snn) |
|  ✅   | 2018 | [Direct Training for Spiking Neural Networks: Faster, Larger, Better](https://arxiv.org/abs/1809.05793) |                 使用 STBP 训练更深的神经网络                 | [源码](https://github.com/yjwu17/STBP-for-training-SpikingNN/tree/yjwu17-pytorch-snn) |
|      | 2017 | [Conversion of Continuous-Valued Deep Networks to Efficient Event-Driven Networks for Image Classification](https://www.frontiersin.org/articles/10.3389/fnins.2017.00682/full) |                                                              |                                                              |
|  ✅   | 2019 | [Going Deeper in Spiking Neural Networks VGG and Residual Architectures](https://www.frontiersin.org/articles/10.3389/fnins.2019.00095/full) |      探索更深的SNN学习训练，以及ANN转SNN（SPIKE-NORM）       |                                                              |
|      | 2021 | [Deep Spiking Convolutional Nerual Network for Single Object Localization Based On Deep Continuous Local Learning](https://arxiv.org/abs/2105.05609) |                                                              |                                                              |







### FAST

| 已读  | 年份   | 论文                                                                                                                                                         | 简介                           | 代码  |
|:---:|:----:|:----------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------:|:---:|
| ✅   | 2022 | [FAST22 - 《DUPEFS: Leaking Data Over the Network With Filesystem Deduplication Side Channels》](https://www.usenix.org/conference/fast22/presentation/bacs) | deduplication 会在时间域上有泄漏数据的风险 |     |
|     |      |                                                                                                                                                            |                              |     |

