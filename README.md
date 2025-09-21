#An Adaptive Deep Embedding Clustering Framework for Unsupervised Text
Clustering
This repository contains the implementation of A-DEC++, a neural network-based unsupervised clustering framework used for DBpedia as the primary dataset and 20 Newsgroups text datasets just for generalization.

## Contents
- `cse425-project.ipynb`: Kaggle notebook with experiments and evaluations
- 'cse425_project.py' : .py file of the Kaggle notebook

## Datasets Used
- DBpedia (HuggingFace)
- 20 Newsgroups (scikit-learn)
  
## Notes
- Sentence embeddings were generated using Sentence-BERT (`all-MiniLM-L6-v2`)
- Labels used only for evaluation via Hungarian matching

## Clustering Evaluation Metrics
- Accuracy (Hungarian)
- NMI, ARI
- Silhouette Score
- Davies-Bouldin Index


## Author
Nahid Hassan – BRAC University
