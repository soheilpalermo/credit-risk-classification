# Credit Risk Analysis
### Overview of the Analysis
The purpose of this analysis is to evaluate the creditworthiness of loan applicants by leveraging machine learning techniques. Using historical lending data from a peer-to-peer lending services company, we built a logistic regression model to predict whether a loan is high risk (default) or healthy (not default).

The dataset includes financial attributes related to loans, and the target variable is the loan status (0 for healthy loans and 1 for high-risk loans). The machine learning process included:

- Preparing the data by splitting it into training and testing sets.
- Training a logistic regression model.
- Evaluating the model using metrics such as accuracy, precision, recall, and F1-score.
  
## Results
### Logistic Regression Model Performance:
- #### Accuracy: 99%
- #### Precision:
- Class 0 (healthy loans): 1.00
- Class 1 (high-risk loans): 0.89
#### Recall:
- Class 0 (healthy loans): 1.00
- Class 1 (high-risk loans): 0.93
#### F1-Score:
- Class 0: 1.00
- Class 1: 0.91
  
## Summary
The logistic regression model performed exceptionally well with an overall accuracy of 99%. It demonstrated perfect precision, recall, and F1-score for predicting healthy loans (0), ensuring the model is highly reliable in identifying loans that are not at risk. However, the performance for predicting high-risk loans (1) is slightly lower, with a precision of 0.89 and recall of 0.93, indicating a small number of false positives and false negatives.

## Recommendation:
Given the high overall accuracy and reliable performance in identifying healthy loans, the model is recommended for use in predicting loan statuses. However, if the company's priority is to minimize false negatives (misclassifying high-risk loans as healthy), further refinement of the model, such as addressing potential class imbalances, could improve its performance for high-risk loan predictions.
