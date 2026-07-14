# Linear Regression Model

An end-to-end machine learning regression project that demonstrates the complete workflow of building and evaluating a Linear Regression model. The project includes data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and visualization using Python and Scikit-learn.

---

# Project Overview

The objective of this project is to predict a continuous target variable using Linear Regression.

The project follows a complete machine learning pipeline, starting from raw data exploration and preprocessing, then training a regression model, evaluating its performance, and interpreting the results through visualizations.

---

# Dataset

Dataset used:

**Expanded_data_with_more_features**

The dataset contains multiple numerical and categorical features suitable for regression analysis.

---

# Project Workflow

## 1. Dataset Exploration

- Loaded the dataset
- Explored dataset dimensions
- Inspected data types
- Identified numerical and categorical features
- Selected the target variable

---

## 2. Data Preprocessing

Performed several preprocessing steps including:

- Missing value handling
- Duplicate detection and removal
- Outlier detection and treatment
- Categorical feature encoding
- Data cleaning

---

## 3. Exploratory Data Analysis (EDA)

Analyzed the dataset to understand feature distributions and relationships.

Visualizations include:

- Target variable distribution
- Correlation heatmap
- Pair plots
- Feature relationship analysis

---

## 4. Feature Scaling

Applied feature scaling where appropriate to improve model performance.

Techniques used:

- StandardScaler
- Min-Max Scaling (where applicable)

---

## 5. Train-Test Split

Prepared the dataset for machine learning by splitting it into training and testing sets.

---

## 6. Linear Regression Model

Built and trained a Linear Regression model using Scikit-learn.

The model was trained using the processed training dataset and later evaluated on unseen testing data.

---

## 7. Model Evaluation

The model was evaluated using several regression metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics were used to measure prediction accuracy and overall model performance.

---

## 8. Model Visualization

Visualizations were created to evaluate model behavior, including:

- Actual vs Predicted Values Scatter Plot
- Regression Plot
- Residual Analysis

These plots help assess prediction quality and identify potential modeling issues.

---

# Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Scaling
- Data Visualization
- Linear Regression
- Model Training
- Model Evaluation
- Regression Metrics
- Machine Learning Workflow

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Repository Structure

```
linear-regression-model/
│
├── Linear_Regression.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

# Results

The Linear Regression model demonstrated a reasonable ability to capture the relationship between the input features and the target variable.

Performance evaluation metrics and visualizations indicated that the model learned the general trend of the data, while leaving room for improvement through more advanced feature engineering and regression algorithms.

---

# Future Improvements

Possible enhancements include:

- Feature Selection
- Advanced Feature Engineering
- Hyperparameter Optimization
- Polynomial Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regression
- Random Forest Regression
- Gradient Boosting Models

---
# Model Performance Summary

Three separate Linear Regression models were trained to predict students' performance in **Math**, **Reading**, and **Writing** scores.

## Evaluation Results

| Target Variable | MAE | RMSE | R² Score |
|-----------------|------:|------:|------:|
| Math Score | 10.44 | 12.82 | 0.267 |
| Reading Score | 11.99 | 14.72 | -0.050 |
| Writing Score | 12.17 | 14.91 | 0.028 |

## Performance Analysis

### Math Score Model

- **MAE:** 10.44
- **RMSE:** 12.82
- **R² Score:** 0.267

The Math model achieved the best performance among the three models. The positive R² score indicates that the model was able to explain approximately **26.7%** of the variance in the target variable, making it the most effective regression model in this project.

---

### Reading Score Model

- **MAE:** 11.99
- **RMSE:** 14.72
- **R² Score:** -0.050

The Reading model showed weak predictive performance. The negative R² score suggests that the Linear Regression model performed worse than simply predicting the average reading score, indicating that the relationship between the available features and the target variable was not well captured.

---

### Writing Score Model

- **MAE:** 12.17
- **RMSE:** 14.91
- **R² Score:** 0.028

The Writing model produced only a slight improvement over the baseline prediction. The very low R² score indicates that Linear Regression was unable to explain much of the variability in writing scores.

---

## Overall Findings

- The **Math Score** model achieved the strongest predictive performance.
- The **Reading** and **Writing** models demonstrated limited predictive capability using a basic Linear Regression approach.
- The evaluation suggests that Linear Regression may not be sufficient for all target variables in this dataset.
- Additional feature engineering, feature selection, or more advanced regression algorithms may improve predictive performance.
---

# Learning Outcomes

This project demonstrates the complete workflow of developing a supervised machine learning regression model, from raw data preprocessing to model evaluation.

It provides practical experience with data preparation, exploratory analysis, regression modeling, and performance assessment using industry-standard Python libraries.
