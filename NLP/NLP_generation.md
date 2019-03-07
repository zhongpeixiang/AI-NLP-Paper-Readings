# NLP - Text Generation
|Paper|Conference|Remarks
|--|--|--|
|[SeqGAN: Sequence Generative Adversarial Nets with Policy Gradient](https://arxiv.org/pdf/1609.05473)|AAAI 2016|1. A major difficulty in generating text using GAN is that the discrete outputs from the generative model make it difficult to pass the gradient update from the discriminative model to the generative model|
|[Generating Sentences from a Continuous Space](http://www.aclweb.org/anthology/K16-1002)|CoNLL 2016|1. Introduce and study an RNN-based variational autoencoder generative model that incorporates distributed latent representations of entire sentences. 2. Present techniques such as KL weight annealing and word drop for solving the difficult learning problem presented by this model.|
|[Toward Controlled Generation of Text](https://arxiv.org/pdf/1703.00955)|ICML 2017|1. Aims at generating plausible natural language sentences, whose attributes are dynamically controlled by learning disentangled latent representations with designated semantics. 2. Propose a new neural generative model which combines variational auto-encoders and holistic attribute discriminators for effective imposition of semantic structures. 3. The proposed model learns highly interpretable representations from even only word annotations, and produces realistic sentences with desired attributes.|
|[An Actor-Critic Algorithm for Sequence Prediction](https://arxiv.org/pdf/1607.07086)|ICLR 2017|1. Present an approach to training neural networks to generate sequences using actor-critic methods from reinforcement learning (RL). 2. Address the train/test discrepancy problem by introducing a *critic* network that is trained to predict the value of an output token, given the policy of an *actor* network.|
|[Adversarial Generation of Natural Language](https://arxiv.org/pdf/1705.10929)|ACL Workshop 2017|1. Introduce a simple baseline that addresses the discrete output space problem in language generation using GAN without relying on gradient estimators. |


[Back to index](../README.md)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTEzNzk4MDE4OCwtNTMyMzIzNjQ4LDg2Nz
Q3MzcyMV19
-->