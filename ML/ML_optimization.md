# ML - Optimization
|Paper|Conference|Remarks
|--|--|--|
|[Practical Recommendations for Gradient-Based Training of Deep Architectures](https://arxiv.org/abs/1206.5533)|Arxiv 2012| A practical guide with recommendations for some of the most commonly used hyperparameters, in particular in the context of learning algorithms based on back-propagated gradient and gradient-based optimization.|
|[Dropout: A Simple Way to Prevent Neural Networks from Overfitting](http://jmlr.org/papers/volume15/srivastava14a.old/srivastava14a.pdf)|JMLR 2014|The key idea is to randomly drop units during training, which prevents units from co-adapting too much.|
|[Adam: A Method for Stochastic Optimization](https://arxiv.org/pdf/1412.6980)|Arxiv 2014| An algorithm for first-order gradient-based optimization of stochastic objective functions, based on adaptive estimates of lower-order moments.|
|[Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift](https://arxiv.org/pdf/1502.03167)|Arxiv 2015| 1. The distribution of each layer's inputs changes during training, which slows down the training by requiring lower learning rates and careful parameter initialization. 2. BN performs normalization for each training mini-batch and allows us to use much higher learning rate and be less careful about initialization|
|[An Overview of Gradient Descent Optimization Algorithms](https://pdfs.semanticscholar.org/e2dc/8810671f76927d862e63faa29c401bdec5da.pdf)|Arxiv 2016| 1. Stochastic vs Batch vs Minibatch Gradient Descent. 2. It introduces momentum, Nesterov accelerated momentum, Adagrad, Adadelta, RMSProps and Adam optimizations.|
|[Population-Based Training for Neural Networks](https://arxiv.org/abs/1711.09846)|Arxiv 2017| 1. Eval: measure validation accuracy of a model. 2. Exploit: copy parameters from other models in population. 3. Explore: perturb  parameters. 4. Ready: a model becomes ready after a few epochs since last parameter update|
|[On the Convergence of Adam and Beyond](https://openreview.net/pdf?id=ryQu7f-RZ)|ICLR 2018| 1. Show that one cause for convergence failure of Adam is the exponential moving average used in the algorithms. 2. Suggests that the convergence issues can be fixed by endowing such algorithms with "long-term memory" of past gradients, and propose new variants of the Adam algorithm which not only fix the convergence issues but often also lead to improved empirical performance.|

### Resources
- [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/)

[Back to index](../README.md)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0NjExNDgzNTUsNjIwNDAxODU0LDE0Nj
kyNDMwOTEsMjA5NTUxMTc0OF19
-->