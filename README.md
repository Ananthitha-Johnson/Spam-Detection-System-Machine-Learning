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
## Results
The spam detection model achieved high performance on the SMS test dataset.

- **Accuracy:** 96.8%
- **Total Test Samples:** 1,115

### Confusion Matrix Summary
- Ham messages correctly classified: 966
- Spam messages correctly classified: 113
- False negatives (spam misclassified as ham): 36
- False positives: 0

### Classification Metrics
- Ham (Class 0):
  - Precision: 0.96
  - Recall: 1.00
  - F1-score: 0.98
- Spam (Class 1):
  - Precision: 1.00
  - Recall: 0.76
  - F1-score: 0.86

- **Macro Average F1-score:** 0.92  
- **Weighted Average F1-score:** 0.97  

The model demonstrates excellent performance in identifying legitimate messages while maintaining high precision for spam detection, making it suitable for real-world SMS filtering applications.


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
