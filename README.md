# BioReddit Embeddings

This repository contains word embeddings trained on medical subreddits. 
We provide embeddings for GloVe ([Pennington et al., 2014](https://nlp.stanford.edu/pubs/glove.pdf)), 
ELMo ([Peters et al., 2018](https://arxiv.org/abs/1802.05365)),
and Flair ([Akbik et al., 2018](https://www.aclweb.org/anthology/C18-1139/)).

The embeddings are trained on ~800,000 Reddit posts from over 60 medical-themed communities. 
The paper describing the training and evaluation process will be presented at the
Tenth International Workshop on Health Text Mining and Information Analysis (LOUHI 2019), 
co-located with the 2019 Conference on Empirical Methods in Natural Language Processing (EMNLP 2019).

## Embeddings

You can download the embeddings in the [release section](https://github.com/basaldella/bioreddit/releases/tag/v1.0) of this repository or using the links in the table below:

| Embedding | Download Link                                                                                                                                                                                 |
|-----------|----------------|
| ELMo      | [options](https://github.com/basaldella/bioreddit/releases/download/v1.0/bioreddit.elmo.json), [weights](https://github.com/basaldella/bioreddit/releases/download/v1.0/bioreddit.elmo.hdf5)                                                                                                                                                                                               |
| Flair     | [forward](https://github.com/basaldella/bioreddit/releases/download/v1.0/bioreddit.flair.forward.pt),   [backward](https://github.com/basaldella/bioreddit/releases/download/v1.0/bioreddit.flair.backward.pt)                                                                                                                                                                                                |
| GloVe 50  | [txt](https://github.com/basaldella/bioreddit/releases/download/v1.0/bioreddit.glove.50.txt),   [bin](https://github.com/basaldella/bioreddit/releases/download/v1.0/bioreddit.glove.50.bin)                                                                                                                                                                                            |
| Glove 100 | [txt](https://github.com/basaldella/bioreddit/releases/download/v1.0/bioreddit.glove.100.txt),   [bin](https://github.com/basaldella/bioreddit/releases/download/v1.0/bioreddit.glove.100.bin)                                                                                                                                                                                           |
| Glove 200 |  [txt](https://github.com/basaldella/bioreddit/releases/download/v1.0/bioreddit.glove.200.txt),   [bin](https://github.com/basaldella/bioreddit/releases/download/v1.0/bioreddit.glove.200.bin) |

## Code 

You can find the code used to download the subreddits [here](https://github.com/basaldella/reddit-scraper).
