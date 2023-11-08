# Loan Eligibility Prediction

## Problem Statement

Dream Housing Finance company deals in all home loans and wants to automate the loan eligibility process based on customer details provided while filling out the online application form. The goal is to identify customer segments that are eligible for loan amounts.

## Data

The dataset contains information on customer details, including Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and other attributes.

## Data Preprocessing

- Handled missing values by imputing with mode for categorical data and median for numerical data.
- Transformed categorical data into numerical data through label encoding.
- Cleaned and prepared the data for analysis.

## Exploratory Data Analysis

- Explored the distribution of key features.
- Visualized the distribution of Applicant Income and Loan Amount.
- Analyzed the relationship between different factors and loan approval status.

## Modeling

- Split the data into training and validation sets.
- Used a Logistic Regression model to predict loan eligibility.
- Evaluated the model's performance using a confusion matrix and achieved an accuracy of 83.77%.

## Interpretation

The analysis revealed that our model can predict loan eligibility with a reasonably high accuracy of 83.77%. Factors like Applicant Income, Loan Amount, and Credit History seem to have a significant impact on loan approval. Customers with a positive credit history are more likely to be eligible for loans.

## Conclusion

Automating the loan eligibility process can help the Dream Housing Finance company target specific customer segments more efficiently and make data-driven decisions. The Logistic Regression model we built provides a useful tool for this purpose.

Your contributions, suggestions, and feedback are highly appreciated!
