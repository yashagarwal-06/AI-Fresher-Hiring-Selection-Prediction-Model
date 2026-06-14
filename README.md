# AI Fresher Hiring Selection Prediction Model

## Overview

This project uses Logistic Regression to predict whether a fresher candidate is likely to be selected during the hiring process based on academic performance, technical skills, internship experience, certifications, projects, and other candidate attributes.

In addition to model building, the project includes Exploratory Data Analysis (EDA) using histograms, boxplots, and correlation heatmaps to identify patterns and relationships within the dataset.

The project was developed using Python, Pandas, Matplotlib, Seaborn, and Scikit-learn.


## Dataset

Dataset Source:

https://github.com/YBIFoundation/ProjectDataSet/raw/main/Fresher%20Hiring%20Selection.csv

### Features Included

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
* Selection Status (Target Variable)


## Data Exploration

The following analysis was performed:

* Displayed dataset records
* Displayed first 10 observations
* Checked dataset dimensions
* Examined data types using `df.info()`
* Checked for missing values
* Generated summary statistics using `df.describe()`
* Calculated percentage of selected candidates


## Exploratory Data Analysis (EDA)

### Histograms

Distribution analysis for:

* CGPA
* Programming Score
* SQL Score

### Boxplots

Comparison between selected and non-selected candidates for:

* CGPA
* Programming Score
* SQL Score

### Correlation Heatmap

Generated a correlation matrix heatmap to identify relationships between features and candidate selection.


## Data Preparation

### Feature Variables (X)

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

### Target Variable (Y)

* Selected

### Train-Test Split

Dataset was divided into training and testing sets using Scikit-learn's `train_test_split()` function.

## Model Building

### Machine Learning Algorithm

* Logistic Regression

### Training

The Logistic Regression model was trained using the training dataset with:

* max_iter = 1000


## Prediction

Generated predictions using the testing dataset.


## Model Evaluation

The model was evaluated using a Classification Report containing:

* Precision
* Recall
* F1-Score
* Accuracy

## Project Screenshots


### Dataset Preview

<img width="1154" height="300" alt="Dataset Preview" src="https://github.com/user-attachments/assets/9aef0876-7bd4-4337-820e-fec02490f945" />

### Dataset Information

<img width="360" height="306" alt="Dataset Information" src="https://github.com/user-attachments/assets/0b69f666-5466-4fbc-b711-8587b0dbdbe3" />

### Summary Statistics

<img width="1264" height="258" alt="Summary Statistics" src="https://github.com/user-attachments/assets/822fe6d1-0f27-4fc2-ab37-4e80f834c996" />

### Selected Candidate Percentage

<img width="518" height="78" alt="Selected Candidate Percentage" src="https://github.com/user-attachments/assets/dcf6199e-fced-44d4-a8a1-217900c6b5e8" />

### CGPA Distribution Histogram

<img width="377" height="366" alt="CGPA Histogram" src="https://github.com/user-attachments/assets/56f15e3f-0ffb-4bcc-bc28-ea3bc381faff" />

### Programming Score Distribution Histogram

<img width="377" height="366" alt="Programming Score Histogram" src="https://github.com/user-attachments/assets/957170af-65ff-40e0-9c36-0aa14d79dc7c" />

### SQL Score Distribution Histogram

<img width="374" height="367" alt="SQL Score Histogram" src="https://github.com/user-attachments/assets/341b60d8-a8e5-402a-9d09-8517a55b4bc8" />

### CGPA vs Selection Boxplot

<img width="375" height="364" alt="CGPA Boxplot" src="https://github.com/user-attachments/assets/5f5fdfae-6df9-4cd3-ae72-16fd2d76d83a" />

### Programming Score vs Selection Boxplot

<img width="379" height="364" alt="Programming Score Boxplot" src="https://github.com/user-attachments/assets/b9b35c16-0d2a-4723-aa63-df078bb19fb6" />

### SQL Score vs Selection Boxplot

<img width="378" height="367" alt="SQL Score Boxplot" src="https://github.com/user-attachments/assets/492e2d98-773c-48ef-904f-c8280c0304d1" />

### Correlation Heatmap

<img width="787" height="612" alt="Correlation Heatmap" src="https://github.com/user-attachments/assets/621dd9ce-afa3-48af-bb7f-732b74e53309" />

### Classification Report

<img width="372" height="122" alt="Classification Report" src="https://github.com/user-attachments/assets/e7ac6a0e-dc44-401b-8ed3-9b225f6e582b" />


## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab


## Learning Outcomes

Through this project, I learned:

* Data Exploration and Analysis
* Exploratory Data Analysis (EDA)
* Data Visualization using Matplotlib and Seaborn
* Correlation Analysis
* Feature Selection
* Train-Test Split
* Logistic Regression
* Classification Problems
* Model Evaluation using Classification Report


## Author

Yash Agarwal

B.Tech Computer Science Engineering, JIIT
