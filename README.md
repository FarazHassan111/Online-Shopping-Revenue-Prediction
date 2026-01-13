Subject: README.md

# Online Shopping Revenue Prediction using KNN

## Overview

This project focuses on predicting whether an online shopping session will result in a purchase. By analyzing user behavior such as page visits, time spent on pages, bounce rates, and visitor type, a machine learning model is trained to identify patterns that lead to successful transactions.

The goal of this project is to demonstrate the practical application of supervised machine learning using real-world data.

---

## Problem Statement

Online businesses often struggle to identify which visitors are most likely to make a purchase. Accurately predicting purchase intent can help improve marketing strategies, user experience, and overall revenue.

This project aims to solve that problem by using a **K-Nearest Neighbors (KNN)** classifier to predict shopping revenue outcomes.

---

## Dataset Description

The dataset (`shopping.csv`) contains multiple features related to a user's interaction with an online store, including:

* Number of pages visited
* Time spent on different page types
* Bounce and exit rates
* Visitor type (new or returning)
* Weekend activity
* Revenue outcome (target variable)

Categorical values are converted into numerical form so they can be processed by the machine learning model.

---

## Methodology

1. The dataset is uploaded and read using Python’s CSV handling.
2. Data preprocessing is performed to convert all values into numerical format.
3. The data is split into training and testing sets (60% training, 40% testing).
4. A **K-Nearest Neighbors classifier (k = 1)** is trained on the dataset.
5. The model predicts whether a purchase will occur.
6. Performance is evaluated using accuracy, sensitivity, and specificity.

---

## Model Evaluation

The model’s performance is measured using:

* **Correct Predictions**
* **Incorrect Predictions**
* **Sensitivity (True Positive Rate)** – how well the model predicts actual purchases.
* **Specificity (True Negative Rate)** – how well the model predicts non-purchases.

These metrics provide a clear understanding of how effectively the model distinguishes between purchasing and non-purchasing sessions.

---

## Technologies Used

* Python
* Google Colab
* scikit-learn
* CSV file handling

---

## How to Run

1. Open the Python file in **Google Colab**
2. Run the program
3. Upload `shopping.csv` when prompted
4. View the prediction results and evaluation metrics

---

## Author

Computer Science Student
GitHub: shahabshahx


---

## Conclusion

This project demonstrates how machine learning can be used to analyze user behavior and predict business outcomes. It provides a strong foundation for understanding classification models and real-world data preprocessing.
