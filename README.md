# Comparing Interpretability of Biologically Inspired and Traditional Word Embeddings

This repository contains the code for the [paper](./paper.pdf) "Comparing Interpretability of Biologically Inspired and Traditional Word Embeddings".  
We worked on this project during the seminar of the Bio-inspired Artificial Intelligence (BAI) course at the University of Hamburg in the winter semester 2021/2022.  
The main research questions in this seminar project was about the interpretability of the [FlyVec](https://github.com/bhoov/flyvec) word embeddings by Liang et al. [1].  
We evaluated the interpretability of FlyVec [1] on the following two metrics and compared it with traditional word embeddings (like word2vec [2], GloVe [3], and BERT [4]).

## Interpretability Score

`InterpretabilityScore.ipynb` contains experiments to evaluate the interpretability for different word embedding techniques with the interpretability score on the [SEMCAT](https://github.com/avaapm/SEMCATdataset2018) dataset introduced by Şenel et al. [5].

## Semantic and Syntactic Relationships

`Relationships.ipynb` contains experiments to evaluate the interpretability for different word embedding techniques on the semantic and syntactic relationships dataset by Mikolov et al. [2].

## References
[1] Yuchen Liang et al. "Can a Fruit Fly Learn Word Embeddings?". In: arXiv preprint arXiv:2101.06887 (2021)  
[2] Tomas Mikolov et al. "Efficient estimation of word representations in vector space". In: arXiv preprint arXiv:1301.3781 (2013)  
[3] Jeffrey Pennington, Richard Socher, and Christopher D Manning. "Glove: Global vectors for word representation". In: Proceedings of the 2014 conference on empirical methods in natural language processing (EMNLP). 2014, pp. 1532-1543  
[4] Jacob Devlin et al. "Bert: Pre training of deep bidirectional transformers for language understanding". In: arXiv preprint arXiv:1810.04805 (2018)  
[5] Lütfi Kerem Şenel et al. "Semantic structure and interpretability of word embeddings". In: IEEE/ACM Transactions on Audio, Speech, and Language Processing 26.10 (2018), pp. 1769-1779  
