📊 Ad Sale Prediction using Logistic Regression
📝 Project Overview
This project builds a simple Logistic Regression model to predict whether a user will buy a product after clicking on a digital advertisement, based on user age and estimated salary.

The model can:

Train on labeled data

Predict outcomes for new users

Compare actual vs predicted results

🎯 Objective
To classify users into:

1 → Customer will buy after seeing the ad

0 → Customer won't buy

📁 Dataset
Filename: DigitalAd_dataset.csv

Features used:

Age

EstimatedSalary

Label:

Purchased (0 or 1)

🧰 Technologies Used
Python

Pandas & NumPy

Scikit-learn

StandardScaler (for feature scaling)

LogisticRegression

🧠 Model Summary
Preprocessing: Feature scaling using StandardScaler

Model: LogisticRegression from scikit-learn

Split: 75% training, 25% testing

Evaluation: Compared predicted vs actual values

🚀 How to Run the Code
Install required packages

nginx
Copy
Edit
pip install pandas numpy scikit-learn
Place your dataset file
Ensure DigitalAd_dataset.csv is in the same folder as your Python script.

Run the script
You'll be prompted to input:

Customer age

Customer salary

The model will predict if the customer is likely to purchase.

🔢 Sample Input/Output
sql
Copy
Edit
Enter New Customer Age: 32
Enter New Customer Salary: 72000
[1]
Customer will Buy
📊 Model Prediction Results
The script also prints a side-by-side comparison of:

Predicted values

Actual test labels

Example:

css
Copy
Edit
[[0 0]
 [1 1]
 [0 1]
 ...
]
📌 Key Code Snippets
python
Copy
Edit
model = LogisticRegression(random_state = 0)
model.fit(x_train, y_train)

# Predict new customer
newCust = [[age, sal]]
result = model.predict(sc.transform(newCust))
✅ Requirements
Python 3.x

pandas

numpy

scikit-learn

You can install them with:

nginx
Copy
Edit
pip install -r requirements.txt
requirements.txt
txt
Copy
Edit
pandas
numpy
scikit-learn
✍️ Author
Kulsum S.G
📧 sgkulsum62@gmail.com
