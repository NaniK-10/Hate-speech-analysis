# Hate Speech Detection in Twitter Data

This project builds a machine learning model to detect hate speech in Twitter posts using Natural Language Processing (NLP) techniques.

## Overview

Online platforms receive a massive number of user-generated posts every day. Detecting hate speech automatically can help improve moderation and reduce harmful content.  

This project analyzes a Twitter dataset and trains machine learning models to classify tweets containing hate speech.

---

## Dataset

- Dataset: Twitter Hate Speech Dataset
- Size: ~20,000 tweets
- Target variable: `class`

The dataset contains tweets labeled according to the presence of hate speech.

---

## Project Workflow

### 1. Data Cleaning
- Loaded dataset using **Pandas**
- Removed unnecessary columns
- Checked dataset size and class distribution

### 2. Exploratory Data Analysis
- Inspected tweet samples
- Analyzed distribution of classes
- Observed dataset characteristics

### 3. Text Preprocessing
Natural Language Processing preprocessing steps were applied:

- Tokenization
- Stop-word removal
- Lemmatization
- Text normalization

These steps help convert raw tweets into meaningful textual features.

### 4. Feature Engineering

Tweets were converted into numerical vectors using:

- **TF-IDF Vectorization**

This representation captures word importance across the dataset.

---

## Machine Learning Models

Two classification models were trained:

- **Naive Bayes**
- **Logistic Regression**

These models were trained using Scikit-learn to classify tweets into hate speech categories.

---

## Results

- **Best Model Accuracy: 93%**
- Evaluated using classification metrics.

The model successfully identifies patterns associated with hate speech in tweets.

---

## Technologies Used

- Python
- Pandas
- NLTK
- Scikit-learn
- NumPy
- Jupyter Notebook

---

## Repository Structure
