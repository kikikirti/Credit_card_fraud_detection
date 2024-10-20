# Credit Card Fraud Detection
This project predicts fraudulent credit card transactions using machine learning techniques.

# Data Source
The data was obtained from a credit card transaction dataset available on [GeeksForGeeks](https://media.geeksforgeeks.org/wp-content/uploads/20240904104950/creditcard.csv).

# Data Exploration
The dataset contains 284,807 rows (transactions) and 31 columns (features). Here's an overview:

* **Time**: Seconds elapsed between the transaction and the first transaction in the dataset.
* **V1-V28**: Anonymized features resulting from a PCA transformation.
* **Amount**: The transaction amount.
* **Class**: Whether the transaction is fraudulent (1.0) or not (0.0). (Target variable)
The dataset is highly imbalanced, with only 0.17% of the transactions being fraudulent.

# Handling Imbalanced Data
Since fraudulent transactions are rare, the class imbalance was a significant challenge. However, for the initial model, no balancing techniques were applied. Future work may involve handling the imbalance using methods like oversampling or SMOTE.

 #Model Training
Two machine learning models were used to predict fraudulent transactions:

* **Random Forest Classifier**: An ensemble model that uses multiple decision trees to improve prediction accuracy.
* **Evaluation Metrics**: Various metrics such as accuracy, precision, recall, and F1-score were used to assess model performance.

# Evaluation
Here are the evaluation results for the Random Forest Classifier:

* Accuracy: 99.95%
* Precision: 96.15%
* Recall: 76.53%
* F1-Score: 85.27%
  
