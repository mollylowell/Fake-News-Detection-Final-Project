# Fake News Detection (NLP Final Project)

Detecting fake vs. real news articles using natural language processing, feature engineering, and classification models.

---

## Overview

This project explores whether fake and real news articles can be distinguished based on **writing style rather than factual accuracy**. Using NLP techniques and feature engineering, I analyzed structural and linguistic patterns in news articles and trained multiple classification models to detect misinformation.

---

## Dataset

- **Fake and Real News Dataset** (Kaggle)
- Approximately **45,000 labeled articles** (fake vs. real)
- Sources include **Reuters** and known fake news websites
- Time period: **2015–2018**

> The dataset is publicly available on Kaggle and is not included in this repository due to size.


---

## Models Used

- Logistic Regression  
- Random Forest  
- Linear Support Vector Machine (SVM)

---

## Key Findings

- Fake news titles tend to be **longer and more sensational**
- Real news articles contain **more numeric and financial detail**
- Writing style alone is highly predictive of fake news
- **Random Forest** achieved the strongest performance (F1 ≈ 0.92)

---

## Files

- `Final_Project_Code.ipynb`  
  Full data cleaning, feature engineering, modeling, and evaluation workflow

---

## Tools & Technologies

Python, pandas, scikit-learn, NLTK, Google Colab

---

## How to Run

1. Open the notebook in Google Colab
2. Download the dataset from Kaggle
3. Run cells in order

