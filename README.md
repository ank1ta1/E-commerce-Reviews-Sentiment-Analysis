# E-commerce-Reviews-Sentiment-Analysis

This repository contains Python code for performing sentiment analysis and predicting product ratings based on customer reviews. The analysis is conducted using various natural language processing (NLP) techniques and machine learning models. Below is an overview of the code's functionality and structure:


### Usage
1. **Data Preparation:** The code starts by loading a CSV file (`clothing_reviews.csv`) containing customer reviews and associated ratings. It cleans the data, removes null values, and combines the review title and text into a single 'Review' column. The code also explores the data by displaying rating distributions, word frequency analysis, and generating word clouds.

2. **Sentiment Analysis:** Sentiment analysis is performed using the VADER sentiment analysis tool from NLTK. It classifies each review as 'positive,' 'negative,' or 'neutral' based on sentiment scores. The results are compared with actual ratings to evaluate sentiment prediction accuracy. The confusion matrix and classification report are also displayed.

3. **Rating Prediction:** The code aims to predict product ratings (0: Negative, 1: Neutral, 2: Positive) from the review text. It uses TF-IDF vectorization to convert the text data into numerical features. Several machine learning models, including Random Forest, Naive Bayes Multinomial, XGBoost, Logistic Regression, and Linear SVC, are trained and evaluated for their accuracy in predicting ratings. The confusion matrix and classification report for each model are presented.

4. **Model Comparison:** A summary table compares the accuracy scores of different machine learning models for rating prediction, helping you identify the best-performing model.

### Conclusion
This code provides a comprehensive analysis of customer reviews, including sentiment analysis and rating prediction. It enables you to gain insights from text data and select a suitable model for predicting product ratings based on customer feedback.

