# Salary Prediction Project - *(Predictive Analytics in Python)*

## Aim

Predicting the salary for a job position is crucial for a business' HR & talent function for optimizing compensation strategy and talent retention in a highly competetive labour market. The aim of this project is to build a salary prediction model for existing and future job seekers by examining an existing dataset of job postings.

The analysis is aimed at explaining every step of the process from defining the problem, discovering dataset, developing model and deploying into production. The model applies data transformation and machine learning on features such as work experience, Job Type, Majors, Industry Type, Degree and Miles from metropolis. The final aim is to predict salary for a job posting based on these available features.

## Dataset Information

The data provided to us has been split in training and testing sets. The files included are training data (train_features_df), testing data (test_features_df) and a Target set (train_salaries_df) containing dependent salary feature.

The dataset includes available features or labelled columns for analysis as follows:

**Job ID/jobId** : Given Job ID for the role

**Company ID** : Company ID for the respective Job ID advertised

**Degree** : Applicant's qualification/degree

**Major** : Degree Specialization

**Industry** : Job ID's categorized industry such as Oil, Auto, Health, Finance etc.

**Experience (Years)** : Requried Experience for the role

**Miles from Metropolis** : Distance of the job location in miles from the nearest metropolitan city

**Salary** : In x1000 dollars of the respective Job ID

## Technologies/Libraries Used

 - *Python 3*
 - *Jupyter*
 - *Pandas*
 - *Numpy*
 - *Seaborn*
 - *Matplotlib*
 - *Scikit-Learn*
 - *Scipy*

## Methodology

*1) Data Cleaning* - Hidden information is clarified and data is analyzed to provide a more structured look. Involves dropping missing or redundant features and renaming.

*2) Exploratory Data Analysis* - In-depth Data Analysis, including summary statistics (descriptive and inferential) and data visualization using regression, distribution, scatter, residual and violent plots.

*3) Machine Learning* - Baseline Model has been built and compared for Evaluation Metrics like *MSE* and *R^2* against other models like Linear Regression, Ridge Regression, Random Forest and Gradient Descent. Involves model tuning using parameters.

*4) Cross-validation and Best Model Selection* - Model with the least MSE and most R^2 was selected to be the best performing model. A summary of the evaluation scores is as follows: 

 *Linear Regression*:  385.0 ; 
 *Polynomial Regressor*:  353.0 ; 
 *Ridge Regressor*:  354.0 ; 
 *Random Forest*:  375.0 ; 
    
*5) Feature Importance* - Most important features in the Automation Pipeline are visualized.

*6) Deployment* - Final model has been built and saved into production using Pipeline. Can be applied to a dataset with unknown Salary values.

## Summary

*The application of a 2nd Order Polynomial Transformation on a Linear Regression Model gave the least MSE of 353 and most accuracy of 76%. This model can provide the most accurate results in futute when supplied with information on Experience (Years), Miles from Metropolis, Job Type, Degree and Major*


### Follow this [Link](https://github.com/rajpurohitpooja/Salary_Prediction_Portfolio/master/SalaryPredictionProject.ipynb) for codes
