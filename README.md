# Fuel Cell Performance Prediction Project

## Project Description

This project focuses on predicting the performance of fuel cells using machine learning models. The dataset used contains various features related to fuel cell performance and multiple target variables. The target variable selected for this project is `Target5`.

## Objectives

- Load and preprocess the dataset.
- Focus on `Target5` as the output variable.
- Train and evaluate multiple machine learning models:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - Lasso Regression
  - Ridge Regression
- Evaluate models using Mean Squared Error (MSE) and R² Score.
- Save evaluation results for analysis.

## Input

The input dataset is `Fuel_cell_performance_data-Full.csv`, containing:

- **Features (F1 to F15)**: Input variables for the models.
- **Target Variables (Target1 to Target5)**: Multiple output variables, with `Target5` selected for this project.

### Example structure of the dataset:

| F1   | F2   | F3   | ... | Target1 | Target2 | Target3 | Target4 | Target5 |
|------|------|------|-----|---------|---------|---------|---------|---------|
| 52.9 | 1.33 | 49.1 | ... | 0.959   | 1.531   | 76.3    | 5.19    | 53.29   |

## Output

The output consists of:

- A trained model for each algorithm.
- Evaluation metrics for each model:
  - Mean Squared Error (MSE)
  - R² Score

### Model Performance (R² Scores)

| Model                    | R² Score |
|--------------------------|-----------|
| Linear Regression        | 0.6943    |
| Random Forest Regressor  | 0.7762    |
| Gradient Boosting        | 0.7717    |
| Lasso Regression         | 0.6973    |
| Ridge Regression         | 0.6944    |
| Decision Tree Regressor  | 0.5950    |

### Output Graph

![image](https://github.com/user-attachments/assets/b002bdb1-5514-49b1-9f87-88e13c89896c)

### Best Model
- **Random Forest Regressor** with an R² score of **0.7762**

### Worst Model
- **Decision Tree Regressor** with an R² score of **0.5950**

## Features

- Evaluate multiple regression models.
- Automatically identifies the best and worst performing models based on R² scores.
- Visualizes model performance using a bar chart.

## Key Learning Outcomes

- Data preprocessing and handling in Python using Pandas.
- Implementation of regression models using scikit-learn.
- Performance evaluation of machine learning models.

## Use Case

This project can be used as a demonstration of:

- Predictive modeling skills.
- Machine learning workflow understanding.
- Ability to preprocess and work with datasets effectively.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

