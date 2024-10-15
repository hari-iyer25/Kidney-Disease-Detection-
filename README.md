# Data Cleaning and Preprocessing Project

## Project Objectives

- Increase familiarity with Pandas and SciKit Learn libraries for data cleaning.
- Work with messy datasets to apply cleaning techniques.
- Combine different datasets into a unified format.
- Understand the importance of data preprocessing for improving model performance.
- Gain experience in encoding categorical features and normalizing numerical features.

## Overview

This project involves preparing a dataset for machine learning by cleaning and preprocessing it. The dataset, collected from 400 patients, contains detailed medical information that can be used to understand and predict Chronic Kidney Disease (CKD). The goal is to create a clean version of the data that can be used effectively for machine learning. Using Pandas, various data cleaning techniques will be applied to transform these datasets into a usable form.

## Data Description

The dataset used in this project comes from a group of doctors and scientists who are researching CKD. This medical data is crucial for predicting CKD in patients, and the objective is to make this data suitable for use in machine learning algorithms by cleaning, combining, and preprocessing it.

## Steps Involved

1. **Data Loading and Exploration**

   - Load the datasets using Pandas.
   - Explore the initial state of the data, noting any issues such as missing values, inconsistencies, or errors.

2. **Data Cleaning**

   - Handle missing values using techniques such as imputation or removal of incomplete rows (using `pandas.DataFrame.dropna`).
   - Standardize inconsistent formats and fix incorrect values.

3. **Combining Datasets**

   - Merge the two provided datasets into a single dataset, handling duplicate or overlapping data.

4. **Data Preprocessing**

   - Encode categorical features using one-hot encoding (`pandas.get_dummies`).
   - Normalize numerical features to improve model performance.
