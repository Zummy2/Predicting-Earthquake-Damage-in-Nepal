# Predicting Earthquake Damage with Decision Tree
This project involves building a classification model using Decision Tree algorithm. Decision tree is a supervised machine learning algorithm used for classification and regression tasks. It works by splitting the data based on a set of conditions (features) that best separates the data into their respective classes or categories.

# Data Wrangling
The data was imported and wrangled with the wrangle function created in the wrangling notebook. The cleaning process involved creating a binary target, identifying leaky columns (columns that reveal information about the target), identifying high cardinality columns (columns with a large number of unique values), and handling missing values.

# Data Splitting
The data was split into training, testing, and validation datasets. The validation dataset was used to evaluate the performance of the model during hyperparameter tuning.

# Performance Metric
The performance metric used for this model was accuracy. Accuracy measures the percentage of correctly classified samples out of the total samples.

# Model Building
OrdinalEncoder was used to encode categorical variables. OrdinalEncoder is a scikit-learn encoder that converts categorical variables to integers.

The model initially overfit the training data, so some hyperparameter tuning was done to find the best depth to train the data with and also to ensure it generalizes well to new data.

# Decision Logic Visualization
A visualization of the decision logic of the model was created to better understand how the model makes its predictions.

# Feature Importance
A horizontal bar chart of the features and their gini importance was created to show the importance of each feature in the model. Gini importance measures how much each feature contributes to the overall impurity reduction in the decision tree.

In conclusion, this part involved building a classification model using decision tree algorithm. The data was cleaned, split into training, testing, and validation datasets. The model was tuned to ensure it generalizes well to new data, and a visualization of the decision logic and feature importance was created to communicate the model's behavior.





