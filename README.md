# INEURON Credit-Card-Default-PredictoN uSING ml

## Overview

This is an end-to-end ML project, which aims at developing a classification model for the problem of predicting credit card frauds using a given labeled dataset.

The classifier used for this project is RandomForestClassifier.


*****************************

## Motivation

With the growing number of credit card users, banks have been facing an escalating credit card default rate. This increase in defaults causes losses to the 
financial institutions along with the card holders. As such data analytics can provide solutions to tackle the current phenomenon and management of credit 
defaults. This project discusses the implementation of an model which predicts if a given credit card
holder has a probability of defaulting in the following month, using their demographic data and
behavioral data from the past 6 months.
**********************************

## Dataset Information

This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.

**Content**
There are 25 variables in the dataset:

* ID: ID of each client
* LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit
* SEX: Gender
  * 1=male, 
  * 2=female
* EDUCATION: 
  * 1=graduate , 
  * 2=university, 
  * 3=high school, 
  * 0, 4, 5, 6=others)
* MARRIAGE: Marital status 
  * 1=married, 
  * 2=single, 
  * 3=divorce, 
  * 0=others
* AGE: Age in years
* PAY_0: Repayment status in September, 2005 
    * -2: No consumption; 
    * -1: Paid in full; 
    * 0: The use of revolving credit; 
    * 1 = payment delay for one month; 
    * 2 = payment delay for two months; 
      . 
      . 
      .; 
    * 8 = payment delay for eight months; 
    * 9 = payment delay for nine months and above.
* PAY_2: Repayment status in August, 2005 (scale same as above)
* PAY_3: Repayment status in July, 2005 (scale same as above)
* PAY_4: Repayment status in June, 2005 (scale same as above)
* PAY_5: Repayment status in May, 2005 (scale same as above)
* PAY_6: Repayment status in April, 2005 (scale same as above)
* BILL_AMT1: Amount of bill statement in September, 2005 (NT dollar)
* BILL_AMT2: Amount of bill statement in August, 2005 (NT dollar)
* BILL_AMT3: Amount of bill statement in July, 2005 (NT dollar)
* BILL_AMT4: Amount of bill statement in June, 2005 (NT dollar)
* BILL_AMT5: Amount of bill statement in May, 2005 (NT dollar)
* BILL_AMT6: Amount of bill statement in April, 2005 (NT dollar)
* PAY_AMT1: Amount of previous payment in September, 2005 (NT dollar)
* PAY_AMT2: Amount of previous payment in August, 2005 (NT dollar)
* PAY_AMT3: Amount of previous payment in July, 2005 (NT dollar)
* PAY_AMT4: Amount of previous payment in June, 2005 (NT dollar)
* PAY_AMT5: Amount of previous payment in May, 2005 (NT dollar)
* PAY_AMT6: Amount of previous payment in April, 2005 (NT dollar)
* default.payment.next.month: Default payment 
  * 1=yes, 
  * 0=no

Link : https://www.kaggle.com/uciml/defaultof-credit-cardclients-dataset
******************************


## Installation
The Code is written in Python 3.10. If you don't have Python installed you can find it here. If you are using a lower version of Python you can upgrade using 
the pip package, ensuring you have the latest version of pip. 

*****************************

## Technologies Used

![image](https://user-images.githubusercontent.com/77207245/198870009-95368c87-f4b5-44cd-8385-c2ae7e81e992.png)


***********************************************
## Libraries Install
matplotlib>=3.2.2
scikit-learn>=1.0.2
seaborn>=0.11.2
pandas>=1.3.5
numpy>=1.21.6
imblearn>=0.0
bz2file>=0.98
Flask>=1.1.4
Jinja2>=2.11.3
gunicorn>=20.1.0
itsdangerous==1.1.0
MarkupSafe==2.0.1
Werkzeug==1.0.1
bz2file==0.98










