# Infosys-Spring-Board-Stroke-Patient-Healthcare-Milestone-3

# Stroke Prediction Using Logistic Regression

# Overview

This project uses a Logistic Regression model to predict the likelihood of a stroke occurring in patients based on a set of features such as age, gender, hypertension, heart disease, and lifestyle factors. The model is trained on a dataset containing real-world patient data, and the aim is to classify whether a patient is at risk of having a stroke.

# Objective

The main objective of this project is to predict the likelihood of a stroke in patients based on multiple features. The project focuses on:

Preprocessing the data.
Training a Logistic Regression model.
Evaluating the model's performance.
Understanding the mathematical concepts behind Logistic Regression.

# Dataset

The dataset used in this project is the Healthcare Stroke Dataset, which contains several columns with information on:

Age
Gender
Hypertension
Heart Disease
Ever Married
Work Type
Residence Type
Avg Glucose Level
BMI
Smoking Status
Stroke (Target variable: 0 = No Stroke, 1 = Stroke)

# Key Steps

1. Data Preprocessing
The dataset contains some missing values and categorical features, which need to be handled before training the model:

Missing values in the bmi column are filled with the median value.
Categorical features such as gender, ever_married, work_type, Residence_type, and smoking_status are encoded using Label Encoding.

2. Splitting the Data
The data is split into training and testing sets using a 70-30 split.

3. Feature Scaling
Numerical features are scaled using StandardScaler to improve the performance of the Logistic Regression model.

4. Training the Logistic Regression Model
A Logistic Regression model is trained on the preprocessed data.

5. Evaluation
The model's performance is evaluated using:

Accuracy: The percentage of correct predictions on the test set.

6. Results and Insights
The model's accuracy is printed, and the result is interpreted.

# Libraries and Tools Used
Pandas: For data manipulation and cleaning.
Scikit-learn: For machine learning algorithms and model evaluation.
Matplotlib, Seaborn: For data visualization.
Logistic Regression: For predicting stroke occurrences.
StandardScaler: For scaling numerical features.

# Results
The Logistic Regression model achieved an accuracy of [insert accuracy]% on the test data.
The model's performance can be further improved by exploring more advanced models or hyperparameter tuning.

# Conclusion
This project demonstrates the application of Logistic Regression for predicting stroke risk based on patient features. The model is a simple yet effective tool for understanding the factors contributing to stroke occurrences and can be expanded with additional features or different machine learning algorithms for better performance.

