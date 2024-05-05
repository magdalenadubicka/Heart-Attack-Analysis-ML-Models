# Heart Attack Analysis & Prediction
## Introduction
This repository contains a Jupyter notebook dedicated to the analysis and prediction of heart attack occurrences using a dataset from Kaggle. The primary goal of this project is to implement and compare various machine learning models to predict heart disease in individuals based on their medical profiles.

## Dataset
The Heart Attack Analysis & Prediction Dataset includes data from 303 individuals, each represented by 14 different features related to heart health. The dataset serves as a foundation for developing machine learning models to predict the likelihood of heart attacks based on individual health data.

## Features Description
### Categorical Attributes:
- **sex**: The sex of the individual; 1 = male, 0 = female.
- **cp** (Chest Pain Type): Represents the type of chest pain experienced.
  - 0: Typical angina
  - 1: Atypical angina
  - 2: Non-anginal pain
  - 3: Asymptomatic
- **fbs** (Fasting Blood Sugar): Indicates if fasting blood sugar is above 120 mg/dl (1 = yes, 0 = no).
- **rest_ecg** (Resting Electrocardiographic Results): Resting electrocardiogram results.
  - 0: Normal
  - 1: ST-T wave abnormality
  - 2: Left ventricular hypertrophy
- **exang** (Exercise Induced Angina): Exercise induced chest pain (1 = yes, 0 = no).
- **slp** (Slope of the Peak Exercise ST Segment)
  - 0: Upsloping
  - 1: Flat
  - 2: Downsloping
- **caa** (Number of Major Vessels Colored by Fluoroscopy): Number of major vessels colored by fluoroscopy (0-3).
- **thall** (Thalassemia): Thalassemia blood disorder category.
  - 1: Fixed defect
  - 2: Normal
  - 3: Reversible defect
- **output**: Classification target indicating presence (1) or absence (0) of heart disease.
### Continuous Attributes:
- **age**: The age of the individual.
- **trtbps** (Resting Blood Pressure): Resting blood pressure in mm Hg.
- **chol** (Serum Cholesterol): Serum cholesterol in mg/dl.
- **thalachh** (Maximum Heart Rate Achieved): Maximum heart rate achieved.
- **oldpeak**: ST depression induced by exercise relative to rest.
## Models Implemented and Highest Achieved Scores: 
- **Logistic Regression**: Used as a baseline for comparison - accuracy: 84.4 %
- **Decision Tree** - accuracy: 84.3%
- **Random Forest** - accuracy: 86.5%
- **Neural Network** - accuracy: 92.2%
- **XGBoost** - accuracy: 82.4%
## Usage
This notebook is intended for educational purposes and as a practical example of applying machine learning techniques in medical diagnostics. 
