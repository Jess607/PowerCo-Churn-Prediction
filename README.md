# Power-Co-Churn-Prediction
This project was undergone as part of the BCG Gamma Data Science And Advanced Analytics Virtual Experience Program. 

# Table Of Contents
* [Installation](https://github.com/Jess607/PowerCo-Churn-Prediction#installation)
* [About the Project](https://github.com/Jess607/PowerCo-Churn-Prediction#about-the-project)
* [Data Gathering](https://github.com/Jess607/PowerCo-Churn-Prediction#data-gathering)
* [File Description](https://github.com/Jess607/PowerCo-Churn-Prediction#file-description)
* [Limitations](https://github.com/Jess607/PowerCo-Churn-Prediction#limitations)

# Installation 
The code requires knowledge of usage of python versions of 3 and above, basic data wrangling using pandas, visualization using matplotlib and seaborn as well as scikit learn for feature selection and building machine learning models.

# About The Project 
PowerCo is an energy utility company with a clientele comprising SMEs and residential customers spanning across Europe. With the energy liberalization policy at play in the region, PowerCo had built a wide network offering quality service but had recently observed some churn among its SME client companies. 

The goal of the project is to create a churn prediction model for these SME client companies. More information on the business understanding can be found in the powerco SME churn pdf file in the folder. 
We were provided with two datasets; one comprising of client data which included energy and power consumption for each client company as well as other forecast parameters for the period between January and March 2016 and the other comprising of peak, off peak and mid peak energy and power prices for the period between January and December 2015. 

After exploratoration and feature selection, a predictive model was built using the random forest algorithm attaining an accuracy of over 90% and an F-beta score of over 91%. 


# Data Gathering 
Data was provided by the BCG Gamma virtual experience program for analysis and model building. 

# File Description 
The folder contains three files :
* A pdf file of the business understanding and research(typically start here)
* An ipynb file of the EDA process 
* An ipynb file of the feature selection and model building process.


# Limitations 
* Perhaps the greatest limitation to the project was the absence of certain important features like competitors' price offerings which according to our hypothesis research could have played an important role in the churn of clients. 

