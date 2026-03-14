# Machine-Learning-Projects
## Project - 1: Used Car Price Prediction using Linear Regression

This project predicts the selling price of a used car using Machine Learning.
I used Linear Regression to understand how different car features affect the resale price.

The goal of this project is to learn and apply basic Machine Learning concepts on a real-world problem.

###  Problem Statement

Used car prices depend on many factors such as:

car age

kilometers driven

fuel type

transmission type

number of previous owners

This project builds a model that estimates the price of a car based on these details.

###  Technologies Used

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

###  Project Workflow

Load and understand the dataset

Perform Exploratory Data Analysis (EDA)

Create new feature Car Age

Convert categorical data into numerical format

Split data into training and testing sets

Apply feature scaling

Train model using Linear Regression

Evaluate model performance

Predict price for new car data

###  Results & Observations

Older cars generally have lower prices.

Higher kilometers driven reduce resale value.

Linear Regression was able to predict car prices reasonably well.

Model performance was evaluated using R² Score and Mean Squared Error.




# Project - 2: Global AI Salary Intelligence System

###  Project Overview
This project builds regression models to predict AI professionals' salaries (USD) using the Global AI Job Market & Salary Trends 2025 dataset.

The main goal is to practice and implement complete regression workflow from data analysis to model evaluation.

###  Problem Statement
AI salaries depend on:

Experience level

Employment type

Company size

Job title

Remote work ratio

Years of experience

### Objective:
Build machine learning regression models to predict salary in USD and compare different regression techniques.

 Dataset
Dataset: Global AI Job Market & Salary Trends 2025

Target:

salary_usd

Important Features:

experience_level

employment_type

company_size

job_title

remote_ratio

years_experience

###  Project Steps
#### 1️ Data Understanding
Checked dataset shape

Checked missing values

Reviewed data types

Viewed statistical summary

#### 2️ Exploratory Data Analysis (EDA)
Plotted salary distribution

Found salary was right-skewed

Applied log transformation (log_salary)

Checked correlation matrix

#### 3️ Feature Engineering
One-hot encoded categorical variables

Grouped top job titles

Created interaction feature:

remote_experience = remote_ratio × years_experience

Scaled features using StandardScaler

#### 4️ Models Implemented
- Linear Regression

Baseline model.

- Polynomial Regression

Captured non-linear relationships.

- Ridge Regression

Controlled overfitting using L2 regularization.
- Lasso Regression

Performed automatic feature selection using L1 regularization.

###  Model Evaluation
Used:

RMSE

R² Score

Train vs Test comparison

Learning curves

Residual analysis

###  Observations
Salary distribution was highly skewed → log transformation improved results.

Experience level strongly impacts salary.

Company size affects salary trends.

Polynomial regression improved fit but increased overfitting.

Ridge gave better balance between bias and variance.

Lasso removed less important features automatically.

###  What I Learned
How to build a complete regression pipeline

How to handle skewed data

How to control overfitting

Difference between Linear, Ridge, and Lasso

How to analyze bias and variance

How to interpret residual plots

###  Tools Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn



# project-3:  Student Placement Prediction using Logistic Regression(mini)
##  Project Overview

This project builds a classification model to predict whether a student will get placed in a company based on academic performance and employability scores.

The main goal is to practice and implement a complete classification workflow, including data analysis, preprocessing, model implementation, and evaluation.

##  Problem Statement

Student placement in companies depends on several academic and skill-related factors such as:

SSC percentage (10th grade)

HSC percentage (12th grade)

Degree percentage

Employability test score

MBA percentage

### Objective:
Build a machine learning classification model using Logistic Regression to predict whether a student will be Placed or Not Placed.

###  Dataset

Dataset: Campus Placement Dataset

Target Variable:

status

Target Meaning:

Placed → 1

Not Placed → 0

Important Features Used:

ssc_p – Secondary school percentage

hsc_p – Higher secondary percentage

degree_p – Degree percentage

etest_p – Employability test score

mba_p – MBA percentage

##  Project Steps
### 1️ Data Understanding

Checked dataset shape

Inspected data types

Identified missing values

Viewed statistical summary

### 2️ Exploratory Data Analysis (EDA)

Visualized placement distribution

Explored relationships between academic scores and placement

Observed that students with higher academic scores tend to have better placement chances

### 3️ Data Preprocessing

Selected important numerical features

Converted target variable (Placed / Not Placed) into binary values

Handled missing values using mean imputation

### 4️ Model Implemented

- Logistic Regression (From Scratch)

Used logistic regression to model the probability of student placement.

Mathematical model:

z = w₁x₁ + w₂x₂ + w₃x₃ + w₄x₄ + w₅x₅ + b

Probability using sigmoid function:

P(y=1|x) = 1 / (1 + e⁻ᶻ)

Decision rule:

Probability ≥ 0.5 → Placed

Probability < 0.5 → Not Placed

Gradient Descent was used to optimize the model parameters.

##  Model Evaluation

Model performance was evaluated using:

Accuracy Score

Prediction comparison with actual values

Accuracy formula:

Accuracy = Correct Predictions / Total Predictions

##  Observations

Students with higher degree percentage and employability scores had a higher chance of placement.

Logistic Regression successfully modeled the probability of placement.

Academic performance plays a significant role in predicting placement outcomes.

