### Overview
In this repository, I provide an overview of my ML modeling framework to predict the sentiment of twitter data. 

### Dataset
I use Twitter Sentiment Analysis Dataset from Kaggle. It can be downloaded from this [link](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis). <br>
Given a message and an entity, the task is to judge the sentiment of the message about the entity. There are three classes in this dataset: Positive, Negative and Neutral. We regard messages that are not relevant to the entity (i.e. Irrelevant) as Neutral.

### Data Processing
I first perform text cleaning (special character removal, etc.), followed by tokenization, stopword removal, and stemming. <br>
I also perform some EDA (exploratory data analysis), looking at distribution of labels, and most frequent words (through wordcloud library)

### Feature Extraction
I extract word frequency base features from each tweet, and use them for predicting the sentiment. <br>
As the next step, I plan to extract word2vec based features from each tweet (by taking the average of all words in a tweet). 

