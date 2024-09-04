Data preprocessing by normalizing and binning continuous variables in Job satisfaction level 
and last performance evaluation  
I created a new feature called project hours interaction by multiplying completed projects and 
average working hours monthly attributes. I encoded categorical variables for salary and and 
job role. I first did salary mapping by categorizing low to 1, medium to 2 and high to 3. I dropped 
irrelevant features. 
I split the dataset in training and testing sets, 20% for testing and 80% for training 
I used random forest classifier because of its ability to handle both types of data and feature 
importance analysis. I trained the data to make predictions. 
I evaluated the accuracy, precision, F1 score and recall:
Feature importance analysis output
# Turnover-Prediction-Analysis
