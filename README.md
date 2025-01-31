# Practical-Application-Assignment-17.1---Comparing-Classifiers
Repo for files for Practical Application Assignment 17.1
Model Performance:

All four classifiers (KNN, Logistic Regression, Decision Tree, SVM) correctly predicted most outcomes, achieving overall accuracy around 90%. This means they performed well in predicting the majority class (no to subscription).
However, when predicting the minority class (yes to subscription), their performance was weaker, especially in terms of recall (ability to identify those who subscribed).
Why This Happens:

The dataset has a large imbalance between those who subscribed (yes) and those who didn’t (no), making it harder for the models to predict the less frequent outcome.
Feature Importance:

Some variables, such as the duration of the last call, are strong predictors. However, since duration is only known after the fact, it cannot be used for making predictions beforehand.
Key Takeaway:

While the models work well for identifying non-subscribers, improvements are needed to better predict potential subscribers.
