# house-price-through-data-diversion
predicting house price by dividing data types and then comparing with sales price
House prices fluctuate over time
# AIM
To find best sales price of house , with different different features like parking , bed room , frontage, area , built up year , etc 
# DATA 
kaggle Advance house pricing data
# PROCEDURE
As this is my first project , and i dont have much knowledege in this domain , so im starting  with dividing the data and comparing each type to find the relation 
1 == numeric under which two categories come that is "discrete" "continious " 
2 == object/categoroical feattures
1 numeric 
2 discrete 
3 continious
4 object/categorical i have seprated year data indiviual after that finding relationship between different data with sales price then im finding the outlier in all data and percent of missing values that is NAN or 0 , and find relation b/w them with sales price by ploting a graph converting nan value to meaning full values for processing after doing all steps of preprocessing saving train data into new (finaltraindata.csv) repeating steps 3,4,5,6,7,10 for test data saving test into new finaltestdata seprating xtrain and ytrain applying lasso rigression (l2 regulalization technique) in x train to find the best feature among them and upadting xtrain
# Python libraries used:


      1  import pandas as pd 
      2  import numpy as np
      3  import matplotlib.pyplot as plt
      4   import seaborn as sns
      5   from sklearn.preprocessing import MinMaxScaler
      6   from sklearn.model_selection import train_test_split
      7   from sklearn.linear_model import Lasso
      8   from sklearn.feature_selection import SelectFromModel 
      9   from sklearn.ensemble import RandomForestRegressor
      10  from sklearn.model_selection import RandomizedSearchCV
      11  from sklearn.metrics import r2_score
      

# Conclusion
 detailed conclusion has been provided in the model.ipynb 
