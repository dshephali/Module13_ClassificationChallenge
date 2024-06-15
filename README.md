# Module13_ClassificationChallenge

In this challenge we were tasked with improving the email filtering system by creating a Machine Learning (ML) model that can classify them into Spam or Not Spam accurately (most of the time if not all). We created 2 Classification models, Lenear Regression and Random Forest, to evaluate which model is more accurate at detecting spam and found Random Forest Classification model to work better than Linear regression in this case.

Authors & Citation

Shephali Dubey
Alberto Aigner's feedback for a couple of errors

Summary

First you import libraries and dependencies, load data from the csv file, check the data type to ensure the data is numeric and not an object or a string, Split the data into training and testing set,  normalize the data by using StandardScaler, create a Linear regression model and predict accuracy score, then create a Random forest classifier model and predict accuracy score, and finally compare to determine the more accurate model.