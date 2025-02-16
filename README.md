# Sentiment Analysis using IMDB Dataset

## Project Description

This project focuses on sentiment analysis of IMDb movie reviews. It involves data cleaning, text processing, and using machine learning algorithms and language processing (NLP) techniques to classify sentiment as positive or negative.


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
