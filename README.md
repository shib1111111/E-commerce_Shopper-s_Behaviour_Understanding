# E-commerce_Shoppers'_Behaviour_Understanding
In this project, we aim to analyze the customer behavior of an e-commerce company using the session data of its users for a year. The main objective is to predict whether a user has made a purchase or not, based on other attributes of the user.

## Data Description
The data contains several attributes related to the user and their session on the e-commerce website. The target variable is "Made_purchase", which is a binary indicator of whether the user made a purchase during the year or not. The data has been collected by non-experts, so there might be some percentage of error in some columns.

## Evaluation Metric
The evaluation metric for this project is the mean F1-score, which is a measure of accuracy that weights recall and precision equally. This means that the algorithm that maximizes both recall and precision simultaneously will perform better than an algorithm that performs extremely well on one but poorly on the other.

## Submission Format
The submission file should be in CSV format and contain a header with the following columns: "id" and "Made_Purchase". The "id" column should contain the unique identifiers for each user in the test set, and the "Made_Purchase" column should contain the predicted values (True/False) for whether the user made a purchase or not.

## Conclusion
By analyzing the customer behavior of the e-commerce company using the session data of its users, we can gain valuable insights into their preferences and shopping habits. By accurately predicting whether a user will make a purchase or not, the e-commerce company can optimize their marketing strategies and improve their overall performance.
