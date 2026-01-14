# Spam Detection System (NLP + ML)

Classifies SMS messages as SPAM or HAM using TF-IDF and Logistic Regression.

## Dataset
SMS Spam Collection (loaded via public TSV mirror).

## Tech Stack
Python, Scikit-learn, TF-IDF, Logistic Regression

## Steps
1. Load dataset (label + text)
2. Split into train/test (stratified)
3. Build pipeline:
   - TF-IDF vectorization
   - Logistic Regression classifier
4. Evaluate using Accuracy, Confusion Matrix, Classification Report
5. Predict on custom messages

## How to Run
Run the notebook cells in order on Google Colab.

## Output
- Spam classifier with evaluation metrics
- Function to test custom SMS inputs
