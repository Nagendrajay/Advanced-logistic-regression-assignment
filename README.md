# Advanced Regression - Assignment
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 

## Table of Contents
* Introduction
* [Technologies Used]: import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from scipy.stats import kurtosis,skew
from sklearn.impute import SimpleImputer
from sklearn.preprocessing import MinMaxScaler
from sklearn.preprocessing import StandardScaler
from sklearn.model_selection import train_test_split
from sklearn.linear_model import Lasso
from sklearn.model_selection import GridSearchCV
from sklearn.model_selection import cross_val_score
from sklearn.linear_model import Ridge
import os
from sklearn.metrics import r2_score

* [Conclusions]
We have seen an implementation of ridge and lasso regression models and the theoretical and mathematical concepts behind these techniques. Some of the key takeaways from this case study include:
Ridge
* No much variance noticed between the train and test data (refer: Figure "r2 and alpha" in section "Ridge")
* Ridge score for train and test data are 0.9095 and 0.8743
* The scores are prety much in the acceptable range.
* Top five significant variables in Ridge are:
'GarageFinish_RFn': 0.082,
'GarageFinish_Unf': 0.094,
'SaleCondition_Normal': 0.098,
'SaleCondition_Others':0.106,
'SaleCondition_Partial': 0.143
The optimum value of 'Lambda' in ridge is = 10

Lasso
* No much variance noticed between the train and test data (refer: Figure "r2 and alpha" in section "Lasso")
* Lasso score for train and test data are 0.8798 and 0.8641
* The scores are accpetable as they are close to each other
* Top five significant variables in Lasso are:
'GarageFinish_RFn': 0.08
'GarageFinish_Unf': 0.082
'SaleCondition_Normal': 0.099
'SaleCondition_Others': 0.121
'SaleCondition_Partial': 0.197
The optimum value of 'Lambda in Lasso is = 0.001

Lasso Regression could be opted because its helps in feature selection.

* [Acknowledgements]
I would like to acknowledge the supporting staffs of upgrad and also the instructors from Industry as well as professors from IIIT-B



## General Information
- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis
- Conclusion 2 from the analysis
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
