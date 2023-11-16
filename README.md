# Tweet Sentiment analysis

Dataset: https://data.world/crowdflower/sentiment-analysis-in-text.

This dataset consists of 40,000 tweets collected from Twitter. Each tweet is annotated with one of 13 distinct sentiment classes. The tweets are preprocessed, tokenized, and embedded using the word2Vec embeddings. In this experiment, I used a bi-directional LSTM model, followed by a 2D convolutional and max pooling layer, to capture the global features and the local features of the input texts. The results are compared to traditional methods such as random forest and RNN.


### Reference

Zhou, P., Qi, Z., Zheng, S., Xu, J., Bao, H., & Xu, B. Text classification improved by integrating
bidirectional LSTM with two-dimensional max pooling. 26th International Conference on
Computational Linguistics, vol. 2, no.1, 3485–3495, 2016.
