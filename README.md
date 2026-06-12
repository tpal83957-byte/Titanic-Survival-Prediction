# Titanic Survival Prediction 🚢

## Overview
Machine learning model to predict passenger survival on the Titanic using Random Forest Classification.

## Results
- **Accuracy: 81.01%**
- **Model:** Random Forest Classifier (100 trees)
- **Dataset:** 891 passengers, 6 features


<img width="500" height="300" alt="Confusion_matrix" src="https://github.com/user-attachments/assets/d7d20f79-3e5d-4c2f-8ce4-66826955ddef" />


## Key Findings
- **Fare** was the strongest predictor of survival
- **Sex** was the second most important factor (women survived more)
- **Age** was the third most important predictor
  
  <img width="600" height="400" alt="result2" src="https://github.com/user-attachments/assets/4ff5474a-fce3-4980-976d-f41af477b0e5" />

  
  <img width="500" height="400" alt="result3" src="https://github.com/user-attachments/assets/3647b993-3558-4eee-a86c-4a41194b961f" />

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
