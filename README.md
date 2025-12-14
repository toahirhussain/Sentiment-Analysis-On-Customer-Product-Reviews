# Amazon Review Sentiment Analysis (Positive vs Negative)

# Overview

This project builds a machine learning pipeline to classify Amazon product reviews as Positive or Negative using Natural Language Processing (NLP). The final selected model is a Support Vector Machine (SVM) trained on vectorized text features and evaluated using multiple classification metrics.

# Objectives

Clean and preprocess raw review text

Convert text into numerical features (e.g., TF-IDF)

Train and tune multiple ML models

Select the best-performing model for sentiment prediction

Provide an evaluation summary and feature impact analysis

# Dataset

Source: [Add dataset source link or description]

# Target: Sentiment label (Positive / Negative)

Text Column: Review (or your column name)

Note: Any missing review values are handled to ensure stable preprocessing and vectorization.

Workflow

Data Loading

Text Preprocessing

Remove punctuation

Remove stopwords

Lemmatization

Vectorization

TF-IDF or Bag-of-Words representation

Train/Test Split

# Model Training

Baseline models (e.g., Logistic Regression, Naive Bayes)

Final model: SVM

Hyperparameter Tuning

GridSearchCV / RandomizedSearchCV

# Model Evaluation

Accuracy, Precision, Recall, F1-score

Cross-validation

Feature Impact

Permutation importance to interpret feature influence

## Models Used

Support Vector Machine (SVM) ✅ (Selected Model)

Logistic Regression

Multinomial Naive Bayes

Bernoulli Naive Bayes

Random Forest (optional / comparison)

## Why SVM?

SVM is selected because it performs strongly on high-dimensional, sparse text features (such as TF-IDF) and produces reliable decision boundaries for binary sentiment classification. It generalizes well and is a strong choice for production-style text classification.

## Results Summary

Best model: Support Vector Machine (SVM)

Evaluation metrics used: Accuracy, Precision, Recall, F1-score (and optional ROC-AUC)

Accuracy: 0.90


<img width="808" height="230" alt="{137FA43E-D7C8-4DAA-8D8D-CDB9C27EE521}" src="https://github.com/user-attachments/assets/f238a51a-9f2a-483a-95b3-f9ae718ac121" />
<img width="1162" height="657" alt="{42884684-8A86-4834-8CCA-DA4273529876}" src="https://github.com/user-attachments/assets/08437359-75fe-499d-a0ae-1b4d38875c55" />


License

This project is provided for educational and portfolio purposes.
License: [MIT]

Author

Md Toahir Hussain
LinkedIn: [https://www.linkedin.com/in/md-toahir-hussain-79009a14b/]

