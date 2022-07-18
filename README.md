# supervised_machine_learning_loans

This repository contains a 2 machine learning models that are able to predict whether a loan will be approved or not. Predictions and Analysis of the results are included to determine which of the 2 models (Logistic Regression or Random Forest Classifier) performs better.

### Predictions

I would expect the Random Forst Classifier to be the better performing model since it takes many subsets of the data and finds the consensus average of these. The Logistic Regression analyzes the dataset as a whole and determines the classes from this which is likely to include some outlier points that may slightly throw off the model.

### Technologies

- Python
- Pandas
- Jupyter Notebook
- Sci-Kit Learn

### Results and Analysis

Both of the models performed extremely well but the Logistic Regression model was actually slightly better on the test data. The Logistic Regression model had a score of 0.9924680148576145 and the Random Forest Classifier model had a score of 0.9917457697069748. These numbers are both quite strong and I imagine since they are so close they could likely flip using a different random state for the dataset.
