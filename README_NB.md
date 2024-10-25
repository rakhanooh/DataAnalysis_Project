# Diabetes Prediction Project

This project focuses on predicting diabetes presence using the Pima Indians Diabetes dataset, sourced from the National Institute of Diabetes and Digestive and Kidney Diseases. The goal is to classify individuals as diabetic or non-diabetic based on specific health measurements.

## Introduction

The objective of this project is to develop a predictive model to determine whether a patient has diabetes, utilizing the following features:
- Pregnancies: Number of pregnancies
- Glucose: Blood glucose level
- BloodPressure: Blood pressure measurement
- SkinThickness: Skin thickness
- Insulin: Insulin level
- BMI: Body mass index
- DiabetesPedigreeFunction: Diabetes likelihood based on family history
- Age: Patient's age
- Outcome: Target variable indicating diabetic (1) or non-diabetic (0) status

## Dataset

The Pima Indians Diabetes dataset includes diagnostic measurements that aid in predicting diabetes presence. It’s a binary classification problem, where the outcome indicates if a patient is diabetic or not.

## Project Structure

- Data Exploration: Analyze and clean the dataset to ensure high quality.
- Modeling: Implement Naive Bayes and Random Forest algorithms for predictive modeling.
- Evaluation: Measure model performance using metrics like accuracy and F1-score.

## Methodology

1. Data Exploration and Preprocessing: Checked for missing values, duplicate entries, and data types to ensure dataset integrity.
2. Model Selection and Implementation: 
   - Naive Bayes: Applied Gaussian Naive Bayes for continuous data, achieving high accuracy and F1-score.
   - Random Forest: Used as a comparison model to validate Naive Bayes’ performance.
3. Evaluation: Both models were evaluated based on accuracy, F1-score, and confusion matrix.

## Results

### Naive Bayes Model
The **Naive Bayes model** performed slightly better than **Random Forest**, achieving:
- Accuracy: 0.77
- F1-Score: 0.81

### Random Forest Model
The **Random Forest model** also yielded strong results:
- **Accuracy**: 0.72
- **F1-Score**: 0.78

While the Naive Bayes model demonstrated a marginally better performance, the Random Forest model remained robust, providing valuable insights and validation for the Naive Bayes model’s effectiveness on this dataset.


## Usage

1. **Load and Explore the Data**: Import the dataset, perform initial data exploration and preprocessing.
2. **Model Training and Evaluation**: Train the Naive Bayes and Random Forest models, then evaluate using accuracy and F1-score.
3. **Comparison of Results**: Review model performance to select the optimal algorithm for diabetes prediction.

### Submited By

- Lamar Waleed Fattah 
- Rakha Matuq Nooh 
  
the College of Computing, Umm Al-Qura University.
