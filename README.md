# predict loan default status Project
This project uses a few different classification algorithms to try and predict customer loan default status  The following algorithms are tested:  
- K-Nearest-Neighbors 
- Decision Trees 
- Support Vector Machines 
- Logistic Regression

## Environment specification
- numpy
- pandas
- sklearn
- seaborn
- matplotlib

## Summary of classification models
![Summary of classification models](https://user-images.githubusercontent.com/102443619/212226939-66d1f35d-a836-4cdc-8d9d-41b1745e2006.PNG)

• Accuracy: This is the overall percent of correct predictions. Higher is better. For example, an accuracy of 0.85 means the model predicted the correct class 85% of the time. This is an easy metric to understand but can be misleading if the classes are imbalanced.

• F1-score: This measures the accuracy for each class, as well as how precise the predictions are. Higher is better, with a maximum of 1. For example, an F1 of 0.90 means the model is very good at predicting both defaulting and non-defaulting customers. F1-score is a good metric to use if the classes are imbalanced.

• Jaccard score: This measures how similar the actual and predicted classes are. Higher is better, with a maximum of 1 indicating perfect similarity. For example, a Jaccard of 0.80 means there is a 80% overlap between the actual and predicted defaulting customers.

• Log loss: This measures the accuracy of the model's predicted probabilities, not just the final class prediction. Lower log loss is better, with a minimum of 0 indicating perfect accuracy. For example, a log loss of 0.45 means the model's predicted probabilities are moderately accurate. Log loss is a good metric for models with more than two classes.

• Confusion matrix: This shows the counts of true positives, true negatives, false positives, and false negatives. Examine the confusion matrix to see which types of errors the model makes most and if there are any patterns. The diagonal values represent correct predictions, so higher values are better.

### Simplified Report Prediction Mode:

The highest accuracy of 74% is achieved by decision tree, support vector machine, logistic regression, It's hard to say how the accuracy of these models could be improved, but some options like collecting more data about customers or feature engineering. It may be helpful to have more information about the customers location, income, marital status, and number of children.

• "There was an 54% overlap between the customers our model predicted would default and those who actually defaulted." (Jaccard = 0.54)

• "Our model's predicted probabilities for loan default status were moderately accurate, with a log loss of 0.54." (Log loss = 0.54)

• "The confusion matrix shows our model rarely incorrectly predicted defaulting customers as non-defaulting, indicated by the high number of true positives."

# Applied Data Science capstone project
### Present...
