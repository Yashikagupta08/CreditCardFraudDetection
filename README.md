Dataset Used: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The following steps were performed:

Exploratory Data Analysis: Data Visualisation was done to see the various coorelations of features and label(transaction was fraud or legal) and to explore the dataset and understand the underlying trends
Preprocessing the dataset: Using under sampling to decrease the legal transaction points to balance the dataset and normalising the features
Divide the dataset into 80% train and 20% test
Tried out different models: Logistic Regression, SVM, Random Forest and XG Boost
Compared the various models via various metrics: accuracy, F1 score, presion and recall & ROC Curve
XG Boost performed well with accuracy: 96% with maximum F1 score
