# Salary Prediction for Data Jobs in the US


This project aims to analyse and predict salaries for various data-related jobs in the United States using machine learning techniques.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Data Collection and Preprocessing](#data-collection-and-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Project Structure](#project-structure)
- [Feature Engineering](#feature-engineering)
- [Model Building and Evaluation](#model-building-and-evaluation)
- [Model Deployment](#model-deployment)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction
This project focuses on predicting salaries for data-related jobs based on several features such as job title, company, location, and other related factors. The goal is to provide insights and accurate salary predictions to help job seekers and employers.

## Dataset
The dataset used in this project includes information about job titles, salary estimates, company ratings, company names, locations, company sizes, founding years, types of ownership, industries, sectors, and revenues. The data is sourced from Glassdoor, comprising 5892 rows and 11 columns.

## Technologies Used
The following technologies and libraries were used in this project:
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Jupyter Notebook

## Data Collection and Preprocessing
Steps involved:
- Imported and cleaned the dataset.
- Handled missing values.
- Encoded categorical variables.

## Exploratory Data Analysis
Several visualizations and statistical analyses were performed to understand the distribution of salaries and the relationship between different features and salaries. Key trends and patterns were uncovered using Matplotlib.

## Project Structure

The project is organized into the following directories and files:

- `datasets/`: Contains the dataset used for analysis.
  - `df.csv`: The main dataset with job and salary data.
- `notebooks/`: Contains the Jupyter Notebook used for the analysis.
  - `Salary_Prediction_Data_Jobs_US.ipynb`: The main Jupyter Notebook that performs the analysis and generates the report.
- `requirements.txt`: Lists the Python libraries and dependencies needed to run the project.

## Feature Engineering
- Created new features.
- Applied one-hot encoding.
- Performed scaling.

## Model Building and Evaluation
Multiple machine learning models were used to predict salaries, including:
- Linear Regression
- Decision Trees
- Random Forest
- Gradient Boosting

Models were evaluated using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) metrics. Hyperparameter tuning and cross-validation were applied to select the best-performing model.

## Model Deployment
Fine-tuned the best model and developed an interface for salary prediction.

## Results
The performance of each model was evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

## Conclusion
The project demonstrates how machine learning can be applied to predict salaries for data jobs. The best-performing model provides accurate predictions, which can be valuable for job seekers and employers alike.
