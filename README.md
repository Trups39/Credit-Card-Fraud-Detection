# Credit-Card-Fraud-Detection

## Model Performance Breakdown

### 🔗 DBSCAN
- **Recall:** Achieved the highest recall, flagging **92% of frauds** 🚨.
- **Challenges:**
  - **Confusion Matrix:** Most transactions were flagged as fraud.
  - **Imbalance Issue:** Fraud accounts for only **0.2% of transactions**, leading to:
    - High **cost 💸** for investigation.
    - **Significant inconvenience** for customers.
- **Conclusion:** DBSCAN, while effective in recall, is **impractical for fraud detection** due to excessive **false positives**.

### 🔄 One-Class SVM and Isolation Forest
- **Recall:** Captured around **87% of frauds** 🔍 with **fewer false positives**.
- **Key Strengths:**
  - **Better balance** between identifying fraud and minimizing false positives.
  - **More practical** for real-world applications as it reduces unnecessary disruptions.
  
- **Conclusion:** **One-Class SVM and Isolation Forest** provide a **more balanced solution** for fraud detection and are more **suitable for real-world applications** ✅.

## Key Takeaways

- **High recall** is critical in fraud detection, but it often comes at the cost of **low precision**.
- **DBSCAN** achieves exceptional recall but is **impractical** due to excessive false positives.
- **One-Class SVM and Isolation Forest** strike a better balance, making them **more suitable for real-world fraud detection** scenarios.

## Technologies Used
- **DBSCAN**
- **One-Class SVM**
- **Isolation Forest**
- **Scikit-learn**
- **Pandas**



