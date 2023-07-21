# Sentimental-Analysis

Sentiment analysis is a natural language processing (NLP) technique used to determine a text's sentiment or emotional tone. Sentiment analysis is a powerful tool that can be applied across various industries to gain insights into customer feedback, public opinion, brand perception, and much more.

The primary goal of sentiment analysis is to classify the sentiment of a given text into different categories such as positive, negative, and neutral.

The data set used in the project is taken from Kaggle - 'Amazon food reviews'.

In this project we have used the concepts of Sentimental analysis to find the sentiment in the reviews of the customer, we have used Logistic Regression with CountVectorizer and the accuracy turned out to be 0.896

![image](https://github.com/Hirshikesh2003/Sentimental-Analysis/assets/78225619/4287fa37-a043-438d-bcbd-56bd5d23bc4b)

And the dataset is also trained with Logistic Regression with tfidf and the accuracy turned out to be 0.892

![image](https://github.com/Hirshikesh2003/Sentimental-Analysis/assets/78225619/5eace4d8-c599-4839-af36-a2cb96e9b824)


# VADER

VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool specifically designed for social media text. It is part of the Natural Language Toolkit (NLTK) library in Python and is widely used for sentiment analysis tasks due to its simplicity and effectiveness.

VADER comes with a pre-built sentiment lexicon that contains a list of words and their associated sentiment scores. Each word is assigned a polarity score (positive or negative) and an intensity score, representing the sentiment's strength. The lexicon also takes into account the context of words and typical punctuation patterns.

We have also used the VADER package in this project and added the polarity score to the dataset.

![image](https://github.com/Hirshikesh2003/Sentimental-Analysis/assets/78225619/43734739-507c-47f1-a3d5-4740c3c5dac7)

And with the below visualization we can see the number of positive, negative and neutral reviews in the dataset.

![image](https://github.com/Hirshikesh2003/Sentimental-Analysis/assets/78225619/452215a4-bb87-4e19-aa60-dfc2b21f6029)



# NLTK

The Text column in the dataset is cleaned using the nltk package by removing the stopowords and so, the clean text along with the score are added to a dataframe.

![image](https://github.com/Hirshikesh2003/Sentimental-Analysis/assets/78225619/3600de7e-df82-448b-84bb-7c637e8e6533)


# Word cloud

Further, to know the most used words in the dataset, we take the help of the wordcloud. The clean text from above is given as the input for the word cloud.

![image](https://github.com/Hirshikesh2003/Sentimental-Analysis/assets/78225619/730f9704-0772-4139-b7c1-df606444c60a)

