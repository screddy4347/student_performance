Prediction using Machine Learning
📌 Project Overview

This project focuses on predicting student exam scores using Supervised Machine Learning (Regression) techniques. The goal is to analyze how academic, personal, and environmental factors affect a student’s final exam score and build models that can accurately predict performance.

This project is suitable for:

Academic mini / major projects

Machine Learning beginners to intermediate learners

GitHub portfolio demonstration

🎯 Problem Statement

Educational institutions want to understand which factors influence student performance. By using historical student data, we aim to build a regression model that can predict the final exam score of a student.

🧠 Machine Learning Type

Learning Type: Supervised Learning

Problem Type: Regression

Target Variable: Exam_Score

📂 Dataset Description

The dataset contains student-related attributes such as:

🔢 Numerical Features

Hours_Studied

Attendance

Sleep_Hours

Previous_Scores

Tutoring_Sessions

Physical_Activity

🏷 Categorical Features (encoded or dropped during preprocessing)

Teacher_Quality

Motivation_Level

Internet_Access

Gender

School_Type

Parental_Involvement

🎯 Target

Exam_Score (numeric value)

The dataset is clean and does not contain missing values initially.

⚙️ Technologies & Libraries Used

Python 3.x

NumPy – numerical operations

Pandas – data manipulation

Matplotlib – visualization

Scikit-learn – machine learning models and preprocessing

🔄 Project Workflow

Data Loading

Data Cleaning

Handling Categorical Variables

Feature Selection

Train–Test Split

Feature Scaling (StandardScaler)

Model Training

Model Evaluation

Prediction on New Data

🧹 Data Preprocessing

Checked for missing values using isnull()

Encoded ordinal variables (e.g., Teacher_Quality)

Dropped low-impact categorical columns to avoid complexity

Applied StandardScaler to input features

Note: The target variable Exam_Score was not scaled, as scaling the target is not required for linear regression.

🤖 Models Implemented
1️⃣ Linear Regression (Baseline Model)

Used to establish a baseline performance

Simple and interpretable

2️⃣ Support Vector Regression (SVR)

Used to capture non-linear relationships

3️⃣ Random Forest Regressor

Ensemble model

Provided the best overall performance

📊 Model Evaluation Metrics

The models were evaluated using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

The model with the highest R² score and lowest RMSE was selected as the final model.


Future Enhancements

Convert exam scores into Pass/Fail classification

Hyperparameter tuning using GridSearchCV

Deploy the model using Flask or Streamlit

Add feature importance visualization
