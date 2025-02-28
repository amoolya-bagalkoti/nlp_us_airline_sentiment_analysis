Project Overview

This project analyzes sentiment in U.S. airline tweets using various text representation techniques, such as Bag of Words (BoW), TF-IDF, Word2Vec, and GloVe. These features are fed into three machine learning models: SVM, Naive Bayes, and Random Forest, to classify tweets as positive, neutral, or negative.

The preprocessing pipeline included noise removal (e.g., deleting URLs, mentions, hashtags, and stop words), text cleaning (standardizing text by converting to lowercase and removing numbers and special characters), tokenization (splitting tweets into individual words), and lemmatization (reducing words to their root forms to minimize dimensionality).

Despite Word2Vec and GloVe being better at capturing semantic relationships, TF-IDF outperformed them due to its ability to highlight key terms and adapt well to the relatively small and structured dataset of airline tweets. This result emphasizes the importance of feature representation in achieving robust sentiment classification.

The project is built upon the publicly available Kaggle Twitter Airline Sentiment dataset and provides actionable insights to help airlines improve their services based on customer feedback.
