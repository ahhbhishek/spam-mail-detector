# 📧 Spam Mail Detection using Machine Learning

## 📌 Overview

This project focuses on classifying messages as **spam** or **ham (not spam)** using Natural Language Processing (NLP) and Machine Learning techniques. It demonstrates an end-to-end pipeline from data preprocessing to model evaluation.

---

## 🚀 Features

* Text preprocessing (lowercasing, stopword removal, stemming)
* Feature extraction using **TF-IDF Vectorization**
* Model training using **Logistic Regression**
* Evaluation using accuracy, confusion matrix, and classification report
* Real-time prediction on custom input messages

---

## 📂 Dataset

The dataset contains labeled messages categorized as:

* **Spam**
* **Ham (Not Spam)**

Stored locally in:

```
content/mail_data.csv
```

---

## 🧠 Approach

1. **Data Cleaning**

   * Removed unnecessary characters
   * Converted text to lowercase

2. **Text Preprocessing**

   * Stopwords removal using NLTK
   * Stemming using PorterStemmer

3. **Feature Extraction**

   * TF-IDF Vectorizer used to convert text into numerical features

4. **Model Training**

   * Train-test split (80-20)
   * Logistic Regression model trained

5. **Evaluation**

   * Accuracy score
   * Confusion matrix
   * Classification report

---

## 📈 Results

* Model Accuracy: **95% on test data**
* Successfully classifies spam and ham messages with high precision

---

## 📸 Sample Output

Example prediction:

```
Input: "Congratulations! You have won a free lottery ticket"
Output: Spam
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/ahhbhishek/spam-mail-detector.git
cd spam-mail-detector
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Open the notebook:

```bash
jupyter notebook notebooks/spam_mail_detection.ipynb
```

Run all cells to see results and predictions.

---

## 📌 Future Improvements

* Implement Naive Bayes and compare performance
* Use advanced NLP techniques (Word Embeddings)
* Deploy as a web application using Streamlit

---



##  Acknowledgment

Dataset sourced from publicly available spam message datasets.
