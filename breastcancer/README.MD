Logistic Regression Machine Learning Model on Breast Cancer Data
===
Hi! This directory holds my breastcancer.py file.

The program pulls from a data set involving measurements of various tumors, and whether they are malignant or benign.


In it, I use 5 parameters, average tumor radius, texture, perimeter, area, and smoothness. It uses a logistic regression model on a training set. The training set involves the 5 parameters as inputs and the answer to whether the tumor is malignant or benign as outputs.


Once the logistic regression model is fitted to the data, it moves on to the testing phase using distinct testing parameters and predicting whether the corresponding parameters indicate cancer or not. Finally, the predictions are compared against the true data of whether there is cancer or not to test the proficiency of the program. 

The model, as of my last run through, predicts cancer positivity with 93% accuracy. That's pretty cool.
