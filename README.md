## Objective
To distinguish between the presence and absence of cardiac arrhythmia and to classify it in one of the 16 groups based on 12-lead ECG (or Electrocardiography) measurements on patients. Taking the cardiologist as a gold standard the goal is to minimize this difference by means of machine learning tools. Hence, it is a supervised learning problem for classification.

## Methods
KNN, logistic regression with elasticnet regularization, decision tree, bagging, random forest, boosting (GBDT & AdaBoost)

## Result 
Among all these methods, bagging has the best performance with accuracy 85.7%, which outperforms the original VF15 algorithm with only 62% accuracy.
