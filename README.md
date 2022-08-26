# Neural_Network_Charity_Analysis

## Overview of Project
The purpose of this project is analyzing the success rate of applicants funded by charity. We utilized python using a neural network, pandas, and tensorflow.

## Results
### Data Preprocessing
The target of the model is the column labeled "Is-Successful". The features variable columns are "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "INCOME_AMT", "SPECIAL_CONSIDERATIONS". The column EIN "Employee Identification" was dropped because these numbers provide no significant value and could inadvertently alter the machine learning model. The "NAME" column was dropped in the first model but used in second model, AlphabetSoupCharity_Optimzation.

### Compiling, Training, and Evaluating the Model
The second model, AlphabetSoupCharity_Optimzation, was able to achieve an accuracy score over 75% and surpass the target goal. Four hidden layers with 100 epochs were used. Each layer used between 40-100 nodes. We converted 3 columns into data points: NAME, APPLICATION_TYPE, and CLASSIFICATION. All of these steps combined to help achieve our goal of a minimum accuracy score of 75%. 

##Summary
Our optimized model has an accuracy score of 79%. Reclassifying the NAME column was likely the biggest reason. We chose 6 times or more for an applicant/NAME appearing. This makes our accuracy so high because it shows the charity has already vetted this applicant in the past and they had a success. It’s unlikely you would see the same applicant numerous of times if they failed frequently in the past. You can always add more hidden layers and increase nodes for better performance. However, you will probably get diminishing increments in accuracy and add significant run time. Since we are targeting a binary variable, we could use other unsupervised machine learning like random forest classification.
