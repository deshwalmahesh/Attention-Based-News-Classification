# Attention-Based-News-Classification
Implementation of "Attention is All you need" style attention layer to classify news articles. Very fast and accurate results.

Attention Layer structure has been adapted from [Jason Brownlee's Blog on Attention Mechanism](https://machinelearningmastery.com/encoder-decoder-attention-sequence-to-sequence-prediction-keras/) which is 
a direct represention of the research paper "Attention is all You need".

The model produced a staggering validation accuracy of `0.98` without even overfitting after running for 10 epochs. We have used `GloVe Enbeddings` of size 100-D and the data set used is 
[BBC News Articles for 5 categories](http://mlg.ucd.ie/datasets/bbc.html).

Model is very fast and trained on a GPU within seconds.
