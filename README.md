# SpaceX Falcon 9 Landing Prediction

## Project Overview

This project applies machine learning classification methods to predict whether the first stage of a SpaceX Falcon 9 rocket will successfully land.

The motivation is business-oriented: if a rocket's first stage can be reused, launch costs can be significantly reduced. Predicting landing success can therefore support cost estimation, risk assessment, and competitive launch pricing.

## Problem Statement

Can we predict the success of a Falcon 9 first-stage landing using historical launch data?

This is a binary classification problem:

- `1` = successful landing
- `0` = unsuccessful landing

## Dataset

The project uses SpaceX launch data from the IBM Data Science Capstone project. The dataset includes launch-related features such as:

- Flight number
- Payload mass
- Orbit type
- Launch site
- Booster version
- Reuse status
- Landing outcome
- Grid fins
- Legs
- Block number
- Booster serial number

## Methods Used

The project follows a standard machine learning workflow:

1. Load and inspect the dataset
2. Define the target variable
3. Standardize numerical features
4. Split data into training and test sets
5. Train classification models
6. Tune hyperparameters using GridSearchCV
7. Compare model performance
8. Evaluate results using accuracy and confusion matrices

## Machine Learning Models

The notebook explores several classification algorithms:

- Logistic Regression
- Support Vector Machine
- Decision Tree Classifier
- K-Nearest Neighbors

## Tools and Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Skills Demonstrated

- Machine learning classification
- Data preprocessing
- Feature scaling
- Train-test splitting
- Hyperparameter tuning
- Model comparison
- Confusion matrix analysis
- Applied business reasoning

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/MasBen71/predictive-analysis.git
