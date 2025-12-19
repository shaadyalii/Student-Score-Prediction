# Student-Score-Prediction
This project focuses on predicting students’ exam performance based on multiple academic, personal, and socio-economic factors. Using Linear Regression.

# Table of Content


* [Brief](#Brief)
* [DataSet](#DataSet)
* [How It Works](#How_It_Works)
* [Tools](#Tools)
* [Model_Performance](#Model_Performance)
* [Remarks](#Remarks)
* [Usage](#Usage)





# Brief

With the growing emphasis on data-driven education, predicting students’ performance can provide valuable insights for teachers, parents, and institutions.
This project builds a machine learning model to predict student exam scores based on academic, personal, and socio-economic factors.


# DataSet

The dataset used in this project is the https://www.kaggle.com/datasets/lainguyn123/student-performance-factors  This dataset provides a comprehensive overview of various factors affecting student performance in exams. It includes information on study habits, attendance, parental involvement, and other aspects influencing academic success



# How_It_Works

 • Load and clean the dataset (handle missing values, encode categorical features, scale numerical ones).
 
 • Perform Exploratory Data Analysis (EDA) and run ANOVA tests to check feature importance.
 
 • Train a Linear Regression model and evaluate it with MAE, RMSE, and R².
 
 • Save the model, scaler, and encoders using pickle.
 
 • Deploy a Streamlit web app where users input student details and get real-time predictions.


# Tools & Libraries
I. VS Code
II. Python 3.x
III. pandas, numpy
IV. matplotlib, seaborn
V. scikit-learn
VI. pickle
VII. Streamlit


# Model_Performance

The Linear Regression model was trained to predict exam scores.
Evaluation on the test set showed:

 • MAE (Mean Absolute Error): 0.879
 • RMSE (Root Mean Squared Error): 1.097
 • R² Score: 0.879
 • These results indicate that the model makes predictions with high accuracy and generalizes well on unseen data.








