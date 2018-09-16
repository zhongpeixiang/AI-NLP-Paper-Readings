# ML - Optimization
|Paper|Conference|Remarks
|--|--|--|
|[Dropout: A Simple Way to Prevent Neural Networks from Overfitting](http://jmlr.org/papers/volume15/srivastava14a.old/srivastava14a.pdf)|JMLR 2014|The key idea is to randomly drop units during training, which prevents units from co-adapting too much.|
|[Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift](https://arxiv.org/pdf/1502.03167)|Arxiv 2015| 1. The distribution of each layer's inputs changes during training, which slows down the training by requiring lower learning rates and careful parameter initialization. 2. BN performs normalization for each training mini-batch and allows us to use much higher learning rate and be less careful about initialization|
|[An Overview of Gradient Descent Optimization Algorithms](https://pdfs.semanticscholar.org/e2dc/8810671f76927d862e63faa29c401bdec5da.pdf)|Arxiv 2016| 1. Stochastic vs Batch vs Minibatch Gradient Descent. 2. It introduces momentum, Nesterov accelerated momentum, Adagrad, Adadelta, RMSProps and Adam optimizations.|
|[Population-Based Training for Neural Networks](https://arxiv.org/abs/1711.09846)|Arxiv 2017| 1. Eval: measure validation accuracy of a model. 2. Exploit: copy parameters from other models in population. 3. Explore: perturb  parameters. 4. Ready: a model becomes ready after a few epochs since last parameter update|

### Resources
- [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/)

[Back to index](../README.md)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTc3OTAyNjU5OSwxNDY5MjQzMDkxLDIwOT
U1MTE3NDhdfQ==
-->