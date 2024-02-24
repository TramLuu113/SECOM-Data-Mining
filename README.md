# Data Mining Project: SECOM Dataset Analysis

## Overview
This repository contains code and resources for performing data mining analysis on the SECOM dataset. The goal of this project is to develop a predictive model to detect faulty manufacturing processes based on sensor readings collected during semiconductor manufacturing.

## Dataset
The SECOM dataset consists of sensor readings from a semiconductor manufacturing process. Each instance in the dataset represents a single manufacturing process, and the features are sensor readings collected during that process. The target variable indicates whether the process resulted in a defective product or not.

## Files
- `train_secom.csv`: CSV file containing the SECOM training dataset.
- `test_secom.csv`: CSV file containing the SECOM test dataset.
- `secom_final_coding.ipynb`: a notebook containing the Python code for data preprocessing, exploratory data analysis, modeling, and evaluation.
- `secom_presentation`: a presentation contraing the explaination to find a best predictive machine learning model.

## Finding the Best Model
The project aims to find the best model for detecting faulty manufacturing processes using the SECOM dataset. The following steps will be undertaken based on CRISP-DM Model:
1. Data Exploratory: Understanding the distribution of features, correlations, and identifying patterns in the data.
2. Data Preprocessing: Handling missing values, scaling, and feature engineering.
3. Model Selection: Trying out various machine learning algorithms: naive bayers, random forest, support vector machines, etc.
4. Hyperparameter Tuning: Optimizing the parameters of selected models using techniques like grid search or randomized search.
5. Model Evaluation: Comparing the performance of models using appropriate evaluation metrics such as accuracy, precision, recall, and F1-score.
