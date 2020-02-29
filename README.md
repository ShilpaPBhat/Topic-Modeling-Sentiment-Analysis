# Topic Modeling & Sentiment Analysis

Topic Modeling: An unsupervised machine learning technique used to categorize set of text/documents into different clusters. It is similar to clustering on numeric data. Topic modeling could be used to identify the topics of a set of customer reviews by detecting patterns and recurring words.

Sentiment Analysis: A NLP technique that extracts the opinions present in the text. Basically summarizes the sentiment of text like positive, neutral and negative.

## Table of contents
* [About](#about)
* [Methodology](#methodology)
* [Code and Data](#code-and-data)
* [Result](#result)
* [Use Case](#use-cases)

## About
The goal of this project was to understand preprocessing text data like cleaning text by removing punctuation, symbols, numbers, stopwords. And then tokenizing, lemmatizing etc. Then perform 3 different analysis.

* Topic modeling - To understand what exactly the customer talk about their stay
* Sentiment analysis - To understand the polarity of the reviews
* Classification - Predicting if the host is super host or not by using features of comments

## Methodology

* Topic modeling with LDA - popular method for fitting topic model.
* Sentiment analysis -  based VADER - it is a type of sentiment analysis that is based on lexicons of sentiment-related words. Each of the words in the lexicon is rated as to whether it is positive, negative or neutral.
* Predicting if the host is super host or not - binary text classification was performed using different supervised machine learning methods and compared all of them to see which suits this dataset best.

## Code and Data
Austin airbnb data was used. The entire analysis and data used can be found [here](https://github.com/ShilpaPBhat/Topic-Modeling-Sentiment-Analysis/tree/master/data_code)

## Result
There were 4 topic mainly customers talked about their stay
* Topic 1: Location
* Topic 2: Overall - stay, location, place, comfort, space, host
* Topic 3: Space and comfort
* Topic 4: Particularly about room and stay

The datset has ~84% neutral, ~16% positive and barely any negative comments

To predict if the host is superhost or not, used 4 different models - Naive bayes, Linear SVC, Logistic regression and Random forest. 
Linear SVC fits the data best with test accuracy of 91.5%

## Use Cases
Came across this article which explains the use cases of [Sentiment Analysis](https://monkeylearn.com/sentiment-analysis/) & [Topic Modeling](https://monkeylearn.com/blog/introduction-to-topic-modeling/)



