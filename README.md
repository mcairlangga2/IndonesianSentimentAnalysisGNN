# IndonesianSentimentAnalysisGNN
This is the repository for Indonesian Sentiment Analysis Using Graph Neural Network.

The implementation of the GNN is based on TextGCN which follow this reference:
- Yao, L., Mao, C., & Luo, Y. (2019, July). Graph convolutional networks for text classification. In Proceedings of the AAAI conference on artificial intelligence (Vol. 33, No. 01, pp. 7370-7377).

The dataset used in this project is taken from:
- Koto, F., Rahimi, A., Lau, J. H., & Baldwin, T. (2020). IndoLEM and IndoBERT: A benchmark dataset and pre-trained language model for Indonesian NLP. arXiv preprint arXiv:2011.00677.

The main issue of the model right now is the test accuracy is significantly drop compared with the train and validation set (overfitting). Further checking should be done especially in the graph modelling step. 
