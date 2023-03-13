# Overview
In this project, I built a classification model using logistic regression. Logistic regression is a statistical method used to analyze a dataset in which there are one or more independent variables that determine an outcome. The dependent variable is a binary variable that takes on values 0 (negative outcome) or 1 (positive outcome). In our case, the model predicts whether a building will be severely damaged or not in the event of an earthquake.

The data was imported and wrangled using the wrangle function created in the wrangling notebook. During the cleaning process, a binary target was created to indicate whether a building was severely damaged or not. Leaky columns, which are columns that contain data that is only available after the target is known, were also identified and removed. High cardinality columns, which are columns with a large number of unique values, were also identified and handled appropriately.

The data was split into 80-20 for training and testing, and the performance metric used was accuracy. In the model building process, I used OneHotEncoder to handle categorical variables and set max_iter on logistic regression to 2000 to ensure convergence. Both the training and test scores beat the baseline score.

I then extracted the feature importances from the model and created a series called odds_ratio to see which features led to an increase or decrease in the likelihood of a building being severely damaged.
