# Linear-Regression

Linear Regression Project

# Importing Libraries
In this project first I have imported all the necessery libraries. (NumPy , Pandas, Seaborn, Matplotlib)


# Importing DataSet

Then I have taken a Data-Set. By using Pandas.

# Deleting String Value columns

As we would work on Numbers only that’s why I dropped all the columns which has String values.

#Checking for Missing values

Then I checked number of null values. 

#Removing Outliers

I checked outliers using box-plot then I deleted outliers as much as possible.

# Correlation Constructing And plotting

Now to check the relation between Our Dependent and Independent variable I Checked the correlation and I plotted it by using seaborn HeatMap.

# Spliting DataSet for training and testing

Then I have spited my dataset into two parts by importing train_test_split from sklearn.model_selection.
Kept 70% of data for training.
The rest 30% of data is for testing.

# Train Model

Now it is time to train our model on our training data!
Import LinearRegression from sklearn.linear_model

Created an instance for the linear regression model.
Then I have fit training data on our intense.
model.fit(X_train, Y_train)

# Tested data

Now that we have fit our model, let's evaluate its performance by predicting off the test values!
Using model.predict() to predict off the X_test set of the data.

# Checking Accuracy

And checked the accuracy rate.
Our Accuracy Score:  0.6129623401328994

# Checking R2 score

R_Squared Score of linear regression: 0.6129623401328994


# Ridge value

For Ridge: from sklearn.linear_model import Ridge
Accuracy Using ridge:  0.6129525920380203

# Lasso Value

For Lesso: from sklearn.linear_model import Lasso
Accuracy Using lasso:  0.6127670843365053
