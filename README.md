# Diabetes Prediction - Binary Classification (Logistic Regression)

Predicts whether a patient has diabetes or not using Logistic Regression.

## Dataset
Pima Indians Diabetes Dataset — 768 samples, 8 features + 1 target  
Target: `Outcome` → 0 (No Diabetes) / 1 (Diabetes)

## Features
Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age

## What the notebook does
1. Loads and explores `diabetes.csv`
2. Checks correlation between features
3. Applies SMOTE to handle class imbalance
4. Splits data — 70% train / 30% test
5. Trains Logistic Regression model
6. Evaluates with classification report

## Results
| Set | Accuracy |
|---|---|
| Train | 74% |
| Test | 76% |

## How to run
1. Install dependencies: `pip install -r requirements.txt`
2. Open `BinaryClassification_Diabetes_Logistic_Regression.ipynb` in Jupyter
3. Run all cells

## Author
Azizullah Asad 
