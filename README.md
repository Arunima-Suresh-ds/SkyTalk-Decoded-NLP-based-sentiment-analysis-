# SkyTalk-Decoded-Automated-Sentiment-Intelligence-from-Airline-Twitter-Data
![Python](https://img.shields.io/badge/Python-3.8+-black?style=flat&logo=python)
![Task](https://img.shields.io/badge/Task-Twitter%20Sentiment%20Analysis-orange)
![Technique](https://img.shields.io/badge/Technique-TF--IDF%20%7C%20NLP-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

SkyTalk Decoded is an NLP-based sentiment analysis project that automatically classifies airline-related tweets into **Positive, Neutral, or Negative** sentiments. The goal is to help airlines monitor customer feedback at scale and gain actionable insights from social media conversations.
The project applies traditional Machine Learning and NLP techniques and evaluates multiple models to identify the best-performing classifier.

---

##  Objectives
- Clean and preprocess raw Twitter text data
- Extract meaningful textual features using TF-IDF
- Build and compare multiple classification models
- Accurately classify customer sentiment into three categories
- Provide data-driven insights for airline service improvement

---

##  Dataset
- **Source:** Airline Twitter data (`tweets.csv`)
- **Records:** ~14,600 tweets
- **Target Variable:** Sentiment (Positive, Neutral, Negative)
- **Data Type:** Unstructured text

---

##  Data Preprocessing
- Text cleaning (lowercasing, removing URLs, mentions, punctuation)
- Tokenization and lemmatization
- Stopword removal
- TF-IDF vectorization for feature extraction

---

## Models Implemented
- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)
- **XGBoost Classifier (Final Model)**

---

##  Model Evaluation
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix

###  Final Model Performance
- **Model:** XGBoost Classifier
- **Accuracy:** ~76%
- Balanced performance across all sentiment classes
- Outperformed a custom-built deep learning neural network

---

##  Key Insights
- Negative sentiment tweets are more frequent and informative
- Machine learning models perform competitively on TF-IDF features
- XGBoost provides strong generalization on noisy social media text

---

##  Impacts

The project enables airlines to:
- Automatically monitor large volumes of customer feedback at scale
- Identify negative sentiment trends related to service disruptions or customer dissatisfaction
- Support faster, data-driven responses to customer issues
- Improve overall customer experience through sentiment-aware decision-making
- Reduce reliance on manual analysis by leveraging automated classification
- Deploy a cost-effective solution using traditional ML models that perform well on noisy text data


---
