# Predicting stock movements using NLP and Deep Learning

## 1. Problem Statement

A significant number of companies in the financial services and banking industry have long
spent millions of dollars and dedicated a vast amount of resources to quantify and analyze
qualitative data from a variety of media outlets in order to gain valuable information in making
investment decisions. Despite its potential, there is limited success in stock market prediction
due to the wide range of difficulties which lie in the complexities of modeling stock market
dynamics (Schumaker and Chen, 2009).

This project attempts to predict the stock movements of Dow Jones Industrial Average (DJIA)
using news headlines scraped from the Reddit WorldNews Channel (r/worldnews). In particular,
this project uses the textual data of historical news headlines to predict whether the DJIA index
will go up or down. Various advanced machine learning algorithms were experimented along
with several deep learning neural network architectures including a fully-connected multilayer
perceptron (MLP), recurrent neural network (RNN), and convolutional neural network (CNN)
for the predictions.

## 2. The Client

The client of this project could be banks, corporate finance offices, and anyone else who is 
interested or involved in trading securities on public markets. The analyses of this project would
help them make better investment decisions.

## 3. Data

The data for the news headlines were crawled from the Reddit WorldNews channel (r/worldnews).
Only the top 25 news headlines were considered for a single date. The DJIA stock data were
downloaded directly from the Yahoo Finance. The combined dataset includes a date column and
a label column along with 25 news headlines columns. The “Label” column is the target feature
and consists of the values of 0 and 1. While 1 indicates that the DJIA adjusted close value stayed
the same or went up on that date, 0 represents that it dropped on that particular date.

## 4. Method

### 1. Text Preprocessing

All the textual data were preprocessed by lowercasing, removing stopwords, punctuation, and numbers,
and lemmatizing words using the NLTK package.

### 2. Machine Learning

Six advanced supervised machine learning models including Logistic regression, Multinomial
Naïve Bayes, Random Forest Classifier, Support Vector Machine Classifier, XGBoost Classifier,
and Bernoulli Naïve Bayes were constructed in a pipeline using Scikit Learn’s Pipeline module.

In addition to these models, three deep learning neural network architectures including a fully-
connected multilayer perceptron (MLP), recurrent neural network (RNN), and convolutional neural 
network (CNN) were constructed using Keras with a Tensorflow backend.

## 5. Results

The top-performing model achieved an accuracy score of 58% on the validation data. Although this
project only touches the surface of NLP techniques here, a 58% accuracy score suggests that the
efforts to extract textual data from a variety of sources to make investment decisions could be
worth the while.

## 6. Business Recommendations

1. Vast amount of resources is being dedicated every year to make better investment
decisions in the financial and banking industry. As this project indicates, the use of NLP
on the textual data extracted from different sources is very promising in providing better
informed decisions. Investment banks, corporate finance offices and anyone else who is
interested or involved in trading securities on public markets as the clients of this project
can take advantage of the qualitative data in making better investment decisions.

2. Since the advent of big data and powerful GPUs, the deep learning neural networks have
the potential to revolutionize the stock market trading.

3. Changes in stock movements was only measured immediately after news headlines
release. However, it is also quite possible that stock movements may react in the days
following the release of news headlines.

## 7. The full report and slide deck are also provided as separate PDF files under the report file.
