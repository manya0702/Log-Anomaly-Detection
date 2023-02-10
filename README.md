# LOG ANOMALY DETECTION

# PROBLEM STATEMENT

In computing, logging is the act of keeping a log of events that occur in a computer system, such as problems, errors or just information on current operations. These events may occur in the operating system or in other software. A message or log entry is recorded for each such event. Log Anomaly Detection is simply detecting anomalies in logs deposited by softwares using Machine Learning.

In software engineering, anomaly can be defined as occurrence of rare or unexpected events that does not fit into the normal patterns and hence a suspicious one. 

Examples could be:

* Unexpected failure of a service
* Sudden increase/decrease of user activity in a customer facing system
* Reasons for these anomalies could be different, like:
* Entry of unperceived inputs to the system
* System running out of memory

# OBJECTIVE : To train a ML model on the dataset that can predict whether a given log in testing data is "abnormal" or "normal".

# DATASET

The dataset contains 41,52,659 entries in the training dataset and 5,95,300 entries in the test dataset.

Columns: Unique ID , Log and Label

# APPROACH

The following approaches were applied on the dataset
1. NLP
2. Decision Tree Algorithms: lgbm, rf, xgboost, extra_tree, xgb_limitdepth and lrl1
3. Naive Bayes 

Naive Bayes provided the best results. Its classification reort is given below -

<img width="284" alt="image" src="https://user-images.githubusercontent.com/72210577/218019973-12c92742-cab6-40a7-922e-9025e5a18ac9.png">

Here 0 is the class representing abnormal logs and 1 is the class representing normal logs.


