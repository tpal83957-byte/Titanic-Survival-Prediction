# Titanic Survival Prediction 🚢

## Overview
Machine learning model to predict passenger survival on the Titanic using Random Forest Classification.

## Results
- **Accuracy: 81.01%**
- **Model:** Random Forest Classifier (100 trees)
- **Dataset:** 891 passengers, 6 features
  <img width="500" height="350" alt="result1" src="https://github.com/user-attachments/assets/ac451a46-f5d3-40ef-8929-23a0177a6c53" />

## Key Findings
- **Fare** was the strongest predictor of survival
- **Sex** was the second most important factor (women survived more)
- **Age** was the third most important predictor
  
  <img width="618" height="432" alt="result2" src="https://github.com/user-attachments/assets/4ff5474a-fce3-4980-976d-f41af477b0e5" />
  
  <img width="567" height="455" alt="result3" src="https://github.com/user-attachments/assets/3647b993-3558-4eee-a86c-4a41194b961f" />

## Features Used
- Passenger Class (Pclass)
- Sex
- Age
- Fare
- Embarked
- Family Size (engineered feature)

## Technologies
- Python, Pandas, NumPy
- Scikit-learn (Random Forest, train_test_split)
- Matplotlib, Seaborn

## What I Learned
- Exploratory Data Analysis (EDA)
- Data cleaning and feature engineering
- Training and evaluating a classification model
- Interpreting feature importance
