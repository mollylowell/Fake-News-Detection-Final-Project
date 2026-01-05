# Fake-News-Detection-Final-Project
Detecting fake vs real news using NLP, feature engineering, and classification models
Fake vs. Real News Detection (NLP Project)

Overview
This project explores whether fake and real news articles can be distinguished based on writing style rather than factual accuracy. Using natural language processing and feature engineering, I analyzed structural and linguistic patterns in news articles and trained classification models to detect misinformation.

Dataset

Fake and Real News Dataset (Kaggle)

~45,000 labeled articles (fake vs real)

Sources include Reuters and known fake news websites

Time period: 2015–2018

What I Did

Cleaned and preprocessed raw news text

Engineered features related to:

Title and article length

Punctuation and formatting patterns

Numeric and statistical content

Linguistic and emotional tone

Explored topic distributions using LDA topic modeling

Trained and compared multiple classification models

Models Used

Logistic Regression

Random Forest

Linear Support Vector Machine (SVM)

Key Findings

Fake news titles tend to be longer and more sensational

Real news articles contain more detailed numeric information

Writing style alone is highly predictive of fake news

Random Forest achieved the strongest performance (F1 ≈ 0.92)

Files

fake_news_detection.ipynb – full data cleaning, analysis, modeling, and evaluation

Tools
Python, pandas, scikit-learn, NLTK, Google Colab

Data Access
The dataset is publicly available on Kaggle and is not included in this repository due to size.
