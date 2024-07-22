Name:SRIYA KOTAGIRIWAR \
Company:CODTECH IT SOLUTIONS \
ID:CT4ML3288 \
Domain:MACHINE LEARNING \
Duration:June to July 2024 \
Mentor:NEELA SANTHOSH KUMAR \

# Overview

1. Purpose:
   The project aims to develop a machine learning model to detect fraudulent credit card transactions.

2. Data:
   - Uses a dataset named 'creditcard.csv'
   - Contains 17,918 transactions with 31 features including time, amount, and 28 anonymized features (V1-V28)
   - Highly imbalanced dataset: 17,836 legitimate transactions vs. 81 fraudulent transactions

3. Data Preprocessing:
   - Checked for null values (found 1 null value in most features)
   - Created a balanced dataset by undersampling legitimate transactions to match the number of fraudulent ones

4. Exploratory Data Analysis:
   - Examined basic statistics of legitimate and fraudulent transactions
   - Compared mean values of features for both classes

5. Model Development:
   - Features: All columns except 'Class'
   - Target: 'Class' column (0 for legitimate, 1 for fraudulent)
   - Used Logistic Regression as the classification algorithm
   - Split data into training (80%) and testing (20%) sets

6. Model Training and Evaluation:
   - Trained the logistic regression model on the balanced dataset
   - Evaluated performance using accuracy score and R2 score
   - Results:
     - Training accuracy: 99.22%
     - Testing accuracy: 96.97%

7. Key Observations:
   - The model shows high accuracy on both training and test sets
   - The balanced dataset approach helped in handling the class imbalance problem

This project demonstrates a basic implementation of a credit card fraud detection system using machine learning, specifically logistic regression, with promising results on a balanced subset of the data.

![image](https://github.com/user-attachments/assets/06981277-6498-4076-b5d4-2699cc5a580a)
