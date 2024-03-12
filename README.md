# Wearables Data Analysis and Predictive Modeling

## Introduction
The inspiration for this study comes after opening a debate in the comment section of a [paper](https://via.hypothes.is/https://www.frontiersin.org/journals/physiology/articles/10.3389/fphys.2018.00743/full) regarding the lack of practice into our course of Sport Analytics and and how practice consolidates arguments
This project aims to analyze sportswear-related data and build predictive models to understand the relationship between various factors and user activities. The analysis utilizes real-world datasets sourced from Kaggle and explores correlations, visualizations, and machine-learning algorithms.

### Data Sources:
1. [Apple Watch and Fitbit Data](https://www.kaggle.com/datasets/aleespinosa/apple-watch-and-fitbit-data)
2. [Sleep, Health, and Lifestyle Data](https://www.kaggle.com/datasets/henryshan/sleep-health-and-lifestyle)

## Predictive Modeling for the Wearables dataset

### Classification Task: Activity Prediction
- **Data Preprocessing:** One-hot encoding is applied to categorical variables, and the dataset is split into training and testing sets.
- **Model Selection:** XGBoost Classifier is chosen to predict user activities based on various features.
- **Model Evaluation:** The accuracy score and classification report are utilized to evaluate the model's performance.

### Regression Task: Calorie Expenditure Prediction
- **Model Selection:** XGBoost Regressor is employed to predict calorie expenditure based on user data.
- **Model Evaluation:** Mean squared error (MSE), mean absolute error (MAE), and R-squared score are used to evaluate the regression model.

### Key Findings and Insights
- Analysis of brand-specific sportwatches reveals significant differences in measurement accuracy, impacting predictive models' performance.
- Predictive models exhibit strong performance in predicting user activities and calorie expenditure

## Predictive Modeling for the Sleep Quality Dataset

- **Model Selection:** XGBoost Regressor to predict the Quality of Sleep based on the other variables available.
- **Model Evaluation:** Same metric used in the previous regression task

### Key Findings and Insights
- Analysis of sleep quality dataset reveals significant correlations between various factors and sleep disorders.
- The outstanding result can depend on how each row was labeled in the dataset, I suppose it was estimated with unsupervised learning
