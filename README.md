# Sentiment Analysis

## 📌 Project Overview

This project focuses on performing sentiment analysis using natural language processing (NLP) techniques. The goal is to classify customer reviews as **positive**, **neutral**, or **negative** based on the text content. This was developed as part of an AICTE internship training program.

## 📂 Dataset

* **Source**: [Amazon Reviews Dataset](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)
* **Description**: This dataset contains over 500,000 food reviews from Amazon, including attributes like review text, rating, summary, and helpfulness.

> **Note:** The dataset is not included in this repository due to size constraints. Please download it from the Kaggle link above and place it in the project directory.

## 🛠️ Technologies Used

* **Language**: Python 3
* **Libraries**:

  * `pandas`
  * `numpy`
  * `matplotlib`
  * `seaborn`
  * `nltk` (for VADER sentiment analysis)
  * `sklearn` (for evaluation)
  * `wordcloud` (for visualizations)

## 📈 Project Workflow

1. **Data Preprocessing**:

   * Removed null values and unnecessary columns
   * Converted text to lowercase
   * Cleaned and tokenized review texts

2. **Sentiment Analysis**:

   * Used **VADER (Valence Aware Dictionary for sEntiment Reasoning)** for rule-based sentiment scoring
   * Classified reviews into `positive`, `neutral`, or `negative` based on compound score

3. **Evaluation**:

   * Compared sentiment predictions with ratings
   * Calculated classification metrics like precision, recall, and F1-score

## 📊 Results

* Successfully categorized thousands of reviews with reasonable accuracy using unsupervised sentiment scoring
* Highlighted relationship between actual review scores and predicted sentiment labels

## 🚀 Future Scope

* Improve model accuracy with supervised learning (e.g., Logistic Regression, SVM)
* Incorporate transformers like BERT for context-aware analysis
* Build a web application for real-time sentiment classification

## 🤝 Contributions

Open for suggestions and improvements. Feel free to fork the project and create a pull request!

## 📜 License

This project is developed for educational purposes under the AICTE Internship Program.

---
