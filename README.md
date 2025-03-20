# Salary Prediction Model using Linear Regression

## Overview
This project implements a linear regression model to predict salaries based on years of experience. The model achieves an accuracy of 95.96% and can be valuable for:
- HR professionals in salary negotiations
- Job seekers in salary expectations
- Businesses in compensation planning

## Project Details
- **Objective**: Develop a predictive model for salary estimation based on experience
- **Model**: Linear Regression with Gradient Descent implementation
- **Accuracy**: 95.96%
- **Features**: Years of Experience
- **Target**: Salary

## Implementation
The project includes two implementations:
1. Using scikit-learn's LinearRegression
2. Custom implementation using Gradient Descent

### Key Components
1. Data Loading and Preprocessing
2. Exploratory Data Analysis
3. Model Development
4. Model Evaluation
5. Salary Prediction

## Features
- Data visualization using matplotlib and seaborn
- Model training and evaluation
- Salary prediction for new data
- Custom gradient descent implementation
- Comprehensive model evaluation metrics


## Model Performance
The model's accuracy is calculated using R² score:
- R² = SSR / SST
where:
- SSR (Sum of Squares Regression) = Σ(y_pred - y_mean)²
- SSE (Sum of Squares Error) = Σ(y_true - y_pred)²
- SST (Total Sum of Squares) = SSR + SSE

## Results
- Successfully implemented a Linear Regression model for salary prediction
- Achieved 95.96% accuracy on test data
- Model can be used for salary estimation based on years of experience
- Visualizations provide clear insights into the data and model performance

## Data Visualization
The project includes various visualizations:
- Experience vs Salary Distribution
- Salary Distribution by Years of Experience
- Model Fitting Process
- Actual vs Predicted Values

## Custom Implementation
The project also includes a custom implementation of Linear Regression using Gradient Descent, demonstrating:
- Parameter optimization
- Cost function minimization
- Model convergence visualization
- Custom prediction function
