# 📝 Project Overview: Yelp Review Binary Classifier

## 🎯 Objective
The goal of this project is to develop a machine learning model that classifies Yelp reviews into binary categories — either **1-star (negative)** or **5-star (positive)** — using the **text content** of the review. This binary sentiment classification helps in identifying strongly negative or positive customer experiences.

---

## 📊 Dataset Summary
The dataset used is the **Yelp Review dataset** from Kaggle, containing millions of user reviews of local businesses. Key features include:

- **`review_id`**: Unique identifier for each review  
- **`business_id`**: ID of the reviewed business  
- **`user_id`**: ID of the reviewer  
- **`date`**: Date of the review  
- **`stars`**: Star rating from 1 to 5  
- **`text`**: The written review  
- **`cool`, `useful`, `funny`**: Number of votes received from other users for the review  

> 🔎 For this binary classification task, we only use reviews rated **1-star or 5-star**.

---

## 🧠 Approach

1. **Data Filtering**:  
   - Select only reviews with 1-star and 5-star ratings.

2. **Text Preprocessing**:
   - Convert text to lowercase  
   - Remove punctuation and stopwords  
   - Tokenize the text  

3. **Feature Extraction**:
   - Use techniques like:
     - `CountVectorizer`
     - `TF-IDF Vectorizer`

4. **Modeling**:
   - Apply machine learning algorithms such as:
     - `Naive Bayes`

5. **Pipeline Implementation**:
   - Use `scikit-learn` pipelines to streamline preprocessing and modeling.

6. **Evaluation Metrics**:
   - `Accuracy`, `Precision`, `Recall`, and `F1-score`

---
