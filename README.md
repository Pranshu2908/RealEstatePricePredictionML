# Real Estate Price Prediction System

## Overview
This repository contains the code for a machine learning model that predicts real estate prices based on various features such as BHK, area in sqft, bath and location. The model aims to provide accurate estimates of property prices to assist buyers, sellers, and real estate professionals in making informed decisions.

## Data Source
The dataset used for training the model consists of real estate listings with corresponding features and sale prices of bangalore city of india. It includes attributes such as:

   - Area type
   - Location (area)
   - society name
   - Property size (Area in square foot)
   - Number of bedrooms and bathrooms
   - Number of Balcony
   - Availability
   - sale prices (in lakhs)

## Dependencies
To run the code in this repository, you'll need the following dependencies:

  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib and Seaborn (for visualization)
  - Jupyter Notebook (optional, for exploring data and notebooks)
  - Flask

## Methodology
1) Data Exploration and Visualization:
    - Explore the dataset to understand the distribution of features and identify any outliers or anomalies.
    - Visualize relationships between features using scatter plots, histograms, and correlation matrices to gain insights into the data.

2) Data Preprocessing:
    - Handle missing values by imputation techniques such as mean, median, or mode.
    - Removing outliers from the data (ex: if no of bathrooms exceeds from BHK, we need to remove it or if sqft area of a 3BHK is less then 2BHK, we need to remove it).
    - Encode categorical variables using techniques like one-hot encoding or label encoding.
    - Scale numerical features to ensure uniformity and facilitate model convergence.

3) Model Selection and Training:
    - Experiment with various regression algorithms such as Linear Regression, Decision Tress, Random forest etc.
    - Train multiple models on the training dataset and evaluate their performance using cross-validation.
    - Using GridSearchCv for finding out the best model and perform hyperparameter tunning of that model.

4) Model Evaluation and Validation:
    - Assess the models' performance using evaluation metrics such as RMSE and MAE.
    - Compare the performance of different models and select the best-performing one for deployment.

5) Deployment
    - deploying the model into a website made using HTML, CSS and JS using Flask.
      
## Conclusion
In conclusion, the real estate ML project represents a powerful tool for accurately predicting property prices, empowering buyers, sellers, and real estate professionals with valuable insights. By leveraging machine learning algorithms, comprehensive data analysis, and continuous model refinement, this project aims to enhance decision-making processes within the real estate market. 


