# 📰 News Article Classifier

A machine learning project that automatically classifies news articles into four categories: Business, Sports, Crime, and Science using various classification algorithms.

## 🎯 Overview

This project implements a news article classification system using natural language processing (NLP) and machine learning techniques. The model processes text data through spaCy and evaluates multiple classifiers to determine the best performance.

## 🔧 Features

- **Text Preprocessing**: Utilizes spaCy for efficient text processing.
- **Vector Embeddings**: Generates vector embeddings to represent text data.
- **Multiple Classifier Implementations**:
  - Decision Tree
  - Multinomial Naive Bayes
  - K-Nearest Neighbors (KNN)
  - Random Forest
  - Gradient Boosting

## 📊 Dataset

The dataset contains 12,695 news articles with the following distribution:

- Business: 4,254 articles
- Sports: 4,167 articles
- Crime: 2,893 articles
- Science: 1,381 articles

## 🚀 Performance

The best performing models were:

- **KNN Classifier**: 88% accuracy
- **Gradient Boosting**: 88% accuracy
