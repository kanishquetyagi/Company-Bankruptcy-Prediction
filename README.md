# Company-Bankruptcy-Prediction
The project will predict whether the company is going to be Bankrupt.

Predicting the financial health of companies and firms has become one of the key interests for their owners, creditors and all the stakeholders alike, especially now when huge amounts of financial data can be stored and analysed on computers.

The purpose of such a predictive model which tries to foreseee the bankruptcy is to combine various econometric parameters that can effectively guage the financial state of a company and enable the management to take pre-emptive measures that can potentially help to avoid any financial distress to the company.

In this project we present our analysis of the data at hand as we go on selecting various subsets of the huge feature space available to us. We try to compile and compare each and every result as we step from a niave modelling to a more nuanced and standard one. We have employed some of the most widely used classification algorithms for this project namely:
1. Logistic Regression
2. SVM
3. KNN
4. XGBoost
5. Gaussian Naive Baye's
6. Random Forest

Conclusion:

1. If Accuracy is critical to the use case, then the KNN model should be used along with feature selection, to obtain a 96.6% Accuracy score.
2. If Recall is critical to the use case, then the Gaussian Naive Bayes model should be used with feature selection and SMOTEENN, to obtain an 88.6% Recall value.
3. If overall performance is critical to the use case, then KNN  Model with, feature selection(RandomForest & Isolation forest) and SMOTE ENN can be used to obtain an F1 score of 33%.
    
Challenges-

    • Exploring literature and resources to understand the problem and to find the solution was a little exhaustive.
    • Balancing the trade-off between recall and precision was a challenge.
    • Feature selection and choosing the right technique that fits in with the problem statement were quite challenging.
