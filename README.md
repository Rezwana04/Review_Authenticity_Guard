# TextAuthenticityGuard - Detecting Genuine and Fake Reviews

## Description
This project aims to distinguish between genuine and fake product reviews within a dataset. The dataset contains a mix of real and computer-generated reviews, each labeled as original (authentic human-created) or computer-generated (fake). The primary objective is to create a system that accurately identifies whether a given review is authentic or fraudulent.

## Methodology
- Data Preprocessing:
  - Eliminating punctuation and digits
  - Converting text to lowercase
  - Removing stopwords
  - Applying stemming and lemmatization
  
- Text Feature Extraction and Normalization:
  - Utilizing CountVectorizer for Bag of Words representation
  - Implementing TFIDF (Term Frequency-Inverse Document Frequency) transformation

- Machine Learning Algorithms:
  - Logistic Regression
  - K Nearest Neighbors
  - Support Vector Classifier
  - Decision Tree Classifier
  - Random Forests Classifier
  - Multinomial Naive Bayes
  - XGBoost
  - K-means clustering

- Performance Evaluation:

## Usage
...
