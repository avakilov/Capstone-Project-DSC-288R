# 288R Capstone Project - Predicting Employee Burnout Using Machine Learning

## Dataset

**Dataset:** [Are Your Employees Burning Out?](https://www.kaggle.com/datasets/blurredmachine/are-your-employees-burning-out)

## Project Goal

The goal of this project is to predict employee burnout using supervised and unsupervised machine learning methods. Employee burnout is an important workplace issue because it affects productivity, job satisfaction, employee well-being, and retention.

Our project uses structured workplace data to predict employee burn rate as a continuous outcome and to better understand the factors most associated with burnout risk.

## Project Overview

This project combines:

- Exploratory Data Analysis
- Data cleaning and preprocessing
- Feature engineering
- Hypothesis testing
- Supervised machine learning
- Unsupervised clustering analysis

The main target variable is **Burn Rate**. Key features include mental fatigue score, resource allocation, designation level, work-from-home availability, company type, gender, and employee tenure.

## Data Pipeline

The data pipeline includes:

- Loading train and test datasets
- Converting date columns into datetime format
- Creating new features such as employee tenure
- Removing irrelevant columns such as Employee ID
- Handling missing values
- Encoding categorical variables
- Preparing the cleaned dataset for EDA and modeling

## Exploratory Data Analysis

Our EDA focuses on understanding relationships between workplace features and burnout. We use visual and statistical methods including:

- Histograms
- Bar plots
- Box plots
- Scatter plots
- Correlation analysis
- Grouped burnout comparisons

Initial findings suggest that mental fatigue score, resource allocation, designation level, and work-from-home availability are important factors related to burnout.

## Feature Engineering

Several engineered features were created to improve model performance and interpretability, including:

- Tenure
- High Burnout indicator
- Burnout Risk Factor
- Seniority Level
- Workload-Fatigue Interaction
- Fatigue Ratio
- Stress Index
- High Fatigue Indicator
- High Workload Indicator

## Modeling Approach

The supervised learning portion of the project focuses on predicting burn rate using models such as:

- Random Forest
- Gradient Boosting
- LightGBM

The unsupervised learning portion uses clustering methods such as K-Means to identify employee groups with similar stress and burnout patterns.

## Evaluation Metrics

Supervised models will be evaluated using:

- Root Mean Squared Error
- Mean Absolute Error
- R-squared

Clustering will be evaluated using interpretability and metrics such as silhouette score.

## Current Progress

So far, our team has:

- Collected and explored the dataset
- Built a preprocessing pipeline
- Created engineered features
- Performed EDA
- Identified key burnout-related patterns
- Built an initial Random Forest baseline model
- Applied K-Means clustering to analyze stress index and burn rate groups

## Team Members

- Shaily Nieves Adame
- Alex Hayslip
- Aryslan Vakilov
- Brian Nam

## References

Dataset:  
[Are Your Employees Burning Out? - Kaggle](https://www.kaggle.com/datasets/blurredmachine/are-your-employees-burning-out)

Relevant literature:
- ScienceDirect. Ensemble machine learning for burnout prediction in service operations.
- BMJ Public Health. Machine learning-based analysis of burnout among healthcare workers.