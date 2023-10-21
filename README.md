# House Price Prediction

In this project, we use machine learning algorithms to predict Bangalore house prices.

## Data Preprocessing

The dataset is sourced from Kaggle. Here's an overview of the steps we followed:

- Importing libraries such as pandas, numpy, and matplotlib.
- Importing the data into a DataFrame and examining its shape and data types.
- Dropping unimportant columns and handling any null values, which were found to be minimal.
- Performing feature engineering to create new, more interpretable features.
- Reducing the dimension of the data by focusing on the most frequent values.
- Removing outliers with the assumption that the data is normally distributed.

## Model Building

Our model building process can be summarized as follows:

1. Splitting the data into the train and test sets.
2. Utilizing GridSearchCV to determine the best model parameters for linear regression, Lasso regression, and decision tree.
3. Training the model with the optimal parameters obtained.
4. Evaluating the model's accuracy using K-fold cross-validation, resulting in an impressive accuracy score of 85.7%.



