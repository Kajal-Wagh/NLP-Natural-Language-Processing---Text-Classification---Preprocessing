# 🧠 NLP Emotion Classification using Machine Learning

A hands-on Natural Language Processing (NLP) project that uses Machine Learning to classify text into different emotion categories.

This project is part of my Data Science and Machine Learning learning journey, where I am practicing how to transform raw text into meaningful numerical features and build machine learning models for text classification.

---

## 📌 Project Overview

The goal of this project is to build an NLP-based emotion classification model that predicts the emotion expressed in a given text.

The project covers the complete workflow:

Text Data → NLP Preprocessing → Feature Extraction → Model Training → Evaluation → Emotion Prediction

---

## 📊 Dataset

The dataset contains approximately **16,000 text records** with corresponding emotion labels.

Example emotions include:

- Joy
- Sadness
- Anger
- Fear
- Love
- Surprise

The dataset contains two main columns:

- `text` – input text
- `emotions` – target emotion

---

## 🔎 NLP Techniques Practiced

### Text Preprocessing

- Tokenization
- Stopword Removal
- Number Removal
- Emoji Removal
- Lemmatization
- Text Cleaning

### Text Representation

- N-Grams
- Count Vectorization

### Machine Learning

- Train-Test Split
- Multinomial Naive Bayes
- Model Prediction
- Model Evaluation

---

## 🤖 Model Used

### Multinomial Naive Bayes

The processed text was converted into numerical features using `CountVectorizer`.

The Multinomial Naive Bayes classifier was then trained to classify the text into different emotion categories.

### Model Accuracy

**Test Accuracy: ~76.78%**

---

## 🧪 Example Predictions

The trained model was tested on new text examples.

Examples:

- "I am feeling very happy today!" → **Joy**
- "I did not get a holiday so I feel terrible." → **Sadness**
- "Someone is following me and I am scared!" → **Fear**

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📂 Project Structure

```text
NLP-Emotion-Classification/
│
├── NLP-Emotion-Classification.ipynb
├── data/
│   └── train.txt
├── README.md
└── requirements.txt
