# 🍽️ Zomato Customer Review Sentiment Analysis Dashboard

## 📌 Project Overview

This project focuses on analyzing customer reviews from Zomato restaurants using Natural Language Processing (NLP) and Machine Learning techniques. The objective is to automatically classify customer reviews into Positive, Neutral, and Negative sentiments, helping businesses understand customer feedback and improve service quality.

The project combines Python, NLP, Machine Learning, Data Visualization, and Power BI to transform raw customer reviews into actionable business insights.

---

## 🎯 Business Problem

Food delivery and restaurant platforms receive thousands of customer reviews daily. Manually reading and analyzing each review is time-consuming and inefficient.

This project provides an automated solution to:

- Analyze customer sentiment
- Identify positive and negative feedback
- Monitor restaurant performance
- Support data-driven decision making
- Improve customer satisfaction

---

## 📊 Dataset Information

**Dataset Source:** Kaggle

**Dataset Name:** Zomato Cafe Reviews Dataset

### Dataset Features

| Feature | Description |
|----------|-------------|
| Name | Restaurant Name |
| Overall_Rating | Customer Rating |
| Review | Customer Review Text |
| Clean_Review | Processed Review Text |
| Review_Length | Length of Review |
| Sentiment | Positive / Neutral / Negative |

---

## 🛠️ Technologies Used

### Programming & Analysis

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Natural Language Processing

- NLTK
- Text Cleaning
- Stopword Removal
- TF-IDF Vectorization

### Machine Learning

- Logistic Regression
- Multinomial Naive Bayes
- Random Forest Classifier

### Business Intelligence

- Power BI

---

## 🔄 Project Workflow

### 1. Data Collection

- Downloaded Zomato customer review dataset from Kaggle
- Loaded dataset into Google Colab

### 2. Data Cleaning

- Removed null values
- Removed special characters
- Converted text to lowercase
- Removed stopwords
- Cleaned customer reviews

### 3. Sentiment Label Creation

Created sentiment categories using rating values:

| Rating | Sentiment |
|----------|------------|
| Rating ≥ 4 | Positive |
| Rating ≥ 3 and < 4 | Neutral |
| Rating < 3 | Negative |

### 4. Feature Engineering

Generated:

- Clean Review Text
- Review Length
- Sentiment Labels

### 5. Text Vectorization

Used TF-IDF Vectorizer to convert text data into numerical features suitable for machine learning algorithms.

### 6. Model Building

Implemented multiple machine learning algorithms:

- Logistic Regression
- Multinomial Naive Bayes
- Random Forest

### 7. Model Evaluation

Evaluated models using:

- Accuracy Score
- Classification Report
- Confusion Matrix

### 8. Power BI Dashboard Development

Designed an interactive dashboard to visualize:

- Customer Sentiment Distribution
- Rating Distribution
- Top Restaurants by Reviews
- Average Ratings
- Sentiment Breakdown
- Machine Learning Results

---

## 📈 Power BI Dashboard Features

### Executive Summary

✅ Total Reviews

✅ Positive Reviews

✅ Negative Reviews

✅ Neutral Reviews

✅ Average Rating

✅ Total Restaurants

---

## 📊 Visualizations

### Customer Sentiment Distribution

Displays proportion of:

- Positive Reviews
- Neutral Reviews
- Negative Reviews

### Review Distribution by Rating

Shows customer rating patterns.

### Top Restaurants by Review Volume

Identifies restaurants receiving the highest number of reviews.

### Top Rated Restaurants

Highlights restaurants with the best customer ratings.

### Sentiment Breakdown by Restaurant

Compares positive, neutral, and negative reviews for each restaurant.

### Review Length Distribution

Analyzes customer review behavior.

### Sentiment Across Ratings

Shows relationship between ratings and sentiment labels.

---

## 📷 Dashboard Preview

### Page 1: Executive Dashboard

- KPI Cards
- Sentiment Distribution
- Rating Analysis
- Restaurant Insights

### Page 2: Machine Learning Insights

- Confusion Matrix
- Model Performance Comparison
- Positive Word Cloud
- Negative Word Cloud

---

## 📌 Key Insights

- Majority of reviews fall under Neutral and Positive categories.
- Highly rated restaurants receive significantly more positive feedback.
- Customer ratings strongly correlate with sentiment classifications.
- Review sentiment can be effectively predicted using machine learning models.

---

## 🚀 Project Outcomes

- Automated sentiment classification system
- Business intelligence dashboard for decision-making
- NLP-based customer feedback analysis
- Machine learning model comparison and evaluation
- Interactive reporting using Power BI

---

## 💼 Skills Demonstrated

### Data Analytics

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Dashboard Development

### Machine Learning

- Text Classification
- Model Training
- Model Evaluation

### Natural Language Processing

- Text Preprocessing
- Tokenization
- TF-IDF Vectorization
- Sentiment Analysis

### Power BI

- KPI Development
- DAX Measures
- Interactive Dashboards
- Business Reporting

---

## 📂 Project Structure

```text
📦 Zomato-Customer-Review-Sentiment-Analysis
│
├── Dataset
│   └── zomato_reviews.csv
│
├── Notebook
│   └── Zomato_Sentiment_Analysis.ipynb
│
├── Dashboard
│   └── PowerBI_Dashboard.pbix
│
├── Charts
│   ├── Sentiment_Distribution.png
│   ├── Rating_Distribution.png
│   ├── Confusion_Matrix.png
│   ├── Positive_WordCloud.png
│   └── Negative_WordCloud.png
│
└── README.md
```

## 👨‍💻 Author

**Mahek Shaikh**

