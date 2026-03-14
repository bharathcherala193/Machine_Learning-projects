# Student Placement Prediction using Logistic Regression
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
