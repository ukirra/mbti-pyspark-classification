# 🧠 MBTI Classification with PySpark & HDFS

Proyek ini mengklasifikasikan tipe kepribadian MBTI berdasarkan teks pengguna menggunakan **PySpark** dengan pipeline NLP, berbagai model machine learning, dan penyimpanan data di **HDFS (Hadoop Distributed File System)**.

---

## 📦 Dataset

- Dataset MBTI dari Kaggle:
  - [MBTI Type Dataset (Datasnaek)](https://www.kaggle.com/datasets/datasnaek/mbti-type)
  - [MBTI 500 Dataset (Zeyad Khalid)](https://www.kaggle.com/datasets/zeyadkhalid/mbti-personality-types-500-dataset)

---

## ⚙️ Tools & Teknologi

- **PySpark** (Spark NLP & MLlib)
- **HDFS** untuk penyimpanan data terdistribusi
- `pandas`, `matplotlib` untuk analisis tambahan dan visualisasi

---

## 📓 Isi Notebook

- Load dan eksplorasi dataset MBTI dari HDFS
- Preprocessing teks: lowercase, tokenizing, stopword removal, stemming, TF-IDF
- Split dataset menjadi data train/test
- Pelatihan & evaluasi beberapa model ML:
  - Logistic Regression
  - Naive Bayes
  - Random Forest
- Evaluasi model dengan metrik:
  - Accuracy
  - Precision
  - Recall

---
