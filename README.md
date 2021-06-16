# Classification-creditcardFraudDetection
We analyse a PCA transformed creditcard spending data(due to security and privacy) which is highly imbalanced data to treat it and create models on it to predict the fraud transactions.

The data is PCA transformed and did not contain any NULL values. But as we had only 0.17% of fraud vases we had to handle this higly imbalanced data. Following algorithms were tried to handle it:

1. Oversampling
2. Undersampling
3. SMOTE (Synthetic Monirity Oversampling Technique)

After Handling imbalanced data I have tried many models on all data after above techniques and they are mentioned below:

1. Logistic Regression
2. Naive Bayes
3. KNN
4. Decision Tree
5. Random Forest
6. Bagging Techniques
7. Boosting Algorithms - AdaBoost, GradientBoost, Boosted Logistic Regression

Metrics used to compare:

1. Accuracy
2. F1 Score
3. Recall

**Result:** AdaBoost has performed the best in terms of Recall which I have concentrated with 0.8787 score. Other good performing models are GradientBoost, Bagging Algo(Best Overall Accuracy - 99.88 and also a good Recall score) and Boosted LR. Worst performing is KNN.
