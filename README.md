# Nepal Earthquake Building Damage Prediction
This project uses data from Open Data Nepal to build a model to predict building damage from the Nepal 2015 Earthquake. The goal is to create a model that when given the characteristics of a builing can accurately predict if the building will suffer severe damage or not in a similar type of earthquake.

# Data
The data used in this project is available from [Open Data Nepal](https://opendatanepal.com/). It is stored in an SQLite database. 

# Methods
This is a classification task, which means that the goal is to predict a categorical outcome variable based on a set of input features. In this case, the outcome variable is the level of damage to a building following the Nepal 2015 earthquake, which can take on one of two values: severely damaged or not severely damaged.

To create a model that can predict the level of building damage, two algorithms were used: decision tree and logistic regression. These are both popular and widely used algorithms for classification tasks.

The performance metric used to evaluate the models was accuracy, which measures the percentage of correct predictions made by the model.

The data used in this project was first wrangled using SQL, and then converted to a dataframe for further exploration and cleaning. The wrangling process involved selecting and joining relevant tables from the SQLite database, and cleaning and transforming the data to prepare it for analysis.

There are four Jupyter notebooks uploaded as part of this project:

* Data Wrangling Notebook: This notebook contains the SQL code used to wrangle the data from the SQLite database, as well as the Python code used to convert the data to a dataframe and perform initial exploratory analysis.

* Logistic Regression Notebook: This notebook contains the Python code used to train and evaluate a logistic regression model for predicting building damage.

* Decision Tree Notebook: This notebook contains the Python code used to train and evaluate a decision tree model for predicting building damage.

* Model Comparison Notebook: This notebook contains the Python code used to compare the performance of the logistic regression and decision tree models, and determine which model had better predictions for the task at hand.

Each notebook includes detailed explanations of the steps taken and the code used, making it easy to follow along and replicate the analysis.


# Installation
To run this project on your machine, you will need to have Python 3 and the packages listed in the requirements.txt file in your environment.


# Usage
To use the models, you can run the Jupyter notebooks provided. The notebooks have detailed explanations of the steps taken and the code used.