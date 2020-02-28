# Topic Modeling & Sentiment Analysis

Topic Modeling: It is a unsupervised machine learning technique used to categorize set of text/documents into different clusters. It is similar to clustering on numeric data.Topic modeling could be used to identify the topics of a set of customer reviews by detecting patterns and recurring words.

Sentiment Analysis: A NLP technique that extracts the opinions present in the text. Basically summarizes the sentiment of text like positive, neutral, and negative

## Table of contents
* [About](#about)
* [Methodology](#methodology)
* [Code and Data](#code-and-data)
* [Result](#result)
* [Use Case](#use-cases)

## About
The goal of this project was to understand preprocess text data like cleaning text by removing punctuation, symbols, numbers, stopwords. And then tokenizing, lemmatizing etc. And perform 3 different analysis.

* Topic modeling - To understand what exactly the customer talk about their stay
* Sentiment analysis - To understand the polarity of the reviews
* Predicting if the host is super host or not 

## Methodology

* Topic modeling with LDA - popular methos for fitting topic model.
* Sentiment analysis -  based VADER - it is a type of sentiment analysis that is based on lexicons of sentiment-related words. Each of the words in the lexicon is rated as to whether it is positive negative or neutral.
* Predicting if the host is super host or not - this analysis was performed using different supervised machine learning methods and compared all of them to see which suits this dataset best.

## Code and Data
The entire analysis and data can be found [here](https://github.com/ShilpaPBhat/Topic-Modeling-Sentiment-Analysis/tree/master/data_code)

## Result
There were 4 topic mainly customers talk about
* Topic 1: Location
* Topic 2: Overall - Stay, location, place, comfort, space, host
* Topic 3: space and comfort
* Topic 4: Particularly about room and stay

The datset has 84% neutral, 16% positive and barely any negative comments

To predict if the host is superhost or not, used 4 different models - Naive bayes, Linear SVC, Logistic regression and Random forest. 
Linear SVC fits the date better with test accuracy of 91.5%

## Use Cases
Came across this article which explains the use cases of [Sentiment Analysis](https://monkeylearn.com/sentiment-analysis/) & [Topic Modeling](https://monkeylearn.com/blog/introduction-to-topic-modeling/)



