# Salary Prediction using Machine Learning

## Project Overview

This project is a Machine Learning system that predicts the **salary of Data Science professionals** based on job-related features such as experience level, job title, company location, and remote work ratio.

The goal is to demonstrate a real-world end-to-end Data Science pipeline including:

- Data collection and preprocessing  
- Feature engineering  
- Machine learning model training  
- Model evaluation  
- Data visualization  

This project is designed as a **portfolio-level ML project** suitable for GitHub and job applications.



# Problem Statement

In the modern job market, salaries vary significantly based on multiple factors such as:

- Experience level  
- Job role  
- Company location  
- Remote work ratio  
- Employment type  

 The objective is to build a regression model that can accurately predict salary (`salary_in_usd`) using these features.



# Dataset Information

The dataset used is sourced from Kaggle:

Dataset: *Data Science Job Salaries*

### Features used:

| Feature | Description |
|--------|-------------|
| experience_level | Entry, Mid, Senior, Executive |
| employment_type | Full-time, Contract, Freelance |
| job_title | Role of employee |
| company_location | Country of company |
| remote_ratio | Percentage of remote work |
| salary_in_usd | Target variable |

---

# Machine Learning Workflow

## 1. Data Collection
- Loaded CSV dataset using Pandas

## 2. Data Cleaning
- Removed missing values
- Selected relevant features

## 3. Feature Engineering
- Converted categorical variables into numeric form using Label Encoding

## 4. Train-Test Split
- 80% training data
- 20% testing data

## 5. Model Building
- Algorithm used: **Random Forest Regressor**
- Reason: Handles non-linear relationships and performs well on structured data

## 6. Model Evaluation
Evaluation metrics used:

- Mean Absolute Error (MAE)
- R² Score


# Results

- Model: Random Forest Regressor  
- Performance: Good predictive accuracy on test data  
- Key Insight: Experience level and job title are the most influential factors in salary prediction  



# Feature Importance

The model identifies which features impact salary the most.

Example:

- Experience Level → High impact  
- Job Title → High impact  
- Company Location → Medium impact  
- Remote Ratio → Low to medium impact  



# Tech Stack

- Python   
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Jupyter Notebook  



# Project Structure
