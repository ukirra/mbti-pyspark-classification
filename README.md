# 🧠 MBTI Classification with PySpark & HDFS

This project classifies MBTI (Myers-Briggs Type Indicator) personality types based on user-generated text using **PySpark**, featuring an NLP pipeline, multiple machine learning models, and distributed storage via **HDFS (Hadoop Distributed File System)**.

---

## 📦 Dataset

Two MBTI datasets from Kaggle were used:

- [MBTI Type Dataset (Datasnaek)](https://www.kaggle.com/datasets/datasnaek/mbti-type)  
- [MBTI 500 Dataset (Zeyad Khalid)](https://www.kaggle.com/datasets/zeyadkhalid/mbti-personality-types-500-dataset)

Each dataset contains user posts along with their MBTI personality type (e.g., INFP, ENTJ).

---

## ⚙️ Tools & Technologies

- **PySpark**
  - Spark NLP for text preprocessing
  - MLlib for machine learning pipeline
- **HDFS** for distributed data storage
- **pandas**, **matplotlib** for additional analysis & visualization

---

## 📓 Notebook Contents

- Load and explore MBTI datasets from HDFS
- Text preprocessing pipeline:
  - Lowercasing  
  - Tokenizing  
  - Stopword removal  
  - Stemming  
  - TF-IDF vectorization  
- Split data into train/test sets
- Train & evaluate machine learning models:
  - Logistic Regression  
  - Naive Bayes  
  - Random Forest  
- Evaluate models using:
  - Accuracy  
  - Precision  
  - Recall  
  - Confusion Matrix (optional)
- Visualization:
  - MBTI class distribution  
  - Word frequency analysis  
  - Model performance comparison
