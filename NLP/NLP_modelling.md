# NLP - Language Modelling
|Paper|Conference|Remarks
|--|--|--|
|[Affect-LM: A Neural Language Model for Customizable Affective Text Generation](https://aclanthology.coli.uni-saarland.de/papers/P17-1059/p17-1059)|ACL 2017|1. The problem of integrating state-of-the-art neural language models with affective information remains an unexplored area. 2. The proposed model Affect-LM enables us to customize the degree of emotional content in generated sentences through an additional design parameter|
|[Breaking the Softmax Bottleneck: A High-Rank RNN Language Model](https://arxiv.org/pdf/1711.03953)|ICLR 2017|1. Formulate language modeling as a matrix factorization problem, and show that the expressiveness of Softmax-based models (including the majority of neural language models) is limited by a Softmax bottleneck. 2. Propose a simple mixture of Softmax to address this issue|
|[On the State of the Art of Evaluation in Neural Language Models](https://arxiv.org/pdf/1707.05589)|ICLR 2018|Re-evaluate several popular architectures and regularisation methods with large-scale automatic black-box hyperparameter tuning and arrive at the somewhat surprising conclusion that standard LSTM architectures, when properly regularised, outperform more recent models.|
|[Regularizing and Optimizing LSTM Language Models](https://openreview.net/pdf?id=SyyGPP0TZ)|ICLR 2018|1. Consider the specific problem of word-level language modeling and investigate strategies for regularizing and optimizing LSTM-based models. 2. Propose the weight-dropped LSTM which uses DropConnect on hidden-to-hidden weights as a form of recurrent regularization. 3. Introduce NT-ASGD, a variant of the averaged stochastic gradient method, wherein the averaging trigger is determined using a non-monotonic condition as opposed to being tuned by the user.|
|[Transformer-XL: Attentive Language Models Beyond a Fixed-Length Context](https://arxiv.org/pdf/1901.02860)|Arxiv 2019|1. Propose a novel neural architecture, Transformer-XL, that enables Transformer to learn dependency beyond a fixed length without disrupting temporal coherence. 2. Transformer-XL learns dependency that is about 80% longer than RNNs and 450% longer than vanilla Transformers, achieves better performance on both short and long sequences, and is up to 1,800+ times faster than vanilla Transformer during evaluation.|

[Back to index](../README.md)

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTc4NDEyMzQwMSwtMTQzMTAxNTUzOF19
-->