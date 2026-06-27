#  Tweet Sentiment Analysis using Naive Bayes

A Machine Learning project that classifies tweets into **Positive** or **Negative** sentiments using the **Multinomial Naive Bayes** algorithm and **TF-IDF Vectorization**.

This project demonstrates the complete machine learning workflow—from text preprocessing and feature extraction to model training, evaluation, and saving the trained model for future predictions.

---

## 📌 Project Overview

This project performs the following tasks:

- Load the tweet dataset
- Clean and preprocess text data
- Remove stopwords and perform stemming
- Convert text into numerical features using TF-IDF
- Train a Multinomial Naive Bayes classifier
- Evaluate the model using accuracy and confusion matrix
- Save the trained model and vectorizer

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Joblib
- Pickle
- Jupyter Notebook

---

## 📂 Project Structure

```
Tweet-Sentiment-Analysis/
│
├── Tweet_Sentimental_Analysis_with_Naive_Bayes.ipynb
├── twitter_training.csv
├── twitter_validation.csv
├── tfidf_enc.csv
├── tfidf_model.joblib
├── model.mdl
└── README.md
```

---

## 🚀 Machine Learning Pipeline

```
Tweet Dataset
      │
      ▼
Text Preprocessing
      │
      ▼
Stopword Removal
      │
      ▼
Stemming
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Multinomial Naive Bayes
      │
      ▼
Sentiment Prediction
```

---

## 🤖 Model Used

**Algorithm:** Multinomial Naive Bayes

**Feature Extraction:** TF-IDF Vectorizer

Multinomial Naive Bayes is a probabilistic machine learning algorithm widely used for text classification tasks because of its simplicity, speed, and effectiveness.

---

## 📈 Model Evaluation

The model is evaluated using:

- Accuracy Score
- Confusion Matrix

---

## 💾 Saving the Model

The project saves the trained artifacts after model training:

- `model.mdl` – Trained Naive Bayes model
- `tfidf_model.joblib` – Saved TF-IDF Vectorizer
- `tfidf_enc.csv` – Encoded TF-IDF feature representation

---

## ▶️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Tweet-Sentiment-Analysis.git
```

### 2. Install dependencies

```bash
pip install pandas numpy nltk scikit-learn joblib
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open and run

```
Tweet_Sentimental_Analysis_Using_Naive_Bayes.ipynb
```

Run all cells in sequence.

---

## 📚 Concepts Covered

- Natural Language Processing (NLP)
- Text Cleaning
- Stopword Removal
- Stemming
- TF-IDF Vectorization
- Naive Bayes Classification
- Model Evaluation
- Model Serialization

---

## 🚀 Future Improvements

- Add Neutral sentiment classification
- Train on a larger dataset
- Compare with Logistic Regression and SVM
- Build a Streamlit or Flask web application
- Improve performance using hyperparameter tuning

---

## 👩‍💻 Author

**Prachi Sharma**

If you found this project helpful, consider giving the repository a ⭐.