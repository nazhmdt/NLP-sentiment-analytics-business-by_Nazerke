# 💬 Sentiment Analytics for Business

> NLP pipeline for classifying customer reviews as positive or negative — from text cleaning to a trained Logistic Regression model.

---

## 📌 Overview

A practical sentiment analysis project applied to restaurant reviews. The goal: turn unstructured customer feedback into a structured signal that a business can act on — automating satisfaction monitoring at scale.

Built as part of the **NLP** course at Astana IT University, based on Sentiment Analysis fundamentals (DataCamp, Chapters 1–4).

---

## 🔍 What's Inside

**1. Data Exploration** — class distribution, review length statistics, dataset profiling

**2. Text Cleaning & Visualization** — WordCloud generation for positive vs negative reviews to surface common themes

**3. Regex-Based Filtering** — extracting reviews that mention key business factors (e.g. "service")

**4. Feature Extraction** — Bag-of-Words via `CountVectorizer` with **unigrams + bigrams** to capture short phrases like "fast service" or "arrived late"

**5. Sentiment Prediction** — Logistic Regression trained on 80/20 split with stratified sampling

**6. Reflection** — limitations of small datasets and considerations for scaling

---

## 📊 Results

- **Model:** Logistic Regression
- **Accuracy:** 0.80 on test set
- **Insight:** Positive reviews cluster around words like *"fresh"*, *"delicious"*, *"service"*; negative reviews around *"terrible"*, *"cold"*, *"rude"*

These themes give a restaurant immediate signal on what customers value and what needs fixing.

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![WordCloud](https://img.shields.io/badge/WordCloud-4C9ED9?style=flat)

---

## 💡 Business Takeaway

Customer reviews can be partially automated for satisfaction monitoring even with simple models. A small dataset already produces 80% accuracy — scaling up the data and adding domain-specific preprocessing would make this production-viable for real review pipelines.

---

## 👤 Author

**Nazerke Zhumadilova** · [@nazhmdt](https://github.com/nazhmdt)
