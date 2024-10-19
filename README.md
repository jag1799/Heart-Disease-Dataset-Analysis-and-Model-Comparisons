# Heart-Disease-Linear-Regression

An analysis and model comparison of Linear and Logistic Regression, Gaussian Naive Bayes, Decision Trees, and Neural Networks using Scikit-Learn and the Cleveland Heart Disease Dataset.

## Results:

The variable most correlated with the target was *ST slope* with a correlation value of ~0.5.  However, the Linear Regression model prediction scores on the test set only ranged from 20% to 30% accuracy when only based on this variable.  The other models used all non-target variables, resulting in the Decision Tree being the best model with an average accuracy of 86% across 100 train-test splits.
