# Linear Regression
**Objective**: The primary objective is to implement the Linear Regression Algo on the Boston House Prediction Dataset and find the price of houses.
## Dataset
The Dataset has to be imported from sklearn.datasets.

**Data Set Characteristics:**  

    :Number of Instances: 506 

    :Number of Attributes: 13 numeric/categorical predictive. Median Value (attribute 14) is usually the target.

    :Attribute Information (in order):
        - CRIM     per capita crime rate by town
        - ZN       proportion of residential land zoned for lots over 25,000 sq.ft.
        - INDUS    proportion of non-retail business acres per town
        - CHAS     Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
        - NOX      nitric oxides concentration (parts per 10 million)
        - RM       average number of rooms per dwelling
        - AGE      proportion of owner-occupied units built prior to 1940
        - DIS      weighted distances to five Boston employment centres
        - RAD      index of accessibility to radial highways
        - TAX      full-value property-tax rate per $10,000
        - PTRATIO  pupil-teacher ratio by town
        - B        1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
        - LSTAT    % lower status of the population
        - MEDV     Median value of owner-occupied homes in $1000's

**EDA**
  :BY doing Basic EDA,i came to know that two features are highly correlated. so, we have to remove either of the features.

**Techniques Used**
  * Stochastic Gradient Descent
  * SGDRegressor from sklearn.linear_model
  * LinearRegression from sklearn.linear_model

**Model Performance Metrics**
  * mean_squared_error
  * r2 score
## Python Library (required)
* tqdm (**pip install tqdm**)
  *  add progress bars to Python code.
* pandas_profiling(**pip install pandas_profiling**)
    * used for EDA
