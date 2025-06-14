Titanic Survival Prediction - Exploratory Data Analysis (EDA)

This repository contains the exploratory data analysis (EDA) performed on the famous Titanic dataset. The goal of this project is to understand the factors that influenced survival on the Titanic and prepare the data for machine learning model building.
Project Steps Completed:
1.	Data Loading and Initial Inspection:
o	Loaded the titanic.csv dataset into a pandas DataFrame.
o	Performed initial inspection using head(), info(), and describe() to understand the data structure, data types, and basic statistics.
2.	Handling Missing Values:
o	Identified columns with missing values (Age, Cabin, Embarked).
o	Imputed missing values in the 'Age' column with the mean age.
o	Dropped the 'Cabin' column due to a large number of missing values.
o	Imputed missing values in the 'Embarked' column with the mode.
3.	Data Visualization:
o	Visualized the distribution of the 'Survived' column using a count plot.
o	Created count plots for categorical features ('Pclass', 'Sex', 'Embarked') to understand their distributions.
o	Visualized the relationship between categorical features and 'Survived' using count plots with hue.
o	Created histograms for numerical features ('Age', 'Fare') to visualize their distributions.
o	Used box plots to visualize the relationship between numerical features ('Age', 'Fare') and 'Survived'.
o	Used box plots to identify potential outliers in numerical columns ('Age', 'Fare', 'SibSp', 'Parch').
4.	Exploring Categorical Variables:
o	Analyzed the unique values and frequencies of 'Sex', 'Embarked', and 'Pclass'.
Next Steps (Planned):
•	Feature Engineering
•	Encoding Categorical Variables
•	Scaling Numerical Features
•	Splitting the Data into Training and Testing Sets
•	Building and Evaluating Machine Learning Models
This README provides an overview of the EDA process. The detailed steps and code can be found in the accompanying Jupyter Notebook (.ipynb) file.
________________________________________

