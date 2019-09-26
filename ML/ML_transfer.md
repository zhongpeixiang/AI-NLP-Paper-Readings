# ML - Transfer Learning
|Paper|Conference|Remarks
|--|--|--|
|[A Kernel Two-Sample Test](http://www.jmlr.org/papers/volume13/gretton12a/gretton12a.pdf)|JMLR 2012| 1. Propose a framework for analyzing and comparing distributions, which we use to construct statistical tests to determine if two samples are drawn from different distributions. 2. The proposed test statistic is the largest difference in expectations over functions in the unit ball of a reproducing kernel Hilbert space (RKHS), and is called the _maximum mean discrepancy_ (MMD).|
|[Generative Moment Matching Networks](https://arxiv.org/abs/1502.02761)|ICML 2015| 1. Formulate a method that generates an independent sample via a single feedforward pass through a multilayer perceptron, as in the GAN. 2. Utilize a technique from statistical hypothesis testing known as maximum mean discrepancy (MMD), which leads to a simple objective that can be interpreted as matching all orders of statistics between a dataset and samples from the model, and can be trained by backpropagation. 3. Further boost the performance of this approach by combining our generative network with an auto-encoder network, using MMD to learn to generate codes that can then be decoded to produce samples.|
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwMDQxOTE3ODksNzMwOTk4MTE2XX0=
-->