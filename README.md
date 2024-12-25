# Salary Prediction Project

This project predicts salary based on various factors such as age, gender, education level, job title, and years of experience.

## Project Overview

The objective of this project is to predict salary using different machine learning models. The dataset contains features such as `Age`, `Gender`, `Education Level`, `Job Title`, and `Years of Experience`, with the target feature being `Salary`. The following steps are applied to the dataset:

1. **Data Cleaning**: Handle null values and preprocess the data.
2. **Label Encoding**: Convert categorical variables into numerical values using Label Encoding.
3. **Data Visualization**: Use scatter plots, box plots, pie charts, and violin plots for exploratory data analysis (EDA).
4. **Model Application**: Apply machine learning models for salary prediction.
   - Linear Regression
   - Ridge Regression
   - Random Forest
   - Gradient Boosting
5. **Evaluation**: Split the data into training and testing sets and evaluate the performance of the models.

## Steps to Run the Code

### 1. Data Cleaning and Preprocessing
- Handle missing values using appropriate techniques like mean or median imputation.
- Apply Label Encoding to convert categorical columns such as `Gender`, `Education Level`, and `Job Title`.

### 2. Data Visualization
- **Scatter Plot**: To visualize the relationship between features (like `Years of Experience`) and `Salary`.
- **Box Plot**: To detect outliers and understand the distribution of the salary data.
- **Pie Chart**: To show the distribution of categorical features like `Gender`.
- **Violin Plot**: To visualize the distribution of salary based on different features.

### 3. Train-Test Split
- Split the dataset into training and testing sets (e.g., 80% train, 20% test).

### 4. Model Training and Evaluation
Apply the following models:
- **Linear Regression**: Basic regression model for salary prediction.
- **Ridge Regression**: Regularized linear model to prevent overfitting.
- **Random Forest**: An ensemble method that uses multiple decision trees.
- **Gradient Boosting**: A boosting algorithm to improve model performance.

### 5. Performance Evaluation
Evaluate the models using appropriate metrics (R² score).

## Conclusion

This project predicts salary based on features like age, gender, and experience using machine learning models. After preprocessing the data and applying various models, the results show how well each model performs. By evaluating the models, we can choose the best one for predicting salary based on the given data.
