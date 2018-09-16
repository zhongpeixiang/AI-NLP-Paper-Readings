# ML - Optimization
|Paper|Conference|Remarks
|--|--|--|
|[Dropout: A Simple Way to Prevent Neural Networks from Overfitting](http://jmlr.org/papers/volume15/srivastava14a.old/srivastava14a.pdf)|JMLR 2014|The key idea is to randomly drop units during training, which prevents units from co-adapting too much.|
|[Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift](https://arxiv.org/pdf/1502.03167)|Arxiv 2015| 1. The distribution of each layer's inputs changes during training, which slows down the training by requiring lower learning rates and careful parameter initialization. 2. BN performs normalization for each training mini-batch and allows us to use much higher learning rate and be less careful about initialization|
|[Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift](https://arxiv.org/pdf/1502.03167)|Arxiv 2015| 1. The distribution of each layer's inputs changes during training, which slows down the training by requiring lower learning rates and careful parameter initialization. 2. BN performs normalization for each training mini-batch and allows us to use much higher learning rate and be less careful about initialization|

[Back to index](../README.md)
<!--stackedit_data:
eyJoaXN0b3J5IjpbNjMwMzYyMTksMjA5NTUxMTc0OF19
-->