# Final-Project-LHL
Heart Disease Prediction Project
Overview
This project aims to develop a machine learning model to predict the likelihood of heart disease. Using the ["Personal Key Indicators of Heart Disease"](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease) dataset from Kaggle, the model will analyze various biomarkers/ idicators of health and predict the presence of heart disease in this individual with a 94.9 accuracy score.

Dataset Description
The dataset includes a range of variables that can be broadly categorized into demographic data, health behaviors, and health status indicators. Key columns in the dataset are:

Demographic Information: Age, Sex, Race, etc.
Health Behaviors: Smoking, Alcohol Intake, Physical Activity, Sleep patterns.
Health Status: BMI, Mental Health, Physical Health, Stroke, Diabetic Status, etc.
Heart Disease Status: Indicates whether the individual has heart disease or not (Target Variable).
Each row in the dataset represents an individual's health profile, with the columns providing detailed information about their health and lifestyle.

Project Objective
The primary goal of this project is to build a predictive model that can accurately determine the presence of heart disease in an individual. This involves:

Performing an exploratory data analysis (EDA) to understand the correlations and patterns within the data.
Preprocessing the data for modeling, including handling missing values, encoding categorical variables, and normalizing the data.
Building and tuning a random forest calssifier model to predict the presence of heart disease.
Evaluating the model's performance using appropriate metrics and interpreting the results.

Repository Structure
data/: Folder containing the dataset file(s).
notebooks/: Jupyter notebooks with data exploration, preprocessing, modeling, and evaluation.
src/: Source code for custom functions or classes used in the project.
requirements.txt: List of Python libraries required for the project.
README.md: This file, providing an overview of the project.


Results
The model has a 94.9 accuracy score after hyper parameter turning using GridSearch CV. This implies that the model will accurately predict heart disease based on an individuals bio markers with a 5 percent margin or error.


Contact
Please email me at bilaalkhan1211@gmail.com for an inquiries regarding this project. 
