# Diabetes Prediction System

This project aims to build a **Diabetes Prediction System** using machine learning techniques. The primary goal is to explore various models and practices to achieve the best possible accuracy for predicting diabetes based on the provided dataset.

## Dataset

The dataset used in this project is a publicly available diabetes dataset, which contains the following features:

- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skinfold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: Diabetes pedigree function
- **Age**: Age (years)
- **Outcome**: Class variable (0 if non-diabetic, 1 if diabetic)

The dataset is stored in the file [`diabetes.csv`](diabetes.csv).

## Project Objectives

1. **Data Preprocessing**:
   - Handle missing or zero values in the dataset.
   - Standardize the data for better model performance.

2. **Model Training**:
   - Train a Support Vector Machine (SVM) classifier with a linear kernel.
   - Experiment with different models and hyperparameters to improve accuracy.

3. **Model Evaluation**:
   - Evaluate the model's performance using accuracy scores on both training and test datasets.
   - Compare results across different models and practices.

4. **Prediction**:
   - Use the trained model to predict diabetes for new input data.

## Results
The project focuses on finding the best practices and models to maximize accuracy. The current implementation uses an SVM classifier, and the accuracy scores are displayed for both training and test datasets.
