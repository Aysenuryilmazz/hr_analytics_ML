# hr_analytics_ML

Your client is a large MNC and they have 9 broad verticals across the organisation. One of the problem your client is facing is around identifying the right people for promotion (only for manager position and below) and prepare them in time. Currently the process, they are following is:

They first identify a set of employees based on recommendations/ past performance
Selected employees go through the separate training and evaluation program for each vertical. These programs are based on the required skill of each vertical
At the end of the program, based on various factors such as training performance, KPI completion (only employees with KPIs completed greater than 60% are considered) etc., employee gets promotion
For above mentioned process, the final promotions are only announced after the evaluation and this leads to delay in transition to their new roles. Hence, company needs your help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle.

They have provided multiple attributes around Employee's past and current performance along with demographics. Now, The task is to predict whether a potential promotee at checkpoint in the test set will be promoted or not after the evaluation process.

The evaluation metric for this competition is F1 Score.

In order to solve this problem, I applied 13 different classification algorithms:
---
- Decision Tree Classifier
- Naive Bayes
- SVM
- k-NN
- Logistic Regression

Also, some ensemble models:
- Random Forest
- Bagging Meta Estimator
- Extra Trees 
- AdaBoost
- CatBoost
- LightGBM
- Gradient Boosting
- XGBoost

Best three models are(almost same f1-score): XGBoost, GradientBoosting and ExtraTrees.  

After that; t-test is applied to these three models to determine the "best one".

 
