# AI Fresher Hiring Selection Prediction Model

## Overview

This project uses Logistic Regression to predict whether a fresher candidate is likely to be selected based on academic performance, technical assessment scores, projects, certifications, internship experience, and other candidate attributes.

The project was developed using Python and Scikit-learn.

## Dataset

Dataset Source:
YBI Foundation : https://github.com/YBIFoundation/ProjectDataSet/raw/main/Fresher%20Hiring%20Selection.csv


The dataset contains candidate information including:

* Age
* CGPA
* Aptitude Score
* Programming Score
* SQL Score
* Communication Score
* Projects
* Certifications
* Internship Months
* Hackathon Participation
* Attendance
* Selection Status

## Steps Performed

### Data Exploration

* Loaded the dataset using Pandas
* Displayed dataset records
* Displayed first 10 records
* Checked data types using `df.info()`
* Checked missing values using `df.isnull().sum()`
* Generated summary statistics using `df.describe()`
* Calculated percentage of selected candidates

### Data Preparation

* Defined input features (X)
* Defined target variable (y)
* Split the dataset into training and testing data using `train_test_split()`

### Model Building

* Imported Logistic Regression from Scikit-learn
* Created a Logistic Regression model
* Trained the model using training data

### Prediction

* Generated predictions on test data

### Evaluation

* Evaluated the model using Classification Report

## Screenshots

### Dataset Preview

<img width="900" alt="Dataset Preview" src="https://github.com/user-attachments/assets/19d23051-8a02-482d-b30d-c008d57e1164" />

### Dataset Information

<img width="900" alt="Dataset Information" src="https://github.com/user-attachments/assets/e525d229-021f-4621-943b-85867f47bc15" />

### Summary Statistics

<img width="900" alt="Summary Statistics" src="https://github.com/user-attachments/assets/951192cd-f943-4013-bddc-53a7b24a1c0a" />

### Selected Candidate Percentage

<img width="900" alt="Selected Candidate Percentage" src="https://github.com/user-attachments/assets/b6307988-5f02-4ce9-a7f7-56fa44567ee8" />

### Classification Report

<img width="900" alt="Classification Report" src="https://github.com/user-attachments/assets/d470362b-30fd-4ed6-8f25-48e88e557c80" />

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Google Colab

## Learning Outcomes

Through this project, I learned:

* Data analysis using Pandas
* Data preprocessing
* Train-Test Split
* Logistic Regression
* Classification problems
* Model evaluation using Classification Report

## Author

Yash Agarwal

B.Tech Computer Science Engineering, JIIT
