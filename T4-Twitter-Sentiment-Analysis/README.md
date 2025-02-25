# Sentiment Analysis on Twitter Data

## Overview
This project focuses on sentiment analysis of Twitter data, aiming to classify tweets as positive, negative, or neutral. The workflow involves text preprocessing, visualization, feature engineering, and machine learning model training to achieve meaningful insights and accurate predictions.

## Workflow

### 1. Data Collection and Preprocessing
- **Data Source**: A dataset of tweets collected Kaggle.
- **Preprocessing Steps**:
  - Removal of special characters, URLs, and hashtags.
  - Lowercasing all text for uniformity.
  - Tokenization and removal of stop words.

### 2. Sentiment Extraction
- **Library Used**: TextBlob
  - Polarity: Measures how positive or negative a tweet is (range: -1 to 1).
  - Subjectivity: Measures the degree of opinion or fact (range: 0 to 1).

### 3. Data Visualization
- **Techniques Used**:
  - Distribution plots for polarity and subjectivity scores to understand the sentiment spread.
  - Word clouds to highlight frequently occurring words in tweets categorized as positive, negative, or neutral.
  - Count of tweets with positive, nuetral and negative sentiment. 
- **Tools**: Matplotlib, Seaborn, WordCloud.

### 4. Feature Engineering
- **Technique**: TF-IDF Vectorization (Term Frequency-Inverse Document Frequency)
  - Converts text into numerical vectors while penalizing commonly used words.
- **Output**: A sparse matrix of TF-IDF scores for each tweet.

### 5. Model Training and Evaluation
- **Algorithm**: Logistic Regression
- **Evaluation Metrics**:
  - **Accuracy**: 83.67%
  - **F1 Score**: 83.30%
- **Tools Used**: Scikit-learn for model implementation, training, and evaluation.

## Libraries and Tools
- **Data Handling**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, WordCloud
- **Text Analysis**: TextBlob
- **Machine Learning**: Scikit-learn
