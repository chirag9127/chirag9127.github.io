---
title: "Survey of Sentiment Classification Methods: Introduction"
date: 2017-01-01
categories:
  - Post
---

This is the start of a series of notes focusing on the sentiment analysis problem.

## Why study sentiment analysis?

For humans competent in a language, it is fairly easy to understand the polarity of a given piece of text. Hence it is important to provide this capability to machines so that analysis of large amounts of text can become possible. There are many applications to this which have already been used in the industry for commercial success.

- Companies analyse Twitter sentiment to understand the popularity of a product or campaign.
- Hedge funds mine opinions of news articles to make stock purchases/sales.

Some of these tools can be generalized to text analysis and classification. E.g. Classifiying a text into two categories.

## Methodology

These notes are going to cover different representations of text and different machine learning methods, with a goal to understand the cases in which a method would work well and why.

Some of the methods which I will try to go through:

- Bag of words with Naive Bayes
- Bag of Bigrams with some text processing
- Word Vector representation with Logistic Regression, SVM and multilayer perceptron
- Parapgraph vectors
- LSTMs for sentiment analysis
- CNNs

The dataset I will be using is the Large Movie Review Dataset (http://ai.stanford.edu/~amaas/data/sentiment/). The dataset consists of 25000 (50% splits of positive and negative) moview reviews for training and 25000 for testing. 

## References

Andrew L. Maas, Raymond E. Daly, Peter T. Pham, Dan Huang, Andrew Y. Ng, and Christopher Potts. (2011). Learning Word Vectors for Sentiment Analysis. The 49th Annual Meeting of the Association for Computational Linguistics (ACL 2011).
