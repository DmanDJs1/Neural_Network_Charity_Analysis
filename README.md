# Neural_Network_Charity_Analysis

## Overview

The purpose of this analysis was to enagage and try to understanding the capabilties of machine learning and neural networks to create a binary classification capable of predicting whether applicants could be successful funded by the firm Alphabet Soup. Using a CSV containing over 30,000 funded organization, we were able to train, evaluate and optimize the Neural Network Model.

## Results

Data Processing

   The target column for this model variable "IS_SUCCESSFUL", as the value in this column determines whether or not a venture was successful in a binary form.
   The features of our model are the variables "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT",   
   "SPECIAL_COUNSIDERATIONS", "ASK_AMT", and in the attept to improve the model, "NAME".
    

Compiling, Training, and Evaluating the Model

   We began with a model that contained 2 hidden layers and 80 and 30 neurons respectively. 
   
 ![image]" Pic " 
   
   We followed that by adding a third layer to optimized model, using a Sigmoid 
   Activation Function. The 3rd layer had 100, 50, and 20 neurons respectively.
   
 ![image]" Pic " 

## Summarize/Conclusion

In summary, we can conclude that a deep learning neural network model did not reach the target of 75% accuracy. The optimization also did not work on improving the results. We can consider other machine learning models like Logistical Regression or Randon Forrest to improve on the reults for our project.
