
# Forecast Spare Parts Inventory
The business case is on the Inventory Management. Keeping
Inventory of spare in various service centre to the market demand is
always a challenge as most service centres spends significant amount
in spare parts inventory costs. In spite of this, availability of spare
parts is been one of the problem areas.

# Data
The data is about a two wheeler spare parts distributor company. This company has many buisiness partners who are 2-wheeler service stations.
The data provided has various spare parts demand for 20 months starting from mid 2018.

# Goal
The goal of this project to create Predictive model for inventory forecasting so that
service centre achieve JIT standards.

# Code 
Please refer the ipynb notebooks for a detailed walkthrough of the entire project.

# Workflow
1.  Exploratory Data Analysis   
    - Basic Checks
    - Missing Values
    - Datetime Variable
    - Numerical Features
    - Categorical features
    - Target Variable
2.  Pre-processing
    - Remove items which are not spares in Target column
3.  Model Building and Evalation  
    - Time Series Models
    - Hyper Parameter Tuning
    - Evalation Results
    - Future Forecast

# Evalation Metric
AIC and RMSE are inter-related but they represent different objectives in choosing the best model. RMSE/MAPE are measures of error and disregards the "complexity" of the model. Optimizing for RMSE/MAPE can give you accurate results, but could lead to overly complex model. It ultimately comes down to the purpose of your model. If having the most accurate prediction matters then you might simply look at RMSE/MAPE, but if you need a model that is more interpretable/explainable then you might want to consider AIC which better balances complexity and accuracy. Here I am looking more into accuracy and will be modelling based on RMSE.

# Contributers
Akshay Shettigar
