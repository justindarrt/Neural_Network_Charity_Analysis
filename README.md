# Neural_Network_Charity_Analysis

## Overview of Project
The purpose of this project is analyze the success rate of applicants funded by charity. We utilized python using a neural network, pandas, and tensorflow. 

## Results
### Data Preprocessing
The target of the model is the column labeled "Is-Successful". The features variable columns are "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "INCOME_AMT", "SPECIAL_CONSIDERATIONS". The column EIN "Employee Identifiaction" was dropped beacuse these numbers provide no signifant value and could inadvertantly alter the machine learning model. The "NAME" coulm was dropped in the first model but used in second model, AlphabetSoupCharity_Optimzation. 

### Compiling, Training, and Evaluating the Model
The second model, AlphabetSoupCharity_Optimzation, was able to achieve an accuracy score over 75% and surpass the target goal. Four hidden layers with 100 epochs were used. Each layer used between 40-100 nodes. We converted 3 columns into data points: NAME, APPLICATION_TYPE, and CLASSIFICATION. 

##Summary
