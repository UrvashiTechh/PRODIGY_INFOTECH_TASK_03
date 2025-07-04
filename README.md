# PRODIGY_INFOTECH_TASK_03
TASK3
🌳 Decision Tree Classifier – Bank Marketing Dataset
<img width="1680" alt="Screenshot 2025-07-04 at 11 05 15 AM" src="https://github.com/user-attachments/assets/006185fc-6048-4055-8c15-dece159a6414" />
📌 Overview
This project is part of my data science internship tasks at Prodigy InfoTech, where I built a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit based on their demographic and behavioral data.

The dataset used is the Bank Marketing Dataset from the UCI Machine Learning Repository.

🎯 Objective
To create a supervised machine learning model that classifies whether a customer will respond positively to a marketing campaign, using:

Age, job, marital status, education

Contact type, campaign duration

Loan and housing status

And more behavioral/demographic features

📁 Dataset Description
Records: ~45,000 marketing contacts

Target variable: y → Has the client subscribed to a term deposit? (yes/no)

Features: 16 input variables (categorical + numerical)

Example columns:

age, job, marital, education

default, balance, housing, loan

contact, day, month, duration, campaign, pdays, previous, poutcome

🧰 Tools & Libraries Used
Python

Jupyter Notebook

pandas and numpy – data handling

matplotlib and seaborn – visualization

scikit-learn – model building and evaluation

🔍 Steps Performed
✅ Data Preprocessing
Handled missing values and inconsistent data

Encoded categorical variables using label encoding / one-hot encoding

Feature scaling (where needed)

📊 Exploratory Data Analysis (EDA)
Distribution of target classes

Correlation heatmap and pair plots

Categorical variable analysis (e.g., job, education, contact type)

🌲 Model Building
Trained a Decision Tree Classifier using scikit-learn

Split the data into training and test sets (e.g., 70/30)

Tuned hyperparameters (e.g., max_depth, criterion)

📈 Evaluation
Evaluated the model using:

Accuracy

Confusion matrix

Precision, Recall, F1-score

Visualized the decision tree

🧠 Key Insights
Contact type and campaign duration strongly influenced customer response

Clients contacted via cellular and with longer durations had a higher chance of subscribing

Age and education also had noticeable impacts

📎 Files Included
bank_marketing_decision_tree.ipynb – Notebook with full code

bank.csv – Dataset file

images/decision_tree.png – Visual of the trained tree (optional)

README.md – Project overview

✅ Conclusion
The Decision Tree Classifier gave meaningful predictions and offered interpretability through the tree structure. This project helped solidify my understanding of classification, decision boundaries, and working with real-world mixed-type datasets.
