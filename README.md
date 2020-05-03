# CreditCardFraudDetection
Credit Card Fraud is a common form of theft in the finance sector. Unauthorized and suspicious transaction on bank statements have been an rising issue and these frauds constitute a significant part of the fiscal loss in the banking sector. Detecting a credit card fraud in real time is an uphill task primarily because of the fact that fraud transactions are very few in amount in comparison to the normal transactions. This Notebook follows all basic steps of a Machine Learning Classification lifecycle, and can be used as reference for the few steps involved in construction of a ML pipeline: <br>
1. Loading Data
2. Exploratory Data Analysis: Correlations, Distributions, Outlier detection
3. Feature Scaling: Standard Scaler
4. Data Segmentation
5. Safe Sampling to mitigate class imbalance: Near Miss and SMOTE
6. Model Training: KNN, Logistic Regression, SVM, Logistic-SVM Ensemble with Hard Voting, Tree Based methods, Bagging Classifier, SGD Classifier and Gradient Boosting Methods
7. Predictions and Evaluation
8. Cross Validation: Grid Search CV
9. Model Explanation
10. Forming a sklearn pipeline
11. Serializing the pipeline and dumping it using Joblib
12. Inference Testing

**Objective:** Detecting as many frauds possible and at same time minimizing the number of Non- Frauds categorized as Frauds in the process. <br>
**Challenges:** Class Imbalance, No description available about the features <br>