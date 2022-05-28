# Linear Regression Salary
This module uses supervised machine learning to classify and cluster credit card risk data. 

### Overview 
Credit risk is difficult to analyze using traditional methods because it is inherently a skewed data set: most credit loans go to low-risk credit holders, with very few high-risk loans granted. Multiple forms of machine learning were used in this analysis to best analyze, train, fit, and assess the data. 

## Results
This section describes the results of six methods of machine learning on the credit card risk data set. 

### Naive Random Oversampling
* Balanced Accuracy Score: 0.663148681566005 (the model is somewhat good at accurately predicting true and false casses for both classes)
* Precision: 0.99 (99% predictions of true positive and true negative predictions were correct)
* Recall: 0.58 (58% of true positive cases were caught)


### SMOTE Oversampling
* Balanced Accuracy Score: 0.663148681566005 (the model is somewhat good at accurately predicting true and false casses for both classes)
* Precision: 0.99 (99% predictions of true positive and true negative predictions were correct)
* Recall: 0.69 (69% of true positive cases were caught)

### Undersampling
* Balanced Accuracy Score: 0.65922683825913 (the model is somewhat good at accurately predicting true and false casses for both classes)
* Precision: 0.99 (99% predictions of true positive and true negative predictions were correct)
* Recall: 0.40 (40% of true positive cases were caught)

### SMOTEEN Sampling
* Balanced Accuracy Score: 0.5418881808667303 (the model is not very good at accurately predicting true and false casses for both classes)
* Precision: 0.99 (99% predictions of true positive and true negative predictions were correct)
* Recall: 0.59 (59% of true positive cases were caught)
 
### Balanced Random Forest Classifier
* Balanced Accuracy Score: 0.7435435750076411 (the model is reasonably good at accurately predicting true and false casses for both classes)
* Precision: 0.99 (99% predictions of true positive and true negative predictions were correct)
* Recall: 0.88 (88% of true positive cases were caught)

### Easy Ensemble AdaBoost Classifier
* Balanced Accuracy Score: 0.9161553316229658 (the model is very good at accurately predicting true and false casses for both classes)
* Precision: 0.99 (99% predictions of true positive and true negative predictions were correct)
* Recall: 0.95 (95% of true positive cases were caught)

## Summary
The balanced accuracy scores of naive random, SMOTE, undersampling, and SMOTEEN were somewhat good. Balanced Random Forest showed an improved accuracy, and AdaBoost showed the best. All models showed the same precision. The recall of naive random, SMOTE, undersampling, and SMOTEEN were all between 50-69%, whereas random forest and AdaBost were above 80%. Overall, AdaBoost showed the best scores and may be the best model for this data set. 
