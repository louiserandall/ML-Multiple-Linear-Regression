# ML-Multiple-Linear-Regression

Read diabetes.csv into a Jupyter notebook.
● The diabetes.csv aims to predict a person’s progression in the condition
with respect to various attributes about them.
● Differentiate between the independent variables and the dependent
variable and assign them to variables x and y.
● Generate training and test sets comprising 80% and 20% of the data
respectively.
● Use a MinMaxScaler and StandardScaler from sklearn.preprocessing. Fit
these scalers on the train set and use these fit scalers to transform the train
and test sets.
● Generate a multiple linear regression model using the training set. Use all
of the independent variables.
● Print out the intercept and coefficients of the trained model.
● Generate predictions for the test set.
● Compute the r2_score of your model on the test set. You can get the
r2_score from sklearn.metrics.
● Ensure your notebook is well commented with topics and comments on
what your code is accomplishing.


Read in the hourlywagedata.csv. This dataset contains information about
the hourly wage paid to employees who work in a hospital, along with their
position, age, and number of years worked (see ‘More about the data’
below).

● Clean up the data: drop any rows which contain a missing value for any one
of the 4 variables (i.e. containing a string made up of only a space “ “) and
convert the hourly wage values to floats.
● Generate three plots showing the average hourly wage against the three
categorical independent variables.
As we did in the advertising example, we are going to use multiple linear
regression to train a model to predict the hourly wage.
● Generate a training and test set, again with an 80:20 split.
● Investigate whether the distribution of the variables in your test set is
representative of the distribution in the training set. For example, find out if
the number of nurses who work in the hospital and the office found in the
test set are similar, proportion-wise, to those found in the training set.
● Generate a multiple linear regression model using the training set. Use all
the independent variables.
● Generate predictions for the test set.
● Generate an error plot for your predictions.
● Compute the Root Mean Squared Error of your model on the test set.
● Print the coefficients and try to interpret them as we did for the
advertisement model.
