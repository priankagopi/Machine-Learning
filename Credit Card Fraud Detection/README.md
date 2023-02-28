# Credit Card Fraud Detection

## Objective

To train a machine learning classification algorithm to detect fraudulemnt transactions.

## Dataset description

The data has various columns from V1 to V28 that represent different attributes. They are mentioned this way to conceal sensitive information. Only 0.17% of the transactions are fraudulent transactions in the above dataset. The seconds that passed between each sale and the first sale in the dataset are contained in the Point' Time field. The sale quantum is the "point"; this point can be used in place of money. The answer variable, called Point Class, has two possible values for fraud and authenticity: 1 and 0, respectively.

## Proposed Model

The proposed system employs various machine learning algorithms, including Decision Trees and Random Forest, to choose the algorithm with the highest accuracy score, F1 score, and precision recall. To account for the imbalanced dataset, methods like SMOTE are used to generate synthetic samples that are similar to the minority class's existing examples in feature space. This approach improves the accuracy of the machine learning algorithms used in the system.


## Evaluation and Results
The proposed system conducted experiments using several baseline classification methods, such as logistic regression, Naive Bayes, K-Nearest Neighbors, Random Forests, and XG-Boost Classifier. However, the dataset had a severe data imbalance, with only a small fraction of transactions being fraudulent. Random Forest Classifier and XG-Boost Classifier showed the most promising results, but the data imbalance caused more false positives. To address this issue, the system utilized oversampling techniques like Random Oversampling and SMOTE, resulting in better performance than the baseline methods. Both data balancing techniques produced similar results, and the XGBoost model outperformed the other algorithm approaches. Overall, the system concluded that XGBoost is a suitable algorithm for detecting anomalies in a heavily skewed dataset.
