# Fake-News-Prediction

## Overview

The topic of fake news detection on social media has recently attracted tremendous attention. The basic countermeasure of comparing websites against a list of labeled fake news sources is inflexible, and so a machine learning approach is desirable. Our project aims to use Natural Language Processing to detect fake news directly, based on the text content of news articles.

## Dataset

- train.csv: A full training dataset with the following attributes:
  - id: unique id for a news article
  - title: the title of a news article
  - author: author of the news article
  - text: the text of the article; could be incomplete
  - label: a label that marks the article as potentially unreliable
    - 1: unreliable
    - 0: reliable
- test.csv: A testing training dataset with all the same attributes at train.csv without the label.


## Models Used

- Logistic Regression
- Naive Bayes Classifier
- Passive Aggressive Classifier

## Accuracies of Models

- Logistic Regression : Accuracy is 0.98
- Multinomial Naive Bayes : Accuracy is 0.95
- Passive Aggressive Classifier : Accuracy is 0.99
