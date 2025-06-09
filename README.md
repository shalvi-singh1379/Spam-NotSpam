# 📩 SMS Spam Classifier

A simple machine learning-based SMS spam detection system built using Python and scikit-learn. It classifies text messages as **Spam** or **Not Spam (Ham)** using a **Multinomial Naive Bayes** model trained on real-world SMS data.

---

## 🔍 Features
- Preprocesses SMS data and transforms it into feature vectors using `CountVectorizer`.
- Trains and evaluates a **Naive Bayes classifier**.
- Saves the model using `joblib` for reuse.
- Classifies user-input messages in real-time via terminal.

---

## 📂 Dataset
- Uses the **SMS Spam Collection Dataset**.
- Loaded from a CSV file `spam.csv` with `latin-1` encoding.
- Labels: `"spam"` or `"ham"`.

---

## 🚀 How to Run

1. Ensure `spam.csv` is in your working directory.
2. Install required libraries:
   ```bash
   pip install pandas scikit-learn joblib
