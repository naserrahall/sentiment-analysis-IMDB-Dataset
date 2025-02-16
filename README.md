# Sentiment Analysis using IMDB Dataset

## Project Description

This project classifies IMDb movie reviews as positive or negative using natural language processing (NLP) and machine learning. It involves data cleaning, text preprocessing (tokenization, stemming, lemmatization, stopword removal), and feature extraction using TF-IDF and Count Vectorization. Multiple classifiers, including Logistic Regression, Random Forest, Naïve Bayes, and K-Nearest Neighbors, were trained and evaluated. Hyperparameter tuning was applied to optimize performance, and models were assessed using accuracy, F1-score, and confusion matrices. The project demonstrates expertise in NLP, machine learning, and model evaluation for sentiment classification tasks.

## Contents

- **Data Import:** Load and analyze the IMDB dataset.
- **Data Cleaning:** Handle missing values and remove unnecessary text.
- **Text Preprocessing:** Convert text into formats suitable for machine learning.
- **Machine Learning Models:** Apply different algorithms for sentiment classification.
- **Model Evaluation:** Measure classification accuracy using metrics like precision and recall.


## **Key Components:**
1. **Data Preprocessing**  
   - Loaded and cleaned the IMDb dataset.  
   - Applied text preprocessing techniques, including tokenization, stemming, lemmatization, and stopword removal.  
   - Used regular expressions to remove punctuation, numbers, and special characters.  

2. **Feature Engineering**  
   - Converted text data into numerical representations using TF-IDF and Count Vectorization.  
   - Encoded labels for supervised learning.  

3. **Machine Learning Models**  
   - Trained and tested multiple classifiers:  
     - Logistic Regression  
     - Random Forest  
     - Naïve Bayes (Gaussian and Multinomial)  
     - K-Nearest Neighbors  
   - Evaluated models using accuracy, precision, recall, and F1-score.  
   - Used confusion matrices to assess misclassification patterns.  

4. **Hyperparameter Tuning**  
   - Employed techniques such as RandomizedSearchCV to optimize model performance.  

5. **Performance Evaluation**  
   - Compared different models to determine the most effective approach for sentiment classification.  
   - Visualized evaluation metrics using matplotlib and seaborn.  
