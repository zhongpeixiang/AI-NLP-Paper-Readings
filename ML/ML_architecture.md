# ML - Architecture
|Paper|Conference|Remarks
|--|--|--|
|[Empirical Evaluation of Gated Recurrent Neural Networks on Sequence Modeling](https://arxiv.org/pdf/1412.3555)|Arxiv 2014|Evaluate LSTM and GRU on
the tasks of polyphonic music modeling and speech signal modeling and results show that they indeed perform better than traditional recurrent units|
|[Neural Turing Machines](https://arxiv.org/pdf/1410.5401)|Arxiv 2014|Coupling neural networks to external memory resources, which they can interact with by attentional processes.|
|[Scheduled Sampling for Sequence Prediction with Recurrent Neural Networks](https://arxiv.org/pdf/1506.03099)|NIPS 2015|To alleviate the discrepancy between training and inference for sequence prediction models, authors propose a curriculum learning strategy to gently change the training process from a fully guided scheme using the true previous token, towards a less guided scheme which mostly uses the generated token instead|
|[Professor Forcing: A New Algorithm for Training Recurrent Networks](https://arxiv.org/pdf/1610.09038)|NIPS 2016|1. Uses adversarial domain adaptation to encourage the dynamics of the recurrent network to be the same when training the network and when sampling from the network over multiple time steps. 2. Produce T-SNEs showing that Professor Forcing successfully makes the dynamics of the network during training and sampling more similar.|
|[Hybrid Computing Using a Neural Network with Dynamic External Memory](https://www.nature.com/articles/nature20101)|Nature 2016| Traditional neural networks are limited in their ability to represent variables and data structures and to store data over long timescales owing the lack of an external memory. This paper proposes a machine learning model called a differential neural computer (DNC), which consists of a neural network that can read from and write to an external memory matrix, analogous to the RAM in a conventional computer.|
|[Convolutional Sequence to Sequence Learning](https://arxiv.org/pdf/1705.03122)|Arxiv 2017| 1. Introduce an seq2seq architecture based entirely on convolutional neural networks.|

[Back to index](../README.md)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjE0MDIwMjQ1MCwtMTE1NTQzNjQ4OV19
-->