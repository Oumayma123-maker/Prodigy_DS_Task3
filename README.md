# Prodigy Infotech Internship : Task 3 :

🌳 Decision Tree Model for Predicting Customer Deposits 💼💰

📊 Project Overview :

This project builds a decision tree classifier to predict whether a customer will make a deposit based on their demographic and behavioral data. The dataset used is the Bank Marketing Dataset from the UCI Machine Learning Repository.

📂 Dataset :

The dataset includes the following features:

Demographic 🧑‍💼: Age, job, marital status, education, etc.

Behavioral 🏠💳: Housing loan, personal loan, contact details, etc.

🎯 Target Variable :

Deposit 💰: Indicates whether the customer will make a deposit (yes/no).

🧠 Knowledge Gained :

Data Preprocessing 🔄: Learned to handle missing values, encode categorical variables, and scale numerical features for machine learning.

Decision Tree 🌳: Gained insights into decision trees.

Hyperparameter Tuning 🛠️: Improved model performance using Grid Search CV to find optimal parameters like max_depth, min_samples_split, and min_samples_leaf.

Model Evaluation 📏: Applied metrics such as accuracy, precision, recall, F1-score, and confusion matrix to assess model performance.

Model Optimization 🚀: Understood the importance of hyperparameter tuning for enhancing the model's predictive power.

⚙️ Steps Involved :

1. Data Preprocessing 🧹 :

-Managed missing values.

-Encoded categorical variables using one-hot encoding

-Scaled numeric variables to normalize the data.

3. Model Building 🏗️ :

-Utilized sklearn's DecisionTreeClassifier to build the initial model.

4. Hyperparameter Tuning 🔧 :

Applied Grid Search CV to optimize:

max_depth

min_samples_split

min_samples_leaf

6. Evaluation Metrics 📊 :

-Accuracy, precision, recall, F1-score

-Confusion matrix to assess model performance

📈 Results :

Best Parameters found through Grid Search CV:

max_depth: 5

min_samples_split: 2

min_samples_leaf: 1

Model Performance:

-New Accuracy Score: 0.91

-Classification Report:

precision    recall  f1-score   support

           0       0.94      0.96      0.95      7269
           1       0.66      0.55      0.60       967

    accuracy                           0.91      8236
   macro avg       0.80      0.75      0.77      8236
weighted avg       0.91      0.91      0.91      8236

-Confusion Matrix:

[[6992  277]
[ 439  528]]


