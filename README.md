😄 Emotion Detection from Text
This project focuses on detecting emotions (like joy, anger, sadness, etc.) from raw text using Natural Language Processing (NLP) and Machine Learning techniques. It uses a dataset of over 30,000+ labeled text entries to train a classification model that can identify the emotion behind a given sentence or message.

📌 Project Overview
Goal: Automatically classify text into emotion categories.

Tech Stack: Python, Scikit-learn, NLP, Streamlit (for deployment), SQLite (for logging).

Model: Logistic Regression (can be extended to other models like SVM, BERT, etc.)

Frontend: Streamlit app for easy interaction and testing.

Dataset Size: 30,000+ labeled entries with multiple emotion classes.

📁 Dataset
The dataset contains short text samples labeled with emotion tags.

Sample emotions: joy, sadness, anger, fear, surprise, love

Preprocessing: Lowercasing, punctuation removal, tokenization, TF-IDF vectorization

🧠 Model Training
Split data into training and testing sets

Preprocessed using Scikit-learn pipelines

Trained using Logistic Regression

Achieved high accuracy on the test set 62%

