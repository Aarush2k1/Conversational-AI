# ANALYSIS OF PRODUCT REVIEWS USING SUPERVISED LEARNING

## Data Collection
![Kaggle challenge](https://www.kaggle.com/c/amazon-pet-product-reviews-classification/data)

## Data Preprocessing
- It cleans the unnecessary Data so that the Machine will Learn batter and also performed well.
- Used nltk copus to remove stopwords, perform tokenization and lemmatization.

## Vectorization
Text is converted into Numeric Form so that the ML model can understand as it is a mathematical model

Many Techniques Present like TF-IDF, Count-Vectorizer, FastText Word Embedding (extension of the word2vec model)

Here I used TF-IDF 
 - It measures how important a word in a given document with a collection of documents
 - TF measures the occurrences of the word in a particular document
 - IDF measures informativeness of word in a collection of documents. In this work,

## Models used for Sentiment Classification
Used Logistic Regression

Nueral Networks are also used, like augmented rnn.
