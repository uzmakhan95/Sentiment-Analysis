# Sentiment-Analysis
This repository contains a sentiment analysis model that classifies text into sentiments using various machine learning algorithms. The model processes input text, applies preprocessing techniques, and predicts the sentiment using trained models.  
  
Features:  
Data Processing: The model preprocesses input text to ensure consistency with training data.  
TF-IDF Vectorization: Transforms text data into numerical features suitable for machine learning models.  
Model Training: Includes training and prediction using multiple algorithms:  
Logistic Regression  
Naive Bayes  
Support Vector Machine (SVM)  
User Interaction: Allows for interactive text input to analyze sentiment in real-time.  

Setup and Usage:  
Install Dependencies: Ensure you have the required libraries (numpy, scikit-learn, joblib).  
Train Models: Fit the TF-IDF vectorizer and machine learning models on your training data.  
Run Predictions: Input text and receive sentiment predictions from the trained models.  

Instructions:  
Preprocess Text: Convert text to lower case and apply other preprocessing steps as needed.  
Vectorize Text: Use the fitted TF-IDF vectorizer to convert text into features.  
Predict Sentiment: Apply the trained models to get sentiment predictions.  
