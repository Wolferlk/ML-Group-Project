# House Price Prediction Using Machine Learning Models

## Problem
In the real estate market, determining the correct price of a house is very important for both
buyers and sellers. House prices depend on many factors such as the size of the house, number of
rooms, location, quality of construction, and year built. However, manually estimating house
prices based on these factors can be difficult and may lead to inaccurate results.
The problem addressed in this project is to predict the sale price of a house using machine
learning techniques. By analyzing historical housing data from the Ames Housing Dataset, we
aim to build models that can learn the relationship between house features and their prices.
This is a supervised learning regression problem, where the target variable is the continuous
value SalePrice. Multiple machine learning algorithms are applied and compared to identify
which model provides the most accurate predictions.
The outcome of this project can help in making better pricing decisions in the real estate industry
and demonstrate how machine learning can be used to solve real-world problems.


## Algorithms Used
- Linear Regression
- Decision Tree
- Random Forest
- Support Vector Regression (SVR)

## Dataset
### The Ames Housing Dataset
The Ames Housing Dataset is a well-known dataset in the field of machine learning and data
analysis. It contains various features and attributes of residential homes in Ames, Iowa, USA.
The dataset is often used for regression tasks, particularly for predicting housing prices.
Here are some key details about the Ames Housing Dataset:
- Number of Instances: The dataset consists of 2,930 instances or observations.
- Number of Features: There are 79 different features or variables that describe various
aspects of the residential properties.
- Target Variable: The target variable in the dataset is the "SalePrice," representing the
sale price of the houses.
- Data Types: The features include both numerical and categorical variables, covering a
wide range of aspects such as lot size, number of rooms, location, construction, and
more.

## Team Members
- Sasindu Diluranga
- Pamuditha
- Janith
- Osindu

## Overall Comparison
- Random Forest Regressor performed the best among all models. It achieved the lowest
error (RMSE) and highest R² score, meaning it predicted house prices more accurately
than the other models.
- Decision Tree Regressor performed better than Linear Regression but slightly worse
than Random Forest. It was able to capture complex relationships but showed signs of
overfitting.
- Support Vector Regression (SVR) gave moderate performance. It worked reasonably
well but required proper feature scaling and parameter tuning to improve accuracy.
- Linear Regression showed the lowest performance. Since it assumes a simple linear
relationship, it could not capture the complex patterns present in the housing dataset.


