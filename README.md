# codeinstitute-project1_bank_churners
Predicting when customers churn (leave a credit card company)

The purpose of the analysis is to determine whether the data could be used to target customers when they may leave the company

I found it challenging to determine what features could be used in a visualisation to answer this question but I have some ideas for a more sophisticated analysis that predicts when when each of the existing customers might leave. Additionally, a more sophisticated imputation method would be to use data mining e.g. k-means to find the closest matches and the mode or weight mode of a subset of data. To be thourough we could use satistical tests to check imputation hasn't altered the distributions of the data.

The data folder contains the original CSV file for the Bank Churner dataset which is imported into the ETL_Pipeline file.

A value of 'Unknown' was found in the dataset looking at the unique values for each of the features. I decided to use the mode to impute these values since this was a simple exercise

A pair plot was created to visualise correlations between features

Checked distributions months on books separated by existing and attrition customers

Used a stack barplot do show proportions of card types for income categories