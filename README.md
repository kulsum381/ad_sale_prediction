## 📊 Ad Sale Prediction using Logistic Regression
📝 Project Overview
This project builds a simple Logistic Regression model to predict whether a user will buy a product after clicking on a digital advertisement, based on user age and estimated salary.

The model can:

✅ Train on labeled data

✅ Predict outcomes for new users

✅ Compare actual vs predicted results

## 🎯 Objective
To classify users into:

1 → Customer will buy after seeing the ad

0 → Customer won't buy

## 📁 Dataset
Filename: DigitalAd_dataset.csv

## 📌 Features used:
Age

EstimatedSalary

🎯 Label:
Purchased → (0 or 1)

## 🧰 Technologies Used
🐍 Python

📦 pandas, numpy

🤖 scikit-learn

⚙️ StandardScaler (for feature scaling)

🔍 LogisticRegression

## 🧠 Model Summary
Preprocessing: Feature scaling using StandardScaler

Model: LogisticRegression from scikit-learn

Split: 75% training, 25% testing

Evaluation: Compared predicted vs actual values
