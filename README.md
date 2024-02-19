# Tweets

![tweet](img/tweets_logo.jpeg)

## Intro to Natural Language Processing. Sentiment Analysis

_Summary:_ This project is an introduction to natural language processing: bag of words, TFIDF, stemming, lemmatization,
stop-words, cosine similarity, n-grams, word2vec.

## Contents

1. [Goals](#goals)
2. [Chapter I](#chapter-i) \
   2.1. [Mandatory part](#mandatory-part)
3. [Chapter II](#chapter-ii) \
   3.1. [Bonus part](#bonus-part)

### Goals

The goal of this project is to give you a first approach to NLP. You will try to preprocess text data and train
different classifiers trying to solve a classification task with the best possible score.

## Chapter I

### Mandatory part

#### a. Task

In this project, you will work on sentiment analysis of tweets. You will need to predict whether a tweet is positive,
negative, or neutral.

* Data preparation. Transform tweets into vectors using different approaches.
* Similarity. Find the top-10 most similar pair of tweets using datasets with different preprocessing.
* Machine learning. Using different machine learning algorithms and different datasets with different preprocessing
  conduct sentiment analysis.

#### b. Dataset

* You will work with the dataset of tweets. The tweets are labeled as positive, negative, and neutral. That is it. The
  [source](/src/datasets/) of the datasets.

**Data preparation**

You can perform any cleaning technique before if you find it useful.

You may also try using [stop-words](https://en.wikipedia.org/wiki/Stop_word) to remove the words that create noise and
not a signal.

**Similarity**

Use different datasets that you prepared in the task above and cosine similarity to find the top-10 similar pairs of
tweets.

**Machine learning**

Try different algorithms and different datasets that you prepared before to solve the classification task – sentiment
analysis.

#### d. Submission

You need to achieve accuracy at least equal 0.832 on the test dataset.

Your repository should contain one or several notebooks with your solutions.

## Chapter II

### Bonus part

* Try to use word2vec to get a better vectorization of texts.✅
* Try to achieve a better accuracy on the test dataset – 0.851. ✅
* Try to achieve an even better accuracy on the test dataset – 0.873. ✅

