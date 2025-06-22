📝 Project Overview: Yelp Review Binary Classifier
🎯 Objective
The goal of this project is to develop a machine learning model that classifies Yelp reviews into binary categories — either 1-star (negative) or 5-star (positive) — using the text content of the review. This binary sentiment classification helps in identifying strongly negative or positive customer experiences.

📊 Dataset Summary
The dataset used is the Yelp Review dataset from Kaggle, containing millions of user reviews of local businesses. Key features include:

review_id: Unique identifier for each review

business_id: ID of the reviewed business

user_id: ID of the reviewer

date: Date of the review

stars: Star rating from 1 to 5

text: The written review

cool, useful, funny: Number of votes received from other users for the review

For this binary classification task, we only use reviews rated 1-star or 5-star.

🧠 Approach
Data Filtering: Select only 1-star and 5-star reviews.

Text Preprocessing: Clean text (lowercasing, removing punctuation/stopwords, tokenization).

Feature Extraction: Convert text to numerical features using techniques like:

CountVectorizer

TF-IDF Vectorizer

Modeling: Use ML algorithms such as:

Naive Bayes

Pipeline Implementation: Combine preprocessing and modeling using scikit-learn pipelines.

Evaluation Metrics: Accuracy, Precision, Recall, F1-score
