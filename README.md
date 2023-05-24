# Insurance Premium Prediction

## Problem Statement:

This project focuses on predicting insurance premiums using machine learning techniques. The dataset used for this project was collected from Kaggle and underwent preprocessing to prepare it for model training. The GradientBoosting Regressor algorithm was chosen and achieved an accuracy of 85% in predicting insurance premiums.

## Project Structure

The project consists of the following key steps:

**Data Collection: ** The dataset was obtained from Kaggle, which includes features such as age, BMI, number of children, smoker status, region, and insurance charges.

**Data Preprocessing:** The collected data was preprocessed to handle missing values, categorical variables, and feature scaling. Exploratory data analysis (EDA) was performed to gain insights into the data.

**Feature Engineering:** Additional features were created from the existing ones, such as age groups and BMI categories, to enhance the predictive power of the model.

**Model Training:** The GradientBoosting Regressor algorithm was selected as it has shown good performance in insurance premium prediction. The data was split into training and testing sets, and the model was trained on the training set.

**Model Evaluation:** The trained model was evaluated on the testing set to measure its performance. The evaluation metrics used include mean absolute error (MAE), mean squared error (MSE), and R-squared score.

**Deployment:** The insurance premium prediction model was deployed using Streamlit, a Python library for creating web applications. The web application allows users to input their information and obtain a predicted insurance premium.

**Project Repository**
The project repository can be found on GitHub at https://github.com/santhulak/Insurance_Premium_Prediction. It contains the following files:

- insurance.csv: This dataset used for training and testing the model.
- Insurance_Premium_Prediction.ipynb: Jupyter Notebook containing the data preprocessing, model training and evaluation process.
- app.py: Streamlit application code for deploying the model.
- requirements.txt: File listing the required Python packages for running the application.
- README.md: Detailed information about the project, including instructions for running the application.

**Deployment**
The model has been deployed using Streamlit Cloud, providing an accessible web interface for users to predict their insurance premiums. You can access the deployed application at https://santhulak-insurance-premium-prediction-app-tt6y3d.streamlit.app/

**Conclusion**
The insurance premium prediction project demonstrates the application of machine learning techniques to estimate insurance costs based on various factors. The deployed application provides a user-friendly interface for obtaining personalized premium predictions.

