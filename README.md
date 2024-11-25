# IPL Win Prediction using Machine Learning

This project aims to predict the winner of an Ipl match based on match stats of ipl players, umpires, venues, etc. For this project, we will initially perform exploratory data analysis and eventually build a machine learning model. For this model we will be using Logistic Regression  which uses a binomial probability distribution function and Naive Bayes and analyze the results to get an optimized model.
## Inference 

For binary class problems like win/lose situations, both the Random Forest Classifier and Logistic Models have shown strong performance.

1. Random Forest:
   - Random Forest reduces overfitting in decision trees and helps improve accuracy.
   - It employs bagging through bootstrap aggregation.
   - Decisions from multiple trees collectively yield much better results than a single overfitted tree.
   - Our Random Forest model achieved an accuracy of 96.8%, attributed to proper hyperparameter tuning (e.g., number of estimators, max features, etc.).

2. Logistic Model:
   - Logistic regression works well for binary classes, providing probabilities for win or lose situations and offering a natural probabilistic view of class predictions.
   - It offers good accuracy for simple datasets and is less prone to overfitting.
   - The Logistic Model achieved an accuracy of approximately 86%, which is not a significant drop as it considers probabilities of situations as well.
