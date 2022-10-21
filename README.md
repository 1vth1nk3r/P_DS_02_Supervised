# Predicting bank customer churn
The project from the Machine Learning in Business sprint of the Practicum DS course.

## Description
Here we have a dataset on churned Beta Bank customers. We aim to build a model to predict whether a customer will leave the bank soon.

First, we should do some data preprocessing: clean the data, fill in the missing values (if any), and change data types. Next, we need to scale and encode the date. Afterward, we could proceed to develop models.

## Conclusion
Using some data on churned Beta Bank customers, we built a DecisionTreeClassifier that predicts the best option with an F1 score of 0.595 and an AUC-ROC metric of 0.844.