# NLP_SentimentClassification

The task of classifying sentiments of texts (for example movie or product reviews) has high practical significance in online marketing as well as financial prediction. This is a non-trivial task, since the concept of sentiment is not easily captured. 
For this project we are using the larger IMDB sentiment benchmark dataset from Stanford, an achieve close to state of the art results. The task is to try out multiple models in ascending complexity, namely: 
1.TFIDF + classical statistical model (eg. RandomForest) 
2.LSTM classification model 
3.LSTM model, where the embeddings are initialized with pre-trained GloVe vectors 
4.fastText model 
5.BERT based model
