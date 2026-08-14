# Titanic Survival Analysis

## Project Overview

This project analyzes the Titanic passenger dataset and builds machine learning models to predict whether a passenger survived the Titanic disaster.

The project covers the complete data science workflow, including data cleaning, exploratory data analysis, feature engineering, model building, hyperparameter tuning, and model evaluation.

---

## Objectives

- Understand the Titanic dataset.
- Clean and preprocess the data.
- Perform exploratory data analysis (EDA).
- Identify factors associated with passenger survival.
- Build multiple machine learning classification models.
- Compare model performance.
- Reduce overfitting through hyperparameter tuning.
- Save the final trained model.

---

## Dataset

The project uses the Titanic dataset from the Kaggle Titanic competition.

The main training dataset contains information about passengers, including:

- Passenger class
- Sex
- Age
- Number of siblings/spouses
- Number of parents/children
- Fare
- Port of embarkation
- Survival status

---

## Technologies Used in the project 
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---
## Project Workflow

1. Data Understanding
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Model Building
6. Model Evaluation
7. Hyperparameter Tuning
8. Feature Importance
9. Final Model Selection
10. Model Saving

---
## Structure of the project 

Titanic-Survival-Analysis/ > ── data/ > ── notebooks/ > ── models/ > ── Images/ > ── reports/ > ── src/ > ── README.md > ── requirements.txt > ── .gitignore

---
## Model Results

| Model | Training Accuracy | Testing Accuracy | Accuracy Gap |
|---|---:|---:|---:|
| Logistic Regression | 80.06% | 81.01% | -0.95% |
| Decision Tree | 97.89% | 78.21% | 19.68% |
| Tuned Decision Tree | 84.69% | 80.45% | 4.24% |
| Random Forest | 97.89% | 81.56% | 16.33% |
| Tuned Random Forest | 85.39% | 81.56% | 3.83% |

---
## Final Model

The Tuned Random Forest was selected as the final model.

- Training Accuracy: 85.39%
- Testing Accuracy: 81.56%
- Accuracy Gap: 3.83%

Hyperparameter tuning reduced overfitting while maintaining the testing performance of the model.

---
## Key Insights

- Gender showed a strong relationship with survival.
- Passenger class was associated with survival rates.
- Fare showed a highly right-skewed distribution.
- The original Decision Tree showed significant overfitting.
- Hyperparameter tuning substantially reduced over fitting.
- The Tuned Random Forest achieved the highest testing accuracy among the evaluated models.

---
## Future Improvements

- Use One-Hot Encoding for categorical variables
- Apply cross-validation
- Perform systematic hyperparameter optimization
- Test additional machine learning algorithms
- Create a web application for predictions
- Submit predictions to the Kaggle Titanic competition

---
## Author

Pavan Saroj Pal

B.Sc. Data Science Student
