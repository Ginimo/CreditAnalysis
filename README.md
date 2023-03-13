# Credit Analysis
Machine Learning Project with the famous "credit" dataset by using Linear Models,  Generalized Additive Models (GAM), Generalised Linear Models (GLM), Support Vector Machines (SVM) and Artificial Neural Networks (ANN) with R conducted by Matthias De Paolis, Lukas Niederhäuser and Daniel Podolecki.


SUMMARY
===================================================================================================

In the zip-folder you will find the PDF-File and the corresponding R-Markdown with the 
Analysis of Credit Data in Germany from 1994 by using various Machine Learning Methods. 
The Analysis is done using the Programming Language R.

Furthermore the zip-folder contains the credit data required for the analysis. 
This dataset classifies people described by a set of attributes as good or bad credit risks.


USAGE 
===================================================================================================

To run the analysis it is recommended to extract the zip-folder and store all the data in
a place of your choice. In R or R-Studio you need to refer to the csv named "dataset_31_credit-g.csv".
Therefore setwd () to your folder where you extracted the data in the zip file. 


METADATA
===================================================================================================

Attribute descriptions

Attribute 1: (qualitative)
Status of existing checking account in Deutsche Mark.
1: ... < 0 DM
2: 0 <= ... < 200 DM
3:  ... >= 200 DM / salary assignments for at least 1 year
4: no checking account

Attribute 2: (numerical)
Duration in month

Attribute 3: (qualitative)
Credit history
1: no credits taken/ all credits paid back duly
2: all credits at this bank paid back duly
3: existing credits paid back duly till now
4: delay in paying off in the past
5: critical account/ other credits existing (not at this bank)

Attribute 4: (qualitative)
Purpose
1: car (new)
2: car (used)
3: furniture/equipment
4: radio/television
5: domestic appliances
6: repairs
7: education
8: retraining
9: business
10: others

Attribute 5: (numerical)
Credit amount in Deutsche Mark.

Attibute 6: (qualitative)
Savings account/bonds in Deutsche Mark.
1: ... < 100 DM
A62 : 100 <= ... < 500 DM
2: 500 <= ... < 1000 DM
3: .. >= 1000 DM
4: unknown/ no savings account

Attribute 7: (qualitative)
Employment since in number of years
1: unemployed
2: ... < 1 year
3: 1 <= ... < 4 years
4: 4 <= ... < 7 years
5: .. >= 7 years

Attribute 8: (numerical)
Installment rate in percentage of disposable income

Attribute 9: (qualitative)
Personal status and sex
1: male : divorced/separated
2: female : divorced/separated/married
3: male : single
4: male : married/widowed

Attribute 10: (qualitative)
Other Parties
1: none
2: co-applicant
3: guarantor

Attribute 11: (numerical)
Residence since in number of years

Attribute 12: (qualitative)
Property Magnitude
1: real estate
2: life insurance
3: car 
4: unknown / no property

Attribute 13: (numerical)
Age in years

Attribute 14: (qualitative)
Other payment plans
1: bank
2: stores
3: none

Attribute 15: (qualitative)
Housing
1: rent
2: own
3: for free

Attribute 16: (numerical)
Number of existing credits at this bank

Attribute 17: (qualitative)
Job
1: unemployed/ unskilled 
2: unskilled 
3: skilled employee
4: management/ self-employed/ highly qualified employee/ officer

Attribute 18: (numerical)
Num dependents: Number of people being liable to provide maintenance for

Attribute 19: (qualitative)
Telephone
1: none
2: yes, registered under the customers name

Attribute 20: (qualitative)
Foreign worker
1: yes
2: no 

Attribute 21(qualitative)
Class 
1: Good
2: Bad
