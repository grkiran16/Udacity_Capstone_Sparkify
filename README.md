# Udacity_Capstone_Sparkify

### Project Overview

We are using a fictional music app called Sparkify to identify which users are at risk to churn - either by downgrading a premium service or opting out from the entire service. Sparkify have access to a large set of music albums with an option for premium service. 


The objective of this project is to create a machine learning model that can predict the customer churn with good accuracy. We are going to use the Pyspark platform to execute this project. This can help Sparkify save money by attempting to retain the customer through various means like coupons, incentives etc.


### Data and Processing


Actual full size data set is 12 GB and it is difficult to process data that big on local machines. So we are using a subset of size 125 MB of the original data provided by Udacity for analysis and prediction purposes. The data we have is user activity tracked by the app which records artist, song, duration, user information time stamps and other relevant information. Before we start with feature selection and machine learning, we should understand the data set thoroughly and decide which variable/features we would like to use for training the model. We are going to do that in subsequent sections

### Python Packages used

This project is executed in a Jupyter Notebook with the help of below packages

1. numpy

2. pandas

3. matplotlib

4. seaborn

5. datetime

6. pyspark.sql

7. pyspark.ml

### Blog Link

https://medium.com/@ravikiran.kiran100/customer-churn-9ac85f5700cb


### Acknowledgements and Licensing

Datatsets for this project are exctracted through the Udacity course

Feel free use the code and other info in this repo for all your references whenever required.
