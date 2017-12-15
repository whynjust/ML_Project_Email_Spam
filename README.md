# ML_Project_Email_Spam

This repository is a simple try of using machine learning to censor email content, and spam junk mails.

## Extracting data

The project data was extracted from UCI dataset, here is the link of the data, https://archive.ics.uci.edu/ml/datasets/spambase

## Manipulating data

Data was processed in four different ways.
### Classic Naive Bayes filter
This is a classic way of filtering junk mails, by looking at frequency of different words, it determines which words has more influence on whether to spam or not. Beacuse the parameter also concerned about the the length and frequency of capital characters, the accuracy is hugely influenced from that.
### Logistic Regression
By simple logistic regression, we used every parameter of the data.
### Logistic Regression with LASSO
Using LASSO to get rid of "useless" parameters or aspects that has little influence on the result of data.
### Neural Network
Set up two layers of neural network, and get the result after 100 epoches.
