# IMDB Sentiment Analysis

## Overview
This project analyzes movie reviews from the IMDB dataset to classify them as **positive** or **negative**. It demonstrates text preprocessing, feature extraction, machine learning model training, and evaluation using Python.

## Dataset
The dataset used is `IMDB Dataset.csv` and contains:
- `review` – text of the movie review
- `sentiment` – target label (`positive` or `negative`)

**Source:** [IMDB Dataset of 50K Movie Reviews on Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

## Tools & Libraries
- Python: `pandas`, `numpy`
- Text Processing: `re`, `string`
- Machine Learning: `scikit-learn` (Logistic Regression, TF-IDF Vectorizer)
- Visualization: `matplotlib`, `seaborn`

## Features
- Clean and preprocess text data (remove punctuation, lowercase, remove numbers)
- Convert text to numerical features using TF-IDF
- Train a Logistic Regression classifier for sentiment prediction
- Evaluate model performance using accuracy, classification report, and confusion matrix
- Predict sentiment for new reviews
