# Predictive Modeling for Rainfall Forecasting

## Overview

This project explores the use of machine learning to predict daily rainfall. It involves a complete data science workflow, from cleaning and preprocessing a large meteorological dataset to building, evaluating, and comparing different classification models. The primary goal is to accurately predict whether it will rain on a given day based on various weather parameters.

## Features

-   *Data Preprocessing:* A robust data pipeline built with Pandas to handle missing values, perform feature scaling, and prepare the dataset for modeling.
-   *Model Implementation:* Built and evaluated multiple machine learning models, including Logistic Regression, Decision Trees, and Random Forest, using the Scikit-learn library.
-   *Performance Evaluation:* Assessed model performance using key classification metrics such as Accuracy, Precision, Recall, and F1-Score to identify the most effective model.
-   *Feature Analysis:* Conducted analysis to understand the relationships between different weather parameters and the probability of rainfall.

## Technologies Used

-   *Language:* Python
-   *Libraries:*
    -   Pandas (for data manipulation and cleaning)
    -   NumPy (for numerical operations)
    -   Scikit-learn (for machine learning models and preprocessing)
    -   Matplotlib / Seaborn (for data visualization)
-   *Development Environment:* Jupyter Notebook

## How to Run

1.  Clone the repository:
    ```bash
    git clone https://github.com/AdvaitV16/Predictive_Modeling_for_Rainfall_Forecasting.git
    
2.  Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    
3.  Open and run the Jupyter Notebook Rainfall_Analysis.ipynb to see the complete data analysis, model training, and evaluation process.

## Results

The final optimized Random Forest Classifier achieved an accuracy of 85% on the test dataset.
