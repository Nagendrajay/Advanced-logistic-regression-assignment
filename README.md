# Advanced Regression - Assignment
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 

## Table of Contents
* Introduction to the case study
* [Technologies Used]: pandas, numpy, seaborn, matplotlib, sklearn, scipy.


* [Conclusions]
  We have seen an implementation of ridge and lasso regression models and the theoretical and mathematical concepts behind these techniques. Some of the key takeaways  from this case study include:
Ridge: 
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

Lasso:
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
The database was in csv file named train.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The model buit is sginificant and tested. The model is not overfitted, not biaed and has least variance. Ridge and Lasso regression were performed over the model. Further detailed conclusion is seen in part 1 file and also in part 2 (pdf)

