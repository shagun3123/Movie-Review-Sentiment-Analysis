# Movie Review Sentiment Analysis

This repository contains a sentiment analysis model developed using a comprehensive dataset of movie reviews. The model classifies the text polarity into positive, negative, and neutral categories.

## Project Overview

### Dataset Utilization
- Developed a sentiment analysis model using a comprehensive dataset of 50,000 movie reviews.
- Additionally, a smaller dataset with 1,000 entries is available for quick testing and prototyping.

### Data Preprocessing and Feature Extraction
- Extensive data preprocessing techniques including text cleaning and tokenization.
- Utilized TF-IDF for feature extraction, resulting in a feature matrix of 25,000 unique terms.

### Model Training
- Trained four different machine learning models:
  - Logistic Regression
  - Random Forest
  - Linear SVC
  - Naïve Bayes
- Used an 80/20 training-test split for robust evaluation.

### Performance Achievements
- Achieved a maximum accuracy of 84.5% with the Random Forest classifier.
- Evaluated model performance using precision, recall, F1-score, and confusion matrix.

## Directory Structure

```plaintext
Movie_Review_Sentiment_Analysis/
│
├── README.md
├── data/
│   ├── large_dataset.csv  # 50,000 entries
│   └── small_dataset.csv  # 1,000 entries
│
├── models/
    ├── logistic_regression_model
    ├── random_forest_model
    ├── linear_svc_model
    |── naive_bayes_model


