# Diabetes Prediction and Analysis

This repository contains a comprehensive analysis and machine learning project on a diabetes dataset. The project demonstrates data preprocessing, exploratory data analysis, regression, classification, deep learning, and clustering techniques using various tools and libraries in Python.

## Project Overview

### 1. Data Loading and Exploration
- **Loading Data**: Reads a diabetes dataset from a CSV file.
- **Exploring Data**: Displays basic statistics and information about the dataset.

### 2. Data Preprocessing
- **Handling Missing Values**: Replaces zeros with NaN in specific columns and fills missing values with column medians.
- **Feature Scaling**: Standardizes the features to have zero mean and unit variance.

### 3. Visualization
- **Scatter Plot**: Visualizes the relationship between 'Skin Thickness' and 'Diabetes Pedigree Function'.
- **Histograms**: Shows the distribution of each feature.
- **Correlation Heatmap**: Displays correlations between features.

### 4. Regression Analysis
- **Linear Regression**: Trains and evaluates a Linear Regression model, compares it with Ridge and Lasso regressions.
- **Ridge and Lasso Regression**: Applies regularization techniques and compares their performance.

### 5. Classification Task
- **K-Nearest Neighbors (KNN)**: Classifies patients' diabetes risk and evaluates performance using accuracy, confusion matrix, and classification report.
- **KNN from Scratch**: Implements a KNN algorithm from scratch to classify data points.

### 6. Deep Learning Classification
- **Neural Network**: Builds and trains a deep learning model using TensorFlow and Keras for binary classification. Evaluates model accuracy and plots training history.

### 7. Clustering
- **K-Means Clustering**: Applies K-Means clustering to segment patients into clusters and visualizes the clusters.

## Installation

To run the code in this repository, you need to have Python and the following libraries installed:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `tensorflow` (for deep learning)
- `keras` (for deep learning)

You can install the required libraries using pip:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn tensorflow
```

## Usage

1. **Load the Dataset**: Ensure `diabetes.csv` is in the same directory as the script or provide the correct path.
2. **Run Analysis**: Execute the Python script or Jupyter notebook to perform data preprocessing, visualization, regression, classification, and clustering.
3. **View Results**: Results will be printed to the console and visualized using plots.

## Files

- `diabetes.csv`: The dataset used for analysis.

## Good Luck!
