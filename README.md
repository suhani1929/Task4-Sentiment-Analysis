# Task4-Sentiment-Analysis

COMPANY : CODTECH IT SOLUTIONS

NAME : SUHANI PANCHOLI

INTERN ID : CT04DL1068

DOMAIN : DATA ANALYTICS

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH

---

# ✈️ Twitter Airline Sentiment Analysis Using NLP

## 📌  Project Overview
- This project performs sentiment analysis on tweets related to major U.S. airlines using Natural Language Processing (NLP) techniques. The goal is to classify tweets into positive, negative, or neutral sentiments and draw insights about customer perception toward different airlines.

- The analysis includes:

  - Data preprocessing and cleaning

  - Text vectorization using TF-IDF

  - Classification using Logistic Regression

  - Visualization of sentiment trends

  - Evaluation metrics and confusion matrix

- This project simulates a real-world task a data analyst might face when working with social media sentiment, helping companies improve customer service and brand reputation monitoring.

---

## 📂 Dataset
- Source: Kaggle - Twitter US Airline Sentiment

- Description: This dataset contains tweets from February 2015 about six U.S. airlines, labeled with sentiment and several metadata fields.

- Key columns:

    - text: the tweet text

    - airline_sentiment: target variable (positive, neutral, negative)

    - airline: airline mentioned

    - tweet_created: timestamp

    - retweet_count: engagement metric

---

## 🛠️ Technologies & Libraries
- Python 3

- Pandas, NumPy: Data manipulation

- NLTK, Scikit-learn: NLP & machine learning

- Matplotlib, Seaborn: Data visualization

- Jupyter Notebook

--- 

## 🔄 Workflow
### 1. Data Cleaning & Preprocessing
- Removed null values.

- Tokenized tweets using nltk.word_tokenize.

- Removed stopwords, URLs, punctuation, and user mentions.

- Converted text to lowercase and performed stemming.

### 2. Sentiment Analysis & Visualization
This step involved both exploring the sentiment labels and visualizing patterns across different airlines.

- 📊 Sentiment Distribution

    - The dataset is imbalanced with the majority of tweets being negative (62%), followed by neutral (21%) and positive (17%).

    - This shows Twitter is often used to express dissatisfaction with airline services.

- ✈️ Sentiment by Airline

    - United Airlines and US Airways received the highest number of negative tweets.

    - Virgin America had a more balanced sentiment distribution, indicating a relatively better public perception.

### 3. Feature Engineering & Model Training
- Text data was vectorized using TF-IDF.

- Used Logistic Regression for classification.

### 4. Model Evaluation
- 📉 Classification Report

    - Overall Accuracy: ~78.7%

    - Negative sentiment had the best precision and recall.
  
    - Neutral and positive sentiments were harder to classify — likely due to overlapping expressions and limited data.

- 🧱 Confusion Matrix

    - Most predictions were accurate for negative tweets.

    - Some neutral and positive tweets were misclassified, indicating model difficulty distinguishing between subtle sentiment tones.

---

## 📈 Results

### 1. Screenshot of classification metrics

  ![Image](https://github.com/user-attachments/assets/bdedec20-7636-42be-a7e8-13752289a33b)

### 2. Confusion matrix heatmap

![Image](https://github.com/user-attachments/assets/31149fa4-7b03-4ab8-b333-6ccd9f0ce997)  

### 3. Sentiment distribution bar chart

 ![Image](https://github.com/user-attachments/assets/eabd81e4-5159-437f-9174-71f59b232a89)   

### 4. Sentiment grouped by airline

 ![Image](https://github.com/user-attachments/assets/6a44f7a8-6b9f-4407-a901-ddf2e0e18429)

---

## 📊 Insights
- Negative sentiment dominated tweets for most airlines, suggesting widespread dissatisfaction.

- Airlines like United and American Airlines received a large volume of negative feedback.

- Southwest had the most balanced sentiment distribution with relatively more positive feedback.

- Tweets with higher retweet counts were more likely to be negative, indicating viral complaint behavior.

---

## 📂 Files Included
File	                               Description
Tweets.csv                        	Raw dataset used for analysis
sentiment_analysis.ipynb	          Complete Jupyter Notebook with code, output, and plots
sentiment_distribution.png	        Sentiment distribution bar chart
sentiment_by_airline.png	          Sentiment grouped by airline
confusion_matrix.png	              Confusion matrix heatmap
classification_report.png	          Screenshot of classification metrics


      
