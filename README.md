# Twitter-Sentiment-Analysis
This project aims to perform sentiment analysis on Twitter data using machine learning techniques. The main objective is to classify tweets into different sentiment categories based on their content.

## Introduction
Sentiment analysis, also known as opinion mining, is the process of determining the sentiment expressed in a piece of text. In this project, we focus on analyzing sentiment in Twitter data. By applying machine learning algorithms, we can automatically classify tweets as positive, negative, or neutral based on their sentiment.

## Dataset
Two datasets are used in this project:
Training Dataset: twitter_training.csv
Validation Dataset: twitter_validation.csv

## Data Preprocessing
Lowercasing: Convert all text to lowercase to ensure uniformity.
Removing Special Characters: Remove all non-alphanumeric characters using regular expressions.
Tokenization and Stemming: Tokenize the text, remove stop words, and apply stemming using the NLTK library.

## Feature Extraction
TF-IDF Vectorization: Convert the text data into numerical vectors using TF-IDF (Term Frequency-Inverse Document Frequency).

## Model Training
Logistic Regression: Train a logistic regression model to classify the sentiment of tweets.

## Model Evaluation
Classification Report: Evaluate the model's performance on both the test set and the validation set using precision, recall, and F1-score metrics.

## Model Selection:
Logistic Regression, with its simplicity and efficiency, performs well for text classification tasks.
The model achieves good accuracy and balance across precision, recall, and F1-score.

## Model Performance:
The logistic regression model demonstrates strong performance on both the test set and the validation set, indicating good generalization capability.

