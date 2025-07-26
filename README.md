# Sentiment Analysis on Twitter Data

## Overview

This project analyzes and visualizes sentiment patterns in Twitter data to understand public opinion and attitudes toward various entities (topics or brands). It combines data preprocessing, sentiment classification, and insightful visualizations using Python and machine learning techniques.

---

## Objective
  
Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or brands.

---

## 📁 Dataset

- **Training File:** `twitter_training.csv`  
- **Validation File:** `twitter_validation.csv`

Each file contains the following columns:
- `tweet_id`: Unique identifier of the tweet  
- `entity`: Brand or topic associated with the tweet  
- `sentiment`: Sentiment label (Positive, Negative, Neutral)  
- `content`: Raw tweet text

---

## Techniques Used

- Text Cleaning and Preprocessing (Regex, Stopwords, Lowercasing)
- Feature Extraction using **TF-IDF**
- Sentiment Classification using **Logistic Regression**
- Data Visualization using **Matplotlib**, **Seaborn**, and **WordCloud**
- Time-series Sentiment Trend Analysis (Simulated)
- Actual vs Predicted Sentiment Comparison

---

## Visualizations

- **Sentiment Distribution** – Overall frequency of sentiments  
- **Word Clouds** – Most common words for each sentiment  
- **Entity-Level Sentiment** – Bar chart comparing sentiment across top entities  
- **Predicted vs Actual Comparison** – Accuracy of predictions visualized per entity  
- **Time-Series Sentiment Trends** – Simulated rolling average trends over 90 days

---
