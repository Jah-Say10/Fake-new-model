# Fake News Detection Model

A machine learning model that detects whether a news article is fake or legitimate using Natural Language Processing (NLP) techniques and the Multinomial Naive Bayes classifier.

## Overview

This project implements a text classification model to identify fake news articles. The model processes news text through various NLP techniques and uses machine learning to classify articles as either fake or legitimate.

## Dataset

The model is trained on a labeled dataset from Kaggle containing:
- Fake news articles: 23,481 samples
- True news articles: 21,417 samples

Dataset source: [Fake News Detection Dataset (Kaggle)](https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets)

## Features

- Text preprocessing pipeline including:
  - Lowercasing
  - Tokenization
  - Stop word removal
  - Lemmatization
  - Punctuation removal
- Feature extraction using Count Vectorization
- Classification using Multinomial Naive Bayes
- ~97% accuracy on test set

## Requirements

The following Python packages are required:

```txt
scikit-learn==1.5.2
fastapi==0.115.5
uvicorn==0.32.0
joblib==1.4.2
numpy==2.0.2
pandas==2.2.3
spacy==3.8.

