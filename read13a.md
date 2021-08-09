# Linear Regressions
Linear Regression is a technique to create mathematical model represents a best fit for data set
we can use numpy, scipy, stats model and sckit learn for linear regression. however, Scikit-learn is a powerful Python module for machine learning.


# for Scikit Learn:
.fit() fits a linear model
.predict() Predict Y using the linear model
.score() Returns the coefficient of determination
# Training and validation data sets:
In practice, linear regression wont be implemented on the entire data set, the set will be splited into training and test data sets. So that it will train the model on training data and see how well it performed on test data.
# Residual Plots:
Residual Plots are a good way to visualize errors in data. regression was a best fit, data should be randomly scattered around model line .
# How to do train-test split
You have to divide your data sets randomly. Scikit learn provides a function called sklearn.model_selection to do this.

# Conclusion
explore the boston data set and then renamed its column names.
use Scikit learn to fit linear regression to the entire data set and calculate the mean squared error.
make a train-test split and calculate the mean squared error for training data and test data.
then plot the residuals for training and test datasets.