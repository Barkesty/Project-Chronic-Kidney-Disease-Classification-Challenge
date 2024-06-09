# Project-Chronic-Kidney-Disease-Classification-Challenge
group project: Chronic Kidney Disease Classification Challenge

## Overview
This project focuses on the classification of Chronic Kidney Disease (CKD) using machine learning techniques. The primary objective is to predict, diagnose, and potentially treat CKD in its early stages based on various medical measurements.

## Abstract
In this project, we address the challenge of classifying early-stage Chronic Kidney Disease (CKD) among patients using machine learning (ML) techniques. The dataset used is derived from the Early Stage of Indian Chronic Kidney Disease (CKD) project, which comprises data on 250 early-stage CKD patients and 150 healthy controls. The classification problem involves determining the presence of CKD based on a variety of medical measurements.

To achieve this, we performed several preprocessing steps, including variable transformation, handling missing values, and outlier analysis. We transformed categorical variables and converted binary variables to numerical form. Additionally, missing values were imputed using median and mode based on the distribution characteristics of each variable.

Exploratory data analysis (EDA) and feature engineering were conducted to understand the dataset's structure and to identify potential relationships between variables. We applied a correlation matrix and variance inflation factor (VIF) analysis to detect multicollinearity issues, which were addressed using Ridge Regression, PCA, or LASSO techniques.

Various ML models were then trained and evaluated for their performance in classifying CKD. The results demonstrate the effectiveness of the applied preprocessing techniques and ML algorithms in accurately diagnosing CKD, thus contributing valuable insights into early-stage disease prediction and potentially aiding in better disease management and treatment strategies.

## Dataset

The dataset used for this project is publicly available from the UCI Machine Learning Repository. It includes 400 observations and 25 variables, with features such as age, blood pressure, specific gravity, albumin, sugar, red blood cells, pus cell, and others. These features provide critical medical measurements necessary for CKD diagnosis.

## Methodology

### Data Preprocessing
1. **Variable Transformation**:
   - Categorical variables: `sg`, `al`, `su`
   - Binary variables: `rbc`, `pc`, `pcc`, `ba`, `htn`, `dm`, `cad`, `appet`, `pe`, `ane`, `class`
   - Continuous variables: `sc`, `pot`, `hemo`, `rbcc`

2. **Handling Missing Values**:
   - Numerical variables were imputed with the median.
   - Categorical and binary variables were imputed with the mode.

3. **Feature Engineering**:
   - Transformation of categorical variables into numerical format.
   - Scaling of numerical values for consistency.

### Exploratory Data Analysis (EDA)
- Descriptive statistics and distribution plots were used to understand data characteristics.
- Correlation matrix and heatmap were employed to identify relationships between variables.
- VIF analysis helped in detecting and addressing multicollinearity.

### Model Training and Evaluation
- Several machine learning algorithms were applied, including Logistic Regression, Decision Trees, Random Forests, and Support Vector Machines (SVM).
- Model performance was evaluated using metrics such as accuracy, precision, recall, and F1-score.

## Results

The application of the aforementioned methodologies led to significant insights into the CKD classification problem. The models demonstrated high accuracy in predicting CKD, proving the effectiveness of our preprocessing techniques and the robustness of the ML algorithms used.

## Conclusion

This project successfully showcases the potential of machine learning in the early diagnosis of Chronic Kidney Disease. By leveraging a comprehensive dataset and applying rigorous data preprocessing and analysis techniques, we were able to build models that can aid in the timely and accurate diagnosis of CKD, ultimately contributing to better patient outcomes.

## Acknowledgements

We extend our gratitude to the UCI Machine Learning Repository for providing the dataset and to the STATS 3DA3 course instructors for their guidance and support throughout this project.

## References

- UCI Machine Learning Repository: [Chronic Kidney Disease Data Set](https://archive.ics.uci.edu/dataset/336/chronic+kidney+disease)


