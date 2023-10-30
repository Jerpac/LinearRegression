# LinearRegression
Used the sklearn library to create a Linear Regression model from a given dataset.

RUNNING
---------
Simply run the code on google colab to output the results.

The results will give you the data from SGDRegressor, the heat map, graphs, and data from  OLS.

________________
Libraries used:

import pandas as pd
import numpy as np
from sklearn.linear_model import SGDRegressor
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import RepeatedStratifiedKFold
import seaborn as sns
from sklearn.metrics import mean_squared_error
from sklearn.model_selection import train_test_split
from sklearn.metrics import r2_score
import matplotlib.pyplot as plt
import statsmodels.api as sm
from statsmodels.sandbox.regression.predstd import wls_prediction_std
