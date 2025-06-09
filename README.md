# 📩 SMS Spam Classifier

A simple machine learning-based SMS spam detection system built using Python and scikit-learn. It classifies text messages as **Spam** or **Not Spam (Ham)** using a **Multinomial Naive Bayes** model trained on real-world SMS data.

---

## Features
- Preprocesses SMS data and transforms it into feature vectors using `CountVectorizer`.
- Trains and evaluates a **Naive Bayes classifier**.
- Saves the model using `joblib` for reuse.
- Classifies user-input messages in real-time via terminal.

---

## Dataset
- Uses the **SMS Spam Collection Dataset**.
- Loaded from a CSV file `spam.csv` with `latin-1` encoding.
- Labels: `"spam"` or `"ham"`.

---

## How to Run

1. Ensure `spam.csv` is in your working directory.
2. Install required libraries:
   ```bash
   pip install pandas scikit-learn joblib
3. Run the script
   ```bash
   python sms_spam_classifier.py
4. Type a message when prompted to see if it's spam or not.

---

##Tech Stack

1. Python
2. scikit-learn
3. pandas
4. joblib

---

##Model Used

Multinomial Naive Bayes: Well-suited for text classification tasks involving word counts or frequencies.

---

##Evaluation

Model performance is evaluated using:
1. Accuracy
2. Precision, Recall, F1-Score via classification_report

---

##Example

<pre> ```python Enter a message to classify (or type 'exit' to quit): Congratulations! You've won a free vacation. The message: 'Congratulations! You've won a free vacation.' is classified as: Spam ``` </pre>

---

##Notes

This is a basic implementation and can be enhanced further using techniques like **TF-IDF, stopword removal, lemmatization, or advanced models**.




