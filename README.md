# Cyberbullying Detection Using Machine Learning

## Project Overview

This project focuses on detecting cyberbullying comments using Natural Language Processing (NLP) and Machine Learning techniques. The model analyzes text data and classifies comments as **Toxic** or **Non-Toxic**.
The system uses **TF-IDF (Term Frequency–Inverse Document Frequency)** for text vectorization and **Logistic Regression** for classification.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

---

## Machine Learning Techniques

* TF-IDF Vectorization
* Logistic Regression
* Train-Test Split
* Confusion Matrix
* Text Classification

---

## Project Workflow

1. Load Dataset
2. Data Preprocessing
3. Text Cleaning
4. Feature Extraction using TF-IDF
5. Model Training using Logistic Regression
6. Model Evaluation
7. Real-Time Comment Prediction

---

## Dataset

Dataset used: **train.csv**

Main columns:

* **comment_text** → User comment text
* **toxic** → Target label (1 = Toxic, 0 = Non-Toxic)

---

## Model Evaluation

The model performance is evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix Visualization

---

## Example Predictions

Input:
you are useless

Output:
Toxic Comment

Input:
have a nice day

Output:
Non-Toxic Comment

---

## Project Structure

Cyberbullying_Detection
│
├── cyberbullying_detection.ipynb
├── train.csv
└── README.md

---

## Future Improvements

* Apply Deep Learning models such as LSTM or BERT
* Deploy the model as a web application
* Integrate with social media moderation systems

---

## Author

**Yasir Ahmed**
B.Tech – Artificial Intelligence and Data Science
