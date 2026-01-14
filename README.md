# Spam Detection System using Machine Learning

This project implements a machine learning–based spam detection system that classifies SMS messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques.

---

## Problem Statement
Spam messages pose security risks such as fraud, phishing, and misinformation.  
This project aims to automatically detect spam messages using text classification techniques, helping users filter malicious or unwanted messages efficiently.

---

## Dataset
- SMS Spam Collection Dataset
- Contains labeled SMS messages categorized as `spam` or `ham`
- Text-based dataset suitable for NLP classification tasks

Target Variable:
- Message label (Spam / Ham)

---

## Methodology
1. Data loading and inspection
2. Text preprocessing:
   - Lowercasing
   - Stopword removal
   - Vectorization using TF-IDF
3. Train–test split
4. Model training:
   - Logistic Regression / Naive Bayes
5. Model evaluation using classification metrics

---

## Results
- The model effectively classifies spam and non-spam messages.
- Evaluation metrics include:
  - Accuracy
  - Precision
  - Recall
  - F1-score
- Confusion matrix analysis shows strong spam detection performance.

---

## Technologies Used
- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Natural Language Processing (NLP)

---

## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook
2. Run all cells sequentially
3. The trained model will output evaluation metrics and predictions

---

## Output
<img width="811" height="540" alt="Spam_Output" src="https://github.com/user-attachments/assets/03d1a962-8be8-4792-bd9c-f5e9e9a5f631" />

---

## Key Learning Outcomes
- Fundamentals of Natural Language Processing
- Text vectorization techniques
- Supervised classification models
- Evaluation of NLP-based ML systems

---

## Future Improvements
- Use advanced NLP models such as BERT
- Deploy as a real-time spam detection API
- Extend to email and social media message filtering

---

## Author
**Ananthitha Johnson**  
BSc (Hons) in Computer Science
