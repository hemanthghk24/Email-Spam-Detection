# Email-Spam-Detection
Detects the spam mails in the inbox

This project demonstrates a machine learning approach to detect spam emails using various classification algorithms. The dataset used is spambase.csv which contains features extracted from emails, with the last column indicating whether the email is spam or not.


#Project Description
The goal of this project is to build and evaluate models capable of classifying emails as spam (1) or non-spam (0). The process involves:

Data Loading: Reading the spambase.csv dataset into a pandas DataFrame.
Data Preprocessing: Splitting the data into features (X) and target (y), followed by splitting into training and testing sets. Feature scaling is applied using StandardScaler.
Model Training: Implementing and training two classification models:
Logistic Regression
Random Forest Classifier
Model Evaluation: Assessing the performance of each model using metrics such as accuracy, confusion matrix, and classification report.
