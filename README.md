# Credit-Card-Fraud-Detection
Model Performance Breakdown
🔗 DBSCAN
Achieved the highest recall, flagging 92% of frauds 🚨, which is impressive.
However, the confusion matrix reveals that most transactions were flagged as fraud.
Given that fraud accounts for only 0.2% of transactions, this leads to:
High cost 💸
Significant inconvenience for customers
Conclusion: This makes DBSCAN an impractical solution for fraud detection.
🔄 One-Class SVM and Isolation Forest
Captured around 87% of frauds 🔍 while predicting fewer overall frauds.
Struck a better balance between:
Identifying fraud
Minimizing false positives
Result: A more practical approach for fraud detection with fewer unnecessary disruptions ✅.
Key Takeaways
High recall is important for fraud detection, but it often comes at the cost of low precision.
DBSCAN achieves exceptional recall but is impractical due to excessive false positives.
One-Class SVM and Isolation Forest provide a better balance, making them more suitable for real-world applications.
