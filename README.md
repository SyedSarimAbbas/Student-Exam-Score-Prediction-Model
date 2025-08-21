# Student Exam Score Prediction

This project is my internship project at Eleevo Pathways, where I built a machine learning model to predict student exam scores based on different academic and lifestyle factors.

The aim is to help educators, institutions, and students gain insights into the factors that influence academic performance and to provide a tool for predicting future outcomes.

## Project Overview

Developed a machine learning pipeline to predict student exam scores.

Compared multiple models including Linear Regression, Ridge, and Lasso.

Applied GridSearchCV for hyperparameter tuning to find the best model.

Built a preprocessing pipeline for numerical and categorical data.

Exported the trained model using Joblib for future predictions.

## Dataset

The dataset contains features related to students' habits and lifestyle, such as:

Study Hours

Sleep Hours

Attendance

Motivation Level

Previous Scores

Other lifestyle/academic factors

Target Variable:

Final Exam Score

## Tech Stack

Python 

NumPy, Pandas → Data handling

Matplotlib, Seaborn → Visualization

Scikit-learn → ML models, preprocessing, pipelines

Joblib → Model persistence

## Workflow

Exploratory Data Analysis (EDA):

Visualized distributions of study habits, sleep, and motivation.

Checked correlations between features and exam score.

## Preprocessing:

Scaled numerical features using StandardScaler.

Encoded categorical features using OneHotEncoder.

## Model Training & Tuning:

Implemented Linear Regression, Ridge, and Lasso.

Used GridSearchCV for best hyperparameters.

## Evaluation:

Measured model accuracy and error metrics.

Compared Ridge vs. Lasso to choose the best model.

## Model Deployment Ready:

Saved best-fit model using Joblib.

Created a prediction function that takes user input and outputs the predicted score.

## Results

Best model achieved:

Training Accuracy: ~71%

Testing Accuracy: ~76%

Ridge and Lasso both performed similarly, final model selected based on interpretability and performance.

## Acknowledgments

This project was completed as part of my Machine Learning Internship at Eleevo Pathways.
Special thanks to my mentors and teammates for guidance and support.
