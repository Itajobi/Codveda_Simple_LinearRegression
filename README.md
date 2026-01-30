# Simple Linear Regression Analysis
This project demonstrates a simple linear regression model built using Python and scikit-learn. 
The model predicts Total Day Charge from Total Day Minutes using telecom churn data. 
The project was completed as Level 2 – Task 1 of the Codveda Technologies Data Analytics Internship.

## Objectives
• Load and validate training and testing datasets  
• Build a simple linear regression model  
• Interpret model coefficients (intercept and slope)  
• Evaluate model performance using R-square and MSE  

## Tools & Technologies
• Python – Programming language  
• pandas – Data loading and validation  
• scikit-learn – Linear regression modeling and evaluation  

## Implementation Features
• Data Loading: Imported training (churn-bigml-80.csv) and testing (churn-bigml-20.csv) datasets  
• Data Validation: Checked for missing values and duplicates → none found  
• Feature Selection:  
   - Independent variable: Total day minutes  
   - Dependent variable: Total day charge  
• Model Training: Fitted a LinearRegression model on training data  
• Prediction: Generated predictions on test data  
• Model Coefficients:  
   - Intercept: 0.0006  
   - Slope: 0.17  

## Interpretation:
The intercept (0.0006) represents the baseline Total Day Charge when Total Day Minutes is 0.
The slope (0.17) means that for every 1-minute increase in Total Day Minutes, the Total Day Charge increases by approximately 0.17 units.
 
 ## Evaluation Metrics:  
   - Mean Squared Error (MSE): 8.24e-06  
   - R-square Score: 0.9999999  


## Key Insights
• The model shows a near-perfect linear relationship between minutes and charges  
• Very low error and high R-square confirm excellent predictive performance  
• Demonstrates simple linear regression: one independent variable predicting one dependent variable  

📌 Author  
Olanireti Itajobi  
Intern, Codveda Technologies
