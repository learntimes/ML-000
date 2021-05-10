作业参见lightgbm.ipynb

note:

复习stacking

关于深度学习
寻找有效 paper 的主要途径：搜索相关Survey[https://scholar.google.com/] 和高规格比赛[https://motchallenge.net/]；
将一篇知名 paper 研究透彻比随意浏览若干篇有更大帮助。

神经网络的经典优化器
Momentum；
如果不需要精细调参，一般来说可采用 Adam；
对于卷积神经网络（CV 应用），SGD+Momentum 常常效果更好。

激活函数
重点关注GeLU、Swish与Mish

BatchNormalization 
关注Ghost Batch Normalization；
详见Summers and Dinneen (2019)。

cnn原理

Residual Connection
for example
fist layer: $x \mapsto F(x) + x $
second layer, input: $y := F(x) + x$ oupput: $F(F(x) + x) + F(x) + x$

Embedding

LSTM

Attention
paper: Attention is all you need

Transformer

Attention 一个其他的应用：Mixture-of-expert

好的paper: Compositional Attention Networks for Machine Reasoning

TabNet
见Arik and Pfister (2019)
 该 paper 的实证研究是否有问题？
 该 paper 的设计模式中是否有反常的地方？
 该 paper 的设计模式中是否有不合理的地方？
 该 paper 是否有提升的可能性？


