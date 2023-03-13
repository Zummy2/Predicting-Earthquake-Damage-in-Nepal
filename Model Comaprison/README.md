# Earthquake Damage in Kavrepalanchok
In this project, I built and compared a logistic regression and decision tree model to predict building damage in the Kavrepalanchok district. This district had the most observations in the id_map table, making it an ideal location to explore how these models can be used to predict building damage.


# Data Splitting
To ensure that the models generalized well to new, unseen data, I split the data into training and validation sets using a randomized split. The size of the validation set was 20% of the total data.

# Performance Metric
The performance metric used was accuracy, which is the proportion of correctly classified observations out of the total number of observations. Accuracy was chosen because it is a simple and easy-to-understand metric that provides a good overall indication of model performance.

# Logistic Regression Model
I started by building a logistic regression model to predict building damage. The model was trained using the training data and evaluated using the validation data. The logistic regression model did performed fairly well in predicting building damage. 
# Decision Tree Model
I decided to try a decision tree model as well to see how well it'll perform. I created a for loop to train the model at all depths from 1 to 15. Then, I plotted a validation curve to find the best value of max_depth that would give me the best validation accuracy score.

The decision tree model performed really well on the test data. The best max_depth value was used to build the final decision tree model. The accuracy score of the decision tree model was higher than the baseline accuracy.

# Feature Importance
To communicate the results, I extracted the features and their importances from the decision tree model. Feature importance is a way to understand which features were most important in predicting building damage in the Kavrepalanchok district.

I plotted a bar chart of the features and their Gini importance. The Gini importance is a measure of the total reduction of impurity provided by a feature. This helped to identify the most important features for predicting building damage in the Kavrepalanchok district. The top three most important features were roof_type, height_pre_earthquake, and age_building.

# Conclusion
Overall, the decision tree model outperformed the logistic regression model in predicting building damage in the Kavrepalanchok district. The feature importance analysis showed that the type of roof, the height of the building before the earthquake, and the age of the building were the most important features in predicting building damage.

This project highlights the importance of exploring different modeling techniques to find the best model for the data at hand. It also emphasizes the value of understanding which features are most important in predicting the outcome of interest, as this can provide valuable insights for decision-making.



