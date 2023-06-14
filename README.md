# Machine-Learning_Credit-Card-Approval
Machine learning model for Credit card approval
Built a machine learning classification prediction model whether a credit card application will be approved or rejected based on 
values of feature variables. 
Data set comprises of 25k records and 21 variables. Classes: 121 – Approved, 25007 - Not Approved. the target variable was 
skewed, so used SMOTE (Synthetic Minority Oversampling Technique) to synthetically oversample the data to remove bias. 
While comparing accuracy of models (Logistic Regression, Decision Tree, Random Forest, XGBoost), it turns out logistic regression 
model performs gives best result(99.93) for this problem because of high accuracy and highest precision, recall and F-1 score.
