# Module 12 Report Template

## Overview of the Analysis

The analysis described in this report describes the machine learning techniques used to meet the challenge,the results obtained, and the conclusions drawn based on the findings. 

Purpose:
The purpose of the challenge was to evaluate machine learning models on loan risk. The starting point for the analysis was the resource dataset that contained historical lending activity from a peer to peer lending services company. The aim was to build a model that can identify the creditworthiness of borrowers. 

Methodology:
The process was set up by identifiying and installing the necessary components for the analysis. The data from the csv file was then read into a pandas dataframe for review. The data was then split into training an testing sets and then viewed to ensure the data was as expected. A critical part of the analysis was to be aware of the balance of the data numbers for the loan conditions. This was carried using the value_counts method.The data was then split into training and testing datasets to lay the foundations for the subsequent model application.
Logistic Regression was used to fit to the training data. The test data was then applied to the prediction model and then evaluated using accuracy score and confusion matrix along with a classification report.
Resampled Training data was then used using the RandomOverSampler module to allow for an analysis with an equal number of datapoints. 
Logistic Regression was again used with the "oversampled" data and an accuracy score, confusion matrix and classification report produced for comparison with the previous data. 


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
