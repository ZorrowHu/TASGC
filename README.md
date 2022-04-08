# CSI-GNN
基于复杂结构信息的图神经网络序列推荐算法 Complex Structural Information for Session-based Recommendation with Graph Neural Networks

## Abstract
摘要
 
现有的基于图神经网络的会话序列推荐算法能够利用图结构信息达到比较好的推荐效果，但是却没有考虑用户在会话序列中的重复点击行为和项目之间的复杂转换，同时也没有很好地利用图中复杂的结构信息。为此提出一种基于复杂结构信息的图神经网络序列推荐算法。算法结合了会话序列图中的有向结构信息与无向结构信息，通过考虑重复点击和引入注意力机制建立了会话中点击项目的复杂转换模型，使得生成的会话向量在推荐过程中预测地更准确。我们在三个真实场景的数据集上进行了实验，实验数据表明该方法优于现有的最佳方法，能够更好地预测用户在会话中的下一次点击的精度。

## 实验效果
各项指标均优于[AAAI-2019 SR-GNN](https://arxiv.org/abs/1811.00855)和[SIGIR-2020 TAGNN](https://arxiv.org/abs/2005.02844)，最高提升可达4.34%

## 论文投稿状态
《计算机工程》（北大核心、CSTPCD）已录用

【DOI】10.19678/j.issn.1000-3428.0061308
