# Capstone_44688
Capstone Project for the MS Data Analytics Program

The report was written in overleaf editor. You can access the report, and the latex editor with the link below.

https://www.overleaf.com/read/zgyxrgsvgnbg#cc7944

### Module 1

Introduction was formed. The issue was identified that this project was going to be working with Westminster College Data, and it was going to be used to predict if a Westminster student would be retained or not. The domain was identified as Higher Education. 

### Module 2

Went through the data collection process. Wrote a script to get data from two databases that are specific to my college. Data was exported from the SQL environment into a .csv file. 

### Module 3

After the data was collected, the cleaning process took place. Null values were replaced with the average in the numerical columns. Other categories were changed into binary variables, after doing some Exploritory data analysis in the next module, returned to this stage and fixed the outliers for GPA that appeared to be entered incorrectly at 0 for high school.

### Module 4

In this section, exploritory data analysis occured. Several charts such as box plots, histograms, and heat charts were created to get a visual of our data, and see some initial insights and how the features related to each other.

### Module 5

We begin to look at various models for the predictive analysis section. Here we looked at a linear regression model, a decision tree model, a neural net model, and an ADA boosted model. The results were printed along with each model.

### Module 6

In this section, the results are discussed. The best model was chosen which was the ADA Boosted Model. Even though it was the top performing model, it was only successful about two thirds of the time. Some items to think about moving forward are expanding the data set size, as this one had a range of 10 years. Also, would add in financial data from our Financial Aid system such as household income, scholarships received, loans taken out, and other grants. Ideally we would like to see this added in to see if we can get the models performance to increase.

# Westminster College: A Retention Prediction Model

### Author: Ryan Smith

### Abstract

In the ever competing world for enrollment in higher education, retention is becoming a primary focus. This project examines building a model to predict if a student will not be retained at Westminster College. The study will focus on a variety of factors for a student to see if they will churn from the institution. The data was sourced from the local databases, and cleaned using Python. Several models were compared (Linear Regression, Decision Tree, Neural Net, ADA Boosted) from the sklearn library. There appeared to be a correlation between several features and retention, but the results were not strong in the models. More features should be explored, such as household income and aid received to see if the models can be enhanced.

### Project Goal

For this project, we want to see if retention can be predicted at Westminster College based on the selected data points, and a machine learning model. As linked above the project itself can be see from the [Overleaf](https://www.overleaf.com/read/zgyxrgsvgnbg#cc7944) site.

### Introduction

This project will be looking to successfully predict if a student is at risk of being retained. We can use this data with our Student Success Center so that they can set up an intervention, or take the appropriate actions to ensure they can help the student persist. After gathering all the data to analyze, a model will be built and trained on train data, and then tested. After the model is completed, we can discuss the results and see how the model performed. 

### Data Sourcing

All the data was sourced from our own databases. There were two databases one that is our student information system, and the other for enrollment. They were joined with student id number. SQL server was used to collect the data from the databases. Once the data was retreived from the databases, it was exported to a .csv file so that Python could be used for the data cleaning and analytics.

### Data Cleaning


