# BiClassifier_R
Portfolio: Class assigment cleaned up for portfolio

Back to [Home Page](https://jerryfinn.github.io/)

**WARNING:** *I had to leave out the main data file loan_stat542.csv and the training data. They are over 100Mb, too large for the free tier of github*

## Introduction

This was an assignment for one of my machine learning classes when I was working on my masters in data science. 

For this assignment, historical data from an institution called the "Lending Club" was taken from Kaggle. The university reduced the variables to 30 features in total including the response 'loan_status'. 

The assignment allowed us to submit up to 3 models for scoring, and the grade was based on the score of the best model. We were also given a file designating 3 train and test splits of the data to use in our own testing and debugging. Originally the programs for the assignment were a group of ".R" files, not a notebook (.Rmd) as I have here. But to make this an easier read, I've put every thing in one notebook.  

This notebook has 3 examples  
 1. Logistical Regression using glmnet  
 2. Gradient Booster Tree using xgboost  
 3. Random Forest using h2o  

