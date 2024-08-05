# College Admission Prediction using Linear Regression

## Overview

This project aims to predict college admission chances based on various features using a Linear Regression model. By analyzing historical data, the model helps in understanding the factors that influence admission decisions and provides insights into the admission process.

## Features

- **Data Preprocessing:** Handling missing values, feature scaling, and encoding categorical variables.
- **Exploratory Data Analysis (EDA):** Visualizing data to uncover patterns and relationships.
- **Model Training:** Implementing and training a Linear Regression model.
- **Model Evaluation:** Assessing model performance using metrics like Mean Squared Error (MSE) and R-squared.
- **Prediction:** Predicting admission chances for new applicants.

## Dataset

The dataset used for this project contains information on applicants, including:

- GRE Score
- TOEFL Score
- University Rating
- Statement of Purpose (SOP)
- Letter of Recommendation (LOR)
- CGPA
- Research Experience
- Admission Decision (Target variable)

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Results

- The model achieved an R-squared score of 0.82 on the test set.
- Significant features influencing admission decisions were CGPA, GRE Score, and Research Experience.
