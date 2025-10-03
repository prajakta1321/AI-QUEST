
# 🇮🇳 Bharat AI Quest — Level 2 Hackathon Practice

This repository contains **two end-to-end Data Science challenges** to help practice for the **Level 2 round of the Bharat AI Quest (NPCI)** hackathon.  
The test involves solving real-world Data Science or GenAI problems within 3 hours on the HackerRank platform (offline).  

This repo covers:
- 🩺 **Diabetes Prediction** — Structured data → Machine Learning Classification  
- 📰 **BBC News Classification** — Text data → NLP with TF-IDF & Naive Bayes  


It contains two end-to-end baseline solutions:
1️⃣ Diabetes Prediction (Structured Data → ML Classification)
2️⃣ BBC News Classification (Text Data → NLP + TF-IDF + Naive Bayes)

👉 Covers data loading, preprocessing, model training, and evaluation in a simple, competition-ready format.
"""

Both challenges follow a simple, competition-ready pipeline from loading data to evaluating baseline models.

---

## 🩺 1️⃣ Diabetes Prediction

Predict whether a person has diabetes using demographic and health data.

### 📊 Dataset Columns
- `gender`
- `age`
- `hypertension`
- `heart_disease`
- `smoking_history`
- `bmi`
- `HbA1c_level`
- `blood_glucose_level`
- `diabetes` (target)

### 🧠 Approach
1. Load and explore the data  
2. Encode categorical variables and scale numerical features  
3. Train-test split  
4. Baseline model: **Logistic Regression**  
5. Evaluate with accuracy and classification report  

### 🛠 Tech Stack
- Python 3  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn (optional for EDA)

---

## 📰 2️⃣ BBC News Classification

Classify BBC news articles into categories based on their title and description.

### 📊 Dataset Columns
- `title` — Article title  
- `pub_date` — Publication date  
- `guide` — Category / label (target)  
- `link` — URL  
- `description` — Article text

### 🧠 Approach
1. Load and preprocess text (drop NAs, combine title + description)  
2. Convert text to numerical features using **TF-IDF Vectorizer**  
3. Train-test split  
4. Baseline model: **Multinomial Naive Bayes**  
5. Evaluate with accuracy and classification report

### 🛠 Tech Stack
- Python 3  
- Pandas, NumPy  
- Scikit-learn  
- TfidfVectorizer for NLP

---
