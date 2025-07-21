# 📰 Fake News Detection Using Machine Learning

## 📌 Project Overview

This project focuses on detecting fake news articles using supervised machine learning algorithms. By analyzing the textual content of news headlines and articles, the model classifies them as either **real (0)** or **fake (1)**. The goal is to support media platforms and readers in identifying misinformation.

---

## 🧠 Algorithms Used

- ✅ Logistic Regression
- ✅ Multinomial Naive Bayes
- ✅ Decision Tree Classifier
- ✅ Support Vector Machine (SVM)

Each model was trained and evaluated for performance using metrics such as **accuracy**, **precision**, **recall**, **F1-score**, and **confusion matrix**.

---

## 📊 Dataset

- **Source**: Kaggle 
- **Columns**:
  - `id`: Unique ID for each news article
  - `title`: Headline of the news article
  - `author`: Author of the article
  - `text`: Full text content
  - `label`: Target variable — `1` for fake, `0` for real

---

## 🧹 Data Preprocessing

- Handled missing values
- Combined `title`, `author`, and `text` into a single content field
- Applied NLP techniques:
  - Lowercasing
  - Removing punctuation and special characters
  - Tokenization
  - Stopword removal
  - Stemming (using NLTK's PorterStemmer)

---

## 🧪 Model Evaluation

| Model                | Accuracy | Precision | Recall | F1 Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 98%      | 0.98      | 0.98   | 0.98     |
| Naive Bayes         | 96%      | 0.96      | 0.95   | 0.95     |
| Decision Tree       | 95%      | 0.95      | 0.94   | 0.94     |
| SVM                 | 98%      | 0.98      | 0.98   | 0.98     |

> 📌 **Note**: SVM and Logistic Regression performed the best in terms of both accuracy and generalization.

---

## 📈 Visualizations

- Confusion matrices for all models
- Accuracy comparison bar chart
- ROC curves (optional)




