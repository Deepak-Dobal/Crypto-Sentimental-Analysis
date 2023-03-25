# Crypto-Sentimental-Analysis
entiment analysis can be used in the crypto industry to predict the rise or fall of a cryptocurrency's price based on the sentiment of its users.

Sentiment Analysis
Sentiment analysis is the process of analyzing and determining the emotional tone behind a piece of text. It is widely used in the financial industry to predict stock prices based on social media posts and news articles. Similarly, sentiment analysis can be used in the crypto industry to predict the rise or fall of a cryptocurrency's price based on the sentiment of its users.
Here are the steps involved in sentiment analysis using ML:
1-Data Collection: The first step in sentiment analysis is to collect data from various sources, such as social media platforms, news articles, and blogs, that contain information about cryptocurrencies. In this project I will be using Twitter data for sentimental analysis.
2-Data Preprocessing: Once the data is collected, it needs to be preprocessed to remove any irrelevant information and noise. This involves removing stop words, stemming, and lemmatizing the text.
3-Feature Extraction: The next step is to extract features from the preprocessed text data. This involves converting text data into numerical data that can be fed into ML algorithms. Some commonly used feature extraction techniques are bag-of-words, term frequency-inverse document frequency (TF-IDF), and word embeddings.
4-ML Model Training: Once the features are extracted, the next step is to train an ML model on the sentiment-labelled data. There are various ML models that can be used for sentiment analysis, such as logistic regression, support vector machines (SVM), and neural networks. But for this project, I will be using vaderSentiment, Roberta Pre Trained Model.
5-Model Evaluation: The final step is to evaluate the performance of the ML model using metrics such as accuracy, precision, recall, and F1-score. This helps to determine the effectiveness of the sentiment analysis model in predicting the sentiment of cryptocurrency users.And 
Wordcloud based on the hashtags
