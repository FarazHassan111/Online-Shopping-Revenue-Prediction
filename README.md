Online Shopping Purchase Prediction (KNN)
Project Description

A Python machine learning project that uses the K-Nearest Neighbors algorithm to predict whether an online shopping session will result in a purchase.

Overview

Not all users who visit an online shopping website complete a purchase. This project applies a machine learning classification approach to predict customer purchasing behavior based on session data such as page visits, session duration, traffic type, visitor type, and more.

The model uses a K-Nearest Neighbors (KNN) classifier to analyze user behavior and predict whether revenue will be generated during a session.

Dataset

The dataset (shopping.csv) contains approximately 12,000 user sessions with the following information:

Page visit counts and durations

Bounce and exit rates

Month of visit

Operating system, browser, and region

Visitor type (Returning or New)

Weekend indicator

Revenue outcome (target variable)

Features Used

Each data point includes the following 17 features:

Administrative

Administrative_Duration

Informational

Informational_Duration

ProductRelated

ProductRelated_Duration

BounceRates

ExitRates

PageValues

SpecialDay

Month (0 = January, 11 = December)

OperatingSystems

Browser

Region

TrafficType

VisitorType (0 = New, 1 = Returning)

Weekend (0 = False, 1 = True)

Target Variable

1 → Revenue generated

0 → No revenue generated

Machine Learning Model

Algorithm: K-Nearest Neighbors (KNN)

k value: 1

Train/Test Split: 60% training, 40% testing

Evaluation Metrics

The model is evaluated using:

Sensitivity (True Positive Rate):
Measures how well the model predicts users who make a purchase.

Specificity (True Negative Rate):
Measures how well the model predicts users who do not make a purchase.

Project Structure
Faraz_Ai_A2/
│
├── shopping.py
├── shopping.csv
├── README.md
└── requirements.txt

Requirements

Python 3

scikit-learn

Install dependencies using:

pip install -r requirements.txt

How to Run

Ensure shopping.py and shopping.csv are in the same folder.

Open a terminal in that folder.

Run the program:

python shopping.py

Sample Output
Correct: 4088
Incorrect: 844
True Positive Rate: 40.92%
True Negative Rate: 90.68%

Author

FarazHassan
