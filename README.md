# Diabetes Prediction and Analysis

This project involves analyzing a dataset of diabetes patients and applying various machine learning approaches to predict and classify diabetes. The dataset is provided by the National Institute of Diabetes and Digestive and Kidney Diseases and includes diagnostic measurements for female patients of Pima Indian heritage.

## Project Overview

The main objectives of this project are:

1. **Data Preparation and Cleaning**: Handle missing values, standardize features, and prepare the data for modeling.
2. **Exploratory Data Analysis**: Visualize and analyze relationships between features, specifically focusing on how skin thickness relates to the Diabetes Pedigree Function.
3. **Regression Analysis**: Predict the Diabetes Pedigree Function using different regression models and compare their performance.
4. **Classification**: Classify patients into high risk or low risk categories using K-Nearest Neighbors (KNN) and a Deep Learning (DL) model.
5. **Unsupervised Learning**: Cluster patients based on their baseline medical measurements using K-Means clustering.

## Features

- **Data Preparation**: Handling missing values and standardizing features.
- **Visualization**: Plotting relationships and clusters in the dataset.
- **Regression Models**: Linear Regression, Ridge Regression, and Lasso Regression.
- **Classification Models**: K-Nearest Neighbors (KNN) and Deep Learning (DL) classification.
- **Clustering**: K-Means clustering to identify patient clusters.

## Dataset

The dataset includes the following features:

- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skin fold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: Diabetes pedigree function
- **Age**: Age (years)
- **Outcome**: Class variable (0 or 1)

## Installation

To run this project, you need to have the following libraries installed:

- numpy
- pandas
- scikit-learn
- tensorflow
- matplotlib
- seaborn

You can install these dependencies using pip:

```bash
pip install numpy pandas scikit-learn tensorflow matplotlib seaborn
```

## Usage

1. **Data Preparation**:
    - Load the dataset.
    - Replace zeros with `NaN` in specific columns and fill missing values with the median.
    - Standardize the features.

2. **Exploratory Data Analysis**:
    - Visualize relationships between features.
    - Analyze how skin thickness is related to the Diabetes Pedigree Function.

3. **Regression Analysis**:
    - Train and evaluate Linear Regression, Ridge Regression, and Lasso Regression models.
    - Plot the regression lines and compare model performance using metrics such as Mean Squared Error (MSE) and R^2 Score.

4. **Classification**:
    - Train and evaluate K-Nearest Neighbors (KNN) and Deep Learning (DL) models.
    - Print accuracy, confusion matrix, and classification report for each model.

5. **Unsupervised Learning**:
    - Apply K-Means clustering to discover patient clusters.
    - Visualize the clusters to understand the distribution of patients.

## Results

- **Regression Models**: Compare the performance of Linear Regression, Ridge Regression, and Lasso Regression based on Mean Squared Error and R^2 Score.
- **Classification Models**: Evaluate the accuracy and classification metrics for KNN and Deep Learning models.
- **Clustering**: Identify and visualize clusters of patients based on their medical measurements.

## Conclusion

This project demonstrates the application of various machine learning techniques to analyze diabetes data, predict outcomes, and classify patient risk levels. The results provide insights into the effectiveness of different models and highlight patterns in the data.
