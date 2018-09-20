# NLP - Word, Sentence and Document Embedding
|Paper|Conference|Remarks
|--|--|--|
|[Learning Word Vectors for Sentiment Analysis](https://ai.stanford.edu/~ang/papers/acl11-WordVectorsSentimentAnalysis.pdf)|HLT 2011|1. 1. Present a model that uses a mix of unsupervised and supervised techniques to learn word vectors capturing semantic term--document information as well as rich sentiment content. 2. Instantiate the model to utilize the document-level sentiment polarity annotations present in many online documents|
|[GloVe: Global Vectors for Word Representation](https://www.aclweb.org/anthology/D14-1162)|EMNLP 2014|1. A new global log-bilinear regression model that combines the advantages of two major model families in the literature: global matrix factorization and local context window methods|
|[Specializing Word Embeddings for Similarity or Relatedness](http://aclweb.org/anthology/D15-1242)|EMNLP 2015|1. 1. Demonstrate the advantage of specializing semantic word embeddings for either similarity or relatedness. 2.  Find that retrofitting and joint-learning approaches yield specialized semantic spaces and perform better than unspecialized spaces|
|[A Simple But Tough-to-Beat Baseline for Sentence Embeddings](https://openreview.net/pdf?id=SyK00v5xx)|ICLR 2016| 1. Proposed a completely unsupervised sentence embedding method. 2. Use word embeddings computed using one of the popular methods on unlabeled corpus like Wikipedia, represent the sentence by a weighted average of the word vectors, and then modify them using PCA/SVD. 3. This weighting improves performance by about 10% to 30% in textual similarity tasks. 4. This paper also gives a theoretical explanation of the success using a latent variable generative model for sentences|
|[Towards Building Affect Sensitive Word Distributions](https://openreview.net/pdf?id=By5SY2gA-)|N.A.|1. To incorporate affect lexica, which capture fine-grained information about a word's psycholinguistic and emotional orientation, into the training process of Word2Vec and GloVe using a joint learning approach. 2. The proposed method outperforms previous work on standard tasks such as word similarity detection, outlier detection and sentiment detection.|
|[A Simple Regularization-based Algorithm for Learning Cross-Domain Word Embeddings](http://aclweb.org/anthology/D17-1312)|EMNLP 2017|Present a simple yet effective method for learning word embeddings based on text from different domains.|
|[A Structured Self-attentive Sentence Embedding](https://arxiv.org/pdf/1703.03130)|ICLR 2017|Proposes a new model for extracting an interpretable sentence embedding by introducing self-attention.|

[Back to index](../README.md)

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTY0NTc2NDA1OCwtMTQ1NTk5OTU0OSwxNT
c2ODY2NTM0LC0xNzc3NjE5MTE0XX0=
-->