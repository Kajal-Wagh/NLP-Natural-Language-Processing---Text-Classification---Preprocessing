# NLP Emotion Classification & Text Preprocessing

## 📌 Project Overview

This project demonstrates an end-to-end **Natural Language Processing (NLP)** workflow for preprocessing text and performing **emotion classification** using Machine Learning.

The project focuses on transforming raw textual data into structured numerical features and using a **Multinomial Naive Bayes** classifier to predict emotions from text.

The project covers the complete workflow from **text cleaning and preprocessing to feature extraction, model training, evaluation, and prediction**.

---

## 🎯 Project Objective

The main objective of this project is to:

* Understand the fundamentals of Natural Language Processing
* Clean and preprocess raw text data
* Convert text into numerical features
* Perform exploratory analysis on textual data
* Build a Machine Learning classification model
* Evaluate model performance
* Predict emotions from new text

---

## 🧠 NLP Workflow

```text
Raw Text
   ↓
Data Cleaning
   ↓
Text Preprocessing
   ↓
Tokenization
   ↓
Stopword Removal
   ↓
Lemmatization
   ↓
N-Gram Analysis
   ↓
Feature Extraction
   ↓
CountVectorizer
   ↓
Train-Test Split
   ↓
Multinomial Naive Bayes
   ↓
Model Evaluation
   ↓
Emotion Prediction
```

---

## 📊 Project Highlights

### Text Preprocessing

The text data was cleaned and prepared using several NLP techniques:

* Removal of unnecessary characters
* Removal of numbers
* Removal of emojis/special characters where required
* Tokenization
* Stopword removal
* Lemmatization
* Text normalization

### Feature Engineering

The processed text was converted into numerical features using:

**CountVectorizer**

N-Gram analysis was also explored to understand combinations of words appearing in the dataset.

### Machine Learning Model

The classification model used in this project is:

**Multinomial Naive Bayes**

The model was trained using the processed textual features and evaluated on unseen test data.

---

## 📈 Model Performance

The Multinomial Naive Bayes model achieved approximately:

### **76.78% Test Accuracy**

The model was evaluated using the test dataset to understand its classification performance.

> Note: Accuracy is only one evaluation metric. Future versions of this project can include Precision, Recall, F1-score and additional model comparisons.

---

## 🛠️ Technologies & Libraries

### Programming Language

* Python

### Data Analysis

* Pandas
* NumPy

### Natural Language Processing

* NLTK

### Machine Learning

* Scikit-learn

### Data Visualization

* Matplotlib
* Seaborn

### Development Environment

* Jupyter Notebook

---

## 🔍 Key Concepts Practiced

Through this project, I practiced:

* Natural Language Processing
* Text Cleaning
* Tokenization
* Stopword Removal
* Lemmatization
* N-Grams
* Feature Extraction
* CountVectorizer
* Supervised Machine Learning
* Text Classification
* Naive Bayes
* Model Evaluation
* Emotion Prediction

---

## 📁 Repository Structure

```text
NLP-Emotion-Classification/
│
├── NLP-Text-Preprocessing-and-Emotion-Classification.ipynb
│
├── data/
│   └── dataset
│
├── images/
│   ├── emotion_distribution.png
│   ├── confusion_matrix.png
│   └── model_results.png
│
├── requirements.txt
│
└── README.md
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/Kajal-Wagh/NLP-Natural-Language-Processing---Text-Classification---Preprocessing.git
```

### 2. Navigate to the project folder

```bash
cd NLP-Natural-Language-Processing---Text-Classification---Preprocessing
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Open the Jupyter Notebook

```bash
jupyter notebook
```

Open the NLP notebook and run the cells sequentially.

---

## 📌 Sample Prediction

The trained model can be used to predict the emotion associated with new text.

Example:

```text
Input:
"I am extremely happy today!"

Output:
Predicted Emotion: Joy
```

*The example above is for illustration of the prediction workflow.*

---

## 💡 Key Learning

This project helped me understand how unstructured text can be transformed into meaningful numerical features and used for Machine Learning classification.

I gained practical experience with the complete NLP pipeline:

**Text → Preprocessing → Feature Extraction → Machine Learning → Prediction**

---

## 🔮 Future Improvements

The project can be further improved by:

* Comparing multiple classification algorithms
* Adding Logistic Regression
* Adding Linear SVM
* Comparing Accuracy, Precision, Recall and F1-score
* Creating a confusion matrix
* Performing hyperparameter tuning
* Using TF-IDF instead of only CountVectorizer
* Exploring word embeddings
* Experimenting with advanced NLP models
* Building a simple web application for real-time emotion prediction

---

## 👩‍💻 Author

**Kajal Pramod Wagh**

Aspiring Data Scientist | Python | SQL | Machine Learning | NLP | Power BI

🔗 GitHub:
https://github.com/Kajal-Wagh

🔗 LinkedIn:
https://www.linkedin.com/in/kajal-wagh-129654219/

---

## ⭐ If you found this project useful

Feel free to explore the repository and connect with me on LinkedIn to follow my Data Science learning journey.
