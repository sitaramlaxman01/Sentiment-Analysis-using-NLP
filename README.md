# Sentiment-Analysis-using-NLP
This project focuses on building a Sentiment Analysis model using Natural Language Processing (NLP) techniques to classify text into Positive, Negative, and Neutral categories.
# Project Overview
The goal of this project is to analyze textual data and automatically determine the sentiment expressed in the text. This is a multiclass classification problem.
# Technologies Used
  Python
  NumPy
  Pandas
  Scikit-learn
  NLP (TF-IDF / CountVectorizer)
# Project Workflow
  Data Cleaning & Text Preprocessing
  Stopwords Removal
  Feature Extraction using TF-IDF
  Model Building (Logistic Regression)
  Model Evaluation (Accuracy & Cross-validation)

  The model was evaluated using train-test split and 5-fold cross-validation to ensure stability and reliability.

  In my project, the model achieved 100% accuracy during cross-validation. This may indicate that the dataset is small or very clean.
  However, such perfect accuracy can sometimes suggest overfitting or data leakage. To ensure model reliability, I verified proper 
  train-test splitting and checked that there was no leakage between training and testing data.
