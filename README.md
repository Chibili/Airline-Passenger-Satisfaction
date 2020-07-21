# Airline Passenger Satisfaction Predictive Model

By: Richard Cornelius Suwandi & Chibili Mugala

Start Date: 21/07/2020

### Project Summary

The aviation industry, like most fast-paced businesses, requires swift action to retain or attract customers. With the aid of data analytics, creating a business model that reflects on customer demands through uncovering patterns in a data-driven model is paramount. 

Other essential tasks will involve correlation tests; this will generate a mapping of variables in relation to multicollinearity. Variables with high variance from the "Satisfaction" independent variable will play a vital role in the modeling stage while ones with little or no variance will be excluded. 

Understanding the service dimensions such as "Leg Room Service", "Inflight Entertainment", "On-board Service" and "Checkin Service" will possibly lead to feature engineering. The target variable (Satisfaction) can undergo data transformation through either label encoding with "Yes" or "No" (0 or 1) outcomes. 

Correspondingly, we will treat this as a binary classification problem, where we will try to create a model that predicts whether the customer is satisfied or not with the experience and/or service provided by the airline.

The following sections will illustrate the steps taken to develop the model;

### I. Data Collection

The Airline Passenger Satisfaction data was collected from [Kaggle.com](https://www.kaggle.com/teejmahal20/airline-passenger-satisfaction). 

### II. Data Cleaning

Based on the data, there are several things that we need to do to prepare the data before fitting it to a model. There are a few categorical variables that need to be encoded, including the target variable "Satisfaction". There are also a couple of columns that can be dropped, such as "Unnamed: 0" and "id", since they don't contain useful information.

### III. Exploratory Data Analysis

The EDA will involve processes related to understanding characteristics of given fields in the underlying data such as variable distributions, whether the dataset is skewed towards a certain demographic, and the data validity of the fields. For  instance, a training dataset may be highly skewed towards Class. If so, how will this impact the results when using it to predict the remaining customer base. In addition, we might ask some interesting questions like: Is the business class generally better rated than the other two classes? Which features/services are poorly rated across all classes? 

Secondly, identifying limitations surrounding the data and gathering external data which may be useful for modeling purposes. This may include exploring other airline data at different service dimensions and creating additional features for the model. For example, **(provide possible feature engineering idea)**
Exploration of interactions between different variables through correlation analysis and look out for multicollinearity by creating interaction variables. An example of this correlation may occur between independent variables "Age" and "Class" – i.e. people of the older brackets will be more inclined to a particular class offering.

Furthermore, transforming the required data so that it is in an appropriate format for analysis. This may include steps such as ensuring that the data types are appropriate and rolling data up to an aggregated level. Or, joining in already aggregated external source data **(provide example)** to create additional variables.

Another possible step to do is factor analysis, where we describe the variability among correlated variables in fewer variables (factors). For instance, instead of having multiple variables to describe the service (On-board Service, Baggage Handling, Inflight Service, etc.), we could work with one factor called "Service".

"Document assumptions, limitations, and exclusions for the data; as well as how you would further improve in the next stage if there was additional time to address assumptions and remove limitations."

### IV. Modeling Data



### V. Data Intepretation


