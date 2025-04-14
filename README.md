# Hate-Speech-Detection
This project focuses on detecting hate speech across social media platforms using advanced Machine Learning techniques. It is built as part of an academic AI/ML research project.

🔍 Objective
To identify and classify hate speech in textual data using efficient and accurate machine learning algorithms.

🛠️ Technologies & Algorithms Used
LightGBM (Gradient Boosting)

XGBoost (Extreme Gradient Boosting)

Logistic Regression

TF-IDF Vectorization

Python, Pandas, Scikit-learn

📊 Dataset
Sourced from Kaggle

~400,000 social media comments labeled as hate or non-hate

Preprocessing includes text cleaning, tokenization, and vectorization

📈 Results
The models were evaluated based on accuracy, precision, recall, and F1-score. LightGBM and XGBoost outperformed traditional classifiers in terms of both speed and accuracy.
📁 Files
HateSpeechDetection.ipynb: Google Collab notebook with data preprocessing, training, and evaluation

lgb_vectorizer.pkl, tfidf_vectorizer.pkl, logreg_vectorizer.pkl: Saved vectorizer files used for each model

📌 Future Work
Deploy as a web app or API

Experiment with deep learning models like LSTM or BERT

