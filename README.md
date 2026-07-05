# Spaceship Titanic - Kaggle Competition 

This repository contains my machine learning solution for the Kaggle **Spaceship Titanic** competition. The goal is to predict which passengers were transported to an alternate dimension during the spaceship's collision.

##  Performance & Results
* **Best Model:** Gradient Boosting Classifier
* **Validation Accuracy:** 78.55%
* **Kaggle Public Score:** **79.448%**

##  Tech Stack & Libraries
* Python 
* Scikit-Learn (Gradient Boosting, GridSearchCV, StandardScaler)
* Pandas & NumPy

## Methodology
1. **Data Preprocessing:** Handled missing values and encoded categorical variables.
2. **Feature Scaling:** Applied `StandardScaler` to numerical inputs.
3. **Model Selection:** Evaluated multiple models including Logistic Regression, Random Forest, SVM, and KNN. Gradient Boosting achieved the highest baseline score.
4. **Hyperparameter Tuning:** Fine-tuned the model using `GridSearchCV`.
