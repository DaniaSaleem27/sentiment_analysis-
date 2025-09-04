Sentiment Analysis Project

Overview
This project implements a simple text sentiment analysis model that classifies movie reviews as positive or negative using machine learning techniques. The model is trained on movie descriptions from the IMDb Top 1000 dataset.

Objective
Build a sentiment analysis classifier that can predict whether a movie review/description expresses positive or negative sentiment.

Dataset
Source: IMDb Top 1000 Movies
File: Top_1000_IMDb_movies_New_version.csv
Features Used: Movie descriptions and ratings
Sentiment Labeling:
Positive (1): Rating ≥ 6.5
Negative (0): Rating < 6.5

Implementation Steps

1. Preprocessing
Convert text to lowercase
Remove special characters and digits
Eliminate extra whitespace
Remove stopwords using NLTK

2. Feature Engineering
Convert text data to numerical format using CountVectorizer
Create a vocabulary of the most frequent 1000 words
Transform text into document-term matrix

3. Model Training
Algorithm: Logistic Regression
Training/Test Split: 80%/20%
Random State: 42 for reproducibility
Max Iterations: 1000 for convergence

4. Model Evaluation
Primary Metric: Accuracy
Additional Metrics: Precision and Recall (optional)
Cross-validation ready implementation
