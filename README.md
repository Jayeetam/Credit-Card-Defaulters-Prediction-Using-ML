# Credit-Card-Defaulters-Prediction-Using-ML

## Objective:
Due to cashless transaction nowadays almost every people use ATM card and credit card for transaction, so fraud can also be increased. Billions of dollars of loss are caused everyday by fraudulent credit card transactions. The design of efficient fraud detection algorithms are key for reducing those losses and more and more algorithms rely on machine learning techniques to assist fraud investigators.

## Problem Statement:
Credit card frauds are increasing heavily and because of the fraud financial losses are increasing drastically. Every year due to fraud billions of amounts lost. The objective of the project is to implement a model using machine learning algorithm to detect credit card fraud with respect to time and amount of transaction. The Credit Card Fraud Detection Problem includes modeling past credit card transactions with the knowledge of the ones that turned out to be a fraud. This model is then used to identify whether a new transaction is fraudulent or not. Our aim here is to detect 100% of the fraudulent transactions while minimizing the incorrect fraud classifications.
Understanding and Defining Fraud
Credit card fraud is any dishonest act and behavior to obtain information without the proper authorization from the account holder for financial gain. Among different ways of frauds, Skimming is the most common one, which is the way of duplicating of information located on the magnetic strip of the card. Apart from this, the other ways are:
•	Manipulation/alteration of genuine cards
•	Creation of counterfeit cards
•	Stolen/lost credit cards
•	Fraudulent telemarketing

## Project Pipeline
The project pipeline can be briefly summarized in the following four steps:
•	Data Understanding: Here, we need to load the data and understand the features present in it. This would help us choose the features that we will need for your final model.
•	Exploratory data analytics (EDA): Normally, in this step, we need to perform univariate and bivariate analyses of the data, followed by feature transformations, if necessary. For the current data set, because Gaussian variables are used, we do not need to perform Z-scaling. However, you can check if there is any skewness in the data and try to mitigate it, as it might cause problems during the model-building phase.
•	Train/Test Split: Now we are familiar with the train/test split, which we can perform in order to check the performance of our models with unseen data. Here, for validation, we can use the k-fold cross-validation method. We need to choose an appropriate k value so that the minority class is correctly represented in the test folds.
•	Model-Building/Hyperparameter Tuning: This is the final step at which we can try different models and fine-tune their hyperparameters until we get the desired level of performance on the given dataset. We should try and see if we get a better model by the various sampling techniques.
•	Model Evaluation: We need to evaluate the models using appropriate evaluation metrics. Note that since the data is imbalanced it is is more important to identify which are fraudulent transactions accurately than the non-fraudulent. We need to choose an appropriate evaluation metric which reflects this business goal.


In Implementation, three behavior of cardholder are taken into consideration. 1) Low spending behavior 2) Medium spending behavior 3) High spending behavior Different cardholders has their different spending behavior (low, medium, high).Low spending behavior of any cardholder means cardholder spend low amount (L), medium spending behavior of any cardholder means cardholder spend medium amount (M), high spending behavior of any cardholder means cardholder spend high amount (H). These profiles are observation symbols. The mechanism requires at least 10 transactions to determine accurately the transaction as fraud or not. 
